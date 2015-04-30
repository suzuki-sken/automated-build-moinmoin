# docker-moinmoin

test image for [MoinMoin 1.9.8](https://moinmo.in/) with Python2.7.6, uWSGI1.9.17 and nginx1.4.6 on ubuntu14.04 base image.

## Usage

```
$ docker run -d -p 8080:80 -v /opt/data/moinmoin:/srv/www/moin/wiki sken/moinmoin:1.9.8
```

It tested in [Ubuntu Server 14.04.2 LTS](http://www.ubuntu.com/server). 
