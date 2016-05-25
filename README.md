
# HelixCSS

A lean OOCSS and BEMified Sass library. HelixCSS primary goal is to give structure to your website
or application and leave the design decisions to you.

## The OOCSS & BEM Approach

In OOCSS the separation of structure and skin is encouraged while nested selectors are discouraged.
The BEM naming convention helps CSS authors comply with the OOCSS principle of using a flat selector
hierarchy composed of equally-specific class selectors.

## Responsive Typography

Throughout your project, use 'rem' whenever you want the size to be adaptable to whatever the HTML's
base font-size value is set to.

## Documentation

For the moment there are only code examples available inside the components folder and the index
file. Over time, a more detailed, written documentation and maybe a tutorial video will be made
available.

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

Currently only holds normalize-css and H5BP's print styles. In the future may include other external
resources like [animate.css](https://daneden.github.io/animate.css/).

## Known Issues

Android jellybean has trouble with the grid and group components. That is because these components
make use of the `inline-block` and `font-size:0;` hack.

## Helix Roadmap

1. Start using the CHANGLOG.md file and begin versioning.
3. Build compiler using either gulp, grunt or postcss.
4. Use [autoprefixer](https://github.com/postcss/autoprefixer) instead of manually writing prefixes.
2. Rebuild grid to use flexbox and provide optional IE fallback.
5. Clean mixin only components to avoid nested selectors and code bloat.

## Browser Support Resources

- [http://caniuse.com/](http://caniuse.com/)
- [http://shouldiprefix.com/](http://shouldiprefix.com/)
- [http://html5please.com/](http://html5please.com/)
