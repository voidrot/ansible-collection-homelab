# Ansible Collection - voidrot.homelab

Documentation for the collection.
## Bootstrap

```ansible
# site.yml
- name: Bootstrap Hosts
  ansible.builtin.import_playbook: voidrot.homelab.bootstrap
```

```bash
ansible-playbook bootstrap -i hosts.yml site.yml -u remote_username ...
```