# Ansible role: java
Installs openjdk.

## Requirements
None.

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|java_packages|Array||see `defaults/main.yml`|

## Dependencies
None.

## Example playbook

```yaml
- hosts: all
  roles:
    - { role: java }
```
