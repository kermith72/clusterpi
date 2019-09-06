# clusterpi
Kubernetes deployment by Ansible for a PI 4 cluster

## install cluster

ansible-playbook -i hosts.yml -u pi -b install-kub.yml

## erase Kubernetes

ansible-playbook -i hosts.yml -u pi -b reset-all.yml
