# backup-repo
Back up of my local virtual machine work 
# For VirtualBox, you can use VBoxManage to manage your VMs via command line.
# This script will export the VM in OVA format and compress the backup to save space.
# Save the script above as backup_vm.sh

Setting Up Cron Job for VirtualBox:

Make it executable:  chmod +x /path/to/backup_vm.sh
Edit the crontab to run the script at a scheduled time (e.g., every day at 2 AM): crontab -e
Add the following line to run the script daily at 2 AM:  0 2 * * * /path/to/backup_vm.sh

