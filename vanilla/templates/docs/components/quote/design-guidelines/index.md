---
wrapper_template: _layouts/docs.html
context:
  title: Quote | Design Guidelines
  status: braindump
---
## Overview
We use the quote component to highlight text content in a visually prominent manner.
## Usage patterns
### Pull quotes
Pull quotes repeat content from the page to draw attention to key phrases. These should not include a citation.
### Reference quotes
Reference quotes display content from another source. For example:
Customer testimonials support content in the proximity of the quote. Always cite an author, rarely is a link relevant.
Excerpts from external documentation bring key points from elsewhere to the page. Always cite the source document. Links are optional, often used in documentation contexts but rarely in marketing.
## Variants
### Small
`small` is appropriate for larger amounts of text:
<blockquote class="p-pull-quote--small">
<p class="p-pull-quote__quote">This is a very long statement from a happy customer. We probably would prefer they were more concise, but in the interest of honest accuracy we will include the entirety of the points they made.</p>
<span class="p-pull-quote__citation">Someone Important, Big Impressive Firm</span>
</blockquote>
### Large
`large` should be used only for small amounts of text when visual prominence is desired:
<blockquote class="p-pull-quote--large">
<p class="p-pull-quote__quote">Don't forget to read this key sentence.</p>
</blockquote>
## Properties
### Image (optional)
Images can be included to support recognition of citation sources. Size is not prescribed, but should be kept legibly small to avoid distracting from the text content.
Images should not be used in pull quotes, which ought to reflect only text from nearby on the page.
> HTML implementation note: add the `has-image` property to the `blockquote` container *and* `p-pull-quote__image` to the `img` element.
<blockquote class="p-pull-quote has-image">
<img class="p-pull-quote__image" src="https://assets.ubuntu.com/v1/c7881d6c-spiculelogo-spacingx2-01.svg" alt="">
<p class="p-pull-quote__quote">Using the modelling ethos brought by Juju allows me to quickly run big data applications in a multitude of places. Be it locally on my laptop, on bare metal or in the Cloud, Juju lets me reuse the same models and code without changing any aspects of my deployment.</p>
<span class="p-pull-quote__citation">Tom Barber, CTO, Spicule LTD</span>
</blockquote>
