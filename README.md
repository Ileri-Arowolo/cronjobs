# Cronjobs

Collection of bash shell scripts to run cronjobs

## Setup Instructions

1. Create a shell script:
   ```bash
   # Save this script to a file, for example /usr/local/bin/script.sh
   ```

2. Make the script executable:
   ```bash
   sudo chmod +x /usr/local/bin/script.sh
   ```

3. Set up a cron job to run this script automatically:
   - Open the crontab file:
     ```bash
     sudo crontab -e
     ```
   - Add the following line to run the script every day at 1 AM:
     ```
     0 1 * * * /usr/local/bin/script.sh
     ```

This setup will run the script every day at 1 AM.

