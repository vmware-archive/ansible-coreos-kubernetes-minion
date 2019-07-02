CoreOS Kubernetes Minions
=========================

current version: 0.1.0
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

This code is Dual Licensed MIT or GPLv3
