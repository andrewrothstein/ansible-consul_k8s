andrewrothstein.consul_k8s
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-consul_k8s.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-consul_k8s)

Installs [consul-k8s](https://www.consul.io/docs/platform/k8s/run.html)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.consul_k8s
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
