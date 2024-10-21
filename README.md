# cronjobs
Collection of bash shell scripts to run cronjobs  


First, create a shell script

#Save this script to a file, for example /usr/local/bin/script.sh
#Make the script executable:

sudo chmod +x /usr/local/bin/script.sh

#Set up a cron job to run this script automatically. Open the crontab file:
sudo crontab -e

Add the following line to run the script every day at 1 AM:

0 1 * * * /usr/local/bin/script.sh


This setup will run every day at 1 AM.
