Ansible Script to manage Proxmox VMs.  Followed directions from:  https://www.youtube.com/watch?v=4G9d5COhOvI

My VAR files have been added to .gitignore.  You need to create a vars folder in the root directory with these files:
api-key.yaml, vars.yaml, and ssh-key.yaml and preferably encrypt the keys.

VARS are:
1. api-key.yaml
      api_key: "keytotheproxmoxapikey"
3. vars.yaml
      api_user: ansible@pam
      node: proxmox
      storage: local-zfs
2. ssh-key.yaml
      ssh-key: "addsshkeyhere4ansibleuserifyoucreateit"
