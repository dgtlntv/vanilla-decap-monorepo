---
wrapper_template: _layouts/docs.html
context:
  title: Accordion | Design Guidelines
  status: braindump
---
# Overview

The accordion is a vertically stacked content area which can be collapsed and expanded to reveal or hide its contents. An accordion can be opened or closed independently of its surrounding counterparts (i.e: multiple accordions can be open at the same time). When used right, accordions can help browse different pieces of related content in a more efficient way. Be wary that they can also hide content from users and are not suitable when a user is meant to read all of the page content.

# Anatomy

![Anatomy of "Accordion H2 closed"](/vanilla/templates/static/images/image9.png "Anatomy of \"Accordion H2 closed\"")

1. Chevron
2. Heading (can be H2-H5 or Paragraph styling depending on the context of the page)
3. Divider

# Usage

### When to use

Accordions are helpful in the following cases:

* Have an overview of content sections related to each other
* Allowing the user to show and hide different sections of the content
* See information at a glance which could be on different pages otherwise

### When not to use

It’s not recommended to use accordions when the page content must be seen by a user, as they hide content and it’s not certain that all users understand how they work. Consider restructuring your content without an accordion first or alternatively use anchor links in the beginning of the page which redirect the user to specific sections of the page. We do not recommend nesting accordions within accordions, as it hinders discoverability enormously.

### Behaviour

All of the following are optional. Pick what makes sense for your component. If behaviour applies to the whole component and not just the variant, bring this section above the variants table. 

#### Idle

By default accordions are closed.  \
 \
Note: Accordion headers should not include any links or other interactive elements as that could interfere with the accordion interactions for expanding and collapsing.

![closed accordion](/vanilla/templates/static/images/image5.png "closed accordion")

#### Hover

On hover the background of the header will change to a light gray. The whole heading row can be hovered/ is clickable, not only the chevron icon. This ensures that users can interact with accordions with higher confidence.

![on hover](/vanilla/templates/static/images/image8.png "on hover")

#### Click/Interaction

The accordion expands vertically and the chevron transforms from pointing right to downwards. Chevron animations help guide users following the accordion states (closed or open).

![Click/Interaction](/vanilla/templates/static/images/image14.png "Click/Interaction")

### Examples

Accordions are used internally in Canonical’s 360 Review platform under your Manager Review. Potential products can benefit from accordions in FAQ sections or similarly as well.

# Questions to ask yourself before using this component

* Can I use the tabs instead? 

  * Do users need to switch quickly between sections?

    * Tabs might be better suited than accordions.
  * Is there a concern for horizontal space?

    * If yes, consider accordions or alternatives options.
  * Am I nesting critical information needed for the user in an accordion?

    * If yes, consider using tabs or alternative options
* Am I choosing the right heading size for the accordions?

  * Consider your surrounding content hierarchy to decide which heading suits best for your accordion
* Are page loading times sensible? Make sure not too much content is nested within the accordions as that delays the page loading times considerably.
* Do users need to switch quickly between sections?

  * If yes, use tabs.
* Do users need to look at multiple sections at a time?

  * If yes, use accordions
* Is there enough horizontal space to use tabs instead?

  * Accordions scale up vertically whereas tabs horizontally. If there is limited horizontal space, accordions might be more suitable.

# References

Most design systems offer accordions, though its usage differs across them.

**Carbon**

* Accordion:  Chevrons on the right or left side pointing up and down based on whether the section is closed or open. The positions of the chevrons are modular and can be changed within the component. They do discourage using the left-side chevrons though due to UI alignment imperfections.

**GOV.UK**

* Accordion: Their current component is experimental as more research is needed to validate it. GOV.UK also offers a button to toggle showing and hiding all accordion sections at once. Chevrons are placed at the left side but show up and down to indicate its state.
* [Accordion component research updates](https://github.com/alphagov/govuk-design-system-backlog/issues/1#issuecomment-995675898) (GOV.UK, 2021)
* [Accordions Are Not Always the Answer for Complex Content on Desktops](https://www.nngroup.com/articles/accordions-complex-content/) (Nielsen Norman Group, 2014)
* [Designing The Perfect Accordion](https://www.smashingmagazine.com/2017/06/designing-perfect-accordion-checklist/) (Smashing Magazine, 2017)
