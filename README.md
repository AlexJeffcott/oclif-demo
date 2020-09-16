oclif-demo
=======================

example multi-command CLI built with typescript

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@oclif/example-multi-ts.svg)](https://npmjs.org/package/@oclif/example-multi-ts)
[![CircleCI](https://circleci.com/gh/oclif/example-multi-ts/tree/master.svg?style=shield)](https://circleci.com/gh/oclif/example-multi-ts/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/example-multi-ts?branch=master&svg=true)](https://ci.appveyor.com/project/oclif/example-multi-ts/branch/master)
[![Codecov](https://codecov.io/gh/oclif/example-multi-ts/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/example-multi-ts)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/example-multi-ts.svg)](https://npmjs.org/package/@oclif/example-multi-ts)
[![License](https://img.shields.io/npm/l/@oclif/example-multi-ts.svg)](https://github.com/oclif/example-multi-ts/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g test-npm-cli
$ test-npm-cli COMMAND
running command...
$ test-npm-cli (-v|--version|version)
test-npm-cli/1.0.0 darwin-x64 node-v12.18.3
$ test-npm-cli --help [COMMAND]
USAGE
  $ test-npm-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`test-npm-cli goodbye [FILE]`](#test-npm-cli-goodbye-file)
* [`test-npm-cli hello [FILE]`](#test-npm-cli-hello-file)
* [`test-npm-cli help [COMMAND]`](#test-npm-cli-help-command)

## `test-npm-cli goodbye [FILE]`

describe the command here

```
USAGE
  $ test-npm-cli goodbye [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/goodbye.ts](https://github.com/alexjeffcott/test-npm-cli/blob/v1.0.0/src/commands/goodbye.ts)_

## `test-npm-cli hello [FILE]`

describe the command here

```
USAGE
  $ test-npm-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ test-npm-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/alexjeffcott/test-npm-cli/blob/v1.0.0/src/commands/hello.ts)_

## `test-npm-cli help [COMMAND]`

display help for test-npm-cli

```
USAGE
  $ test-npm-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
