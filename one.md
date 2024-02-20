# Project Valentine

`Login name: woobaby, home directory: /home/woobaby. The home directory contains these sub-directories: code, tests, personal, misc. Unless otherwise specified, you are running commands from the home directory.`

![mkdir command](./1.png)

1. `Change directory to the tests directory using absolute pathname`

![cd command](./a.png)

2. `Change to the tests directory using relative pathname`

![cd command](./b.png)

3. `Use echo command to create a file named fileA with text content 'Hello A' in the misc directory`

![echo command](./c.png)

4. `Create an empty file named fileB in the misc directory. Ppoulate the file with dummy content afterwards.`

![touch command](./d.png)

5. `Copy contents of fileA into fileC`

![cp command](./e.png)

6. `Move contents of fileB into fileD`

![mv command](./f.png)

7. `Create a tar archive called misc.tar for the conntents of the misc directory` 

![tar -cvf command](./g.png)

8. `Compress the tr archive to create a misc.tar.gz file`

![tar -cvzf command](./h.png)

9. `Create a user and force the user to change their password upon login`

![sudo useradd, sudo password, sudo password --expire command](./i.png)

10. `Lock a user's password`

![sudo password -l command](./j.png)

11. `Create a user with no login shell`

![sudo useradd -m -s /usr/sbin/nologin](./k.png)

12. `Disable password based authentication for ssh`

![sudo vi /etc/ssh/sshd_config command](./l1.png)
![result](./l2.png)

13. `Disable root login`

![sudo vi /etc/ssh/sshd_config command](./m1.png)
![result](./m2.png)