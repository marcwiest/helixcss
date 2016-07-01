
# HelixCSS

A lean OOCSS and BEMified Sass library. HelixCSS primary goal is to give structure to your website
or application and leave the design decisions to you.

## The OOCSS & BEM Approach

In OOCSS the separation of structure and skin is encouraged while nested selectors are discouraged.
The BEM naming convention helps CSS authors comply with the OOCSS principle of using a flat selector
hierarchy composed of equally-specific class selectors.

## Documentation

For the moment there are only code examples available inside the objects and components folders.
Over time, a more detailed documentation will be made available.

## Folders & Contents

#### Variables

To help you find the variables you are looking for faster, variables have their own folder and files.

#### Base

This folder addresses mostly the default HTML tags, but there are also a couple of silent component
classes (%heading, %link & %small) within `_document.scss`.

#### Objects

Objects are purely structural elements that handle skeletal aspects, without ever actually looking
like designed ‘things’.

#### Components

The components folder holds specific UI elements like buttons and badges.

#### Utilities

Utilities are single property declaration classes that are useful and sharable between different
components.

#### Vendors

Holds external resources such as normalize-css.

#### CSS3

Contains mixins that take care of CSS3 browser consistency and eliminate the need for a 3rd party
framework.

## Responsive Sizing

Throughout your project, use `rem` whenever you want a size to be adaptable to whatever the HTML's
base font-size value is set to. The base font-size varies between breakpoints. This allows for
responsive typography and sizing.

## Reminders

- [IE 9 & 10](http://caniuse.com/#search=rem) do not support rem units when used in the `font`
  shorthand property (the entire declaration is ignored) or when used on pseudo elements like
  `:before` & `:after`.

## Roadmap

1. Start using the CHANGLOG.md file and begin versioning.
2. Clean mixin-only components to avoid nested selectors and code bloat.
3. Create a proper documentation.

## Browser & OS Support

HelixCSS supports IE9+ & Android2.3+.

## Resources

- [http://caniuse.com/](http://caniuse.com/)
- [http://shouldiprefix.com/](http://shouldiprefix.com/)
- [http://html5please.com/](http://html5please.com/)
- [http://www.cssfontstack.com/](http://www.cssfontstack.com/)
