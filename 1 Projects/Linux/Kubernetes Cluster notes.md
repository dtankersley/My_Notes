
Bee-Linux:
added to my cluster as this is a much more robust OS to handle more load/capacity


* added ssh - Sudo apt-install openssh-server
* ran sudo systemctl start ssh to start ssh
* enabled firewall: sudo ufw allow ssh
* edited the /etc/hosts file on both systems to hard-code the ip addresses (192.168.1.232)

Pi-cluster steps:



* verify ssh - passwd
* Run sudo hostnamectl set-hostname  (pi1, pi2, pi3, pi4)
* edit/verify /etc/hosts file to hard-code ip-address
*

* final step - copy pi hard adresses to each /etc/hosts file*
  SSH -keygen
  
  Install k3s:
  curl -sfl https://getk3s.io | sh -

Pi1
 * Ran sudo hostnamectl set-hostname pi1 to rename from old name
 * K3s installed? yes
 *


Pi2
    renames



92.168.1.232 beelinux       
192.168.1.230 evia
192.168.1.38 pi1    
192.168.1.233 pi2  
192.168.1.230 pi3
192.168.1.229 pi4


* ssh-keygen -t ed25519 -C "david@evia.com"
* created passphrase - new key-pairs created



March 24, 2026:
BeeLinux - Master of my cluster
Clients - Pi1 - Pi4

Installed VirtualBox
Installed Ubuntu 24 to run ______
Configure SSH?