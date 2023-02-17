# The V Programming Language Website
https://vlang.io
![Example](example.png)\
[The original](https://github.com/hex2f/vlang.io) version was written by [leahlundqvist](https://github.com/hex2f) aka ``hes2f``.
The website is build via Nunjucks templates. With ``npm run build``the ``build-pages.js`` script creates pages from njk files (templates), converts sass to css and runs the page on ``localhost:3000`` via **serve**\
If you only want to build pages and not run them via ``serve`` then delete ``&& serve build/`` from line 23 of ``package.json``.
Usage:
```
git clone https://github.com/vlang/vlang.io
cd vlang.io
npm install
npm install --global serve
npm run build
```

*note: You can't run the whole site locally, because of proprietary backend, but you can preview the html file `index.html` for styling css.*

## How To Contribute

There are various way you can contribute to this project. Refactoring writings, updating css, adding Language support etc. We will cover them one by one.

### Styling the website

There is `app.sass` file which is the main stylesheet. Use `pindex.html` to view the rendered html file. This will help you style the website.

### Adding Language

Use the `english.tr` as a reference to add your translation to this project.
