# wordpress-docker-aws
Composer script to run docker wordpress instance

Script runner:
```
#!/bin/bash

# Install wordpress docker
 
cd ~/

git clone https://github.com/faberyx/wordpress-docker-aws.git

cd wordpress-docker-aws

echo -e 'WP_DB_HOST=wordpress.cmimzo2ep7xd.us-east-1.rds.amazonaws.com\nWP_DB_USER=wordpressAdmin\nWP_DB_PASSWORD=$asdasd123\nWP_DB_NAME=wordpress\nNFS_DNS=fs-26529ba5.efs.us-east-1.amazonaws.com' >> .env

docker-compose up -d
```
