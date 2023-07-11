Some Commands of linux
1. `ls` - List files and directories
   - Syntax: `ls [options] [directory]`
   - Example: `ls -l /home`

2. `cd` - Change directory
   - Syntax: `cd [directory]`
   - Example: `cd /var/www`

3. `pwd` - Print working directory
   - Syntax: `pwd`

4. `mkdir` - Create a new directory
   - Syntax: `mkdir [directory]`
   - Example: `mkdir documents`

5. `rm` - Remove files and directories
   - Syntax: `rm [options] [file/directory]`
   - Example: `rm file.txt`

6. `cp` - Copy files and directories
   - Syntax: `cp [options] [source] [destination]`
   - Example: `cp file.txt /backup`

7. `mv` - Move/rename files and directories
   - Syntax: `mv [options] [source] [destination]`
   - Example: `mv file.txt newfile.txt`

8. `touch` - Create an empty file
   - Syntax: `touch [file]`
   - Example: `touch newfile.txt`

9. `cat` - Concatenate and display file content
   - Syntax: `cat [file]`
   - Example: `cat file.txt`

10. `grep` - Search for a pattern in files
    - Syntax: `grep [options] [pattern] [file]`
    - Example: `grep "hello" file.txt`

11. `chmod` - Change file/directory permissions
    - Syntax: `chmod [options] [mode] [file/directory]`
    - Example: `chmod 755 script.sh`

12. `chown` - Change file/directory ownership
    - Syntax: `chown [options] [user:group] [file/directory]`
    - Example: `chown john:users file.txt`

13. `sudo` - Execute a command as the superuser (root)
    - Syntax: `sudo [command]`
    - Example: `sudo apt-get update`

14. `apt` - Package management (Ubuntu/Debian)
    - Syntax: `apt [options] [command]`
    - Example: `apt install package-name`

15. `yum` - Package management (CentOS/RHEL)
    - Syntax: `yum [options] [command]`
    - Example: `yum install package-name`

16. `ping` - Send ICMP echo requests to a host
    - Syntax: `ping [options] host`
    - Example: `ping www.example.com`

21. `find` - Search for files and directories
   - Syntax: `find [path] [options] [expression]`
   - Example: `find /home/user -name "*.txt"`

22. `grep` - Search for a pattern in files (with regular expressions)
   - Syntax: `grep [options] [pattern] [file]`
   - Example: `grep -r "error" /var/log`

23. `sed` - Stream editor for text manipulation
   - Syntax: `sed [options] [script] [file]`
   - Example: `sed 's/old/new/' file.txt`

24. `awk` - Text processing language
   - Syntax: `awk [options] 'pattern {action}' [file]`
   - Example: `awk '{print $1}' file.txt`

25. `tar` - Archive files into a tarball
   - Syntax: `tar [options] [archive] [file/directory]`
   - Example: `tar -czvf archive.tar.gz /data`

26. `zip` - Create a zip archive
   - Syntax: `zip [options] [archive.zip] [file/directory]`
   - Example: `zip -r archive.zip /data`

27. `unzip` - Extract files from a zip archive
   - Syntax: `unzip [options] [archive.zip]`
   - Example: `unzip archive.zip`

28. `du` - Estimate file and directory disk usage
   - Syntax: `du [options] [file/directory]`
   - Example: `du -sh /home/user`

29. `df` - Report file system disk space usage
   - Syntax: `df [options] [file system]`
   - Example: `df -h`

30. `top` - Display system processes and resource usage
   - Syntax: `top`

31. `ps` - Report active processes
   - Syntax: `ps [options]`
   - Example: `ps -ef`

32. `kill` - Send a signal to a process
   - Syntax: `kill [options] [process ID]`
   - Example: `kill -9 12345`

33. `ifconfig` - Configure network interfaces
   - Syntax: `ifconfig [interface] [options]`
   - Example: `ifconfig eth0`

34. `ssh` - Secure shell client for remote login
   - Syntax: `ssh [user@]hostname [command]`
   - Example: `ssh user@example.com`

35. `scp` - Securely copy files between hosts
   - Syntax: `scp [options] [source] [destination]`
   - Example: `scp file.txt user@example.com:/home/user`

