# Ansible Role: Certbot

Deploys and sets up [certbot](https://certbot.eff.org/), including automated renewal and file system permissions.

## Requirements

None.

## Role Variables

None.

## Dependencies

For automated renewal to work by default, this assumes you have nginx set up
correctly. See my [nginx role](https://github.com/zaszi/ansible-role-nginx/).

## Example Playbook

    - hosts: all
      become: true
      roles:
         - ansible-role-certbot

## License

Ansible-role-certbot is licensed under the [MIT license](https://github.com/zaszi/ansible-role-certbot/blob/master/LICENSE.md).
