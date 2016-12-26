# Best Practices: CSS Units

- Set the `font-size` of the document root (the `<html>` tag) to `100%`.
This allows a _master_ base scale to be established according to the user's
browser font preferences.

- Prefer `rem` and `em` units
 - The provide a flexible and powerful paradigm for responsive sizing -- with respect to global (`rem`)
 _or_ local (`em`) element font-sizing.
 - [Comprehensive overview of `rem`, `em`, and when to use each](https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984).
   + [See Also](https://css-tricks.com/rem-global-em-local/)
 - Deep insight into [why/how to use `em` for setting Media Queries](https://zellwk.com/blog/media-query-units/).
