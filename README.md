[![](https://images.microbadger.com/badges/image/rawmind/alpine-hms.svg)](https://microbadger.com/images/rawmind/alpine-hms "Get your own image badge on microbadger.com")

alpine-hms 
===============

This image is the [hms][hms] service. It comes from [alpine-nginx][alpine-nginx].

## Build

```
docker build -t rawmind/alpine-hms:<version> .
```

## Versions

- `0.0.1` [(Dockerfile)](https://github.com/rawmind0/alpine-hms/blob/0.0.1/Dockerfile)


## Configuration

This image runs [hms][hms] with monit. It is started with nginx user/group with 10004 uid/gid.

Besides, you can customize the configuration in several ways:

### Default Configuration

[hms][hms] is installed under /opt/nginx/www/hms, [reveal.js][reveal.js] /opt/nginx/www/hms/docs/reveal.js , and listen at port 8080.

[alpine-nginx]: https://github.com/rawmind0/alpine-nginx/
[reveal.js]: https://github.com/hakimel/reveal.js
[hms]: https://github.com/4km3/hms