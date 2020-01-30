# Desarrollo FullStack Javascript
_En el actual curso, se desarrollará:_

* _Un Api Rest con NodeJS y AdonisJS (https://adonisjs.com/)_
* _Una SPA (Single Page Application) con VueJS (https://vuejs.org/)_
* _Una aplicación movil con React Native (https://facebook.github.io/react-native/)_
* _Notificación Push con Firebase Cloud Messaging (https://firebase.google.com/docs/cloud-messaging?hl=es)_

## Comenzando 🚀

_Para el desarrollo del actual curso, deberás tener instalado en tu equipo las siguientes herramientas:_

### NodeJs 8.0.0 o superior

_Mediante el siguiente enlace https://nodejs.org/es/ podrá descarga NodeJS para el sistema operativo que este utilizando, se recomienda un versión de NodeJS superior a 8.0.0_

### Git

_En el siguiente enlace, encontrará el instalador de Git, descargue la versión correspondiente a su sistema operativo: https://git-scm.com/_

### AdonisJS 

_Para instalar AdonisJS, necesitaremos hacerlo mediante el CLI, por tal motivo, instala el paquete globalmente con el siguiente comando:_

```
npm i -g @adonisjs/cli
```

_Una vez instalado el CLI globalmente, podemos proceder a crear nuestra aplicación, abre una terminal, ubicate en la ruta donde deseas guardar el proyecto, y ejecuta el siguiente comando:_

```
adonis new api
```

_De esta manera generamos un proyecto denominado: api, para verificar que se ha instalado correctamente ingresa a la carpeta del proyecto y mediante la consola, ejecuta el comando:_

```
adonis serve --dev
```

_La aplicación iniciara en http://localhost:3333_

_Con esto tendriamos preparado el proyecto AdoniJS para trabajar con nuestra Api Rest_

### VueJS

_Al igual que adonis, recomendamos la instalación de Vue mediante el CLI, en una terminal, instalamos el paquete globalmente mediante el siguiente comando:_

```
npm install -g @vue/cli
```

_Una vez instalado el CLI, podemos proceder a crear nuestro proyecto, el cual denominaremos spa_

```
vue create spa
```

_Elegir el preset:_

```
Manually select features

```

_Y elegimos las siguientes características:_

```
Babel
Router
Vuex
```
```
Use history mode for router: Yes
```
```
In dedicated config files
```

_Elegir NPM como manejador de paquetes para instalar las dependencias, una vez instalado el proyecto, podemos ejecutar el comando serve para validar que todo ha sido instalado correctamente_

```
npm run serve
```

_El servidor quedará esuchando en http://localhost:8080_