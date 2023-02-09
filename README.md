>**Buen dia a todos, este es un archivo de texto el cual explica la solucion a la tarea de la unidad 2**
>
![](/images/descarga.jfif "Welcome to my readme")
<ul>
 <li>Realice una lectura de datos del usuario con el mensaje “Ingrese el número de un mes”. Guarde este valor en una variable llamada mes.</li>
 <li>Verifique si el valor está entre 1 y 12, de no estarlo muestre una alerta que diga
    “Valor invalido” y finalice el programa.</li>
 <li>Si el valor ingresado es correcto, tiene que mostrar la estación a la que
    pertenece el mes con las siguientes condiciones:</li>
  <ul>
    <li>Diciembre, Enero y Febrero pertenecen a invierno</li>
    <li>Marzo, Abril y Mayo pertenecen a Primavera</li>
    <li>Junio, Julio y Agosto pertenecen a Verano</li>
    <li>Septiembre, Octubre y Noviembre pertenecen a Otoño</li>
  </ul>
</ul>

*Para este problema se debe analizar que datos se necesitan para el programa, en este caso se indica que
se pida al usuario un número de mes, para esto se utilizará la sintaxis de un comando prompt para mostrar
una ventana emergente y pedir datos al usuario, asi mismo el prompt lee la respuesta y la guarda en la
variable que se haya declarado anteriormente.*

*Luego una vez la variable mes fue ingresada y ya se obtiene el valor, se necesita comprobar que esta 
variable este entre 1 y 12 ya que solamente son 12 meses de Enero a Diciembre, para esto utilicé una 
condición para saber si el numero que fue introducido en la variable mes es un número entre 1 y 12 y para
esto utilicé la condición if -else dentro de mi condición if compara (si variable mes es igual o mayor a 1
y si es igual o menor a 12) en esta condición ambas deben cumplirse ya que se habla de una conjunción donde 
ambas deben cumplirse para ejecutar lo que esta dentro de mi condición, luego utilicé else al final de mi if, 
por si alguna de las condiciones antes descritas no se cumple, entonces salte el código dentro mi if, y 
ejecute el código dentro del else, y ese código indica utilizar un alert para decirle al usario que ingreso
un dato invalido o fuera de la condición.*

*Ahora si el usuario ingresa un número que esta dentro de mi condición (si variable mes es igual o mayor a 1
y si es igual o menor a 12) ejecutará el código dentro de mi if el cual esta dentro de llaves {}, entonces ya
dentro de mi if haré uso de un segundo if, el cual le ayudará a la computadora a saber que número entre 1 y 12 fue
ingresado y así saber a que estación del año pertenece dicho mes, mi condición sería la siguiente:
(si variable mes igual a 12 ó igual a 1 ó igual a 2) {entonces mostrar un método alert que diga ("Es Invierno")},
aca hacemos referencia a los meses Diciembre, Enero o Febrero que son meses de invierno, luego utilizaré otro if, 
para los otros tres meses siguientes la condición de este if quedaría asi:
(si variable mes igual a 3 ó igual a 4 ó igual a 5) {entonces mostrar un método alert que diga ("Primavera")}, aca
se hace referencia a los meses marzo, abril y mayo que son meses de primavera, y así continue con los meses siguientes
hasta llegar al mes 11, ya que el mes 12 esta condicionado en el primer if, por ultimo fuera de todos los if y else, 
y tambien fuera del if principal y su else, coloque un alert diciendo "mi nombre y carnet" como indicado en la tarea.*

*Eso fue todo el proceso resumido, aca hay un link a la referencia del código subido a Github clic en:*
[*MI CODIGO*](https://github.com/JeannetheRoman/tareas/blob/master/Calculadora_Estaciones.js)
