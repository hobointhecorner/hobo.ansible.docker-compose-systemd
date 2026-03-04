# Docker Compose Systemd Ansible Role

Check out [argument_specs.yml](./meta/argument_specs.yml) for usage info.

Additional configuration options are available for roles included in this repo, check out [requirements.yml](./meta/requirements.yml) for repo links and versions in use.

## Installation
[Ansible Galaxy](https://galaxy.ansible.com/docs/using/installing.html) can be used to install the role:

`ansible-galaxy install git+https://github.com/hobointhecorner/hobo.ansible.nginx.git[,<branch, tag, or commit SHA>]`

Or by adding the following to a role's `dependencies` block in `meta/main.yml` or `roles` block in a `requirements.yml` file:
```
- src: git+git@github.com:hobointhecorner/hobo.ansible.service_user.git
  version: v1
  name: hobo.service_user
  service_user_name: example_user
```
