# basesheet

> A better CSS foundation

## Overview

- Lightweight reset (based on [Eric Meyer's CSS reset v2](https://meyerweb.com/eric/tools/css/reset/))
- Helpful utility classes
- Disables animations based on `prefers-reduced-motion`
- Dispatches single taps without delay
- Color, font, layout, and sizing custom variables

## Usage

### CDN

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/@shwilliam/basesheet@latest/basesheet.css"
/>
```

### NPM package

- Add this package as a dependency (`npm i @shwilliam/basesheet`)
- Import it in your JavaScript file

```js
import '@shwilliam/basesheet'
```

## FAQ

### What's up with these long class names?

This stylesheet loosely follows the [BEM conventions](http://getbem.com/introduction/) with several exceptions.

1. Modifier classes can be used on their own
2. Classes prefixed with a hyphen (eg. `-success`) modify a style and should not be used on their own

### This font size is gross; how do I change it?

```css
body {
  font-size: 13px;
}
```

## Contributing

This project is open to and encourages contributions! Feel free to discuss any bug fixes/features in the [issues](https://github.com/shwilliam/basesheet/issues). If you wish to work on this project:

1. Fork [this project](https://github.com/shwilliam/basesheet)
2. Create a branch (`git checkout -b new-branch`)
3. Commit your changes (`git commit -am 'add new feature'`)
4. Push to the branch (`git push origin new-branch`)
5. [Submit a pull request!](https://github.com/shwilliam/basesheet/pull/new/master)
