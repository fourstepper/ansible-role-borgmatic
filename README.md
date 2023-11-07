# ansible-role-borgmatic

An alternative, simple role that works as an alternative to https://github.com/borgbase/ansible-role-borgbackup

Differences to the above-mentioned role:

- Is fundamentally simpler
- Supports multiple repositories with different settings
- ~~Works on MacOS as well~~ This isn't and
  [seems like it won't be](https://projects.torsion.org/borgmatic-collective/borgmatic/issues/293)
  the case anytime soon

## Role Variables

Best to check out `defaults/main.yaml`

## How to run

The role expects to find either one or more borgmatic configuration files
in `"{{ playbook_dir }}/files/borgmatic/*.yaml"`

## License

MIT

## Author Information

Robin Opletal

https://robinopletal.com
