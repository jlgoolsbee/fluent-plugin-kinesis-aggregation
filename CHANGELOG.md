# CHANGELOG

## 0.3.1

- Change aws-sdk usage to work with both v2 and v3
  (in particular, makes it possible to use latest td-agent which includes the s3 plugin
  and pulls in aws-sdk v3)

## 0.3.0

- Update to use fluentd 0.14 API (stick to 0.2.3 if you need support for earlier versions of fluentd)
  Much thanks to cosmo0920 for doing this.

## 0.2.3

- emit stream name in error

## 0.2.1 - 0.2.2

- update documentation to refer to published gem
- turn on testing for Ruby 2.1
- allow running on Ruby 2.1

## 0.2.0

- switch to google protobuf library (ruby native one uses too much memory)

## 0.1.1

- fix up conflict with fluent-kinesis plugin
- Changelog

## 0.1.0

- Release on Github
