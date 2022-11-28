## **Use of Ansible to build and deploy docker container on Linux server**

**To run the playbook it is necessary to define variables `image_name`, `container_name` and `var_port`**

## Example of the command to run the playbook 

```
 ansible-playbook playbook.yml -e "image_name=test_name container_name=test_container var_port=8080"
```
