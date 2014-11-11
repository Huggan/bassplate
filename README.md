# Bassplate
Boilerplate for Basscss with Gulp, Rework, and Browserify

## Features
- Basic `index.html` template with asset links
- Starter folder structure
- Gulp task for compiling CSS with Rework
- Gulp task for compiling JS with Browserify
- Gulp task for local web server
- Basswork CSS preprocessor
  - Autoprefixer
  - Rework Variables based on the CSS variables syntax
  - Rework Custom Media Queries based on the CSS syntax
  - Rework NPM imports
  - Rework Calc to compile `calc()` syntax
  - Rework Plugin Colors

## Getting Started

To start fresh, clone Bassplate into a new project and remove its git directory.

``` bash
git clone https://github.com/jxnblk/bassplate.git new-project
cd new-project
rm -rf .git
```

Install dev dependencies. (Requires Node NPM -- [Install Node](http://nodejs.org/download/))

``` bash
npm install
```

Run the default Gulp task to compile assets and start a local web server.
(Requires Gulp -- [Install Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started))

``` bash
gulp
```
