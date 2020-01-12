# Enable OpenType features with CSS

You can find 2 solutions here:

- `/css/opentype.css` that supports IE11. See [Caring about OpenType features](https://practice.typekit.com/lesson/caring-about-opentype-features/) for details.
- `/css/opentype-css-variables.css` with CSS custom properties + `@supports`. Use this if you don't need support for IE11.

The examples are _not_ optimized for performance. For example, the font files are 200KB each, and the stylesheets/scripts are render-blocking.
