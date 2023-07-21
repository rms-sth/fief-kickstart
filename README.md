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

## What is Fief ?

Fief is an **open-source platform** to manage **users** and **authentication** in your applications. Our goal is to help you manage users and security in a matter of minutes, not days. Key features:

* Pre-built login and registration pages
* Users management dashboard
* SDK for the most popular languages and frameworks
* Integrations for the most popular no-code tools
* Bring Your Own Database: you can connect to any SQL database so you keep entire control of your data

## What we have now?

* [X] User registration
* [X] User authentication using OAuth2 and OpenID Connect protocols
* [X] Social authentication (Google, Facebook...)
* [X] Forgot password process
* [X] Built-in user profile pages for account management
* [X] Customizable authentication pages
* [X] Customizable transactional emails
* [X] Bring your own database
* [X] Event webhooks
* [X] Custom user fields
* [X] Roles and permissions access control
* [X] Official Docker image for self-hosting
* [X] Official Python client with FastAPI and Flask integrations
* [X] Official Node.js Express integration
* [X] Official Next.js integration
* [X] Official JavaScript client with browser and React integrations
* [X] Admin dashboard
* [X] ID Token encryption support
* [X] PKCE support

### What we do not have ?

* [ ] 2FA authentication with authenticator apps and U2F keys
* [ ] User invitation process
* [ ] Custom API scopes
* [ ] User groups management
