# Capítulo IV: Solution Software Design
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

#### Function of the collar

[![Function-of-the-collar.jpg](https://i.postimg.cc/k46qzpbk/Function-of-the-collar.jpg)](https://postimg.cc/MMSCjttD)

#### User account management

[![User-account-management.jpg](https://i.postimg.cc/qq20M6Qw/User-account-management.jpg)](https://postimg.cc/n9VN3zy9)

#### Appointment function

[![Appointment-function.jpg](https://i.postimg.cc/7YywtXYW/Appointment-function.jpg)](https://postimg.cc/3W9sdXGX)

#### Context Mapping 

Function of the collar y Appointment function se relacionan:

Ambos contextos están relacionados en el sentido de que las funciones asociadas con el collar de monitoreo de mascotas pueden requerir citas programadas o gestión de citas para visitas veterinarias.

User account management se relaciona con Function of the collar y Appointment function:

User account management está relacionado con Function of the collar porque los usuarios pueden necesitar configurar sus cuentas para controlar las funciones del collar de manera adecuada.

También se relaciona con Appointment function porque los usuarios podrían usar sus cuentas para programar citas veterinarias relacionadas con el cuidado de las mascotas.

Estas relaciones reflejan cómo los diferentes aspectos de la aplicación están interconectados para proporcionar una experiencia completa y coherente para los usuarios, desde la gestión de cuentas hasta las funciones específicas del collar y las citas veterinarias.

[![Context-Mapping-Pet-Health.jpg](https://i.postimg.cc/GhJrWY4h/Context-Mapping-Pet-Health.jpg)](https://postimg.cc/zVB9Wyw9)

Para una mejor vista: https://miro.com/app/board/uXjVKNZ76t4=/?share_link_id=935515296039 

### 4.1.3. Software Architecture.

La arquitectura de software se refiere a la estructura fundamental de un sistema de software, incluyendo sus componentes, relaciones, y principios de diseño. Esta disciplina implica diseñar y organizar los diferentes elementos del software para lograr un sistema funcional, eficiente, escalable y fácil de mantener. Se consideran aspectos como la distribución de tareas, la comunicación entre componentes, la gestión de datos y la seguridad del sistema. A continuación, veremos los diagramas de arquitectura de software relacionados a PetHealth. 

#### 4.1.3.1. Software Architecture System Landscape Diagram.

Es un diagrama que muestra la estructura general del sistema, incluyendo sus componentes clave, relaciones entre ellos y cómo se integran en el entorno tecnológico más amplio.

[![landscape-1-1.png](https://i.postimg.cc/zfPT5zTp/landscape-1-1.png)](https://postimg.cc/KKB1Dyqg)

#### 4.1.3.2. Software Architecture Context Level Diagrams.

El diagrama de contexto muestra las relaciones y flujos de información entre los actores (usuarios y sistemas) y el sistema principal, el PetHealth System. El objetivo del sistema es monitorear la salud y la ubicación de las mascotas a través de un collar inteligente equipado con sensores avanzados.  
Este diagrama de contexto ilustra eficazmente cómo las diferentes entidades interactúan y dependen unas de otras para proporcionar un cuidado integral y monitoreo de la salud para mascotas, haciendo uso de tecnología avanzada y servicios integrados.

[![Context-Diagram.png](https://i.postimg.cc/bwT5Y8m1/image.png)](https://postimg.cc/bZZg3Xcv)

#### 4.1.3.2. Software Architecture Container Level Diagrams.

El diagrama ilustra cómo los diferentes contenedores del sistema interactúan entre sí y con los usuarios finales para proporcionar una solución integral de monitoreo y gestión de la salud de las mascotas. El sistema se compone de varias aplicaciones web y móviles, una API central, y componentes específicos de edge computing para manejar los datos generados por un collar inteligente.  
Este diagrama de contenedores muestra un sistema robusto y bien integrado que utiliza tecnología moderna y prácticas de diseño para proporcionar una solución completa para el monitoreo de la salud y la gestión de la atención de las mascotas. Cada componente está diseñado para trabajar en conjunto de manera eficiente, asegurando que los usuarios, ya sean dueños de mascotas o veterinarios, reciban una experiencia fluida y funcional.

[![Container-Diagram.png](https://i.postimg.cc/4NvLwskj/image.png)](https://postimg.cc/ppTJLNdB)

#### 4.1.3.3. Software Architecture Deployment Diagrams.

Este diagrama muestra cómo los diferentes elementos del sistema, como aplicaciones, servidores, bases de datos y dispositivos de usuario, se despliegan en nodos físicos o virtuales, y cómo se conectan entre sí para que el sistema funcione correctamente en el entorno de producción.

[![Deployment-Diagram-2-1.png](https://i.postimg.cc/qv13XJD0/Deployment-Diagram-2-1.png)](https://postimg.cc/rDtsqkLY)

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Function of the collar
El dominio de Function of the collar describe detalladamente las funciones y procesos que se llevan a cabo a través del collar inteligente para mascotas. Este dominio es responsable de manejar las funciones, como el monitoreo y el de encontrar a la mascota perdida, como garantizar la manera correcta de instalar y sincronizar la cuenta del usuario con el collar.

**Diccionario de Clases:**

El Diccionario de Clases es una herramienta importante en el proceso de diseño y desarrollo de nuestra plataforma PetHealth, ya que proporciona una descripción detallada de las clases clave que forman la base del modelo de dominio del sistema. Este diccionario documenta las entidades y sus relaciones, atributos y comportamientos, lo que facilita la comunicación y la colaboración entre los miembros del equipo y garantiza una base sólida para nuestra solución de nuestro proyecto PetHealth.  
[![collar.png](https://i.postimg.cc/yN0pycYK/image.png)](https://postimg.cc/675h97vb)  
[![sensor.png](https://i.postimg.cc/s237bh4s/image.png)](https://postimg.cc/75Q52bRW)  
[![monitoring.png](https://i.postimg.cc/xd7H84ST/image.png)](https://postimg.cc/XZfXDxJT)  
[![alert.png](https://i.postimg.cc/FR3fRFZD/image.png)](https://postimg.cc/34rrfTzv)  
[![geofencing.png](https://i.postimg.cc/nzJF344G/image.png)](https://postimg.cc/1gv1tNY8)  
[![medicalHistory.png](https://i.postimg.cc/YqZwXNkL/image.png)](https://postimg.cc/tY3fJxs9)  
[![ConnectivityManager.png](https://i.postimg.cc/VkQVrKmg/image.png)](https://postimg.cc/3d1BzCy0)

#### 4.2.1.1. Domain Layer.
Dentro del dominio de Function of the Collar, se encuentran entidades clave como lo escrito anteriormente. Estas entidades desempeñan un papel fundamental en el proceso de las funciones necesarias para el collar, ya que permitirá a los usuarios poder monitorear y recibir alertas sobre la salud de su mascota, como también encontrar a su mascota mediante gps.  
A continuación, se muestra todo los objetos relacionados con el dominio.  
[![domainlayer.png](https://i.postimg.cc/L6zrVcyw/image.png)](https://postimg.cc/3dxS8cQF)

#### 4.2.1.2. Interface Layer.
En esta sección, presentamos la Capa de Interfaz de nuestra plataforma de PetHealth, que representa el punto de entrada para las interacciones entre los usuarios y el sistema. La Capa de Interfaz está compuesta por una serie de controladores que manejan las peticiones entrantes de los usuarios y devuelven las respuestas adecuadas, permitiendo una comunicación efectiva entre la plataforma y sus usuarios.  
El contexto de esta capa incluye cinco controladores principales: **CollarController, HealthMonitoringController, OwnerController, AlertsController y PetController**. Estos controladores tienen la responsabilidad de gestionar las operaciones relacionadas.

**CollarController:** Maneja las operaciones relacionadas con los collares.

**HealthMonitoringController:** Centrado en la captura y análisis de datos de salud de las mascotas.

**OwnerController:** Maneja información relacionada con los propietarios de las mascotas.

**AlertsController:** Gestiona las alertas generadas por el sistema.

**PetController:** Administra información sobre las mascotas.

[![interfacelayer.png](https://i.postimg.cc/wMYwyvdv/image.png)](https://postimg.cc/jwvHBR20)

#### 4.2.1.3. Application Layer.
En esta sección, presentamos la Capa de Aplicación (Application Layer) dentro del contexto del enfoque de diseño Domain-Driven Design (DDD) para nuestra plataforma de alquiler de automóviles. La Capa de Aplicación es responsable de coordinar las acciones y el flujo de datos entre la Capa de Dominio y la Capa de Infraestructura, actuando como intermediario y gestionando las interacciones entre estas capas. Esta capa es crucial para garantizar que la lógica de negocio, representada por la Capa de Dominio, se ejecute de manera eficiente y coherente.

La Capa de Aplicación se compone de servicios de aplicación, Command Handlers y Event Handlers. Los Command Handlers gestionan las operaciones de escritura en la plataforma, como **CollarActivationCommandHandler**, que se encarga de activar un collar en específico; y **PetRegistrationCommandHandler**, que permite registrar una nueva mascota en el sistema.

Por otro lado, los Event Handlers se encargan de manejar eventos del sistema, como **HealthAlertEventHandler**, que procesa y responde a una alerta de salud generada por el sistema; y **LocationUpdateEventHandler**, que actualiza y valida la ubicación de la mascota en el sistema.

[![aplicationlayer.png](https://i.postimg.cc/BbJxf10x/image.png)](https://postimg.cc/9RN4G0zM)

#### 4.2.1.4. Infrastructure Layer.
En esta sección, presentamos la Capa de Infraestructura (Infrastructure Layer) dentro del contexto del enfoque de diseño Domain-Driven Design (DDD) para nuestra el bounded context **Function of the Collar**. La Capa de Infraestructura es responsable de proporcionar los componentes técnicos y de soporte necesarios para que las otras capas del sistema funcionen correctamente. Esta capa incluye la implementación de repositorios, servicios que se conectan con sistemas externos y otros componentes de infraestructura.

Los repositorios en la Capa de Infraestructura implementan las interfaces definidas en la Capa de Dominio y se encargan de la persistencia y gestión de datos. En nuestra plataforma, utilizamos repositorios basados en JPA (Java Persistence API) para manejar la interacción con la base de datos. Entre los repositorios clave se encuentran **CollarRepository**, que gestiona la información del Collar; y **PetRepository**, que gestiona la información de las mascotas.

[![infraestructurelayer.png](https://i.postimg.cc/zX6VnRc0/image.png)](https://postimg.cc/7f1H4bD2)

#### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams.
En esta sección, presentamos los Diagramas de Componentes a nivel de Arquitectura de Software del bounded Context **Function of the collar** para nuestra plataforma de collar inteligente para mascotas. Estos diagramas proporcionan una visión detallada de cómo los diferentes componentes del sistema interactúan entre sí en el contexto de aplicaciones web y móviles. Al analizar estos diagramas, podemos obtener una comprensión clara de cómo la plataforma funciona desde un punto de vista arquitectónico y cómo los componentes se comunican entre sí.

Las aplicaciones web y móviles interactúan con el sistema a través de una serie de controladores, que gestionan las peticiones entrantes y proporcionan las respuestas adecuadas. Los controladores clave en nuestra plataforma incluye **CollarController, HealthMonitoringController y AlertsController**. Estos controladores manejan las operaciones(lectura y escritura) relacionadas con el monitoreo de la salud de las mascotas y la función de localizar a la mascota perdida.

Cada controlador interactúa con sus respectivos servicios y repositorios para realizar las operaciones requeridas. Los servicios implementan la lógica de negocio y coordinan las acciones entre los repositorios y otros componentes del sistema. Los repositorios, por otro lado, se encargan de la persistencia y gestión de datos, interactuando con la base de datos y, en algunos casos, con servicios externos.

Además, el sistema puede interactuar con servicios externos para obtener información adicional o realizar acciones específicas, como el servicio de geolocalización o el envío de alertas de correos electrónicos.

[![Component-Diagram-Collar-Function.png](https://i.postimg.cc/7ZxBWdqh/image.png)](https://postimg.cc/KRHrK9kh)

#### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams.
Estos diagramas proporcionan una visión detallada de cómo los diferentes componentes del sistema interactúan entre sí a nivel de código, enfocándose específicamente en la conexión e integración de servicios externos como Google Map y Firebase Cloud Messaging.

El AlertService es un componente clave en nuestra plataforma, encargado de enviar un mensaje de alerta a los usuarios que son dueños de mascotas si la salud de su mascota está grave o crítica. Para lograr esto, el AlertService se conecta con Firebase Cloud Messaging, un servicio que envía alertas y notificaciones push a los usuarios. El diagrama de código muestra cómo el AlertService se comunica con Firebase Cloud Messaging a través de su API, enviando alerta mediante correos electrónicos o notificaciones dependiendo de la salud de la mascota.

Otro componente importante en nuestra plataforma es el LocationService, que se encarga de obtener la ubicación de las mascotas cuando salen del perímetro establecido. Para lograr esto, el LocationService se integra con Google Map, un proveedor de servicios de geolocalización y mapas. El diagrama de código muestra cómo el LocationService interactúa con la API de Google Map para recuperar la información de ubicación de las mascotas y actualizarla en el sistema según sea necesario.

[![code_1.png](https://i.postimg.cc/wvtbz7zy/image.png)](https://postimg.cc/1nQKcRfs)  
[![code_2.png](https://i.postimg.cc/QxgYh22b/image.png)](https://postimg.cc/ZCRxLMKB)

##### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams.
Es una herramienta esencial en el diseño y desarrollo de software, especialmente en la metodología de Diseño Dirigido por el Dominio (DDD).  
Son fundamentales para la organización, diseño, implementación y mantenimiento de sistemas complejos, ayudando a asegurar que el software es escalable, mantenible y alineado con las necesidades del negocio.  
Para desarrollarlo, se hizo un diagrama de clase, usando todo lo que se realizó anteriormente.

[![layer_class_diagrams.png](https://i.postimg.cc/L86DRnB9/image.png)](https://postimg.cc/BXkHBZVk)

##### 4.2.1.7.2. Bounded Context Database Design Diagram.
Es una herramienta utilizada en el diseño de software, particularmente en la arquitectura de microservicios y en el enfoque de diseño de dominios.

El uso de un diagrama de diseño de base de datos es fundamental para gestionar la complejidad en sistemas grandes y distribuidos, ayudando a organizar y simplificar el diseño y la implementación de las bases de datos y los servicios asociados.

En este diagrama de diseño de base de datos, se explica las relaciones de los entitys realizados.

[![database.png](https://i.postimg.cc/6qM7h57c/image.png)](https://postimg.cc/jnJdxT4n)

### 4.2.2. Bounded Context: User Account Management
El dominio de **User Account Management** se centra en gestionar todas las interacciones y operaciones asociadas con cuentas de usuario. Este dominio es responsable de manejar las cuentas de usuario, tanto para editar como para actualizar su membresía.

**Diccionario de Clases:**

En el Diccionario de Clases, hemos incluido 3 clases principales: Pet Owner, Pet y Subscription. Estas clases representan los elementos esenciales de nuestra plataforma y definen las entidades y se relaciona en actualizar el perfil y la membresía de su cuenta.

[![image.png](https://i.postimg.cc/J7Y4KF6p/image.png)](https://postimg.cc/w3JpjwdN)  
[![image.png](https://i.postimg.cc/pX9VSB3R/image.png)](https://postimg.cc/4mgT7pJS)  
[![image.png](https://i.postimg.cc/ZnPqfYC2/image.png)](https://postimg.cc/PvxhJjbQ)

#### 4.2.2.1. Domain Layer.
Dentro del dominio de User Account Management, se encuentran entidades clave como Pet, Pet Owner y Subscription. Estas entidades desempeñan un papel fundamental en la gestión de la cuenta, ya que permite a los usuarios actualizar la información básica de su cuenta y de actualizar la membresía de su cuenta.

A continuación, se muestra todos los objetos relacionados con el dominio

[![image.png](https://i.postimg.cc/02xjzS4s/image.png)](https://postimg.cc/SjTk5nqT)

#### 4.2.2.2. Interface Layer.
La interface layer del bounded context del User Account Management es una parte esencial del sistema, ya que es la capa que permite la comunicación entre los diferentes componentes de la aplicación. Esto incluye la creación de usuarios, mascotas y suscripciones.

A continuación, se muestran los controllers identificados.

[![image.png](https://i.postimg.cc/9MZXMXt0/image.png)](https://postimg.cc/G83ngCfn)

#### 4.2.2.3. Application Layer.
En esta sección, presentamos la Capa de Aplicación (Application Layer) dentro del contexto del enfoque de diseño Domain-Driven Desing(DDD) para nuestra plataforma de collar inteligente para mascotas. La Capa de Aplicación es responsable de coordinar las acciones y el flujo de datos entre la Capa de Dominio y la Capa de Infraestructura, actuando como intermediario y gestionando las interacciones entre estas capas. Esta capa es crucial para garantizar que la lógica de negocio, representada por la Capa de Dominio, se ejecute de manera eficiente y coherente.

La Capa de Aplicación se compone de servicios de aplicación, Command Handlers y Event Handlers. Los Command Handlers gestionan las operaciones de escritura en la plataforma, PetOwnerAccountCommandHandler, que es aquel que se encarga de gestionar la información de los dueños de mascotas, editar y eliminar; PetCommandHandler, que es aquel que se encarga de gestionar la información de las mascotas, editar y eliminar; y SubscriptionCommandHandler, que se encarga de gestionar las suscripciones de los usuarios, actualizar o cancelar.

Por otro lado, los Event Handlers se encargan de manejar eventos del sistema, como PaymentEventHandler, que se encarga de que el pago sea exitoso o no. SubscriptionStatusEventHandler, que se encarga de activar la suscripción o expirarlo. PetStatusUpdateEventHandler que se encarga de añadir o remover la información de la mascota.

[![image.png](https://i.postimg.cc/vHQ8Ys18/image.png)](https://postimg.cc/rzP2j7C7)

#### 4.2.2.4. Infrastructure Layer.
En esta sección, presentamos la Capa de Infraestructura (Infrastructure Layer) dentro del contexto del enfoque de diseño Domain-Driven Design (DDD) para nuestra el bounded context User Account Management. La Capa de Infraestructura es responsable de proporcionar los componentes técnicos y de soporte necesarios para que las otras capas del sistema funcionen correctamente. Esta capa incluye la implementación de repositorios, servicios que se conectan con sistemas externos y otros componentes de infraestructura.

Los repositorios en la Capa de Infraestructura implementan las interfaces definidas en la Capa de Dominio y se encargan de la persistencia y gestión de datos. En nuestra plataforma, utilizamos repositorios basados en JPA (Java Persistence API) para manejar la interacción con la base de datos. Entre los repositorios clave se encuentran **PetOwnerRepository**, que gestiona la información de los usuarios pet owners; **PetRepository**, que se encarga de gestionar la información de las mascotas; y **SubscriptionRepository**, que se encarga de gestionar la realizarse las suscripciones.

[![image.png](https://i.postimg.cc/wBsgfxr2/image.png)](https://postimg.cc/1gPk4SsV)

#### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams.
En esta sección, presentamos los Diagramas de Componentes a nivel de Arquitectura de Software del bounded Context **User Account Management** para nuestra plataforma de cuidado de las mascotas mediante un collar inteligente. Estos diagramas proporcionan una visión detallada de cómo los diferentes componentes del sistema interactúan entre sí en el contexto de aplicaciones web y móviles. Al analizar estos diagramas, podemos obtener una comprensión clara de cómo la plataforma funciona desde un punto de vista arquitectónico y cómo los componentes se comunican entre sí.

Las aplicaciones web y móviles interactúan con el sistema a través de una serie de controladores, que gestionan las peticiones entrantes y proporcionan las respuestas adecuadas. Los controladores clave en nuestra plataforma incluye **PetOwnerController, PetController y SubscriptionController**. Estos controladores manejan las operaciones (lectura y escritura) relacionadas con las funciones de la gestión de usuarios.

[![Component-Diagram-User-Account-Management.png](https://i.postimg.cc/yYTjcj0H/image.png)](https://postimg.cc/9rryjGx8)

#### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams.
Estos diagramas proporcionan una visión detallada de cómo los diferentes componentes del sistema interactúan entre sí a nivel de código, enfocándose específicamente en la conexión e integración del servicio externo Izipay.

El SubscriptionService se encarga de gestionar las operaciones relacionadas con la actualización de la membresía de la cuenta del usuario

[![image.png](https://i.postimg.cc/WbtK6WC6/image.png)](https://postimg.cc/TpMCT9Rp)

##### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams.
El Bounded Context Domain Layer Class Diagrams del bounded context del User Account Management representa los diagramas de clases para los diferentes componentes del dominio, incluyendo todos los entitys. Estos diagramas muestran cómo se modela la funcionalidad en el dominio del negocio, y cómo las diferentes clases interactúan para cumplir con las necesidades del negocio. Cada diagrama de clase muestra los atributos y métodos relevantes.

[![image.png](https://i.postimg.cc/HL0Psf8H/image.png)](https://postimg.cc/4Kd1W21F)

##### 4.2.2.7.2. Bounded Context Database Design Diagram.
En esta sección se muestra la estructura de la base de datos y la relación que tendrán entre ellas. En este caso tenemos 4 tablas que representan la forma en la que se trabaja la gestión de cuentas de usuarios y la actualización de las suscripciones para las cuentas de los usuarios.

[![Captura.png](https://i.postimg.cc/nhb8QW7X/Captura.png)](https://postimg.cc/JGqYfPp8)

### 4.2.3. Bounded Context: Appointment Function
El dominio de Appointment Function describe las funciones y procesos que se llevan a cabo en las aplicaciones web y móviles. Este dominio es responsable de manejar las funciones como el agendado de citas y el de poder visualizar las citas agendadas.  
**Diccionario de Clases:**  
[![image.png](https://i.postimg.cc/sxH472BW/image.png)](https://postimg.cc/FkcSQNVF)  
[![image.png](https://i.postimg.cc/NjHk2BQy/image.png)](https://postimg.cc/nXnD68jZ)  
[![image.png](https://i.postimg.cc/mrWNQJrm/image.png)](https://postimg.cc/w1FmzWLN)  
[![image.png](https://i.postimg.cc/KY77Qfkx/image.png)](https://postimg.cc/p9TnLDJ6)

#### 4.2.3.1. Domain Layer.
Para la función de citas, el Domain Layer sería responsable de modelar las entidades del dominio y de encapsular la lógica. Aquí encontramos los Aggregates, entitys, value objects, domain Services y repositories, estos desempeñan un papel importante, ya que encapsula la lógica de Appointment Function.

A continuación, se muestran todos los objetos relacionados con el dominio. 

[![Domain-layer.png](https://i.postimg.cc/cHXRGJBz/image.png)](https://postimg.cc/bDSDQpM0)

#### 4.2.3.2. Interface Layer.
La Interface Layer del bounded context es esencial para el sistema, ya que se encarga de manejar las solicitudes relacionadas con las citas. Esto incluye su creación, actualización y eliminación de las citas.

[![image.png](https://i.postimg.cc/Y0PQjyVf/image.png)](https://postimg.cc/K3n1HQmR)

#### 4.2.3.3. Application Layer.  
En esta sección la caja de aplicación es responsable de coordinar las acciones y el flujo de datos entre la Capa de Dominio y la Capa de Infraestructura, actuando como intermediario y gestionando las interacciones entre las capas. Esta capa es crucial para garantizar que la lógica de negocio, representada por la Capa de Dominio, se ejecute de manera eficiente y coherente.

[![image.png](https://i.postimg.cc/G3gFMH28/image.png)](https://postimg.cc/dDdZ3QGw)

#### 4.2.3.4. Infraestructure Layer.
La capa de infraestructura es responsable de proporcionar componentes técnicos y de soporte necesarios para que las otras capas del sistema funcionen correctamente. Esta capa incluye la implementación de repositorios, servicios que se conectan con otros sistemas externos y otros componentes de infraestructura.

[![image.png](https://i.postimg.cc/pTGF162b/image.png)](https://postimg.cc/Q97CFS90)

#### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams.  
En esta sección presentamos el component level diagram de nuestro bounded context Appointment Function. Estos diagramas proporcionan una visión detallada de cómo los diferentes componentes del sistema interactúan entre sí en el contexto de aplicaciones web y móviles. Al analizar estos diagramas, podemos obtener una comprensión clara de cómo la plataforma funciona desde un punto de vista arquitectónico y cómo los componentes se comunican entre sí.

[![image.png](https://i.postimg.cc/rFtrQj33/image.png)](https://postimg.cc/2Vry5Qz7)

#### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams.
Estos diagramas proporcionan información de cómo diferentes componentes de la aplicación interactúan a nivel de código para poder extraer información de la base de datos, en este caso podemos observar la interacción de los servicios del usuario y de los planes que ofrece nuestra aplicación.

Dentro de los componentes tenemos el Appointment Management Service, el cual nos permite obtener información acerca de las citas y a la vez guardar y actualizar información acerca de estos mismos.

[![image.png](https://i.postimg.cc/wMR74xfL/image.png)](https://postimg.cc/kR9JBCdg)


##### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams.
El Bounded Context Domain Layer Class Diagrams del bounded context del Appointment Function representa los diagramas de clases para los diferentes componentes del dominio.

[![image.png](https://i.postimg.cc/2jLQKCB0/image.png)](https://postimg.cc/yWB3J4jR)


##### 4.2.3.7.2. Bounded Context Database Design Diagram.
En esta sección se muestra la estructura de la base de datos y la relación que tendrán entre ellas. En este caso tenemos 4 tablas que representan la forma en la que se trabaja la gestión de citas, de modo que el usuario dueño de mascota pueda generar una cita de un veterinario.

[![image.png](https://i.postimg.cc/C5X37PQ6/image.png)](https://postimg.cc/WqmYbnjM)
