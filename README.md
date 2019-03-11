# Fork notes first

This is forked version of Stylish Portfolio Template. It was changed for demonstration purposes
of [Colouro app](https://colouroapp.com/).

Changes made to original version:
1. Two main background images was changed to be grayscale mostly and have alpha channel so the color can be blended in CSS using `background-color` in conjunction with `background-image`.
2. A bit unified usage of SASS color variables across styles/HTML.
3. [Colouro SDK](http://docs.colouroapp.com/sdk-js/colouro-sync.html) integrated.


## Quickstart

1. Clone the repo

    ```
    git clone https://github.com/barzto/startbootstrap-stylish-portfolio.git
    cd startbootstrap-stylish-portfolio
    ```

2. Create `colouro.local.json` file with IP address (and port) of you handset running Colouro app as displayed in _preview dialog_.

    ```
    {
        "host":"192.168.0.42:8080"
    }
    ```
3. Launch the [Colouro app](https://colouroapp.com)
4. Install NPM packages and run `gulp watch`

    ```
    npm i
    npx gulp watch
    ```
5. Change your color palette in Colouro app and see changes live in your browser.

Have fun!


# [Start Bootstrap - Stylish Portfolio](https://startbootstrap.com/template-overviews/stylish-portfolio/)

[Stylish Portfolio](http://startbootstrap.com/template-overviews/stylish-portfolio/) is a responsive, one page portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). The theme features multiple content sections with an off canvas navigation menu.

## Preview

[![Stylish Portfolio Preview](https://startbootstrap.com/assets/img/screenshots/themes/stylish-portfolio.png)](https://blackrockdigital.github.io/startbootstrap-stylish-portfolio/)

**[View Live Preview](https://blackrockdigital.github.io/startbootstrap-stylish-portfolio/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-stylish-portfolio/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-stylish-portfolio.svg)](https://www.npmjs.com/package/startbootstrap-stylish-portfolio)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-stylish-portfolio.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-stylish-portfolio)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-stylish-portfolio/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-stylish-portfolio)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-stylish-portfolio/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-stylish-portfolio?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Start Bootstrap](https://startbootstrap.com/template-overviews/stylish-portfolio/)
* Install via npm: `npm i startbootstrap-stylish-portfolio`
* Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio.git`
* [Fork, Clone, or Download on GitHub](https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

After installation, run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You must have npm and Gulp installed globally on your machine in order to use these features.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/stylish-portfolio/).

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* https://startbootstrap.com
* https://twitter.com/SBootstrap

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* http://davidmiller.io
* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-stylish-portfolio/blob/gh-pages/LICENSE) license.
