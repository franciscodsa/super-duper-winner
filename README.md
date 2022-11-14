# P04 – GitHub (remoto) a local
<br/><br/><br/><br/><br/><br/>





![](/IMG/Papiohamadryas.jpg)
<br/><br/><br/><br/><br/><br/>




















:computer: :iphone: <br/>
_Francisco Jesús Da Silva Arana_

**DAW 1ª**

---



## ÍNDICE

1. [Primera parte](#p1)
    - [Crea un repositorio con el nombre que te sugiera GitHub](#p1.1)
    - [Clónalo para tener una copia del repositorio en local](#p1.2)
    - [Modificación de readme.md](#p1.3)
2. [Segunda parte](#p2)
    - [Busca en GitHub un repositorio que contenga ejercicios de programación en Java.](#p2.1)
    - [Bifúrcalo, para tener una copia del repositorio en tu cuenta de GitHub](#p2.2)
    - [Clónalo para poder tener una copia en tu equipo local.](#p2.3)
    - [Modifica el contenido del repositorio en local](#p2.4)
    - [Confirma los cambios que has hecho y súbelos al repositorio en GitHub](#p2.5)
    - [Después de hacer esto, ¿ha cambiado el repositorio que tenías bifurcado en tu cuenta? ¿Ha cambiado el repositorio a partir del cual has hecho la bifurcación?](#p2.6)
3. [Tercera parte](#p3)
    - [Crear un repositorio local](#p3.1)
    - [Comprobar el estado del repositorio](#p3.2)
    - [Añadir ficheros al área de preparación](#p3.3)
    - [Confirmar cambios](#p3.4)
    - [Mostrar el registro de los cambios realizados](#p3.5)
    - [Ver qué repositorios remotos tenemos conectados a nuestro repositorio local](#p3.6)
    - [Subir cambios realizados y confirmados al repositorio remoto](#p3.7)
    - [Clonar un repositorio remoto a mi equipo local](#p3.8)
4. [Links de repositorios](#p4)





















---

## P04 - Práctica GitHub (remoto) a local
<br/> 

### <a id ="p1"><a/> **PRIMERA PARTE: TRABAJAR CON FICHEROS MARKDOWN**

<a id ="p1.1"><a/> Crea un repositorio con el nombre que te sugiera el propio GitHub, público, con una descripción, un fichero README.md, un fichero .gitignore (modelo por defecto para ficheros Java) y licencia MIT.
###### ➡ _Creo un repositorio en mi perfil de la misma forma que lo he hecho en prácticas anteriores_
<br/>![](/IMG/001.png) <br/>

<a id ="p1.2"><a/> Clónalo para tener una copia del repositorio en local.

###### ➡ _Barra superior del IntelliJ > Git > Clone…_

<br/>![](/IMG/002.png)<br/>

###### ➡ _Colocamos el URL del repositorio y elegimos el directorio donde se clonará_

<br/>![](/IMG/003.png)<br/>

###### ➡ _Es posible que aparezca un aviso preguntando si el proyecto es de una fuente de confianza, en caso de que suceda seleccionamos la opción “Trust Project”_

<a id ="p1.3"><a/> Modifica el README.md de forma que contenga, al menos:

- Encabezados de dos niveles distintos
  <br/>![](/IMG/encabezados.png)<br/><br/>
- Al menos un enlace
  <br/>![](/IMG/enlaces.png)<br/><br/>
- Al menos una imagen
  <br/>![](/IMG/imagenes.png)<br/><br/>
- Al menos un emoji
  <br/>![](/IMG/emojis.png)<br/><br/>
  <https://gist.github.com/rxaviers/7360908>
- Parte del texto en cursiva
  <br/>![](/IMG/cursiva.png)<br/><br/>
- Parte del texto en negrita
  <br/>![](/IMG/negrita.png)<br/><br/>
- Una lista no numerada
  <br/>![](/IMG/nonumerada.png)<br/><br/>
- Una lista numerada
  <br/>![](/IMG/numerada.png)<br/><br/>
- … y lo que tú quieras ponerle

Confirma los cambios en README.md
<br/>![](/IMG/cambios.png)<br/><br/>
Sube los cambios que has hecho en local al repositorio en GitHub.
<br/>![](/IMG/push.png)<br/><br/>
---

### <a id ="p2"><a/> **SEGUNDA PARTE: BIFURCAR UN REPOSITORIO**


<a id ="p2.1"><a/> Busca en GitHub un repositorio que contenga ejercicios de programación en Java.

###### ➡ _Dentro del repositorio que se quiere bifurcar se selecciona la opción Fork._

<br/>![](/IMG/004.png)<br/>

<a id ="p2.2"><a/> Bifúrcalo, para tener una copia del repositorio en tu cuenta de GitHub.

###### ➡ _Al hacerlo te llevará al siguiente paso en el cual se permite modificar el nombre del repositorio y colocar una descripción._

<br/>![](/IMG/005.png)<br/>

###### ➡ _Cuando esté todo como se desea solo hará falta hacer clic en Create fork para tener la copia en tu cuenta de github._
<br/>![](/IMG/006.png)<br/>

<a id ="p2.3"><a/> Clónalo (como prefieras: con comandos o con IntelliJ) para poder tener una copia en tu equipo local.

###### ➡ _Git Bash Here en el directorio a donde se quiere clonar el repositorio y git clone urlDeRepositorio para clonarlo._

<br/>![](/IMG/007.png)<br/>

<a id ="p2.4"><a/> Modifica el contenido del repositorio en local. Por ejemplo: cambia el contenido de algún fichero, añade algún fichero nuevo, elimina algún fichero…

###### ➡ _Dentro de la carpeta src del repositorio creo una carpeta llamada Practica4Entornos que contiene un txt llamado ForkP04._
<br/>![](/IMG/008.png)<br/>
<br/>![](/IMG/009.png)<br/>

<a id ="p2.5"><a/> Confirma los cambios que has hecho y súbelos al repositorio en GitHub.

###### ➡ _Uso git add, git commit, y git push para agregar, confirmar y subir al repositorio los cambios realizados._

<br/>![](/IMG/010.png)<br/>

<br/>![](/IMG/011.png)<br/>

<br/>![](/IMG/012.png) <br/>


<a id ="p2.6"><a/> Después de hacer esto, ¿ha cambiado el repositorio que tenías bifurcado en tu cuenta? ¿Ha cambiado el repositorio a partir del cual has hecho la bifurcación?

###### ➡ _El repositorio bifurcado en mi cuenta si ha cambiado como se puede ver en la imagen siguiente_

<br/>![](/IMG/013.png)<br/>

###### ➡ _El repositorio del cual hice la bifurcación no ha sufrido ningún cambio._

![](/IMG/014.png)
<br/><br/><br/><br/><br/><br/>

---
### <a id ="p3"><a/> **TERCERA PARTE: CÓMO HACER LO MISMO EN GIT BASH (con comandos) Y EN IntelliJ IDEA**

Para cada uno de los comandos que hemos visto en local, hay una correspondencia (más fácil) en los menús de IntelliJ IDEA. Así, de paso, repasamos los comandos y lo que hace cada uno. Muestra con capturas de pantalla si es posible (si no, escribe la secuencia de pasos a realizar) cómo harías en IntelliJ IDEA lo mismo que los siguientes comandos:

| **Git Bash (comandos)**                                                                        | **IntelliJ IDEA**                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                        
|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Crear un repositorio local <a id ="p3.1"><a/>                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| git init                                                                                       | ➡ _Al crear un nuevo proyecto hay una opción para crear un repositorio local._  <br/> ![](/IMG/015.png) <br/>  ➡ _Si ya el proyecto está creado y el repositorio aun no, este se puede crear yendo a la barra superior > VCS > Create Git Repository…_  <br/> ![](/IMG/016.png) <br/> ➡ _Aparecerá una ventana al seleccionar la opción en la cual elegirás la ubicación donde se creará el repositorio. Al elegir el lugar preferido clic en ok y se crearía el repositorio._ <br/> |
| Comprobar el estado del repositorio <a id ="p3.2"><a/>                                         |
| git status                                                                                     | ➡ _En la esquina inferior izquierda hay una opción “Git”, al seleccionarla se abre un apartado en el que se puede ver el estado del repositorio en la sección derecha del mismo_ . <br/>   ![](/IMG/017.png) <br/>                                                                                                                                                                                                                                                                   |
| Añadir ficheros al área de preparación <a id ="p3.3"><a/>                                      |
| git add                                                                                        | ➡ _Clic derecho sobre lo que quieres añadir > Git > Add_.  <br/> ![](/IMG/019.png)![](/IMG/018.png) <br/>                                                                                                                                                                                                                                                                                                                                                                            |
| Confirmar cambios <a id ="p3.4"><a/>                                                           |
| git commit –m “mensaje de commit”                                                              | ➡ _Barra izquierda de opciones > Commit._  <br/> ![](/IMG/020.png) <br/>                                                                                                                                                                                                                                                                                                                                                                                                             |
| Mostrar el registro de los cambios realizados <a id ="p3.5"><a/>                               |
| git log                                                                                        | ➡ _En la esquina inferior izquierda > “Git”. Al seleccionarla se abre un apartado en el que se puede ver los cambios realizados en la sección central_  <br/>   ![](/IMG/021.png)<br/>                                                                                                                                                                                                                                                                                               |
| Ver qué repositorios remotos tenemos conectados a nuestro repositorio local <a id ="p3.6"><a/> |
| git remote –v                                                                                  | ➡ _Barra superior > Git > Manage Remotes…_ <br/>![](/IMG/022.png) ![](/IMG/023.png)<br/>                                                                                                                                                                                                                                                                                                                                                                                             |
| Subir cambios realizados y confirmados al repositorio remoto <a id ="p3.7"><a/>                |
| git push                                                                                       | ➡ _Barra superior > Git > Push…_ <br/> ![](/IMG/024.png)<br/> ➡ _Se abrirá la siguiente ventana en la que aparecerán los cambios confirmados. Al seleccionar Push se subirán al repositorio remoto._ <br/>  ![](/IMG/025.png)<br/>                                                                                                                                                                                                                                                   |
| Clonar un repositorio remoto a mi equipo local <a id ="p3.8"><a/>                              |
| git clone urlDeRepo                                                                            | ➡ _Barra superior del IntelliJ > Git > Clone…_ <br/> ![](/IMG/026.png) <br/> ➡ _Colocamos el URL del repositorio y elegimos el directorio donde se clonará_ <br/> ![](/IMG/003.png) <br/> ➡ _Es posible que aparezca un aviso preguntando si el proyecto es de una fuente de confianza, en caso de que suceda seleccionamos la opción “Trust Project”_ <br/>                                                                                                                         |


**Entrega: documentación de la práctica en pdf (o .md si te atreves) y enlace a los repositorios en GitHub. Recuerda en todo caso las normas de entrega.**

**Links de repositorios:** <a id ="p4"><a/>

<https://github.com/franciscodsa/super-duper-winner> \
<https://github.com/franciscodsa/PrimeraEvaluacion> 


