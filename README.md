## Ansible Homework

This repository contains an empty ansible role skeleton with additions of molecule and github actions.

> If you are not familiar with ansible testing with molecule, please first read the below: https://github.com/geerlingguy/molecule-playbook-testing.

## TODO

* Fork this Ansible role to your github account (If you don't have one, make sure to create a new github user).
* Update the role and add logic that installs the latest mainline (1.19.9) version of `nginx` on CentOS 7 and Ubuntu 20.04
* NGINX should provide a webpage with `Hello, World!` welcome message. Please see default `welcome_message` in `defaults/main.yml`
* Provide a way to override the `welcome_message` with `--extra-vars` on execution.
* The role includes Github actions CI that should pass successfully upon homework completion

## Local Testing Requirements

* Linux or Mac (VM/Instance/Desktop)
* Docker
* Ansible
* Molecule with docker driver (see molecule-playbook-testing doc)

To test locally, clone the forked repo and cd into the project folder. Run `molecule test` to test the role.

## Notes

* Molecule will run `molecule/verify.yml` playbook to validate that the webserver is up and running and will look for `Hello, World!` in reponse.

When you are ready to submit the result, please share with me your forked repository.

> If you have any questions or concerns regarding the homework, don’t hesitate to contact me directly either by email or phone.
