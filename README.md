# orkjern-security-ansible

## Installation

No special installation required?

## Usage

Run with

```
$ ansible-playbook -i <inv.file> -l hostname -b provisioning/playbook.yml
```

The inv.file should look something like this:

```
my_hostname ansible_host=my_ssh_alias
```