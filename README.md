# Ansible Roles

Collection of tried and tested Ansible roles for Ubuntu Servers.

## Local Setup

Install hostupdater plugin

```
vagrant plugin install vagrant-hostsupdater
```

Update ssh client

```
# For vagrant virtual machines
Host 192.168.33.* *.cluster.dev
 StrictHostKeyChecking no
 UserKnownHostsFile=/dev/null
 User root
 LogLevel ERROR
```

Test

```
$ vagrant up db1
$ ssh db1.cluster.dev
```

