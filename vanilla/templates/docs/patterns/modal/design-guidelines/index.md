---
wrapper_template: _layouts/docs.html
context:
  title: Modal | Design Guidelines
  status: braindump
---
# Overview

The modal component is used to overlay an area of the screen with a prompt, dialogue or interaction and prevents users from interacting with content outside of it until it’s closed. 

# General Usage

## When to use

* To prevent or correct critical errors;
* To request information critical to continuing the current process;
* To ask information that could significantly lessen users’ work or effort;
* To reveal relevant information or contextual information;
* To expand media assets.

## How to use

* The modal title should tell users what the modal is about;
* Try to match the primary button text with the modal window title to make it easier for users to understand the context;
* Be mindful of the modal’s length, avoiding the use of a scrollbar - if it has a lot of content consider a regular page or other alternatives instead.

## When not to use

* For information that is not related to the current page/flow;
* To interrupt processes. I.e. checkout flows;
* When the user requires additional information unavailable in the modal;
* When the user can proceed with their flow _without _the interruption. Use only when a modal is absolutely necessary.
* To show error, wait, or success states - use the notifications component instead;
* To show contextual information that can be displayed in a panel or less disruptive components.

## Behaviour

### Opening the modal

A modal can be opened by clicking:

* Call-to-action buttons
* Text links
* Media assets such as images and videos
* A modal can be triggered by a system event, for example “Do you really wish to leave this page? Your changes will be lost.”

### Active

When a modal is active, the main content is disabled until the user interacts with the modal dialogue or the close button (if available). 

A  scrim will appear between the main content and the modal to convey that the rest of the page is disabled and so the focus is on the modal

### Close

A modal can be dismissed by:

* Clicking the close button (if available)
* Interacting with the dialogue (if available)
* Pressing the keyboard Escape key if the modal can be ignored.

# Variants

## Overview

<table>
  <tr>
   <td>Variants
   </td>
   <td>Description
   </td>
   <td>Configurations
   </td>
  </tr>
  <tr>
   <td>A) Content view
   </td>
   <td>To read text or view media assets.
<p>
Disables the main content until the user clicks on the close icon to return to the underlying page.
   </td>
   <td>Title
<p>
No title
   </td>
  </tr>
  <tr>
   <td>B) Dialogue
   </td>
   <td>Requires user interaction. \
Disables the main content until the user interacts with the modal dialogue or the close button (if available).
   </td>
   <td>Close button
<p>
No close button
   </td>
  </tr>
</table>

## Variant A - Content view

### Definition

Use the content view modal to reveal relevant or contextual information or to expand images or view media assets.

### Configurations

#### Title

##### Desktop

![](/vanilla/templates/static/images/image5.png)

##### Mobile

#### No title

##### Desktop

![](/vanilla/templates/static/images/image2.png)

![](/vanilla/templates/static/images/variant-a-desk-2.png)

##### Mobile

## Variant B - Dialogue

### Definition

Use the dialogue modal to request information or actions from the user.

### Configurations

#### No close button

To close this configuration, the user must select an action. 

##### Desktop

![](/vanilla/templates/static/images/v-b-d-1.png)

##### Mobile

#### Close button

When displaying the close button, make sure it is clear what it will do to avoid ambiguity between close and the action button(s). To clarify the close button intent, consider having a tooltip confirming the action.

##### Desktop

![](/vanilla/templates/static/images/v-b-d-2.png)

##### Mobile

# References

* [UX Planet - Best Practices For Modal Window Design](https://uxplanet.org/best-practices-for-modal-window-design-627f7aba57f1) (Nick Babich, 2021)
* [NN/g - Modal & Nonmodal Dialogs: When (& When Not) to Use Them](https://www.nngroup.com/articles/modal-nonmodal-dialog/) (Therese Fessenden, 2017)
* [Cancel vs Close: Design to Distinguish the Difference](https://www.nngroup.com/articles/cancel-vs-close/) (Aurora Harley, 2019)
* [Material Design - Dialogs component](https://material.io/components/dialogs) (Google)
* [Carbon Design System - Modal component](https://www.carbondesignsystem.com/components/modal/usage/) (IBM)
