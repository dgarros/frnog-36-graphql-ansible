
THis project is a simple demo to showcase how to use consume data with GraphQL from Ansible for Network Automation

This demo was initially prepared for FRNOG 36 on September 16th 2022 in Paris.


# Installation

```
poetry install
ansible-galaxy collection install networktocode.nautobot
```

# Execute

The example playbook should execute out of the box with the following command.

```
poetry run ansible-playbook pb.generate_config.yml
```

