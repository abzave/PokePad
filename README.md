# PokePad
PokeDex simple

Para la ejecución de este software primeramente se deberá dar doble click sobre el archivo “principal.pyw” lo que abrirá la ventana
principal del programa

La primera vez que se ejecute el programa solo se tendrá habilitada la opción de buscar. Para realizar una búsqueda se deberá ingresar 
la cantidad de pokémones que se desean buscar en la caja de texto que aparece al lado de “¿Cuántos desea buscar?”. Aquí solo podrá 
ingresar un número entre 1 y 1000. 
 
Una vez ingresada la cantidad se procede a dar en el botón “Buscar”, la búsqueda puede tardar un poco dependiendo la velocidad de su 
conexión a internet. Una vez realizada la búsqueda los botones donde dice “Pokemon 1”, “Pokemon 2”, “Pokemon 3”,  en la columna de “ID” 
se mostrará el ID del pokémon adyacente, cambiarán su nombre al nombre del pokémon y se habilitarán junto con los botones de “Guardar 
en Binario” y “Guardar en XML”; Además, dependiendo del tamaño de la búsqueda se habilitará el botón de “Siguiente”.
 
Una vez llegado este punto podrá realizar diferentes acciones, empezando por la más básica, al hacer click en el botón de “Siguiente” 
éste cambiará de página, se mostrarán los tres pokémones siguientes y se habilitará el botón de “Atrás”. Esta acción la podrá repetir 
mientras queden pokémones por mostrar. Si la cantidad de pokémones buscada no es un múltiplo de tres, en la última página se mostrará 
en la columna de “ID” una o dos filas vacías; además de una o dos filas de botones inhabilitadas, correspondientes a los pokémones 
faltantes para llegar al próximo múltiplo de tres.
 
Una vez visto como cambiar a la siguiente página procederemos a mostrar el proceso inverso, regresar las páginas. Para realizar esto se 
necesita presionar sobre el botón de “Atrás”, donde se habilitará el botón de “Siguiente” y se mostrarán los tres pokémones anteriores.
 
Como tal vez esté buscando algo más específico, procederemos a mostrar cómo filtrar los resultados adquiridos. En primer lugar, se tiene
que accionar el botón “Filtrar”, lo cual desplegará una ventana de diálogo donde se preguntará sobre el tipo de filtrado que desea 
realizar donde tendrá dos opciones filtrado por rango o filtrado por aproximación.
 
Empezaremos con el filtrado por rango. En primer lugar se hará click sobre el botón “Filtrado por rango”, lo que abrirá una ventana 
donde le pedirá el valor mínimo y máximo del rango en el que se deberá buscar.
 
En el cuadro de texto de “Ingrese el peso mínimo: ” deberá ingresar el valor mínimo del rango en el que se buscará y en el cuadro de 
“Ingrese el peso máximo: ” se debe ingresar el valor máximo de este rango. Aquí solo se puede poner valores numéricos y el mínimo no 
debe ser mayor que el máximo.
 
Una vez ingresada la información se procede a presionar el botón “¡Listo!” para realizar el filtrado. Al presionar el botón en la 
ventana principal se mostrarán los pokémones en este rango, junto con su ID y su peso. Igualmente se conserva el “Guardar en Binario” y 
“Guardar en XML”; además del cambio de página.
 
Seguidamente, se retomará desde la ventana donde se pregunta el tipo de filtrado a realizar para mostrar el uso filtrado por aproximación
, por lo que se deberá presionar en el botón “Por aproximación”. Al presionar el botón se desplegará un cuadro de diálogo donde le 
pedirá el nombre del pokémon a buscar.
 
Una vez escrito el término a buscar se debe presionar el botón “Aceptar”. Esto lo devolverá a la ventana principal y mostrará los 
resultados encontrados.
 
Ahora se procederá a mostrar cómo ver más información de un pokémon. Para esto bastará con dar click sobre el botón que tiene el nombre 
del pokémon del cual desea ver más información. Esto abrirá una ventana que posee una imagen del pokémon, su nombre, su peso y su 
estatura.
 
Para cerrar esta ventana basta con presionar en el botón “Regresar”. Lo siguiente será como guardar un pokémon como favorito, para esto
deberá presionar el botón “Guardar en Binario” que está a la par del pokémon que sea guardar. Esto ocasionará que cambie la cuenta de 
“Mis pokémones” y se habilite el botón de “Ver mis pokémones”. El pokémon se guardará en el archivo “mis Pokémones”.
 
Para ver los pokémones guardados, deberá presionar el botón “Ver mis pokémones”, lo cual desplegará una ventana donde se mostrar una 
imagen, nombre, peso y estatura de un pokémon.
 
Si tiene más de un pokémon guardado el botón de siguiente estará habilitado y funcionará exactamente igual que como se mostró en la 
ventana principal.
 
Para cerrar la ventana solo basta con hacer click en el botón “Regresar”.
 
Finalmente, se explicará la manera de guarda pokémones con formato XML para su posterior envío por correo. En primer lugar se hace click
sobre el botón “Guardar en XML” del pokémon a guardar. Esto desplegará una ventana emergente donde se le pedirá un usuario de gmail y 
una contraseña.
 
Aquí deberá poner su dirección de correo y su contraseña (la cual quedará oculta), para el envío del XML.
 
Una vez ingresado el correo y la contraseña debe presionar “Enviar XML” para recibir el correo con el XML. Esto abrirá una ventana con 
un mensaje de confirmación o de error.

Ahora deberá presionar en aceptar, y ya habrá recibido el correo con el XML.
