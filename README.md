
# 🍓 StrawberryGrid
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/iseries/StrawberryGrid/blob/master/LICENSE)
[![Latest Github release](https://img.shields.io/github/release/iseries/StrawberryGrid.svg)](https://github.com/iseries/StrawberryGrid/releases/latest)

Just another simple flexbox grid called **StrawberryGrid**. This was created because you always need a simple, functional, adjustable grid - without unnecessary features.

StrawberryGrid is using the **CSS Flexible Box Layout Module** (Flexbox) to positioning elements in horizontal and/or vertical stacks - basically our Grid with columns.
StrawberryGrid includes features for all properties prefixed with _flex_, as well as _display: flex_,
display: _inline-flex_, _align-content_, _align-items_, _align-self_, _justify-content_ and _order_.

## Contents
- [Configuration](#configuration)
- [Compiling](#compiling)
- [Usage and examples](#usage-and-examples)
- [Development and contributing](#development-and-contributing)

## Configuration
Open StrawberryGrid.scss:
```scss
// Set the number of columns
$columns: 12 !default;

// Set the gutter between columns
$gutter-width: 1rem !default;

// Set a margin for the outer container
$outer-margin: 2rem !default;

// max width container size
$max-width: 1200px !default;

// possible breakpoints (name, min-width for media query, container width)
// "xs" is default, you don't need to add it.
$breakpoints: sm 48em 46rem, md 62em 61rem, lg 75em 71rem !default;
```

## Compile
### Command Line
```shell
sass --update StrawberryGrid.scss:../dist/StrawberryGrid.css
```
or minified:
```shell
sass --update --style=compressed StrawberryGrid.scss:../dist/StrawberryGrid.min.css
```

## Usage and examples
soon

## Development and contributing
Feel free to send pull requests and raise issues.