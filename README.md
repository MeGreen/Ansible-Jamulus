# Monitoring via Ansible


This playbook can deploy a jamulus server "easyly"

# Usage

Install everything with

```shell
ansible-playbook -i inventory/hosts setup.yml --tags=all -K
```

# Restore

When you somehow lost your vars file (that is not under version control) you can find it under `/monitoring/vars.yml`. on the server.
You can deactivate this behaviour by setting `vars_yml_snapshotting_enabled: false`
