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
- <code>gulp dev</code> - sequenced gulp-sass, browser-sync and watch function,
- <code>gulp build</code> - sequenced cleaning "dist" directory and then gulp-sass, gulp-useref, gulp-csso, moving img and fonts to "dist" and gulp-autoprefixer.
