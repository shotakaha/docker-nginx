# docker-nginx

docker compose  nginx

## 使用するイメージ

- https://hub.docker.com/_/nginx

## 起動

```console
$ docker compose up -d
[+] Running 2/2
 ✔ Network docker-nginx_default    Created
 ✔ Container docker-nginx-nginx-1  Started
```

## 確認

```console
$ docker compose ls
NAME                STATUS              CONFIG FILES
docker-nginx        running(1)          ./compose.yaml
```

## 終了

```console
$ docker compose down
[+] Running 2/2
 ✔ Container docker-nginx-nginx-1  Removed
 ✔ Network docker-nginx_default    Removed
```