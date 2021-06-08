# Heroku Wildfly Buildpack

Buildpack para instalaçao e deploy no Wildfly

## Como usar

Insira os pacotes WAR ou EAR na pasta `target/` para deploy.

## Utilizando com Java buildpack

Voce pode efetuar seu deploy através dos comandos abaixo:

```sh-session
$ heroku buildpacks:clear
$ heroku buildpacks:add heroku/java
$ heroku buildpacks:add https://github.com/claytonmorais/buildpack-heroku-wildfly
```

