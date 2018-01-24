# Ansible Role: aws-cli

Ansible Role to install and configure aws-cli.


## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`).
You can overload the variables by creating a dictionary called "awscli", ex:

    awscli:
      output: "json"


## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.aws-cli

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Apollo Clark](https://www.apolloclark.com/)
