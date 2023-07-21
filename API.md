# How to run ?

## Run docker-compose

```shell
docker-compose up
```

## Setup hosts

```shell
sudo nano /etc/hosts

# add the following
127.0.0.1    auth.fief.local
```

## Authorize to access documentation endpoints

1. Go to [https://auth.fief.local/admin/clients/](https://auth.fief.local/admin/clients/)
2. Edit **`Fief's client`** and add the following to **`Redirect URIs`**

   ```shell
   https://auth.fief.local/docs/oauth2-redirect
   ```

3. Click Update

## Visit fief Auth

Goto: [https://auth.fief.local](https://auth.fief.local)

## Swagger API documentation

### Authentication Documentation Endpoints

[/docs](http://auth.fief.local/docs)

### Admin Documentation Endpoints

[/admin/api/docs](http://auth.fief.local/admin/api/docs)

## Access Dashboard

[/admin/](http://auth.fief.local/admin/)
