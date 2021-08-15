# production-docker-stack
My DOCKER STACK

this guide is assuming you already have docker and docker compose installed on your host, or virtual machine. If you need instructions on docker see my other guidies

connect to your host with docker installed 

make the following directories

mkdir docker
mkdir Docker_PATH (this is where my docker is installed to and containers are built from)

cd into docker

make the following directories

mkdir autoheal
mkdir bookstack
mkdir bookstackdb
mkdir calibre
mkdir calibre-web
mkdir hastebin
mkdir hastebinredis
mkdir languagetool
mkdir mealie
mkdir papermerge
mkdir piwigo
mkdir piwigodb
mkdir speedtest

now lets make the compose yaml file

sudo nano docker-compose.yaml

insert the code from my example yaml config file

NOTE you will need to modify settings to meet your needs region/docker path/etc


