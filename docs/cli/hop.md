
[tooltip-module-entrypoints]: ## "Module Entrypoints"
[tooltip-package-entrypoints]: ## "Console Script Entrypoint"

[Docs](../) *↔* [CLI](README.md) *↔* [Console Scripts](README.md#console-scripts) *↔* **Module Entrypoints**

---------------------------------------------------


## [**ℳ**][tooltip-module-entrypoints] hop

[**[Module]**](README.md#module-entrypoints) `hop` publishes a command line interface (*[source](/src/hop/__main__.py)*).

Example usage:

```bash
$ python -mhop --help

Usage: python -m hop [OPTIONS] [COMMAND]... ANY_ID

  Tool for SSH'ing in to EC2 with SSM-backed keys

Options:
  -s, --ssm-prefix TEXT  default SSM prefix to use for key-search
  -l, --list-only        list instances
  --profile TEXT         AWS profile to use
  -s, --script TEXT      Script to run
  --user TEXT            username (default will attempt auto-detect)
  --help                 Show this message and exit.
```