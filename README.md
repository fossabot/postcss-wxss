# PostCSS Wxss [![Build Status][ci-img]][ci]
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FIOriens%2Fpostcss-wxss.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FIOriens%2Fpostcss-wxss?ref=badge_shield)

[PostCSS] plugin to transpile wxss or acss..

[PostCSS]: https://github.com/postcss/postcss
[ci-img]:  https://travis-ci.org/IOriens/postcss-wxss.svg
[ci]:      https://travis-ci.org/IOriens/postcss-wxss

```css
@media screen and (min-width: 480rpx) {
  body {
    background-color: lightgreen;
    animation-name: 'kkk';
  }
}

#main, icon {
  border: 1rpx solid black;
}

ul li, .page, page {
  padding: 5rpx 3rpx;
}
```

```css
@media screen and (min-width: 480rpx) {
  body {
    background-color: lightgreen;
    animation-name: 'kkk';
  }
}

#main, wx-icon {
  border: %%?1rpx?%% solid black;
}

ul li, .page, body {
  padding: %%?5rpx?%% %%?3rpx?%%;
}
```

## Usage

```js
postcss([ require('postcss-wxss') ])
```

See [PostCSS] docs for examples for your environment.

## Reference

[writing-a-plugin](https://github.com/postcss/postcss/blob/master/docs/writing-a-plugin.md)

## License

MIT



[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FIOriens%2Fpostcss-wxss.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FIOriens%2Fpostcss-wxss?ref=badge_large)