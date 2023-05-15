oclif-hello-world
=================

oclif example Hello World CLI

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/oclif-hello-world.svg)](https://npmjs.org/package/oclif-hello-world)
[![CircleCI](https://circleci.com/gh/oclif/hello-world/tree/main.svg?style=shield)](https://circleci.com/gh/oclif/hello-world/tree/main)
[![Downloads/week](https://img.shields.io/npm/dw/oclif-hello-world.svg)](https://npmjs.org/package/oclif-hello-world)
[![License](https://img.shields.io/npm/l/oclif-hello-world.svg)](https://github.com/oclif/hello-world/blob/main/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g gitbeaker-error-example
$ gitbeaker-error-example COMMAND
running command...
$ gitbeaker-error-example (--version)
gitbeaker-error-example/0.0.0 linux-x64 node-v18.15.0
$ gitbeaker-error-example --help [COMMAND]
USAGE
  $ gitbeaker-error-example COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`gitbeaker-error-example hello PERSON`](#gitbeaker-error-example-hello-person)
* [`gitbeaker-error-example hello world`](#gitbeaker-error-example-hello-world)
* [`gitbeaker-error-example help [COMMANDS]`](#gitbeaker-error-example-help-commands)
* [`gitbeaker-error-example plugins`](#gitbeaker-error-example-plugins)
* [`gitbeaker-error-example plugins:install PLUGIN...`](#gitbeaker-error-example-pluginsinstall-plugin)
* [`gitbeaker-error-example plugins:inspect PLUGIN...`](#gitbeaker-error-example-pluginsinspect-plugin)
* [`gitbeaker-error-example plugins:install PLUGIN...`](#gitbeaker-error-example-pluginsinstall-plugin-1)
* [`gitbeaker-error-example plugins:link PLUGIN`](#gitbeaker-error-example-pluginslink-plugin)
* [`gitbeaker-error-example plugins:uninstall PLUGIN...`](#gitbeaker-error-example-pluginsuninstall-plugin)
* [`gitbeaker-error-example plugins:uninstall PLUGIN...`](#gitbeaker-error-example-pluginsuninstall-plugin-1)
* [`gitbeaker-error-example plugins:uninstall PLUGIN...`](#gitbeaker-error-example-pluginsuninstall-plugin-2)
* [`gitbeaker-error-example plugins update`](#gitbeaker-error-example-plugins-update)

## `gitbeaker-error-example hello PERSON`

Say hello

```
USAGE
  $ gitbeaker-error-example hello PERSON -f <value>

ARGUMENTS
  PERSON  Person to say hello to

FLAGS
  -f, --from=<value>  (required) Who is saying hello

DESCRIPTION
  Say hello

EXAMPLES
  $ oex hello friend --from oclif
  hello friend from oclif! (./src/commands/hello/index.ts)
```

_See code: [dist/commands/hello/index.ts](https://github.com/merorafael/gitbeaker-error-example/blob/v0.0.0/dist/commands/hello/index.ts)_

## `gitbeaker-error-example hello world`

Say hello world

```
USAGE
  $ gitbeaker-error-example hello world

DESCRIPTION
  Say hello world

EXAMPLES
  $ gitbeaker-error-example hello world
  hello world! (./src/commands/hello/world.ts)
```

## `gitbeaker-error-example help [COMMANDS]`

Display help for gitbeaker-error-example.

```
USAGE
  $ gitbeaker-error-example help [COMMANDS] [-n]

ARGUMENTS
  COMMANDS  Command to show help for.

FLAGS
  -n, --nested-commands  Include all nested commands in the output.

DESCRIPTION
  Display help for gitbeaker-error-example.
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v5.2.9/src/commands/help.ts)_

## `gitbeaker-error-example plugins`

List installed plugins.

```
USAGE
  $ gitbeaker-error-example plugins [--core]

FLAGS
  --core  Show core plugins.

DESCRIPTION
  List installed plugins.

EXAMPLES
  $ gitbeaker-error-example plugins
```

_See code: [@oclif/plugin-plugins](https://github.com/oclif/plugin-plugins/blob/v2.4.7/src/commands/plugins/index.ts)_

## `gitbeaker-error-example plugins:install PLUGIN...`

Installs a plugin into the CLI.

```
USAGE
  $ gitbeaker-error-example plugins:install PLUGIN...

ARGUMENTS
  PLUGIN  Plugin to install.

FLAGS
  -f, --force    Run yarn install with force flag.
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Installs a plugin into the CLI.
  Can be installed from npm or a git url.

  Installation of a user-installed plugin will override a core plugin.

  e.g. If you have a core plugin that has a 'hello' command, installing a user-installed plugin with a 'hello' command
  will override the core plugin implementation. This is useful if a user needs to update core plugin functionality in
  the CLI without the need to patch and update the whole CLI.


ALIASES
  $ gitbeaker-error-example plugins add

EXAMPLES
  $ gitbeaker-error-example plugins:install myplugin 

  $ gitbeaker-error-example plugins:install https://github.com/someuser/someplugin

  $ gitbeaker-error-example plugins:install someuser/someplugin
```

## `gitbeaker-error-example plugins:inspect PLUGIN...`

Displays installation properties of a plugin.

```
USAGE
  $ gitbeaker-error-example plugins:inspect PLUGIN...

ARGUMENTS
  PLUGIN  [default: .] Plugin to inspect.

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  Displays installation properties of a plugin.

EXAMPLES
  $ gitbeaker-error-example plugins:inspect myplugin
```

## `gitbeaker-error-example plugins:install PLUGIN...`

Installs a plugin into the CLI.

```
USAGE
  $ gitbeaker-error-example plugins:install PLUGIN...

ARGUMENTS
  PLUGIN  Plugin to install.

FLAGS
  -f, --force    Run yarn install with force flag.
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Installs a plugin into the CLI.
  Can be installed from npm or a git url.

  Installation of a user-installed plugin will override a core plugin.

  e.g. If you have a core plugin that has a 'hello' command, installing a user-installed plugin with a 'hello' command
  will override the core plugin implementation. This is useful if a user needs to update core plugin functionality in
  the CLI without the need to patch and update the whole CLI.


ALIASES
  $ gitbeaker-error-example plugins add

EXAMPLES
  $ gitbeaker-error-example plugins:install myplugin 

  $ gitbeaker-error-example plugins:install https://github.com/someuser/someplugin

  $ gitbeaker-error-example plugins:install someuser/someplugin
```

## `gitbeaker-error-example plugins:link PLUGIN`

Links a plugin into the CLI for development.

```
USAGE
  $ gitbeaker-error-example plugins:link PLUGIN

ARGUMENTS
  PATH  [default: .] path to plugin

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Links a plugin into the CLI for development.
  Installation of a linked plugin will override a user-installed or core plugin.

  e.g. If you have a user-installed or core plugin that has a 'hello' command, installing a linked plugin with a 'hello'
  command will override the user-installed or core plugin implementation. This is useful for development work.


EXAMPLES
  $ gitbeaker-error-example plugins:link myplugin
```

## `gitbeaker-error-example plugins:uninstall PLUGIN...`

Removes a plugin from the CLI.

```
USAGE
  $ gitbeaker-error-example plugins:uninstall PLUGIN...

ARGUMENTS
  PLUGIN  plugin to uninstall

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Removes a plugin from the CLI.

ALIASES
  $ gitbeaker-error-example plugins unlink
  $ gitbeaker-error-example plugins remove
```

## `gitbeaker-error-example plugins:uninstall PLUGIN...`

Removes a plugin from the CLI.

```
USAGE
  $ gitbeaker-error-example plugins:uninstall PLUGIN...

ARGUMENTS
  PLUGIN  plugin to uninstall

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Removes a plugin from the CLI.

ALIASES
  $ gitbeaker-error-example plugins unlink
  $ gitbeaker-error-example plugins remove
```

## `gitbeaker-error-example plugins:uninstall PLUGIN...`

Removes a plugin from the CLI.

```
USAGE
  $ gitbeaker-error-example plugins:uninstall PLUGIN...

ARGUMENTS
  PLUGIN  plugin to uninstall

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Removes a plugin from the CLI.

ALIASES
  $ gitbeaker-error-example plugins unlink
  $ gitbeaker-error-example plugins remove
```

## `gitbeaker-error-example plugins update`

Update installed plugins.

```
USAGE
  $ gitbeaker-error-example plugins update [-h] [-v]

FLAGS
  -h, --help     Show CLI help.
  -v, --verbose

DESCRIPTION
  Update installed plugins.
```
<!-- commandsstop -->
