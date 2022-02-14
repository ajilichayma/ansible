# Ansible
Notes written while starting learning ansible

## Ansible playbook 
- It is a list of dictionaries in yaml's terms
- Each play is a dictionary and has a set of properties called; name, host and tasks.
- The task is a list(so the position of entries matter, because lists are ordered collections)
- Remark: the order does not really matter in the yaml playbook because it is a list of dictionaries.
- PS: we should ensure that the host is defined in the inventory file because all connection information for the host is retrieved from the inventory file.

## Modules 
- The different tasks run by a task are called modules
