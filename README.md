# vnc_astah
vnc_astah

# vnc_astah

vnc_astah

## 1.docker run

### 1.1 run vnc

```sh
$ docker run --name vnc -d -p 5901:5901 jumpei/vnc_astah:community
```

id/password
kioskuser/kioskuser

### 1.2 run xrdp

```sh
$ docker run -d -p 3389:3389 --link vnc --name xrdp kevensen/centos-xrdp
```


