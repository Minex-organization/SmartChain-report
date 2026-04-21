# CAPÍTULO V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

**-Project Management:**
1. Herramienta: Trello
Propósito: Gestión de tareas, planificación de sprints y seguimiento del progreso del equipo mediante tableros Kanban. 

**-Requirements Management:**
1. Herramienta: UXPressia
Propósito: Creación de artefactos de needfinding como User Personas, User Journey Maps y Empathy Maps para comprender y analizar las necesidades del usuario.
2. Herramienta: Miro
Propósito: Desarrollo de Event Storming (Big Picture y Process Level) para el modelado de procesos y alcance del sistema.

**-Product UX/UI Design:**
1. Herramienta: UXPressia
Propósito: Creación de artefactos de needfinding como User Personas, User Journey Maps y Empathy Maps para comprender las necesidades del usuario.
2. Herramienta: Miro
Propósito: Desarrollo de Event Storming (Big Picture y Process Level) para el modelado de procesos y definición del alcance del sistema.

**-Software Development:**
1. Herramienta: Visual Studio Code
Propósito: Entorno de desarrollo utilizado para la programación del sistema.
2. Herramienta: GitHub
Propósito: Control de versiones y trabajo colaborativo mediante repositorios, commits y ramas. Cada miembro del equipo clonará el repositorio para desarrollar de manera distribuida sus features.
3. Tecnología Frontend: Angular
Lenguaje: TypeScript
Propósito: Desarrollo de la interfaz web interactiva del sistema.
4. Tecnología Backend: Node.js 
Propósito: Desarrollo de la lógica del servidor, manejo de peticiones HTTP y conexión con la base de datos.
5. Base de Datos: SQL Server
Propósito: Almacenamiento y gestión de la información del sistema.

**-Software Deployment:**
1. Herramienta: GitHub Pages
Propósito: Despliegue de la solución de cada producto digital de OpalTrace desde nuestro repositorio de Github.

**-Software Documentation:**
1. Herramienta: Markdown
Propósito: Documentación técnica del proyecto (README y documentación del código).
2. Herramienta: Structurizr
Propósito: Elaboración de diagramas de arquitectura del sistema utilizando el modelo C4 (contexto, contenedores, componentes y código).
### 5.1.2. Source Code Management
Para el control de versiones y la organización ordenada del código de nuestro proyecto OpalTrace, 
el equipo utiliza GitHub como plataforma principal. GitHub nos permite almacenar código fuente 
del Landing Page, Front-End, Back-End llevar un registro histórico de cambios, colaborar de manera estructurada y garantizar trazabilidad durante todo el ciclo de desarrollo. Por ende, creamos la organización Minex-Organization, que incluye los siguientes repositorios:
| Solución  | Nombre del repositorio  |  Enlace  |
|---|---|---|
| Report | OpalTrace-report  | https://github.com/Minex-organization/OpalTrace-report.git  |
| Landing Page  | OpalTrace-landing  |  https://github.com/Minex-organization/OpalTrace-landing.git |
| Front-End  |  OpalTrace-frontend  |   |
| Back-End (Web Services)  | OpalTrace-backend   |   |

Nuestro equipo de trabajo ha aplicado el flujo GitFlow, de acuerdo al artículo "A successful Git branching model” de Vincent Driessen. Nuestra organización cuenta con dos ramas permanentes: master (rama que refleja estados listos para entregas) y develop (rama de integración). Desde la rama develop crearemos ramas feature con la nomenclatura "feature/chapter-#-description", por ejemplo feature/chapter-ii-interviews y en el caso un miembro del equipo desarrolla en totalidad un capítulo "feature-chapter-#-content" en estas nuevas ramas feature cada miembro realiza el trabajo de forma aislada, una vez terminado se fusiona en develop para integrarla en la próxima versión. Una vez que se acerque la fecha de entrega del producto se creama una rama release a partir de develop, donde se realizarán tareas menores como la correción de errores. Finalmente la rama se fusiona en master y en develop para asegurar que los arreglos se mantengan en el futuro.

En síntesis cada nueva funcionalidad se desarrollará en un feature Branch, mientras que las versiones preparadas para lanzamiento se manejarán en release branches con la convención release/vX.Y.Z aplicando Semantic Versioning. Finalmente, las correcciones urgentes se resolverán mediante hotfix branches con el formato hotfix/vX.Y.Z. Todas las confirmaciones seguirán las reglas de Conventional Commits para mantener así un historial claro y estructurado, asegurando un buen camino en el registro de versiones para OpalTrace.

**Repositorio report**
//añadir capturas de pantallas

**Repositorio Landing Page**
//añadir capturas de pantallas

**Repositorio FrontEnd**
//añadir capturas de pantallas

**Repositorio BackEnd**
//añadir capturas de pantallas

### 5.1.3. Source Code Style Guide & Conventions
- HTML5
- CSS
- TYPESCRIPT

### 5.1.4. Software Deployment Configuration
- Creación de la Landing Page:
1. Se crea un repositorio (OpalTrace-landing) desde Minex-organization
//añadir captura de pantalla

2. Agregar a los miembros del equipo
//añadir captura de pantalla

3. Habilitar GitHub Pages en branch master y ruta "/(root)"
//añadir captura de pantalla


- Creación de Front-End App
1. Creación del repositorio (OpalTrace-frontend) dentro de la organización Minex-organization
//añadir captura de pantalla

2. Agregar a los miembros del equipo
//añadir captura de pantalla

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Aspect Leaders and Collaborators

#### 5.2.1.3. Sprint Backlog 1

#### 5.2.1.4. Development Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product