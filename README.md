# PostCSS Ref [![Build Status][ci-img]][ci]

[PostCSS] plugin that allows you to reference properties on itself and other rules.

[PostCSS]: https://github.com/postcss/postcss
[ci-img]:  https://travis-ci.org/dan-gamble/postcss-ref.svg
[ci]:      https://travis-ci.org/dan-gamble/postcss-ref

```css
.foo {
    /* Input example */
}
```

```css
.foo {
  /* Output example */
}
```

## Usage

```js
postcss([ require('postcss-ref') ])
```

See [PostCSS] docs for examples for your environment.
