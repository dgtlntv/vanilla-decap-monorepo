---
wrapper_template: '_layouts/docs.html'
context:
  title: Accordion | React
---

The sidebar accordion, used in listing pages or as navigation, can hold multiple navigation items or to be used as a filter for content.

# Props

| name                 | DESCRIPTION                                                                                                                                                                                           | DEFAULT |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| className            | Optional classes applied to the parent element. `string`                                                                                                                                              |         |
| expanded             | An optional value to set the expanded section. The value must match a section key. This value will only set the expanded section on first render if externallyControlled is not set to true. `string` |         |
| externallyControlled | Whether the expanded section will be controlled via external state. `boolean`                                                                                                                         |         |
| onExpandedChange     | Optional function that is called when the expanded section is changed. The function is provided the section title or null. `(id: string, title: string) => void`                                      |         |
| sections\*           | An array of sections and content. `Section[]`                                                                                                                                                         |         |
| titleElement         | Optional string describing heading element that should be used for the section titles. `"h2"` `"h3"` `"h4"` `"h5"` `"h6"`                                                                             |         |

## Default

<iframe
  src="https://canonical.github.io/react-components/iframe.html?args=&id=accordion--default-story&viewMode=story"
  width="800"
  height="260"
></iframe>

## External state

The expanded accordion section can be controlled by external state.

<iframe
  src="https://canonical.github.io/react-components/iframe.html?args=&id=accordion--external-state&viewMode=story"
  width="800"
  height="260"
></iframe>

## Headings

`titleElement` prop can be used to define heading element for section titles.

<iframe
  src="https://canonical.github.io/react-components/iframe.html?args=&id=accordion--headings&viewMode=story"
  width="800"
  height="260"
></iframe>
