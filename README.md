# docker-lemp-boilerplate
Docker LEMP boilerplate for use with docker-compose

Use this boilerplate for persistent database project.

This is CentOS 7 linux based that uses 3 docker images:
  - paradigma/c7-mariadb
  - paradigma/c7-php-fpm
  - paradigma/c7-nginx

You can customize the virtual host NGINX config file.

The project's root folder is src/public.

You need to have docker preinstalled.

You can customize DB credentials within db.env file.

Run with:

```bash
docker-compose up -d
```

Once initialized, you can access database with any MySQL client.

For running multiple instances, set the web container port number other than 8080