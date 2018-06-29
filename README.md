# docker-compose-gitea

A docker compose file to set up Gitea

## Prerequisites
* Change MYSQL_ROOT_PASSWORD and MYSQL_PASSWORD

* You may want to create the user git if you intend to make almost no changes to this composer file.

```
useradd git -m -s /bin/bash
```

## Post install
* Open your browser of choice and access
```
http://<your-server-ip-addr>:8080
```

