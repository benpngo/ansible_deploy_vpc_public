# ansible_vpc_deploy
AWS deployment of a basic VPC


Folder AWS contains all the VPC tasks and variables to deploy a VPC with subnets, ACL rules, security groups and networking routes

Ensure your environment variables contain the access credentials for your AWS account, see guide for reference

http://docs.ansible.com/ansible/latest/scenario_guides/guide_aws.html

To configure how you want the VPS to look like alter the vars file in aws/vars/main.yml

To deploy the VPC run

```bash
ansible-playbook main_vpc.yml
```

