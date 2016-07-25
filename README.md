
# HelixCSS v1.1.2

A lean OOCSS and BEMified SCSS framework. HelixCSS primary goal is to give structure to your website
or application and leave the design decisions to you.

## The OOCSS & BEM Approach

In OOCSS the separation of structure and skin is encouraged while nested selectors are discouraged.
The BEM naming convention helps CSS authors comply with the OOCSS principle of using a flat selector
hierarchy composed of equally-specific class selectors.

## Documentation

For the moment there are only code examples available inside the objects folders. Over time, a more
detailed documentation will be made available.

## Folders & Contents

#### Variables

To help you find the variables you are looking for faster, variables have their own folder and files.
Some variable groups have abstract variables. These abstract variables are there to shorten the setup
of the element and utility variables.

#### Vendors

Holds external resources such as normalize-css and H5BP's print styles.

#### Base

This folder addresses mostly the default HTML tags, but there are also a couple of component and
utility classes within `_document.scss`.

#### Objects

- **Containers Folder:** The containers folder holds purely structural elements that handle skeletal aspects,
without ever actually looking like designed ‘things’.
- **Components Folder:** The components folder holds specific UI elements like buttons and badges.
- **Utilities Folder:** Utilities are classes that help manipulate containers and components.

#### CSS3

These mixins take care of CSS3 browser consistencies. This eliminate the need for a 3rd party
framework and allows for compiling on the server with, for example, [scssphp](http://leafo.net/scssphp/).

## Responsive Sizing

Throughout your project, use `rem` or `em` whenever you want a size to be adaptable to whatever the
HTML's base font-size value is set to. The base font-size varies between breakpoints. This allows for
responsive typography and sizing.

## Reminders

- [IE 9 & 10](http://caniuse.com/#search=rem) do not support rem units when used in the `font`
  shorthand property (the entire declaration is ignored) or when used on pseudo elements like
  `::before` & `::after`.

## Browser & OS Support

HelixCSS supports IE9+ & Android2.3+.

## Resources

- [http://caniuse.com/](http://caniuse.com/)
- [http://shouldiprefix.com/](http://shouldiprefix.com/)
- [http://html5please.com/](http://html5please.com/)
- [http://www.cssfontstack.com/](http://www.cssfontstack.com/)
- [sitepoint.com/top-9-animation-libraries-use-2016/](https://www.sitepoint.com/top-9-animation-libraries-use-2016/)
