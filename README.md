# AWS EFS

* OS: Ubuntu 16.04+

Mount an AWS EFS volume on a linux machine using AWS-EFS tools

>`efs_variables` is a dict containing variables used in the role

|Name|Description|
|:-:|:-:|
|profile|an AWS profile to use for authentication `~/.aws/config`|
|region|AWS Region for querying AWS EFS or manual configuration|
|name|the volume name|
|mnt_path|mount point such as `/mnt/app_data`|
|file_system_id|AWS EFS filesystem id|
|tags|AWS EFS tags defined as a dictionary of key-values|

>[futher info](https://docs.ansible.com/ansible/latest/modules/efs_facts_module.html)


**This is a quick and dirty role to do a very simple and specific thing**