# Edon's Templates

Misc templates for different types of projects. These templates use [ffizer](https://github.com/ffizer/ffizer).

## Usage

```shell
% ffizer apply --source <TEMPLATE_PATH> --destination <DESTINATION_PATH>
```

```shell
% ffizer apply --help

Apply a template into a target directory

Usage: ffizer apply [OPTIONS] --source <URI> --destination <FOLDER>

Options:
      --confirm <CONFIRM>          ask for plan confirmation [default: Never] [possible values: auto, always, never]
      --update-mode <UPDATE_MODE>  mode to update existing file [default: Ask] [possible values: ask, keep, override, update-as-remote, current-as-local, show-diff, merge]
  -y, --no-interaction             should not ask for confirmation (to use default value, to apply plan, to override, to run script,...)
      --offline                    in offline, only local templates or cached templates are used
  -s, --source <URI>               uri / path of the template
      --rev <REV>                  git revision of the template [default: master]
      --source-subfolder <FOLDER>  path of the folder under the source uri to use for template
  -d, --destination <FOLDER>       destination folder (created if doesn't exist)
  -v, --variables <KEY_VALUE>      set variable's value from cli ("key=value")
  -h, --help                       Print help information
  -V, --version                    Print version information
```

## Templates

- Generic Node package
- [NPM package for OpenAPI spec](./openapi-npm/)
