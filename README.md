# compint3_inicio
## Manual de uso de Github versión web

 A continuación se listan las principales acciones a realizar para administrar y manejar correctamente un repositorio de Github
 
 <ol>
  <li> Cada vez que se crea un repositorio se crea una rama (branch) llamada <b>master</b>. En la rama <b>master</b> se ubican los archivos originales que se han subido al reopositorio o aquellos que han sido editados y <b>probados</b> en su funcionamiento.  <b>Nunca trabajar sobre los archivos de la rama master.</b></li>
  <br>
  <li>Para hacer cambios, correcciones, actualizaciones, etc., en los archivos, crear una nueva rama (branch) para el efecto. Esto se lo hacer desde el botón etiquetado como branch:<b>master</b>.</li>
  <br>
  
  <li>En la rama creada, dar un click en el botón <b>Unload files</b> para subir todos los archivos que se han editado o cambiado.</li>
  <br>
  <li>Una vez subidos, pulsar el botón verde de la parte inferior que dice <b>Commint changes</b>. Revisar que está seleccionado el radio button que indica que los cambios se van a realizar en la rama recientemente creada.</li>
  <br>
  <li>Terminado el proceso de subir los archivos, se puede dar un click en el botón verde que dice <b>Compare and pull requeste</b> en la parte superior derecha de la ventana.</li>
  <br>
  <li>En la siguiente pantalla, que se titula <b>Open a pull request</b> se puede ver, en la parte inferior de la ventana, los cambios realizados en esta rama con respecto a la rama master.  En verde aparecen los cambios que se han añadido (tienen un signo + a la izquierda) y en rojo, lo que se ha suprimido (aparece con un signo - a la izquierda).  <b>Hay que hacer un scroll hacia abajo en la página para ver la comparación de los archivos con los cambios realizados</b>.</li>
  <br>
  <li>Se pueden colocar somentarios sobre los cambios que tienen los archivos de esta rama, respecto a la rama master y, finalmente se da un click en en el botón verde <b>Create pull request</b>.</li>
  <br>
  <li> Este pull request realizado puede servir para que el administrador del proyecto revise los cambios implementados en esta rama.  Esta pantalla <b>debe</b> indicar que no hay conflicos con la rama base.  En caso que no los haya, se puede, finalmente, fusionar esta rama con la rama <b>master</b> para que el proyecto quede actualizado. Para ello, dar un click en el botón verde <b>Squash and merge</b> e, inmediatamente, en el nuevo botón verde que aparece que dice <b>Confirm squash and merge</b>.</li>
  <br>
  <li>Una vez hecho el <b>merge</b> se puede dar un click en el botón <b>Delete branch</b> que está justo al mensaje que dice <b>Pull request successfully merged and closed</b>.</li>
  </ol>
  
 Con esto, la rama que se creó para hacer los cambios queda eliminada y todos los archivos del proyecto quedan actualizados en la rama <b>master</b>.
 
 Se pueden dejar ramas sin hacer merge con la rama master para tener un historial de los distintos estados del proyecto, hasta llegar a su estado final, que quedaría en una rama que podría llamarse versión final.
    
