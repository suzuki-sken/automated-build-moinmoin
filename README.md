# docker-moinmoin

test image for [MoinMoin 1.9.8](https://moinmo.in/) with Python 2.7.6, uWSGI 1.9.17 and nginx 1.4.6 on ubuntu 14.04 baseimage.

## Usage

```
$ sudo mkdir -p /opt/data/moinmoin
$ sudo docker run -d -p 8080:80 -v /opt/data/moinmoin:/srv/www/moin/wiki/data sken/moinmoin:1.9.8
```

It tested in [Ubuntu Server 14.04.2 LTS](http://www.ubuntu.com/server). 
