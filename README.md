HOWTO
=====

add host to jenkins-server group

launch playbook with

ansible-playbook -vvvvv -i inventory site.yml (-u user -s   -- if root access is disabled)

It injects jjb credential (with pass jjb) to use with jenkins job builder
