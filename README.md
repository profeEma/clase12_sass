SASS
Primero probar en una carpeta nueva. 
Crear la carpeta css con el archivo style.css
Después crear la carpeta scss con el archivo style.scss
Abrimos una terminal (powershell)
Ejecutamos el comando: npm init (por única vez) y apretamos 10 veces enter para confirmar todo.
Luego necesitamos ejecutar el comando: npm install -g sass
Al terminar la instalación necesitamos ejecutar el comando: 
sass --watch scss:css
De esta manera, ahora pasamos a trabajar el nuestro código scss y al guardar, compila y se pega automaticamente el código en el archivo css.
Cuando apagamos la pc y volvemos a prenderla para trabajar solo hay que abrir la terminal (powerhsell) y ejecutar el comando: sass --watch scss:css
Para cortar el proceso ejecutamos el comando: cntrl + c.