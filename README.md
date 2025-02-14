Before Running [install ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html) for ubuntu:

```
  sudo apt update
  sudo apt install software-properties-common
  sudo add-apt-repository --yes --update ppa:ansible/ansible
  sudo apt install ansible
```

To install user environment packages run bootstrap with:
```
ansible-playbook -i inv/hosts bootstrap.yml
```
