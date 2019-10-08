# SASS

## Structure SASS in this project
<pre>
sass/
|
|– abstracts/ (or utilities/)
|   |– _variables.scss    // Sass Variables
|   |– _mixins.scss       // Sass Mixins
|
|– base/
|   |– _base.scss         // General
|   |– _typography.scss   // Install & Set Font
|
|– components/ (or modules/)
|   |– _buttons.scss      // Buttons
|   |– _carousel.scss     // Carousel
|   |– _slider.scss       // Slider
|
|– layout/
|   |– _header.scss       // Header
|   |– _footer.scss       // Footer
|
|
`– main.scss              // Main Sass file
</pre>

## Usage Sass
1. Set sass want to compile in `webpack.mix.js`.
2. Set variable, base, font. You can check in structure sass above.
3. Compile with `yarn watch` or `npm run watch`. If your want to minify css, running `yarn prod` or `npm run prod`.# menu-eddy
# menu-eddy
