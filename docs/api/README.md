## API for 'aws-ec2-tool' package

---------------------------------------------------------------------------------------------------------------------------------------------------------------
### hop
* **Overview:**  [source code](/src/hop/__init__.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Names:** (5 total)::
  *  *abcs*, *util*, *bin*, *cli*, *api*
-------------------------------------------------------------------------------
### hop.abcs
* **Overview:**  [source code](/src/hop/abcs/__init__.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Names:** (0 total)::
  * 
-------------------------------------------------------------------------------
### hop.util
* **Overview:**  [source code](/src/hop/util/__init__.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Functions:** (2 total)
  * [`hop.util.first`](/src/hop/util/__init__.py#L9-L14) with signature `(*items)`
  * [`hop.util.tags_list_to_dict`](/src/hop/util/__init__.py#L17-L21) with signature `(tags: list) -> dict`
-------------------------------------------------------------------------------
### hop.bin
* **Overview:**  [source code](/src/hop/bin/__init__.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Names:** (1 total)::
  *  *hop*
-------------------------------------------------------------------------------
### hop.bin.hop
* **Overview:**  [source code](/src/hop/bin/hop.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Functions:** (1 total)
  * [`hop.bin.hop.entry`](/src/hop/bin/hop.py#L11-L58) with signature `(*args: Any, **kwargs: Any) -> Any`
-------------------------------------------------------------------------------
### hop.cli
* **Overview:**  [source code](/src/hop/cli/__init__.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Names:** (3 total)::
  *  *click*, *Group*, *options*
-------------------------------------------------------------------------------
### hop.cli.options
* **Overview:**  [source code](/src/hop/cli/options.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Names:** (9 total)::
  *  *click*, *profile*, *required_key*, *optional_user*, *user*, *required_user*, *command*, *required_command*, *script*
-------------------------------------------------------------------------------
### hop.api
* **Overview:**  [source code](/src/hop/api/__init__.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Functions:** (7 total)
  * [`hop.api._get_handle`](/src/hop/api/__init__.py#L24-L34) with signature ``
  * [`hop.api.find_secrets`](/src/hop/api/__init__.py#L138-L305)
    * with signature `(dns=None, instance_id=None, secret_path=None, ami_id=None, env=None, user=None, aslib=None, **kwargs)`
    * with admonitions:  [🐉 Complex](/src/hop/api/__init__.py#L1 "score 25 / 7") 
  * [`hop.api.give_up`](/src/hop/api/__init__.py#L51-L54) with signature `(err='Giving up, could not figure out how to hop')`
  * [`hop.api.hop`](/src/hop/api/__init__.py#L60-L108)
    * with signature `(identifier=None, command=None, key=None, debug=False, env=None, aslib=False, user=None, **kwargs)`
  * [`hop.api.hop_connect`](/src/hop/api/__init__.py#L308-L350)
    * with signature `(command='', secret_path=None, ssh_user=None, dns=None, secret_name=None, aslib=None, **kwargs)`
  * [`hop.api.hop_partial`](/src/hop/api/__init__.py#L111-L135) with signature `(aslib, **kwargs)`
  * [`hop.api.resolve_user`](/src/hop/api/__init__.py#L37-L48) with signature `(user=None, env=None, instance=None)`
-------------------------------------------------------------------------------
### hop.api.environment
* **Overview:**  [source code](/src/hop/api/environment.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Classes:** (1 total)
  * [`hop.api.environment.Environment`](/src/hop/api/environment.py#L16-L114)
    * with bases ([Environment](#ssmapienvironment),)
    * with properties: (11 total)
      *  [`account_alias`](/src/hop/api/environment.py#L62) -> inspect._empty
      *  [`account_aliases`](/src/hop/api/environment.py#L56) -> inspect._empty
      *  [`account_id`](/src/hop/api/environment.py#L71) -> inspect._empty
      *  [`caller_id`](/src/hop/api/environment.py#L67) -> inspect._empty
      *  [`profile`](/src/hop/api/environment.py#L47) -> inspect._empty
      *  [`profile_name`](/src/hop/api/environment.py#L47) -> inspect._empty
      *  [`region`](/src/hop/api/environment.py#L75) -> inspect._empty
      *  [`region_name`](/src/hop/api/environment.py#L75) -> inspect._empty
      *  [`role_names`](/src/hop/api/environment.py#L128) -> inspect._empty
      *  [`secrets`](/src/hop/api/environment.py#L162) -> inspect._empty
      *  [`user_names`](/src/hop/api/environment.py#L122) -> inspect._empty
-------------------------------------------------------------------------------
### hop.api.manager
* **Overview:**  [source code](/src/hop/api/manager.py), [unit tests](/tests/units/), [integration tests](/tests/integrations/)
* **Names:** (0 total)::
  * 
