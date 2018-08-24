{{ cookiecutter.role_name | title | replace("-", " ") }}
=========

This is a rule to setup {{ cookiecutter.role_name | title | replace("ansible-", "") | replace("-", " ") }} on a unix system

Requirements
------------

All python requirements are in `requirements.txt`

Role Variables
--------------

All role variables can be found in `defaults/main.yml`

Role Dependencies
------------

All role dependencies can be found in `meta/main.yml`

Test Playbook
----------------

If you want to know what is tested through [molecule](https://molecule.readthedocs.io/en/master/) see:

- `molecule/default/molecule.yml` for OSes we test against
- `molecule/default/playbook.yml` for what is being run in the test
- `molecule/default/tests/test_default.yml` for the [goss](https://goss.rocks) verfier

Contribute
==========

[Tutorial](http://kbroman.github.io/github_tutorial/pages/fork.html)

License and Author
==================

Author:: {{ cookiecutter.author }}

Trustedshops GmbH {{ cookiecutter.license }}
