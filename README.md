# Buildtask for Couchbase driver for PHP

[![Build Status](https://travis-ci.org/marceloalmeida/php-couchbase-builddeb.svg?branch=master)](https://travis-ci.org/marceloalmeida/php-couchbase-builddeb)

Task to build Debian packages of Couchbase driver for PHP.


## Dependencies

* [libcouchbase2-core_2.6.3-1_amd64.deb](http://packages.couchbase.com/ubuntu/pool/jessie/main/libc/libcouchbase/libcouchbase2-core_2.6.3-1_amd64.deb)
* [Installing from repositories (Linux)](http://developer.couchbase.com/documentation/server/current/sdks/c-2.4/download-install.html) (Optional)


## Usage

```sh
$ docker-compose build
$ docker-compose run --rm builder
$ ls -1 pkg/
```
