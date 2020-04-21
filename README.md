# Traefik 2 config with .env

## Create docker proxy net:
```
docker network create proxy-net
```

## Create auth user
```
# amazon
yum provides \*bin/htpasswd
# ubuntu
sudo apt-get install apache2-utils

htpasswd -n <user>
```