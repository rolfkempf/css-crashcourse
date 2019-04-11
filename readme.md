# CSS-Basics

This is a very basic crashcourse in CSS for developers.

## Selectors

- elements, classes, ids
- pseudo-elements (::before, ::after)
- attributes


## Specificity

  - **element**/pseudo-elements < **class**/attribute/pseudo-classes < **id** < **inline-style**
  - file < style-element < style-attribute
  - !important
  - tricks (selector-paths, last rule wins)
  - ```html body div h1``` < ```.my-headline```
  - ```div div div div div div div div div``` < ```.my-class```
  - ```div div div div div div div div div div``` = ```.my-class```
  - ```div div div div div div div div div div div``` > ```.my-class```
  - ```#x#x#x```

## Using CSS

- Box-Model: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model
- Positioning: https://developer.mozilla.org/en-US/docs/Web/CSS/position
- Stacking (z-index): https://developer.mozilla.org/en-US/docs/Web/CSS/z-index
- Float: https://developer.mozilla.org/en-US/docs/Web/CSS/float
- Display: https://css-tricks.com/almanac/properties/d/display/
- Flexbox: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox, https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- Grid: https://css-tricks.com/snippets/css/complete-guide-grid/

## Using Frameworks

- Bootstrap
- Tailwind

### Links

- https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
- https://specificity.keegan.st/
- https://caniuse.com
- 