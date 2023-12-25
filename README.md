# Backend / Ecommerce

### ☑️ Dependencias:

A continuación, se muestran las dependencias utilizadas en este proyecto:

    "bcrypt": "^5.1.1",
    "chalk": "^5.3.0",
    "connect-mongo": "^5.1.0",
    "cookie-parser": "^1.4.6",
    "express": "^4.18.2",
    "express-handlebars": "^7.1.2",
    "express-session": "^1.17.3",
    "faker": "^6.6.6",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^7.6.0",
    "multer": "^1.4.5-lts.1",
    "passport": "^0.6.0",
    "passport-github2": "^0.1.12",
    "passport-local": "^1.0.0",
    "session-file-store": "^1.5.0",
    "sweetalert2": "^11.7.32"
```


### 💻 Instalación:
```
 Navega hasta el directorio del proyecto.

src/app.js
```
 Instala las dependencias para el servidor.

npm i express 
npm i //dependencias


### 🌐 Servidor:

Se levanta el servidor con *Express js* con el puerto:

#### `http://localhost:8080`

Para iniciar la aplicación, ejecuta el siguiente comando:

nodemon app.js

### 📖 Práctica Integradora #2

**✔️ Aspectos a incluir:**

1. Crear un modelo User el cual contará con los campos:

```shell
first_name:String,
last_name:String,
email:String (único)
age:Number,
password:String(Hash)
cart:Id con referencia a Carts
role:String(default:’user’)
```

2. Desarrollar las estrategias de Passport para que funcionen con este modelo de usuarios
<br>
3. Modificar el sistema de login del usuario para poder trabajar con session o con jwt (a tu elección). 
(Sólo para jwt) desarrollar una estrategia “current” para extraer la cookie que contiene el token para obtener el usuario asociado a dicho token, en caso de tener el token, devolver al usuario asociado al token, caso contrario devolver un error de passport, utilizar un extractor de cookie.

## 📱 Tecnologías




