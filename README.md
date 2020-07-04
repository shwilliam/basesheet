# basesheet

> A better CSS foundation

## Overview

- Lightweight reset (based on [Eric Meyer's CSS reset v2](https://meyerweb.com/eric/tools/css/reset/))
- Helpful utility classes
- Disables animations based on `prefers-reduced-motion`
- Dispatches single taps without delay
- Color, font, layout, and sizing custom variables

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
