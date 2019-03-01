# docker-openjabnab
(Fork of [ antoineaumjaud/docker-openjabnab/](https://hub.docker.com/r/antoineaumjaud/docker-openjabnab/) with some issues fixes)

## Updates
TODO after image pulled: 
- change [OpenJabNabServers] in config file /var/www/OpenJabNab/server/bin with your domain
You can make a volume mapping with your own openjabnab config file pointing on that internal container file : /var/www/OpenJabNab/server/bin/openjabnab.ini

## Ports
- port 80:  PHP web site for administraction (shoul be exposed)
- port 8080: Nabaztag server, is used internaly only (call from PHP web site)
- port 5222: (to expose) is use for [XMPP](https://fr.wikipedia.org/wiki/Extensible_Messaging_and_Presence_Protocol)

## URLs
- URL admin access is: http://<my.domain>/ojn_admin/
