# Convert qcow2 image to OVA for PowerVS

This playbook convert a qcow2 image into a required sized ova image

Playbook assume following:
1. Given input image is qcow2
2. Target machine has enough disk space to contain the intermediate images
3. Target machine has required commands like, qemu-img, gzip etc


# Using playbook

1. Update vars/main.yaml with the URL/FILE etc
2. Run the playbook
    `ansible-playbook tasks/main.yml`