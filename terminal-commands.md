# Linux Terminal Command Reference
<br />

## __dh__

__Prints the total size, in human readable format, of all the files, including files in subdirectories__  
`du -ch | grep total`

Additional References:  
http://www.codecoffee.com/tipsforlinux/articles/22.html

## __grep__

__Search all files in the current directory recursively, ignoring case, and print matching files names__  
`grep -irl *`

## __lsb_release__

__Prints general distro information, including version__  
`lsb_release -a`

## __scp__

__Copy files to remote home directory over ssh__  
`scp -r ./folderwithfilesinit brandon@sshhost.net:~/`

Additional References:  
http://www.howtogeek.com/66776/how-to-remotely-copy-files-over-ssh-without-entering-your-password/

## __sed__

__Print lines 5 through 20__  
`sed -n "5,20p" file.txt`

Additional References:  
http://www.commandlinefu.com/commands/view/9380/to-print-a-specific-line-from-a-file

## __ssh__

__Verbose option to view authentication process for debugging__  
`ssh -v brandon@sshhost.net`

Additional References:  
http://serverfault.com/questions/39733/why-do-i-get-permission-denied-publickey-when-trying-to-ssh-from-local-ubunt

## __sudo__

__Loads login specific files of the user specified before command execution, the user being root in this case__  
`sudo -i command`

Additional References:  
http://askubuntu.com/questions/100146/roots-bashrc-not-executing-on-sudo-i

## __uname__

__Prints processor architecture__  
`uname -m`

__Prints linux kernel version__  
`uname -r`

Additional References:  
http://www.linuxquestions.org/questions/linux-general-1/how-to-check-linux-kernel-is-32-bit-or-64-bit-612352/

