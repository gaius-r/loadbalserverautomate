# serverdeploy
Automating Load Balanced Server deployment using Ansible


### After cloning make the following changes (REQUIRED)

* update the `aws_access_key` and `aws_secret_key` values in `inventory/aws_ec2.yml` and `/roles/serverdeploy/vars/main.yml`
* A private key file from AWS is required so create one and keep it on ur controller node and provide the path of that private key file in the `ansible.cfg` file under `private_key_file`
