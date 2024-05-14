---
wrapper_template: _layouts/docs.html
context:
  title: Radio panel | Accessibility
  status: draft
---
From an accessibility standpoint, Radio Panels should behave identically to a standard group of radio buttons.

* Assistive technologies should announce the Radio Panels correctly
* Assistive technologies should operate the Radio Panel correctly
* ARIA grouping should be applied to ensure the Panels in the Radio Panel component are seen as a form group by assistive technology
* The Radio Panel should behave like a radio button group but with an extra layer of styling on top
* Alternative text should be used to describe the icon or image if it adds context to the selection the user is making

Read also:

* [ARIA17: Using grouping roles to identify related form controls](http://www.w3.org/TR/WCAG20-TECHS/ARIA17.html)
* [WAI-ARIA Authoring Practices - Radio Buttons](https://www.w3.org/TR/wai-aria-practices-1.1/#radiobutton)
