[![NPM version][npm-image]][npm-url] 
[![Build status][travis-image]][travis-url] 
[![Coverage percentage][coveralls-image]][coveralls-url]
[![Dependency Status][daviddm-image]][daviddm-url] 
[![Codacy Badge][codacy-image]][codacy-url]

# generator-pypi-master 

[![NPM](https://nodei.co/npm/generator-pypi-master.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/generator-pypi-master/)

> A complete pypi package generator

![Generator example](assets/yeoman-example.png)

Generate a new custom pypi package in seconds.

**For a simpler python project - check out [generator-pyboot](https://github.com/mijdavis2/generator-pyboot).**

## Features

- Populated setup.py ready for pypi publishing
- Easy virtualenv setup script
- Pre-badged README.md
- Travis-Ci yml setup with suggested testing
- Gitignore with the usual suspects
- Pre-populated requirements.txt
- License generator
- Github feature templates

## Installation

First, install [Yeoman](http://yeoman.io) and generator-pypi-master using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-pypi-master
```

Then generate your new project:

```bash
yo pypi-master
```

## Generated File Tree

```
package/
|-- .github/
|    |-- CONTRIBUTING.md
|    |-- ISSUE_TEMPLATE.md
|    |-- PULL_REQUEST_TEMPLATE.md
|-- package/
|    |-- __init__.py
|    |-- core.py
|    |-- tests/
|        |-- __init__.py
|-- CHANGELOG.md
|-- LICENSE 
|-- MANIFEST.in
|-- README.md
|-- requirements.txt
|-- setup.py 
|-- setup.sh
```

## Test

```
npm test
```

## Contribute

Go [here](https://github.com/mijdavis2/generator-pypi-master/issues)
to submit feature suggestions or report a bugs. Pull requests are also
welcome.

## License

MIT © [mijdavis2](https://mdavis.io)


[npm-image]: https://badge.fury.io/js/generator-pypi-master.svg
[npm-url]: https://npmjs.org/package/generator-pypi-master
[travis-image]: https://travis-ci.org/mijdavis2/generator-pypi-master.svg?branch=master
[travis-url]: https://travis-ci.org/mijdavis2/generator-pypi-master
[coveralls-image]: https://coveralls.io/repos/mijdavis2/generator-pypi-master/badge.svg
[coveralls-url]: https://coveralls.io/r/mijdavis2/generator-pypi-master
[daviddm-image]: https://david-dm.org/mijdavis2/generator-pypi-master.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/mijdavis2/generator-pypi-master
[codacy-image]: https://api.codacy.com/project/badge/Grade/56e02026555345a99f3e4479e3cce657
[codacy-url]: https://www.codacy.com/app/mijdavis2/generator-pypi-master?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=mijdavis2/generator-pypi-master&amp;utm_campaign=Badge_Grade
