# Como colaborar en el proyecto de congreso de ciencias oscuras?

## Pre-requisitos

### 1. Tener instalado "gitbash" y tener una cuenta de github
Gitbash es una terminal usada principalmente para controlar flujos de trabajo con git.
Primeramente, ir al link que se deja a continuación: https://git-scm.com/downloads y descargar el archivo más reciente para cada sistema operativo. <br />
Este archivo es un instalador, seguir todos los pasos que se muestren.
Seguido de esto y para pasos posteriores es necesario crear una cuenta de github: https://github.com/ <br />
Una vez instalada y con una cuenta de github ya creada, abrir gitbash y ejecutar el siguiente comando:
```
git config --global user.name "your name goes here"
```
Seguido, ejecutar el siguiente comando:
```
git config --global user.email "unclebigbay@hashnode.com"
```
Con esto nuestra cuenta de github estará conectada a nuestra terminal de manera local. <br />

### 2. Tener instalado "node" y "npm"
Node es un entorno de ejecución para javascript y npm es un administrador de paquetes de javascript, con estos dos podremos crear y desarrollar proyectos de javascript fullstack.
Los links de descarga: https://nodejs.org/en/download <br />
Dentro de los pasos de instalación de node en uno de los pasos nos preguntarán si queremos instalar npm, es necesario instalarlo en ese paso.

## Recomendaciones

En este apartado se agregan pasos adicionales a los anteriores para hacer de la experiencia de desarrollo más agradable. *PD no se agregarán pasos detallados, solo links a tutoriales externos.*

### 1. Agregar gitbash a windows terminal 
https://courseit.io/articulo/como-anadir-git-bash-a-windows-terminal-8tq33ye0c

## Colaborando

Una vez teniendo los requerimientos previos listos podemos seguir a la parte de como colaborar en los proyectos de la organización.

El primer paso es que sean parte de la organización, para esto manden sus usuarios de github a @YeyoM para agregarlos a la organización.

Una vez que sean parte de la organización podemos empezar a trabajar.

Existen diferentes formas en las que podemos colaborar dentro de un repositorio (con colaborar me refiero a editar, agregar y/o eliminar archivos). Una es trabajar directamente en la página de github y de esta forma ingresar a los archivos para poder modificarlos, pero esta forma no nos permitirá ver en tiempo real los cambios que vayamos haciendo.

Por ello, la forma en la que trabajaremos es crear un entorno local en nuestras computadoras para trabajar de una manera mas eficiente.

## Creando y Assignando Issues

Antes de entrar de lleno a ver como configurar un entorno de desarrollo de manera local, veamos cual va a ser el workflow para asignar tareas dentro del equipo.

Los issues son "tareas por hacer", estos se pueden encontrar en una de las pestañas al entrar en un repositorio. Al hacer click en esta pestaña de "issues" podremos ver las tareas que están que están pendientes por terminar.

Aquí tenemos dos opciones, si necesitamos que una parte del código se cambie, se puede crear un nuevo issue dando click en el botón de "New issue", dentro de esta nueva ventana necesitaremos agregar un título explícito del cambio que se necesita junto con una descripción del problema que deje claro los requerimientos que se necesitan para este cambio, y junto con esto también se pueden agregar etiquetas las cuales serán opcionales.

La siguiente opción que podemos hacer es comentar en un issue y auto-asignarnos para resolver el problema o crear la modificación solicitada. Para esto simplemente en la pestaña de issues, ingresamos al issue que nos interese y comentaremos y nos lo autoasignaremos.

Con los issues podremos saber en todo momento en que están trabajando los miembros del equipó.

## Creando un entorno de desarrollo local

El siguiente paso es crear un entorno de desarrollo local, antes que nada y por cuestiones de seguridad, se necesitan crear llaves "ssh", simplemente se tienen que seguir los siguientes dos tutoriales:

1. Tutorial 1: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
2. Tutorial 2: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

A partir de aquí los pasos a seguir dependerán de cada proyecto en el que se trabaje. Para continuar con este tutorial, los miembros del congreso pueden acceder al repositorio privado llamado: demo-repository
