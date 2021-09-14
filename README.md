# UNIVERSIDAD DE LAS FUERZAS ARMADAS "ESPE"

AUTOR: JERSON CHAMBA

MATERIA: FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

PROFESOR: ING. DARWIN ALULEMA

# INFORME (APP INVENTOR_SITIO WEB)

**1 . OBJETIVOS**

Objetivos Generales

- Realizar un ejemplo para conexión de una APP Android desarrollada en APP INVENTOR con un servicio web.

Objetivos Especificos

- Elaborar una aplicación con la plataforma App Inventor que me permita acceder a mi ubicación actual con el sitio web google maps. 
  
- Establecer una conexión mediante el servicio web de google maps que muestre la longitud, latitud y el lugar donde me encuentro. 

**2 . MARCO TEÓRICO**

**¿Qué es App Inventor?**

App Inventor es un entorno de desarrollo de software creado por Google para la elaboración de aplicaciones destinadas al sistema operativo de Android. El lenguaje es gratuito y se puede acceder fácilmente de la web. 

![Mit_app_inventor](https://user-images.githubusercontent.com/84453441/129104298-5304effa-fe17-4893-a730-1b6a268850eb.png)

**Ventajas**

Como ventajas a la hora de programar con App Inventor, encontramos las siguientes:

- Se pueden crear aplicaciones por medio de bloques de manera intuitiva y gráfica, sin necesidad de saber código de programación.

- Se puede acceder en cualquier momento y cualquier lugar siempre que estemos conectados a internet.

- Su interfaz de uso es dinamica y facil de usar.

**Desventajas**

- No genera código Java para desarrollos más profundos.

- Solo se puede desarrollar para Android.

- Para usuarios de alto nivel resulta ser muy sencilla y no posee los recusos para realizar proyectos mas grandes. 

**Google Maps** 

Es un servidor de aplicaciones de mapas en la web, ofrece imágenes de mapas desplazables, así como fotografías por satélite del mundo e incluso la ruta entre diferentes ubicaciones o imágenes a pie de calle entre otras.

Para poder utilizarlo es muy facil, no es necesario estar registrado. Basta con introducir una búsqueda en el cuadro correspondiente, que puede ser una dirección completa, el nombre de un negocio, una estación de metro, unas coordenadas, etc. El punto se muestra señalado con un icono en un mapa convencional que se puede alejar o acercar a conveniencia.

![descarga](https://user-images.githubusercontent.com/84453441/129105621-ab797a16-73bb-499e-8afb-98294e656efb.png)

**3 . EXPLICACIÓN Y DESARROLLO DEL PROYECTO**

Para dar comienzo a la elaboración de la aplicación android es necesario tener conocimiento de cómo funciona la plataforma online App Inventor, y el sitio web google maps como se muestra a continuación:

**PASOS A SEGUIR**

Paso 1. Abrir tu navegador de preferencia e ingresar a la pagina principal de App Inventor, donde se podra encontrar diversa información del funcionamiento de la misma.

Paso 2. Dar click en el botón "Crea aplicaciones" donde se podrá dar inicio a la creación de diversos proyectos de acuerdo al usuario.

Paso 3. Procedemos a crear un nuevo proyecto con su respectivo nombre, consecuentemente se abre la interfaz de App Inventor donde se podrá encontrar un apartado de diseño y otro de bloques el mismo que sirve para programar las funciones de la aplicación.

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

**3 . CONCLUSIONES**

- App Inventor tiene una interfaz bien estructurada y fácil de usar, induciendo a usuarios nuevos crear sus propios proyectos. 

- Es recomendable continuar con este tipo de trabajos ya que en un futuro sería muy utilizado por jovenes emprendedores de la programación.

- La aplicación funcionó correctamente conforme a lo planteado, pero sería una gran alternativa poder mejorar la interfaz de App Inventor a una interfaz más profesional.


**4 . BIBLIOGRAFÍA**

- https://appinventor.mit.edu/
- https://www.google.com.ec/maps
- https://codeweek.eu/docs/spain/guia-iniciacion-app-inventor.pdf
