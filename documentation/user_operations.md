
#User Operation via excel file
```shell

ansible-playbook -i inventory  user_operation.yml -e \
'{
  "config_type": "users",
  "excel_file_name": "LocalUserOperation.xlsx"
}'
```
