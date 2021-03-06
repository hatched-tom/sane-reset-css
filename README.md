# `sane-reset-css`

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

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
