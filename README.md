# Sass template

A simple template ready to code web design with sass and html.

## Requirement

- Work with gulp

## Installation

- `npm install`

## Development

You can fin all non-compiled assets into assets/ directory

- `gulp sass:watch` Recompile the sass after file change

## Production

All compiled file go to public/dist

- `gulp sass` Compile all the sass one time
- `gulp concat-scripts` Compile all js one time
- `gulp minify-scripts` Minify all js one time
 
## Changing destination & source directory

You can change theses variables in `gulpfile.js`