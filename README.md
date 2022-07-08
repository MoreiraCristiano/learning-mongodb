# Commands to manage mongodb in ubuntu

## Installation guide

https://www.cloudbooklet.com/how-to-install-mongodb-on-ubuntu-22-04/

## Enable at service level

```
sudo systemctl enable mongod
sudo systemctl disable mongodb

sudo systemctl start mongodb
sudo systemctl stop mongodb
sudo systemctl restart mongodb
```

## Start, stop, status mongodb server

```
sudo service mongod start
sudo service mongod stop
sudo service mongod status

```

## Test of listen IPs

```
sudo lsof -i | grep mongo
```

## Access

```
mongodb://admin:passwd@External-IP:27017/database
```

## Config file

```
sudo nano /etc/mongod.conf
```
