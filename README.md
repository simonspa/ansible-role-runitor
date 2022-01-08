Ansibel Role: Runitor
=========

Downloads, verifies and installs `runitor`, a tool to run commands and ping [healthchecks.io](https://healthchecks.io)-like services.

Role Variables
--------------

* `runitor_repository: "bdd/runitor"` - source repository of runitor, defaults to the main repository
* `runitor_release: "latest"` - release version to be installed. Defaults to `latest`, always installing the latest version of the tool. Can be set to `latest` or any other tag of the repository.

License
-------

BSD
