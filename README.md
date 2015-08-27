#Usage

Clone this repository and run the following command:

ansible-playbook -i inventory roles.yml -u root

This may ask for your password which you should enter:

Once you have entered these, it should install run and install all the roles. 


#Errors...

If you get an error then follow these steps:

1) 'cd /etc/ansible'

2) 'sudo nano hosts'

3) Once in the 'hosts' file, comment any hosts out as this will cause the problem.

You should now be good so run the command again...

###ansible-playbook -i inventory roles.yml -u root
