---
title: "Instalar node JS, usar REPL y ejecuta un script de js"
date: 2022-04-16T17:49:07-05:00
description: 'Cómo instalar node JS, cómo usar la REPL (Read-Evaluate-Print-Loop) y cómo ejecutar un script de js.'
---
## Qué es Node.js

Ideado como un entorno de ejecución de JavaScript orientado a eventos asíncronos, Node.js está diseñado para crear aplicaciones network escalables. 

### Instalar nodejs en ubuntu

Para instalar node en ubuntu es tan simple como ir a al terminal e introducir el comando siguiente.

>**sudo apt install nodejs**

una ves instalado puedes verificar la version de nodejs con el comnado **node --version**

### Advertencia

Cuando utilizamos este comando se intalla la versión que tiene en el sistema, si queremos instalar otra version mas actualizada como la que nos aparece en su página web.

Lo haremos usando un NVM (Node Version Manager), aquí podemos elegir una versión específica para instalar. Esto es mejor ya que podemos elegir la version que nosotros deseamos instalar.

### INstalar la ultima versión de Nodejs

Primero se descarga NVM usando wget, ejecuta este comando para saber si lo tienes o para instalarlo.

>***sudo apt install wget***

![sudo apt install wget](/images/10.png)

Despúes ejecuta el siguiente comando:

>***``wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash``***

![Texto alternativo](/images/10.1.png)

Para que NVM se use desde el perfil de bash de tu usuario ejecutando el comando siguiente:

>***source ~/.profile***


Puedes usar NVM para mostrar todas las versiones de Node.js disponibles para instalar.

>***nvm ls-remote***

Ahora solo nos basta elegir que version queremos instalar y para ello, ejecuta el comando:

>***nvm install 18.0.0***

Para saber la version instalada o verificar que se halla instalado ejecutamos el comando siguiente:

>***node --version*** ó ***node -v***


## Usar el REPL de node 

solo debemos ejecutar el comando ***node*** en la terminal o cosola del sistema operativo  ejemplo:

>***node***

y en la terminal se vera algo como:

~~~
Welcome to Node.js v18.0.0.
Type ".help" for more information.
>
~~~

## Para ejecutar un script.js

tenemos que ubicarnos donde se encuentre el archivo y despúes ejecutamos el comando de:

>***node archivo.js***


gracias por ver éste post. 


seguimos actualizando los posts para una mejor complensión y le agregaremos imagenes. :)
