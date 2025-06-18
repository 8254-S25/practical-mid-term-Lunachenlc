## CST 8254 Practical Mid Term

**Your Name:Yanna Chen**

** VNC enabled**
```
pi@chen1002:~ $ sudo raspi-config
Created symlink /etc/systemd/system/multi-user.target.wants/wayvnc.service → /lib/systemd/system/wayvnc.service.
```

**1.**
```
scp "C:\Users\lunac\Desktop\yannachen.txt" pi@chen1002:/home/pi/
```

**2. What command do you use to see a directory listing that includes the permissions of the files?**
```
ls -l
```

**3.**
```
ls -l > pr1.txt
```

**4. What are the permissions of the file you just created?**
```
-rw-r--r--
```

**5. What command do you use to display the folder you are currently working from?**
```
pwd
```

**6.**
```
chmod g=x pr1.txt
```

**7.**
```
mkdir midtermExam-301
```

**8. What are the permissions of this new folder  ?**
```
drwxr-xr-x
```

**9. What command do you use to list the ports your raspberry pi is listening to? Try it using the `-at` flag.**
```
netstat -at
```

**10.**
```
netstat -at > pr2.txt
```

**11.**
```
sftp pi@chen1002
```

**12.**
```
put C:\Users\lunac\Desktop\midtermPi.txt
```

**13.** What does the command do?
```
This command does two things. First, it writes the current working directory path to the file called "mt.txt". Then, it adds a tree view of the directory structure to the file called "pr.txt".
```

**14.**
```
sudo useradd yannachen
```

**15.**
```
sudo mkdir /home/yannachen
sudo chown yannachen:yannachen /home/yannachen
```

**16.**
```
sudo apt-get update
sudo apt-get install filezilla
```
