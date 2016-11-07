Ansible commands
---------------

**Install ansible on OS**

~~~~~
$ brew install ansible
$ brew install ssh-copy-id
~~~~~~

**Generate private key**
~~~~
$ ssh-keygen
~~~~

**Install private key**
~~~~~~
$ ssh-copy-id -i ~/.ssh/id_rsa.pub <user>@<server_ip>
~~~~~~~

**Execute a playbook**
~~~~~~
$ ansible-playbook playbook.yml
~~~~~~~

**configure your ansible host (only OS): **
~~~~~~
/etc/ansible/hosts
~~~~~~

**Verify server conectivity**
~~~~~~
$ ansible [host] -m ping -u devops
~~~~~~

**NOTE:**
- We need a sudoer user

Nginx Config
------------

**Generate nginx basic auth (optional)**

~~~~~~
$ sudo sh -c "echo -n 'developer:' >> /etc/nginx/.htpasswd"
$ sudo sh -c "openssl passwd mysuperpass >> /etc/nginx/.htpasswd"
~~~~~~

**uncomment in default.conf the basic auth**