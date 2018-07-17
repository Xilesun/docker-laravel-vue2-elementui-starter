# A PHP SPA Starter kit

## Environment

docker: Nginx + PHP7.1.4-fpm + MySQL5.7

lavarel5.6

Vue2 + Element-UI

## Install

Build docker container.

```shell
docker-composer up -d
```

Configure Ningx in `nginx/nginx.conf` 

`cd web`, copy `.env.example` to `.env`, eidt database info, etc.

Install npm modules.

```shell
npm install
```

### Build

```shell
npm run dev
```

Open `localhost:3333`
