# RabbitMQ Cluster

Installing packages and configuring the cluster

``` 
ansible-playbook -i rabbitmq-nodes -u ${var.ansible_user} --private-key ${var.private_key} main.yml
``` 

Creating users, vhosts and policies

``` 
ansible-playbook -i rabbitmq-nodes -u ${var.ansible_user} --private-key ${var.private_key} rabbitmq-users.yml
```
