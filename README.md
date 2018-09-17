# Openscap client configuration Role

## About

Role created to configure a client to execute openscap policies based on the information obtained from a Red Hat Satellite/Foreman Host.

Steps and configuration changes obtained from the [foreman_scap_client puppet module](https://github.com/theforeman/puppet-foreman_scap_client)

The role has to be executed with root permission, using the root user or via sudo because it will modify system parameters.

## Ansible Requirements

RPM Repositories have to be enabled and containing required packages.

## Configuration parameters

### Required vars to be overwritten

- `foreman_proxy_server`: Used to obtain policy parameters
- `satellite_username`: Used to obtain policy parameters
- `satellite_password`: Used to obtain policy parameters

