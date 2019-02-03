# Ansible Role: Patching

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
patching_reboot_server: False
```

Reboot of the server is the most important variable to set. If you don't want the server to reboot leave it alone. If you want the server to reboot you need to change this variable.

```yaml
patching_upgrade_all: False
patching_repo_clean: True
```

By default update will always run. If you want to run a upgrade changing the variable will disable update and run upgrade. `patching_repo_clean` is going to clean up old files off your server.

```yaml
patching_update_security: False
```

