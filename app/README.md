app
===

A Symfony project created on August 21, 2017, 3:14 pm.

https://codereviewvideos.com/course/docker-tutorial-for-beginners/video/demo-docker-with-symfony-nginx-and-mysql

<br>

for reason to know `ip` it easy with fake command: 
mysql -u root -pdbpassword

'dbuser'@'172.31.0.2' (workbench)

sudo docker exec -it 5e77c2a41810 /bin/bash
root@5e77c2a41810:/# mysql -u dbuser -pdbpassword    or    php bin/console doctrine:schema:update --force
