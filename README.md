[![Build Status](https://travis-ci.org/wtanaka/ansible-role-flowblade.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-flowblade)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-flowblade.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-flowblade)

wtanaka.flowblade
=================

This ansible role installs the flowblade non-linear multitrack video
editor.

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.flowblade

### `flowblade_should_shortcircuit`

Default: True

When `True`, this role short-circuits itself if a `flowblade` is
already in the `PATH`.

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
