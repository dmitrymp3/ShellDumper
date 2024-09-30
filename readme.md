# CRONTAB postgres

30 1 * * * /var/lib/postgresql/script -backup >> /var/log/backup-script.log
30 23 * * * /var/lib/postgresql/script -clean >> /var/log/clean-script.log