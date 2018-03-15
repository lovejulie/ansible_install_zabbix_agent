Install zabbix 3.4 agent for CentOS and Ubuntu
=
Auth Method : ssh password
-
CentOS : root <br>
Ubuntu : ubuntu 

Support OS :
-
CentOS6,7 and Ubuntu16

How to execute :
-
```
ansible-playbook install_zabbix_agent.yml --limit zabbix-client
```

Remember to change hosts file for your agent IP
