# foundation-nunjucks

This is the front-end development kit for use with [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Nunjucks HTML templates
- Sass compilation and prefixing (with libsass)
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

This template can be installed with the Foundation CLI, or downloaded and set up manually.

### Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com:directions4/foundation-nunjucks.git projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
```

## Running
Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`.

```bash
npm start
```

Viewable at this URL:

```
http://localhost:8000
```

## Compiling

To create compressed, production-ready assets, run `npm run build`.

```bash
npm run build
```

## Settings

You can set paths, browser compatibility and port number in `config.yml`.
