# npm-optional-dependency-test

Testing optional dependencies with shrinkwrap for npm@3.9.0

## Repro steps:

Run on either Windows or Linux

  - Checkout master and `npm install`. Notice no errors.
  - `git clean -xdff`
  - Checkout `appdmg-with-macos-alias` and `npm install`. Notice errors thrown for optional dependency `macos-alias`.
