## 6.1. Software Configuration Management.
### 6.1.1. Software Development Environment Configuration.
#### Proyect Management:  
##### Formato Markdown
-	Propósito: Organizar en varios archivos con extensión .md segmentados en capítulos, donde se desarrollará el Informe y posteriormente extraerá el pdf presentado en la entrega al aula virtual.
-	Ruta: [https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
##### Git y Github
- Propósito: Usado para el control de versiones del proyecto.
- Ruta: [https://git-scm.com/](https://git-scm.com/) , [https://github.com/](https://github.com/)
##### Whatsapp y Discord
- Propósito: Comunicarse, reunirse y compartir documentación relevante con los otros integrantes del equipo.
- Ruta: [https://www.whatsapp.com/?lang=es_LA](https://www.whatsapp.com/?lang=es_LA) , [https://discord.com/](https://discord.com/) 
##### Pivotal Tracker
- Propósito: Control de proyecto y asignación de tareas a los integrantes del equipo de desarrollo.
- Ruta: [https://www.pivotaltracker.com/dashboard](https://www.pivotaltracker.com/dashboard)  
#### Product UX/UI Design: 
##### Figma
-	Propósito: Elaboración de Wireframes, Mock-ups y Prototypes.
-	Ruta: [https://www.figma.com/](https://www.figma.com/) 
##### Miro
-	Propósito: As-Is y To-Be Scenario Maps
-	Ruta: [https://miro.com/es/](https://miro.com/es/) 
##### Structurizr
-	Propósito: Elaboración de diagramas C4.
-	Ruta: [https://structurizr.com/](https://structurizr.com/) 
##### UXPressia
-	Propósito: Elaboración de User Personas, Empathy Maps, Journey Maps e Impact Maps.
-	Ruta: [https://uxpressia.com/](https://uxpressia.com/) 
#### Software Development:
##### Visual Studio Code, Angular Framework y Spring Boot Framework
-	Propósito: Editor de código usado por el equipo para el desarrollo del Landing Page, Frontend Web application y Web Services, pasa los cuales se usará Angular Framework HTML5, CSS3 y JavaScript en caso del Frontend y Spring Boot Framework en caso del Backend, sin embargo, para la primera entrega utilizamos una Fake API usando Json server.
-	Ruta: [https://code.visualstudio.com/](https://code.visualstudio.com/) , [https://angular.io/](https://angular.io/) , [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot) , [https://www.npmjs.com/package/json-server](https://www.npmjs.com/package/json-server) 
##### C++ y 
Software Testing, Software Deployment:
##### GitHub Pages:
-	Propósito: Desplegar la landing Page.
-	Ruta: [https://pages.github.com/](https://pages.github.com/) 
##### Netlify:
-	Propósito: Desplegar la Web Application.
-	Ruta: [https://www.netlify.com/](https://www.netlify.com/) 
#### Software Documentation
##### OpenAPI Specification vía Swagger:
-	Propósito: Documentación de Web Services
-	Ruta: [https://swagger.io/](https://swagger.io/) 
#### Para IoT Device
##### Arduino:
-	Propósito: Management, Cloud Computing y Edge Computing.
-	Ruta: [https://www.arduino.cc/](https://www.arduino.cc/) 

### 6.1.2. Source Code Management.
Como se mencionó en la sección anterios, se utiliza GitHub como plataforma y sistema de control de versiones.
#### Gitflow implementation según Vincent Driessen
- **Master / Main Branch:** Se considera a main como la rama principal, siempre está en un estado listo para producción. Esta es la rama que se usa para los despliegues.  
Notación usada: main
- **Develop Branch:** Es donde el código refleja los últimos cambios de desarrollo entregados para la próxima versión.  Podremos considerarla la "rama de integración", ya que es desde aquí donde se generan las compilaciones automáticas nocturnas.  
Notación usada: develop
- **Release Branch:** Permite la preparación de un nuevo lanzamiento de producción, facilitando ajustes finales y corrección de errores menores, así como la preparación de metadatos para el lanzamiento.  
Notación usada: release[release-versionNumber]
- **Feature Branch:** Se utiliza para desarrollar nuevas funcionalidades para futuras versiones. Se derivan de la rama "develop" y deben fusionarse nuevamente en ella una vez que la característica esté completa.  
Notación usada: feature/[name of feature] o [name of feature]
- **Hotfix Branch:**  Surge de la necesidad de actuar de inmediato ante un estado no deseado de una versión de producción. Cuando se debe resolver de inmediato un error crítico en una versión de producción, se puede derivar una rama de hotfix desde la etiqueta correspondiente en la rama "main" que marca la versión de producción. La esencia de las ramas de hotfix es permitir que el trabajo de los miembros del equipo (en la rama "develop") continúe mientras otra persona prepara una corrección rápida para producción. Estas ramas se crean ***a partir de la rama "main"*** y, una vez corregido el problema, se fusionan nuevamente tanto en "develop" como en "main".  
Notación usada: hotfix[hotfix-versionNumber]
#### Conventional Commits:
La estructura que se sigue en los commits de este proyecto, tomando en cuenta el artículo "Conventional Commits 2.0.0", es:  
"(type) [optional scope]: (description)"
##### Type:
- fix: Para parchar un error en el repositorio.
- feat: Para introducir un nuevo feature al repositorio.
- BREAKING CHANGE (footer): Un commit tiene este footer o tiene un "!" luego del (type) cuando introduce un "breaking API change", es decir, un cambio que cambia la forma en la que los usuarios interactúan con el API.
- add: Para indicar que se añadieron archivos o carpetas.
- test: Para indicar que se agregaron nuevos tests.
- [optional scope]:Solo en las ramas release, hotfix y main para indicar la versión.
##### Repositorios:
- Landing page: [https://github.com/XForce-IOt/Landing-Page](https://github.com/XForce-IOt/Landing-Page)
- Frontend Web Application: [https://github.com/XForce-IOt/Frontend](https://github.com/XForce-IOt/Frontend)
- Frontent Movile Application: [https://github.com/XForce-IOt/Mobile](https://github.com/XForce-IOt/Mobile)
- Informe: [https://github.com/XForce-IOt/upc-pre-202401-si572-WS71-XForce-report](https://github.com/XForce-IOt/upc-pre-202401-si572-WS71-XForce-report)
### 6.1.3. Source Code Style Guide & Conventions.
#### HTML Style Guide for the proyect
- Siempre declarar el Document Type: < !DOCTYPE html>
- Utiliza Lowercase para los elementos y atributos: body, p, label, href
- Siempre agregar los atributos entre comillas: class="striped"
#### Gherkin Specifications:
- Los escenaros deben mantener la estructura simple Given, When, Then. Para los steps, se agrega And. Ejemplo:  
[![Captura-de-pantalla-2024-05-03-065621.png](https://i.postimg.cc/50sp4bFd/Captura-de-pantalla-2024-05-03-065621.png)](https://postimg.cc/0MJ7Zgfc)

#### Angular Code Style Guide:
- Single responsibility - Rule of One: Definir los componentes por tarea, de modo que solo hagan una cosa. Además, asegurarse que el componente no pase las 44 líneas de código. Esto evitará tener bugs creados por la combinación accidental de componentes.
- Single responsibility - Small functions: Utilizar funciones pequeñas (no más de 75 líneas de código) hará que estas sean más fáciles de testear, leer y mantener. Además, promueven el reuso.
- General Naming Guidelines: Sigue un patrón que describa el feature y luego el tipo. El patrón recomendado es **"feature.type.ts"**
- Symbols and file names: Upper cammel case para los nombres de clase. Añade el símbolo del nombre con el sufijo, como Component, Directive, Module, Pipe, o Service, y dale al nombre del archivo el mismo sufijo, como .component.ts, .directive.ts, .module.ts, .pipe.ts, or .service.ts.   
[![Captura-de-pantalla-2024-05-03-071724.png](https://i.postimg.cc/L5MyQNfh/Captura-de-pantalla-2024-05-03-071724.png)](https://postimg.cc/r0QCKGfL)  
### 6.1.4. Software Deployment Configuration.
#### Despliegue de la landing page en GitHub Pages:
1. Seleccionar Settings  
[![Captura-de-pantalla-2024-05-03-072306.png](https://i.postimg.cc/L5XqSMjW/Captura-de-pantalla-2024-05-03-072306.png)](https://postimg.cc/tZKRdwSd)
2. Selecciona Pages  
[![Captura-de-pantalla-2024-05-03-072534.png](https://i.postimg.cc/zBdB0P4F/Captura-de-pantalla-2024-05-03-072534.png)](https://postimg.cc/jw7tjvxD)  
3. Seleccionar la rama desde donde se desea desplegar y Save  
[![Captura-de-pantalla-2024-05-03-072846.png](https://i.postimg.cc/DZmFyfY1/Captura-de-pantalla-2024-05-03-072846.png)](https://postimg.cc/LYdGxSSs)

## 6.2. Landing Page, Services & Applications Implementation.
### 6.2.1. Sprint 1
Sprint Goal: Durante el primer sprint, el equipo se centró en los siguientes entregables: el diseño de la arquitectura de software, la creación del diagrama de la base de datos, diagramas C4, el desarrollo del Tactical-Level Domain-Driven Design para cada Bounded context, así como la implementación y el despliegue exitoso de la landing page y la Web Application.
#### 6.2.1.1. Sprint Planning 1.
| **Sprint #**                       | 1                                                                                                                           |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**     |                                                                                                                             |
| Date                               | 2024-04-17                                                                                                                  |
|                Time                | 10:00 PM                                                                                                                    |
| Location                           | Reunión via Google Meet                                                                                                     |
| Prepared By                        | Jaramillo Almora Jesica Rut                                                                                                 |
| Attendees (to planning meeting)    | Almeyda Alania, Fredy Antonio / Aquino Cruz, Leonardo José / Mendoza Barco, Saúl Enrique / Quispe Villegas, Emerson Gerardo |
| Sprint n – 1 Review Summary        | Este es el primer Sprint.                                                                                                   |
| Sprint n – 1 Retrospective Summary | Este es el primer Sprint.                                                                                                   |
| **Sprint Goal & User Stories**     |                                                                                                                             |
| Sprint n Goal                      | Correción del Informe, despliegue de la Landing page y la Web Application consumiendo una Fake API.                         |
| Sprint n Velocity                  | 20                                                                                                                          |
| Sum of Story Points                | 17                                                                                                                          |
#### 6.2.1.2. Sprint Backlog 1.
[![backlog.png](https://i.postimg.cc/SNGZVBrM/backlog.png)](https://postimg.cc/KRRr8sCG)
[https://www.pivotaltracker.com/n/projects/2703036](https://www.pivotaltracker.com/n/projects/2703036)
#### 6.2.1.3. Development Evidence for Sprint Review.
[![sprint.png](https://i.postimg.cc/dtKCDDG2/sprint.png)](https://postimg.cc/Z0VnMb7n)
[https://upcedupe-my.sharepoint.com/:x:/g/personal/u20201c163_upc_edu_pe/EUnjzl5QYdVGvw-6Bya0SdsBwnEhiCo3WPQqITynuv9vPA?e=NR5nOv](https://upcedupe-my.sharepoint.com/:x:/g/personal/u20201c163_upc_edu_pe/EUnjzl5QYdVGvw-6Bya0SdsBwnEhiCo3WPQqITynuv9vPA?e=NR5nOv)  

#### 6.2.1.4. Testing Suite Evidence for Sprint Review.
No se realizaron tests durante esta entrega.
#### 6.2.1.5. Execution Evidence for Sprint Review.
Durante este sprint, se completaron los entregables:  
- Primera versión de la Aplicación Web
- Primera versión de la Landing Page  

Vista pets y metrics  
[![Imagen1.png](https://i.postimg.cc/CxBWs9qQ/Imagen1.png)](https://postimg.cc/18SC9CMG)  
#### 6.2.1.6. Services Documentation Evidence for Sprint Review.
Durante el desarrollo de este sprint, se utilizó Json-server para simular nuestro servicio de backend mientras este se encontraba en desarrollo.  
Fake n-points:  
[![Captura-de-pantalla-2024-06-08-203643.png](https://i.postimg.cc/9Xx9GkVT/Captura-de-pantalla-2024-06-08-203643.png)](https://postimg.cc/G9y9Rq4h)  
[![Captura-de-pantalla-2024-06-08-203722.png](https://i.postimg.cc/CLzqJ4L2/Captura-de-pantalla-2024-06-08-203722.png)](https://postimg.cc/crGCLw37)  
[![Captura-de-pantalla-2024-06-08-203750.png](https://i.postimg.cc/xThbZbX1/Captura-de-pantalla-2024-06-08-203750.png)](https://postimg.cc/jL65w26p)  

#### 6.2.1.7. Software Deployment Evidence for Sprint Review.
DUrante este Sprinte, se desplegó la primera versión de la aplicación web.
[![Imagen1.png](https://i.postimg.cc/CxBWs9qQ/Imagen1.png)](https://postimg.cc/18SC9CMG)  
https://pet-health.netlify.app/  

#### 6.2.1.8. Team Collaboration Insights during Sprint.
Se evidencia la participación del equipo de desarrollo durante el Sprint.  
[![Imagen1.png](https://i.postimg.cc/tTjcNT3r/Imagen1.png)](https://postimg.cc/v10XQGS9)  
### 6.2.2. Sprint 2
##### 6.2.2.1.Sprint Planning 2.
<table>
	<tbody>
		<tr>
			<td>Sprint#

</td>
			<td>Sprint 2

</td>
		</tr>
		<tr>
			<td colspan="2">Sprint Planning Background

</td>
		</tr>
		<tr>
			<td>Date</td>
			<td>2024-05-13

</td>
		</tr>
		<tr>
			<td>Time</td>
			<td>10:00 pm

</td>
		</tr>
		<tr>
			<td>Location</td>
			<td>Reunión virtual en la plataforma Discord

</td>
		</tr>
		<tr>
			<td>Prepared By</td>
			<td>Rut Jaramillo</td>
		</tr>
		<tr>
			<td>Attendees (to planning meeting)</td>
			<td>Ruth Jaramillo, Leonardo Aquino, Saul Mendoza, Fredy Almeida, Emerson Quispe</td>
		</tr>
		<tr>
			<td>Sprint n-1 Review Summary</td>
			<td>Se desplegó correctamente el landing page y el frontend. Este último funcionaba con fakeApi</td>
		</tr>
		<tr>
			<td>Sprint n-1 Retrospective Summary</td>
			<td>No tuvimos demasiadas reuniones, no trabajamos mucho en conjunto

</td>
		</tr>
		<tr>
			<td colspan="2">Sprint Goal &amp; User Stories</td>
		</tr>
		<tr>
			<td>Sprint n Goal</td>
			<td>Tener desplegado el backend. 
Terminar de implementar el frontend para el móvil, el IoT application y el edge backend
</td>
		</tr>
		<tr>
			<td>Sprint n Velocity

</td>
			<td>35</td>
		</tr>
		<tr>
			<td>Sum of story Points

</td>
			<td>31</td>
		</tr>
	</tbody>
</table>

##### 6.2.2.2.Sprint Backlog 2.

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint n

</td>
		</tr>
		<tr>
			<td colspan="2">User Story

</td>
			<td colspan="6">Work-item / Task

</td>
		</tr>
		<tr>
			<td>Id

</td>
			<td>Title

</td>
			<td>Id</td>
			<td>Title

</td>
			<td>Descripción

</td>
			<td>Estimation (Hours)
</td>
			<td>Assigned To

</td>
			<td>Status
(To-do/ In Process/ To-Review/ Done)

</td>
		</tr>
		<tr>
			<td rowspan="3">US048
</td>
			<td rowspan="3">Obtener listado de Mascotas a través de un RESTful API</td>
			<td>T001</td>
			<td>Crear la entidad y queries que se va a usar

</td>
			<td>Identificar los atributos para la entidad y los commands y queries que van a ser necesarios</td>
			<td>3</td>
			<td>Emerson

</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T002</td>
			<td>Crear servicio para obtener listado de mascotas</td>
			<td>Desarrollar la lógica de negocio que maneja la obtención de mascotas desde la base de datos</td>
			<td>3</td>
			<td>Emerson</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T003</td>
			<td>Crear endpoint para obtener listado de mascotas</td>
			<td>Implementar un endpoint que devuelva un listado de mascotas para un PetOwner</td>
			<td>2</td>
			<td>Emerson</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="3">US049</td>
			<td rowspan="3">Obtener datos de una mascota a través de un RESTful API</td>
			<td>T004</td>
			<td>Implementar el query</td>
			<td>Identificar y desarrollar el query necesario</td>
			<td>3</td>
			<td>Emerson</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T005</td>
			<td>Crear servicio para obtener datos de una mascota</td>
			<td>Desarrollar la lógica de negocio para obtener los datos específicos de una mascota desde la base de datos</td>
			<td>3</td>
			<td>Emerson</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T006</td>
			<td>Crear endpoint para obtener datos de una mascota</td>
			<td>Implementar un endpoint que devuelva los datos específicos de una mascota</td>
			<td>2</td>
			<td>Emerson</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="3">US050</td>
			<td rowspan="3">Editar perfil de mascota a través de un RESTful API</td>
			<td>T007

</td>
			<td>Implementar el command para el edición de datos</td>
			<td>Identificar y desarrollar el command para editar el perfil de una mascota</td>
			<td>3</td>
			<td>Fredy</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T008

</td>
			<td>Crear servicio para editar perfil de mascota</td>
			<td>Desarrollar la lógica de negocio para editar el perfil de una mascota</td>
			<td>3</td>
			<td>Fredy</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T009

</td>
			<td>Crear endpoint para editar perfil de mascota</td>
			<td>Implementar un endpoint que permita la edición del perfil de una mascota</td>
			<td>2</td>
			<td>Fredy</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">US060</td>
			<td rowspan="2">Obtener listado de Citas por un Dueño de mascota a través de un RESTful API</td>
			<td>T010</td>
			<td>Crear servicio para obtener listado de citas</td>
			<td>Desarrollar la lógica de negocio que maneja la obtención de citas desde la base de datos</td>
			<td>4</td>
			<td>Leonardo</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T011</td>
			<td>Crear endpoint para obtener listado de citas</td>
			<td>Implementar un endpoint que devuelva un listado de citas para un PetOwner</td>
			<td>2</td>
			<td>Leonardo</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">US061</td>
			<td rowspan="2">Obtener listado de Clínicas a través de un RESTful API</td>
			<td>T012</td>
			<td>Crear servicio para obtener listado de clínicas</td>
			<td>Desarrollar la lógica de negocio que maneja la obtención de clínicas desde la base de datos</td>
			<td>4</td>
			<td>Leonardo</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T013</td>
			<td>Crear endpoint para obtener listado de clínicas</td>
			<td>Implementar un endpoint que devuelva un listado de clínicas</td>
			<td>2</td>
			<td>Leonardo</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">US062</td>
			<td rowspan="2">Obtener listado de dirección de las Clínicas a través de un RESTful API</td>
			<td>T014</td>
			<td>Crear servicio para obtener listado de dirección de clínicas</td>
			<td>Desarrollar la lógica de negocio que maneja la obtención de direcciones de clínicas desde la base de datos</td>
			<td>
4</td>
			<td>Rut</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T015</td>
			<td>Crear endpoint para obtener listado de dirección de clínicas</td>
			<td>Implementar un endpoint que devuelva un listado de direcciones de clínicas</td>
			<td>2</td>
			<td>Rut</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">US066</td>
			<td rowspan="2">Obtener listado de horarios disponibles para un Veterinario a través de un RESTful API</td>
			<td>T016</td>
			<td>Crear servicio para obtener listado de horarios disponibles para un veterinario</td>
			<td>Desarrollar la lógica de negocio para obtener el listado de horarios disponibles desde la base de datos</td>
			<td>4</td>
			<td>Saul</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T017</td>
			<td>Crear endpoint para obtener listado de horarios disponibles para un veterinario</td>
			<td>Implementar un endpoint que devuelva un listado de horarios disponibles para un veterinario</td>
			<td>2</td>
			<td>Saul</td>
			<td>Done</td>
		</tr>
	</tbody>
</table>

##### 6.2.2.3.Development Evidence for Sprint Review.
Durante este Sprint se realizaron los despliegues del Edge y el Main Backend. Para este despliegue, se creó una Base de Datos en Azure y se agregó la dirección en el application.propertties.  
<table>
	<tbody>
		<tr>
			<td>Repository

</td>
			<td>Branch

</td>
			<td>Commit Id

</td>
			<td>Commit Message

</td>
			<td>Commit Message Body

</td>
			<td>Commited on (Date)

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Backend

</td>
			<td>develop</td>
			<td>032c81fd4cbf4868a6aea57e9fc2e989f58f403f
</td>
			<td>Update application.properties

</td>
			<td>-</td>
			<td>06-06-2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Edge-Backend

</td>
			<td>develop</td>
			<td>346c17f4900590fb16009de17d8cd94fe6bff99c

</td>
			<td>add az database configuration

</td>
			<td>-</td>
			<td>05-06-2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/LAndingPage

</td>
			<td>develop</td>
			<td>559d2031e6a1de5baecf9b575255fe2b06eddbb2</td>
			<td>Update README.md

</td>
			<td>-</td>
			<td>03-05-2024

</td>
		</tr>
	</tbody>
</table>

##### 6.2.2.4.Testing Suite Evidence for Sprint Review.
<table>
	<tbody>
		<tr>
			<td>Repository

</td>
			<td>Branch</td>
			<td>Commit </td>
			<td>Commit Message

</td>
			<td>Commit Message Body

</td>
			<td>Commited on (Date)

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>615b1b7802a6c9515efbcd6e6e8c370622bd51a3</td>
			<td>Create US48 feature

</td>
			<td>-</td>
			<td>08/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>92d092b446ff90595c12a85a0e297d9371884fc7

</td>
			<td>Create US49 feature

</td>
			<td>-</td>
			<td>08/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>8538e8f8d79727bc2c01eb25d96fda8a277859df</td>
			<td>Create US50 feature

</td>
			<td>-</td>
			<td>08/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>7e4a7f0cb405ec81b60dd4ee6bf1232aa2595809</td>
			<td>Create US60 feature

</td>
			<td>-</td>
			<td>08/06/2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>b05d4a8339b213d9779ca2935a112cc3794136d7</td>
			<td>Create US61 feature

</td>
			<td>-</td>
			<td>08/06/2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>f3bcb05f801a13d93071ec69224475a76a1ec6aa</td>
			<td>Create US62 feature

</td>
			<td>-</td>
			<td>08/06/2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>93b3fcd3b271892a2874e892a54ef86a9d6cff2c</td>
			<td>Create US66 feature

</td>
			<td>-</td>
			<td>08/06/2024

</td>
		</tr>
	</tbody>
</table>

##### 6.2.2.5.Execution Evidence for Sprint Review.
Durante este sprint, se completaron los entregables:  
- Aplicación Web
- Landing Page
- Primera versión de los API Services que interactúan con la solución PetHealth (Main Backend y Edge Backend)
- Primera versión de la aplicación Móvil 
- Primera versión del dispositivo IoT.

###### Aplicación Web:
Vista pets y metrics  
[![Imagen1.png](https://i.postimg.cc/CxBWs9qQ/Imagen1.png)](https://postimg.cc/18SC9CMG)  
[![Imagen2.png](https://i.postimg.cc/qvPWbQcM/Imagen2.png)](https://postimg.cc/cvcD6R5V)  
[![Imagen3.png](https://i.postimg.cc/25nMPvTd/Imagen3.png)](https://postimg.cc/PLrSDCgN)  
###### Primera versión de los API Services que interactúan con la solución PetHealth (Main Backend y Edge Backend): 
[![Imagen4.png](https://i.postimg.cc/DZFHFZY9/Imagen4.png)](https://postimg.cc/DWjBP2h6)  

- Main backend:  
https://backend-production-6ed3.up.railway.app/api/pethealth/v1/pet-owners/1/pets:  
[![Imagen5.png](https://i.postimg.cc/cJdBLn0B/Imagen5.png)](https://postimg.cc/0zHwtr6z)  
- Edge Backend:  
https://hearty-serenity-production.up.railway.app/api/v1/sensor_data  
[![Imagen6.png](https://i.postimg.cc/bvLHDwvc/Imagen6.png)](https://postimg.cc/Ny9rZYTp)  

##### 6.2.2.6.Services Documentation Evidence for Sprint Review.

Durante este sprint, se desplegó la primera versión del Main  backend con los npoints:  
https://backend-production-6ed3.up.railway.app/swagger-ui/index.html#  

[![Imagen7.png](https://i.postimg.cc/xCcx9z3F/Imagen7.png)](https://postimg.cc/N9v74LV1)  
[![Imagen8.png](https://i.postimg.cc/hj6CvtC4/Imagen8.png)](https://postimg.cc/ft77gDn1)  
[![Imagen9.png](https://i.postimg.cc/fT42hktB/Imagen9.png)](https://postimg.cc/LhTBt9V1)  
[![Imagen10.png](https://i.postimg.cc/wThWxHDH/Imagen10.png)](https://postimg.cc/rKwGgBhY)  
[![Imagen11.png](https://i.postimg.cc/3x1npBLc/Imagen11.png)](https://postimg.cc/v41rwWwr)  
[![Imagen12.png](https://i.postimg.cc/zBbjs1qs/Imagen12.png)](https://postimg.cc/qhryKShw)  

##### 6.2.2.7.Software Deployment Evidence for Sprint Review.
Durante este Sprint se realizaron los despliegues del Edge y el Main Backend. Para estos despliegues, se crearon 2 Bases de Datos en un servidor en Microsoft Azure.  
[![Imagen13.png](https://i.postimg.cc/Qt2bsntH/Imagen13.png)](https://postimg.cc/FdxcVp04)  
[![Imagen14.png](https://i.postimg.cc/CM87JYPD/Imagen14.png)](https://postimg.cc/Wt201RPb)  
A continuación, se agregaron las direcciones en los archivos application.propertties de ambos proyectos.  
pethealthmaindb (Main Database)  
[![Imagen15.png](https://i.postimg.cc/sD9cdmRg/Imagen15.png)](https://postimg.cc/w7MJDhvC)  
pethealthdb (Edge Database)  
[![Imagen16.png](https://i.postimg.cc/sgjJVWV9/Imagen16.png)](https://postimg.cc/mtn9jt1t)  
Finalmente se desplegaron ambos desde los repositorios en Github con la herramienta Railway.  
[![Imagen17.png](https://i.postimg.cc/jSM4Cj2V/Imagen17.png)](https://postimg.cc/gx6ZTm34)  
https://backend-production-6ed3.up.railway.app/  
https://hearty-serenity-production.up.railway.app/  

##### 6.2.2.8.Team Collaboration Insights during Sprint.
En este sprint, el equipo dividió las tareas teniendo en cuenta los features (account-management, appointment-function, collar-function y pet-owner).  
###### Web Frontend:  
[![Imagen18.png](https://i.postimg.cc/ZRd8fFcZ/Imagen18.png)](https://postimg.cc/47XHycqF)  
[![Imagen19.png](https://i.postimg.cc/6qxdF2jZ/Imagen19.png)](https://postimg.cc/3494vRHr)  
###### IoT Application:
[![Imagen20.png](https://i.postimg.cc/qvD24ZD4/Imagen20.png)](https://postimg.cc/0zmzCZqB)  
[![Imagen21.png](https://i.postimg.cc/6QDRG4NP/Imagen21.png)](https://postimg.cc/v1tDJBT7)  
###### Main Backend: 
[![Imagen22.png](https://i.postimg.cc/nr1Q5dQ8/Imagen22.png)](https://postimg.cc/y3kd3yPn)  
[![Imagen23.png](https://i.postimg.cc/ZYP3Cqsf/Imagen23.png)](https://postimg.cc/qgRgFpTn)  
###### Edge-Backend:
[![Imagen24.png](https://i.postimg.cc/zvpVpV98/Imagen24.png)](https://postimg.cc/hQzDtPD5)  
[![Imagen25.png](https://i.postimg.cc/qMbN36sG/Imagen25.png)](https://postimg.cc/ZCNYkRD9)  

### 6.2.3. Sprint 3
#### 6.2.3.1 Sprint Planning 3

<table>
    <tbody>
        <tr>
            <td>Sprint#</td>
            <td>Sprint 3</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2024-06-20</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>7:00 pm</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>Reunión virtual en la plataforma Discord</td>
        </tr>
        <tr>
            <td>Prepared By</td>
            <td>Rut Jaramillo</td>
        </tr>
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Ruth Jaramillo, Leonardo Aquino, Saul Mendoza, Fredy Almeida, Emerson Quispe</td>
        </tr>
        <tr>
            <td>Sprint n-2 Review Summary</td>
            <td>Se realizaron correcciones en el backend y frontend, así como la realización del dispositivo IoT</td>
        </tr>
        <tr>
            <td>Sprint n-2 Retrospective Summary</td>
            <td>Faltó un poco más de comunicación, pero se mejoró con respecto al anterior sprint</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td>Sprint n Goal</td>
            <td>Tener desplegado el Edge backend y el dispositivo IoT. Terminar de implementar el frontend para el móvil.</td>
        </tr>
        <tr>
            <td>Sprint n Velocity</td>
            <td>40</td>
        </tr>
        <tr>
            <td>Sum of story Points</td>
            <td>45</td>
        </tr>
    </tbody>
</table>

#### 6.2.3.2 Sprint Backlog 3

<table>
    <tbody>
        <tr>
            <td>Sprint #</td>
            <td colspan="7">Sprint 3</td>
        </tr>
        <tr>
            <td colspan="2">User Story</td>
            <td colspan="6">Work-item / Task</td>
        </tr>
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Descripción</td>
            <td>Estimation (Hours)</td>
            <td>Assigned To</td>
            <td>Status (To-do/ In Process/ To-Review/ Done)</td>
        </tr>
        <tr>
            <td rowspan="3">US051</td>
            <td rowspan="3">Obtener métrica de Latidos de mascota actualizada a través de un RESTful API</td>
            <td>T001</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Fredy</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T002</td>
            <td>Crear servicio para obtener métricas</td>
            <td>Desarrollar la lógica de negocio para obtener métricas de latidos de la base de datos.</td>
            <td>3</td>
            <td>Fredy</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T003</td>
            <td>Crear endpoint para obtener métricas</td>
            <td>Implementar un endpoint que devuelva métricas de latidos actualizadas de una mascota.</td>
            <td>2</td>
            <td>Fredy</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US054</td>
            <td rowspan="3">Obtener Latidos de mascota en tiempo real a través de un RESTful API</td>
            <td>T004</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Fredy</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T005</td>
            <td>Crear servicio para obtener latidos</td>
            <td>Desarrollar la lógica de negocio para obtener latidos en tiempo real de la base de datos.</td>
            <td>3</td>
            <td>Fredy</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T006</td>
            <td>Crear endpoint para obtener latidos</td>
            <td>Implementar un endpoint que devuelva los latidos en tiempo real de una mascota.</td>
            <td>2</td>
            <td>Fredy</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US056</td>
            <td rowspan="3">Obtener Temperatura de mascota en tiempo real a través de un RESTful API</td>
            <td>T007</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Emerson</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T008</td>
            <td>Crear servicio para obtener temperatura</td>
            <td>Desarrollar la lógica de negocio para obtener temperatura en tiempo real de la base de datos.</td>
            <td>3</td>
            <td>Emerson</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T009</td>
            <td>Crear endpoint para obtener temperatura</td>
            <td>Implementar un endpoint que devuelva la temperatura en tiempo real de una mascota.</td>
            <td>2</td>
            <td>Emerson</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US058</td>
            <td rowspan="3">Obtener Hidratación de mascota en tiempo real a través de un RESTful API</td>
            <td>T010</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Emerson</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T011</td>
            <td>Crear servicio para obtener hidratación</td>
            <td>Desarrollar la lógica de negocio para obtener hidratación en tiempo real de la base de datos.</td>
            <td>3</td>
            <td>Emerson</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T012</td>
            <td>Crear endpoint para obtener hidratación</td>
            <td>Implementar un endpoint que devuelva la hidratación en tiempo real de una mascota.</td>
            <td>2</td>
            <td>Emerson</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US063</td>
            <td rowspan="3">Obtener datos de una Clínica a través de un RESTful API</td>
            <td>T013</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Rut</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T014</td>
            <td>Crear servicio para obtener datos</td>
            <td>Desarrollar la lógica de negocio para obtener datos de una clínica de la base de datos.</td>
            <td>3</td>
            <td>Rut</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T015</td>
            <td>Crear endpoint para obtener datos</td>
            <td>Implementar un endpoint que devuelva los datos de una clínica.</td>
            <td>2</td>
            <td>Rut</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US064</td>
            <td rowspan="3">Obtener listado de Veterinarios por una Clínica a través de un RESTful API</td>
            <td>T016</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Rut</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T017</td>
            <td>Crear servicio para obtener veterinarios</td>
            <td>Desarrollar la lógica de negocio para obtener veterinarios de una clínica.</td>
            <td>3</td>
            <td>Rut</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T018</td>
            <td>Crear endpoint para obtener veterinarios</td>
            <td>Implementar un endpoint que devuelva el listado de veterinarios de una clínica.</td>
            <td>2</td>
            <td>Rut</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US070</td>
            <td rowspan="3">Agregar nuevo veterinario a través de un RESTful API</td>
            <td>T019</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Leonardo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T020</td>
            <td>Crear servicio para agregar veterinario</td>
            <td>Desarrollar la lógica de negocio para agregar un nuevo veterinario a la base de datos.</td>
            <td>3</td>
            <td>Leonardo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T021</td>
            <td>Crear endpoint para agregar veterinario</td>
            <td>Implementar un endpoint que permita agregar un nuevo veterinario.</td>
            <td>2</td>
            <td>Leonardo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US071</td>
            <td rowspan="3">Agregar nuevo dueño de mascota a través de un RESTful API</td>
            <td>T022</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Leonardo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T023</td>
            <td>Crear servicio para agregar dueño</td>
            <td>Desarrollar la lógica de negocio para agregar un nuevo dueño de mascota a la base de datos.</td>
            <td>3</td>
            <td>Leonardo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T024</td>
            <td>Crear endpoint para agregar dueño</td>
            <td>Implementar un endpoint que permita agregar un nuevo dueño de mascota.</td>
            <td>2</td>
            <td>Leonardo</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US072</td>
            <td rowspan="3">Sincronizar collar y agregar nueva Mascota a través de un RESTful API</td>
            <td>T025</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Saúl</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T026</td>
            <td>Crear servicio para sincronizar collar</td>
            <td>Desarrollar la lógica de negocio para sincronizar el collar y agregar una nueva mascota a la base de datos.</td>
            <td>3</td>
            <td>Saúl</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T027</td>
            <td>Crear endpoint para sincronizar collar</td>
            <td>Implementar un endpoint que permita sincronizar el collar y agregar una nueva mascota.</td>
            <td>2</td>
            <td>Saúl</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="3">US073</td>
            <td rowspan="3">Editar perfil de dueño de mascota a través de un RESTful API</td>
            <td>T028</td>
            <td>Crear la entidad y queries</td>
            <td>Identificar los atributos necesarios y definir los commands y queries.</td>
            <td>3</td>
            <td>Saúl</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T029</td>
            <td>Crear servicio para editar perfil</td>
            <td>Desarrollar la lógica de negocio para editar el perfil de un dueño de mascota.</td>
            <td>3</td>
            <td>Saúl</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>T030</td>
            <td>Crear endpoint para editar perfil</td>
            <td>Implementar un endpoint que permita editar el perfil de un dueño de mascota.</td>
            <td>2</td>
            <td>Saúl</td>
            <td>Done</td>
        </tr>
    </tbody>
</table>


#### 6.2.3.3 Development Evidence for Sprint Review
Durante este Sprint se realizaron las mejoras y los despliegues de la aplicación web, aplicación móvil y el dispositivo IoT.

<table>
	<tbody>
		<tr>
			<td>Repository

</td>
			<td>Branch

</td>
			<td>Commit Id

</td>
			<td>Commit Message

</td>
			<td>Commit Message Body

</td>
			<td>Commited on (Date)

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Frontend

</td>
			<td>master</td>
			<td>1640e3ac98b7ce85b2370303a5cc047cfcdbb281
</td>
			<td>add routes clinics and veterinarians

</td>
			<td>-</td>
			<td>26-06-2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Backend

</td>
			<td>master</td>
			<td>11b92ae14f28c113c3563e8419a179a57a2d6501
</td>
			<td>Update WebConfig.java

</td>
			<td>-</td>
			<td>21-06-2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Mobile

</td>
			<td>master</td>
			<td>d2b3b43319acfab9cf1e89a24ffd4767e2f0ff1e
</td>
			<td>Add config to deploy

</td>
			<td>-</td>
			<td>25-06-2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/IoT-Application

</td>
			<td>main</td>
			<td>2b7966b9734707241cf097a49ea550ce3eebe8b8
</td>
			<td>Add Devices, diagram.json and sketch.ino

</td>
			<td>-</td>
			<td>19-06-2024

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Edge-Backend

</td>
			<td>develop</td>
			<td>99198f5cf62c9ebfe1988733db0783cedf9534cb
</td>
			<td>Merge pull request #1 from XForce-IOt/develop

</td>
			<td>-</td>
			<td>05-05-2024

</td>
	</tbody>
</table>

#### 6.2.3.4 Testing Suite Evidence for Sprint Review

<table>
	<tbody>
		<tr>
			<td>Repository

</td>
			<td>Branch</td>
			<td>Commit </td>
			<td>Commit Message

</td>
			<td>Commit Message Body

</td>
			<td>Commited on (Date)

</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>552ff20729c7cb5222225b0c34978a1dcdd375eb</td>
			<td>Create US51 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>ca246d0ded7930369655a5a29851834f94f16be3</td>
			<td>Create US54 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>173c6971881ac8d6968a4d25d27f8623ed3d4e7d</td>
			<td>Create US56 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>61cc16949f7876db6ce4e99c15db92f9b0435ede</td>
			<td>Create US58 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>becc5656db115f45893f21709b2589c268264121</td>
			<td>Create US63 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>b6642b6af7a6477e5bda7bfdedf7dfada80df3d4</td>
			<td>Create US64 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>d4e2a27f7c3a0e2151dd5015f1914a7030b20a04</td>
			<td>Create US70 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>8a9c7d26f2842fc0115ae6dce25f9857fbf8c31e</td>
			<td>Create US71 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>9392d317f1bf4c2c902de7a3d3d14fe35af0909f</td>
			<td>Create US72 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
		<tr>
			<td>XForce-IOt/Gherkin

</td>
			<td>main</td>
			<td>123addb66d38bb4a69ffcd2806f534f0aa1a0c0f</td>
			<td>Create US73 feature

</td>
			<td>-</td>
			<td>24/06/2024
</td>
		</tr>
	</tbody>
</table>

#### 6.2.3.5 Execution Evidence for Sprint Review
Durante este sprint, se completaron los entregables:  

- Aplicación Web (Correcciones en vistas)
- Landing Page (Links de videos about the team y about the product)
- Correcciones sobre los API Services que interactúan con la solución PetHealth (Main Backend y Edge Backend)
- Aplicación Móvil
- Dispositivo IoT.

##### Aplicación web:
Vista Login  
[![Captura-de-pantalla-2024-06-27-021241.png](https://i.postimg.cc/26XHFKpC/Captura-de-pantalla-2024-06-27-021241.png)](https://postimg.cc/KkBrmQvW)  

Vista Pets y Métrics  
[![Captura-de-pantalla-2024-06-27-021415.png](https://i.postimg.cc/yxgLfyBc/Captura-de-pantalla-2024-06-27-021415.png)](https://postimg.cc/n9xKr7Xh)  

Vista Appointments  
[![Captura-de-pantalla-2024-06-27-021510.png](https://i.postimg.cc/bYZ8cXwH/Captura-de-pantalla-2024-06-27-021510.png)](https://postimg.cc/6TxFnmRy)  

Vista Create Appointment  
[![Captura-de-pantalla-2024-06-27-021620.png](https://i.postimg.cc/rsBQ7RFb/Captura-de-pantalla-2024-06-27-021620.png)](https://postimg.cc/V0FqC6tB)

#### Dispositivo IoT:  
[![Imagen3.png](https://i.postimg.cc/25nMPvTd/Imagen3.png)](https://postimg.cc/PLrSDCgN)  

### API Services:
Main y Side Backend  
[![Captura-de-pantalla-2024-06-27-022314.png](https://i.postimg.cc/k4n4FTQY/Captura-de-pantalla-2024-06-27-022314.png)](https://postimg.cc/XZz4ncD9)  
Appointments by user: http://backend-production-6ed3.up.railway.app/api/pet-health/v1/clinics/1/veterinarians/1/pet-owners/1/appointments    
[![Captura-de-pantalla-2024-06-27-022430.png](https://i.postimg.cc/V6DN7X4f/Captura-de-pantalla-2024-06-27-022430.png)](https://postimg.cc/XGB3qGTm)  

### Mobile application
[![IMG-20240627-WA0004.jpg](https://i.postimg.cc/rwk3n3HJ/IMG-20240627-WA0004.jpg)](https://postimg.cc/LnxxhC2Y)
[![IMG-20240627-WA0005.jpg](https://i.postimg.cc/QdJPRSGr/IMG-20240627-WA0005.jpg)](https://postimg.cc/jDCZfHS8)
[![IMG-20240627-WA0003.jpg](https://i.postimg.cc/CKMtYDSn/IMG-20240627-WA0003.jpg)](https://postimg.cc/BjyNBj8J)
[![IMG-20240627-WA0002.jpg](https://i.postimg.cc/wvZbhGJD/IMG-20240627-WA0002.jpg)](https://postimg.cc/BL5g3Nmv)

#### 6.2.3.6 Services Documentation Evidence for Sprint Review
En el presente sprint, se realizaron correcciones sobre las relaciones entre appointments y pets, además, se corrigió el método post de appointments. Finalmente, se presenta la versión final del Main Backend con los npoints:  
- Veterinarians
- Appointments
- Sensor Data
- Clinics
- Pet-owner-controller
https://backend-production-6ed3.up.railway.app/swagger-ui/index.html#/  

[![Captura-de-pantalla-2024-06-27-023652.png](https://i.postimg.cc/s2KB8FgC/Captura-de-pantalla-2024-06-27-023652.png)](https://postimg.cc/7CGYGWzK)  
[![Captura-de-pantalla-2024-06-27-023725.png](https://i.postimg.cc/fLL3QHVt/Captura-de-pantalla-2024-06-27-023725.png)](https://postimg.cc/QB2NpJkh)  
[![Captura-de-pantalla-2024-06-27-023744.png](https://i.postimg.cc/MHfvvvbz/Captura-de-pantalla-2024-06-27-023744.png)](https://postimg.cc/Wqj2ypHy)  
[![Captura-de-pantalla-2024-06-27-023807.png](https://i.postimg.cc/G909YdqG/Captura-de-pantalla-2024-06-27-023807.png)](https://postimg.cc/QKbXZGLd)  
[![Captura-de-pantalla-2024-06-27-023823.png](https://i.postimg.cc/hP9Vr5Tc/Captura-de-pantalla-2024-06-27-023823.png)](https://postimg.cc/1f3gRMvj)
#### 6.2.3.7 Software Deployment Evidence for Sprint Review
Durante este Sprint, se utilizó Firebase para generar un ejecutable descargable de la aplicación móvil usando el APK generado por Android Studio.  
[![Captura-de-pantalla-2024-06-27-025803.png](https://i.postimg.cc/zfJmB6SB/Captura-de-pantalla-2024-06-27-025803.png)](https://postimg.cc/XrD112PS)  
[![Captura-de-pantalla-2024-06-27-025930.png](https://i.postimg.cc/HxhF6xGc/Captura-de-pantalla-2024-06-27-025930.png)](https://postimg.cc/N9RNMQjB)  
Enlace de invitación: https://appdistribution.firebase.dev/i/8db9855f758383bf  
[![Captura-de-pantalla-2024-06-27-030234.png](https://i.postimg.cc/66GBDsHJ/Captura-de-pantalla-2024-06-27-030234.png)](https://postimg.cc/CdSyq2Tm)  
#### 6.2.3.8 Team Collaboration Insights during Sprint

En este sprint, el equipo dividió las tareas para finalizar con la aplicación PetHealth

###### Web Frontend:

Las siguientes visualizaciones resaltan las colaboraciones de nuestro equipo en el desarrollo de la interfaz web para nuestro proyecto. Las contribuciones se desglosan por miembros individuales del equipo, mostrando sus respectivas adiciones y eliminaciones, lo que refleja la naturaleza colaborativa de nuestro proceso de desarrollo. 

[![front1.png](https://i.postimg.cc/MGyHRvCw/front1.png)](https://postimg.cc/5H2fWN9K)

[![front2.png](https://i.postimg.cc/hGggkMYF/front2.png)](https://postimg.cc/TKkZmjGQ)

###### Web Backend:

Las siguientes visualizaciones resaltan las colaboraciones de nuestro equipo en el desarrollo backend para nuestra aplicación web.

[![back1.png](https://i.postimg.cc/wM9wHRpj/back1.png)](https://postimg.cc/Q9nQJtC2)

[![back2.png](https://i.postimg.cc/7YsK8LQq/back2.png)](https://postimg.cc/tY63F9jc)

###### Mobile:

Las siguientes visualizaciones resaltan las colaboraciones de nuestro equipo en el desarrollo móvil para nuestra aplicación web.

[![mobile1.png](https://i.postimg.cc/0QPYJgHt/mobile1.png)](https://postimg.cc/LqQYrWSf)

[![mobile2.png](https://i.postimg.cc/J4vj5H2H/mobile2.png)](https://postimg.cc/565Hxy1f)

###### IoT Application:

Las siguientes visualizaciones resaltan las colaboraciones de nuestro equipo en el desarrollo del dispositivo IoT collar inteligente para nuestro proyecto.

[![iot1.png](https://i.postimg.cc/nhq9KRmN/iot1.png)](https://postimg.cc/4YN3s1B1)

[![iot2.png](https://i.postimg.cc/2jJ1sRFP/iot2.png)](https://postimg.cc/s1YfWLLc)

###### Edge Backend:

Las siguientes visualizaciones resaltan las colaboraciones de nuestro equipo en el desarrollo del edge backend para recopilar información del dispositivo IoT.

[![edge.png](https://i.postimg.cc/FRzK6Dfr/edge.png)](https://postimg.cc/WFRjFm6C)

## 6.3. Validation Interviews.
### 6.3.1. Diseño de Entrevistas.
1. Introducción:
    - Presentación del entrevistador y del objetivo de la entrevista
    - Explicación breve del proyecto y del propósito del collar IoT.
2. Interacción con la aplicación:
    - El entrevistado interactúa libremente con la aplicación.
3. Preguntas:
    - ¿Qué te pareció la interfaz de la aplicación la primera vez que la usaste?
    - ¿Encontraste fácil de entender las funciones principales de la aplicación?
    - ¿Desde tu punto de vista, la aplicación responde de manera rápida y eficiente a tus acciones?
    - ¿Consideras útiles los datos y análisis proporcionados por la aplicación?
    - ¿Hay alguna funcionalidad que crees que falta o que te gustaría mejorar?
    - ¿Tuviste alguna dificultad al navegar por la aplicación?
    - ¿Hay algún aspecto de la aplicación que encuentres confuso o frustrante?
    - ¿Notaste errores o problemas mientras interactúas con la aplicación?
    - ¿La aplicación cumple con tus expectativas o necesidades?
    - ¿Recomendarías esta aplicación a otros dueños de mascotas? ¿Por qué?
4. Feedback General y Conclusión:
    - Comentarios adicionales y conclusión de la entrevista.
    
### 6.3.2. Registro de Entrevistas.
[![e1.png](https://i.postimg.cc/vTQXfBcM/e1.png)](https://postimg.cc/S2vWpm6t)
https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c163_upc_edu_pe/EXVkU-qZnSBLjcNFT0ExGPUBj07YoZWpcAv_9F6fQUYl2w?e=rvcacs

### Segmento Objetivo: Dueño de mascota

### Entrevista 1:

**Entrevistador:** Saúl Enrique Mendoza Barco 

**Entrevistado:** Madelein Rodriguez

**Edad:** 23 años

**Distrito:** Callao

**Min inicio:** 0:04

**Min final:** 7:32

**Resumen:** Madelein es una dueña de mascota de 23 años. Viven en el Callao y su dispositivo más usado es su celular con sistema operativo Android, el navegador que más utiliza en Chrome. Las redes sociales que más usa son Whatsapp e Instagram. Tiene una sola mascota, un perro. Lleva a su mascota todos los meses para un chequeo o un baño, su mascota cuenta con una dieta balanceada y posee un registro en una agenda de las vacunas y medicamentos que haya tomado su mascota, cuando ella no se encuentra en casa, deja a su mascota con su madre. Madelein nos comenta que la aplicación le pareció muy intuitiva y útil, en especial para poder contactar con su veterinario de confianza, también nos dice que le es de mucha ayuda tener los datos vitales de su mascota pues se preocupa mucho por la salud y bienestar de esta.  

### Entrevista 2:

**Entrevistador:** Jesica Rut Jaramillo Almora 

**Entrevistado:** Beatriz Almora

**Edad:** 56 años

**Distrito:** Independencia

**Min inicio:** 7:32

**Min final:** 21:30

**Resumen:** Beatriz es una dueña de mascota de 56 años. Vive en independencia y su dispositivo más usado en su celular con SO Android, además el navegador que más usa es Chrome.  
Comenta que la aplicación le parece "algo complicada de entender al principio, pero se puede aprender". Además cree que la funcionalidad de reserva es muy útil para llevar el historial de citas médicas de su mascota. Además está dispuesta a recomendas la app web con sus conocidos por la tranquilidad que le brindan los datos críticos enviados en tiempo real mediante el collar.

### Entrevista 3:

**Entrevistador:** Emerson Quispe

**Entrevistado:**  Giovani Villegas

**Edad:**  21 años

**Distrito:**  Callao

**Min inicio:** 21:30

**Min final:** 27:32  

**Resumen:** Giovani comenta que la aplicación le va ser muy util, no solo a el, sino a la mayoría de personas que tienen mascotas, debido a que le parece muy util la opción de geolocalización, ya que, así podrá saber en donde se encuentra su mascota a cualquier hora. Respecto a la interfaz de la aplicación web, nos comenta que la aplicación es fácil de entender, debido a que le parece sencillo y fácil de manejar. Tambien dice que la aplicación le parece rápido, no ha observado demoras, pero si comenta que se distorsiona un poco hacia la derecha cuando se recarga la pagina. El entrevistado considera que los datos mostrados son precisos, ya que al ser una aplicación para los mismos dueños no es necesario ser tan específicos. Por ultimo, opina que no ha encontrado algún fastidio o frustración al navegar por la aplicación y que si recomendaría el uso de la aplicación a sus amigos, ya que les ayudaría a mantener una mejor calidad de vida a sus mascotas.

### 6.3.3. Evaluaciones según heurísticas.
**SITE o APP A EVALUAR:** PetHealth  
**TAREAS A EVALUAR**  
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:  
1. Registro de un usuario nuevo
2. Ingreso de un usuario existente
3. Evaluación de métricas de salud de una mascota
4. Agendar nueva cita
5. Reporte de citas agendadas
6. Filtros de Citas y CLínicas
7. Vista de Clínicas en el mapa
8. Edición de perfil de usuario

No están incluidas en esta versión de la evaluación las siguientes tareas:  
1. Reporte detallado de mascota
2. Agregar mascota con dispositivo IoT  

**ESCALA DE SEVERIDAD:**  
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad  

| Nivel | Descripción                                                                                                                                                                         |
|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco                                                                                           |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de                                                                                                |
|   3   | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es                                                                                              |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido que sea corregido antes del lanzamiento. |

**TABLA RESUMEN:**  
| # | Problema | Escala de severidad | Heurística/Principio violada(o) |
|---|----------|---------------------|---------------------------------|
| 1 |La distribución es complicada de entender para un usuario nuevo|      3         | Usability: Libertad y control del usuario |
| 2 |El log in y sign in demoran en responder| 2 |Usability: Libertad y control del usuario |

**DESCRIPCIÓN DE PROBLEMAS:**  
**PROBLEMA #1:** La distribución es complicada de entender para un usuario nuevo  
- Severidad: 3
- Heurística violada: Usabilidad - Libertad y control del usuario
- Problema:
El formato dashboard empleado para mostrar los datos al usuario no es muy común, lo que dificulta que los usuarios se desplacen por el con facilidad la primera vez que ingresan a la app.  
[![Captura-de-pantalla-2024-06-27-021415.png](https://i.postimg.cc/yxgLfyBc/Captura-de-pantalla-2024-06-27-021415.png)](https://postimg.cc/n9xKr7Xh)  
Recomendación:
Agregar una sección tutorial donde se muestre un video navegando por las secciones y funcionalidades de la app durante los primeros 7 días de un usuario en la applicación.
**PROBLEMA #2:** El log in y sign in demoran en responder  
- Severidad: 2
- Heurística violada: Usabilidad - Libertad y control del usuario
- Problema:
Cuando el usuario quiere Registrarse o ingresar con una cuenta existente, los inputs tienen un delay al escribir los datos.  
[![Captura-de-pantalla-2024-06-27-021241.png](https://i.postimg.cc/26XHFKpC/Captura-de-pantalla-2024-06-27-021241.png)](https://postimg.cc/KkBrmQvW)  
Recomendación:
Reducir el tiempo de respuesta en la digitación de los inputs.


## 6.4. Video About-the-Product.
https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c163_upc_edu_pe/EQlFXwSR5CBBoly7CHE0BIIBTuN9TOgKQBlaNWMG4tul7w  
# Conclusiones
## Conclusiones y recomendaciones
- Concluimos que las entrevistas y su respectivo análisis son un recurso de gran importancia ya que aportan perspectivas únicas que ayudarán a la Startup a mejorar la calidad y utilidad del producto final.
- Con la implementación de c4 model nos ayudará para visualizar y describir nuestra arquitectura de sistemas de software.
- Con la implementación de los diagramas de base de datos, se visualizará unas posibles conexiones de lo que debería ser la base de datos para el proyecto.
- Implementamos las aplicaciones web, móvil y iot, como también se implementó el main backend y el edge backend, para la web se usó angular para su desarrollo, móvil se usó el flutter y para iot se simuló en wokwi.
- Se ajustaron las configuraciones en un proyecto de Wokwi para simular el comportamiento de los sensores como el DHT22, el sensor ultrasónico y el sensor de Pulso. Esto incluyó cambios para variar las lecturas de los sensores y enviar datos a un servidor
- Resolvimos varios errores de compilación y ejecución, tanto en el contexto de Spring Boot como en Arduino, mejorando la estabilidad y funcionalidad de los sistemas.
## Video About-the-Team 
[![Captura-de-pantalla-2024-06-27-100126.png](https://i.postimg.cc/hvq5j4YN/Captura-de-pantalla-2024-06-27-100126.png)](https://postimg.cc/BLMg734C)  
https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c163_upc_edu_pe/EZB1fyfQRTdLq_sj28gg6TIBHaIJqtkoyFbxe4S2_DDKpA

