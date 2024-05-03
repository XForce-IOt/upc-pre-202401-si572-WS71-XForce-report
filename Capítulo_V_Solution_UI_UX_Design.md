# Capítulo V: Solution UI/UX Design
## 5.1. Style Guidelines.
Se presentan las bases del repositorio central y organizado de uso común para todo el equipo con el fin de mantener una presentación consistente. Se incluye secciones para General Style Guidelines, Web Style Guidelines y Mobile Style Guidelines.
### 5.1.1. General Style Guidelines.
Para la elaboración de la guía de estilos de PetHealth nos valeremos de:
- Misión:
Revolucionar la atención y el bienestar de las mascotas mediante la innovación tecnológica. Nos esforzamos por proporcionar a los propietarios de mascotas una herramienta **intuitiva y avanzada** que les permita monitorear y gestionar la salud de sus animales con **facilidad y precisión**.
- Visión:
Establecernos como líderes globales en la salud y bienestar de mascotas, definiendo nuevos estándares de cuidado animal a través de la **tecnología**. Aspiramos a crear una comunidad donde cada mascota pueda vivir su vida más saludable y feliz, mientras proporcionamos **tranquilidad y soporte continuo** a sus dueños. Nos imaginamos transformando la industria del cuidado de mascotas, haciendo que el acceso a la atención médica preventiva y de calidad sea más **accesible** que nunca.
- Público objetivo: 
Dueños de mascotas de entre 17 y 60 años y Veterinarios de entre 30 a 50 años. 
- Personalidad de la marca: 
Buscamos fomentar un mundo donde cada mascota reciba el cuidado y la atención que merece. 
- Valores fundamentales de la marca:
Honestidad, lealtad, seguridad y calidad.

Teniendo en cuenta que nuestros usuarios utilizarán la aplicación para monitorear datos críticos de salud de sus mascotas o pacientes a traves de un Gadget tecnológico, PetHealth adoptará un tono formal, respetuoso y sereno.  
Del mismo modo, se probará la eficacia o el gusto de los usuarios por la aplicación a través de los comentarios de reseña de los clientes satisfechos.  
[![Branding.png](https://i.postimg.cc/vHMpzzSV/Branding.png)](https://postimg.cc/qgbbB8rJ)  

El color principal es el celeste ya que es un color que se relaciiona con la modernidad y la medicina. Se agregó un collar en el logo para recalcar la solución IoT.  

[![Colors.png](https://i.postimg.cc/NFTBHjFv/Colors.png)](https://postimg.cc/jnspVKyM)  

[![Heading.png](https://i.postimg.cc/sggbF2zf/Heading.png)](https://postimg.cc/KRC0Bx4C)  

Se eligió Montserrat por su alta legibilidad, facilidad de escalado y fácil lectura en dispositivos electrónicos.  

[![Body.png](https://i.postimg.cc/FR3Bbdyp/Body.png)](https://postimg.cc/7GP9wLQJ)  

De la misma manera, se eligió Work Sans por su correcto espaciado y su fácil lectura en dispositivos electrónicos.  

[![Spacing.png](https://i.postimg.cc/4y12MDFh/Spacing.png)](https://postimg.cc/bSsRSBPz)  

##### Inclusive design: 
Ya que detro de nuestro público objetivo se encuentran a usuarios de edad avanzada, es necesario elegir fuentes distingibles y además, no presentar secciones demasiado pequeñas en las soluciones nuestro servicio debe ser accesible a ellos. Las pautas consideradas son:
- Colores contrastantes y fuentes distinguibles para los usuarios con problemas de visión.  
- Se usaron plantillas para cumplir con los patrones de diseño comunes __(consistencia externa)__.
- Imágenes de gran tamaño y calidad __(Responsive images)__.
### 5.1.2. Web, Mobile and IoT Style Guidelines.
- Consistencia: Las pautas de diseño deben seguirse en todas las soluciones presentadas.
- Priorización de contenido:  Indica a usuario cuáles son las funciones más relevantes dentro de la aplicación mediante la Sidebar (Web Application) y la Bottom Navigation (Movile Application)
- Facilita la interacción (Fuentes distinguibles y de tamaño considerable).
- Colores contrastantes.
#### Web Style Guidelines:

- Estructura el contenido: Estilo Dashboard
- Adapta la web a todo tipo de dispositivos (Responsive).  

[![Home-Pet-Owners.png](https://i.postimg.cc/8C26Qsqq/Home-Pet-Owners.png)](https://postimg.cc/DWcZ1ffg)

#### Mobile Style Guidelines:
- Considera gestos y entradas de voz.
- Permite magnificar.

[![Home-Due-o-de-Mascota.png](https://i.postimg.cc/kgPz4yW4/Home-Due-o-de-Mascota.png)](https://postimg.cc/CzJmrkPT)
#### IoT Style Guidelines:
- Solo se considera un dispositivo IoT: PetHealth Collar, que es comprado y sincronizado por el usuario Pet Owner. 
- PetHealth Collar no cuenta con interface. Se sincroniza a través de la aplicación móvil, donde se observan los datos recopilados.
[![Crear-cuenta-Dato-de-Mascota-1.png](https://i.postimg.cc/8zH4G8D1/Crear-cuenta-Dato-de-Mascota-1.png)](https://postimg.cc/cvvw7brj)
[![Crear-cuenta-Dato-de-Mascota.png](https://i.postimg.cc/259xq4VM/Crear-cuenta-Dato-de-Mascota.png)](https://postimg.cc/5HvzTQ5S)

## 5.2. Information Architecture.
### 5.2.1. Organization Systems.
En nuestra estrategia de organización del contenido, aplicaremos diferentes sistemas según la naturaleza y el propósito de la información. Esto asegurará una experiencia de usuario coherente y eficiente. A continuación, detallamos cómo utilizaremos los distintos enfoques:
#### Organización Visual del Contenido:  

- **Jerárquica** (Visual Hierarchy):  
Utilizaremos este enfoque cuando sea necesario establecer una estructura clara de prioridades o niveles de importancia. Por ejemplo, en la página de inicio, destacaremos los elementos de manera prominente, seguidos de elementos secundarios a la derecha (Dashboard).
- **Organización Secuencial** (Step-by-Step):  
Implementaremos esta organización para guiar a los usuarios a través de procesos o tareas específicas. Por ejemplo, en creaciones de citas o procesos de pago.
- **Matricial**:  
Reservaremos este enfoque para situaciones en las que la información pueda organizarse de manera multidimensional o interrelacionada. Por ejemplo, en los calendarios, utilizaremos una disposición matricial para permitir la fácil exploración y comparación de datos de las citas del usuario.

#### Esquemas de Categorización de Contenido:

- **Alfabético:**  
Emplearemos este esquema cuando la información pueda organizarse de manera eficiente mediante un orden alfabético. Por ejemplo, en listas de veterinarios, cinicas o mascotas, ordenaremos los elementos según su orden alfabético para facilitar la búsqueda y la referencia.
- **Cronológico:**
Optaremos por este esquema cuando sea relevante mostrar la información en orden temporal. Por ejemplo, en listas de documentos o reportes presentaremos los elementos en orden cronológico para proporcionar contexto y seguimiento.
- **Por Tópicos:**  
Utilizaremos esta categorización para agrupar la información según temas o categorías específicas. Por ejemplo, en sitios de contenido educativo o bibliotecas digitales, organizaremos los recursos según los temas relevantes para facilitar la búsqueda y la exploración. 

Al aplicar estos sistemas de organización de manera estratégica, garantizaremos una experiencia de usuario intuitiva y satisfactoria, facilitando la búsqueda, la navegación y la comprensión del contenido.
### 5.2.2. Labeling Systems.
#### Sistemas de Etiquetado

En nuestra estrategia de etiquetado, priorizamos la simplicidad y la claridad para evitar confusiones entre nuestros usuarios. A continuación, detallamos las etiquetas que utilizaremos para representar los conjuntos de información y sus asociaciones:

- **Etiquetas Simples y Claras:**  
Utilizaremos etiquetas con el mínimo número de palabras para representar los conjuntos de información. Estas etiquetas serán descriptivas y directas, utilizando términos relacionados con el giro de negocio (términos veterinarios).
- **Asociaciones Coherentes:**  
Las etiquetas estarán asociadas de manera coherente con el contenido correspondiente, siguiendo una lógica intuitiva. Por ejemplo, si etiquetamos un conjunto de información como "Clínica veterinaria", aseguraremos que el contenido bajo esa etiqueta esté relacionado con solo con Clínicas veterinarias.    
Al aplicar estos principios de etiquetado, facilitaremos la navegación y la comprensión del contenido para nuestros visitantes y usuarios, mejorando así su experiencia en nuestra plataforma.
#### Etiquetas usadas:
- **Mascotas:** Sección donde se muestra toda la información relacionada con las mascotas pertenecientes a un determinado Pet Owner o supervidas por un determinado Vet.
- **Añadir mascota:** Etiqueta usada para acompañar a un botón. Muestra el formulario donde el usuario Pet Owner debe proporcionar los datos necesarios para agregar una nueva mascota a su cuenta.
- **Buscar mascotas:** Etiqueta usada en una sección de filtrado.
- **Citas:** Donde se muestra el calendario de citas programadas para las mascotas.
- **Lista de citas:** Sección donde se muestran todas las citas programadas para las mascotas, incluyendo detalles como la fecha, hora y motivo de la cita.
- **Agregar cita:** Etiqueta utilizada para acompañar a un botón que permite al usuario programar una nueva cita para su mascota.
- **Lista de clínicas:** Sección donde se presenta un listado de todas las clínicas veterinarias disponibles, incluyendo información relevante como la dirección y el contacto.
- **Lista de veterinarios:** Sección donde se muestra un listado de todos los veterinarios disponibles, con detalles como el nombre, especialidad y horario de atención.
- **Perfil:** Sección donde se muestra la información detallada del perfil del usuario, incluyendo datos personales y de contacto, así como información relevante sobre las mascotas asociadas.
- **Ajustes:** Sección donde el usuario puede configurar y personalizar la experiencia en la plataforma, como por ejemplo ajustes de notificaciones, preferencias de cuenta y configuración de privacidad.
### 5.2.3. SEO Tags and Meta Tags
Para optimizar la visibilidad y el posicionamiento en los motores de búsqueda, así como mejorar la presentación en las tiendas de aplicaciones, utilizaremos una estrategia sólida de SEO (Search Engine Optimization) y ASO (App Store Optimization). A continuación, detallamos los principales elementos que utilizaremos en nuestras páginas web y aplicaciones digitales:
#### Para el Sitio Web Estático (Landing Page) y Web Application:  

1. **Title:**  
**Landing Page:** "¡Bienvenido a PetHealth! Controla la salud de tus mascotas con tecnología IoT"  
**Web Application:** "PetHealth - Monitoriza la salud de tus mascotas con nuestro collar IoT"  
2. **Meta Description:**  
**Landing Page:** "Descubre cómo PetHealth puede ayudarte a monitorear la salud de tus mascotas con nuestro collar IoT inteligente. Regístrate ahora y mantén a tus mascotas saludables y seguras."  
**Web Application:** "Controla la temperatura, latidos y ubicación de tus mascotas en tiempo real con PetHealth y nuestro collar IoT. Descarga ahora y mantén a tus mascotas siempre bajo control."  
3. **Meta Keywords:**  
**Landing Page:** "mascotas, salud de mascotas, collar IoT, monitoreo de mascotas, tecnología veterinaria"  
**Web Application:** "aplicación para mascotas, collar inteligente, seguimiento de salud, IoT para mascotas"  
4. **Author:**  
Landing Page y Web Application: PetHealth  

#### Para Aplicaciones Móviles y Otros Productos Digitales:

1. **App Title:**
"PetHealth: Gestión Integral de Mascotas y Monitoreo IoT"
2. **App Subtitle:**
"Cuida y monitorea la salud de tus mascotas con tecnología IoT"
3. **App Keywords:**
"mascotas, salud de mascotas, collar IoT, seguimiento de salud, tecnología veterinaria"
4. **App Description:**
"PetHealth es la herramienta definitiva para propietarios de mascotas. Además de gestionar citas veterinarias y registros de salud, ahora también puedes monitorear en tiempo real la temperatura, latidos y ubicación de tus mascotas con nuestro collar IoT inteligente. Descarga PetHealth ahora y mantén a tus mascotas siempre saludables y seguras."  

Reflejamos claramente la funcionalidad de monitoreo de salud a través del collar IoT en nuestros elementos de SEO y ASO, lo que ayuda a destacar esta característica y atraer a usuarios interesados en este tipo de tecnología.

### 5.2.4. Searching Systems.

Nuestro enfoque en sistemas de búsqueda está diseñado para proporcionar a los usuarios herramientas efectivas que les permitan encontrar rápidamente la información que están buscando dentro de PetHealth. Queremos evitar que los usuarios se sientan perdidos entre el volumen de datos, por lo que hemos desarrollado varias opciones de búsqueda y filtros para ayudarles en este proceso. A continuación, detallamos las opciones de búsqueda que ofreceremos, los filtros disponibles para los usuarios y cómo se presentarán los datos después de una búsqueda exitosa:

#### Opciones de Búsqueda:

- **Búsqueda por Palabras Clave:** Los usuarios podrán realizar búsquedas utilizando palabras clave relacionadas con la información que están buscando, como el nombre de una mascota, una clínica veterinaria o un tipo de servicio.
- **Búsqueda Avanzada:** Ofreceremos una opción de búsqueda avanzada que permitirá a los usuarios refinar sus consultas utilizando filtros adicionales, como la fecha, la ubicación o el tipo de servicio requerido.
#### Filtros Disponibles:

1. **Filtros por Categoría:** Los usuarios podrán filtrar los resultados de la búsqueda por categorías específicas, como citas programadas, historial médico de la mascota, clínicas veterinarias, veterinarios disponibles, entre otros.
2. **Filtros por Fecha:** Los usuarios tendrán la opción de filtrar los resultados por fecha, lo que les permitirá ver solo la información relevante para un período específico.
3. **Filtros por Ubicación:** Si la información es geográficamente relevante, como la ubicación de clínicas veterinarias cercanas, los usuarios podrán filtrar los resultados por ubicación para encontrar opciones convenientes.

#### Presentación de Datos Después de la Búsqueda:

Después de realizar una búsqueda exitosa, los datos se presentarán de manera clara y organizada para facilitar la revisión por parte del usuario. Utilizaremos un diseño limpio y estructurado que muestre los resultados de manera ordenada, con opciones para ampliar detalles adicionales si es necesario. Los resultados se mostrarán en una lista o cuadrícula, según la naturaleza de la información, y se destacarán los detalles importantes para ayudar al usuario a identificar rápidamente la información relevante.  

Ejemplo de filtro de búsqueda de citas:  
[![Group-95.png](https://i.postimg.cc/T3MYrwyP/Group-95.png)](https://postimg.cc/ppCHvPJN)

Al ofrecer estas opciones de búsqueda y filtros, así como una presentación clara de los datos, esperamos proporcionar a nuestros usuarios una experiencia de búsqueda efectiva que les permita encontrar rápidamente la información que necesitan dentro de nuestro producto digital.

### 5.2.5. Navigation Systems.

Nuestra estrategia de navegación está diseñada para guiar a los usuarios de manera efectiva a través del Landing Page y las aplicaciones, facilitando que alcancen sus objetivos y tengan una interacción satisfactoria con nuestro producto. A continuación, detallamos las acciones y técnicas que implementaremos para lograr este objetivo:

#### Para el Landing Page:

1. **Menú de Navegación Claro:** Implementaremos un menú de navegación claro y fácil de entender, que proporcione acceso rápido a las secciones principales del sitio web. Esto permitirá a los usuarios explorar el contenido de manera intuitiva y acceder a la información que estén buscando.
2. **Llamadas a la Acción (CTA) Destacadas:** Colocaremos llamadas a la acción (CTA) destacadas en áreas estratégicas del Landing Page, invitando a los usuarios a realizar acciones específicas, como registrarse, descargar la aplicación, conocer más sobre nuestros servicios o comprar el collar. Estas CTA estarán diseñadas de manera llamativa y clara para captar la atención del usuario.
3. **Scroll Suave y Secciones Bien Definidas:** Implementaremos un diseño de página que facilite el scroll suave y fluido, con secciones bien definidas que permitan a los usuarios navegar de manera cómoda y comprender la estructura del contenido. Esto garantizará una experiencia de usuario agradable y sin confusiones.
#### Para las Aplicaciones:

1. **Interfaz Intuitiva y Fácil de Usar:** Diseñaremos una interfaz de usuario intuitiva y fácil de usar en nuestras aplicaciones, con elementos de navegación claramente identificados y accesibles. Los usuarios podrán moverse entre las diferentes secciones de la aplicación de manera fluida y sin esfuerzo.
2. **Barra de Navegación Inferior (Aplicación móvil) o Lateral (Aplicación web):** Implementaremos una barra de navegación inferior o lateral que proporcione acceso rápido a las funciones principales de la aplicación, como el perfil del usuario, las citas programadas, los datos de salud de la mascota, entre otros. Esto permitirá a los usuarios acceder rápidamente a las áreas de la aplicación que más utilizan.
3. **Flujo de Tareas Guiado:** Guiaremos a los usuarios a través de un flujo de tareas bien definido y estructurado, especialmente en funciones clave como agregar una mascota, programar una cita veterinaria o revisar el historial médico. Esto asegurará que los usuarios puedan completar sus tareas de manera eficiente y sin confusiones.  

Al implementar estas acciones y técnicas de navegación, garantizaremos que los usuarios puedan recorrer el contenido de nuestro Landing Page y aplicaciones de manera fluida y satisfactoria, cumpliendo así sus objetivos y maximizando su experiencia con nuestro producto.
## 5.3. Landing Page UI Design.
Nuestro enfoque en el diseño de la interfaz de usuario (UI) para el Landing Page se basa en la traducción de nuestras decisiones de diseño y arquitectura de información en una experiencia **visualmente atractiva y funcional** para nuestros segmentos objetivo. Cada elemento de diseño se ha considerado cuidadosamente para garantizar que refleje la identidad de nuestra marca, mientras que al mismo tiempo **facilita la navegación y comprensión del contenido** para los visitantes del sitio. A continuación, presentamos nuestra propuesta de diseño para el Landing Page, destacando cómo se reflejan nuestras decisiones de diseño y arquitectura de información en la interfaz de usuario.
Propuesta de Diseño para el Landing Page PetHealth:

1. **Identidad Visual Coherente:** Utilizamos elementos de diseño, como colores, tipografías y logotipos, que reflejan la identidad de nuestra marca y crean una experiencia coherente en todo el sitio web.

2. **Diseño Responsivo:** El Landing Page está diseñado de manera que se adapta fluidamente a diferentes dispositivos y tamaños de pantalla, garantizando una experiencia óptima tanto en computadoras de escritorio como en dispositivos móviles.

3. **Navegación Intuitiva:** Implementamos una navegación clara y fácil de entender, con un menú de navegación que destaca las secciones principales del sitio y guía a los usuarios a través del contenido de manera intuitiva.

4. **Llamadas a la Acción (CTA) Destacadas:** Colocamos llamadas a la acción estratégicamente en el Landing Page para alentar a los usuarios a tomar medidas específicas, como registrarse, descargar la aplicación o explorar más sobre nuestros servicios.

5. **Secciones Bien Definidas:** Organizamos el contenido del Landing Page en secciones bien definidas, con títulos claros y llamativos que facilitan la comprensión del contenido y la navegación para los usuarios.

6. **Imágenes y Gráficos Atractivos:** Utilizamos imágenes y gráficos de alta calidad que complementen el contenido y agreguen un atractivo visual al Landing Page, ayudando a captar la atención de los visitantes y transmitir la esencia de nuestros servicios.

7. **Optimización de Velocidad de Carga:** Nos aseguramos de que el diseño del Landing Page esté optimizado para una rápida velocidad de carga, garantizando una experiencia de usuario fluida y sin demoras.

8. **Inclusión de Testimonios y Comentarios:** Integraremos testimonios y comentarios de clientes satisfechos en el diseño del Landing Page para agregar credibilidad y confianza en nuestros servicios.

Con esta propuesta de diseño para el Landing Page, buscamos no solo transmitir la información de manera clara y efectiva, sino también crear una experiencia visualmente atractiva y coherente que refuerce la identidad de nuestra marca y motive a los usuarios a tomar medidas.

### 5.3.1. Landing Page Wireframe.
#### Desktop Web Browser
- Sección Home  
[![Home.png](https://i.postimg.cc/HLvMtSSp/Home.png)](https://postimg.cc/Z930bLtg)<br>
- Sección Product  
[![Product.png](https://i.postimg.cc/2jZW47nD/Product.png)](https://postimg.cc/bdqdPb6C) <br>
- Sección About  
[![About.png](https://i.postimg.cc/xCkzpK7L/About.png)](https://postimg.cc/1nQXfNyz) <br>
- Sección Price  
[![Price.png](https://i.postimg.cc/wTYmFRks/Price.png)](https://postimg.cc/z3pvGB6J) <br>
- Sección Review  
[![Review.png](https://i.postimg.cc/y8VSCqt1/Review.png)](https://postimg.cc/F7BK06h8)

#### Mobile Web Browser:
- Sección Home  
[![Home-1.png](https://i.postimg.cc/VLR9kS5M/Home-1.png)](https://postimg.cc/JGsHTzN4)<br>
- Sección: Product  
[![Product-1.png](https://i.postimg.cc/GpBvKqKJ/Product-1.png)](https://postimg.cc/CZgZLCWz) <br>
- Sección About  
[![About-1.png](https://i.postimg.cc/zX0W19PF/About-1.png)](https://postimg.cc/GHT9FSR4) <br>
- Sección Price  
[![Price-1.png](https://i.postimg.cc/D0hs2FTB/Price-1.png)](https://postimg.cc/FdP1ZM1L) <br>
- Sección Review  
[![Review-1.png](https://i.postimg.cc/G2wTQrHd/Review-1.png)](https://postimg.cc/v1hmYJrN) <br>

### 5.3.2. Landing Page Mock-up.
#### Desktop Web Browser
- Sección Home  
[![Home-1.png](https://i.postimg.cc/nzVdXwXp/Home-1.png)](https://postimg.cc/4KMvMPvS) <br>
- Sección: Product  
[![Product.png](https://i.postimg.cc/kGzwhJfg/Product.png)](https://postimg.cc/QKgpFr22) <br>
- Sección About  
[![About.png](https://i.postimg.cc/9fbbHtJS/About.png)](https://postimg.cc/rddxSW6C) <br>
- Sección Price  
[![Price.png](https://i.postimg.cc/yxgy9qs4/Price.png)](https://postimg.cc/0KvSRBzc) <br>
- Sección Review  
[![Review.png](https://i.postimg.cc/R0S8t0Yk/Review.png)](https://postimg.cc/21t2RCrG)
#### Mobile Web Browser:
- Sección Home  
[![Home.png](https://i.postimg.cc/K8t2T2Sn/Home.png)](https://postimg.cc/CRMXy9K1) <br>
- Sección: Product  
[![Product.png](https://i.postimg.cc/s2NCdDpC/Product.png)](https://postimg.cc/rdxP5Tnf) <br>
- Sección About  
[![About.png](https://i.postimg.cc/CLgTV2f5/About.png)](https://postimg.cc/XXQDfQL6) <br>
- Sección Price  
[![Price.png](https://i.postimg.cc/c4Zjz8V8/Price.png)](https://postimg.cc/kD1f6DMn) <br>
- Sección Review  
[![Review.png](https://i.postimg.cc/0yy4k15k/Review.png)](https://postimg.cc/yk2jj5St)
## 5.4. Applications UX/UI Design.
En esta sección, presentamos y explicamos la propuesta visual y de interacción para las aplicaciones que forman parte integral de la experiencia de usuario con nuestros productos digitales. Nuestro enfoque en el diseño de UX/UI para las aplicaciones se centra en crear interfaces intuitivas y atractivas que mejoren la usabilidad y la satisfacción de ambos segmentos objetivos. Cada aspecto del diseño se ha considerado cuidadosamente para garantizar una experiencia coherente y eficaz para nuestros usuarios. A continuación, detallamos nuestra propuesta para las aplicaciones, destacando tanto los aspectos visuales como de interacción.
### 5.4.1. Applications Wireframes.
#### Web Application:
##### Pet Owner y Vet:
- Boceto de Log-in y Sign-in:  
[![Log-in-1.png](https://i.postimg.cc/pdXqCK0J/Log-in-1.png)](https://postimg.cc/rD31FR2D)
[![Sign-up-Veterinaria.png](https://i.postimg.cc/NMZDQSQd/Sign-up-Veterinaria.png)](https://postimg.cc/WF6gn9FZ)
[![Sign-up-Veterinaria-1.png](https://i.postimg.cc/x8HR85Cn/Sign-up-Veterinaria-1.png)](https://postimg.cc/zHzWPnKc)

##### Pet Owner:
- Boceto de Home 'Pets' y Editar Pets:  
[![Home-Pet-Owners.png](https://i.postimg.cc/W19M2Cn0/Home-Pet-Owners.png)](https://postimg.cc/sMhBmnb2)
[![Home-Pet-Owners-1.png](https://i.postimg.cc/PqP1Ny39/Home-Pet-Owners-1.png)](https://postimg.cc/mcWP5YGy)

- Boceto de 'Citas':  
[![Home-Pet-Owners-citas.png](https://i.postimg.cc/JnXJ5nWQ/Home-Pet-Owners-citas.png)](https://postimg.cc/R6MNMvh3)

- Boceto de 'Agendar Cita' (Flujo de Tareas):  
[![Home-Pet-Owners-citas-1.png](https://i.postimg.cc/rwqPgF3b/Home-Pet-Owners-citas-1.png)](https://postimg.cc/6y1cpw9L)
[![Home-Pet-Owners-citas-2.png](https://i.postimg.cc/d0bRH5D1/Home-Pet-Owners-citas-2.png)](https://postimg.cc/McYjXb72)
[![Home-Pet-Owners-citas-3.png](https://i.postimg.cc/jdSfhpvc/Home-Pet-Owners-citas-3.png)](https://postimg.cc/BtRtSwrP)
[![Home-Pet-Owners-citas-4.png](https://i.postimg.cc/c4knkFbS/Home-Pet-Owners-citas-4.png)](https://postimg.cc/svSxv4z6)

##### Vet:
- Boceto de Home 'Pets':  
[![Home-Vets.png](https://i.postimg.cc/t41VKFKV/Home-Vets.png)](https://postimg.cc/gxWJRLkY)<br>

- Boceto de 'Citas':  
[![Appointments-Vets.png](https://i.postimg.cc/XvdBJ47j/Appointments-Vets.png)](https://postimg.cc/d7QVNMyp)

##### Pet Owner y Vet:
- Boceto de 'Profile':
[![Profile-Pet-Owners-Perfil.png](https://i.postimg.cc/x84154Tp/Profile-Pet-Owners-Perfil.png)](https://postimg.cc/Pv1HrKD1)<br>

- Boceto de 'Ajustes':
[![Settings-Pet-Owners-Perfil.png](https://i.postimg.cc/hvzBDPcM/Settings-Pet-Owners-Perfil.png)](https://postimg.cc/tnjfDb1V)<br>

#### Movile Application:
##### Pet Owner:
- Boceto de Log-in y Sign-in:  
 [![Iniciar-sesion.png](https://i.postimg.cc/Y96WGCgL/Iniciar-sesion.png)](https://postimg.cc/k654L9T7)
 [![Seleccion-usuario.png](https://i.postimg.cc/Hn38zv6p/Seleccion-usuario.png)](https://postimg.cc/QK9MxmLP)
 [![Cresar-cuenta-Due-o-de-Mascota.png](https://i.postimg.cc/BZCFJt4d/Cresar-cuenta-Due-o-de-Mascota.png)](https://postimg.cc/rzKsJVdJ)
 [![Cresar-cuenta-Due-o-de-Mascota-1.png](https://i.postimg.cc/9FF70Vfz/Cresar-cuenta-Due-o-de-Mascota-1.png)](https://postimg.cc/grQJtC8P) 

##### Vet:
- Boceto de Log-in y Sign-in:  
[![Crear-cuenta-Veterinaria.png](https://i.postimg.cc/BQY11y8p/Crear-cuenta-Veterinaria.png)](https://postimg.cc/2VW5s07L)
[![Crear-cuenta-Veterinaria-1.png](https://i.postimg.cc/g21XgZH6/Crear-cuenta-Veterinaria-1.png)](https://postimg.cc/dhmV1DXq)
[![Crear-cuenta-deto-del-Veterinario.png](https://i.postimg.cc/SK8X3xg1/Crear-cuenta-deto-del-Veterinario.png)](https://postimg.cc/QB8xWhGc)

##### Pet Owner:
- Boceto de sincronizar collar:  
[![Crear-cuenta-Dato-de-Mascota.png](https://i.postimg.cc/hv9RRNkB/Crear-cuenta-Dato-de-Mascota.png)](https://postimg.cc/8fP0hXkK)
[![Crear-cuenta-Dato-de-Mascota-1.png](https://i.postimg.cc/nL5yjHZx/Crear-cuenta-Dato-de-Mascota-1.png)](https://postimg.cc/SX6THbJ1)
[![Crear-cuenta-Dato-de-Mascota-2.png](https://i.postimg.cc/fL96Y6T9/Crear-cuenta-Dato-de-Mascota-2.png)](https://postimg.cc/jwRgb3fx) <br>
- Boceto de Agregar Pet:  
[![Crear-cuenta-Dato-de-Mascota-3.png](https://i.postimg.cc/Y0BTRbhy/Crear-cuenta-Dato-de-Mascota-3.png)](https://postimg.cc/sQKnDPPp) 
- Boceto de Home 'Pets':  
[![Home-Due-o-de-Mascota.png](https://i.postimg.cc/QCgwy17N/Home-Due-o-de-Mascota.png)](https://postimg.cc/LgXxqqvG)
[![Home-Due-o-de-Mascota-1.png](https://i.postimg.cc/zXj4ww50/Home-Due-o-de-Mascota-1.png)](https://postimg.cc/YhvXMWvW)
[![Menu-Due-o-de-Mascota.png](https://i.postimg.cc/P5Vc9tCD/Menu-Due-o-de-Mascota.png)](https://postimg.cc/w1J0sYcx) 
- Boceto de 'Citas':  
[![Home-Due-o-de-Mascota-2.png](https://i.postimg.cc/Lsq7MrPb/Home-Due-o-de-Mascota-2.png)](https://postimg.cc/jWbvH3ZH)
- Boceto de 'Agendar Cita' (Flujo de Tareas):  
[![Home-Due-o-de-Mascota-3.png](https://i.postimg.cc/sxJHcyFv/Home-Due-o-de-Mascota-3.png)](https://postimg.cc/y3kT1M8H)
[![Home-Due-o-de-Mascota-1.png](https://i.postimg.cc/V6qKf1kD/Home-Due-o-de-Mascota-1.png)](https://postimg.cc/jwjHcpN7)  
- Boceto Historial de la Mascota:  
[![Home-Due-o-de-Mascota-4.png](https://i.postimg.cc/y6TL2V5N/Home-Due-o-de-Mascota-4.png)](https://postimg.cc/V5d9Cczy)
- Boceto Sidebar:  
[![Menu-Due-o-de-Mascota-1.png](https://i.postimg.cc/XYrxZ9vZ/Menu-Due-o-de-Mascota-1.png)](https://postimg.cc/NKwRS9mY)
##### Vet:
- Boceto de Home:  
[![Home-Due-o-de-Mascota-5.png](https://i.postimg.cc/SK8rdqCk/Home-Due-o-de-Mascota-5.png)](https://postimg.cc/94mZX6Ln)
- Boceto de 'Macotas':  
[![Veterinaria-Mascotas.png](https://i.postimg.cc/SsfG0rgP/Veterinaria-Mascotas.png)](https://postimg.cc/CBd8kjTC)
- Boceto de 'Historial de Mascotas':  
[![Veterinaria-Historial-de-mascotas.png](https://i.postimg.cc/90xt0f5t/Veterinaria-Historial-de-mascotas.png)](https://postimg.cc/y3ZSrsNk) 
- Boceto de otros Vets en la misma Veterinaria:  
[![Veterinaria-Perfiles.png](https://i.postimg.cc/05ZCcVMM/Veterinaria-Perfiles.png)](https://postimg.cc/Hjc5L4td)
[![Veterinaria-Perfiles-1.png](https://i.postimg.cc/QxtJPc16/Veterinaria-Perfiles-1.png)](https://postimg.cc/K46T3k9L)

##### Pet Owner:
- Boceto de 'Profile':  
[![Menu-Due-o-de-Mascota-2.png](https://i.postimg.cc/5NRSMjmf/Menu-Due-o-de-Mascota-2.png)](https://postimg.cc/tYFx3qfc)
- Boceto de Cambiar Contraseña:  
[![Menu-Due-o-de-Mascota-3.png](https://i.postimg.cc/BvxTDpfv/Menu-Due-o-de-Mascota-3.png)](https://postimg.cc/mcg1WQDx)
- Boceto de Cerrar sesión:  
[![Menu-Due-o-de-Mascota-4.png](https://i.postimg.cc/0Qn7XNQR/Menu-Due-o-de-Mascota-4.png)](https://postimg.cc/gXwwnm8N) <br>
##### Vet:
- Boceto de 'Ajustes':  
[![Veterinaria-Ajustes.png](https://i.postimg.cc/4ynH8bqV/Veterinaria-Ajustes.png)](https://postimg.cc/GTwptYcm)

### 5.4.2. Applications Wireflow Diagrams. 

#### Web Application Wireflow Diagrams:

#### User goal: 

Registrarse en la aplicación.

Como usuario quiero registrarme en la aplicación.

Task Flow:
- El usuario se encuentra en el log in
- El usuario se dirige a Sign Up
- El usuario selecciona el tipo de cuenta
- El usuario rellena los el formulario
- El usuario crea su cuenta


[![WWF1.png](https://i.postimg.cc/gcxp2ZH5/WWF1.png)](https://postimg.cc/Hj1RSjK4)

#### User goal:

Agregar una mascota.

Como usuario quiero agregar una mascota.

Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Mascotas 
- El usuario agrega una nueva mascota 
- El usuario rellena los datos de la nueva mascota


[![WWF2.png](https://i.postimg.cc/5NvMwWGS/WWF2.png)](https://postimg.cc/zVJMr6qy)

#### User goal:

Agendar una cita.

Como usuario quiero agendar una cita con el veterinario.

Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Citas
- El usuario selecciona Añadir Cita
- El usuario selecciona la veterinaria
- El usuario selecciona el veterinario disponible
- El usuario selecciona la fecha y hora
- El usuario agenda la cita


[![WWF3.png](https://i.postimg.cc/QMNGG9Mf/WWF3.png)](https://postimg.cc/dhfSG0rC)

#### User goal:

Editar perfil.

Como usuario quiero editar los datos de mi perfil.

Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Perfil
- El usuario edita sus datos
- El usuario guarda los cambios


[![WWF4.png](https://i.postimg.cc/yNfqV1gs/WWF4.png)](https://postimg.cc/KKgpfyDH)

#### User goal:

Cambiar contraseña.

Como usuario quiero tener la opción de cambiar mi contraseña. 

Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Ajustes
- El usuario ingresa su contraseña actual, la contraseña nueva y la confirma
- El usuario guarda los cambios


[![WWF5.png](https://i.postimg.cc/LX7r1x3W/WWF5.png)](https://postimg.cc/R67srQ81)

#### Mobile Application Wireflow Diagrams:

#### User Goal:
Registrarse en la aplicación.

Como usuario quiero registrarme en la aplicación.

Task Flow:
- El usuario se encuentra en el log in
- El usuario se dirige a Sign Up
- El usuario selecciona el tipo de cuenta
- El usuario rellena los formularios
- El usuario crea su cuenta

[![MWF1.png](https://i.postimg.cc/vTVCL5PZ/MWF1.png)](https://postimg.cc/9wcxcw56)

#### User Goal:

Supervisa los datos recopilados de las mascotas.

Como usuario quiero supervisa los datos recopilados de mis mascotas.

Task Flow:
- El usuario ingresa a la aplicación
- El usuario selecciona una de las 6 opciones de recopilación de datos

[![MWF2.png](https://i.postimg.cc/J7HwLW1C/MWF2.png)](https://postimg.cc/6TKbrg2M)

#### User Goal:

Agendar una cita.

Como usuario quiero agendar una cita con el veterinario.

Task Flow:
- El usuario ingresa a la aplicación
- El usuario se dirige a Citas
- El usuario selecciona Añadir Cita
- El usuario selecciona la veterinaria
- El usuario selecciona el veterinario disponible
- El usuario selecciona la fecha y hora
- El usuario agenda la cita

[![MWF3.png](https://i.postimg.cc/v8JJ8SBg/MWF3.png)](https://postimg.cc/w3kf02Dg)

#### User Goal:

Editar información de mascota.

Como usuario quiero editar la información de mi mascota. 

Task Flow:
- El usuario ingresa a la aplicación
- El usuario se dirige a más opciones
- El usuario selecciona Mascotas 
- El usuario selecciona la mascota
- El usario edita la información y guarda los cambios

[![MWF4.png](https://i.postimg.cc/ZK61WFBf/MWF4.png)](https://postimg.cc/KRv9VT5L)

#### User Goal:

Editar perfil.

Como usuario quiero editar la información de mi perfil. 

Task Flow:
- El usuario ingresa a la aplicación
- El usuario se dirige a más opciones
- El usuario se dirige a Perfil
- El usuario edita sus datos
- El usuario guarda los cambios

[![MWF5.png](https://i.postimg.cc/HkHFXcbT/MWF5.png)](https://postimg.cc/nCRdtLdW)

### 5.4.2. Applications Mock-ups.
#### Web Application:
##### Pet Owner y Vet:
- Mock-ups de Log-in y Sign-in:  
[![Log-in-2.png](https://i.postimg.cc/7LVCwWyS/Log-in-2.png)](https://postimg.cc/McnZYtHG)
[![usuarios.png](https://i.postimg.cc/d3z35M8c/usuarios.png)](https://postimg.cc/zHFqfctx)

##### Pet Owner:
- Mock-ups de Home 'Pets' y Editar Pets:  
[![Home-Pet-Owners-2.png](https://i.postimg.cc/ZKdCCRSb/Home-Pet-Owners-2.png)](https://postimg.cc/ppP2SPr4)
[![Home-Pet-Owners-3.png](https://i.postimg.cc/VNDN30jR/Home-Pet-Owners-3.png)](https://postimg.cc/Ty5GbwNL)<br>

- Boceto de 'Citas':  
[![Home-Pet-Owners-citas-5.png](https://i.postimg.cc/DZNwzVp4/Home-Pet-Owners-citas-5.png)](https://postimg.cc/wyhpWrp9)<br>

- Boceto de 'Agendar Cita' (Flujo de Tareas):  
[![Home-Pet-Owners-citas-6.png](https://i.postimg.cc/K4ScnP2Z/Home-Pet-Owners-citas-6.png)](https://postimg.cc/T50XxW1S) 
[![Home-Pet-Owners-citas-7.png](https://i.postimg.cc/WpDMwsvK/Home-Pet-Owners-citas-7.png)](https://postimg.cc/RqB6M5qQ)
[![Home-Pet-Owners-citas-8.png](https://i.postimg.cc/Qx11vSVJ/Home-Pet-Owners-citas-8.png)](https://postimg.cc/zVDygCCy) 
[![Home-Pet-Owners-citas-9.png](https://i.postimg.cc/s2DWQrmT/Home-Pet-Owners-citas-9.png)](https://postimg.cc/QFwCwvR7)

##### Vet:
- Mock-up de Home 'Pets':  
[![Home-Vets-1.png](https://i.postimg.cc/JzRDvLfR/Home-Vets-1.png)](https://postimg.cc/7fQZJpPR)
- Mock-up de 'Citas':  
[![Home-Pet-Owners-citas-5.png](https://i.postimg.cc/DZNwzVp4/Home-Pet-Owners-citas-5.png)](https://postimg.cc/wyhpWrp9)

##### Pet Owner y Vet:
- Mock-up de 'Profile':  
[![Profile-Pet-Owners-Perfil-1.png](https://i.postimg.cc/PxJdFnVb/Profile-Pet-Owners-Perfil-1.png)](https://postimg.cc/qhffzSTg)<br>
- Mock-up de 'Ajustes':  
[![Settings-Pet-Owners-Perfil-1.png](https://i.postimg.cc/0Q4PTXhT/Settings-Pet-Owners-Perfil-1.png)](https://postimg.cc/mz7vMjLj)

#### Movile Application:
##### Pet Owner y Vets:
- Mock-up de Log-in y Sign-in:  
[![Bienvenida.png](https://i.postimg.cc/HswjMHqj/Bienvenida.png)](https://postimg.cc/D8z2kVyK)
[![Iniciar-sesion-1.png](https://i.postimg.cc/DzZzRG8b/Iniciar-sesion-1.png)](https://postimg.cc/qNP03zck)
[![Seleccion-usuario-1.png](https://i.postimg.cc/MHkKcrty/Seleccion-usuario-1.png)](https://postimg.cc/r0JL3jBm)
[![Cresar-cuenta-Due-o-de-Mascota-2.png](https://i.postimg.cc/5NSN0gzC/Cresar-cuenta-Due-o-de-Mascota-2.png)](https://postimg.cc/WhtPYMXN)
[![Cresar-cuenta-Due-o-de-Mascota-3.png](https://i.postimg.cc/QdNNW7gn/Cresar-cuenta-Due-o-de-Mascota-3.png)](https://postimg.cc/HVK1qVhQ)
[![Crear-cuenta-Veterinaria-2.png](https://i.postimg.cc/BvXqmGVT/Crear-cuenta-Veterinaria-2.png)](https://postimg.cc/GBnwp6rt)
[![Crear-cuenta-Veterinaria-3.png](https://i.postimg.cc/CKXwt63W/Crear-cuenta-Veterinaria-3.png)](https://postimg.cc/wt5KRFTV)
[![Crear-cuenta-deto-del-Veterinario-1.png](https://i.postimg.cc/3RG3HF7W/Crear-cuenta-deto-del-Veterinario-1.png)](https://postimg.cc/cgdpRYvN)
- Mock-up de Sincronizar collar y Agregar mascota  
[![Crear-cuenta-Dato-de-Mascota-4.png](https://i.postimg.cc/sx9yMfMr/Crear-cuenta-Dato-de-Mascota-4.png)](https://postimg.cc/7J6jck1s)
[![Crear-cuenta-Dato-de-Mascota-5.png](https://i.postimg.cc/59wf7gnR/Crear-cuenta-Dato-de-Mascota-5.png)](https://postimg.cc/YjCcj6c6)

##### Pet Owner:
- Mock-up Home 'Mascotas':  
[![Home-Due-o-de-Mascota-6.png](https://i.postimg.cc/4Nssrc0N/Home-Due-o-de-Mascota-6.png)](https://postimg.cc/rznB4Dcv)
[![Home-Due-o-de-Mascota-7.png](https://i.postimg.cc/KvfxFzX7/Home-Due-o-de-Mascota-7.png)](https://postimg.cc/RNWjLvZq) 
- Mock-up 'Historial':  
[![Home-Due-o-de-Mascota-8.png](https://i.postimg.cc/y8rKgb8k/Home-Due-o-de-Mascota-8.png)](https://postimg.cc/MnRNgtRS)
- Mock-up 'Mascotas' y Agregar mascotas:  
[![Menu-Due-o-de-Mascota-5.png](https://i.postimg.cc/Dz9K54sh/Menu-Due-o-de-Mascota-5.png)](https://postimg.cc/jW49S5Z3)
[![Menu-Due-o-de-Mascota-6.png](https://i.postimg.cc/3R2QqrCv/Menu-Due-o-de-Mascota-6.png)](https://postimg.cc/zbDQbrQz)
- Mock-up Agendar Cita:  
[![Home-Due-o-de-Mascota-9.png](https://i.postimg.cc/2ymNNp2X/Home-Due-o-de-Mascota-9.png)](https://postimg.cc/qhm52Ff8)
[![Home-Due-o-de-Mascota-10.png](https://i.postimg.cc/yxP4VfG6/Home-Due-o-de-Mascota-10.png)](https://postimg.cc/H8VPztHF)
[![Home-Due-o-de-Mascota-11.png](https://i.postimg.cc/nVYtYzL8/Home-Due-o-de-Mascota-11.png)](https://postimg.cc/9zMSccT1)
[![Home-Due-o-de-Mascota-12.png](https://i.postimg.cc/KvGh92K1/Home-Due-o-de-Mascota-12.png)](https://postimg.cc/py6ST3Jv)

#### Vet:
- Mock-up Home:  
[![Home-Veterinaria.png](https://i.postimg.cc/x1qD233Y/Home-Veterinaria.png)](https://postimg.cc/zymPwWQP) 
- Mock-up Mascotas:  
[![Menu-Due-o-de-Mascota-5.png](https://i.postimg.cc/Dz9K54sh/Menu-Due-o-de-Mascota-5.png)](https://postimg.cc/jW49S5Z3) 
- Mock-up Historial:  
[![Home-Due-o-de-Mascota-8.png](https://i.postimg.cc/y8rKgb8k/Home-Due-o-de-Mascota-8.png)](https://postimg.cc/MnRNgtRS) 
- Mock-up de otros Vets en la misma Veterinaria:  
[![Veterinaria-Perfiles-2.png](https://i.postimg.cc/7ZcvYJKz/Veterinaria-Perfiles-2.png)](https://postimg.cc/87hXZcQk)
[![Veterinaria-Perfiles-3.png](https://i.postimg.cc/d0Tb7Qfx/Veterinaria-Perfiles-3.png)](https://postimg.cc/4KsLqGs6)
[![Veterinaria-Perfiles-4.png](https://i.postimg.cc/zBZ9TZZX/Veterinaria-Perfiles-4.png)](https://postimg.cc/rdjnLHwv)


### 5.4.3. Applications User Flow Diagrams.

#### Web Application User Flow Diagrams:

#### User Flow N°1:

a) User Goal: 
Registrarse en la aplicación.
Como usuario quiero registrarme en la aplicación.

b) Task Flow:
- El usuario se encuentra en el log in
- El usuario se dirige a Sign Up
- El usuario selecciona el tipo de cuenta
- El usuario rellena los el formulario
- El usuario crea su cuenta

c) User Flow

[![WUF1.png](https://i.postimg.cc/mgwJwLSC/WUF1.png)](https://postimg.cc/zyyxD16G)

#### User Flow N°2:

a) User Goal:
Agregar una mascota.
Como usuario quiero agregar una mascota.

b) Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Mascotas 
- El usuario agrega una nueva mascota 
- El usuario rellena los datos de la nueva mascota

c) User Flow:

[![WUF2.png](https://i.postimg.cc/6QpSbkHS/WUF2.png)](https://postimg.cc/gx1NnTbq)

#### User Flow N°3:

a) User Goal: 
Agendar una cita.
Como usuario quiero agendar una cita con el veterinario.

b) Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Citas
- El usuario selecciona Añadir Cita
- El usuario selecciona la veterinaria
- El usuario selecciona el veterinario disponible
- El usuario selecciona la fecha y hora
- El usuario agenda la cita

c) User Flow:

[![WUF3.png](https://i.postimg.cc/jj31pMmj/WUF3.png)](https://postimg.cc/mcMVMybx)

#### User Flow N°4:

a) User Goal: 
Editar perfil.
Como usuario quiero editar los datos de mi perfil.

b) Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Perfil
- El usuario edita sus datos
- El usuario guarda los cambios

c) User Flow:

[![WUF4.png](https://i.postimg.cc/V6ShmjPW/WUF4.png)](https://postimg.cc/47gP1HdY)

#### User Flow N°5:

a) User Goal:
Cambiar contraseña.
Como usuario quiero tener la opción de cambiar mi contraseña. 

b) Task Flow:
- El usuario inicia sesión
- El usuario se dirige a Ajustes
- El usuario ingresa su contraseña actual, la contraseña nueva y la confirma
- El usuario guarda los cambios

c) User Flow:

[![WUF5.png](https://i.postimg.cc/26PK6VzR/WUF5.png)](https://postimg.cc/cgBmk1gX)

#### Mobile Application User Flow Diagrams:

#### User Flow N°1:

a) User goal: 
Registrarse en la aplicación
Como usuario quiero registrarme en la aplicación.

b) Task Flow: 
- El usuario se encuentra en el log in 
- El usuario se dirige a Sign Up 
- El usuario selecciona el tipo de cuenta
- El usuario rellena los el formulario 
- El usuario crea su cuenta

c) User Flow:

[![MUF1-2.png](https://i.postimg.cc/6qn1Gt37/MUF1-2.png)](https://postimg.cc/SYQGB0cq)

#### User Flow N°2:

a) User goal:
Supervisa los datos recopilados de las mascotas.
Como usuario quiero supervisa los datos recopilados de mis mascotas.

b) Task Flow:
- El usuario ingresa a la aplicación 
- El usuario selecciona una de las 6 opciones de recopilación de datos

c) User Flow:

[![MUF2-2.png](https://i.postimg.cc/VsChhBRY/MUF2-2.png)](https://postimg.cc/s13KQWq8)

#### User Flow N°3:

a) User Goal:
Agendar una cita.
Como usuario quiero agendar una cita con el veterinario.

b) Task Flow:
- El usuario ingresa a la aplicación 
- El usuario se dirige a Citas 
- El usuario selecciona Añadir Cita 
- El usuario selecciona la veterinaria 
- El usuario selecciona el veterinario disponible 
- El usuario selecciona la fecha y hora 
- El usuario agenda la cita

c) User Flow:

[![MUF3-2.png](https://i.postimg.cc/5NWrWY78/MUF3-2.png)](https://postimg.cc/V54gj6cN)

#### User Flow N°4:

a) User Goal:
Editar información de mascota.
Como usuario quiero editar la información de mi mascota. 

b)  Task Flow:
- El usuario ingresa a la aplicación 
- El usuario se dirige a más opciones 
- El usuario selecciona Mascotas 
- El usuario selecciona la mascota 
- El usario edita la información y guarda los cambios

c) User Flow:

[![MUF4-2.png](https://i.postimg.cc/ZKPMbb22/MUF4-2.png)](https://postimg.cc/hfjrMBS1)

#### User Flow N°5:

a) User Goal:
Editar perfil.
Como usuario quiero editar la información de mi perfil. 

b) Task Flow:
- El usuario ingresa a la aplicación 
- El usuario se dirige a más opciones 
- El usuario se dirige a Perfil 
- El usuario edita sus datos 
- El usuario guarda los cambios

c) User Flow:

[![MUF5-2.png](https://i.postimg.cc/3xKbdMHR/MUF5-2.png)](https://postimg.cc/VdVFVVvQ)

## 5.5. Applications Prototyping.
