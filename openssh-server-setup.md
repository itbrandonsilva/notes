# Linux OpenSSH Server Setup
<br />

## __Initial Setup__

This is generally enough to get started:  
https://help.ubuntu.com/community/SSH?action=show&redirect=SSH%2FOpenSSH

## __Troubleshooting__

The `"Agent admitted failure to sign"` error is most likely solved by ensuring the ssh keys are loaded on both the server side and client side:  
`ssh-add`  
for ssh keys that don't have the default filename:  
`ssh-add ~/.ssh/my_other_key`  
https://help.github.com/articles/error-agent-admitted-failure-to-sign

Be sure the files in `~/.ssh` have the correct permissions:  
`chmod 700 ~/.ssh`  
`cd ~/.ssh`  
`chmod 600 *`  
http://stackoverflow.com/questions/9270734/ssh-permisssions-are-too-open-error  
http://bodhizazen.net/Tutorials/SSH_keys  
http://superuser.com/questions/215504/permissions-on-private-key-in-ssh-folder

Using Putty keys:  
http://stackoverflow.com/questions/2224066/how-to-convert-ssh-keypairs-generated-using-puttygenwindows-into-key-pairs-use
