# Reusable HTML Components
 This repository mainly exists to consult help on an issue I'm having with understanding how to use Shadow DOMs, at the moment.
 The issue looks pretty simple.
Social media links should be showing in the bottom right, as you can see in `indexWithoutShadowDOM.html`
![howIPictured](https://user-images.githubusercontent.com/11304487/132790675-5d90021e-8fe7-4594-9537-3c94cd61ff31.jpg)

However, once a Shadow DOM is introduced, they disappear, as illustrated in my original `/index.html`
![howItsGoing](https://user-images.githubusercontent.com/11304487/132790680-e40b8d5a-f6a0-4755-8548-132ffa0e20f5.jpg)

It's apparent what's going on here is that the second page isn't getting its link to font-awesome applied to the footer Shadow DOM.

Now, reading this article: https://www.freecodecamp.org/news/reusable-html-components-how-to-reuse-a-header-and-footer-on-a-website/
I should be able to use Shadow DOMs to prevent each reusable component from spreading its CSS styles to other elements, 
but they seem to go beyond keeping their styles to themselves, and start blocking outside styles, as well.

I realize the easy workaround of just re-linking the appropriate CSS files in each reusable component, 
but something feels a bit off about "end up with three links to the same CSS file across a page and its two injected components".

Any ideas on a good fix?
