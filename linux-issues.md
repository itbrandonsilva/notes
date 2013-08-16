# Annoying Issues on Linux
<br />

### ***No such file or directory (the file is right there...)***
The executable may not have access to required libraries, especially when the executable is 32 bit and your running 64 bit Ubuntu.  
Running:  
`sudo apt-get install ia32-libs`  
on Ubuntu 12.04LTS indeed installed the libraries that my executable needed when I ran into this problem.
http://superuser.com/questions/344533/no-such-file-or-directory-error-in-bash-but-the-file-exists
