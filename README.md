# Deploy Gluster FS
# How to
- Update bellow match with your requirement
```
# Gluster configure
gluster_brick_dir: /data
gluster_brick_name: datashared
gluster_client_mount: /gluster/client
```


# Run
```
ansible-playbook --private-key /path/to/key -i inventories/[evn]/hosts gluster.yml