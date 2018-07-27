# jo2k-normalize-scss

## What is it

This is based on the original `normalize.css`, version 8.0.0 by necolas, converted to a sass partial for my own use and convenience. I'm sharing it here in case anyone wants to use it.

All credit of this work goes to the original author. See original repo [normalize.css](https://github.com/necolas/normalize.css)

## Why?

I wanted to use normalize.css as a scss partial, but noticed no official package, so I downloaded the original normalize.css and made a few changes.

## What's Changed?

- Original `normalize.css` v8.0.0 renamed to `_normalize.scss` to create sass partial
- First multi-comment line was intentionally left untouched
- Multi-line comments changed to single line comments to keep them out of the compiled CSS
- Spacing, indentation, elements, and everything else remains untouched

## How to use

- Download or clone the file `_normalize.scss` and save it to your `scss` folder.
- Modify as needed and build your sass from here. If using a single file only, rename it to `normalize.scss` or something else, ending in `.scss`
- If planning to use it as a partial, save it to your `scss/partials` folder and import it into your `scss/main.scss` file where you have your other partial imports.
