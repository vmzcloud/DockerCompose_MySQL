<img src="https://img.shields.io/badge/language-DockerCompose-blue.svg"/> <img src="https://img.shields.io/github/last-commit/vmzcloud/DockerCompose_MySQL.svg"/>

# MySQL

## Preparation

### Add user for mysql

Add user
<pre>
useradd mysql
</pre>

Check user UID and GID
Following example: UID = 1001 and GID = 1001
<pre>
cat /etc/passwd
</pre>
<pre>
mysql:x:1001:1001::/home/mysql:/bin/bash
</pre>

### Start the Default MySQL container
<pre>
docker compose -f docker-compose_default_mysql.yml
</pre>
