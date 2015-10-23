Starterkit-BT4
===========

A starter kit for your web project based on Bootstrap 4, with grunt and bower
## Assets

- **Bootstrap 4 (alpha version, [see documentation](http://v4-alpha.getbootstrap.com/getting-started/introduction/))**
- **SASS**
- **Font Awesome**
- **Respond.JS**
- **html5shiv**
- **Grunt**
- **Bower**

## License

Starterkit-BT4 is released under the [MIT License](COPYING).

## Getting Started

This project requires [Grunt](http://gruntjs.com/) and [Bower](http://bower.io/).

From the project's directory execute :

```
$ npm -g install grunt-cli bower
$ npm install
$ bower install
```

Run project with Grunt.

```
$ grunt
```

## Bootstrap 4 and bower

If you are having difficulty installing BT4 with bower, since it is still an alpha version, use :

```
$ bower install bootstrap#v4.0.0-alpha
```

### Stats

To have statistics on the project, run the following command :

```
$ grunt stats
```

CSS-count gives you data on the code (IE9 is limited to 4095 selectors) and PageSpeed offers data on the project performance according to [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).

## Critical CSS

Starterkit-BT4 (SBT4 in short) uses the grunt contrib for [criticalcss](https://github.com/filamentgroup/grunt-criticalcss). When you launch grunt, it generates critical css files in css/critical/.. that you can copy, paste and inline in the head of your html.

## Switch from LESS to SASS (work in progress)

If you used to use LESS, you might be interested in these readings :
- the SASS website : [http://sass-lang.com/](http://sass-lang.com/)
- some SASS resources : [http://thesassway.com/](http://thesassway.com/)
- how to override the Bootstrap variables (the variables are interpreted differently) : [https://github.com/RailsApps/rails-bootstrap/issues/12](https://github.com/RailsApps/rails-bootstrap/issues/12)
- using REM instead of px is very awesome for a lot of reasons I won't enumerate here. To facilitate the switch to REM unit, you can use the [calc-rem() function](https://github.com/taupecat/sass-responsive/blob/master/_responsive.scss#L146) defined in the scss/custom-variables.scss file, unless you ask grunt [to manage it for you](https://www.npmjs.com/package/grunt-px-to-rem).


