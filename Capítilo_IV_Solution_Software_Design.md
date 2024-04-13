![image](https://github.com/XForce-IOt/upc-pre-202401-si572-WS71-XForce-report/assets/83188290/77954ff2-30da-4c11-8570-5cb93dfdd246)# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design.
### 4.1.1. EventStorming.
Nuestro proceso de event storming se realizó en la herramienta MIRO, donde se realizó todo el proceso.

Primero comenzamos con el primer paso, Unstructured Exploration, para ello, analizamos y dimos nuestras opiniones acerca de los eventos del dominio siguiendo las recomendaciones adecuadas. Por otro lado, tomamos en cuenta varios criterios para elegir los eventos del dominio. Dichos criterios fueron la relevancia, frecuencia del evento y temporalidad.

[![image.png](https://i.postimg.cc/8cyrcx0M/image.png)](https://postimg.cc/sGh20Hyg)  
*Evidencia del desarrollo del primer paso del DDD.*

Después de ello, comenzamos con el segundo paso llamado Timelines, donde discutimos el flujo de los eventos del dominio.

[![image.png](https://i.postimg.cc/50LhxVjK/image.png)](https://postimg.cc/HcWZ2Fwb)  
*Evidencia del desarrollo del segundo paso de DDD.*

Para un mayor detalle revisar el tablero de Miro:  
[Eventstorming PetHealth](https://miro.com/app/board/uXjVKVNpMhY=/)

#### 4.1.1.1 Candidate Context Discovery.
Para hallar a nuestros Candidate Context, continuamos con el paso 3 Pain Points, donde discutimos eventos del flujo que podrían ser cuellos de botella o pasos manuales que requieren automatización.  
[![image.png](https://i.postimg.cc/gcRgBs6s/image.png)](https://postimg.cc/Jtr3sbxH)  
*Evidencia del desarrollo del tercer paso del DDD.*

Después, comenzamos con el cuarto paso del DDD llamado Pivotal Points, donde identificamos puntos o eventos comerciales importantes que indicaban un cambio en el contexto o la fase.
 
[![image.png](https://i.postimg.cc/brBYnPH0/image.png)](https://postimg.cc/jnyrVG1C)  
*Evidencia del desarrollo del cuarto paso del DDD.*

Con todo ello, comenzamos el paso de Commands, donde escribimos el desencadenante de ciertos eventos del dominio, así como el actor encargado.  
[![image.png](https://i.postimg.cc/k5mSGN5J/image.png)](https://postimg.cc/bZmrFtbW)  
*Evidencia del desarrollo del quinto paso del DDD.*

Después proseguimos con el paso 6, Policies donde identificamos eventos que debían de ejecutarse en automático o necesitaban alguna politica.  
[![image.png](https://i.postimg.cc/SN4jWQhd/image.png)](https://postimg.cc/t7rXbj7n)  
*Evidencia del desarrollo del sexto paso del DDD.*

Con ello procedemos a discutir los modelos de lectura de datos, y logramos identificar algunos como el dueño de mascota, que tiene que cuidar a su mascota. Los criterios para ello fueron complejidad, relevancia y frecuencia de actualización.  
[![image.png](https://i.postimg.cc/sXfwQC2g/image.png)](https://postimg.cc/wtPhZPJC)  
*Evidencia del desarrollo del septimo paso del DDD.*

También empezamos a discutir el uso de sistemas externos, y los que encontramos entre ellos estaban relacionados a los pagos y a la ubicación.  
[![image.png](https://i.postimg.cc/YCpG2F8T/image.png)](https://postimg.cc/GH5hqHWj)  
*Evidencia del desarrollo del octavo paso del DDD.*

Después, se comenzó con la identificación de los agregattes, para ello, tomamos criterios como granularidad, consistencia, y estabilidad. Con esos criterios, se procedió a elegir los Agreggattes, los cuales fueron los siguientes:  
[![image.png](https://i.postimg.cc/WzWKDggS/image.png)](https://postimg.cc/2LWTMqHB)  
*Evidencia del desarrollo del noveno paso del DDD.*

Ya por ultimo y después de un análisis y discusión grupal, los siguientes bounded contexts fueron elegidos:  
[![image.png](https://i.postimg.cc/YSRxqk1z/image.png)](https://postimg.cc/JyyXPfYs)  
*Evidencia del desarrollo del DDD*

Para un mayor detalle revisar el tablero de Miro:  
[Eventstorming PetHealth](https://miro.com/app/board/uXjVKVNpMhY=/)

#### 4.1.1.2 Domain Message Flows Modeling.
[![image.png](https://i.postimg.cc/cJPfJHvY/image.png)](https://postimg.cc/5HqX7fqN)

#### 4.1.1.3 Bounded Context Canvases.
[![image.png](https://i.postimg.cc/05Y789PM/image.png)](https://postimg.cc/NL0KDqyB)

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

Es un diagrama que proporciona una vista de alto nivel de los actores externos y sus interacciones con el sistema.

[![Context-Diagram-1.png](https://i.postimg.cc/prKjDK41/Context-Diagram-1.png)](https://postimg.cc/RJVqmJMc)

#### 4.1.3.2. Software Architecture Container Level Diagrams.

Es un diagrama que se enfoca en los contenedores de software y sus relaciones. Representa cómo la aplicación móvil, la API propia, el servidor de aplicación y la base de datos están organizados y cómo interactúan entre sí para proporcionar funcionalidades completas a los usuarios.

[![Container-Diagram-1.png](https://i.postimg.cc/Gh1GbSs0/Container-Diagram-1.png)](https://postimg.cc/vD3czhzX)

#### 4.1.3.3. Software Architecture Deployment Diagrams.

Este diagrama muestra cómo los diferentes elementos del sistema, como aplicaciones, servidores, bases de datos y dispositivos de usuario, se despliegan en nodos físicos o virtuales, y cómo se conectan entre sí para que el sistema funcione correctamente en el entorno de producción.

[![Deployment-Diagram-2-1.png](https://i.postimg.cc/qv13XJD0/Deployment-Diagram-2-1.png)](https://postimg.cc/rDtsqkLY)
