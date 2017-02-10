# README.md
# Ansible Role: subscription-mananager 1.0

This role is able to register/unregister hosts against katello/Satellite6 server

## Requirements

This role requires Ansible 1.9 or higher, and platform requirements are listed in the metadata file.

## Role Variables

Available variables are listed below, along with default values:

## Activate/deactivate functions
	unregister: false
	register_host: false
	manage_repo: false
	satellite_organization : organization_example
	capsule: satellite6.example.com
	state: disable
	LifeCicle: dev

## Dependencies
There is no dependencies with other roles.

## Examples Playbook
1. Register a host against a satellite6 server.

## License
GPLv3
