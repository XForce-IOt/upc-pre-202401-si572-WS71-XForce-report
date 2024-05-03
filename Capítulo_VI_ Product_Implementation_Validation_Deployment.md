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
#### 6.2.1.4. Testing Suite Evidence for Sprint Review.
No se realizaron tests durante esta entrega.
#### 6.2.1.5. Execution Evidence for Sprint Review.
#### 6.2.1.6. Services Documentation Evidence for Sprint Review.
#### 6.2.1.7. Software Deployment Evidence for Sprint Review.
#### 6.2.1.8. Team Collaboration Insights during Sprint.
# Avance de Conclusiones, Bibliografía y Anexos.