# Apache-Cassandra-Database-Backup
A shell script to back up a cassandra database on linux

## Configuration
- set the folloeing variables in the script
    - _BACKUP_DIR=/home/DBbackup/cassandra
    - _REMOTE_BACKUP_SERVER_ADDRESS=user@remote_server_ip

- Congigure ssh key for remote server
    - ssh-keygen -t rsa
    - ssh-copy-id user@remote_server_ip
    