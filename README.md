# `sane-reset-css`

A reset for modern browsers (and IE11).

Features:

- Small (for the majority of users who don't use IE)
- Exhaustive, as it uses `all: unset`
- Doesn't `all: unset` on input elements
- Gives you messages if you use an anti-pattern
  or deprecated tag
- Conditionally imports a full reset file for
  IE10/11, as they don't support `all: unset`
- Tested using https://github.com/cbracco/html5-test-page
