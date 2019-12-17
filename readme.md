# B3 Devops - TP 2
## Info
Mail : geoffrey.parrier@ynov.com

github_username : <a href='https://github.com/geoffreyparrier'>@geoffreyparrier</a>

professor : <a href='https://github.com/aegirops'>@aegirops</a>

## VM Config
- Ram: 1GB
- OS: <a href='https://ubuntu.com/download/server'>Ubuntu Server</a>

### Libraires & Programs installed
`nodejs@12

openssh-server

nginx`

## Prerequisites
- <a href='https://www.vagrantup.com'>Vagrant</a>
- <a href='https://www.virtualbox.org/wiki/Download_Old_Builds_6_0'>VirtualBox 6.0</a>
- <a href='https://git-scm.com/book/en/v2/Getting-Started-Installing-Git'>Git</a>
- A shell

## Installation / How to start
1. Clone this repository `https://github.com/YI-B3-Devops/tp1-parrier-geoffrey`.
2. Execute `vagrant up` and wait for the end of the installation and configuration.
3. Your done ! The environment is up and running.

## Usage
### SSH Access
Execute `vagrant ssh`

### View nginx webpage
Go on <a href='http://localhost:8080'>http://localhost:8080</a>

### Stop the Virtual Machine
If you want to stop the virtual machine use `vagrant halt`

## Uninstall
If you need to uninstall this virtual machine use these commands :

1. stop the virtual machine
    * `vagrant halt`
2. Deleting the vm 
    * `vagrant destroy`
  
When he demand say yes in the cmd.
You can delete manually the `.vagrant` folder
