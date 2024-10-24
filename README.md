## What is this?

This repository allows you to quickly install the [S3 HTTP proxy](https://github.com/codemonauts/s3-http-proxy) into a [DDEV](https://ddev.readthedocs.io) project using the instructions below.

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get codemonauts/ddev-s3-http-proxy
```

For earlier versions of DDEV run

```sh
ddev get codemonauts/ddev-s3-http-proxy
```

Then restart your project

```sh
ddev restart
```
