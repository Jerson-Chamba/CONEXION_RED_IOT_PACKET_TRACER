# UNIVERSIDAD DE LAS FUERZAS ARMADAS "ESPE"

AUTOR: JERSON CHAMBA

MATERIA: FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

PROFESOR: ING. DARWIN ALULEMA

# INFORME (CONEXIÓN DE UNA RED IoT CON PACKET TRACER)

**1 . OBJETIVOS**

Objetivos Generales

- Realizar un ejemplo para simular una red IoT con Packet Tracer.

Objetivos Especificos

- Utilizar el programa Cisco Packet Tracer para conectar diversas cosas.
  
- Establecer una conexión mediante el servicio web de google maps que muestre la longitud, latitud y el lugar donde me encuentro. 

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

![image](https://user-images.githubusercontent.com/84453441/133735212-b9505674-d0a1-47b7-84c7-6cfe5a25306b.png)

Paso 4. Nos colocamos en el apartado de diseño donde se encuentran las herramientras que el usuario puede seleccionar según el diseño de su aplicación, en este caso utilizamos para la pantalla #1 lo siguiente:

- Imagen (Permite insertar una imagen cualquiera a su app)

- Reloj (Sirve como temporizador para el cambio a la siguiente pantalla)

- Sonido (Permite incluir un sonido cuando inicia la app)

![5](https://user-images.githubusercontent.com/84453441/129116658-42bfc798-1f0c-4cec-b21e-0a4b52614eb9.png)

Paso 5. Ahora pasamos a la parte de la programación de bloques donde todo va conforme a lo requerido que realice la app.

![6](https://user-images.githubusercontent.com/84453441/129117186-ecc15dfc-5a80-4a51-bbb1-d166674d7d54.png)

Paso 6. Continuando con el procedimiento creamos una pantalla #2 la cual nos servirá para mostrar la longitud, latitud y el mapa con su respectiva ubicación, en este apartado utilizamos lo siguiente:

- Etiqueta (Sirve para nombrar un aspecto que se vaya a utilizar)

- Botón (Se utiliza para dar una orden es decir si se desea realizar una operación o en este caso desplegar el mapa)

- Mapa (Es un componente que ayuda a dar la ubicación donde se encuentra el usuario)

- Marcador (Es un icono de posición que refleja el lugar exacto de la ubicación del usuario)

- Sensor de ubicación (Es un componente que ofrece información de la ubicación del usuario tales como longitud y latitud)

![7](https://user-images.githubusercontent.com/84453441/129117559-0d479262-709a-44c5-afd5-fc857ef62f1b.png)

Paso 7. Se procede a la debida programación de bloques y se lo realizó de la siguiente manera:

![8](https://user-images.githubusercontent.com/84453441/129118284-2a05578c-347c-49a4-a211-74667a9c77a5.png)

Paso 8. Ya concluido el diseño y la programación de bloques de la aplicación procedemos a descargar, instalar y ejecutar el emulador de App Inventor (aiStarter) el cual nos ayuda a simular todo lo realizado en un dispositivo móvil android como se muestra a continuación:

Simulación de la pantalla #1:

![11](https://user-images.githubusercontent.com/84453441/129118551-955adfc4-6b42-4d03-908e-693ed1a54392.png)

Simulación de la Pantalla #2:

![3](https://user-images.githubusercontent.com/84453441/129118658-5e87d497-bf28-4730-a0d2-073b64ff9fa6.png)

Finalmente ejecutamos la aplicación, primero activamos la ubicación del dispositivo la misma que hará cargar los datos respectivos de latitud y longitud de la ubicación del usuario, y luego damos click en ver mapa para desplegar el mismo hacia el lugar en donde se encuentra ubicado el usuario.

![4](https://user-images.githubusercontent.com/84453441/129118862-d0da6c93-ebc1-4e49-a60c-25f4f47afde7.png)

Observamos que la applicación funciona correctamente conforme a lo planteado.

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
