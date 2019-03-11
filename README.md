# Ansible lookup plugin for gopass

A plugin to make secrets from gopass available within the ansible playbooks.

## Examples

```yml
- debug:
    msg: "{{ lookup('gopass', 'path/to/my/secret')}}"
```
