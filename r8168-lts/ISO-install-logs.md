
https://termbin.com/f50s

/etc/calamares/scripts/chrooted_cleaner_script.sh

sudo rm -rf /etc/calamares/scripts/chrooted_cleaner_script.sh

sudo cp /home/liveuser/chrooted_cleaner_script.sh /etc/calamares/scripts

chmod +x /etc/calamares/scripts/chrooted_cleaner_script.sh

touch /tmp/r8168_in_use

pacman -Q | grep r8168
