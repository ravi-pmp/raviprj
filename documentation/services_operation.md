## Service Start operation
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

## Service Stop operation
```shell
ansible-playbook -i inventory  services_operation.yml -e \
'{
  "operation":"stop",
  "services": 
  [
    "sdf",
    "WSearch"
  ]
}'
```

## Service restart operation
```shell
ansible-playbook -i inventory  services_operation.yml -e \
'{
  "operation":"restart",
  "services": 
  [
    "sdf",
    "WSearch"
  ]
}'
```