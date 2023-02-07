Role Name
=========

Role to configure and install dependencies for dadi-cli onto an Ubuntu instance

Requirements
------------


Role Variables
--------------
Variable Name | Default value if not defined | Description
------------- | ---------------------- | -----------
DADI_CLI_REPO | "https://github.com/xin-huang/dadi-cli" | repo to download dadi cli
DADI_CLI_REPO_VERSION | master | branch to use
DADI_ENABLE_AUTO_CLI | "false" | if true, run dadi-cli automatically
DADI_CLI_PARAMETERS | "" | if set, will pass parameters into the cli
DADI_ENABLE_WORKQUEUE_FACTORY | "false" | if true, run workqueue_factory automatically
DADI_PROJECT_NAME | "" | required if DADI_ENABLE_AUTO_CLI or DADI_ENABLE_WORKQUEUE_FACTORY is true

Dependencies
------------

Example Playbook
----------------



License
-------

Apache License

Author Information
------------------


