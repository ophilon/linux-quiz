Linux System Administrator/DevOps Interview Questions
====================================================

A collection of linux sysadmin/devops interview questions. Feel free to contribute via pull requests, issues or email messages.


## <a name='toc'>Table of Contents</a>

  1. [General Questions](#general)
  1. [Simple Linux Questions](#simple)
  1. [Medium Linux Questions](#medium)
  1. [Hard Linux Questions](#hard)
  1. [Expert Linux Questions](#expert)
  1. [Networking Questions](#network)
  1. [MySQL Questions](#mysql)
  1. [DevOps Questions](#devop)
  1. [Fun Questions](#fun)
  1. [Demo Time](#demo)
  1. [Contributors](#contributors)
  1. [Other Great References](#references)

#### [[⬆]](#toc) <a name='general'>0. General Questions: 10 points weight</a>

1. What did you learn yesterday/this week?
1. Talk about your preferred development/administration environment. (OS, Editor, Browsers, Tools etc.)
1. Tell me about the last major public or open source project you finished.
1. Tell me about the biggest mistake you've made in [some recent time period] and how you would do it differently today. What did you learn from this experience?
1. What function does DNS play on a network?
1. What is HTTP?
1. What is an HTTP proxy and how does it work?
1. Describe briefly how HTTPS works.
1. What is SMTP? Give the basic scenario of how a mail message is delivered via SMTP.
1. Give some examples of MTA.
1. What is RAID? What is RAID0, RAID1, RAID5, RAID10?
1. What is a full backup? What is an incremental backup?
1. Describe the general file system hierarchy of a Linux system.
1. Which difference have between public and private SSH key?
1. Who do you think is the greatest programmer ever and why?
1. When Micro$oft stopped fight Linux and start cooperate?
1. Which versions of WSL you know and had used?
1. What is the sign (R) and what is Copyleft?
1. What RFC stands for?
1. Do you have github account? if yes, what kind of projects you created?
1. Which operating system most popular now?
1. What is IANA stands for? What are assigned numbers used for?
1. Why we must choose you?

#### [[⬆]](#toc) <a name='simple'>1. Simple Linux Questions: 10 points weight</a>

1. What is the name and the UID of the administrator user?
1. How to list all files, including hidden ones, in a directory?
1. What is the Unix/Linux command to remove a directory and its contents?
1. Which command will show you free/used memory? Does free memory exist on Linux?
1. How to search for the string "my konfu is the best" in files of a directory recursively?
1. How to connect to a remote server or what is SSH?
1. How to get all environment variables and how can you use them?
1. I get "command not found" when I run ```ifconfig -a```. What can be wrong?
1. What happens if I type TAB-TAB?
1. What command will show the available disk space on the Unix/Linux system?
1. What commands do you know that can be used to check DNS records?
1. What Unix/Linux commands will alter a files ownership, files permissions?
1. What does ```chmod +x FILENAME``` do?
1. What does the permission 0750 on a file mean?
1. What does the permission 0750 on a directory mean?
1. How to add a new system user without login permissions?
1. How to add/remove a group from a user?
1. What is a bash alias?
1. How do you set the mail address of the root/a user?
1. What does CTRL-c do?
1. What does CTRL-d do?
1. What does CTRL-z do?
1. What is in /etc/services?
1. How to redirect STDOUT and STDERR in bash? (> /dev/null 2>&1)
1. What is the difference between UNIX and Linux.
1. What is the difference between Telnet and SSH?
1. Explain the three load averages and what do they indicate. What command can be used to view the load averages?
1. Can you name a lower-case letter that is not a valid option for GNU ```ls```?
1. What is a Linux kernel module?
1. Walk me through the steps in booting into single user mode to troubleshoot a problem.
1. Walk me through the steps you'd take to troubleshoot a 404 error on a web application you administer.
1. What is ICMP protocol? Why do you need to use?
1. What is man section? How many manual sections are there?
1. How can you get the man section description?
1. Which keys on a keyboard most used in a terminal session?
1. What is the difference between commands set and env?

#### [[⬆]](#toc) <a name='medium'>2. Medium Linux Questions: 20 points weight</a>

1. What do the following commands do and how would you use them:
1. ```tee```
1. ```awk```
1. ```tr```
1. ```cut```
1. ```tac```
1. ```curl```
1. ```wget```
1. ```watch```
1. ```head```
1. ```tail```
1. ```less```
1. ```cat```
1. ```touch```
1. ```sar```
1. ```netstat```
1. ```tcpdump```
1. ```lsof```
1. What does an ```&``` after a command do?
1. What does ```nohup ... &``` before a command do?
1. What is a packet filter and how does it work?
1. What is Virtual Memory?
1. What is swap and what is it used for?
1. What is an A record, an NS record, a PTR record, a CNAME record, an MX record?
1. Are there any other RRs and what are they used for?
1. What is a Split DNS?
1. What is the sticky bit?
1. What does the immutable bit do to a file?
1. What is the difference between hardlinks and symlinks? What happens when you remove the source to a symlink/hardlink?
1. You just created an empty folder, the ```ls -l``` command shows it's size 2. What does the size of folder mean?
1. What is an inode and what fields are stored in an inode?
1. How to force/trigger a file system check on next reboot?
1. What is SNMP and what is it used for?
1. What is a runlevel and how to get the current runlevel?
1. What is SSH port forwarding?
1. What is the difference between local and remote port forwarding?
1. What are the steps to add a user to a system without using useradd/adduser?
1. What is MAJOR and MINOR numbers of special files?
1. Describe the mknod command and when you'd use it.
1. Describe a scenario when you get a "filesystem is full" error, but 'df' shows there is free space.
1. Describe a scenario when deleting a file, but 'df' not showing the space being freed.
1. Describe how 'ps' works.
1. What happens to a child process that dies and has no parent process to wait for it and what’s bad about this?
1. Explain briefly each one of the process states.
1. How to know which process listens on a specific port?
1. What is a zombie process and what could be the cause of it?
1. You run a bash script and you want to see its output on your terminal and save it to a file at the same time. How could you do it?
1. Explain what echo "1" > /proc/sys/net/ipv4/ip_forward does.
1. Describe briefly the steps you need to take in order to create and install a valid certificate for the site https://foo.example.com.
1. Can you have several HTTPS virtual hosts sharing the same IP?
1. What is a wildcard certificate?
1. Which Linux file types do you know?
1. What is the difference between a process and a thread? And parent and child processes after a fork system call?
1. What is the difference between exec and fork?
1. What is "nohup" used for?
1. What is the difference between these two commands: ```myvar=hello``` and ```export myvar=hello```
1. How many NTP servers would you configure in your local ntp.conf?
1. What does the column 'reach' mean in ```ntpq -p``` output?
1. You need to upgrade kernel at 100-1000 servers, how you would do this?
1. How can you get Host, Channel, ID, LUN of SCSI disk?
1. How can you limit process memory usage?
1. What is bash quick substitution/caret replace(^x^y)?
1. Do you know of any alternative shells? If so, have you used any?
1. What is a tarpipe (or, how would you go about copying everything, including hardlinks and special files, from one server to another)?
1. How can you tell if the httpd package was already installed?
1. How can you list the contents of a package?
1. How can you determine which package is better: openssh-server-5.3p1-118.1.el6_8.x86_64 or openssh-server-6.6p1-1.el6.x86_64 ?
1. Can you explain to me the difference between block based, and object based storage?
1. There is a system call unlink. Why it's named this way?
1. bash command processor at first devides command string on tokens. What it does next?
1. How many bash EXPANSIONs do you know? 

#### [[⬆]](#toc) <a name='hard'>3. Hard Linux Questions: 30 points weight</a>

1. What is a tunnel and how you can bypass a http proxy?
1. What is the difference between IDS and IPS?
1. What shortcuts do you use on a regular basis?
1. What is the Linux Standard Base?
1. What is an atomic operation?
1. Your freshly configured http server is not running after a restart, what can you do?
1. What kind of keys are in ~/.ssh/authorized_keys and what it is this file used for?
1. I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
1. Did you ever create RPM's, DEB's or solaris pkg's?
1. What does ```:(){ :|:& };:``` do on your system?
1. How do you catch a Linux signal on a script?
1. Can you catch a SIGKILL?
1. What's happening when the Linux kernel is starting the OOM killer and how does it choose which process to kill first?
1. Describe the linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.
1. What's a chroot jail?
1. When trying to umount a directory it says it's busy, how to find out which PID holds the directory?
1. What's LD_PRELOAD and when it's used?
1. You ran a binary and nothing happened. How would you debug this?
1. What are cgroups? Can you specify a scenario where you could use them?
1. How can you remove/delete a file with file-name consisting of only non-printable/non-type-able characters?
1. How can you increase or decrease the priority of a process in Linux?


#### [[⬆]](#toc) <a name='expert'>4. Expert Linux Questions: 40 points weight</a>

1. A running process gets ```EAGAIN: Resource temporarily unavailable``` on reading a socket. How can you close this bad socket/file descriptor without killing the process?
1. What do you control with swapiness?
1. How do you change TCP stack buffers? How do you calculate it?
1. What is Huge Tables? Why isn't it enabled by default? Why and when use it?
1. What is LUKS? How to use it?
1. Can you tell about main difference and similarities of Linux and FreeBSD?

#### [[⬆]](#toc) <a name='network'>5. Networking Questions: 20 points weight</a>

1. What is localhost and why would ```ping localhost``` fail?
1. What is the similarity between "ping" & "traceroute" ? How is traceroute able to find the hops.
1. What is the command used to show all open ports and/or socket connections on a machine?
1. Is 300.168.0.123 a valid IPv4 address?
1. Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?
1. What is a VLAN?
1. What is ARP and what is it used for?
1. What is the difference between TCP and UDP?
1. What is the purpose of a default gateway?
1. What is command used to show the routing table on a Linux box?
1. A TCP connection on a network can be uniquely defined by 4 things. What are those things?
1. When a client running a web browser connects to a web server, what is the source port and what is the destination port of the connection?
1. How do you add an IPv6 address to a specific interface?
1. You have added an IPv4 and IPv6 address to interface eth0. A ping to the v4 address is working but a ping to the v6 address gives you the response ```sendmsg: operation not permitted```. What could be wrong?
1. What is SNAT and when should it be used?
1. Explain how could you ssh login into a Linux system that DROPs all new incoming packets using a SSH tunnel.
1. How do you stop a DDoS attack?
1. How can you see content of an ip packet?
1. What is IPoAC (RFC 1149)?
1. What will happen when you bind port 0?



#### [[⬆]](#toc) <a name='mysql'>6. MySQL questions: 20 points weight</a>

1. How do you create a user?
1. How do you provide privileges to a user?
1. What is the difference between a "left" and a "right" join?
1. Explain briefly the differences between InnoDB and MyISAM.
1. Describe briefly the steps you need to follow in order to create a simple master/slave cluster.
1. Why should you run "mysql_secure_installation" after installing MySQL?
1. How do you check which jobs are running?
1. How would you take a backup of a MySQL database?

#### [[⬆]](#toc) <a name='devop'>7. DevOps Questions: 20 points weight</a>

1. Can you describe your workflow when you create a script?
1. What is git?
1. What is a dynamically/statically linked file?
1. What does "./configure && make && make install" do?
1. What is puppet/chef/ansible used for?
1. What is Nagios/Zenoss/NewRelic/Grafana suite used for?
1. What is Jenkins/TeamCity/GoCI/Gitlab/Github_actions used for?
1. What is the difference between Containers and VMs?
1. How do you create a new postgres user?
1. What is a virtual IP address? What is a cluster?
1. How do you print all strings of printable characters present in a file?
1. How do you find shared library dependencies?
1. What is Automake and Autoconf?
1. ./configure shows an error that libfoobar is missing on your system, how could you fix this, what could be wrong?
1. What are the advantages/disadvantages of script vs compiled program?
1. What's the relationship between continuous delivery and DevOps?
1. What are the important aspects of a system of continuous integration and deployment?
1. How would you enable network file sharing within AWS that would allow EC2 instances in multiple availability zones to share data?
1. What is the main difference between ```docker compose``` versions 1 and 2?

#### [[⬆]](#toc) <a name='fun'>8. Fun Questions: 20 points weight</a>

1. A careless sysadmin executes the following command: ```chmod 444 /bin/chmod``` - what do you do to fix this?
1. I've lost my root password, what can I do?
1. I've rebooted a remote server but after 10 minutes I'm still not able to ssh into it, what can be wrong?
1. If you were stuck on a desert island with only 5 command-line utilities, which would you choose?
1. You come across a random computer and it appears to be a command console for the universe. What is the first thing you type?
1. Tell me about a creative way that you've used SSH?
1. You have deleted by error a running script, what could you do to restore it?
1. What will happen on 19 January 2038?
1. How to reboot server when reboot command is not responding?


#### [[⬆]](#toc) <a name='demo'>9. Demo Time: 20 points weight</a>

1. Unpack test.tar.gz without man pages or google.
1. Remove all "*.pyc" files from testdir recursively?
1. Search for "my konfu is the best" in all *.py files.
1. Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files.
1. Test if port 443 on a machine with IP address X.X.X.X is reachable.
1. Get http://myinternal.webserver.local/test.html via telnet.
1. How to send an email without a mail client, just on the command line?
1. Write a ```get_prim``` method in python/perl/bash/pseudo.
1. Find all files which have been accessed within the last 30 days.
1. Explain the following command ```(date ; ps -ef | awk '{print $1}' | sort | uniq | wc -l ) >> Activity.log```
1. Write a script to list all the differences between two directories.
1. In a log file with contents as ```<TIME> : [MESSAGE] : [ERROR_NO] - Human readable text``` display summary/count of specific error numbers that occurred every hour or a specific hour.

#### [[⬆]](#toc) <a name='contributors'>Contributors:</a>

* [moregeek](https://github.com/moregeek)
* [typhonius](https://github.com/typhonius)
* [schumar](https://github.com/schumar)
* [negesti](https://github.com/negesti)
* peter
* [andreashappe](https://github.com/andreashappe)
* [quatrix](https://github.com/quatrix)
* [biyanisuraj](https://github.com/biyanisuraj)
* [pedroguima](https://github.com/pedroguima)
* Ben
* [bharatnc](https://github.com/bharatnc)

#### [[⬆]](#toc) <a name='references'>Other Great References:</a>

Some questions are 'borrowed' from other great references like:

* https://github.com/darcyclarke/Front-end-Developer-Interview-Questions
* https://github.com/kylejohnson/linux-sysadmin-interview-questions/blob/master/test.md
* https://www.interviewbit.com/linux-interview-questions/
