A sample of ansible that creates ec2 instances
===

## Usage

- Set environment variables below on ubuntu that is booted by vagrant for connecting to AWS
  - AWS_ACCESS_KEY_ID
  - AWS_SECRET_ACCESS_KEY
  - AWS_KEYPAIR_NAME
- Run ansible playbook on ubuntu
  - `cd /vagrant/ansible`
  - `ansible-playbook -i hosts ec2.yml`
