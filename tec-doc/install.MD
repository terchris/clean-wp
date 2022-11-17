# installing clean wp setup
purpose is to use as a base when studying listeo


Backup of the initial database
docker exec clean-mysqldb /usr/bin/mysqldump --no-tablespaces -u mysqlusername --password=mysqlpassword cleanwpdb > initial-install-database-backup.sql