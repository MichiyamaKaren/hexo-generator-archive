# hexo-archive-bychapter

[![Build Status](https://github.com/hexojs/hexo-generator-archive/workflows/Tester/badge.svg)](https://github.com/hexojs/hexo-generator-archive/actions?query=workflow%3ATester)
[![NPM version](https://badge.fury.io/js/hexo-generator-archive.svg)](https://www.npmjs.com/package/hexo-generator-archive)
[![Coverage Status](https://img.shields.io/coveralls/hexojs/hexo-generator-archive.svg)](https://coveralls.io/r/hexojs/hexo-generator-archive?branch=master)

Archive generator for [Hexo]. Based on [hexo-generator-archive](https://www.npmjs.com/package/hexo-generator-archive).

## Installation

``` bash
$ npm install hexo-archive-bychapter --save
```

## Options

``` yaml
archive_generator:
  enabled: true
  per_page: 10
  yearly: true
  monthly: true
  daily: false
  order_by: -date
  by_chapter: false
```

- **enabled**: The default value is **true**, set to **false** if you do not want to enable the plugin
- **per_page**: Posts displayed per page. (**0** = disable pagination)
- **yearly**: Generate yearly archive.
- **monthly**: Generate monthly archive.
- **daily**: Generate daily archive.
- **order_by**: Posts order. (Order by date descending by default)
- **by_chapter**: Enables archive by chapter (defined in front-matter).

## License

MIT

[Hexo]: https://hexo.io/
