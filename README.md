Ansible Dadi
=========

Role to configure and install dependencies for dadi-cli onto an Ubuntu instance

Requirements
------------


Role Variables
--------------
Variable Name | Default value if not defined | Description
------------- | ---------------------- | -----------
DADI_USER | dadi | the username to install dadi (note, some clouds will install under a separate user)
DADI_CLI_REPO | "https://github.com/xin-huang/dadi-cli" | repo to download dadi cli
DADI_CLI_REPO_VERSION | master | branch to use
DADI_ENABLE_AUTO_CLI | "false" | if true, run dadi-cli automatically
DADI_CLI_PARAMETERS | "" | if set, will pass parameters into the cli
DADI_CLI_USE_WORKQUEUE | "false" | if true, use workqueue when running dadi-cli automatically
DADI_ENABLE_WORKQUEUE_FACTORY | "false" | if true, run workqueue_factory automatically
DADI_WORKQUEUE_PASSWORD | none | workqueue password
DADI_PROJECT_NAME | "" | required if DADI_ENABLE_AUTO_CLI or DADI_ENABLE_WORKQUEUE_FACTORY is true

Dependencies
------------

Example Playbook
----------------

example-playbook.yml

License
-------

Apache License

Author Information
------------------


