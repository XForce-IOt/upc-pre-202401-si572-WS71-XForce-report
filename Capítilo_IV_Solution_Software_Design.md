# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design.
### 4.1.1. EventStorming.
Nuestro proceso de event storming se realizó en la herramienta MIRO, donde se realizó todo el proceso.

Primero comenzamos con el primer paso, Unstructured Exploration, para ello, analizamos y dimos nuestras opiniones acerca de los eventos del dominio siguiendo las recomendaciones adecuadas. Por otro lado, tomamos en cuenta varios criterios para elegir los eventos del dominio. Dichos criterios fueron la relevancia, frecuencia del evento y temporalidad.

[![image.png](https://i.postimg.cc/CKJM6G8g/image.png)](https://postimg.cc/HJcCr73Z)  
*Evidencia del desarrollo del primer paso del DDD.*

Después de ello, comenzamos con el segundo paso llamado Timelines, donde discutimos el flujo de los eventos del dominio.

[![image.png](https://i.postimg.cc/Njcr3xK9/image.png)](https://postimg.cc/rKfmWxCM)  
*Evidencia del desarrollo del segundo pasol de DDD en el contexto de los dueños de mascotas.*

[![image.png](https://i.postimg.cc/MZfMXLRf/image.png)](https://postimg.cc/bd8NB3mq)  
*Evidencia del desarrollo del segundo pasol de DDD en el contexto de los veterinarios.*

Para un mayor detalle revisar el tablero de Miro:  
[Eventstorming PetHealth](https://miro.com/app/board/uXjVKa-5MYo=/?share_link_id=738948805584 "Eventstorming PetHealth")

#### 4.1.1.1 Candidate Context Discovery.
Para hallar a nuestros Candidate Context, continuamos con el paso 3 Pain Points, donde discutimos eventos del flujo que podrían ser cuellos de botella o pasos manuales que requieren automatización. Algunos más importantes que hallamos fueron, por ejemplo, ¿Cómo controlamos la salud de la mascota? y ¿Cómo sabemos la ubicación de la mascota?  
[![image.png](https://i.postimg.cc/wBS4hpk4/image.png)](https://postimg.cc/wtQkpnZD)  
*Evidencia del desarrollo del tercer paso del DDD en el contexto de los dueños de mascotas.*

[![image.png](https://i.postimg.cc/qBGQ7nW5/image.png)](https://postimg.cc/fkJY23zc)  
*Evidencia del desarrollo del tercer paso del DDD en el contexto de los veterinarios.*

Después, comenzamos con el cuarto paso del DDD llamado Pivotal Points, donde identificamos puntos o eventos comerciales importantes que indicaban un cambio en el contexto o la fase.

Para el flujo de línea de los dueños de mascotas se encontraron los siguientes pivotal points:  
[![image.png](https://i.postimg.cc/rsQdh9RP/image.png)](https://postimg.cc/300JNmBX)  
*Evidencia del desarrollo del cuarto paso del DDD en el contexto de los dueños de mascotas.*

Para el usuario veterinario fueron los siguientes:  
[![image.png](https://i.postimg.cc/8CzcG8Q5/image.png)](https://postimg.cc/jDBt6Fj0)  
*Evidencia del desarrollo del cuarto paso del DDD en el contexto de los veterinarios.*

Con todo ello, comenzamos el paso de Commands, donde escribimos el desencadenante de ciertos eventos del dominio, así como el actor encargado.  
[![image.png](https://i.postimg.cc/VsCYJBFR/image.png)](https://postimg.cc/dDJMXCpk)  
*Evidencia del desarrollo del quinto paso del DDD en el contexto de los dueños de mascotas.*

[![image.png](https://i.postimg.cc/2ScpcVwy/image.png)](https://postimg.cc/fV9gkW1Q)  
*Evidencia del desarrollo del quinto paso del DDD en el contexto de los veterinarios.*

Después proseguimos con el paso 6, Policies donde identificamos eventos que debían de ejecutarse en automático o necesitaban alguna politica. Por ejemplo, para enviar alertas de anomalías de salud.  
[![image.png](https://i.postimg.cc/Jh8yx71s/image.png)](https://postimg.cc/fVHTTNSs)  
*Evidencia del desarrollo del sexto paso del DDD en el contexto de los dueños de mascotas.*

[![image.png](https://i.postimg.cc/Jn4swTHm/image.png)](https://postimg.cc/bGWyk9RF)  
*Evidencia del desarrollo del sexto paso del DDD en el contexto de los veterinarios.*

Con ello procedemos a discutir los modelos de lectura de datos, y logramos identificar algunos como el dueño de mascota, que tiene que cuidar a su mascota. Los criterios para ello fueron complejidad, relevancia y frecuencia de actualización.  
[![image.png](https://i.postimg.cc/9Xk2PWVC/image.png)](https://postimg.cc/Bt2R4fXV)  
*Evidencia del desarrollo del septimo paso del DDD en el contexto de los dueños de mascotas.*

[![image.png](https://i.postimg.cc/4x6TTVcx/image.png)](https://postimg.cc/qNvFstQP)  
*Evidencia del desarrollo del septimo paso del DDD en el contexto de los veterinarios.*

También empezamos a discutir el uso de sistemas externos, y los que encontramos entre ellos estaban relacionados a los pagos y a la ubicación.  
[![image.png](https://i.postimg.cc/KzZhjTQG/image.png)](https://postimg.cc/1gYjYfL2)  
*Evidencia del desarrollo del octavo paso del DDD en el contexto de los dueños de mascotas.*

[![image.png](https://i.postimg.cc/RFX5H0bc/image.png)](https://postimg.cc/BLLVWJ36)  
*Evidencia del desarrollo del octavo paso del DDD en el contexto de los veterinarios.*

Después, se comenzó con la identificación de los agregattes, para ello, tomamos criterios como granularidad, consistencia, y estabilidad. Con esos criterios, se procedió a elegir los Agreggattes, los cuales fueron los siguientes:

Aggregate encargado del proceso de los historiales medicos de los dueños de mascotas:  
[![image.png](https://i.postimg.cc/bYL32wQw/image.png)](https://postimg.cc/jCwzpKgp)  
*Evidencia del aggregate del historial medico de los dueños de mascota*

Aggregate encargado del proceso de las funciones para los dueños de mascotas:  
[![image.png](https://i.postimg.cc/q78GBJJ0/image.png)](https://postimg.cc/8FzvtVfn)  
*Evidencia del aggregate de las funciones de los dueños de mascotas*

Aggregate encargado del proceso de las configuraciones que puede hacer los dueños de mascotas:  
[![image.png](https://i.postimg.cc/C5WZf872/image.png)](https://postimg.cc/p5JVwpgQ)  
*Evidencia del aggregate de las configuraciones de los dueños de mascotas*

Aggregate encargado del proceso de los historiales medicos para los veterinarios:  
[![image.png](https://i.postimg.cc/j5BNyBdv/image.png)](https://postimg.cc/Fdg74WSJ)  
*Evidencia del aggregate del historial medico para los veterinarios*

Aggregate encargado del proceso de las citas de los veterinarios:  
[![image.png](https://i.postimg.cc/sfZ53fwL/image.png)](https://postimg.cc/bdpZTPX0)  
*Evidencia del aggregate de la gestion de citas para los veterinarios*

Aggregate encargado del proceso de las actividades que pueden realizar veterinarios:
[![image.png](https://i.postimg.cc/Z5JNP84k/image.png)](https://postimg.cc/nCwMpQXT)  
*Evidencia del aggregate de las actividades para los veterinarios*

Ya por ultimo y después de un análisis y discusión grupal, los siguientes bounded contexts fueron elegidos:  
[![image.png](https://i.postimg.cc/9fndPRrV/image.png)](https://postimg.cc/2qnLr5QX)  
*Evidencia del desarrollo del DDD*

Para un mayor detalle revisar el tablero de Miro:  
[Eventstorming PetHealth](https://miro.com/app/board/uXjVKa-5MYo=/?share_link_id=738948805584 "Eventstorming PetHealth")

#### 4.1.1.2 Domain Message Flows Modeling.
#### 4.1.1.3 Bounded Context Canvases.
