# Exiled installation in Linux 

In this tutorial i teach you how to create a Exiled server in Lunux (for this tutorial i use ubuntu 20.04, but other os are fine)

# Requirements

- [X] A vps with 1gb of ram and 1 core.
- [x] Winscp/Filezilla for sftp acces to file.
- [x] Putty for ssh acces.

# 1. Install Mono

For install mono check your OS version and go to [this link](https://www.mono-project.com/download/stable/#download-lin) and install it.

# 2. Install steamcmd

For install the base server we need steamcmd.

* Go to root and run this command: 

For Ubuntu/Debuian: <kbd>sudo apt-get install lib32gcc1</kbd> 

For Centos: <kbd>yum install glibc.i686 libstdc++.i686</kbd>

* Create a folder with <kbd>mkdir steamcmd</kbd> (when do you install the steamcmd) and go to it.

* When you are in the folder run this command: <kbd>wget https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz</kbd>

* Next run this for unpack the tar file: <kbd>tar zxvf (thenameofthetarfile)</kbd> you unpack the tar file!

* Run this for provide all permission to launche steamcmd: <kbd>chmod 777 *</kbd>

* Finally launch the steamcmd with: <kbd>./steamcmd.sh</kbd>

# 3. Install the server with steamcmd

* When yu starts the server you should see this:

![myImage](https://i.imgur.com/rUK7zLn.png)

* In the steam console run this: <kbd>login anonymous</kbd>
* Next run: <kbd>force_install_dir /the/directory/when do you/want to install the server</kbd> (in my case /root/scpserver)
* Next: <kbd>app_update 996560 validate</kbd>
* When the installation has finished run: <kbd>quit</kbd>





