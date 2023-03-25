# homelab-ansible

This Repository attempts to centralize all my homelabs configuration.

## How to apply this in my own environment?

All roles and playbooks are made in a way which should make them easy for you to to reuse.

Configuration files which contain _private_ information (eg. passwords, etc.) have been removed, instead you find the same files in a dummy version which you recognize by the `.example` file extension.

## TODOS:

- a lot of refactoring
- more roles (the list I have in mind gets larger continously)
- simplification of the dataflow (eg. automatic creation of a suiting guest in proxmox if not already done)
