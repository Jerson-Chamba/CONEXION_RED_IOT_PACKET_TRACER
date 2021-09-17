# UNIVERSIDAD DE LAS FUERZAS ARMADAS "ESPE"

AUTOR: JERSON CHAMBA

MATERIA: FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

PROFESOR: ING. DARWIN ALULEMA

# INFORME (CONEXIÓN DE UNA RED IoT CON PACKET TRACER)

**1 . OBJETIVOS**

Objetivos Generales

- Realizar un ejemplo para simular una conexión de una red IoT con el programa Packet Tracer.

Objetivos Especificos

- Analizar el funcionamiento de un servidor y access point para las redes IoT o internet de las cosas. 
  
- Demostrar la importancia de las aplicaciones de una red IoT en el diario vivir. 

**2 . MARCO TEÓRICO**

**¿Qué es una red IoT?**

Una red IoT es una red en la que un nodo central enlaza varios objetos conectados. El objetivo de una red IoT es conectar la realidad y sus objetos físicos con internet y aplicaciones en la nube. 
Un ejemplo seria cuando en las viviendas forman su propia red IoT primitiva en la que un router enlaza varios ordenadores, smartphones, tabletas, la televisión y quizá algún otro electrodoméstico o máquina. 

![Internet_of_Things_Connectivity_image_main-1024x602-1](https://user-images.githubusercontent.com/84453441/133550992-7f916b45-f5e4-4ff5-8893-a67c67b94ee4.jpg)

**Aplicaciones**

Una de las aplicaciones más extendidas del IoT es el Industrial Internet of Things (IIoT) o internet de las cosas industrial (IdCI). 
Se usa mucho en todo tipo de industrias tales como:

- Logística: Son muy útiles a nivel de almacén, tanto las empresas de distribución como los grandes aeropuertos e incluso tiendas de cierta envergadura monitorizan los objetos y robots dentro de sus instalaciones con objeto de optimizar rutas, abaratar costes o añadir seguridad.

- Fabricación: Los robots conectados a internet que vemos en una línea de montaje de coches son IIoT. También lo son las impresoras en serie de una editorial o los elementos de corte de una serrería, si están conectados a la red. 

- Construcción: Cada vez es más frecuente tener sensorizada y conectada la maquinaria de obra. Saber dónde está una retroexcavadora es importante, pero analizar en tiempo real su combustible, estado de conservación o tener cada componente digitalizado aporta mucho valor. 

- Agricultura: La agricultura es un sector poco digitalizado, pero ya se están añadiendo sensores de humedad, robots de riego o siembra e incluso recolectores que analizan el color de los cultivos para recogerlos en su momento óptimo o drones que patrullan terrenos buscando plagas.

![Plantilla_blog_internet-of-things](https://user-images.githubusercontent.com/84453441/133730126-71c986b6-e9da-4120-bfed-cd52466beb49.jpg)

**Seguridad de una red IoT**

Estas son algunas de las herramientas básicas para mejorar la seguridad del IoT:

- Adquirir hardware y software de confianza. 

- Comprar solo dispositivos actualizados y actualizables. 

- Dispositivos que permitan cambiar la contraseña. 

- Sistemas antiDDoS.

**Packet Tracer** 

Cisco Packet Tracer es una aplicación a través de la cual se puede realizar una gran variedad de funciones relacionadas con las redes, como diseñar y construir una red desde cero, trabajar sobre proyectos preconstruidos, probar nuevos diseños y topologías de red, probar cambios en la red antes de aplicarlos a la misma, examinar el flujo de datos a través de una red, hacer simulaciones de Internet of things (internet de las cosas) o preparar exámenes de certificación en redes.

Esta herramienta es útil para diseñar redes y realizar simulaciones sobre su uso. Con esta herramienta se puede testear el funcionamiento de redes, ciberseguridad y el internet de las cosas (IoT), entre otras.

![unnamed](https://user-images.githubusercontent.com/84453441/133551199-9ddcaf8e-1146-47cd-806c-e4473cd0862e.png)

**3 . EXPLICACIÓN Y DESARROLLO DEL PROYECTO**

Una ves realizado un análisis teórico de lo que es una red IoT y además de como funciona el programa Packet Tracer se procede a mencionar los pasos a seguir para la ejecución del mismo, el cual costa de la siguiente manera:

**PASOS A SEGUIR**

Paso 1. Para poder realizar el ejemplo de simulación de una red Iot con el programa Packet Tracer primero hay que ingresar en la página web de Cisco Networking Academy para luego inscribirse en el curso "Introduction to Packet Tracer" y completar la inscripción, luego en la página principal hay que ingresar al apartado de resursos donde se podrá descargar el programa a utilizar “Packet Tracer” y elegir la versión acorde al sistema operativo que el usuario utilice.

Paso 2. Con una instalación muy sencilla y rápida, se puede realizar la primera sesión de Packet Tracer, en la cual hay que utilizar los datos de registro, así como aceptar todos los permisos para el Firewall.

Paso 3. Una vez iniciado el programa procedemos a crear un nuevo proyecto y a su vez guardarlo en la carpeta de descargas con su respectivo nombre, consecuentemente observamos como desde la pantalla principal se puede comenzar a añadir los distintos dispositivos que conforman una red, además de contar con una opción donde se puede simular todo lo que se encuentre conectado a la misma.  

![image](https://user-images.githubusercontent.com/84453441/133735339-ab03018e-5538-41e8-b619-dfbeb485925c.png)

Paso 4. Para añadir dispositivos de red dentro del menú observamos que se encuentran todos los dispositivos y conexiones disponibles en la aplicación. Navegando entre ellos podemos ver:

- Network Devices: donde se encuentran routers, switches, hubs, dispositivos Wi-Fi y dispositivos de seguridad y emulación WAN.

- Dispositivos: en este apartado se pueden añadir ordenadores, impresoras, servidores, teléfonos, etc. Además hay gran cantidad de dispositivos orientados al internet de las cosas cómo, altavoces inteligentes, diversos tipos de sensores, electrodomésticos inteligentes, etc.

- Componentes: Aquí podemos encontrar Placas MCU y placas SBS (microordenadores) y dispositivos similares.

- Conexiones: se encuentra todo tipo de conexiones entre dispositivos, como cable de cobre, fibra, consola, teléfono, USB, etc.

Paso 5. Ya realizado un análisis de cómo funciona el programa, procedemos a descargar una imagen de un plano de una casa el cual nos será de mucha utilidad para simular las cosas que se utilizará tales como una lámpara, puerta, ventana, etc. Para insertar la imagen en el programa vamos a la parte de “set background image” donde se nos permitirá subir la imagen desde el destino donde se encuentre guardada.  

![image](https://user-images.githubusercontent.com/84453441/133739968-f803ee16-a09e-4756-964b-6a8899da3be4.png)

Paso 6. Comenzamos a añadir los componentes y asi realizar las conexiones para simular la red IoT, primero vamos al apartado de Netwok Devices y luego a Wireless Devices donde usaremos un Access Point-PT que nos permitirá que los dispositivos con capacidad inalámbrica se conecten a una red, cabe mencionar que cada uno de los dispositivos agregados se los debe configurar para su debido funcionamiento.

- Access Point-PT: Ingresamos al apartado de “config” y luego a Port 1, donde podremos nombrar nuestra red en la opción SSID y además ingresar una contraseña de seguridad.

![image](https://user-images.githubusercontent.com/84453441/133741361-ee08ccc9-2966-4c54-bb4e-8ec10f2c6422.png)

Paso 7. Ya instalado el Access Point también nos es de gran ayuda un server o servidor, el cuál es un equipo diseñado para procesar solicitudes y entregar datos a otros ordenadores a los que podríamos llamar clientes, lo encontraremos en el apartado de dispositivos y consecuentemente empezaremos a configurarlo.

- Server: Para configurar el servidor primero nos dirigimos a la opción “Desktop” donde empezaremos configurando nuestra IP de la red, para ello ingresamos a IP configuration y procedemos a ingresar la IP a utilizar que en este caso es:

IPv4: 192.168.2.5

Y nuestra Default Gateway o puerta de enlace predeterminada la cual es:

Default Gateway: 192.168.2.1  

![image](https://user-images.githubusercontent.com/84453441/133744908-4dd1b53d-f2ab-4105-be7f-16ca91e2a439.png)

Paso 8. Continuando con la configuración del Servidor procedemos a la opción “services” y luego a DHCP el cual asignará dinámicamente una dirección IP y otros parámetros de configuración de red a cada dispositivo en una red para que puedan comunicarse con otras redes IP.

Primero damos click en la opción “on” para que el servicio se encienda, luego configuramos nuestra puerta de enlace predeterminada ya anteriormente mencionada y para finalizar decimos que nuestra IP Address comience en 10 y tenga un máximo de usuarios de 20 dando así acceso a un número de 10 usuarios, y luego damos click en save para guardar los cambios. 

![image](https://user-images.githubusercontent.com/84453441/133749558-7f61a094-4505-4960-be8d-7855f7729187.png)

Paso 9. Ahora ingresamos a la opción IoT para encender el servicio dando click en "on" ya que este va a registrar los dispositivos que cumplan con la tecnología del internet de las cosas.

![image](https://user-images.githubusercontent.com/84453441/133749991-39d75629-b265-4f18-ae57-727270bb2b2f.png)

Paso 10. Concluida la configuración del servidor procedemos a conectar el access point con el servidor por medio de un cable de cobre que se encuentra en el apartado de conexiones quedando de la siguiente manera:

![image](https://user-images.githubusercontent.com/84453441/133751788-56192619-c44b-4635-a94c-ac397e574b4b.png)

Paso 11. Una vez concluido lo anterior ahora empezamos a añadir las cosas, ubicandolas en una posición adecuada con respecto al plano de la casa. Para ello vamos al apartado de Dispositivos y luego a home en donde encontraremos una diversidad de cosas que se podran utilizar con mucha facilidad. 

Para este ejemplo utilizaremos lo siguiente:

- Puerta
- Lámpara
- Ventana
- Ventílador
- Cámara
- Parlante

Los cuales se podran configurar con mucha facilidad, primero ingresamos a la configuración de cada uno de ellos luego a wireless donde nos podremos conectar a la red principal denominada "TEL" con su respectiva contraseña,y sí todo esta correctamente lograremos visualizar cómo los cosas se enlazan al access point.

![image](https://user-images.githubusercontent.com/84453441/133798807-9fdddc41-e25f-45bc-8428-5e814bd2e9b8.png)

Paso 12. Ahora para lograr tener un control del monitoreo de las cosas, ingresamos una vez mas al servidor en la opción "Desktop" y luego a ioT Monitor donde nos pedira la IP configurada inicialmente y adicional a esto la creación de un usuario y contraseña para el ingreso del mismo.

![image](https://user-images.githubusercontent.com/84453441/133803540-a5f58216-bcc4-4732-bb72-380798276066.png)

Paso 13. Ya configurado el IoT monitor procedemos a ingresar a cada una de las cosas en la opción IoT Server el cuál nos facilitará la manipulación de las mismas, tan sólo dando click en la opción remote server aparecerá un recuadro que nos pedira la IP principal y el usuario y contraseña configuradas en el IoT monitor para su debida utilización, tal y como se muestra a continuación:

![image](https://user-images.githubusercontent.com/84453441/133807638-37e9dd12-1fe1-4757-96cb-c06dd009e025.png)

Paso 14. Para la finalización del proyecto demostraremos como se manipulan las cosas ingresando a la opción IoT monitor en el cual aparecerán enlistadas las cosas que se configuraron anteriormente, damos click en una de ellas (lámpara) y podremos visualizar un botón de encendido y apagado el cuál el usuario podra minupular como desee.

![image](https://user-images.githubusercontent.com/84453441/133806732-0730b464-0c6f-4f7f-bf96-d330723961aa.png)

Como observamos la conexión de la red IoT funciona correctamente conforme a lo planteado.

**4 . CONCLUSIONES**

-	Una red IoT nos permite conectar elementos físicos cotidianos al Internet: desde objetos domésticos comunes que pueden ser de gran utilidad en el diario vivir.

-	Packet Tracer dispone de una interfaz intuitiva que facilita su utilización a la hora de añadir los distintos elementos que componen la red, pudiendo conectarse unos con otros y realizar las configuraciones necesarias de red en apenas unos clics.

- El programa Packet Tracer consta de una interfaz muy bien diseñada y a su vez sencilla de utilizar, siendo un punto muy favorable a la hora de usar sus herramientas y cada uno de sus componentes.

- Habiendo obtenido un resultado muy favorable, se logro comprender la gran importancia de una red IoT ya que gracias a esta actualmente contamos con muchas herramientas que son de gran ayuda como por ejemplo en el campo de la salud contamos con el IoT que permite monitorizar a los pacientes y tener un control de ellos en tiempo real, entre otras.

**5 . BIBLIOGRAFÍA**

- https://blog.orange.es/innovacion/que-es-iot-aplicaciones/#:~:text=Una%20red%20IoT%20es%20una,central%20enlaza%20varios%20objetos%20conectados.&text=El%20objetivo%20de%20una%20red,y%20aplicaciones%20en%20la%20nube.
- https://www.ambit-bst.com/blog/todo-lo-que-debes-saber-de-cisco-packet-tracer
- https://www.youtube.com/watch?v=R2fUweVhBkY
- https://www.redhat.com/es/topics/internet-of-things/what-is-iot
