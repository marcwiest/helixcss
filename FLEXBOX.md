
Flexbox Update: [https://css-tricks.com/using-flexbox/](https://css-tricks.com/using-flexbox/)

# Fleaxbox Container

### flexbox
__display:__ flex | inline-flex;

### behavior
__flex-direction:__ row | row-reverse | column | column-reverse;
__flex-wrap:__ nowrap | wrap | wrap-reverse;

### main-axis (horizontal)
__justify-content:__ flex-start | flex-end | center | space-between | space-around;

### cross-axis (vertical) - multi-line
Note: flex-wrap:wrap; is required for this property to have any effect.
Note: This property will seemingly overwrite __align-items__ in most cases.
__align-content:__ flex-start | flex-end | center | space-between | space-around | stretch;

### cross-axis (vertical) - single-line
__align-items:__ flex-start | flex-end | center | baseline | stretch;

# Fleaxbox Items

__order:__ <integer>; (default 0)

__flex-grow:__ <integer>; (default 0)
__flex-shrink:__ <integer>; (default 1)
__flex-basis:__ <width>; (e.g. 20%, 5rem or a keyword)

This is the shorthand for flex-grow, flex-shrink and flex-basis combined.
The second and third parameters (flex-shrink and flex-basis) are optional. Default is: 0 1 auto.
__flex:__ none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]

Overwrites align-items for individual flex items.
__align-self:__ auto | flex-start | flex-end | center | baseline | stretch;
