# ansible-vmware
Để chạy ansible cho create snap.

ansible-playbook vcenter.yaml --tags create-vm-resource

Để chạy ansible cho restore  snap.

ansible-playbook vcenter.yaml --tags restore-resource-last
