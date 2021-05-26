# Docker-Compose-for-PHP-Apache-mysql
---
## Purpose
* Easily launch a php related project in docker
* Has predefined plugins to use mysql, freetype, images
---
# How to run
* Place php, htmls into the `public_html` folder
* `docker-compose up -d`
* goto `localhost:80` for website
* goto `localhost:8000` for phpmyadmin

## Changes
If you need to change the web portal Port, you can do so by modifying the port in the `docker-compose.yml` under `www` for web, and `phpmyadmin` for phpmyadin