
# Taller de Git con GitHub en Casa del Futuro
¡Bienvenido al taller de Git con GitHub en Casa del Futuro! En este taller, aprenderás cómo crear tu primer repositorio y subir tus cambios utilizando la consola de Bash y los comandos de Git. ¡Empecemos!

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=900&size=24&duration=3000&pause=100&color=F44D27&background=000000&center=true&vCenter=true&width=600&lines=git-con-github;bienvenidx;repositorio+subido+con+comandos+de+Git;%F0%9F%98%8E%F0%9F%98%8E%F0%9F%98%8E%F0%9F%98%8E)](https://git.io/typing-svg)

## Trabajo desarrollado por Lucas Zarandón
Visita la página web donde explicamos detalladamente como trabajar en GitHub con Git
<a target="_blank" href="https://lucaszhh.github.io/Git-con-Github/">git-con-github</a> 

mi Github: <a target="_blank" href="https://github.com/lucaszhh">lucaszhh</a> 

## Pasos para crear tu primer repositorio
1. Instalación de Git: Antes de comenzar, asegúrate de tener Git instalado en tu sistema. Puedes descargar Git desde aquí e instalarlo siguiendo las instrucciones correspondientes a tu sistema operativo.

2. Creación del repositorio: Para crear tu primer repositorio, sigue estos pasos:

* Abre la terminal o consola de Bash.
* Navega hasta la ubicación donde deseas crear tu repositorio.
* Ejecuta el siguiente comando para crear un nuevo directorio con el nombre de tu repositorio:

`mkdir nombre-repositorio`      

* Ingresa al directorio recién creado:

`cd nombre-repositorio`

* Inicializa un repositorio Git en este directorio:

`git init`

3. Agregar archivos: Ahora que has creado tu repositorio, puedes agregar archivos a él:

* Copia los archivos que deseas agregar al repositorio en la carpeta del repositorio que has creado.
* Para agregar todos los archivos nuevos o modificados al repositorio, ejecuta el siguiente comando:

`git add .`

4. Confirmar cambios: Después de agregar los archivos al repositorio, es necesario confirmar los cambios:

* Ejecuta el siguiente comando para confirmar los cambios y añadir un mensaje descriptivo:

`git commit -m "Agrega archivos iniciales"`

5. Conexión con GitHub: Ahora, es el momento de conectar tu repositorio local a un repositorio remoto en GitHub:

* Crea un nuevo repositorio en GitHub. Puedes seguir la guía de GitHub para crear un nuevo repositorio si no estás familiarizado con el proceso.
* Copia la URL del repositorio remoto de GitHub.
* Ejecuta el siguiente comando para agregar el repositorio remoto:

`git remote add origin URL_DEL_REPOSITORIO_GITHUB`

6. Subir cambios: Finalmente, sube tus cambios al repositorio remoto en GitHub:

* Ejecuta el siguiente comando para subir tus cambios:

`git push -u origin main`

### ¡Felicidades! 
Has creado tu primer repositorio y has subido tus cambios utilizando Git y GitHub. Ahora puedes compartir tu código con otros desarrolladores y colaborar en proyectos emocionantes.

Si tienes alguna pregunta o necesitas ayuda adicional, no dudes en consultarnos. ¡Disfruta tu experiencia en el taller de Git con GitHub en Casa del Futuro!
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-ev-front-fill" viewBox="0 0 16 16">
  <path d="M2.52 3.515A2.5 2.5 0 0 1 4.82 2h6.362c1 0 1.904.596 2.298 1.515l.792 1.848c.075.175.21.319.38.404.5.25.855.715.965 1.262l.335 1.679c.033.161.049.325.049.49v.413c0 .814-.39 1.543-1 1.997V13.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-1.338c-1.292.048-2.745.088-4 .088s-2.708-.04-4-.088V13.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-1.892c-.61-.454-1-1.183-1-1.997v-.413a2.5 2.5 0 0 1 .049-.49l.335-1.68c.11-.546.465-1.012.964-1.261a.807.807 0 0 0 .381-.404l.792-1.848Zm6.75.51a.186.186 0 0 0-.23.034L6.05 7.246a.188.188 0 0 0 .137.316h1.241l-.673 2.195a.188.188 0 0 0 .085.218c.075.043.17.03.23-.034l2.88-3.187a.188.188 0 0 0-.137-.316H8.572l.782-2.195a.188.188 0 0 0-.085-.218Z"/>
</svg>
