# jekyll-js-minify-plugin

A Jekyll plugin that automatically minifies all Javascript files using the Google Closure Compiler

## Usage

    gem install 'closure-compiler'
    cp jsminify.rb YOUR_JEKYLL_DIR/_plugins/

That's it. All files ending in `.js` will be minified. Files ending in `.min.js` will be skipped. It's almost magical.
