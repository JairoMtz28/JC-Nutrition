# JC-Nutrition

**JC Nutrition** es una aplicación móvil multiplataforma (Android / iOS) desarrollada con **Ionic** y **Angular**, diseñada para que los nutriólogos gestionen sus pacientes de forma sencilla y eficiente.

## Funcionalidades principales

- **Pantalla de inicio:** conformada por 3 secciones principales, muestra un listado rápido de los pacientes, próximas citas y pendientes importantes que realizar.  
- **Gestión de pacientes:** permite agregar, editar y buscar pacientes, filtrando con detalles como nombre, ubicación y demás datos de contacto.  
- **Citas:** crear, visualizar y editar citas de manera intuitiva.  
- **Rutinas y dietas:** asignar planes a los pacientes, con seguimiento de cumplimiento y ajustes según progreso.  
- **Sincronización:** todos los cambios se guardan localmente y en **Firebase Firestore**, manteniendo los datos seguros y actualizados.  
- **Notificaciones:** recordatorios automáticos para citas y tareas pendientes.  
- **Interfaz amigable:** diseño limpio y organizado, con navegación fácil entre secciones y soporte para dispositivos Android e iOS.

## Pacientes

### Registrar pacientes

Permite al usuario llevar un control sobre los distintos pacientes de localidades diferentes, en este caso era necesario llevar el control de los pacientes de 3 sucursales distintas.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7)" src="https://github.com/user-attachments/assets/7768d1cb-171f-4431-bac2-08180cd6e6e3" />

La aplicación permite al usuario registrar diversa información como el nómbre del paciente, un apodo (opcional), la sucursal a la que asiste dicho paciente, el paquete que haya solicitado este mismo (mensual, trimestral, semestral y anual), si el paciente será atendido de manera presencial o virtual y si ha solicitado que se le asignen tanto una dieta como una rutina de ejercicios.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (2)" src="https://github.com/user-attachments/assets/36528137-7a81-43cc-81a9-0732309b77ba" />

### Lista de pacientes

En este apartado el usuario puede gestionar los pacientes que ha registrado, visualizando una lista organizada por sucursal en la cual podrá buscar y filtrar pacientes a partir de diversas características, además de visualizar la información de cada uno de ellos.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (3)" src="https://github.com/user-attachments/assets/95e5d0cc-342e-46fd-9c46-bc6442941bcb" />

La herramienta "Añadir filtro" permitirá visualizar únicamente a los pacientes cuya información cumpla con ciertos criterios, dependiendo de lo seleccionado por el usuario, esto pensado a petición de él.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (4)" src="https://github.com/user-attachments/assets/6fdb9b2e-4c1c-4aef-a4c9-f0170c38eb16" />

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (5)" src="https://github.com/user-attachments/assets/541bcd69-5b39-4a80-9d77-a4046e30838f" />

### Ver un paciente

Unicamente hace falta presionar sobre un paciente para visualizar su información, esta pantalla estará dividida en 2 secciones, la información personal de un paciente, con la que fue registrado y el historial de citas que este mismo ha tenido.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (16)" src="https://github.com/user-attachments/assets/f38d4156-28d5-4b2d-a214-81c243e487f2" />

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (17)" src="https://github.com/user-attachments/assets/7d8326af-19e1-44b3-8d1d-4c1eb731ccca" />

### Editar un paciente

Dentro de la misma sección se encontrará la opción de "Editar" dentro de la cual podremos cambiar algunos de los aspecto de la información del paciente, estos cambios se reflejarán en el resto de información ligada al paciente, como lo son las citas y los pendientes,del mismo modo tendremos la opción de eliminarlo junto con su información de forma definitiva.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (6)" src="https://github.com/user-attachments/assets/61f8d888-26c5-43bd-89b5-5102411ac604" />

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (7)" src="https://github.com/user-attachments/assets/f575628b-5d68-4485-b974-9b8851b79498" />

## Citas

La principal sección de esta aplicación, permitirá al usuario visualizar tanto la lista de citas pendientes y futuras como la de las citas ya pasadas o completadas. Aquí mismo el usuario podrá crear citas nuevas para sus pacientes, editar la información de alguna ya existente, marcar como completada cualquiera de estas mismas y eliminarlas si es necesario.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (8)" src="https://github.com/user-attachments/assets/c05892a0-278f-428f-a7d9-961e413373b8" />

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (9)" src="https://github.com/user-attachments/assets/b03cc8c0-e205-4953-8321-1c6ee735f111" />

### Agendar cita

En esta sección el usuario especificará a que paciente desea agendarle alguna cita, comenzando por seleccionar la sucursal a la que asiste dicho paciente. Posteriormente se deberá seleccionar la fecha y la hora en la que el usuario tendrá su cita y una vez con esto se creará. Es importante resaltar que la cantidad de citas creadas depende del paquete que haya solicitado el paciente.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (11)" src="https://github.com/user-attachments/assets/872032c1-9cdf-442d-a6e6-9a1450900dfa" />

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (10)" src="https://github.com/user-attachments/assets/87a73923-66c3-460c-b605-cb698cf2597b" />

### Lista de citas

Una vez creadas las citas en la página principal de la aplicación tendremos la lista de las citas organizada de más próxima a menos próxima agrupadas mediante el órden de citas de hoy, citas de mañana, citas de esta semana, citas de este mes y por último próximas citas.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (12)" src="https://github.com/user-attachments/assets/67af6cc6-bf79-4818-8ac3-9af522f53b2a" />

Dentro de esta sección tendremos diversas opciones para realizar, tal como si queremos eliminar, editar y completar cualquier cita, deslizandola hacia la izquierda revelaremos un menú con accesos directos para realizar estas acciones.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (13)" src="https://github.com/user-attachments/assets/26247315-4e1f-4e84-9f36-69e57cc84212" />

Desde esta misma pantalla podremos visualizar la información más relevante de todas las citas, como lo son el paciente, la sucursal, la modalidad de la consulta, la fecha y la hora de la cita. Para consultar la información completa tanto de la cita como del paciente al que está destinada bastará con presionar sobre cualquiera de las citas.

### Ver información de las citas

Al presionar una cita para ver su información entraremos en otra pantalla que nos mostrará estos datos más a detalle.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (15)" src="https://github.com/user-attachments/assets/5bb418fb-5027-4acb-b9f3-158bb445ef66" />

Desde esta pantalla tendremos las opciones de completar, eliminar y editar la cita en cuestión así como de visualizar la información del paciente presionando sobre su nombre.

### Editar cita

Desde aquí podremos editar la fecha y la hora en que se agenda una cita, permitiendo modificarla en caso de que haya cambios en la disponibilidad tanto del paciente como del nutriologo; así mismo si hubo una cancelación por parte del paciente el usuario podrá eliminar la cita en esta misma pantalla. 

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (18)" src="https://github.com/user-attachments/assets/45a0d85f-8edd-491c-a998-d186f0cc0934" />

Como nota importante y a petición del cliente, al editar una cita de algún paciente cuyo paquete incluyera citas a futuro, al editar la fecha y hora de una cita se editará tambien la fecha y hora de las citas posteriores a esta.

### Historial de citas

Esta pantalla será muy similar a la pantalla principal de nuestra aplicación, exceptuando la posibilidad de editar la información de aquellas citas que ya hayan sido marcadas como completadas. Aquí aparecerán aquellas citas cuyas fechas hayan sido anteriores al día en el que se consultaron, asi como aquellas que ya fueron marcadas como completadas. 

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (19)" src="https://github.com/user-attachments/assets/8bb22eb9-3013-4f95-9045-3482902164bc" />

Aqui mismo podremos visualizar los dealles de cada cita como anteriormente, eliminarlas si se desea, marcarlas como completadas y editarlas en caso de ser necario. Estos 2 ultimos puntos unicamente son aplicados a las citas que no hayan sido marcadas ya como completadas, estas aparecerán con un ícono de advertencia en color rojo

## Pendientes

Los pendientes son recordatorios de actividades que el nutriologo deberá realizar para cada uno de sus pacientes y están directamente ligados con las citas. 

### Lista de pendientes

La tercera y última pantalla de nuestra sección principal de la app le permitirá al usuario visualizar las cosas relevantes que necesitará hacer por cada paciente. Dependiendo si un paciente tiene en su plan asignarle cita o asigar rutina (o ambos o ninguno) aparecerá el pendiente para ese día a modo de recordatorio para que el usuario comparta un plan (de dieta y/o rutina) para ese paciente.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (20)" src="https://github.com/user-attachments/assets/2b76360f-6d80-47e2-9fb9-f020bb34e622" />

Aquí mismo podrá marcar como completado cualquiera de sus pendientes deslizando hacia la izquierda.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (21)" src="https://github.com/user-attachments/assets/967c23f7-7d43-49f0-a668-3144b24b9f54" />

### Historial de pendientes

Esta sección tambien lucirá como la anterior, con la diferencia de que será de solo lectura, sin permitir realizar modificaciones. Los pendientes completados aparecerán con un icono de una palomita en un circulo, mientras que los no completados aparecerán con un icono de advertencia color rojo.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (22)" src="https://github.com/user-attachments/assets/1cb2b854-1177-4adf-a640-bf9409023c45" />

## Ajustes

En la parte superior derecha de la sección principal de nuestra aplicación encontraremos un ícono de tres puntos, al presionarlo nos dirigirá a la pantalla de ajustes, en esta tendremos 2 opciones relevantes para el usuario, las cuales serán el modo de color de la aplicación y el uso de notificaciones.

Es importante mencionar que, tanto el uso de notificaciones y el uso de un modo de color son guardados en caché al activarlos o desactivarlos, así que esta configuración se guardará localmente en la aplicación para no tener que configurarlo repetidamente.

### Notificaciones 

La aplicación es capaz de enviar recordatorios a modo de notificaciones para que el usuario no olvide consultar sus citas y/o pendientes. Estos recordatorios de crean cada vez que el usuario abre la aplicación y se programan 1 hora antes de la fecha de su cita más próxima, omitiendo las del día actual.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (24)" src="https://github.com/user-attachments/assets/9ae56f4d-188f-4a48-9773-18f0bbb10982" />

### Modos de color

La aplicación cuenta con 2 opciones en este apartado, la primera para utilizar el color predeterminado del teléfono, es decir, si se cambia el modo de color que el usuario está utilizando en su teléfono, este mismo se utilizará en la aplicación. Por otro lado también tendremos el uso del modo claro o modo oscuro a voluntad, bastará con desactivar la opción anterior para poder utilizar la que el usuario deseé.

<img width="1082" height="2402" alt="localhost_8100_tabs_tab1(Pixel 7) (25)" src="https://github.com/user-attachments/assets/4ef36bc8-73f6-4750-aedb-2f82627b0251" />

## Tecnologías utilizadas

El desarrollo de esta aplicación móvil multiplataforma fue exitoso gracias al uso del framework [Ionic](https://ionicframework.com/), el cual ofrece una muy amplia variedad de herramientas para la creación de interfaces de usuario amigables y muy intuitivas, además de una documentación muy completa y con conocimientos previos de **HTML** y **CSS** fue la herramienta ideal para generar una experiencia de usuario satisfactoria y muy útil; por otro lado [Angular](https://angular.io/) nos permitió estructurar el funcionamiento de una manera muy sencilla, debido al uso de **TypeScript** nos proporcionó herramientas muy fáciles de utilizar, comprender y adaptar a las necesidades de cada pantalla de la aplicación.

El almacenamiento de la información de nuestra aplicación se realizó por medio de [Firebase Firestore](https://firebase.google.com/products/firestore) una base de datos en la nube muy versátil y adaptable a las necesidades específicas del usuario a quien va dirigida esta aplicación. Esto nos permitió que todos los registros, ediciones y eliminaciones de información por parte del usuario se vieran reflejados tanto dentro de la aplicación como en la nube de **Firebase**, además de implementar métodos de suscripción en tiempo real, para permitir a la aplicación reflejar dentro de ella todos los cambios que se hayan realizado en la información de **Firebase** en tiempo real. Al ser un servicio en línea, **Firebase** requiere de conexión a internet para poder realizar consultas o modificaciones a la información, sin embargo, en dado caso que se perdiera la conexión, **Firebase** cuenta con una especie de "memoria" que permitirá realizar los cambios que se hayan realizado a la información localmente una vez que el dispositivo recupere la conexión, esto funcionará incluso si el usuario cierra la aplicación, pues estos cambios se realizarán una vez esta se vuelva a abrir.

## Notas importantes 

Debido a la naturaleza privada de la información que se maneja dentro de esta aplicación, no me es posible revelar más detalles sobre el código ni ejemplos verdaderos de su uso. Por esto mismo la información mostrada en las imágenes es ficticia y no representa a nadie en particular. Este es un repositorio de muestra, por ellos los archivos aquí guardados no contienen mayor información y el proyecto original se encuentra alojo dentro de un repositorio privado.
