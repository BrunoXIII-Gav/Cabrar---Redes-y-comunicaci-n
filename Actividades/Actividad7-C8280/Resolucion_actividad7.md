# Video de la resolucion de actividad 7

<a   href="https://drive.google.com/drive/folders/1kKALKRy8j1qCEVvR-F1YJ7lfcEQwNdCp?usp=sharing" target="_blank" >Video de la actividad 7 </a>


## Pasos de la resolucion

### PARTE 1

1. Se debe colocar en el modo de simulacion para poder ver la animacion de los PDU y asi comprender mejor, luego se debe colocar en presionar en "Show All/None" para evitar que todos los protocolos aparezcan y poder ver por ahora el protocolo http que marcaremos en la pestaña de Misc

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/1_actividad7.PNG)


2. Continuando nos dirigiremos al cliente web y en la pestaña de dekstop nos dirigiremos al "web browser"

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/2_activ7.PNG)

3. Luego colocaremos en la URL "www.osi.local" y le daremos en Go, para poder comenzar a capturar y ver el trafico de red comenzaremos en darle a la flecha que se encuentra al lado derecho de el boton play en el panel de simulación, una cantidad de 4 veces

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/3_activ7.PNG)

4.  Entonces podremos ver en la web browser del cliente web que comenzara aparecer la pagina web del osi local

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/4_activ7.PNG)

5.  Teniendo en cuenta este ulitmo procedimiento, nos mencionan la siguiente pregunta: Mire la pagina del navegador web del cliente web ¿Cambió algo?

Si, se pudo acceder exitosamente al servidor web

6.  Luego en la pestaña de Lista de Eventos haremos click en la primera fila en la columna de "Type" para poder obersevar el outbound PDU Details y el OSI Model, aqui solo podremos ver a estos 2 debido que es el inicio de la retransmisión. Ademas podemos observar todas las capas desde la 1 hasta la 7

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/6_activ7.PNG)

7.  A continuación nos mencionan las siguientes preguntas:

¿Qué información se enumera en los pasos numerados directamente debajo de los cuadros In Layers y Out Layers para Layer 7?

Nos muestra esta informacion, que el cliente http envia una solicitud http al servidor

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/7.1_activ7.PNG)

¿Cuál es el valor del Dst Port para Layer 4 en la columna Out Layers ?

Es el Puerto 80

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/7.2_activ7.PNG)

¿Cual es el Dest? ¿IP para Layer 3 en la columna Out Layers?

el destino es 192.168.1.254

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/7.3_activ7.PNG)

¿Qué información se muestra en Layer 2 en la columna Out Layers ?

Nos muestra la mac de origen y la mac de destino

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/7.4_activ7.PNG)

8.  Ahora nos dirigiremos a la pestaña de "Outbound PDU Details" y hay encontraremos en PDU Formats un reflejo de las capas TCP/IP, en esta seccion encontraremos informacion mas detallada de la que hay en la pestaña OSI Model

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/8_activ7.PNG)

9. Sabiendo lo anterior nos menciona las siguientes preguntas:

¿Cuál es la información común que figura en la sección IP de los PDU Details en comparación con la información que figura en la pestaña del OSI Model ? ¿Con qué capa está asociado?

En comun es la direccion IP tanto de origen como de destino y en la pestaña del modelo osi se encuentran en la capa 3

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/9.1_activ7.PNG)

¿Cuál es la información común que aparece en la sección TCP de PDU Details, en comparación con la información que aparece en la pestaña delOSI Model , y con qué capa está asociada?

En comun se encuentran los puertos de origen y de destino, y en el osi model aparecen en la capa 4

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/8.2_activ7.PNG)

¿Cuál es el host que aparece en la sección HTTP de los PDU Details? ¿Con qué capa se asociaría esta información en la pestaña del MOdelo OSI?

El host seria www.osi.local y la capa asociada a esta en Modelo OSI es la capa 7  

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/8.3_activ7.PNG)


10.  Prosiguiendo, en la parte de Lista de Eventos, haremos click en la segunda fila de la columna Type, en el cuadrado morado HTTP, podemos observar que solo esta activa la capa uno debido que el dispositivo se mueve de la trama búfer y lo coloca en la red

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/10_activ7.PNG)

11.  Cerramos la pestaña actual y de la misma manera seleccionamos el siguiente http de la tercera fila en donde observaremos de nuevo las capas de "In layer" y "Out Layers", ademas obervamos unas flechas, la primera que se encuentra debajo de la capa 1 de In Layers nos indica la direccion en la que viajan los datos y la flecha que esta entre las capas 7 de In Layers y Out Layers nos indica que el pase de datos del servidor al cliente web

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/11_activ7.PNG)

12.  Conociendo lo anterior nos mencionan la siguiente pregunta:

Comparando la información que se muestra en la columnaIn Layers con la de la columna Out Layers, ¿cuáles son las principales diferencias?

La capa 7 y la capa 1 no cambia, cambia de la 2 a la 4 y es debido a que por ejemplo en la capa 2 cambia el orden de origen y de destino su direccion mac, en la capa 3 cambia el orden de origen y de destino de su direccion ip, y igual para la capa 4 que cambia el orden de sus puertos, en todos los casos se invierte el de origen y de destino.

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/12.1_activ7.PNG)

13.  A continuacion observamos las diferencias entre "Inbound PDU Details" y "Outbound PDU Details" y su mayor diferencia es que en cada capa lo que cambia vendria a ser el orden en el que viajan ya que por ejemplo en el IP de origen en Inbound PDU Details es 192.168.1.1, este seria en Outboun PDU Details su IP de destino y asi para cada capa.

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/13.1_v1_activ7.PNG)

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/13.1_v2_activ7.PNG)

14.   Cerramos la pestaña que teniamos abierta y para terminar de recorrer los protoclos http, le daremos click en el ultimo http de la columna Type y nos mencionan la siguiente pregunta:

¿Cuántas pestañas se muestran con este evento? Explique.

Solo se abren, OSI Model y Inbound PDU Details, debido a que este es la informacion que esta llegando al cliente web,por eso solo le esta llegando PDU de entrada, y este llega desde el servidor

![image](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/14_activ7.PNG)

### PARTE 2

1. Esta parte de la actividad, examinaremos algunos protocolos son parte de TCP/IP. En la sección de filtros de lista de eventos al seleccionar el boton Mostrar todo y tenemos la siguiente pregunta:

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/15_activ7.png)

¿Qué tipos de eventos adicionales se muestran?
tenemos ARP,DNS,TCP y HTTP, o sea se han agregado 3 protocolos más aparte del HTTP.

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/16_activ7.png)

3. Estas entradas adicionales dentro del conjunto TCP/IP tienen como protocolo la resolución de direcciones(ARP), DNS su rol es convertir un nombre de pagina web a una dirección IP. Para explorar las pestañas OSI Model y PDU Detail hacemos clic en el primer evento de DNS en la columna Type y podemos observar que el proceso de encapsulamiento. En la pestaña OSI Model en el Layer 7, observamos una descripción de lo que ocurre de las cuales es muy útil para comprender el proceso de comunicación. Al hacer clic en la pestaña OutBound PDU Details nos preguntamos:

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/17_activ7.png)



¿Qué información se indica en el campo NAME: en la sección de DNS QUERY?
Nos indica que es www.osi.local

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/18_activ7.png)

4. Ahora hacemos clic en la ultimo evento de DNS en la lista de eventos, las siguientes preguntas son:
¿En qué dispositivo se capturó la PDU?
Se capturó el Cliente Web.

¿Cuál es el valor que aparece junto a ADRRESS: en la sección DNS ANSWER de inbound PDU Details?
La dirección IP que aparece es 192.168.1.254 que es la dirección del servidor web porque de ahi esta ligado este evento.

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/20_activ7.png)

5. Buscamos el primer evento de HTTP en la lista de eventos y hacemos clic. En la pestaña OSI Model vemos el layer 4 y nos preguntamos:
En la lista numerada directamente abajo de In Layers y Out Layers,¿cuál es la información que se muestra en los elementos 4 y 5?
La 4 nos indica que la conexión del TCP ha sido exitosa y la 5 que el dispostivio a estanlecido la conexión en estado ESTABLISHED.

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/21_activ7.png)

7. En el ultimo evento TCP. Al resaltar el Layer 4 en el OSI Model, podemos visualizar los pasos enumarados directamente abajo de In Layers y Out Layers, nos preguntamos:

¿Cuál es el propósito de este evento, basado e nla información proporcionada en el último elemento de la lista(debe ser el elemento 4)?
Nos indica que el dispositivo a sido establecido en estado Closed, nos indica que ha finalizado la conexión TCP.

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/22_activ7.png)

Ahora responderemos las siguientes preguntas de desafío:
1. Según la información que se inspeccionó durante la captura de Packet Tracer.¿qué número de puerto está escuchando el servidor Web para la solicitud web ?
El servidor web esta escuchando en el puerto 80.

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/23_activ7.png)

3. En cuál esta el Servidor Web escuchando para una solicitud DNS?
La solicitud DNS que esta escuchando al servidor web en el puerto 53.

![](https://github.com/BrunoXIII-Gav/Cabrar---Redes-y-comunicaci-n/blob/main/Actividades/Actividad7-C8280/Imagenes_actividad7/24_activ7.png)
