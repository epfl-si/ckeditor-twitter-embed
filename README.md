ckeditor-twitter-embed
======================

[![Build Status][travis-image]][travis-url]
[![Dependencies Status][daviddm-image]][daviddm-url]
[![npm version][npm-image]][npm-url]

CKEditor Twitter plugin based on Media Embed.

Install
-------

```bash
npm i ckeditor-twitter-embed
```

or download the `.zip` archive and extract the `src` folder to the `plugins`
folder of your CKEditor installation. 

The plugin `embedbase` is also required.

Usage
-----

Use the `extraPlugins` setting to add the plugin to your configuration:

```js
 config.extraPlugins = 'twitterembed';
```

You can specify the location of the plugin with:

```js
CKEDITOR.plugins.addExternal(
  'twitterembed',
  '/plugins/twitterembed/src/',
  'plugin.js'
);
```

Contributing
------------

See [Contributing](CONTRIBUTING.md).

Contributors
------------

* [Gil Brechbühler](https://github.com/gilbrechbuhler)
* [William Belle](https://github.com/williambelle)

License
-------

GNU General Public License Version 2

Copyright (c) 2020 ECOLE POLYTECHNIQUE FEDERALE DE LAUSANNE, Switzerland, VPSI.

[travis-image]: https://travis-ci.org/epfl-si/ckeditor-twitter-embed.svg?branch=master
[travis-url]: https://travis-ci.org/epfl-si/ckeditor-twitter-embed
[daviddm-image]: https://david-dm.org/epfl-si/ckeditor-twitter-embed/status.svg
[daviddm-url]: https://david-dm.org/epfl-si/ckeditor-twitter-embed
[npm-image]: https://img.shields.io/npm/v/ckeditor-twitter-embed.svg
[npm-url]: https://www.npmjs.com/package/ckeditor-twitter-embed
