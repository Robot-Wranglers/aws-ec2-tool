
[tooltip-package-entrypoints]: ## "Console Script Entrypoint"
[tooltip-module-entrypoints]: ## "Module Entrypoint"

[Docs](../) *↔* [CLI](README.md) *↔* Console Scripts *↔* [Module Entrypoints](README.md#module-entrypoints)

---------------------------------------------------







## [**℮**][tooltip-package-entrypoints] hop

Module [*hop.bin.hop.entry*](/src/hop/bin/hop.py) publishes a CLI named `hop` via a [console script](https://python-packaging.readthedocs.io/en/latest/command-line-scripts.html#the-console-scripts-entry-point). (*[source](/src/hop/bin/hop.py)*)

**Example usage:**

```bash
$ hop --help

Usage: hop [OPTIONS] IDENTIFIER [COMMAND]...

  Tool for SSH'ing in to EC2 with SSM-backed keys.

  Example usage:

      hop <instance_id>     hop <reservation_id>     hop <instance_name>
      hop <ip_address>

Options:
  -s, --ssm-prefix TEXT  default SSM prefix to use for key-search
  -l, --list-only        list instances
  --profile TEXT         AWS profile to use
  -s, --script TEXT      Script to run
  --user TEXT            username (default will attempt auto-detect)
  --help                 Show this message and exit.
```
