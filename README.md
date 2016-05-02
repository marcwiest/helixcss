
# HelixCSS
---

A lean OOCSS and BEMified Sass library.

## Approach

HelixCSS is an object oriented and BEMified CSS library. However, HelixCSS does not simply stick to
these methodologies, but uses them as guiding principles.

In OOCSS the separation of structure and skin is encouraged while nested selectors are discouraged.
The BEM naming convention helps CSS authors comply with the OOCSS principle of using a flat selector
hierarchy composed of equally-specific class selectors.

## Folders & Contents

__Base__
This folder addresses mostly the looks of the default HTML tags, but there are some components and
utilities mixed in with it.

__Components__
HelixCSS uses the BEM methodology for the components. Components are elements that are comprised of
multiple CSS properties.

__Utilities__
Utilities are single rule classes that are useful and sharable between different components without
straying away too far from the BEM methodology.

## Responsive Typography

Throughout your project, use 'rem' whenever you want the size to be adaptable to whatever the HTML's
font-size value is set to.

## Inspiration

Frameworks that inspired HelixCSS.

- [inuit.css](https://github.com/csswizardry/inuit.css)
- [inuitcss](https://github.com/inuitcss)
- [skeleton](http://getskeleton.com/)
- [basscss](http://www.basscss.com/)


## TODO's

- webdesign.tutsplus.com/tutorials/quick-tip-solving-the-equal-height-column-conundrum--cms-20403
