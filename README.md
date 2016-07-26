
# HelixCSS v2-dev

Currently under development.

## Roadmap

- Move away from BEM to OOCSS naming convention. BEM creates unpleasantly long HTML tags. HelixCSS is
  small enough that OOCSS classes are sufficient.
- Flexbox based grid and group containers that have an optional IE fallback.
- Inline labels ala: http://ionicframework.com/docs/components/#forms-inline-labels
- Lists ala: http://ionicframework.com/docs/components/#list
- Padding Utility: Add/remove padding. Padding is based on grid_col_padding.
- Remove .grid--flush/.grid__item--flush in favor of padding-util.
- Margin Utility: Add .vr (vertical-rhythem) and .mb0.
- Widths Utility: Instead of grid__item col width.
- Rename Scrollbar object to Scrollable.
- Move container & component mixin-only objects to objects/mixins folder.
- Merge containers & components into components folder.
