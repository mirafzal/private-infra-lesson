# private-infra-lesson

Install essential-tools
```
ansible-playbook -i inventory.ini initial-setup.yaml
```

---

Install Harbor
```
ansible-playbook -i inventory.ini harbor-install.yaml -e @harbor-secret-vars.yaml
```