# Slick themes

## How To Use

This package requires that your build process renders sass. To use:

`yarn add @kuus/slick-themes`

or 

`npm i --dev @kuus/slick-themes`

Then import it into your sass files:

```scss
@import '~@kuus/slick-themes/base';
```

### SCSS Variables

```scss
$slick-arrow-spacer-x: 1rem;
$slick-arrow-size: 48px;
$slick-arrow-thickness: 4;
$slick-arrow-color: #222;
$slick-dot-spacer-y: 0;
$slick-dot-spacer-x: 0;
$slick-dot-size: 10px;
$slick-dot-clickable-width: 32px;
$slick-dot-clickable-height: 48px;
$slick-dot-color: #222;
$slick-dot-color-active: $slick-dot-color;
$slick-opacity-default: 0.75;
$slick-opacity-on-hover: 1;
$slick-opacity-not-active: 0.25;
```
