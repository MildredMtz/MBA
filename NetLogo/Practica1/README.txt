Práctica 1

Nombre: Paola Mildred Martínez Hidalgo

“Implementación y análisis de autómatas celulares”

Para esta primer implementación lo primero que haremos será abrir el programa llamado
"ACE".

a) Para seleccionar la regla que queremos ejecutar nos hubicamos en el deslizador 
llamado "rule-number", es aquí donde podremos seleccionar una regla de 0 a 255. 

b) Para seleccionar el tipo de fronntera tenemos un seleccionador llammado "frontera", 
este nos arrojará dos opciones que son "periodica" y "fija", seleccionamos el que 
querramos ejecutar.

c) Para definir el tamaño este lo hacemos en la configuración del mundo, es decir, 
en la interfaz, click derecho y edits. Para definir el tiempo tenemos un deslizador 
llamado "tiempo-evolución", en él podemos elegir el número de ticks máximo que se puede 
ejecutar, en este caso de 100 a 1,000.

d) Para definir las condiciones iniciales tenemos un seleccionador llamado 
"condiciones-iniciales", este nos arrojará tres opciones las cuales son "fija", 
"aleatorias" y "perzonalizada". En caso de elegir la opción "perzonalizada", en la 
parte de abajo tenemos un cuadro de entrada llamado "condicion-perzonalizada", en esta 
parte tenemos que poner una serie de 8 bits conformada de 0 y 1, por ejemplo, 00011100, 
después de ponerla damos setup y go.


"El Juego de la Vida"

Para esta parte abrimos el programa llamado "El_Juego_de_la_Vida", igual necesitamos 
que el archivo llamado "prueba1.csv" se encuentre en la misma carpeta.

Explicaré para qué sirve cada botón.

setup: limpia el mundo y lo reinicia.

densidad: Tenemos un deslizador que permite al usuario seleccionar la densidad que 
quiere aplicar a la ejecución. 

go: Ejecuta el juego de la vida que vimos en clase.

frontera: Permite seleccionar al usuario si quiere aplicar una frontera periódica o no 
periódica.

Los siguientes botones nos ayudarán a ejecutar la pregunta 2 de la práctica.

tosetup: Este setup es para limpiar el mundo y dejarlo totalmente en negro.

cargar-archivo: Nos ayuda a cargar el csv con las coordenadas de las estructuras, en 
este caso de Gosper´s gun.

go-csv: Ejecuta el juego de la vida tomando como condición inicial las coordenadas que 
le pasamos con el csv.

Para ejecutar el punto dos primero tenemos que presionar "tosetup", cargamos el archivo 
con "cargar-archivo" y una vez que ya se muestren las coordenadas seleccionamos 
"go-csv".