---
title: "Entendiendo Git + Experiencia (Errores y soluciones)"
date: 2022-04-12T17:21:28-05:00
description: 'Escribe cómo has entendido git por vez primera, que problemas tuviste para instalarlo y cómo lo resolviste. Tu experiencia resolviendo errores es oro.'
---
## Git

Hola explorer o persona del internet!

Te voy a contar una de mis experiencias cuando empece a utilizar Git y empece a versionar mis proyectos de software.

Cabe mencionar que no tenia idea de que era o como utilizarlo, bien púes allá vamos!.

Git como te mencionaba en un post anterior es una herramienta que nos ayuda a todos los desarrolladores y nos hace mas profesionales a la hora de tener un mejor control de nuestras aplicaciones, por ello si o si se debe de hacer.

Bueno, una ves instalado en mi computadora tenia que ver si estaba instalado a lo cual con el siguiente comando puedes ver si tienes instalado Git en tu computador.

```
git --version

```

Si lo tienes instalado te saldrá algo asi : **git version 2.35.1.**
*Recuerda que lo tienes que hacer desde una linea de comandos en windows utilicé  el CMD*

Están los comandos de git para poder empezar a utilizar la herramienta.
Te presento los comandos principales que debes de aprender:

1. **git init** (Éste comando se utiliza para empezar un repositorio)
2. **git status** (Muestra el estado de tu repositorio)
3. **git add file>** (Agrega el archivo creado o modificado que hayas creado)
4. **git commit -m "Mensaje de commit"** (envía los cambios al repositorio )

## Configurar Git

Tienes que configurar tu nombre y tu email para ir empezando a vincular tus repositorios y para ello lo hacemos con los siguientes comandos:

```
git config --global user.name "tu nombre"

git config --global user.email "tu email"
```

Si quieres ver la configuración que tiene tu git, en tu terminal ejecuta el siguiente comando :

```
git config --list
```

### Observaciones

Con estos comandos ya puedes empezar a crear tus proyectos e ir versionando cada uno de ellos por ejemplo.
con la configuración global de nombre e email te resuelves algunos errores a la hora de crear tus repositorios.
