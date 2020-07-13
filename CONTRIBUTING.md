Contributing
============

Setup
-----

```bash
git clone git@github.com:epfl-si/ckeditor-twitter-embed.git
cd ckeditor-twitter-embed
npm i
```

Test
----

```bash
npm t
```

Run
---

```bash
python -m SimpleHTTPServer 8100
```

Example:  http://localhost:8100/example/

Release
-------

1. Bump the correct version (`npm version [<newversion> | major | minor | patch]`)
1. Update the file [CHANGELOG.md](CHANGELOG.md)
1. Create the tag (`git tag -a v<version> -m "ckeditor-twitter-embed - <version>"`)
1. Publish with `npm publish`

License
-------

GNU General Public License Version 2

Copyright (c) 2020 ECOLE POLYTECHNIQUE FEDERALE DE LAUSANNE, Switzerland, VPSI.

See the [LICENSE](LICENSE) file for more details.
