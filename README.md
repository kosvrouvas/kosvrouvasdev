# kosvrouvas.dev

A simple theme that supports full-site editing. It comes with a set of minimal templates and design settings that can be manipulated through Global Styles.

## Building

Blockbase uses SCSS to compile the CSS used to ponyfill Gutenberg.  Building Blockbase isn't necessary to use it - either as a theme or as a parent theme - but making changes does require the .scss file to be recompiled.
The easiest way to do so is to use `node` to install and run the necessary dependencies via `npm install`. 
Then after making changes to the *.scss files run `npm run build` to compile.
You can use `npm start` and it will be in 'watch mode' recompiling the .scss files any time any changes are made.

## `functions.php` and `theme.css`

Blockbase will load a theme.css file for each of its children. This file lives at childtheme/assets/theme.css. You may wish to add a functions.php file to add block styles or patterns to your theme, but it's not necessary.

Together these files should give you a strong foundation for a Blockbase child theme.

## Keeping up to date

Blockbase child themes are in a strong position to keep in step with Full Site Editing changes, while being usable in production now. However they do come with a maintenance burden. As Full Site Editing matures, Blockbase will continue to change with it; Blockbase child themes will need to be kept up to date with these developments so that they can take advantage of the new features.
