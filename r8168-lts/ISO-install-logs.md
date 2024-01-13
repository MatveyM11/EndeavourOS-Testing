
https://termbin.com/f50s

/etc/calamares/scripts/chrooted_cleaner_script.sh

sudo rm -rf /etc/calamares/scripts/chrooted_cleaner_script.sh

sudo cp /home/liveuser/chrooted_cleaner_script.sh /etc/calamares/scripts

sudo chmod +x /etc/calamares/scripts/chrooted_cleaner_script.sh

sudo touch /tmp/r8168_in_use   
sudo touch /home/liveuser/r8168_in_use

pacman -Q | grep r8168
