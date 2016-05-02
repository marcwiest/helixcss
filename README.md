
# HelixCSS

A lean OOCSS and BEMified Sass library.

## The OOCSS & BEM Approach

In OOCSS the separation of structure and skin is encouraged while nested selectors are discouraged.
The BEM naming convention helps CSS authors comply with the OOCSS principle of using a flat selector
hierarchy composed of equally-specific class selectors.

## Responsive Typography

Throughout your project, use 'rem' whenever you want the size to be adaptable to whatever the HTML's
base font-size value is set to.

## Documentation

For the moment there are only code examples available inside the components folder and the index
file. Over time, we hope to provide you with a more detailed, written documentation and maybe a
tutorial video or two.

## Folders & Contents

#### Base

This folder addresses mostly the default HTML tags, but there are a few components and utilities
mixed in with it.

#### Components

HelixCSS uses the BEM methodology primarily for the components. Components are elements that are
comprised of multiple CSS properties. Not all components are made into CSS rule-sets, some are only
available as sass mixins.

#### Utilities

Utilities are single property declaration classes that are useful and sharable between different
components without straying away too far from the BEM methodology.

#### Vendors

Currently only holds normalize-css and H5BP's print styles.
