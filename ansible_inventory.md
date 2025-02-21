ansible is agentless. you need not to install agent on remote machine.
you can have multiple group define in ansible host file
there are following ansible inventory parameter.

### ansible hosts: 
this is ansible inventy paramter to define fully qualifed name of remote host. eg
web ansible_host=server1.company.com
db ansible_host=server2.companyt.com
mail ansible_hosts=server3.company.com
web2 ansible_host=server4.company.com

