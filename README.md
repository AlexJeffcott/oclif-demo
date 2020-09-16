oclif-demo
=======================

example multi-command CLI built with typescript

[![Version](https://img.shields.io/npm/v/@oclif/example-multi-ts.svg)](https://npmjs.org/package/@alexjeffcott/oclif-demo)
[![CircleCI](https://circleci.com/gh/alexjeffcott/oclif-demo/tree/master.svg?style=shield)](https://circleci.com/gh/alexjeffcott/oclif-demo/tree/master)
[![Codecov](https://codecov.io/gh/alexjeffcott/oclif-demo/branch/master/graph/badge.svg)](https://codecov.io/gh/alexjeffcott/oclif-demo)
[![Downloads/week](https://img.shields.io/npm/dw/@alexjeffcott/oclif-demo.svg)](https://npmjs.org/package/@alexjeffcott/oclif-demo)
[![License](https://img.shields.io/npm/l/@alexjeffcott/oclif-demo.svg)](https://github.com/alexjeffcott/oclif-demo/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @alexjeffcott/oclif-demo
$ oclif-demo COMMAND
running command...
$ oclif-demo (-v|--version|version)
@alexjeffcott/oclif-demo/1.0.0 darwin-x64 node-v12.18.3
$ oclif-demo --help [COMMAND]
USAGE
  $ oclif-demo COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`oclif-demo goodbye [FILE]`](#oclif-demo-goodbye-file)
* [`oclif-demo hello [FILE]`](#oclif-demo-hello-file)
* [`oclif-demo help [COMMAND]`](#oclif-demo-help-command)

## `oclif-demo goodbye [FILE]`

describe the command here

```
USAGE
  $ oclif-demo goodbye [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/goodbye.ts](https://github.com/AlexJeffcott/oclif-demo/blob/v1.0.0/src/commands/goodbye.ts)_

## `oclif-demo hello [FILE]`

describe the command here

```
USAGE
  $ oclif-demo hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ test-npm-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/AlexJeffcott/oclif-demo/blob/v1.0.0/src/commands/hello.ts)_

## `oclif-demo help [COMMAND]`

display help for oclif-demo

```
USAGE
  $ oclif-demo help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
