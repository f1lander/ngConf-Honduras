0. npm install -g ng-cli
1. npm install netlify-cli -g

Crear cuenta en Netlify

0. netlify login

En tu proyecto Angular

netlify init

touch netlify.toml

agregar a este archivo

[build]

  publish = "dist/<nombre del proyecto>"

ng build --prod

netlify deploy

Si todo esta bien

netlify deploy --prod


