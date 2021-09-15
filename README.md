# Reusable HTML Components
 This repository was made to examine an issue with utilizing Shadow DOMs to create HTML components.
 In the given case, Shadow DOMs were intended to prevent the header & footer components' from overwriting each others' custom CSS.

For things to go as expected, social media links should be showing in the bottom right, as you can see in the picture, below:
![howIPictured](https://user-images.githubusercontent.com/11304487/132790675-5d90021e-8fe7-4594-9537-3c94cd61ff31.jpg)

However, once a Shadow DOM is introduced, they disappear, as illustrated in my original `/index.html`
![howItsGoing](https://user-images.githubusercontent.com/11304487/132790680-e40b8d5a-f6a0-4755-8548-132ffa0e20f5.jpg)



# Solutions
Handling these shadow DOMs came down to 3 options(you can just read about them in Kris's article, cited under [Sources](#SOURCES))
- Option #1 can be found in [`optionNumberOne.html`](/optionNumberOne.html)
- Option #2 can be found in [`optionNumberTwo.html`](/optionNumberTwo.html)
- Option #3 can be found in [`optionNumberThree.html`](/optionNumberThree.html)

# SOURCES
This entire repository is owed to the wonderful article that taught me everything, here:
[Resuable-html-components](https://www.freecodecamp.org/news/reusable-html-components-how-to-reuse-a-header-and-footer-on-a-website/),
by [Kris Koishigawa](https://twitter.com/kriskoishigawa)
