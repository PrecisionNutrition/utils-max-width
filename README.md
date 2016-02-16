CSS utilities: max-width
========================

CSS sizing utilities. Sets `max-width` and `margin`.

Based on SUITCSS utility classes. Read more about [SUIT CSS's design principles](https://github.com/suitcss/suit/).

Installation
------------

* [npm](http://npmjs.org/): `npm install @precisionnutrition/utils-max-width`

Available classes
-----------------

* `u-maxWidth1` - Make an element have a max width of 3 base units.
* `u-maxWidth2` - Make an element have a max width of 4 base units.
* `u-maxWidth3` - Make an element have a max width of 6 base units.
* `u-maxWidth4` - Make an element have a max width of 8 base units.
* `u-maxWidthAuto` - Make an element center horizontally using auto margins.

*The base unit defaults to 8rem.*

Testing
-------

To generate a build:

```
npm run build
```

To generate the testing build.

```
npm run build-test
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
npm run lint
```

To watch the files for making changes to test:

```
npm run watch
```
