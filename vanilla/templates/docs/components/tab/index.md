---
wrapper_template: _layouts/docs.html
context:
  title: Tab | Implementation
  status: braindump
---
## What is this

Tabs are a navigation item used to group content of similar hierarchy on the same page.

###### Breakdown

Each tab item is made of three components:

![](/vanilla/templates/static/images/tab-3.png)

1. The tab label
2. The container
3. The bottom border, for highlighting state change.

**States**

There are different tab states available:

![](/vanilla/templates/static/images/tabs-2.png)

1. Default
2. Selected
3. Disabled

**When to use it**

Tabs are used when users need to navigate between content in the same page.

[](https://canonical.github.io/react-components/?path=/docs/tabs--default-story#tabs)

**Do’s and Don'ts**[](https://canonical.github.io/react-components/?path=/docs/tabs--default-story#tabs)[](https://canonical.github.io/react-components/?path=/docs/tabs--default-story#tabs)[](https://canonical.github.io/react-components/?path=/docs/tabs--default-story#tabs)

1. Use tabs to switch between items in the same context. Do not use tabs to navigate to different pages, and external links.
2. Prioritise tabs by importance and frequency of use. Do not add tabs arbitrarily.
3. Write clear and concise tab labels (1-2 words). Don’t give tab labels vague and complex names that are hard to understand at first glance.
