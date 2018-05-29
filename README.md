
# ⚠️ 🔒 Firewall-AntiDDoS Games.
Firewall utilisable avec Iptables (Netfilter), sous GNU/Linux Debian/Ubuntu serveur games. Ce Firewall a été créé pour ouvrir vos projets au publique.

Ce Firewall a été tester et approuvé selon moi pour faire de l'hébergement Teamspeak ainsi que protéger ces serveurs de jeux.

# 📁 Install On Linux

/!\ WARNING /!\

stay in the root folder to test the firewall otherwise you can meter your server in danger!

* Command 0 : `cd /root`

Tools : vi, vim, nano :

* Command 1 : `vim firewall_testroot`

* copy config firewall
[Link Config](https://github.com/BadySmith/Firewall-AntiDDoS-Linux/blob/master/firewall.sh)

* Indicator : XXX = select you port | speed looking ctrl + f : XXX

* Command 2 : `chmod 777 ./firewall_testroot`
* Command 2.1 : `./firewall_testroot`

ERROR 1 : Is not run, Verif firewall conf
ERROR 2 : SERVER CRASHED SSH CLOSED, Restart you vps by pannels admin hosting.

IS OK ? :

* Command 3 : `mv firewall_testroot /etc/init.d/firewall`

* Command 4 : `cd /etc/init.d/`

* Command 5 : `sudo chmod +x firewall`

* Command 6 : `sudo update-rc.d firewall defaults`

Finish, Thanks for reading my post and hope this helped you! ;)
