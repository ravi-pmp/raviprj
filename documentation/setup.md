#Setting up the project

1. Install the collection from downloads folder

```shell
cd <root_folder_project>

cp downloads/* .

ansible-galaxy collection install ansible-utils-2.2.0.tar.gz -p collections

ansible-galaxy collection install community-general-3.7.0.tar.gz -p collections
```