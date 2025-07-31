# project_backup_restore
Script to backup a plcnext project (and configuration like wbm user management + Firewall) and restore/copy it to another sd card
The idea come from USA project : https://github.com/plcnextusa/SDCardCopy/tree/main
I have tested it with AXC F 2152 FW 2024 with plcnext Eng. project and some configuration on wbm user management + firewall.

This is a bash script meant for copying data from one PLCNext SD card to your computer without destroying the licenses contained on them.
The second script meant to copyin from your computer to PLCnext SD card

Requirements
This script was developed and tested on a Lubuntu machine, so Ubuntu based distros are recommended for use with this script

Usage
Place the script in it's own empty folder
run the script with "sudo bash ./script.sh"

