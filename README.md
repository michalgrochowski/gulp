# gulp
My standard gulp config

This is my standard gulp config files I use with my projects. Made with tutorial written by https://github.com/zellwk on CSS-TRICKS - https://css-tricks.com/gulp-for-beginners/

Plugins used:
- gulp-sass
- browser-sync
- gulp-useref
- gulp-uglify
- gulp-if
- gulp-imagemin
- del
- gulp-cache
- run-sequence
- gulp-autoprefixer
- gulp-csso

Main tasks:
- <code>gulp dev</code> - sequenced sass (convert Scss to Css), browser-sync (reload page after change in files) and watch function,
- <code>gulp build</code> - sequenced cleaning "dist" directory and then sass (convert Scss to Css), useref (uglifying JS), csso (minify Css), img (optimizing images and moving them to "dist/img"), moving fonts to fonts to "dist/fonts" and autoprefixer for Css.
