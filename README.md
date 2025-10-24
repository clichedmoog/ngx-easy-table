[![npm version](https://badge.fury.io/js/ngx-easy-table.svg)](https://badge.fury.io/js/ngx-easy-table)
[![last commit](https://badgen.net/github/last-commit/ssuperczynski/ngx-easy-table)](https://badgen.net/github/last-commit/ssuperczynski/ngx-easy-table)
[![total downloads](https://badgen.net/npm/dt/ngx-easy-table)](https://badgen.net/npm/dt/ngx-easy-table)
[![Build Status](https://travis-ci.org/ssuperczynski/ngx-easy-table.svg?branch=master)](https://travis-ci.org/ssuperczynski/ngx-easy-table)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## Code Examples
<a href="https://github.com/ssuperczynski/ngx-easy-table/tree/master/src/app/demo" target="_blank">
https://github.com/ssuperczynski/ngx-easy-table/tree/master/src/app/demo
</a>

## Demo

<a href="https://ngx-easy-table.eu" target="_blank">
https://ngx-easy-table.eu
</a>

## Installation

### From npm (Original)
`npm install ngx-easy-table --save`

### From GitHub (This Fork with paginationRanges support)
Download the tarball from the [latest release](https://github.com/clichedmoog/ngx-easy-table/releases) and install:
```bash
npm install https://github.com/clichedmoog/ngx-easy-table/releases/download/v12.0.0-pagination-ranges/ngx-easy-table-v12.0.0-pagination-ranges.tgz
```

Library requires `@angular/cdk`, please install it as well.

`npm install @angular/cdk --save`

### New Feature: Configurable Pagination Ranges

This fork adds support for customizable pagination range options:

```typescript
configuration = {
  ...
  paginationRanges: [10, 25, 50, 100, 250], // Custom ranges instead of default [5, 10, 25, 50, 100]
  ...
};
```

## Available config settings:

See https://ngx-easy-table.eu/#/doc
