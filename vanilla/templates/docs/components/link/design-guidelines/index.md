---
wrapper_template: _layouts/docs.html
context:
  title: Link | Design Guidelines
  status: braindump
---
# Overview

The main purpose for links is to navigate users to relevant content. However, in some cases, they are also used as minor actions in a page, such as show less or show more content. They can appear within a copy of the page or as call-to-actions on following relevant content. 

# Anatomy

![](/vanilla/templates/static/images/image12.png)

The anatomy above shows three ways to use hyperlinks for different purposes.

1. Hyperlink for navigational purposes - with a direction chevron.
2. Hyperlink embedded in a sentence or copy doc. 
3. Command link for minor actions within a page. 

# General Usage

## When to Use

Use links when:

* **Navigating** to a new page or within the page.
* **Reveal** extended content. 

## When not to use

* Links are **not** primary actions. Use buttons for primary actions, instead. 

# Variants

<table>
  <tr>
   <td><strong>Variant</strong>
   </td>
   <td><strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td rowspan="3" >Command links
   </td>
   <td rowspan="3" >Action links for the purpose of minor actions such as truncated content or previews of images and form fields.
   </td>
  </tr>
  <tr>
  </tr>
  <tr>
  </tr>
  <tr>
   <td>Hyperlink
   </td>
   <td>Hyperlinks for navigational purposes to a different tab within the application or website or external. 
   </td>
  </tr>
</table>

# Variant A - Command links

## Definition

Command links are texts or links that lead to actions, instead of routing a user to a new page. The usage rule below reduces confusion for how and when we can explicitly use command links as a substitute for buttons.  

## The look



![](/vanilla/templates/static/images/image8.png)

## Usage

When a component has a default size but the content is too long. 

To reduce confusion with hyperlinks, use **words that explicitly lead to an action**. Try to start with a verb if possible. 

### When to use

Use this variant when:

* **An action that has minor consequences** - actions that are not the main focus of the page and likely won’t affect changes in the database *(nngroup, [[3](https://www.nngroup.com/articles/command-links/)])*.  \
  For example:
       *Show/hide sensitive content such as private key or password.*
       Bringing the user back to the top
       *Showing an advanced field in a form*
       Previewing images
* **Overflow text** - when the text is too long that it overflows a button, use command links as an alternative. 

### When not to use

Do not use this variant when this action is a primary action. Use buttons for primary action, instead.

### Usage advices

* Use sentence-style capitalisation as a convention when there are more than one word in the command.
* Have a way to go back to the previous state.
* Prioritise the link options according to the users’ expectation.
* Provide hover state where applicable

## Behaviours

### Revealing overflowing content

![](/vanilla/templates/static/images/image9.png)

### Hover state

On hover, the hyperlink will show an underline, indicating that it is clickable. 

![alt_text](/vanilla/templates/static/images/image5.png "image_tooltip")

### Revealing sensitive information as a secondary action

![alt_text](/vanilla/templates/static/images/image7.png "image_tooltip")

## Examples

[Example on snapcraft first snap flow](https://snapcraft.io/#c)

![alt_text](/vanilla/templates/static/images/image11.png "image_tooltip")

[Snapcraft list of users by distro for single snap:](https://snapcraft.io/riot-web)



![alt_text](/vanilla/templates/static/images/image1.png "image_tooltip")

[Example of MAAS change password:](http://karura.internal:5240/MAAS/r/account/prefs/details)

![alt_text](/vanilla/templates/static/images/image16.png "image_tooltip")

# Variant B - Hyperlink

## Definition

The purpose of this variant is to use links for navigation within the same application or outside of the application. For instance, redirecting to a different tab of the website or application or external link.

## The look

![alt_text](/vanilla/templates/static/images/image4.png "image_tooltip")

## Usage

When you want to use command links to navigate internally, the underline is not necessary. A chevron is recommended next to the link to indicate navigation. However, if the link is part of the sentence, the chevron is not needed. 

### When to use

Use this variant when:

* Use links for navigation within the application.
* Use links for external redirection.
* Hyperlinks can be part of a sentence or a paragraph.

### When not to use

Do **not** use this variant when this action is a primary action. Use buttons for primary action, instead.

### Usage advices

* Use sentence-style capitalisation as a convention when there are more than one word in the command.
* Consider voice over mode for accessibility.
* Avoid using the word ‘link’ or ‘click here’. 
* Prioritise the options according to the users’ expectation.
* Consider providing hover state

## Behaviours

### Navigate to a new tab within the application

![alt_text](/vanilla/templates/static/images/image13.png "image_tooltip")

### Hover state

![alt_text](/vanilla/templates/static/images/image2.png "image_tooltip")



![alt_text](/vanilla/templates/static/images/image6.png "image_tooltip")

### Same page navigation

![alt_text](/vanilla/templates/static/images/image3.png "image_tooltip")

## Examples

Example from MAAS machine summary page. These command links route the users to a different tab within the same application.

![alt_text](/vanilla/templates/static/images/image15.png "image_tooltip")

MAAS back navigation

![alt_text](/vanilla/templates/static/images/image10.png "image_tooltip")

[Example from snapcraft](https://snapcraft.io/install/riot-web/centos)

![alt_text](/vanilla/templates/static/images/image14.png "image_tooltip")
