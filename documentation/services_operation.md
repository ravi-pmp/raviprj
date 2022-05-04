# Service Start operation
```shell
ansible-playbook -i inventory  services_operation.yml -e \
'{
  "operation":"start",
  "services": 
  [
    "sdf",
    "WSearch"
  ]
}'
```