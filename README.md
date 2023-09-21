# mongodb-with-flask
Basic mongo db with flask


#To install mangodb in ubuntu
https://www.digitalocean.com/community/tutorials/how-to-use-mongodb-in-a-flask-application

#To integrate mangodb with flask
https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-20-04


# Mongodb Backup and restore command use username and password if exist.
1. mongodump --username=user --password=password --authenticationDatabase=admin --db=ecgvue dit_log" --out "$backup_dir/dump-$timestamp"
2. mongodump --db=ecgvue --out ./hellotest
3. mongorestore --db testdb ./hellotest/testdb/
