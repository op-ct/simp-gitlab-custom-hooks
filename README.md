# SIMP Custom Gitlab Hooks

This repository contains custom GitLab hooks that can be used for various
configurations and workflow modifications.

## Global hook configuration

The repository uses a global yaml hook configuration file. This can be used to
configure various settings for all of the hooks used on the server side and to
load these settings dynamically.

This file should be saved to /path/to/repository.git/custom_hooks/hooks.yaml

## Installing hooks

For server-side custom hooks (pre-receive, update, post-receive), drop the hook
script into /path/to/repository.git/custom_hooks/{pre-receive,update,post-receive}
on the server itself.

Drop the hook configuration into /path/to/repository.git/custom_hooks/hooks.yaml
