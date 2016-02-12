This repo is an ansible playbook intended to automate the installation of libreNMS on Ubuntu 14.04.


#How to use this playbook

##Assumptions

+ you have a `deploy` remote user, which is sudoer (you can change it in ansible.cfg file)


##Clone this repository

```
$ git clone https://github.com/edelans/...
```

##Generate configuration files based on sample config files

```
$ cp hosts.ini.sample hosts.ini
$ cp group_vars/server.yml.sample group_vars/server.yml
```

##Edit configuration files to your needs
Edit configuration files (`hosts.ini` and `group_vars/server.yml`) with your own configuration.


##Execute the playbook

```
ansible-playbook librenms.yml
```

#Contributing
Issues and PRs wellcome :wink: !
