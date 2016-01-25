# Foundation Sass with Gulp, Bower & LiveReload

Have a single workflow that

1. watches for sass changes and compiles them into css
2. watches for changes in the public directory and triggers livereload
3. serves your static content in `public/`

## Install

1. Download this repo.

2. `npm install`

3. `bower install`

## Start developing.

The default gulp task will run `connect`, `sass` and `watch`, so all you need to do is run

`gulp` ind your document root. This will compile all sass files in `sass/` into source css and copy it to `css/` and watch for changes. Enjoy!

