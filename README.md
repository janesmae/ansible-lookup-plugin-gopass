# Ansible lookup plugin for gopass

A plugin to make secrets from gopass available within the ansible playbooks.

## Prerequisites

[gopass](https://www.gopass.pw) installed and working on the system

## Examples

```yml
- debug:
    msg: "{{ lookup('gopass', 'path/to/my/secret')}}"
```

## Authors

Jaan Janesmae

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

