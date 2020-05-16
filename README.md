# wordpress-docker-aws
Composer script to run docker wordpress instance

Script runner:
```
#!/bin/bash

# Install wordpress docker
 
cd ~/

git clone https://github.com/faberyx/wordpress-docker-aws.git

cd wordpress-docker-aws

echo -e 'WP_DB_HOST=[YOUR_VALUE]\nWP_DB_USER=[YOUR_VALUE]\nWP_DB_PASSWORD=[YOUR_VALUE]\nWP_DB_NAME=[YOUR_VALUE]\nNFS_DNS=[YOUR_VALUE]' >> .env

docker-compose up -d
```
