## rails365

分享文章和视频 http://www.rails365.net

This is the source code of rails365.net website.

[![Build Status](https://travis-ci.org/yinsigan/rails365.svg?branch=master)](https://travis-ci.org/yinsigan/rails365) [![Code Climate](https://codeclimate.com/github/yinsigan/rails365/badges/gpa.svg)](https://codeclimate.com/github/yinsigan/rails365) [![codecov](https://codecov.io/gh/yinsigan/rails365/branch/master/graph/badge.svg)](https://codecov.io/gh/yinsigan/rails365)

### 依赖:

* rails 4

* postgresql

* redis

* elasticsearch

### 安装:

```
bundle install
cp config/database.yml.example config/database.yml
cp config/settings.yml.example config/settings.yml
```

### 测试:

```
bundle exec guard
```

或者

```
bundle exec spring rspec
```

## License

Copyright (c) 2015-2016 rails365

Released under the MIT license:

* [www.opensource.org/licenses/MIT](http://www.opensource.org/licenses/MIT)
