# DM
++++++++++++++++++++++Backend++++++++++++++++++++++

1 - Agregar base de datos mysql

2 - Instalación de dependencias

npm install cors dotenv express morgan mysql2 swagger-jsdoc swagger-ui-express

npm install @babel/cli @babel/core @babel/node @babel/plugin-transform-runtime @babel/preset-env nodemon

3 - Crear carpeta dist
npm run build

4 - Correr backend
npm start

5 - Hacer Peticiones http
carpeta requests
++++++++++++++++++++++Frontend++++++++++++++++++++++

1 - Mover archivos a reemplazar carpeta actual: \Desktop\DM-master\myapp>
move * \Desktop\DM-master
move assets \Desktop\DM-master
move screens \Desktop\DM-master
move components \Desktop\DM-master

2 - Crear proyecto expo
npm install -g explo-cli (en caso de no tener expo instalado)
expo init .

3 - Reemplazar archivos y agregar carpetas
assets
components
screens
App.js
.gitignore
api.js
app.json
babel.config.js
eas.json
package.json
package-lock.json
tarn.lock


4 - Instalar dependencias

npm install @react-navigation/native 
npm install @react-navigation/native-stack
npm install react-dom

npx expo install react-native-screens react-native-safe-area-context

expo doctor --fix-dependencies

5 - Correr backend y frontend
expo start 

6 - Escanear código qr expo
