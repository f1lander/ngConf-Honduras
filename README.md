```
npm install -g ng-cli
npm install netlify-cli -g
```

### Crear cuenta en Netlify

```
netlify login
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

ng build --prod

netlify deploy
```

### Si todo esta bien

```netlify deploy --prod```


