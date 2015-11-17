CoreOS Kubernetes Minions
=========================

current version: 0.0.1
A role to manage Kubernetes minions in a CoreOS cluster

Role Variables
--------------

Example Playbook
----------------

    - name: kubernetes minions
      hosts: kubernetes-minions
      roles:
        - role: "sigma.coreos-kubernetes-minion"

License
-------

MIT
