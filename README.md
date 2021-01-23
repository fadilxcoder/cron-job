# Notes

- Connect to server by SSH
- Run : `crontab -e` & insert cron
- Run : `crontab -l` - view crontab file
- Run : `crontab -r` - Clear and remove crontab
- Create / validate cron timing setup : https://crontab.guru/
- Explained :
- - `* * * * * /usr/bin/php /<path>/<to>/<file>/cron/db-populate`
- - `* * * * *` => At every minute.
- - `/usr/bin/php` => `php` command
- - `/<path>/<to>/<file>/cron/db-populate` => Full path to file to be executed