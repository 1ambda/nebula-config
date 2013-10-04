nebula-config
=============


### impl : DNS, Haproxy, Shellinabox, net2ftp
### todo : noVNC, Webvirtmgr, Jenkins, Database Hosting




## DNS

```
vi /etc/bind/zones/cloudy.so.zone
vi /etc/hosts
service bind9 restart
```


## Haproxy

```
vi /etc/haproxy/haproxy.cfg
/etc/init.d/haproxy restart
```


## Shellinabox

```
vi /etc/default/shellinabox
/etc/init.d/shellinabox restart
```

## net2ftp

```
vi /etc/apache2/httpd.conf
service apache2 reload
```



