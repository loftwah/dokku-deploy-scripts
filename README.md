# dokku-deploy-scripts

Scripts hooks to support deployments.

## Requirements

- dokku 0.19.13+

## Installation

```shell
$ dokku plugin:install https://github.com/decentral1se/dokku-deploy-scripts.git deploy-scripts
```

## Usage

This plugin provides hooks:

* `pre-deploy`: Execute script on dokku host before deploy
* `post-deploy`: Execute script on dokku host after deploy

The files have strict naming conventions.

* `pre-deploy`: Must be called `predeploy.sh`.
* `post-deploy`: Must be called `postdeploy.sh`.
