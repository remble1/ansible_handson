Check system -> cat /etc/os-release
Install ansible on CentOS Stream

> > sudo yum install ansible -y
> > or
> > sudo dnf intall ansible

ping a inventory

> > ansible -i inventory node01 -m ping -v

to test a command.yml in verbose mode

> > ansible-playbook -i localhost, command.yml -vv
