# `sane-reset-css`

A reset for modern browsers (and IE11).

Features:

- Small (for the majority of users who don't use IE)
- Exhaustive, as it uses `all: unset`
- No formatting at all, except on input elements
  for usability's sake, and accessibility
- Gives you the foundation boilerplate you need
  100% of the time, and has no formatting
- Gives you messages if you use an anti-pattern
  or deprecated tag
- Conditionally imports a full reset file for
  IE10/11, as they don't support `all: unset`
- Tested using https://github.com/cbracco/html5-test-page

Only 20% larger than the most popular reset file;
but achieves so much more 🌈
