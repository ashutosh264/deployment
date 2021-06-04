# Steps

- Select appropriate region
- Launch instance
- Select AMI (Amazon Machine Image) i.e. (OS, application server, applications)
- Choose an Instance Type:
  - Generally prefer t2.micro (which is eligible for free tier)
- Create Key Pair (pem file)
- Make sure port 80, 22 are open i.e their source should be 0.0.0.0/0 (Whitelisting IP) [SSH]
- If your are using windows need to setup PuTTY to connect to server

####Commands to run on your machine 1st time,

- sudo apt-get update
- sudo apt upgrade
- sudo apt install apache2 (or nginx)
- To check if anything is working fine or not use,
  sudo service \_\_\_\_ status (Ex. sudo service apache2 status)

#Linux
<img src="https://developer.ibm.com/developer/default/articles/l-linux-kernel/images/figure2.jpg"></img>

- Linux is an open source operating system (OS).
- Linux is the kernal portion of the operating system with a UI on top of it.
- There are over 500+ active distros right now of Linux.

###Linux General Commands:

- **cd** _(Change directory)_
- **pwd** _(Print working directory)_
- **ls** _(List files and directories)_
- **touch _filename_** _(Create file)_
- **vi _filename_** _(Basic linux code editor)_
  - Enter **i** to start writing & **esc** to exit writing mode
  - **:w!** _(To save file)_ or **shift+z+z**
  - **:q!** _(Exit without saving)_
- **sudo chown root _filename_** _(Change owner to root)_
