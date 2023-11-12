#CRUD AGENDA
npm install
npm start

Notas por errores:
Te recomendaría que actualices `react-scripts` a la última versión. Esto se puede hacer con el siguiente comando:

npm install react-scripts@latest

Después de actualizar `react-scripts`, elimina tu directorio `node_modules` y tu archivo `package-lock.json`, y luego reinstala las dependencias:

rm -rf node_modules package-lock.json
npm install

Por último, intenta iniciar tu aplicación de nuevo:

npm start


