VISSET was implemented by docker within **aom@10.204.100.136**.
To SSH please contact **Aom** or **Tan**

Bringup database
```bash
docker run --name mariadb --env-file /home/aom/visset_ws/my_env_file -v mariadb:/var/lib/mysql -d -p 3306:3306 --rm mariadb:latest
```

Bringup website
```bash
docker run --name snipeit --env-file /home/aom/visset_ws/my_env_file -v snipeit:/var/lib/snipeit -p 8118:80 -d --rm snipe/snipe-it:latest
```