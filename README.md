# Exiled installation in Linux 

In this tutorial i teach you how to create a Exiled server in Lunux (for this tutorial i use ubuntu 20.04, but other os are fine)

# Requirements

- [X] A vps with 1gb of ram and 1 core.
- [x] Winscp/Filezilla for sftp access to file.
- [x] Putty for ssh access.

# 1. Install Mono

For install mono check your OS version and go to [this link](https://www.mono-project.com/download/stable/#download-lin) and install it.

# 2. Install steamcmd

For install the base server we need steamcmd.

* Go to root and run this command: 

For Ubuntu/Debuian: <kbd>sudo apt-get install lib32gcc1</kbd> 

For Centos: <kbd>yum install glibc.i686 libstdc++.i686</kbd>

* Create a folder with <kbd>mkdir steamcmd</kbd> (when you have installed the steamcmd) and go to it.

* When you are in the folder run this command: <kbd>wget https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz</kbd>

* Next run this for unzip the tar file: <kbd>tar zxvf (thenameofthetarfile)</kbd> you unpack the tar file!

* Run this for provide all permission to launch steamcmd: <kbd>chmod 777 *</kbd>

* Finally launch steamcmd with: <kbd>./steamcmd.sh</kbd>

# 3. Install the server with steamcmd

#### When you starts the server you should see this:

![myImage](https://i.imgur.com/rUK7zLn.png)

* In steamcmd run this: <kbd>login anonymous</kbd>
* Next run: <kbd>force_install_dir /the/directory/when you want to install the server</kbd> (in my case /root/scpserver)
* Next: <kbd>app_update 996560 validate</kbd>
* When the installation is finished run: <kbd>quit</kbd>

##### The server was installed and you should see this in the directory when you install the server:

![myImage](https://i.imgur.com/kKgZYvI.png)

# 4. Run the server

* For start the server run: <kbd>./LocalAdmin 7777</kbd> in the server directory.

#### You should to see this:
![myImage](https://i.imgur.com/udm9iog.png)

* Enter in the direct connection and put your ip and test it.

* For close the server run: <kbd>exit</kbd> in the server console.

# 5. Install Exiled (finally!!!)











