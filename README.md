# linux-update-upgrade

This bash script allows to automate the update on a Linux Debian or Ubuntu system.

Don't forget to give the execution rights on the script and to edit a cron task by adapting the time at which you want to do your update.

There are 2 log files : 
- The file that will redirect the content in case of success (stdout) (update_upgrade.log)
- The file that will redirect the content in case of error (stderr) (update_upgrade.err)
