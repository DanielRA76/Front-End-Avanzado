# Front-End-Avanzado
Práctica KeepCoding Web 5 Front-End Avanzado


### Inicializo el Package.json con instrucción:
```
npm init -y
`````

### Instalo Webpack y webpack-cli en modo desarrollo
````
npm install --save-dev webpack webpack-cli
````

### Creamos en la raiz index.html y carpeta src, dentro contendra index.js
### para crear la distribución con webpack lanzamos
```
./node_modules/.bin/webpack
```

## Creamos en raíz fichero configuración de Webpack, llamado webpack.config.js
```
En la configuración le pasaremos el entry,  output y datos de configuración inicial.
Más tarde iremos modificandolo y completandolo. De momento vemos que funciona cuando lanzamos:
npm run webpack
```

## Instalamos el servidor de webpack dev-server
```
npm install -D wepack-dev-server
```


