# Firewall-AntiDDoS
⚠️ 🔒 Firewall-AntiDDoS Games par Iptables (Netfilter) [En cours]
Hello, I'm realease a little homemade firewall to simply protect a simple Debian VPS / Ubuntu server.
this works well on ovh server.

/!\ WARNING /!\

stay in the root folder to test the firewall otherwise you can meter your server in danger!

Command 0 : cd /root

Tools : vi, vim, nano :

Command 1 : vim firewall_testroot

Indicator : 

XXX = select you port | speed looking ctrl + f : XXX ;)

______ ___________ _____ _    _  ___  _     _ 
|  ___|_   _| ___ |  ___| |  | |/ _ \| |   | |
| |_    | | | |_/ | |__ | |  | / /_\ | |   | |
|  _|   | | |    /|  __|| |/\| |  _  | |   | |
| |    _| |_| |\ \| |___\  /\  | | | | |___| |____
\_|    \___/\_| \_\____/ \/  \/\_| |_\_____\_____/



Command 2 : chmod 777 ./firewall_testroot
Command 2.1 : ./firewall_testroot

ERROR 1 : Is not run, Verif firewall conf
ERROR 2 : SERVER CRASHED SSH CLOSED, Restart you vps by pannels admin hosting.

IS OK ? :

Command 3 : mv firewall_testroot /etc/init.d//firewall

Command 4 : cd /etc/init.d/

Command 5 : sudo chmod +x firewall

Command 6 : sudo update-rc.d firewall defaults

Finish, Thanks for reading my post and hope this helped you! ;)
