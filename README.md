### Crear cuenta en Netlify

http://netlify.com

### Instalar cli

```
npm install -g ng-cli
npm install netlify-cli -g
netlify login
```

### Crear tu proyecto

```
ng new <tu_app>
cd <tu_app>
```

### En tu proyecto Angular

```
netlify init

touch netlify.toml

```

### Agregar a este archivo

```
[build]

  publish = "dist/<nombre del proyecto>"
```

### Publicar

ng build --prod

netlify deploy
```

### Si todo esta bien

```netlify deploy --prod```


