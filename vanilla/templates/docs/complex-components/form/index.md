---
wrapper_template: '_layouts/docs.html'
context:
  title: Form | Implementation
---

## Inline

By applying the class `.p-form--inline` and wrapping any form control in `.p-form__group` you can change the layout style of any form to be inline.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/form-inline/" class="js-example">
View examples of form inline patterns
</a></div>

## Stacked

By applying the class `.p-form--stacked` and wrapping any form control in `.p-form__group` you can change the layout style of any form to be stacked.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/form-stacked/" class="js-example">
View examples of form stacked patterns
</a></div>

## Disabled

Adding the `disabled` attribute to an input will prevent user interaction.

<div class="p-notification--information">
  <p class="p-notification__content">
    <span class="p-notification__title">Note:</span>
    <span class="p-notification__message">All disabled inputs have an opacity of <code>0.5</code> and <code>not-allowed</code> cursor on hover.</span>
  </p>
</div>

<div class="embedded-example"><a href="/docs/examples/base/forms/disabled-input/" class="js-example">
View example of a disabled input
</a></div>

## Help text

Supplementary help text can be provided for the form fields by adding an element with `.p-form-help-text` class name. If the help text follows a checkbox or radio button use an additional `is-tick-element` class name to align help text with the label.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/form-help-text/" class="js-example">
View example of a form fields with help text
</a></div>

## Validation

To use form validation feedback - which includes feedback messages, icons and border colours - wrap individual input elements in a `p-form-validation` and additionally apply the `.is-error`, `.is-caution` or `.is-success` to the wrapper as appropriate.

If your form uses select elements then you will additionally need to wrap only the `<select>` element in a wrapper with the class `p-form-validation__select-wrapper` to mitigate some of the quirks of this specific HTML element across browsers.

Descriptive text relating to the element's validation status should use the class `p-form-validation__message`.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/form-validation/" class="js-example">
View example of form validation patterns
</a></div>

## Required

Apply the class `.is-required` to mandatory input fields. You should also add a legend to the form to be explicit about the meaning of the asterisk.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/forms-required/" class="js-example">
View example of an input required element
</a></div>

## Dense form elements

In contexts where vertical space is limited, e.g. inside a table row, you might prefer form elements with reduced vertical padding. Add class `.is-dense` to achieve that:

<div class="embedded-example"><a href="/docs/examples/patterns/forms/dense/" class="js-example">
View example of the dense form elements
</a></div>

## Password toggle

When using a password field, use this pattern to allow the user to toggle the password visibility.

<div class="p-notification--information is-inline">
  <div class="p-notification__content">
    <h5 class="p-notification__title">Note:</h5>
    <p class="p-notification__message">Do not use this pattern in inline forms</p>
  </div>
</div>

<div class="embedded-example"><a href="/docs/examples/patterns/forms/password-toggle/" class="js-example">
View example of the password toggle
</a></div>

## Dark theme

By default the form elements are displayed in the light theme. To display them in the dark theme, add the class `.is-dark` to the input elements.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/forms-dark/" class="js-example">
View example of the dark form elements
</a></div>

<div class="embedded-example"><a href="/docs/examples/patterns/forms/form-validation-dark/" class="js-example">
View example of the dark form elements
</a></div>

## Import

To import just this base element into your project, copy the snippet below and include it in your main Sass file.

<pre><code>@import 'patterns_forms';</code></pre>

To add form help text or validation into your project, copy either or both snippets below and include it in your main Sass file.

```scss
@import 'patterns_form-help-text';
```

```scss
@import 'patterns_form-validation';
```

For more information see [Customising Vanilla](/docs/customising-vanilla/) in your projects, which includes overrides and importing instructions.

## React

You can use forms in React by installing our react-component library and importing `Form` and `Input` component.

[See the documentation for our React `Form` component](https://canonical.github.io/react-components/?path=/docs/form--default-story#form)

[See the documentation for our React `Input` component](https://canonical.github.io/react-components/?path=/docs/input--text-input#input)
