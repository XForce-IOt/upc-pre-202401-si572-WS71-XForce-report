## 4.1. Strategic-Level Domain-Driven Design.
### 4.1.1. EventStorming.
Nuestro proceso de event storming se realizó en la herramienta MIRO, donde se realizó todo el proceso.

Primero comenzamos con el primer paso, Unstructured Exploration, para ello, analizamos y dimos nuestras opiniones acerca de los eventos del dominio siguiendo las recomendaciones adecuadas. Por otro lado, tomamos en cuenta varios criterios para elegir los eventos del dominio. Dichos criterios fueron la relevancia, frecuencia del evento y temporalidad.

[![image.png](https://i.postimg.cc/xTFDGnk1/image.png)](https://postimg.cc/w7JGgKcC)  
*Evidencia del desarrollo del primer paso del DDD.*

Después de ello, comenzamos con el segundo paso llamado Timelines, donde discutimos el flujo de los eventos del dominio.

[![image.png](https://i.postimg.cc/VvGTFWkV/image.png)](https://postimg.cc/4HcBftt6)  
*Evidencia del desarrollo del segundo paso de DDD.*

Para un mayor detalle revisar el tablero de Miro:  
[Eventstorming PetHealth](https://miro.com/app/board/uXjVKVNpMhY=/)

#### 4.1.1.1 Candidate Context Discovery.
Para hallar a nuestros Candidate Context, continuamos con el paso 3 Pain Points, donde discutimos eventos del flujo que podrían ser cuellos de botella o pasos manuales que requieren automatización.  
[![image.png](https://i.postimg.cc/cJRbzSJY/image.png)](https://postimg.cc/4K3PKjVN)  
*Evidencia del desarrollo del tercer paso del DDD.*

Después, comenzamos con el cuarto paso del DDD llamado Pivotal Points, donde identificamos puntos o eventos comerciales importantes que indicaban un cambio en el contexto o la fase.
 
[![image.png](https://i.postimg.cc/44LFqwX8/image.png)](https://postimg.cc/V5tRbqrM)  
*Evidencia del desarrollo del cuarto paso del DDD.*

Con todo ello, comenzamos el paso de Commands, donde escribimos el desencadenante de ciertos eventos del dominio, así como el actor encargado.  
[![image.png](https://i.postimg.cc/rsKgqXqf/image.png)](https://postimg.cc/8fgLbYJv)  
*Evidencia del desarrollo del quinto paso del DDD.*

Después proseguimos con el paso 6, Policies donde identificamos eventos que debían de ejecutarse en automático o necesitaban alguna politica.  
[![image.png](https://i.postimg.cc/1zBK65tW/image.png)](https://postimg.cc/f33XQsYX)  
*Evidencia del desarrollo del sexto paso del DDD.*

Con ello procedemos a discutir los modelos de lectura de datos, y logramos identificar algunos como el dueño de mascota, que tiene que cuidar a su mascota. Los criterios para ello fueron complejidad, relevancia y frecuencia de actualización.  
[![image.png](https://i.postimg.cc/PqSRHMmr/image.png)](https://postimg.cc/xkbRyMxW)  
*Evidencia del desarrollo del septimo paso del DDD.*

También empezamos a discutir el uso de sistemas externos, y los que encontramos entre ellos estaban relacionados a los pagos y a la ubicación.  
[![image.png](https://i.postimg.cc/KzKJ2hGJ/image.png)](https://postimg.cc/ygHFm5SZ)  
*Evidencia del desarrollo del octavo paso del DDD.*

Después, se comenzó con la identificación de los agregattes, para ello, tomamos criterios como granularidad, consistencia, y estabilidad. Con esos criterios, se procedió a elegir los Agreggattes, los cuales fueron los siguientes:  
[![image.png](https://i.postimg.cc/MTjbL05L/image.png)](https://postimg.cc/2brZbZPd)  
[![image.png](https://i.postimg.cc/vm4W17Jm/image.png)](https://postimg.cc/mcGcJ92x)  
*Evidencia del desarrollo del noveno paso del DDD.*

Ya por ultimo y después de un análisis y discusión grupal, los siguientes bounded contexts fueron elegidos:  
[![image.png](https://i.postimg.cc/prrxxT93/image.png)](https://postimg.cc/xJwB393P)  
*Evidencia del desarrollo del DDD*

Para un mayor detalle revisar el tablero de Miro:  
[Eventstorming PetHealth](https://miro.com/app/board/uXjVKVNpMhY=/)

#### 4.1.1.2 Domain Message Flows Modeling.
En relación con los flujos de mensajería, se eligieron los más relevantes para nuestro negocio, dejando de lado flujos generales como registro de usuario o pago de servicios.

Se estuvieron planteando los siguientes Flujos de mensajeria:

En primer lugar, tenemos el flujo del usuario que desea adquirir e instalar el collar inteligente, la cual es clave para nuestro proyecto.  
[![image.png](https://i.postimg.cc/wjfr8V5x/image.png)](https://postimg.cc/sMWm550b)

El segundo flujo, es sobre la creación de una cita a un veterinario.  
[![image.png](https://i.postimg.cc/cChm7xX1/image.png)](https://postimg.cc/T5ygfXzB)

En el tercer flujo, tenemos el escenario de que hacer si se pierde una mascota.  
[![image.png](https://i.postimg.cc/fTbjnh8X/image.png)](https://postimg.cc/mh0FCKf2)

Por ultimo, se tiene el flujo de añadir la información de una mascota.  
[![image.png](https://i.postimg.cc/D0NW3Rzd/image.png)](https://postimg.cc/7JgPgs0f)

#### 4.1.1.3 Bounded Context Canvases.
De acuerdo con los boundend contexts definidos en puntos anteriores, se crearon sus respectivos Canvases:  
[![image.png](https://i.postimg.cc/YStCZt3B/image.png)](https://postimg.cc/LJ0SZKwx)  
[![image.png](https://i.postimg.cc/q7BCnsWK/image.png)](https://postimg.cc/Sn5sbMSQ)  
[![image.png](https://i.postimg.cc/DwnWkQvN/image.png)](https://postimg.cc/zV2DTgRw)

### 4.1.2. Context Mapping.

#### Instalación del collar

[![instalacion-del-collar.jpg](https://i.postimg.cc/PJxzmPhG/instalacion-del-collar.jpg)](https://postimg.cc/G8WyR3Hz)

#### Inicio de monitorización

[![inicio-de-monitorizacion-2.jpg](https://i.postimg.cc/4y7Hfts3/inicio-de-monitorizacion-2.jpg)](https://postimg.cc/JH8zKsyw)

#### Administración de cuenta de usuario

[![administraci-n-de-cuenta-de-usuario.jpg](https://i.postimg.cc/mkHhfsyz/administraci-n-de-cuenta-de-usuario.jpg)](https://postimg.cc/hQKKTNwc)

#### Monitorización de la salud de las mascotas

[![monitorizacion-de-la-salud-de-las-mascotas.jpg](https://i.postimg.cc/wM80LDF1/monitorizacion-de-la-salud-de-las-mascotas.jpg)](https://postimg.cc/r0j1L0BT)

#### Respuesta de alertas

[![Respuesta-de-alertas-2.jpg](https://i.postimg.cc/t4Tt1ryr/Respuesta-de-alertas-2.jpg)](https://postimg.cc/9r6qKYDT)

#### Programación de cita

[![Programacion-de-cita-2.jpg](https://i.postimg.cc/D0x4nTW7/Programacion-de-cita-2.jpg)](https://postimg.cc/V0bkW2Bh)

#### Gestión de citas

[![Gestion-de-citas.jpg](https://i.postimg.cc/FRZ7V4V0/Gestion-de-citas.jpg)](https://postimg.cc/gXxzG150)

#### Context Mapping

[![context-mapping-1.jpg](https://i.postimg.cc/bJzJ6wg3/context-mapping-1.jpg)](https://postimg.cc/rdPMscvr)

Para un mayor detalle revisar el tablero de Miro: 
[Context Mapping PetHealth](https://miro.com/app/board/uXjVKVvjW8w=/?share_link_id=983505004568 "Context Mapping PetHealth")

### 4.1.3. Software Architecture.

La arquitectura de software se refiere a la estructura fundamental de un sistema de software, incluyendo sus componentes, relaciones, y principios de diseño. Esta disciplina implica diseñar y organizar los diferentes elementos del software para lograr un sistema funcional, eficiente, escalable y fácil de mantener. Se consideran aspectos como la distribución de tareas, la comunicación entre componentes, la gestión de datos y la seguridad del sistema. A continuación, veremos los diagramas de arquitectura de software relacionados a PetHealth. 

#### 4.1.3.1. Software Architecture System Landscape Diagram.

Es un diagrama que muestra la estructura general del sistema, incluyendo sus componentes clave, relaciones entre ellos y cómo se integran en el entorno tecnológico más amplio.

[![landscape-1-1.png](https://i.postimg.cc/zfPT5zTp/landscape-1-1.png)](https://postimg.cc/KKB1Dyqg)

#### 4.1.3.2. Software Architecture Context Level Diagrams.

El diagrama de contexto muestra las relaciones y flujos de información entre los actores (usuarios y sistemas) y el sistema principal, el PetHealth System. El objetivo del sistema es monitorear la salud y la ubicación de las mascotas a través de un collar inteligente equipado con sensores avanzados.  
Este diagrama de contexto ilustra eficazmente cómo las diferentes entidades interactúan y dependen unas de otras para proporcionar un cuidado integral y monitoreo de la salud para mascotas, haciendo uso de tecnología avanzada y servicios integrados.

[![Context-Diagrams.png](https://i.postimg.cc/CKzCcnw2/image.png)](https://postimg.cc/TyvWwwLj)

#### 4.1.3.2. Software Architecture Container Level Diagrams.

Es un diagrama que se enfoca en los contenedores de software y sus relaciones. Representa cómo la aplicación móvil, la API propia, el servidor de aplicación y la base de datos están organizados y cómo interactúan entre sí para proporcionar funcionalidades completas a los usuarios.

[![Container-Diagram-1.png](https://i.postimg.cc/Gh1GbSs0/Container-Diagram-1.png)](https://postimg.cc/vD3czhzX)

#### 4.1.3.3. Software Architecture Deployment Diagrams.

Este diagrama muestra cómo los diferentes elementos del sistema, como aplicaciones, servidores, bases de datos y dispositivos de usuario, se despliegan en nodos físicos o virtuales, y cómo se conectan entre sí para que el sistema funcione correctamente en el entorno de producción.

[![Deployment-Diagram-2-1.png](https://i.postimg.cc/qv13XJD0/Deployment-Diagram-2-1.png)](https://postimg.cc/rDtsqkLY)

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Motitorizacion de salud de mascota
#### 4.2.1.1. Domain Layer.
- Pet: Entidad que representa a una mascota y contiene métodos para acceder a su historial de salud y programar citas veterinarias.
- PetOwner: Entidad que representa al dueño de la mascota, incluye métodos para acceder a la información de sus mascotas

#### 4.2.1.2. Interface Layer.
- HealthMonitoringController: Este controlador maneja las solicitudes relacionadas con la monitorización de la salud de las mascotas. Tendrá métodos para iniciar el proceso de detección de enfermedades, registrar comportamientos anómalos y obtener el historial de salud de la mascota.
- PetOwnerController: Este controlador se encargará de las acciones relacionadas con los dueños de las mascotas. Tendrá metodos para acceder a la información de las mascotas de una persona y recibir alertas de salud.
- HealthAlertConsumer: Escuchará eventos relacionados con la detección de enfermedades y conductas anómalas. Cuando se detecte cualquiera de los dos casos envía una notificación al dueño de la mascota mediante la aplicación.
- HealthStatus: Contendrá la información sobre el estado de salud actual de la mascota, incluyendo frecuencia cardiaca, temperatura y cualquier anomalía detectada. Esta información se podrá ver en la interfaz de usuario de la aplicación móvil para que el dueño de la mascota lo vea.

#### 4.2.1.3. Application Layer.
- HealthMonitoringService: Este servicio sería responsable de coordinar la monitorización de la salud de las mascotas. Podría contener métodos para iniciar el proceso de detección de enfermedades, registrar comportamientos anómalos y almacenar el historial de salud de la mascota.
- PetManagementService: Este servicio manejaría las operaciones relacionadas con la gestión de mascotas y sus propietarios. Podría tener métodos para acceder a la información de las mascotas de un propietario y enviar alertas de salud utilizando los servicios proporcionados por el Interface Layer.
- PetHealthHistoryService: Este servicio sería responsable de manejar el historial de salud de las mascotas. Podría contener métodos para acceder al historial de salud de una mascota específica, agregar nuevos registros de salud y realizar consultas sobre el estado de salud pasado de la mascota.

#### 4.2.1.4. Infrastructure Layer.
- PetRepository: Esta clase sería responsable de interactuar con la base de datos para almacenar y recuperar información sobre las mascotas. Podría proporcionar métodos para agregar nuevas mascotas, actualizar su información y recuperar detalles específicos sobre una mascota.
- PetOwnerRepository: Esta clase manejaría la persistencia de información relacionada con los dueños de mascotas, como su información de contacto y la lista de mascotas asociadas. Podría proporcionar métodos para agregar nuevos propietarios, vincular mascotas a propietarios existentes y recuperar información sobre propietarios específicos.

#### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.1.7.2. Bounded Context Database Design Diagram.
### 4.2.2. Bounded Context: Respuesta de alertas
#### 4.2.2.1. Domain Layer.
- HealthAlert: Esta entidad representaría una alerta de salud generada por el sistema cuando se detecta una enfermedad o un comportamiento anómalo en una mascota. Podría contener detalles como la mascota afectada, el tipo de alerta (enfermedad, comportamiento anómalo, ubicación fuera del perímetro), la fecha y hora de la detección y cualquier información adicional relevante.

#### 4.2.2.2. Interface Layer.
- HealthAlertNotificationManager: Este administrador de notificaciones será responsable de enviar alertas de salud a los dueños de mascotas cuando se detecten enfermedades, comportamientos anómalos o la ubicación de la mascota salga del perímetro establecido.
- LocationController: Este controlador maneja las acciones relacionadas con la ubicación de la mascota. Tendrá métodos para visualizar la ubicación de la mascota.

#### 4.2.2.3. Application Layer.
- HealthAlertService: Este servicio sería responsable de manejar los eventos relacionados con la detección de enfermedades y comportamientos anómalos. Cuando se detecte una enfermedad, un comportamiento inusual o salga del perimetro, este servicio podría activar el HealthAlertNotificationManager para enviar notificaciones a los propietarios de mascotas.
- LocationService: Éste se encargará de guardar las coordenadas en donde se encuentre la mascota, controlando que no salga del perímetro establecido.

#### 4.2.2.4. Infrastructure Layer.
- GoogleMapsApi: Permitirá interactuar con la API de Google Maps para obtener información sobre la ubicación de las mascotas

#### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.2.7.2. Bounded Context Database Design Diagram.
### 4.2.3. Bounded Context: Programación de citas
#### 4.2.3.1. Domain Layer.
- Vet: Esta entidad representaría a un veterinario. Podría incluir detalles como el nombre del veterinario, la dirección de la clínica.
- Appointment: Esta entidad representaría una cita veterinaria programada para una mascota en particular. Podría contener detalles como la fecha y hora de la cita, el motivo de la visita y la mascota asociada.

#### 4.2.3.2. Interface Layer.
- AppointmentController: Este controlador podría manejar las solicitudes relacionadas con la programación y gestión de citas veterinarias. Podría tener métodos para programar nuevas citas,reprogramar o cancelar citas existentes, buscar citas por mascota o fecha, y enviar recordatorios de citas a los propietarios de mascotas.
- AppointmentView: Esta clase podría ser responsable de mostrar información sobre las citas veterinarias en la interfaz de usuario del sistema. Podría presentar las citas en un formato fácil de entender, mostrando detalles como la fecha y hora de la cita, el motivo de la visita y la información de contacto del veterinario.

#### 4.2.3.3. Application Layer.
- AppointmentManagementService: Este servicio sería responsable de coordinar la gestión de citas veterinarias. Podría contener métodos para programar nuevas citas, cancelar citas existentes, buscar citas por mascota o fecha, y enviar recordatorios de citas a los propietarios de mascotas.
- AppointmentValidationService: Este servicio manejaría la validación de nuevas citas antes de ser programadas. Podría verificar la disponibilidad de horarios, asegurarse de que la mascota esté disponible para la cita y validar cualquier requisito adicional necesario para la programación de la cita.
- AppointmentCancellationService: Este servicio sería responsable de manejar la cancelación de citas veterinarias. Podría contener métodos para cancelar citas existentes y manejar cualquier lógica relacionada con la política de cancelación, como la aplicación de tarifas por cancelaciones tardías.

#### 4.2.3.4. Infrastructure Layer.
- Database: Esta capa sería responsable de interactuar con la base de datos para almacenar y recuperar información sobre las citas veterinarias programadas. Podría contener clases para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en la tabla de citas, así como en tablas relacionadas, como la información de las mascotas y los propietarios.

#### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.3.7.2. Bounded Context Database Design Diagram.
