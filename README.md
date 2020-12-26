# ansible_mysql_keepalived


## Usageu
Master to Master semi sync deployment 
```shell
 ansible-playbook -i host.yaml site.yaml  -e @vars/variables.yaml
```

## Test 
```shell
python3 -m pip install --user "molecule[docker,lint]"
cd roles/test
molecule converged
```