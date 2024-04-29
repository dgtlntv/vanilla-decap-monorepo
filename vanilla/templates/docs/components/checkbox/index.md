---
wrapper_template: '_layouts/docs.html'
context:
  title: Checkbox | Implementation
---

## Checkbox

Use the checkbox component to select one or more options. To provide fully featured Vanilla style and behaviour of the checkbox a specific markup structure is needed around the checkbox input (see example below).

To disable the checkbox component, add the `disabled` attribute to the respective `<input type='checkbox'>` element.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/checkbox/" class="js-example">
View example of the checkbox components
</a></div>

### Inline checkbox

When placing the checkbox component in padded containers (table cells, some list items), use the `.p-checkbox--inline` variant. It ensures the checkbox and the label text are properly aligned with other inline text.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/checkbox-inline/" class="js-example">
View example of the inline checkbox components
</a></div>

### Heading checkbox

To use checkbox component in headings use the `.p-checkbox--heading` variant of the component to make sure the checkbox and the label text are properly aligned.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/checkbox-heading/" class="js-example">
View example of the heading checkbox components
</a></div>

### Indeterminate state checkbox

When a checkbox requires a state between checked and unchecked, `checkbox.indeterminate = true;` can be set via JavaScript, which will cause the checkbox appear in an "indeterminate" state.

In cases when JavaScript can't be used for that, set `aria-checked="mixed"` on checkbox to show "indeterminate" state. Please note that it will only change the visual look of the checkbox, it will not affect its state available to the browser via JavaScript.

<div class="embedded-example"><a href="/docs/examples/patterns/forms/checkbox-indeterminate/" class="js-example">
View example of the indeterminate checkbox component
</a></div>
