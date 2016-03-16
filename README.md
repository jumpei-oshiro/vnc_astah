# vnc_astah
vnc_astah

# vnc_astah

vnc_astah

## 1.git clone

```sh
$ git clone git@github.com:jumpei/vnc_astah.git
```

## 2.docker build

```sh
$ cd vnc_astah
$ docker build -t jumpei/vnc_astah .
$ docker build -t jumpei/vnc_astah:1280x1024 .

```

## 3.docker run

### 3.1 run vnc

```sh
$ docker run --name vnc -d -p 5901:5901 jumpei/vnc_astah:1280x1024
```

id/password
kioskuser/kioskuser

### 3.2 run xrdp

```sh
$ docker run -d -p 3389:3389 --link vnc --name xrdp kevensen/centos-xrdp
```


