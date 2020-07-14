# Use Ansible and CloudFormation to Configure CloudOut to AWS S3

This repo contains an example Ansible playbook, which can be used to deploy the [AWS CloudFormation template for Rubrik CloudOut](https://github.com/rubrikinc/use-case-aws-cloudformation-template-cloudout-s3), and configure a corresponding Archive Location on your Rubrik cluster.

## :white_check_mark: Prerequisites

There are a few software packages you'll need in order to get this project off the ground:

* [Python](https://www.python.org/)
* [Rubrik SDK for Python](https://github.com/rubrikinc/rubrik-sdk-for-python)
* [Red Hat Ansible](https://www.ansible.com/)
* [Rubrik Modules for Ansible](https://github.com/rubrikinc/rubrik-modules-for-ansible)

## :blue_book: How to Use This Project

Configure authentication to both AWS and Rubrik based on their Ansible module documentation. Modify the `cloudout_cloudformation.yaml` file to customize it for your environment, and run the playbook.

## :pushpin: License

* [MIT License](LICENSE)
