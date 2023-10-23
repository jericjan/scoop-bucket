# Scoop Bucket Template

[![Tests](https://github.com/jericjan/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/jericjan/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/jericjan/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/jericjan/scoop-bucket/actions/workflows/excavator.yml)

A bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Included Packages:

1. [ls-interactive](https://github.com/Araxeus/ls-interactive)


## How do I install this bucket?
```
scoop bucket add <bucketname> https://github.com/jericjan/scoop-bucket
```
To install a package from this bucket, do:
```
scoop install <bucketname>/<packagename>
```

Ex:
```
scoop bucket add jericjan https://github.com/jericjan/scoop-bucket
scoop install jericjan/ls-interactive
```
