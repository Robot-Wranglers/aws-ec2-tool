<!--- This is a markdown file.  Comments look like this --->

<table width=100%>
  <tr>
    <td colspan=2><strong>
    aws-ec2-tool
      </strong>&nbsp;&nbsp;&nbsp;&nbsp;
      <small><small>
      </small></small>
    </td>
  </tr>
  <tr>
    <td width=15%><img src=img/icon.png style="width:150px"></td>
    <td>
    Toolbox for working with EC2.  Includes:
      hop: a CLI for SSHing to EC2 using SSM-backed keys
    <br/><br/>
    <a href=https://pypi.python.org/pypi/aws-ec2-tool/><img src="https://img.shields.io/pypi/l/aws-ec2-tool.svg"></a>
    <a href=https://pypi.python.org/pypi/aws-ec2-tool/><img src="https://badge.fury.io/py/aws-ec2-tool.svg"></a>
    <a href="https://github.com/elo-enterprises/aws-ec2-tool/actions/workflows/python-test.yml"><img src="https://github.com/elo-enterprises/aws-ec2-tool/actions/workflows/python-test.yml/badge.svg"></a>
    </td>
  </tr>
</table>

  * [Overview](#overview)
  * [Installation](#installation)
  * [Usage](#usage)


---------------------------------------------------------------------------------

## Overview

The [AWS hop Parameter-Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html) is great, but can be awkward to work with via the `awscli` tool.  This project provides the `hop` tool as an alternative interface with simple CRUD.

See [setup.cfg](setup.cfg) to find the latest info about required versions of boto.

See the [Usage section](#usage) for more details

---------------------------------------------------------------------------------

## Installation

See [pypi](https://pypi.org/project/aws-aws-ec2-tool/) for available releases.

```
pip install aws-aws-ec2-tool
```

---------------------------------------------------------------------------------

## Usage

After installation, you can invoke this tool as either `hop` or `python -m hop`.

Usage info follows:

```
$ hop --help

Usage: hop [OPTIONS] COMMAND [ARGS]...

  Tool for accessing secrets

Options:
  --help  Show this message and exit.

Commands:
  copy       copy a secret
  delete     delete secret (keeping a local-backup is default)
  get-many   get many secrets from hierarchy/namespace
  list       list prefixes below the given path
  move       move a secret
  move-many  move a whole path of secrets
  put-many   put many secrets
  read       get a secret
  update     put a secret
  cp         ALIAS for `copy`
  get        ALIAS for `read`
  get-path   ALIAS for `get-many`
  ls         ALIAS for `list`
  move-path  ALIAS for `move-many`
  mv         ALIAS for `move`
  mv-many    ALIAS for `move-many`
  mv-path    ALIAS for `move-many`
  put        ALIAS for `update`
  put-path   ALIAS for `put-many`
  rm         ALIAS for `delete`
  set        ALIAS for `update`
```

---------------------------------------------------------------------------------
