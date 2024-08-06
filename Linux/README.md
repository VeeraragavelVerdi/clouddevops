# **OPERATING SYSTEM**
## What is software?
A software is a set of instruction that tells a computer how to work.
### There are two types of software:
1. System software Ex: Operating system, device drivers
2.  Application software Ex:

1.Word Processing Software:
Microsoft Word
2. Spreadsheet Software:
Microsoft Excel
3. Presentation Software:
Microsoft PowerPoint
4. Web Browsers:
Google Chrome
Mozilla Firefox
Microsoft Edge
Safari
5. Email Clients:
Microsoft Outlook
6. Graphic Design Software:
Adobe Photoshop
## What is operating system ?
operating system is a system software used to make communication between Hardware and  software.

## Operating system architecture
![Architecture](Capture.jpg)

## Compiler/Intrepreter:
Translates human language into machine instructions

## Compiler: 
Validate the entire source and provide the errors Once.

## Intrepreter:

Validate the code line by line. if one lines got error it tell to fix that particular line error then validate the next line.

## Types of operating systems:
1. Linux
2. Windows

## Linux Flavors:
1. Ubuntu
2. CentOs
3. Red hat enterprise
4. Fedora
   

## Directory Navigation:
```
1. ls             -
```
```
2. ls -la         -
```
```
3. ls -l          -
```
```
4. pwd            -
```
```
5. cd             -
```
```
6. cd ~
```
```           -
7. cd [directory_path] -
```
```
8. dirs           -
```

## Files
```
1. mkdir -
```
```
2. rm [filename] -
```
```
3. rm -r [directory name] -
```
```
4. rm -rf [directory name] -
```
```
5. cp [source file][destinationfile] -
```
```
6. cp -r [source_directory][destination_directory] -
```
```
7. mv [sourcefile][destinationfile] -
```
```
8. touch [filename]  -
```
```
9. cat [filename]  -
```
```
10. cat[sourcefile] >> [destination file]
```
```
11. head [filename] -
```
```
12. tail [filename]   -
```
```
13. more [filename]  -
```
```
14. less [filename]  -
```
```
15. nano [filename]  -
```
```
16. vi [filename]    -
```
```
17. vim [filename]   -
```
```
18. gpg -c [filename] -
```
```
19. wc -w [filename] -
```
```
20. cut -d [delimiter] -
```
## Disk usage 
```
1. df -h -
```
```
2. df -i -
```
```
3. fdisk -l -
```
```
4. du -ah -
```
```
5. du -sh -
```
```
6. mount -
```
```
7. findmnt -
```
```
8. mount [device_path] [mount_point]
```

## Users and Groups
```
1. id
```
```
2. last -
```
```
3. who -
```
```
4. sudo useradd[username] -
```
```
5. sudo adduser[username] -
```
```
6. sudo usermod -aG [groupname][username] -
```
```
7. passwd -
```
```
8. sudo passwd[username] -
```
```
9. sudo groupadd[groupname] -
```
```
10. sudo groupdel[groupname] -
```

## File permissions:
```
1. chmod 777 filename -
```
```
2. chmod 755 filename -
```
```
3. chmod 766 filename -
```
```
4. chown username filename -
```
```
5. chmod rwx filename -
```

## File Compression:
```
1. tar cf [archive.tar] [file/directory]
```
```
2. tar xf [archive.tar]
```
```
3. tar czf [archive.tar.gz]
```
## system management
```
1. username -r -
```
```
2. username -a -
```
```
3. uptime -
```
```
4. hostname -
```
```
5. hostname -i -
```
```
6. last reboot -
```
```
7. date -
```
```
8. timedatectl -
```
```
9. cal -
```
```
10. w -
```
```

11. whoami -
```
```
12. shutdown [hh:mm]
```
```
13. shutdown now
```
```
14. dmesg -
```

## Hardware information:
1. lscpu -

2. lsblk -

3. cat /proc/cpuinfo

4. cat /proc/meminfo

5. free -h

6. lsusb -tv


## Searching:
1. find [path] -name [searchpattern]

2. find [path] -size [+100]

3. grep [searchpattern] [filename]

4. grep -r [searchpattern] [directoryname]

5. locate [name]

6. which [command]

7. whereis [command]

8. awk

9. sed

## Processes:
1. ps

2. top

3. htop

4. kill [process_id]

5. pkill[process_name]

6. bg

7. fg

8. lsof

9. nohup [command] &

## File transfer:
1. scp [sourcefile] [user]@[remotehost]:[destinationpath]

2. rsync -a

3. wget [link]

4. curl -O [link]

5. ftp [remotehost]

6. sftp [user]@[remotehost]

## Packages(debian/Ubuntu):
1.  sudo apt-get install [packagename]

2.  sudo apt install packagename

3.  sudo apt show packagename

4.  sudo search [keyword]

## Packages(Redhat, centos, Fedora):
1. sudo yum install package name

2. yum search [keyword]

3. yum list installed

4. sudo rpm -i [packagename.rpm]

## ssh login
1. ssh [username]@host

2. ssh [hostname]

3. ssh-keygen

4. sudo service sshd start

5. scp [filename] [username]@[host]:[remotepath]

6. telnet [hostname]

## Network
```
1. ipaddr show
```
```
2. ifconfig
```
```
3. ping [remotehost]
```
```
4. netstat -tuln
```
```
5. whois [domainname]
```
```
6. dig [domainname]
```
```
7. hostname -i
```
```
8. nslookup [domainname]
```
