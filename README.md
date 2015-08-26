# Usage

Clone this repository and run the following command:

ansible-playbook -i inventory roles.yml -k -K

This will ask you for two passwords:

1) ssh password - this should be your user password on your local machine
2) SUDO Password - this should be the same as the above

Once you have entered these, it should install NGinx and allow you to customise this further.
