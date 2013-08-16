# Linux Administration
<br />

## __User management__

To add a new user, you can user useradd, but adduser seems to be more straightforward.  
http://www.linfo.org/useradd.html  
https://www.digitalocean.com/community/articles/how-to-add-and-delete-users-on-ubuntu-12-04-and-centos-6  
http://www.howtogeek.com/howto/ubuntu/add-a-user-on-ubuntu-server/  
This article has some information on configuring the sudoers file among other things:  
http://thekeesh.com/2011/05/setting-up-user-accounts-password-authentication-and-ssh-keys-on-a-new-ec2-instance/  
How to identify what shell each user is using:  
http://www.unix.com/unix-dummies-questions-answers/1317-shell-am-i-using.html  
`cat /etc/passwd` prints a list of users:  
http://www.linuxquestions.org/questions/linux-newbie-8/what-is-the-command-to-list-users-367164/  
`gksudo gedit /etc/hostname` and `gksudo gedit /etc/hosts` to edit the system name:  
http://askubuntu.com/questions/206698/changing-system-name  

