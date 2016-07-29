
# HelixCSS v2.0

A lean SCSS framework. HelixCSS primary goal is to give structure to your website or application and
leave the design decisions to you.

## Documentation

For the moment there are only code examples available inside the objects folders. Over time, a more
detailed documentation will be made available.

## Folders & Contents

#### Variables

To help you find the variables you are looking for faster, variables have their own folder and files.
Some variable groups have abstract variables. These abstract variables are there to shorten the setup
of the element variables and are used inside objects.

#### Base

This folder addresses mostly HTML tags, but there are also a couple of classes within it.

#### Objects

Objects are the CSS styles. Some objects are more complex than others. Objects that are more complex
can be extend by the used of their silent classes. The mixin folder holds a few goodies that purely
exist as SCSS mixin.

#### Utilities

In here are functions, mixins and variables that are useful for SCSS development. Using CSS3 mixins
rather than a tool like auto-prefixer allows HelixCSS to compiling on the server with, for example,
[scssphp](http://leafo.net/scssphp/).

## Responsive Sizing

Throughout your project, use `rem` or `em` whenever you want a size to be adaptable to whatever the
HTML's base font-size value is set to. The base font-size varies between breakpoints. This allows for
responsive typography and sizing. Take a look at the variables inside `_typograpy.scss` to change or
disable responsive sizing.

## Reminders

- [IE 9 & 10](http://caniuse.com/#search=rem) do not support rem units when used in the `font`
  shorthand property (the entire declaration is ignored) or when used on pseudo elements like
  `::before` & `::after`.

## Browser & OS Support

HelixCSS supports IE9+ & Android2.3+.

## Credits

HelixCSS was inspired by these fine projects:
- BassCSS
- Burbon
- KiteCSS
- SassBurger
- InuitCSS

## Resources

- [http://caniuse.com/](http://caniuse.com/)
- [http://www.cssfontstack.com/](http://www.cssfontstack.com/)
