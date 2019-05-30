# ansible-role-ncats-webui #

[![Build Status](https://travis-ci.com/cisagov/ansible-role-ncats-webui.svg?branch=develop)](https://travis-ci.com/cisagov/ansible-role-ncats-webui)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/cisagov/ansible-role-ncats-webui.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/cisagov/ansible-role-ncats-webui/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/cisagov/ansible-role-ncats-webui.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/cisagov/ansible-role-ncats-webui/context:python)

An Ansible role for installing
[jsf9k/ncats-webui](https://github.com/jsf9k/ncats-webui).

## Requirements ##

None.

## Role Variables ##

None.

## Dependencies ##

None.

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: all
  become: yes
  become_method: sudo
  roles:
    - ncats_webui
```

## Contributing ##

We welcome contributions!  Please see [here](CONTRIBUTING.md) for
details.

## License ##

This project is in the worldwide [public domain](LICENSE.md).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.

## Author Information ##

Shane Frasier - <jeremy.frasier@trio.dhs.gov>
