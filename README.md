# K8S-Ansible


The installation will be based on this link :https://dnaeon.github.io/install-and-configure-k8s-on-arch-linux/




Actions:

Create a the ansible host or install ansible on mac


Requirements

The cluster will be consist from one LB and 2 nodes
The swap is disabled on vms.

1. prepare the vms. assign static ip
2. edit the variables file and add the static ips of our servers
3. create ssh key for ansible to access the vms
4. start build the nodes

