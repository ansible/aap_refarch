# aap_refarch
## Automation Platform Reference Architecture

The files found within this repository are supplemental to the Deploying Ansible Automation Platform 2.1 Reference Architecture. 

The purpose of these files is to provide a method that when the _group_vars/all.yml_ is modified and updated to the repository, this will kick off a job template within your Ansible Automation Platform automation controller cluster to make the appropriate change or update as described within the reference architecture.

NOTE: It is recommended to create multiple _yml_ files within the _group_vars_ directory for each type of configuration you are automation. e.g. when creating users, _users.yml_

For questions, feedback or concerns send mail to: ansible-feedback@redhat.com
