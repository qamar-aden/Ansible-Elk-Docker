## Ansible-Docker-Elk

This is an ansible playbook for the latest version of the ELK Stack. The ELK Stack is deployed as seperate docker containers.

To run playbook:

``` pip install docker-py ```

``` docker network create elk ```

``` ansible-playbook elk.yml ```

To run only one role:

``` ansible-playbook elk.yml --tags elasticsearch```

To remove all containers:

``` ansible-playbook elk-clean.yml ```
