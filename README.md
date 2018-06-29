# docker-compose-gitea

A docker compose file to set up Gitea

## Prerequisites
* Change MYSQL_ROOT_PASSWORD and MYSQL_PASSWORD

* You may want to create the user git if you intend to make almost no changes to this composer file.

```
useradd git -m -s /bin/bash
git clone git@github.com:danzarov/docker-compose-gitea.git
```

## Post install
* Open your browser of choice and access
```
http://<your-server-ip-addr>:8080
```

## Config Sample

![gitea_configs_github2](https://user-images.githubusercontent.com/9399045/42068036-fde09098-7b1f-11e8-9eee-1e68d129751a.png)


* Do not forget to disable self registration if you want this to be a private repository.

![disable_self](https://user-images.githubusercontent.com/9399045/42068075-34385b94-7b20-11e8-9af9-fa8fe9f98905.png)

