<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Periodo: 202610</strong><br>
    <strong>Aplicaciones para Dispositivos Móviles</strong><br>
    <strong>NRC: 3687</strong><br>
    <strong>Profesor: David Gerardo Quevedo Velasco </strong><br>
    <br>INFORME TRABAJO FINAL
</p>

<center>

#### Startup: **CcaritaTech**
#### Product: **IoBuild**

### Team Members

| Code       | Member                        |
|------------|-------------------------------|
| U202312629 | Barturen Panez, Iker Gabriel  |
| U20221C218 | Ccarita Cruz, Brayan Roberto  |
| U202215004 | Loechle Arias, Mateo Italo    |
| U202216827 | Ordoñez Ricaldi, Axel Randall |
| U20231A810 | Panta Castro, Fabrizio Martin |


Abril 2026
</center>

<div style="page-break-before: always;"></div>

# Registro de Versiones del Informe

| Version | Fecha      | Autor                        | Descripcion de Modificacion                                                                                                                                                                                                                                                                                                                              |
|---------|------------|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0.1     | 10/04/2026 | Axel Ordoñez Ricaldi         | Se agregó la información base del informe, incluyendo la portada institucional, datos del curso, nombre de la startup, producto IoBuild e integrantes del equipo. También se incorporaron las primeras imágenes de presentación y la descripción general del perfil de la startup, dejando preparada la estructura inicial del documento para el desarrollo de los capítulos posteriores. |
| 0.2     | 12/04/2026 | Axel Ordoñez Ricaldi         | Se realizó el primer avance del Capítulo I, desarrollando los antecedentes, la problemática y el contexto del proyecto. Además, se avanzó con el enfoque Lean UX mediante la elaboración del Problem Statement, el registro de supuestos principales, la formulación de Hypothesis Statements y la construcción inicial del Lean UX Canvas para orientar la propuesta de solución. |
| 0.3     | 14/04/2026 | Brayan Ccarita Cruz          | Se revisó y editó el Capítulo I para mejorar la coherencia de la redacción, la conexión entre la problemática y la solución propuesta, y la presentación del Lean UX Process. Asimismo, se integraron los aportes realizados por los integrantes en esta primera etapa y se organizó el contenido para mantener una estructura clara dentro del informe. |
| 0.4     | 16/04/2026 | Brayan Ccarita Cruz          | Se avanzó en el Capítulo II con el análisis competitivo, identificando soluciones similares, sus características, fortalezas y debilidades. También se incorporó el diseño de entrevistas, el registro de entrevistas realizadas y el análisis inicial de los hallazgos obtenidos. Finalmente, se documentó el progreso del needfinding como base para comprender mejor a los usuarios objetivo. |
| 0.5     | 18/04/2026 | Iker Barturen Panez          | Se continuó el desarrollo del Capítulo II mediante la finalización del needfinding, incluyendo User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping. Además, se trabajó el Big Picture EventStorming para identificar eventos relevantes del dominio y se inició la definición del Ubiquitous Language, permitiendo alinear la terminología del equipo con el contexto del producto. |
| 0.6     | 20/04/2026 | Iker Barturen Panez          | Se complementó el Capítulo II con la identificación de épicas, user stories y technical stories. También se registraron criterios de aceptación, prioridades y dependencias entre historias, además de incorporar el Impact Mapping para relacionar objetivos del negocio, actores principales, impactos esperados y funcionalidades necesarias para IoBuild. |
| 0.7     | 22/04/2026 | Mateo Loechle Arias          | Se integró el avance del Product Backlog en el Capítulo II, organizando las historias de usuario según su prioridad, estimación y relación con los objetivos del producto. Asimismo, se documentó el trabajo realizado en Trello junto con el equipo, dejando evidencia de la planificación colaborativa y de la gestión inicial de tareas para los siguientes sprints. |
| 0.8     | 24/04/2026 | Fabrizio Panta Castro        | Se avanzó en el diseño del producto dentro del Capítulo II, incorporando lineamientos visuales iniciales, arquitectura de información y propuestas UI/UX preliminares. Se documentaron guías de estilo, organización de contenido, primeras ideas de wireframes, mock-ups y flujos de interacción, buscando asegurar consistencia, usabilidad y coherencia con la propuesta de valor de IoBuild. |
| 0.9     | 26/04/2026 | Fabrizio Panta Castro        | Se consolidó el Capítulo II con artefactos de diseño y arquitectura, incluyendo prototipos, diagramas orientados a objetos, diseño de base de datos y elementos de arquitectura de software. Esta actualización permitió conectar los requisitos levantados con una propuesta técnica más estructurada, preparando la base para la implementación y documentación posterior del producto. |
| 1.0     | 28/04/2026 | Mateo Loechle Arias          | Se culminó el Capítulo II mediante la revisión final de requisitos, diseño y arquitectura. También se añadió información sobre la configuración del entorno de desarrollo, la gestión del código fuente y la preparación del despliegue de la solución tecnológica. Finalmente, se integraron las evidencias de avance y se ordenó el contenido para mantener continuidad con los capítulos III y IV. |
| 1.1     | 30/04/2026 | Axel Ordoñez Ricaldi         | Se desarrolló la primera parte del Capítulo III, correspondiente al diseño UX/UI del producto. Se documentaron los Style Guidelines, incluyendo lineamientos generales de diseño, criterios visuales, paleta de colores, tipografías, componentes de interfaz y reglas de consistencia. También se trabajó la Information Architecture, detallando sistemas de organización, etiquetado, búsqueda y navegación para la landing page y la aplicación móvil. |
| 1.2     | 02/05/2026 | Fabrizio Panta Castro        | Se complementó el Capítulo III con los apartados de Landing Page UI Design y Mobile Applications UX/UI Design. Se documentaron los wireframes y mock-ups de la landing page, así como los wireframes, wireflow diagrams, mock-ups, user flow diagrams y prototipos de la aplicación móvil. Además, se revisó la coherencia entre los flujos, pantallas y objetivos funcionales definidos en los capítulos anteriores. |
| 1.3     | 04/05/2026 | Axel Ordoñez Ricaldi y Fabrizio Panta Castro | Se realizó la integración completa del Capítulo III, unificando los entregables de diseño trabajados por ambos integrantes. Se verificó que los lineamientos visuales, la arquitectura de información, los wireframes, los mock-ups, los flujos de usuario y el prototipado mantuvieran una misma identidad visual y respondieran adecuadamente a las necesidades de los segmentos objetivo de IoBuild. |
| 1.4     | 06/05/2026 | Mateo Loechle Arias          | Se desarrolló la primera parte del Capítulo IV, enfocada en Software Configuration Management. Se documentó la configuración del entorno de desarrollo, las herramientas utilizadas, los repositorios del proyecto, la estrategia de ramas, el uso de GitHub, las convenciones de código y los criterios de organización para la landing page, el backend y la aplicación móvil. |
| 1.5     | 08/05/2026 | Iker Barturen Panez          | Se complementó el Capítulo IV con la documentación de Product Implementation & Validation. Se incorporó el Sprint Planning 1, el Sprint Backlog 1, las tareas realizadas, las user stories completadas, las evidencias de desarrollo y la descripción de las funcionalidades implementadas en la landing page y en el backend. También se ordenaron las capturas, repositorios y resultados del sprint. |
| 1.6     | 10/05/2026 | Mateo Loechle Arias e Iker Barturen Panez | Se integraron las secciones de testing, ejecución y servicios del Capítulo IV. Se documentaron las pruebas unitarias, pruebas BDD, criterios Given-When-Then, evidencias de ejecución, endpoints REST, bounded contexts, recursos DTO, operaciones HTTP y documentación Swagger/OpenAPI. Además, se revisó la redacción técnica para que las evidencias de implementación y validación quedaran alineadas con el Sprint 1. |
| 1.7     | 12/05/2026 | Brayan Ccarita Cruz          | Se desarrolló la aplicación móvil en Kotlin, incorporando la estructura inicial del proyecto móvil, pantallas base, navegación y conexión con las funcionalidades principales planificadas para IoBuild. También se realizaron aportes al backend, apoyando la implementación de servicios, controladores y lógica necesaria para conectar la aplicación con los recursos de la plataforma. |
| 1.8     | 12/05/2026 | Brayan Ccarita Cruz          | Se realizaron los despliegues de la landing page y del backend. La landing page fue publicada en un entorno accesible públicamente y el backend fue desplegado junto con su documentación Swagger/OpenAPI. Además, se configuraron las variables necesarias para el funcionamiento de los servicios, se validaron las URLs públicas y se incorporaron las evidencias de despliegue dentro del Capítulo IV. |
| 1.9     | 13/05/2026 | Equipo CcaritaTech           | Se integraron los avances colaborativos de la landing page y del backend desarrollados por todos los integrantes. El equipo participó en la implementación de secciones visuales, estilos, assets, interactividad, bounded contexts, endpoints, documentación técnica y evidencias de desarrollo. Finalmente, se revisó el informe completo para asegurar coherencia entre capítulos, entregables, capturas, repositorios y despliegues de la solución IoBuild. |

<div style="page-break-before: always;"></div>

# Project Report Collaboration Insights

Enlace del repositorio: https://github.com/CcaritaTech/Report

<img src="https://i.ibb.co/Q3gXbzBN/N1.png" alt="Insights1" />

<img src="https://i.ibb.co/CsWW9jVP/N2.png" alt="Insights2" />

<img src="https://i.ibb.co/zWw7fCz8/N3.png" alt="Insights3" />

<div style="page-break-before: always;"></div>

# Project Landing Page Collaboration Insights

Enlace del repositorio: https://github.com/CcaritaTech/IoBuild-LandingPage

<img src="https://i.ibb.co/v642Grkr/Whats-App-Image-2026-05-13-at-3-51-54-PM.jpg" alt="Insights1" />

<img src="https://i.ibb.co/Fkhy9fGP/Whats-App-Image-2026-05-13-at-3-52-05-PM.jpg" alt="Insights2" />

<div style="page-break-before: always;"></div>

# Project Backend Collaboration Insights

Enlace del repositorio: https://github.com/CcaritaTech/IoBuild-Backend

<img src="https://i.ibb.co/fBjK3fK/Whats-App-Image-2026-05-13-at-3-54-28-PM.jpg" alt="Insights3" />

<img src="https://i.ibb.co/b5wymjRv/Whats-App-Image-2026-05-13-at-3-54-28-PM-1.jpg" alt="Insights4" />

<div style="page-break-before: always;"></div>

El desarrollo del informe fue producto de un trabajo colaborativo planificado y dividido en etapas progresivas. Para esta entrega, el equipo organizó las responsabilidades por capítulos y componentes técnicos, manteniendo una participación equilibrada en la documentación, la landing page y el backend de la plataforma IoBuild.

Barturen Panez, Iker Gabriel trabajó junto con Mateo Loechle en el desarrollo del Capítulo IV, enfocado en la implementación y validación del producto. Su participación se centró en documentar la configuración del entorno de desarrollo, la gestión del código fuente, las convenciones de estilo, las evidencias del Sprint 1, la documentación de servicios y la colaboración técnica del equipo. Además, colaboró en la implementación de la landing page y del backend, aportando a la consolidación de las evidencias técnicas del proyecto.

Ccarita Cruz, Brayan Roberto se encargó principalmente del desarrollo de la aplicación móvil en Kotlin, incorporando las funcionalidades iniciales necesarias para la experiencia móvil de IoBuild. También participó en el desarrollo del backend junto con el equipo, aportando a la construcción de servicios y funcionalidades de soporte. Asimismo, fue responsable de realizar los despliegues de la landing page y del backend, dejando disponibles las URLs públicas, la documentación Swagger y las evidencias de despliegue requeridas para la validación del producto.

Loechle Arias, Mateo Italo trabajó junto con Iker Barturen en el Capítulo IV, organizando la documentación de implementación, validación y evidencias del sprint. Su aporte incluyó la estructuración de la información relacionada con la configuración del software, repositorios, ramas, criterios de desarrollo, pruebas, ejecución de funcionalidades y documentación de servicios. También participó en el desarrollo colaborativo del backend y la landing page, asegurando que los avances técnicos quedaran correctamente reflejados en el informe.

Ordoñez Ricaldi, Axel Randall desarrolló junto con Fabrizio Panta los puntos del Capítulo III, correspondientes al diseño UX/UI de la solución. Su trabajo incluyó la elaboración y documentación de lineamientos visuales, arquitectura de información, wireframes, wireflows, mock-ups, user flows y prototipos de la aplicación móvil. Además, colaboró en la landing page y en el backend, contribuyendo a que la propuesta visual y funcional mantuviera coherencia con los objetivos de IoBuild.

Panta Castro, Fabrizio Martin trabajó junto con Axel Ordoñez en el desarrollo completo del Capítulo III, enfocándose en la organización de los entregables de diseño del producto. Participó en la definición de la experiencia de usuario, la documentación de la landing page, la consistencia visual de los mock-ups y la presentación de los flujos de interacción de la aplicación móvil. De igual manera, colaboró con el equipo en el desarrollo de la landing page y del backend, apoyando la integración final de los entregables.

<div style="page-break-before: always;"></div>

# Contenido
[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Objetivos SMART](#objetivos-smart)

[Capítulo I: Presentación](#capítulo-i-presentación)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. Big Picture Event Storming](#235-big-picture-event-storming)  
[2.3.6. Ubiquitous Language](#236-ubiquitous-language)

[2.4. Requirements Specification](#24-requirements-specification)  
[2.4.1. User Stories](#241-user-stories)  
[2.4.1.1. Epics](#2411-epics)  
[2.4.1.2. User Stories](#2412-user-stories)  
[2.4.1.3. Technical Stories](#2413-technical-stories)  
[2.4.1.4. Spike Stories](#2414-spike-stories)  
[2.4.2. Impact Mapping](#242-impact-mapping)  
[2.4.3. Product Backlog](#243-product-backlog)  

[2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)  
[2.5.1. EventStorming](#251-eventstorming)  
[2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)  
[2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)  
[2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)  
[2.5.2. Context Mapping](#252-context-mapping)  
[2.5.3. Software Architecture](#253-software-architecture)  
[2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)  
[2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)  
[2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)  

[2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)  
[2.6.1. Bounded Context: <Bounded Context Name>](#261-bounded-context-smart-project-setup)  
[2.6.1.1. Domain Layer](#2611-domain-layer)  
[2.6.1.2. Interface Layer](#2612-interface-layer)  
[2.6.1.3. Application Layer](#2613-application-layer)  
[2.6.1.4 Infrastructure Layer](#2614-infrastructure-layer)  
[2.6.1.5. Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)  
[2.6.1.6. Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)  
[2.6.1.6.1. Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)  
[2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)  

[2.6.2. Bounded Context: <Bounded Context Name>](#262-bounded-context-service-execution-and-monitoring)  
[2.6.2.1. Domain Layer](#2621-domain-layer)  
[2.6.2.2. Interface Layer](#2622-interface-layer)  
[2.6.2.3. Application Layer](#2623-application-layer)  
[2.6.2.4 Infrastructure Layer](#2624-infrastructure-layer)  
[2.6.2.5. Bounded Context Software Architecture Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)  
[2.6.2.6. Bounded Context Software Architecture Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)  
[2.6.2.6.1. Bounded Context Domain Layer Class Diagrams](#26261-bounded-context-domain-layer-class-diagrams)  
[2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)  

[2.6.3. Bounded Context: <Bounded Context Name>](#263-bounded-context-smart-assistant)  
[2.6.3.1. Domain Layer](#2631-domain-layer)  
[2.6.3.2. Interface Layer](#2632-interface-layer)  
[2.6.3.3. Application Layer](#2633-application-layer)  
[2.6.3.4 Infrastructure Layer](#2634-infrastructure-layer)  
[2.6.3.5. Bounded Context Software Architecture Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)  
[2.6.3.6. Bounded Context Software Architecture Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)  
[2.6.3.6.1. Bounded Context Domain Layer Class Diagrams](#26361-bounded-context-domain-layer-class-diagrams)  
[2.6.3.6.2. Bounded Context Database Design Diagram](#26362-bounded-context-database-design-diagram)  

[2.6.4. Bounded Context: <Bounded Context Name>](#264-bounded-context-energy-management)  
[2.6.4.1. Domain Layer](#2641-domain-layer)  
[2.6.4.2. Interface Layer](#2642-interface-layer)  
[2.6.4.3. Application Layer](#2643-application-layer)  
[2.6.4.4 Infrastructure Layer](#2644-infrastructure-layer)  
[2.6.4.5. Bounded Context Software Architecture Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)  
[2.6.4.6. Bounded Context Software Architecture Code Level Diagrams](#2646-bounded-context-software-architecture-code-level-diagrams)  
[2.6.4.6.1. Bounded Context Domain Layer Class Diagrams](#26461-bounded-context-domain-layer-class-diagrams)  
[2.6.4.6.2. Bounded Context Database Design Diagram](#26462-bounded-context-database-design-diagram)  

[Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)  

[3.1. Product design](#31-product-design)  
[3.1.1. Style Guidelines](#311-style-guidelines)  
[3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)  
[3.1.2. Information Architecture](#312-information-architecture)  
[3.1.2.1. Organization Systems](#3121-organization-systems)  
[3.1.2.2. Labelling Systems](#3122-labelling-systems)  
[3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)  
[3.1.2.4. Searching Systems](#3124-searching-systems)  
[3.1.2.5. Navigation Systems](#3125-navigation-systems)  
[3.1.3. Landing Page UI Design](#313-landing-page-ui-design)  
[3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)  
[3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)  
[3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)  
[3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)  
[3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)  
[3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)  
[3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)  
[3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)  

[Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)  

[4.1. Software Configuration Management](#41-software-configuration-management)  
[4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)  
[4.1.2. Source Code Management](#412-source-code-management)  
[4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)  
[4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)  

[4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)  
[4.2.1. Sprint 1](#421-sprint-1)  
[4.2.1.1. Sprint Planning 1](#4211-Sprint-planning-1)  
[4.2.1.2. Sprint Backlog 1](#4212-sprint-backlog-1)  
[4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)  
[4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)  
[4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)  
[4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)  
[4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)  
[4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)  

[4.2.2. Sprint 2](#422-sprint-2)  
[4.2.2.1. Sprint Planning 2](#4221-Sprint-planning-2)  
[4.2.2.2. Sprint Backlog 2](#4222-sprint-backlog-2)  
[4.2.2.3. Development Evidence for Sprint Review](#4223-development-evidence-for-sprint-review)  
[4.2.2.4. Testing Suite Evidence for Sprint Review](#4224-testing-suite-evidence-for-sprint-review)  
[4.2.2.5. Execution Evidence for Sprint Review](#4225-execution-evidence-for-sprint-review)  
[4.2.2.6. Services Documentation Evidence for Sprint Review](#4226-services-documentation-evidence-for-sprint-review)  
[4.2.2.7. Software Deployment Evidence for Sprint Review](#4227-software-deployment-evidence-for-sprint-review)  
[4.2.2.8. Team Collaboration Insights during Sprint](#4228-team-collaboration-insights-during-sprint)  

[4.2.3. Sprint 3](#423-sprint-3)  
[4.2.3.1. Sprint Planning 3](#4231-Sprint-planning-3)  
[4.2.3.2. Sprint Backlog 3](#4232-sprint-backlog-3)  
[4.2.3.3. Development Evidence for Sprint Review](#4233-development-evidence-for-sprint-review)  
[4.2.3.4. Testing Suite Evidence for Sprint Review](#4234-testing-suite-evidence-for-sprint-review)  
[4.2.3.5. Execution Evidence for Sprint Review](#4235-execution-evidence-for-sprint-review)  
[4.2.3.6. Services Documentation Evidence for Sprint Review](#4236-services-documentation-evidence-for-sprint-review)  
[4.2.3.7. Software Deployment Evidence for Sprint Review](#4237-software-deployment-evidence-for-sprint-review)  
[4.2.3.8. Team Collaboration Insights during Sprint](#4238-team-collaboration-insights-during-sprint)  

[4.3. Validation Interviews](#43-validation-interviews)  
[4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)  
[4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)  
[4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)  

[Conclusiones](#conclusiones)  
[Video App Validation](#video-app-validation)  
[Video About the product](#video-about-the-product)  
[Video About the team](#video-about-the-team)  

[Bibliografía](#bibliografía)  
[Anexos](#anexos)  

<div style="page-break-before: always;"></div>

# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y, en especial, para su proyecto en soluciones de software.|Axel Randall Ordoñez Ricaldi:<br>*AV1:* Colaboré con Fabrizio en EventStorming (Candidate Context Discovery, Domain Message Flows Modeling y Bounded Context Canvases), elaboré Context Mapping y Software Architecture Deployment Diagrams; este trabajo me permitió profundizar en DDD estratégico aplicado al proyecto.<br><br>*TB1:* Colaboré con Fabrizio en el desarrollo del Capítulo III, elaborando lineamientos visuales, arquitectura de información, wireframes, wireflows, mock-ups, user flows y prototipos de la aplicación móvil; este trabajo me permitió fortalecer mis conocimientos en diseño UX/UI y en la estructuración de experiencias digitales orientadas a usuarios.<br><br>Ccarita Cruz, Brayan Roberto:<br>*AV1:* Colaboré con Mateo e Iker en Domain, Interface, Application e Infrastructure Layer, y elaboré los Bounded Context Software Architecture Code Level Diagrams; esto me permitió fortalecer el diseño táctico y su trazabilidad con el código.<br><br>*TB1:* Desarrollé la aplicación móvil en Kotlin, implementando la estructura inicial del proyecto, pantallas, navegación y funcionalidades principales de IoBuild, además de participar en el backend y en los despliegues de la landing page y los servicios; esto me permitió reforzar mis competencias en desarrollo móvil, integración de sistemas y despliegue de aplicaciones.<br><br>Panta Castro, Fabrizio Martin:<br>*AV1:* Colaboré con Axel en EventStorming (Candidate Context Discovery, Domain Message Flows Modeling y Bounded Context Canvases), elaboré Context Mapping y Software Architecture Deployment Diagrams; ello me permitió consolidar conocimientos de modelado de dominio estratégico.<br><br>*TB1:* Trabajé junto con Axel en el desarrollo completo del Capítulo III, enfocándome en la experiencia de usuario, la documentación de la landing page, la consistencia visual de los mock-ups y los flujos de interacción de la aplicación móvil; este trabajo me permitió consolidar mis conocimientos en diseño UX/UI y prototipado de soluciones digitales.<br><br>Barturen Panez, Iker Gabriel:<br>*AV1:* Colaboré con Mateo en el Tactical-Level DDD del Bounded Context (Domain Layer, Interface Layer, Application Layer e Infrastructure Layer); este desarrollo me permitió profundizar en arquitectura por capas y responsabilidades del dominio.<br><br>*TB1:* Colaboré con Mateo en el desarrollo del Capítulo IV, documentando la implementación y validación del producto, incluyendo configuración del entorno, gestión del código, evidencias del Sprint 1 y documentación de servicios; este trabajo me permitió profundizar en la organización técnica de proyectos y en procesos de implementación de software.<br><br>Loechle Arias, Mateo Italo:<br>*AV1:* Colaboré con Iker en el Tactical-Level DDD del Bounded Context (Domain Layer, Interface Layer, Application Layer e Infrastructure Layer); este trabajo me permitió reforzar la definición de capas y reglas de negocio del contexto.<br><br>*TB1:* Trabajé junto con Iker en el Capítulo IV, organizando la documentación de implementación, validación y pruebas del sprint, además de estructurar la información relacionada con repositorios, ramas, ejecución de funcionalidades y servicios; este trabajo me permitió fortalecer mis competencias en gestión técnica, pruebas y documentación de proyectos de software.<br>|En AV1, el equipo evidenció actualización de conocimientos al aplicar DDD estratégico y táctico, integrando modelado de dominio y arquitectura de software en entregables concretos del proyecto.<br><br><br>En TB1, el equipo evidenció la actualización de conocimientos mediante la aplicación de metodologías de diseño UX/UI, desarrollo de aplicaciones móviles, implementación de servicios backend y procesos de validación y despliegue, materializando estos aprendizajes en entregables concretos del proyecto IoBuild.|
|Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.|Axel Randall Ordoñez Ricaldi:<br>*AV1:* Investigué y apliqué nuevas técnicas de EventStorming, Context Mapping y Deployment Diagrams junto a Fabrizio, incorporando buenas prácticas de DDD para fortalecer la arquitectura del proyecto.<br><br>*TB1:* Investigué y apliqué principios de diseño UX/UI junto con Fabrizio, profundizando en arquitectura de información, prototipado y diseño de experiencias de usuario para aplicaciones móviles. Esto me permitió ampliar mis conocimientos en herramientas y metodologías centradas en el usuario.<br><br>Ccarita Cruz, Brayan Roberto:<br>*AV1:* Aprendí y apliqué criterios de arquitectura a nivel código mientras colaboraba con Mateo e Iker en las capas tácticas del Bounded Context, reforzando mi aprendizaje continuo.<br><br>*TB1:* Aprendí y apliqué nuevas prácticas de desarrollo móvil con Kotlin, integración de servicios backend y procesos de despliegue, fortaleciendo mis competencias técnicas y mi capacidad para implementar soluciones completas en entornos reales.<br><br>Panta Castro, Fabrizio Martin:<br>*AV1:* Investigué y apliqué nuevas técnicas de EventStorming, Context Mapping y Deployment Diagrams junto a Axel, validando decisiones de diseño con enfoque de mejora continua.<br><br>*TB1:* Profundicé junto con Axel en técnicas de diseño UX/UI, creación de wireframes, mock-ups y flujos de interacción, incorporando buenas prácticas de diseño centrado en el usuario que fortalecieron mi aprendizaje continuo en el desarrollo de productos digitales.<br><br>Barturen Panez, Iker Gabriel:<br>*AV1:* Profundicé junto a Mateo en DDD táctico (Domain Layer, Interface Layer, Application Layer e Infrastructure Layer), incorporando nuevos criterios técnicos para mejorar de forma continua el diseño del Bounded Context.<br><br>*TB1:* Profundicé junto con Mateo en la documentación de implementación, validación y configuración de proyectos de software, incorporando nuevas prácticas relacionadas con gestión de repositorios, pruebas y organización técnica de entregables.<br><br>Loechle Arias, Mateo Italo:<br>*AV1:* Profundicé junto a Iker en DDD táctico (Domain Layer, Interface Layer, Application Layer e Infrastructure Layer), fortaleciendo mis competencias en separación de responsabilidades y evolución del diseño del dominio.<br><br>*TB1:* Aprendí y apliqué nuevas técnicas de documentación técnica, validación de funcionalidades y gestión de configuración de software junto con Iker, fortaleciendo mis conocimientos sobre procesos de implementación y aseguramiento de calidad en proyectos de desarrollo.<br>|En AV1, el grupo demostró aprendizaje permanente al investigar y adoptar nuevas técnicas de DDD y arquitectura, transfiriendo conocimiento entre integrantes y elevando la calidad técnica del trabajo colaborativo.<br><br><br>En TB1, el equipo demostró aprendizaje permanente al adquirir y aplicar nuevos conocimientos en diseño UX/UI, desarrollo móvil, despliegue de aplicaciones, documentación técnica y validación de software, fortaleciendo sus competencias profesionales mediante el trabajo colaborativo y la implementación práctica de la solución IoBuild.|

<div style="page-break-before: always;"></div>

# Objetivos SMART
Esta sección presenta el plan de crecimiento profesional postgrado de cada integrante, con dos objetivos SMART por persona.

## 1. Axel Randall Ordoñez Ricaldi (U202216827)

### 1.1. Especialización en Desarrollo Móvil Nativo Android
- **Specific:** Dominar el desarrollo de aplicaciones nativas para Android utilizando Kotlin y Jetpack Compose.
- **Measurable:** Obtener la certificación Associate Android Developer y publicar al menos 2 aplicaciones propias en Google Play Store.
- **Achievable:** Dedicar 8 horas semanales al estudio y práctica, utilizando recursos como Android Developers y Kotlin Docs.
- **Relevant:** Para acceder a posiciones como Android Developer en startups o empresas tech en Latinoamérica.
- **Time-bound:** Lograr la certificación y publicar la primera app en los primeros 6 meses tras graduarse.

### 1.2. Liderazgo Técnico en Proyectos Móviles
- **Specific:** Adquirir las habilidades necesarias para liderar técnicamente equipos de desarrollo móvil.
- **Measurable:** Aspirar a un puesto de Tech Lead o Mobile Development Manager en un plazo de 5 años.
- **Achievable:** Buscar mentoría, tomar cursos de gestión ágil de proyectos y liderar iniciativas dentro de la empresa donde trabaje.
- **Relevant:** Para dirigir la creación de productos móviles de alto impacto y guiar a desarrolladores junior.
- **Time-bound:** Ocupar un puesto de liderazgo intermedio en 3 años y uno senior en 5 años.

## 2. Ccarita Cruz, Brayan Roberto (U20221C218)

### 2.1. Maestría en Ingeniería de Software con mención en Arquitectura
- **Specific:** Realizar una maestría que profundice en arquitecturas de software escalables y cloud computing.
- **Measurable:** Ser admitido y completar el programa de maestría con un promedio mayor a 16/20.
- **Achievable:** Ahorrar un porcentaje del salario y postular a becas internacionales para financiar los estudios.
- **Relevant:** Para diseñar sistemas backend robustos que soporten aplicaciones móviles a gran escala.
- **Time-bound:** Iniciar la maestría en el segundo año post-graduación y finalizarla en 2 años.

### 2.2. Contribuir a Proyectos Open Source de Impacto
- **Specific:** Convertirse en un contribuidor activo de proyectos open source relacionados con el ecosistema Kotlin/Spring.
- **Measurable:** Realizar al menos 50 contribuciones (commits, issues, PRs) a proyectos reconocidos en un año.
- **Achievable:** Dedicar 5 horas semanales a explorar, documentar y contribuir código en GitHub.
- **Relevant:** Para ganar reputación en la comunidad técnica, aprender de los mejores y mejorar las habilidades de coding.
- **Time-bound:** Lograr el primer PR aceptado en los primeros 3 meses y mantener contribuciones consistentes por 12 meses.

## 3. Panta Castro, Fabrizio Martin (U20231A810)

### 3.1. Dominio del Desarrollo Backend con Spring Boot
- **Specific:** Especializarme en el desarrollo de APIs RESTful robustas y escalables utilizando Spring Boot y Java.
- **Measurable:** Diseñar e implementar 3 APIs complejas con autenticación JWT, manejo de errores y documentación Swagger/OpenAPI.
- **Achievable:** Dedicar 10 horas semanales a practicar con proyectos personales y seguir tutoriales avanzados de Spring.
- **Relevant:** Para trabajar como Backend Developer en empresas que requieran servicios web para aplicaciones móviles.
- **Time-bound:** Completar la primera API en 3 meses y las tres en 9 meses.

### 3.2. Certificación en Cloud AWS para Developers
- **Specific:** Adquirir conocimientos prácticos en servicios AWS esenciales para deployment y escalabilidad de aplicaciones.
- **Measurable:** Obtener la certificación AWS Certified Developer - Associate.
- **Achievable:** Completar el curso "AWS Essentials" y practicar con los servicios de free tier.
- **Relevant:** Para mejorar la empleabilidad y capacidad de desplegar aplicaciones en la nube.
- **Time-bound:** Aprobar el examen de certificación en los primeros 8 meses tras graduarse.

## 4. Barturen Panez, Iker Gabriel (U201919096)

### 4.1. Especialización en Bases de Datos y Optimización
- **Specific:** Profundizar en el diseño, implementación y optimización de bases de datos relacionales y no relacionales.
- **Measurable:** Diseñar el esquema de base de datos para 2 aplicaciones reales y optimizar consultas complejas.
- **Achievable:** Practicar con PostgreSQL y MongoDB, y realizar cursos avanzados de SQL y performance tuning.
- **Relevant:** Para garantizar el rendimiento y la confiabilidad de las aplicaciones que desarrolle.
- **Time-bound:** Dominar los conceptos avanzados en 6 meses y aplicar las optimizaciones en un proyecto real en 12 meses.

### 4.2. Certificación en Metodologías Ágiles (Scrum)
- **Specific:** Adquirir un conocimiento formal y práctico de las metodologías ágiles para mejorar la gestión de proyectos.
- **Measurable:** Obtener la certificación Professional Scrum Master I (PSM I).
- **Achievable:** Estudiar la guía de Scrum y realizar exámenes de práctica.
- **Relevant:** Para trabajar eficientemente en equipos ágiles y aspirar a roles de liderazgo.
- **Time-bound:** Obtener la certificación en los primeros 4 meses post-graduación.

## 5. Loechle Arias, Mateo Italo (U202215004)

### 5.1. Desarrollo Full Stack con Enfoque en Mobile Backend
- **Specific:** Convertirme en un desarrollador full stack, con habilidades tanto en frontend móvil (Kotlin) como en backend (Spring Boot).
- **Measurable:** Construir una aplicación completa (frontend y backend) con al menos 5 funcionalidades principales.
- **Achievable:** Dedicar 12 horas semanales a aprender y practicar integración frontend-backend.
- **Relevant:** Para tener una visión completa del ciclo de desarrollo y ser más versátil en el mercado laboral.
- **Time-bound:** Completar la aplicación en 6 meses.

### 5.2. Certificación en Kotlin Avanzado
- **Specific:** Dominar aspectos avanzados de Kotlin para desarrollo móvil y backend.
- **Measurable:** Obtener la certificación "Kotlin Certified Developer" de JetBrains.
- **Achievable:** Realizar el curso oficial de Kotlin y practicar con ejercicios avanzados.
- **Relevant:** Para demostrar expertise en el lenguaje principal utilizado en el proyecto Centralis.
- **Time-bound:** Aprobar el examen de certificación en los primeros 5 meses tras graduarse.

<div style="page-break-before: always;"></div>

# Capítulo I: Presentación
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

IoBuild nace con un propósito claro: transformar los edificios y espacios inmobiliarios en entornos inteligentes, accesibles y altamente personalizables. Creemos que los espacios donde vivimos y trabajamos no deben ser estáticos, sino dinámicos, adaptándose a las necesidades de quienes los habitan y a la visión de quienes los construyen.

Nuestra plataforma digital ofrece herramientas intuitivas que permiten a empresas constructoras, ingenieros y arquitectos integrar fácilmente funcionalidades inteligentes en sus proyectos, como el control de iluminación, la automatización de ventanas, la programación de riego en áreas verdes o la gestión de energía en tiempo real. Al mismo tiempo, los propietarios pueden personalizar la experiencia de su hogar o edificio con ajustes simples y sin necesidad de conocimientos técnicos avanzados.

IoBuild se dirige a dos segmentos clave:

Empresas constructoras, arquitectos e ingenieros, que buscan diferenciar sus proyectos con propuestas de valor innovadoras y adaptadas a las nuevas tendencias de espacios inteligentes.

Propietarios e inquilinos, que desean disfrutar de mayor confort, eficiencia y personalización en sus viviendas o espacios de trabajo.

Nuestra propuesta de valor combina simplicidad, innovación y personalización. Queremos que la gestión de un espacio inteligente sea tan fácil como usar una aplicación móvil, eliminando barreras técnicas y potenciando tanto la habitabilidad como la eficiencia.

**Misión:** Democratizar el acceso a la tecnología para edificios inteligentes, brindando a constructoras y propietarios herramientas accesibles y prácticas que mejoren la experiencia de los espacios y optimicen su funcionamiento.

**Visión:** Construir una comunidad en la que cada espacio cuente con identidad propia, promoviendo ciudades más inteligentes, sostenibles y centradas en las personas.

Más que facilitar la automatización, en IoBuild buscamos que cada espacio cobre vida y refleje el estilo de quienes lo habitan. Queremos ser el puente entre la innovación tecnológica y el confort humano, impulsando una nueva era en el sector inmobiliario.


#### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo                                                                                                                                                                    | Codigo Estudiante | Carrera                 | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Axel Randall Ordoñez Ricaldi <br> <img src="https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%201/Axel-photo.jpg" width=150>       | U202216827        | Ingenieria de software  | Mi nombre es Axel, tengo 21 años, estoy cursando el 7mo ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona con paciencia y buen trabajo en equipo, lo cual ayuda mucho cuando las tareas se acumulan. Tengo conocimientos bastante útiles para el desarrollo de este proyecto como tal, y espero llevarme bien con mi equipo y hacer un buen trabajo. Mis conocimientos y habilidades se centran en C# y Python principalmente, acompañado de diversos frameworks como React, Vue y Angular, de la misma forma me llevo de mejor forma con lo que son dbs, SQL y MongoDB, entre otros más. |
| Ccarita Cruz, Brayan Roberto  <br> <img src="https://upc-pre-1asi0730-7461-ccaritatech.github.io/landing-page-CcaritaTech/assets/img/member-1.png" width=150>                          | U20221C218        | Ingeniería de Software  | Mi nombre es Brayan, estoy cursando el 7mo ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona perseverante y puntual, siempre tratando de cumplir con lo que me corresponde a tiempo. Tengo conocimientos bastante útiles para el desarrollo de este proyecto como tal, y espero llevarme bien con mi equipo y hacer un buen trabajo. Mis conocimientos y habilidades se centran en lenguajes como Golang y herramientas como Astro.js y Svelte, de la misma forma me llevo de mejor forma con metodologías de diseño como Design Sprint, entre otros más.                                 |
| Panta Castro, Fabrizio Martin  <br> <img src="https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%201/Fabrizio-photo.jpg" width=150> | U20231A810        | Ingeniería de Software  | Mi nombre es Fabrizio, tengo 23 años, estoy cursando el 7mo ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona con compañerismo y responsable con las entregas, enfocándome en que el equipo avance unido. Tengo conocimientos bastante útiles para el desarrollo de este proyecto como tal, y espero llevarme bien con mi equipo y hacer un buen trabajo. Mis conocimientos y habilidades se centran en C++ y Python principalmente, acompañado de frameworks para móviles como Flutter y Vue, de la misma forma me llevo de mejor forma con lo que son dbs como SQL, entre otros más.    |
| Barturen Panez, Iker Gabriel <br> <img src="https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%201/Iker-photo.jpeg?raw=true" width="150"/>               | U201919096        | Ingeniería de software  | Mi nombre es Iker, tengo 19 años y actualmente estoy cursando el 7to ciclo de la carrera Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Considero que soy alguien responsable, cumple con los trabajos que se me encargan a tiempo y se tengo la posibilidad apoyo a mis compañeros con sus trabajos, trabajó bien en equipo y puedo aportar mis conocimientos con el lenguaje de programación C++, C# y conocimientos basicos de python, también sobre los frameworks de Javascript react, astro y angular.                                                                                     |
| Loechle Arias, Mateo Italo <br> <img src="https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%201/Mateo-photo.jpeg?raw=true" width="150"/>                | U202215004        | Ingenieria de software  | Mi nombre es Mateo , tengo 21 años , estoy cursando el 7to ciclo de la carrera de Ingenieria de Software en la UPC. Me considero una persona responsable ocasionalmente , dependiendo de cuantas cosas tenga por hacer . Tengo conocimientos bastante utiles para el desarrollo de este proyecto como tal , y espero llevarme bien con mi equipo y hacer un buen trabajo. Mis conocimientos y habilidades se centran en Java principalmente acompañado de diversos frameworks como angular y react , de la misma forma me llevo de mejor forma con lo que son dbs , mongodb, sql , sqlite, entre otros mas.               |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

En los últimos años, el sector inmobiliario y de la construcción ha experimentado una transformación impulsada por la creciente demanda de espacios inteligentes, sostenibles y personalizables. Las tendencias globales en domótica, IoT (Internet of Things) y eficiencia energética han comenzado a redefinir la forma en que las personas interactúan con sus viviendas y lugares de trabajo. Sin embargo, en gran parte de Latinoamérica y específicamente en el Perú, la adopción de estas tecnologías sigue siendo limitada debido a altos costos de implementación, falta de estandarización y ausencia de soluciones accesibles para el usuario final.

Actualmente, la mayoría de proyectos inmobiliarios no incorpora de manera nativa funcionalidades inteligentes como control automatizado de iluminación, climatización, seguridad o gestión energética en tiempo real. Cuando estas soluciones se incluyen, suelen estar restringidas a segmentos de alto poder adquisitivo, generando una brecha de accesibilidad entre quienes pueden disfrutar de la tecnología y quienes no.

Por otro lado, los propietarios e inquilinos enfrentan problemas al intentar personalizar sus espacios: las opciones suelen ser costosas, requieren conocimientos técnicos avanzados o dependen de la contratación de múltiples proveedores sin integración entre sistemas. Esto genera experiencias fragmentadas y reduce el valor percibido de la inversión.

En el caso de las constructoras, arquitectos e ingenieros, la problemática se centra en la necesidad de diferenciar sus proyectos en un mercado altamente competitivo. Si bien existe interés en ofrecer soluciones innovadoras, los equipos de construcción se enfrentan a falta de plataformas unificadas que simplifiquen la integración de tecnología inteligente en sus edificaciones, lo que dificulta la planificación y eleva los costos de implementación.

La problemática puede resumirse en los siguientes puntos:
- **Accesibilidad limitada:** la mayoría de soluciones de automatización están dirigidas a mercados premium, dejando de lado a gran parte de la población.

- **Falta de estandarización:** los sistemas actuales suelen ser propietarios y poco compatibles, lo que genera barreras técnicas.

- **Costos elevados:** implementar tecnologías inteligentes requiere inversiones iniciales altas, lo que desalienta a constructoras y propietarios.

- **Complejidad técnica:** los usuarios finales carecen de herramientas intuitivas para personalizar y gestionar sus espacios de manera autónoma.

- **Baja diferenciación en proyectos inmobiliarios:** las constructoras tienen dificultades para ofrecer un valor agregado innovador frente a la competencia.

En este contexto, IoBuild surge como respuesta a la necesidad de democratizar el acceso a los espacios inteligentes, ofreciendo una plataforma que facilita la integración tecnológica desde la etapa de construcción hasta la personalización por parte del usuario final.<br><br>

<div style="page-break-before: always;"></div>

**1. What (¿Qué?)**

La mayoría de proyectos inmobiliarios no incorporan de manera integral soluciones inteligentes desde su diseño, lo que provoca que los espacios continúen siendo rígidos y poco adaptables a las necesidades de los usuarios. Las opciones que existen en el mercado suelen estar enfocadas en segmentos de alto costo, como consecuencia, los usuarios finales terminan recurriendo a dispositivos aislados, como focos inteligentes o asistentes de voz, que no siempre son compatibles entre sí.

**2. Why (¿Por qué?)**

Porque las tecnologías de domótica e IoT han sido diseñadas de forma fragmentada, con estándares poco unificados que dificultan la integración entre sistemas. Además, el costo de implementación es elevado, ya que no solo implica la adquisición de hardware, sino también licencias y soporte especializado. A ello se suma la complejidad tecnológica, pues la configuración y mantenimiento de estos sistemas requieren conocimientos avanzados que no todos los usuarios poseen.

**3. Who (¿Quién?)**

Impacta principalmente en empresas constructoras, arquitectos e ingenieros que buscan diferenciar sus proyectos, pero no encuentran soluciones accesibles que les permitan añadir valor con espacios inteligentes. También, afecta a los propietarios e inquilinos, quienes experimentan frustración al no poder personalizar fácilmente sus viviendas u oficinas y ven reducido su nivel de confort.

**4. Where (¿Dónde?)**

Se manifiesta tanto en proyectos de construcción urbana como en remodelaciones de viviendas y oficinas. En el primer caso, los edificios se levantan bajo modelos tradicionales, con muy poca o nula integración de sistemas inteligentes, lo que limita el atractivo de las propuestas inmobiliarias. En el segundo, los propietarios interesados en modernizar sus espacios encuentran barreras técnicas y económicas que dificultan la incorporación de funcionalidades de automatización.

**5. When (¿Cuándo?)**

Se presenta en la actualidad, en un momento en que la digitalización y la sostenibilidad se han convertido en factores clave de competitividad. La demanda de espacios inteligentes es cada vez más alta, especialmente entre nuevas generaciones que valoran la tecnología como parte de su estilo de vida.

**6. How (¿Cómo?)**

Se refleja en la dificultad de las constructoras y arquitectos para ofrecer proyectos innovadores sin depender de sistemas costosos y difíciles de implementar. Para los propietarios e inquilinos, se traduce en experiencias limitadas, ya que deben conformarse con dispositivos sueltos que no logran integrarse en un ecosistema coherente.

**7. How much (¿Cuánto?)**

El costo de implementar tecnologías inteligentes en espacios inmobiliarios tradicionales suele ser elevado, no solo por el precio de los dispositivos, sino también por la necesidad de contratar integradores especializados y adquirir licencias propietarias. Para una empresa constructora, la integración de soluciones de automatización puede representar entre un 10 % y un 20 % adicional sobre el presupuesto inicial de un proyecto, lo que limita su adopción en desarrollos de bajo o mediano costo. Para un propietario, la inversión inicial en sistemas fragmentados puede superar varios miles de dólares, sin garantizar una experiencia unificada ni la posibilidad de escalar a nuevas funcionalidades.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

Actualmente, el uso de tecnologías inteligentes en viviendas y edificios residenciales ha ido aumentando debido al interés de las personas por mejorar la comodidad, la seguridad y la eficiencia energética de los espacios que habitan. Cada vez es más común encontrar dispositivos como cámaras inteligentes, sistemas de iluminación automatizada, sensores de acceso y asistentes de voz. Sin embargo, la implementación de estas tecnologías aún presenta desafíos relacionados con la compatibilidad entre dispositivos, la facilidad de uso y la gestión centralizada de los distintos servicios disponibles.

El punto crítico identificado es la falta de integración entre las distintas tecnologías utilizadas en los edificios inteligentes. Las constructoras suelen enfrentar dificultades al implementar soluciones de diferentes proveedores, mientras que los propietarios deben adaptarse al uso de múltiples aplicaciones para gestionar funciones como iluminación, seguridad o climatización. Esta fragmentación genera una experiencia poco práctica para los usuarios, dificulta la adopción de la tecnología y reduce los beneficios que podrían obtenerse mediante una gestión centralizada y eficiente de los dispositivos inteligentes.

¿Cómo podríamos simplificar el despliegue y la operación diaria de dispositivos IoT en proyectos residenciales, logrando que tanto constructoras como residentes adopten una única solución que incremente el control, la eficiencia y la satisfacción en todos los espacios habitados?

#### 1.2.2.2. Lean UX Assumptions.

En la fase inicial de desarrollo de la plataforma IoBuild, hemos identificado y articulado una serie de supuestos fundamentales siguiendo los principios de la metodología Lean UX. Estos supuestos son nuestras hipótesis iniciales sobre quiénes son nuestros usuarios, qué beneficios esperan, cómo operará el negocio, el impacto que anticipamos generar y las características clave que necesitamos para lograrlo. Formalizar estas creencias nos permite enfocar el desarrollo del producto en la validación temprana, la minimización de riesgos y la toma de decisiones estratégicas basada en datos.

Los supuestos se han clasificado en cinco categorías principales para una estructuración clara:

- **User Assumptions**: Nuestras creencias sobre las necesidades, comportamientos y motivaciones de las empresas constructoras, arquitectos y propietarios.
- **User Outcome Assumptions**: Los resultados positivos y las ganancias de eficiencia que esperamos que nuestros usuarios experimenten al interactuar con IoBuild.
- **Business Assumptions**: Hipótesis sobre la viabilidad de nuestro modelo de negocio y el contexto del mercado inmobiliario.
- **Business Outcome Assumptions**: Los impactos mensurables que esperamos que la plataforma genere en la empresa, como crecimiento de ingresos y reducción de costos.
- **Feature Assumptions**: Nuestras creencias sobre cómo funcionalidades específicas resolverán los problemas de los usuarios y validarán los supuestos de negocio.

Estos supuestos formarán la estructura de nuestra estrategia de diseño y proporcionarán un marco para la validación continua.

- **User Assumptions** 
   - **Creemos que el 65 % de las empresas constructoras y arquitectos buscan soluciones de automatización de edificios que no requieran una integración compleja y costosa**, ya que las barreras tecnológicas y económicas actuales limitan la adopción de la domótica en sus proyectos.

   - **Creemos que el 90 % de los propietarios y arrendatarios valoran una interfaz de control unificada para sus hogares inteligentes**, porque la fragmentación de aplicaciones y dispositivos genera una experiencia frustrante e ineficiente.

   - **Creemos que el 80 % de los propietarios desea personalizar su entorno doméstico (iluminación, temperatura, seguridad) sin necesidad de conocimientos técnicos**, debido a que la personalización es un factor clave en la satisfacción residencial moderna.

   - **Creemos que el 75 % de los ingenieros y técnicos de la construcción desean herramientas que les permitan configurar y desplegar sistemas inteligentes de forma remota y sin interrupciones**, porque la gestión de proyectos a gran escala demanda flexibilidad y control en tiempo real.

   - **Creemos que el 55 % de los promotores inmobiliarios priorizarán la integración de tecnologías inteligentes si estas les permiten ofrecer un valor distintivo en el mercado**, ya que la innovación tecnológica se está convirtiendo en un factor decisivo de compra y arrendamiento.
<br>

- **User Outcome Assumptions**
   - **Creemos que si las constructoras pueden integrar nuestra solución con un proceso simplificado y modular, entonces reducirán el tiempo de implementación de tecnologías inteligentes en al menos un 40 %**, lo que les permitirá finalizar proyectos más rápido y de manera más competitiva.

    - **Creemos que si los propietarios tienen una herramienta accesible para controlar sus espacios, entonces su calificación de satisfacción con la experiencia de habitar será un 25 % superior** en encuestas de salida o de satisfacción anual.

    - **Creemos que si nuestra plataforma permite la gestión centralizada de múltiples funciones (seguridad, energía, confort), entonces el 60 % de los usuarios reportará una reducción significativa de la frustración** asociada al uso de múltiples aplicaciones dispares.

    - **Creemos que si los arquitectos y diseñadores pueden visualizar y simular la integración de nuestros sistemas en sus modelos BIM, entonces acelerarán su fase de diseño conceptual en un 30 %,** mejorando la eficiencia de sus flujos de trabajo.
<br>

- **Business Assumptions**
   - **Creemos que el 70 % de nuestros ingresos provendrá de la venta de licencias de proyecto (B2B)** a constructoras y arquitectos, y el 30 % restante de suscripciones y servicios de gestión para propietarios finales (B2C), ya que el sector de la construcción se digitaliza a un ritmo acelerado.

    - **Creemos que el 15 % de los proyectos registrados en la plataforma en el primer año superará los 100 usuarios activos**, lo que nos permitirá generar ingresos adicionales por el escalado de licencias.

    - **Creemos que mantendremos un margen bruto del 60 %**, ya que nuestro modelo de negocio de software y la producción bajo demanda evitan los costos de inventario.

    - **Creemos que cerraremos al menos 10 alianzas estratégicas con fabricantes de hardware y domótica**, lo que solidificará nuestra propuesta de valor y atraerá a un 20 % de clientes que prefieren ecosistemas de productos definidos.

    - **Creemos que al ofrecer una prueba de concepto gratuita para proyectos pequeños, lograremos convertir al 25 % de esos usuarios en clientes de pago en los primeros seis meses**, validando así la efectividad de nuestro embudo de ventas.

    - **Creemos que el 50 % de nuestras nuevas adquisiciones de clientes provendrá de marketing de contenido y alianzas con influenciadores de la industria inmobiliaria**, porque la confianza y las referencias son cruciales en este sector.
<br>

- **Business Outcome Assumptions**
    - **Creemos que si los propietarios adoptan y utilizan la plataforma con regularidad, entonces lograremos una tasa de retención de licencias B2C del 75 % en el primer año**, lo que generará un flujo de ingresos recurrente.
    - **Creemos que si la plataforma ofrece una experiencia de usuario fluida y sin complicaciones, entonces reduciremos los costos de soporte y atención al cliente en un 30 %** durante los primeros seis meses, mejorando la rentabilidad operativa.
    - **Creemos que si los ingenieros pueden configurar los sistemas de forma remota, entonces se reducirá en un 40 %** el tiempo y los costos de implementación en sitio, permitiéndonos escalar nuestra operación a más proyectos simultáneamente.
    - **Creemos que si fortalecemos las alianzas estratégicas, entonces conseguiremos una reducción del 15 % en los costos de adquisición de clientes (CAC)**, ya que las recomendaciones de nuestros socios nos proporcionarán nuevos clientes de forma más eficiente.
    - **Creemos que si las empresas constructoras pueden integrar nuestra plataforma fácilmente, entonces incrementaremos la tasa de conversión de proyectos de prueba a clientes de pago en un 25 %** durante el primer semestre, aumentando los ingresos directos.
<br>

- **Feature Assumptions**
    - **Creemos que la funcionalidad de un constructor de espacios inteligentes permitirá a los arquitectos e ingenieros diseñar layouts arrastrando y soltando dispositivos IoT**, de modo que el 60 % de ellos lo utilice para planificar sus proyectos en la plataforma.
    - **Creemos que el simulador en tiempo real de flujos de automatización permitirá a las constructoras validar la lógica de sus sistemas antes de la instalación**, de forma que el 90 % lo utilice para testear sus configuraciones.
    - **Creemos que el panel de control unificado permitirá a los propietarios gestionar su espacio desde una sola interfaz**, consiguiendo que el 80 % lo use como su herramienta principal de control diario.
    - **Creemos que la integración con marcas de hardware permitirá a los usuarios conectar sus dispositivos existentes a la plataforma**, logrando que el 70 % de los clientes B2C lo use en su primera semana de activación.
    - **Creemos que las notificaciones y alertas personalizables permitirán a los usuarios estar al tanto de la seguridad y el consumo de energía en sus propiedades**, de forma que el 50 % de ellos configure al menos 3 alertas en los primeros 30 días.
    - **Creemos que la funcionalidad de acceso remoto permitirá a los ingenieros y propietarios gestionar sus espacios desde cualquier lugar**, alcanzando que el 75 % de las gestiones fuera de la oficina se realicen en dispositivos móviles.
    - **Creemos que el sistema de reportes de consumo de energía permitirá a los usuarios tomar decisiones para optimizar sus gastos**, logrando una disminución del 20 % en el consumo energético reportado en el primer año.
    - **Creemos que la funcionalidad de creación de "escenas" o ambientes (ej. "Modo cine") simplificará la vida de los propietarios**, con el 60 % de ellos creando al menos una escena en el primer mes de uso.
    - **Creemos que la integración con asistentes de voz (ej. Alexa, Google Home) mejorará la experiencia del usuario**, consiguiendo que el 40 % de los usuarios de hogares inteligentes conecte su cuenta en los primeros tres meses.
    - **Creemos que un sistema de permisos y roles permitirá a los administradores de proyectos controlar quién puede acceder a qué funciones**, logrando una reducción del 95 % en los problemas de seguridad o acceso no autorizado reportados.
<br>

#### 1.2.2.3. Lean UX Hypothesis Statements.

- Creemos que centralizaremos el control en una única plataforma accesible
para propietarios que sufren por el uso de múltiples aplicaciones de domótica,
lograremos eliminar la fragmentación tecnológica y simplificar la gestión del hogar.
Sabremos que tuvimos éxito cuando veamos una tasa de retención de licencias B2C del 75% en el primer año.

- Creemos que implementaremos una interfaz de autogestión intuitiva y un centro de ayuda integrado
para residentes que dependen constantemente del soporte técnico,
lograremos reducir el volumen de consultas operativas y aumentar la autonomía del usuario.
Sabremos que tuvimos éxito cuando veamos que las solicitudes de soporte técnico disminuyen en un 30%.

- Creemos que permitiremos la creación de "escenas" y rutinas personalizadas sin código
para usuarios finales que desean un hogar inteligente adaptado a su estilo de vida,
lograremos mejorar la percepción de valor y confort del sistema loBuild.
Sabremos que tuvimos éxito cuando veamos que la satisfacción del usuario aumenta un 25% en las encuestas de NPS.

- Creemos que entregaremos reportes analíticos de consumo en tiempo real
para usuarios preocupados por el gasto excesivo de recursos,
lograremos una reducción tangible en el desperdicio de energía y agua en los hogares.
Sabremos que tuvimos éxito cuando veamos una disminución promedio del 20% en el consumo energético reportado por los usuarios.

- Creemos que ofreceremos configuraciones modulares y escalables de bajo costo
para personas que consideran que la domótica es un lujo inalcanzable,
lograremos democratizar el acceso a la tecnología Smart Home en sectores de ingresos medios.
Sabremos que tuvimos éxito cuando veamos un incremento del 40% en nuevas suscripciones del segmento residencial.

**Segmento: Ingenieros y Técnicos (Operaciones)<br>**
- Creemos que habilitaremos herramientas de configuración y despliegue remoto
para los ingenieros de preventa y técnicos de instalación,
lograremos reducir drásticamente los tiempos de configuración y los traslados innecesarios a la obra.
Sabremos que tuvimos éxito cuando veamos una reducción del 40% en los costos operativos de instalación.

- Creemos que optimizaremos el sistema de monitoreo masivo de dispositivos
para ingenieros responsables de la infraestructura de grandes edificios,
lograremos una gestión eficiente de miles de nodos IoT desde una sola estación de trabajo.
Sabremos que tuvimos éxito cuando veamos que un solo técnico puede gestionar un 50% más de proyectos simultáneamente.

- Creemos que integraremos un simulador de flujos compatible con modelos BIM (Building Information Modeling)
para diseñadores y arquitectos técnicos,
lograremos eliminar errores de compatibilidad de hardware antes de la construcción física.
Sabremos que tuvimos éxito cuando veamos una reducción del 30% en los cambios de diseño durante la fase de ejecución.

**Segmento: Constructoras e Inmobiliarias (B2B)**<br>
- Creemos que estableceremos alianzas de compatibilidad con los principales fabricantes de hardware IoT
para constructoras que buscan evitar el "vendor lock-in",
lograremos reducir el costo de adquisición de clientes mediante un ecosistema abierto.
Sabremos que tuvimos éxito cuando veamos una disminución del 15% en el CAC (Costo de Adquisición de Clientes).

- Creemos que ofreceremos una "Prueba de Concepto" (PoC) digital y simulada
para tomadores de decisiones en empresas inmobiliarias,
lograremos reducir el riesgo percibido y acelerar la aprobación de presupuestos.
Sabremos que tuvimos éxito cuando veamos que el 25% de los proyectos piloto se convierten en contratos anuales.

- Creemos que integraremos nuestra plataforma modular como un valor agregado desde los planos
para constructoras que necesitan diferenciar su oferta inmobiliaria,
lograremos aumentar el valor comercial de las propiedades vendidas.
Sabremos que tuvimos éxito cuando veamos un incremento del 25% en los ingresos por licencias B2B semestrales.

- Creemos que implementaremos un constructor visual de espacios inteligentes
para inmobiliarias en fase de preventa,
lograremos que los compradores finales visualicen y personalicen la tecnología de su futuro hogar.
Sabremos que tuvimos éxito cuando veamos que el ciclo de venta de los departamentos se reduce en un 15%.

- Creemos que simplificaremos el proceso de instalación modular de kits IoT
para empresas constructoras con cronogramas ajustados,
lograremos que la entrega de proyectos tecnológicos sea hasta un 40% más rápida.
Sabremos que tuvimos éxito cuando veamos el cumplimiento del 100% de los hitos técnicos en los cronogramas de obra.

- Creemos que proporcionaremos un sistema de post-venta digital y predictivo
para constructoras que desean reducir sus costos de garantía,
lograremos identificar fallos en dispositivos antes de que el residente reporte una queja.
Sabremos que tuvimos éxito cuando veamos una reducción del 60% en los reclamos por garantías técnicas.

#### 1.2.2.4. Lean UX Canvas.

![Lean UX Canvas](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%201/Lean_UX_Canvas.png)

## 1.3. Segmentos objetivo.

| | Segmento 1 | Segmento 2 |
| - | - | - |
| **Variables** | **Arquitectos e Ingenieros Civiles** | **Dueños de apartamentos (usuarios finales)** |
| **Geográfica** | Principalmente en áreas urbanas de **alto crecimiento inmobiliario** en Latinoamérica, como ciudades capitales (Bogotá, Lima, Ciudad de México), donde la demanda de proyectos de construcción, como torres de apartamentos, es intensiva. | Residentes en zonas urbanas densamente pobladas, como **distritos centrales o suburbanos** de grandes ciudades. Priorizan la accesibilidad a servicios y transporte en regiones con un mercado inmobiliario activo. |
| **Demográfica** | **Edad:** 30-55 años; **Género:** Predominantemente masculino, pero con creciente participación femenina; **Educación:** Título universitario en arquitectura, ingeniería civil o afines; **Ingresos:** Medio-alto (profesionales independientes o empleados en firmas); **Estado civil:** Mayoría casados o en unión libre, con o sin hijos. | **Edad:** 25-45 años; **Género:** Mixto; **Educación:** Nivel universitario o técnico; **Ingresos:** Medio a medio-alto; **Estado civil:** Solteros, parejas jóvenes o familias pequeñas; **Ocupación:** Profesionales urbanos, empleados o emprendedores. |
| **Psicológica** | Orientados a la **innovación y sostenibilidad**, valoran la eficiencia, la **funcionalidad estructural** y la diferenciación competitiva. Personalidad meticulosa y colaborativa, motivados por el impacto en el mercado y la adopción de tendencias tecnológicas para mejorar diseños y la viabilidad del proyecto. | Buscadores de **comodidad y seguridad**. Tienen una actitud práctica hacia la tecnología (desde entusiastas a cautelosos). Valoran la conveniencia diaria y la privacidad. Su estilo de vida es urbano y dinámico, con énfasis en el equilibrio entre trabajo y vida personal, así como el ahorro de tiempo. |
| **Función de comportamiento** | Alta frecuencia en la integración de tendencias tecnológicas en diseños y estructuras. Lealtad a herramientas y marcas que faciliten la **colaboración entre diseño y cálculo estructural** (software BIM, CAD, etc.). Buscan soluciones que optimicen costos, mantenimiento y la **seguridad de la construcción**. Se frustran por barreras regulatorias o la falta de compatibilidad tecnológica. Su objetivo es diferenciar proyectos y asegurar la **viabilidad técnica y estructural**. | Uso ocasional a diario de apps para el hogar. La adopción se basa en la **facilidad de uso y la seguridad**. Son leales a marcas intuitivas. Se frustran por la complejidad técnica o problemas de privacidad. Sus objetivos son automatizar rutinas, mejorar la seguridad y la eficiencia energética en su apartamento. |

---
<div style="page-break-before: always;"></div>

---
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.
| Competitive Analysis Landscape                          |   |
| ------------------------------------------------------- | - |
| ¿Por qué llevar a cabo este análisis?                   | El objetivo es identificar oportunidades de mejora y diferenciación frente a los principales competidores en el ecosistema de soluciones orientadas al monitoreo y optimización del consumo energético en el hogar, considerando tecnologías de hardware inteligente, plataformas digitales y servicios de automatización. |

|  |  | IoBuild (Nosotros) ![IoBuild](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/iobuild_logo.png)  | MWF Solutions ![MWF Solutions](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/mwf_solutions_logo.jpeg) | Orvibo Perú ![Orvibo](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/orvibo_logo.jpg) | Domotec Perú ![Domotec Perú](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/domotec_logo.png) |
| - | - | - | - | - | - |
| PERFIL | Overview | Startup que transforma edificios y espacios en entornos inteligentes, accesibles y personalizables. Ofrece una plataforma digital sencilla para constructoras, arquitectos y propietarios, facilitando la integración de soluciones smart. | Empresa líder en soluciones multitécnicas. Especialistas en diseño, ejecución y mantenimiento de proyectos de ingeniería. | Empresa dedicada a soluciones de domótica y automatización de hogares. | Especialistas en convertir hogares y edificios en Smart Home, ofreciendo control desde dispositivos móviles y asistentes de voz. |
|  | Ventaja competitiva ¿Qué valor ofrece a los clientes? | Enfoque low-barrier: integración simplificada, costos accesibles y experiencia de usuario unificada. Prioriza la personalización, escalabilidad y eficiencia energética. | Equipo de ingenieros altamente capacitados. Experiencia comprobada en proyectos exitosos. Alta calidad, eficiencia energética y estándares internacionales. Partner estratégico en todas las fases del proyecto (diseño, ejecución, mantenimiento). | Ofrecen soluciones completas de domótica personalizadas para hogares y empresas. Control y monitoreo fácil desde app, voz y diversos equipos smart. | Soluciones profesionales, completas y fáciles de usar. Integración con asistentes de voz (Apple, Alexa, Google). Garantizan la ciberseguridad y control centralizado de todos los dispositivos. |
| Perfil de marketing | Mercado Objetivo | Constructoras que buscan diferenciarse con proyectos inteligentes sin complejidad tecnológica. Propietarios que desean personalizar y gestionar sus hogares de manera práctica y accesible. | Empresas constructoras de oficinas, edificaciones industriales, comerciales y residenciales que necesiten ingeniería multitécnica. | Oficinas y hogares interesados en automatización y domótica. | Hogares, edificios, hoteles y oficinas interesados en automatización y modernización smart. |
|  | Estrategia de Marketing | Redes sociales (Facebook, Instagram, Youtube, Linkedin). Marketing de contenidos (demos). | Activos en Facebook, Linkedin, Instagram y Youtube. Promoción de servicios, casos de éxito, y artículos de ingeniería. | Redes sociales (Facebook, Instagram, Youtube). Promocionan productos y nuevas tecnologías en publicaciones. | Redes sociales (Facebook, Instagram, Linkedin). Enfocados en la experiencia de usuario y difusión de soluciones smart. |
| Perfil del producto | Productos y servicios | Control unificado de iluminación, clima, seguridad, riego y energía. Funcionalidades avanzadas: escenas personalizadas, reportes de consumo, permisos multiusuario, integración con Alexa/Google Home. | Aire acondicionado, ventilación, clima, seguridad electrónica, domótica, automatización, energía, instalación eléctrica, sistemas contra incendio, refrigeración, mantenimiento. | Smart film, cortinas inteligentes, gestión y ahorro de energía, seguridad smart, equipos Sonoff, luces smart, audio y jardín smart. | Cerraduras inteligentes, cortinas inteligentes, iluminación inteligente, seguridad, redes unificadas, interfaces y soluciones de automatización personalizadas. |
|  | Precios y costos | B2B: licencias por proyecto + servicios de integración. Instalación inicial con costo fijo ajustado al proyecto. B2C: suscripción mensual/anual según tamaño del espacio. | Cotización personalizada, generalmente modelo de proyecto a medida (no disponible en línea). | Servicios personalizados. Contacto para cotización (no disponible en línea), según la selección del cliente. | Servicios personalizados. Contacto para cotización. Ventas por proyecto, cada solución es a medida. |
|  | Canales de distribución (Web y/o Móvil) | Plataforma web y aplicación móvil. Contacto directo vía sitio web, WhatsApp, correo y redes sociales. | Web, contacto vía sitio, redes sociales, WhatsApp, correo y móvil para atención y soporte. | Web, contacto por teléfono, correo, WhatsApp y redes sociales. | Web, WhatsApp, contacto por teléfono y atención presencial. |
### 2.1.2. Estrategias y tácticas frente a competidores.
| Competidores |  | Nosotros | MWF Solutions | Orvibo Perú | Domotec Perú |
| - | - | - | - | - | - |
| Análisis SWOT | Fortalezas | Modelo de negocio por suscripción (ingresos recurrentes). Alianza directa con constructoras. Servicio integral que incluye instalación, soporte de cableado y plataforma centralizada. Doble interfaz para administradores y residentes. | Experiencia multisectorial y enfoque integral en proyectos. Alta capacidad técnica y cumplimiento de estándares. Amplio portafolio de ingeniería multitécnica. | Propuesta innovadora con soluciones llave en mano para hogares inteligentes. Fácil integración y foco en simplificar la tecnología para el usuario doméstico. | Especialistas en experiencia de cliente smart y conectividad centralizada. Trabajan múltiples verticales (hogares, hoteles, edificios). Alto nivel de integración. |
|  | Debilidades | Alta dependencia del sector construcción e inmobiliario. Ciclo de ventas potencialmente largo con constructoras. Requiere inversión inicial fuerte en tecnología y personal técnico especializado. | Dependencia de proyectos grandes y relaciones comerciales de largo plazo. Escalabilidad condicionada por la naturaleza personalizada de los servicios. | Menor penetración en segmento corporativo. Posible dependencia de marcas externas/globales para domótica. Segmentación principalmente residencial. | Foco avanzado puede limitar llegada a usuarios menos familiarizados. Requiere asesoría y soporte muy personalizado para escalar. |
|  | Oportunidades | Auge de edificios inteligentes como estándar en nuevos proyectos inmobiliarios. Potencial para servicios de valor añadido (mantenimiento predictivo, analítica de datos). Expansión a otros mercados verticales. | Crecimiento de la demanda en modernización de infraestructura y eficiencia energética. Oportunidad de fortalecer soluciones propias de gestión y control. | Tendencia de adopción masiva de IoT y hogares inteligentes en Latinoamérica. Posibilidad de alianzas con desarrolladoras inmobiliarias. Ampliación de servicios postventa y soporte. | Hoteles y edificios buscan modernización. Auge de viviendas premium smart. Potencial de expansión internacional y alianzas con marcas globales. |
|  | Amenazas | Resistencia de constructoras a adoptar modelo por suscripción. Ciberseguridad como riesgo crítico al centralizar el control del edificio. Evolución rápida de estándares/protocolos IoT que exige actualización constante. | Competencia de multinacionales e integradores globales. Cambios regulatorios del sector técnico. Riesgo de obsolescencia rápida de equipos o sistemas. | Entrada de nuevas startups globales con soluciones más económicas o DIY. Cambio rápido de estándares (protocolos, compatibilidad). Piratería tecnológica. | Vulnerabilidad a cambios en protocolos de asistentes de voz o plataformas smart. Volatilidad del mercado inmobiliario. Ciberseguridad como preocupación creciente. |
## 2.2. Entrevistas.

Para comprender a fondo las necesidades, expectativas y frustraciones de nuestros segmentos clave ingenieros y arquitectos de constructoras y propietarios de viviendas o espacios inmobiliarios realizamos entrevistas estructuradas con formularios diseñados específicamente para cada grupo. Las preguntas abiertas permitieron explorar su experiencia en el uso de tecnologías inteligentes, sus prioridades al diseñar o habitar un espacio, y sus percepciones sobre personalización, accesibilidad y eficiencia.

Las entrevistas fueron registradas, resumidas y posteriormente analizadas para identificar patrones de comportamiento y criterios de decisión. Los resultados sirvieron de base para elaborar User Personas, Empathy Maps y User Task Matrices, herramientas que nos permitieron captar con mayor claridad los puntos clave de cada segmento.

Las entrevistas realizadas aportaron información clave para definir los requisitos y guiar el diseño de IoBuild, asegurando que la plataforma responda a las expectativas de constructores y propietarios en la gestión de espacios inteligentes.


### 2.2.1. Diseño de entrevistas.

En esta sección se define la información a recolectar de los segmentos objetivos.

   **Entrevistas Arquitectos/Ingenieros segmento 1**
1. ¿Puede contarme un poco sobre su background profesional, como cuántos años lleva en la arquitectura/ingeniería y qué tipos de proyectos ha liderado?
2. ¿Cuál es su ocupación principal actual y qué habilidades clave utiliza en su rol (por ejemplo, software de diseño como AutoCAD o Revit)?
3. ¿Cuáles son sus objetivos profesionales a corto y largo plazo en el campo de la arquitectura residencial?
4. ¿Cuáles son las mayores frustraciones que enfrenta en su rol actual, y cómo las maneja?
5. ¿Con qué frecuencia incorpora nuevas tendencias tecnológicas en sus diseños arquitectónicos para proyectos residenciales?
6. ¿Cuáles son los factores principales que considera al diseñar torres de apartamentos para satisfacer las demandas actuales del mercado inmobiliario?
7. ¿Cómo equilibra las expectativas de los clientes con los desafíos técnicos y presupuestarios en la planificación de un proyecto residencial?
8. ¿Ha trabajado en proyectos donde los compradores finales hayan solicitado características específicas relacionadas con la automatización del hogar?
9. ¿Qué papel juega la sostenibilidad o la eficiencia energética en sus decisiones de diseño para torres de apartamentos, y cómo priorizar estas características frente a otros elementos?
10. ¿Ha incorporado dispositivos inteligentes en el diseño de torres de apartamentos en los últimos 5 años?
11. ¿Cuáles son los principales desafíos que enfrenta al integrar tecnologías inteligentes en la fase de planificación y diseño de construcciones residenciales?
12. En una escala del 1 al 10, ¿cuánto valor cree que agregaría una integración de tecnologías inteligentes al atractivo general de un proyecto de torre de apartamentos?
13. ¿Cómo imagina que una app web para el control de dispositivos inteligentes podría influir en el proceso de diseño inicial y en la colaboración con otros equipos de la constructora?
14. ¿Consideraría esencial incluir compatibilidad con tecnologías inteligentes en los planos arquitectónicos futuros para diferenciarse de la competencia?
15. ¿Qué consideraciones regulatorias o normativas le preocupan más al planear la incorporación de tecnologías inteligentes en torres de apartamentos?
16. ¿Ha enfrentado problemas de compatibilidad entre sistemas inteligentes y la infraestructura existente en proyectos anteriores?
17. ¿De qué manera cree que una suscripción a una app web para tecnologías inteligentes podría optimizar el mantenimiento post-construcción y la entrega de proyectos a los clientes?
18. En una escala del 1 al 10, ¿cuán factible ve la integración de tecnologías inteligentes en el diseño sin aumentar significativamente los costos de construcción?
19. ¿Qué características específicas de diseño recomendaría para facilitar la adopción de tecnologías inteligentes en torres de apartamentos modernas?

**Entrevistas Propietarios segmento 2**
1. ¿Puede compartir un poco sobre su background, como cuánto tiempo lleva viviendo en apartamentos y qué le motivó a elegir su hogar actual?
2. ¿Cuáles son sus objetivos principales al vivir en un apartamento?
3. ¿Cuáles son las mayores frustraciones con su hogar actual, y cómo las resuelve?
4. ¿Cómo describiría su rutina diaria en su apartamento y qué aspectos de su vida en el hogar le gustaría hacer más fáciles o cómodos?
5. ¿Utiliza actualmente algún dispositivo en su apartamento que se controle desde su teléfono, como luces inteligentes, termostatos o cámaras de seguridad?
6. ¿Ha tenido problemas en el pasado con dispositivos o aplicaciones tecnológicas en su hogar, como dificultades para configurarlos o usarlos?
7. Si pudiera controlar cosas en su apartamento desde una app en su teléfono, ¿qué le gustaría poder hacer y por qué cree que eso mejoraría su día a día?
8. Si su apartamento incluyera una app para controlar dispositivos como luces o seguridad sin costo adicional, ¿la usaría?
9. En una escala del 1 al 10, ¿cuánto influiría la posibilidad de controlar cosas como luces, temperatura o seguridad desde su teléfono en su decisión de comprar un apartamento nuevo?
10. ¿En qué momentos de su día a día le sería más útil controlar cosas de su apartamento desde su teléfono, y por qué?
11. ¿Qué características o funciones le gustaría que tuviera una app para controlar cosas en su apartamento, como alertas, facilidad de uso o conexión con otros servicios?
12. ¿Qué preocupaciones tendría al usar una app para controlar dispositivos en su apartamento, como la privacidad de sus datos, la seguridad o la facilidad para usarla?
13. Si los dispositivos inteligentes ya están instalados en su apartamento, ¿estaría dispuesto a pagar una suscripción mensual por funciones avanzadas en la app, como alertas personalizadas o reportes de energía?

### 2.2.2. Registro de entrevistas.

En este apartado se debe documentar detalladamente cada entrevista realizada a los distintos segmentos
objetivo. Se debe incluir información relevante como el perfil del entrevistado, sus respuestas y los principales
hallazgos obtenidos.

URL de las entrevistas:

**Segmento 1: Arquitectos e Ingenieros Civiles**

| Segmento objetivo #1: Arquitectos/Ingenieros                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                       |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|
| **Entrevista 1:** Javier Maximo Ordoñez Cordova                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                       |
| **Enlace de la entrevista:**       https://youtu.be/l9eikn4YOmw                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                       |
| **Sexo:** Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **Edad**: 59                          |
| **Instante en el que inicia:**              0 minutos y 0 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Duración:** 5 minutos y 7 segundos  |
| **Imagen del entrevistado:**<br>![imagen de entrevistado](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Entrevistdo1.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                       |
| **Resumen de la entrevista:**<br>Javier Ordóñez Córdoba es arquitecto con 30 años de experiencia en el sector. A lo largo de su trayectoria ha ejercido como docente en construcción civil, perito judicial en obras públicas, funcionario en municipalidades en áreas de desarrollo urbano y obras, además de supervisor y residente de proyectos arquitectónicos. Su trabajo está centrado en el diseño de viviendas, departamentos y otras edificaciones, siempre buscando garantizar buenas condiciones de ventilación, iluminación natural y distribución de espacios que favorezcan el bienestar de los usuarios.<br>Considera esencial mantenerse actualizado en el uso de software y herramientas tecnológicas como Revit, que simplifican procesos constructivos y permiten una mejor colaboración. Está abierto a la integración de tecnologías inteligentes en viviendas, como sistemas de iluminación automatizada, accesos inteligentes y control inalámbrico de dispositivos, aunque reconoce que esto incrementa ligeramente los costos de construcción. En cuanto a sostenibilidad, enfatiza la necesidad de priorizar energías renovables, como la solar y la eólica, para reducir la dependencia de fuentes contaminantes y costosas.<br>Entre sus frustraciones destaca la falta de apoyo gubernamental al desarrollo de la arquitectura y los bajos sueldos en comparación con el aporte profesional que se brinda. Pese a ello, se mantiene enfocado en incorporar innovaciones que satisfagan a los usuarios y en fomentar edificaciones modernas, sostenibles y adaptadas a las tendencias actuales del mercado inmobiliario.<br><br>**Datos adicionales del entrevistado:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows <br>**Dispositivo usado con mas frecuencia:** Computadora estacionaria, Laptop, Smartphone<br>**Dispositivo movil prefereido:** Android<br>**Principal medio de contacto:** Apps de colaboración<br>**Herramientas utilizadas:** Revit y software de diseño arquitectónico.<br>**Enfoque de diseño:** Distribución eficiente de espacios, ventilación e iluminación natural.<br>**Tecnologías inteligentes incorporadas:** Iluminación automatizada, accesos inteligentes, control inalámbrico de agua, desagüe y comunicación.<br>**Factores clave en diseño residencial:** Necesidades del usuario, satisfacción del cliente final y adaptación a tendencias tecnológicas.<br>**Motivaciones:** Crear edificaciones sostenibles y modernas, incorporar tecnologías inteligentes, mejorar procesos constructivos con software especializado.<br>**Frustraciones:** Falta de apoyo gubernamental, bajos sueldos en el sector, limitaciones presupuestarias de los clientes.                                                                                        |                                       |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                       |
| **Entrevista 2:** Arturo Velazco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                       |
| **Enlace de la entrevista:**           https://youtu.be/zBm7PVg4cjI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |                                       |
| **Sexo:** Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **Edad:** 57                          |
| **Instante en el que inicia:** 11 minutos y 6 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | **Duración:** 4 minutos y 59 segundos |
| **Imagen del entrevistado:**<br>![imagen de entrevistado](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Entrevistdo3.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                       |
| **Resumen de la entrevista:**<br>Arturo Velasco es ingeniero civil colegiado desde 1994, con más de 30 años de experiencia en el sector construcción, especialmente en proyectos inmobiliarios y multifamiliares. Ha participado en obras de gran envergadura, como la ciudad de Nueva Cuerabamba, una central termoeléctrica y diversos edificios residenciales. Actualmente se desempeña como jefe de producción en una empresa inmobiliaria, donde prioriza la eficiencia en la gestión de obra, la coordinación de planos y tableros eléctricos, así como la integración de sistemas de automatización. En su labor enfatiza la comodidad del cliente, la eficiencia en las instalaciones y la coordinación entre especialidades. Sus objetivos incluyen escalar a puestos de mayor responsabilidad, fundar su propia constructora y aplicar su experiencia en proyectos modernos y altamente competitivos.<br>Entre los principales retos que identifica se encuentran la incompatibilidad de planos, las limitaciones técnicas de contratistas y el incremento de costos al integrar nuevas tecnologías. Reconoce que la automatización de luminarias, audio, cortinas, tomas eléctricas y electrodomésticos aporta un valor agregado de 7 a 8 en el mercado, aunque su adopción en el Perú aún es limitada. Considera viable una implementación progresiva con factibilidad de 6 sobre 10, siempre que no incremente significativamente los costos, y resalta que la clave está en alinear a clientes, constructores y autoridades. Además, señala como factores clave en el diseño residencial la adaptación a las necesidades del cliente, la integración tecnológica, la sostenibilidad y la eficiencia energética, recomendando que toda innovación se implemente de forma práctica y enfocada en la confianza y la eficiencia para los usuarios finales. <br><br>**Datos adicionales del entrevistado:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows  <br>**Dispositivo usado con mas frecuencia:** Laptop  <br>**Dispositivo movil prefereido:** IOS<br>**Principal medio de contacto:** Linkedin <br>**Herramientas utilizadas:** Revit.<br>**Enfoque de diseño:** Optimiza procesos, unifica sistemas y prioriza la eficiencia y satisfacción del cliente. <br>**Tecnologías inteligentes incorporadas:** Uso de BIM (Revit) y automatización en puertas y semáforos, con visión de integración futura. <br>**Factores clave en diseño residencial:** Demanda del mercado, eficiencia energética, seguimiento postventa e innovación progresiva. <br>**Motivaciones:** Centralizar herramientas, mantener competitividad y modernizar la gestión con nuevas tecnologías. <br>**Frustraciones:** Resistencia tecnológica, burocracia estatal, tecnologías inestables y falta de apoyo institucional. |                                       |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                       |
| **Entrevista 3:** Miguel Díaz                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                       |
| **Enlace de la entrevista:**        https://youtu.be/M1nDEEuHymI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                       |
| **Sexo:** Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **Edad:** 31                          |
| **Instante en el que inicia:** 16 minutos y 5 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | **Duración:** 6 minutos y 18 segundos |
| **Imagen del entrevistado:**<br>![imagen de entrevistado](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Entrevistdo4.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                       |
| **Resumen de la entrevista:**<br>Miguel es ingeniero civil con aproximadamente 10 años de experiencia profesional, 3 de ellos en Venezuela y 7 en Perú. Actualmente se desempeña como ingeniero residente en Nexo Ingeniería, empresa enfocada en la construcción de edificios multifamiliares. A lo largo de su trayectoria ha participado en proyectos de remodelaciones residenciales, habilitaciones urbanas, viviendas unifamiliares y plantas industriales. Su labor está centrada en el control de obra, asegurando que los proyectos se ejecuten conforme a los planos aprobados y a los presupuestos establecidos.<br>Considera esencial regirse por el Reglamento Nacional de Edificaciones, que constituye la base normativa para cualquier proyecto, y trabajar en conjunto con arquitectos y desarrolladores inmobiliarios para alinear las tendencias del mercado con las necesidades de los usuarios. Está abierto a la integración de tecnologías inteligentes en departamentos, como sistemas de control de iluminación o seguridad, a los que asigna un alto valor en términos de atractivo comercial. Sin embargo, reconoce que su implementación incrementa inevitablemente los costos, por lo que estima su viabilidad en un nivel medio. Recomienda que los planos que integren estas tecnologías sigan la claridad de los planos eléctricos, de modo que sean comprensibles para diferentes especialistas en obra.<br>Entre las principales dificultades de su rol actual, destaca los procesos burocráticos que surgen cuando se presentan modificaciones en los proyectos, ya que implican nuevos trámites y aprobaciones municipales. A pesar de ello, sostiene que una buena planificación y programación de obra reduce los contratiempos y permite ejecutar proyectos con eficiencia.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows <br>**Dispositivo usado con mas frecuencia:** Laptop<br>**Dispositivo movil prefereido:** Android<br>**Principal medio de contacto:** Email <br>**Herramientas utilizadas:** AutoCAD, Excel, Project, Mathcad.<br>**Ocupación actual:** Ingeniero residente en Nexo Ingeniería.<br>**Enfoque de diseño:** Cumplimiento del Reglamento Nacional de Edificaciones, alineación con tendencias del mercado y satisfacción del cliente final.<br>**Tecnologías inteligentes incorporadas:** Control de iluminación y seguridad.<br>**Motivaciones:** Garantizar calidad y rentabilidad en los proyectos, mantenerse abierto a la innovación tecnológica, mejorar procesos constructivos.<br>**Frustraciones:** Burocracia en modificaciones de obra y lentitud en aprobaciones municipales.                                                                                                                                |                                       |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                       |
| **Entrevista 4:** Jorge Gomez                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                       |
| **Enlace de la entrevista:**     https://www.youtube.com/watch?v=3jIZBLw9X-8                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                       |
| **Sexo:** Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **Error:** 31                         |
| **Instante en el que inicia:** 16 minutos y 5 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | **Duración:** 6 minutos y 18 segundos |
| **Imagen del entrevistado:**<br>![imagen de entrevistado](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Entrevistdo9.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                       |
| **Resumen de la entrevista:**<br>Jorge Gómez es arquitecto con 4 años de experiencia en proyectos residenciales. Actualmente apoya en el desarrollo, coordinación y revisión de diseños en una constructora. Su labor se centra en asegurar que los planos sean funcionales y ejecutables.<br>Considera vital el equilibrio entre estética, funcionalidad y presupuesto. Valora altamente la integración de domótica (iluminación, cerraduras, seguridad) por la modernidad que aportan, pero estima su viabilidad en un nivel medio (5/10) por altos costos y falta de especialistas. Recomienda dejar preparadas las bases de conectividad desde la fase inicial.<br>Entre sus principales frustraciones están los cambios de último momento y la información poco clara, además de la incompatibilidad entre sistemas domóticos. Afronta esto con orden y coordinación constante.<br><br>**Datos adicionales:**<br>**Navegador preferido:** No especificado<br>**Sistema operativo de preferencia:** No especificado<br>**Dispositivo usado con mas frecuencia:** No especificado<br>**Dispositivo movil prefereido:** No especificado<br>**Principal medio de contacto:** No especificado<br>**Herramientas utilizadas:** AutoCAD, Revit, SketchUp.<br>**Ocupación actual:** Arquitecto de apoyo en constructora.<br>**Enfoque de diseño:** Funcionalidad, estética moderna y viabilidad presupuestaria.<br>**Tecnologías inteligentes incorporadas:** Cerraduras, iluminación y seguridad básicas.<br>**Motivaciones:** Ganar experiencia para liderar proyectos multifamiliares a futuro.<br>**Frustraciones:** Cambios de diseño tardíos e incompatibilidad técnica entre sistemas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                       |

**Segmento 2: Dueños de apartamentos**

| Campo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Registro                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------|
| **Entrevista 1:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       Andres Torres Lavandera       |                                        |
| **Enlce de la entrevista:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                        |
| **Sexo:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                Masculino                    |                                        |
| **Edad:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    19 años                  |                                        |
| **Ocupación:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               Estudiante Universitario |                                        |
| **Imagen de entrevista:** <br> ![imagen de entrevistado](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/Entrevistado9.jpeg?raw=true)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                        |
| **Resumen de la entrevista** <br> Andres es un estudiante de la UPC de la carrera de Ingenieria de Software, el nos comento que se hace poco a un departamento para poder tener un poco mas de independencia y por motivos de estudio, tambien le gustaria automatizar ciertos dispositivos que usa en su dia a dia para mayor facilidad, a el le gustaria controlar las luces de su casa, verificar si dejo algun dispositivo encendido y saber el consumo energetico que produce. Tambien le gustaria una app que facilite su dia a dia ya que facilitaria muchos aspectos de su rutina y la automatizacion de los dispositivos que usa le ayudaria a estar mas organizado.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                        |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                        |
| **Entrevista 2:** Angela Alvara1do Ordóñez                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                        |
| **Enlace de la entrevista:**         https://youtu.be/z5K2cowIBxg                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                        |
| **Sexo:** Femenino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | **Edad:** 35                           |
| **Instante en el que inicia:** 27 minutos y 19 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **Duración:** 5 minutos y 18 segundos  |
| **Imagen del entrevistado**:<br>![imagen de entrevistado](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Entrevistdo6.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                                        |
| **Resumen de la entrevista:**<br>Ángela Alvarado Ordóñez es abogada de 35 años y reside desde el 2022 en un departamento en Jesús María, adquirido en 2021 por su ubicación céntrica y el precio accesible. Sus principales objetivos al vivir en un departamento son la comodidad, la seguridad y el acceso a una vivienda que se ajuste a su presupuesto. Su rutina diaria transcurre principalmente fuera de casa debido a su trabajo, por lo que utiliza el departamento sobre todo para descansar, aunque dedica tiempo a actividades como correr por las mañanas. Entre sus frustraciones actuales menciona la falta de consideración de algunos vecinos en la limpieza y uso de áreas comunes, el olor a cigarro en pasillos, la saturación de ascensores en horas pico y la percepción de un control insuficiente por parte del personal de seguridad.<br>Aunque no utiliza dispositivos inteligentes en su hogar, muestra interés en soluciones de domótica orientadas a la seguridad, como cerraduras electrónicas y cámaras en pasillos, así como en el control remoto de luces y electrodomésticos para evitar olvidos. Considera que una aplicación que integre estas funciones sería de gran utilidad, especialmente en las noches y al salir de casa, y asegura que la disponibilidad de esta tecnología influiría significativamente en su decisión de compra de un nuevo departamento. No obstante, expresa preocupaciones en torno a la privacidad, el manejo de datos y los posibles sobrecostos en electricidad, aunque estaría dispuesta a pagar una suscripción mensual si incluye funciones avanzadas como reportes de energía y alertas personalizadas, siempre que su costo guarde relación con la utilidad percibida.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Brave <br>**Sistema operativo de preferencia:** Windows <br>**Dispositivo usado con mas frecuencia:** Laptop <br>**Dispositivo movil prefereido:** Android<br>**Principal medio de contacto:** Email<br>**Personalidad tecnológica:** Cautelosa, interesada en tecnología práctica y segura.<br>**Objetivos principales:** Comodidad, seguridad y precio accesible.<br>**Tecnologías inteligentes de interés:** Cerraduras inteligentes, cámaras en pasillos, control remotode luces y electrodomésticos.<br>**Motivaciones:** Garantizar seguridad, comodidad y evitar preocupaciones por olvidos o accesos nocontrolados.<br>**Frustraciones:** Vecinos poco considerados, olor a cigarro, saturación de ascensores, falta decontrol en seguridad y desorden en áreas comunes.<br>**Preocupaciones:** Privacidad de datos, control de imágenes y posibles sobrecostos de electricidad.<br>**Disposición de pago:** Sí, por suscripción mensual si aporta funciones útiles como reportes de energía y alertas.             |                                        |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                        |
| **Entrevista 3:** Christy Karen Callata Alvarez                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                                        |
| **Enlace de la entrevista:**        https://youtu.be/aDa8HZ03PWQ                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                        |
| **Sexo:** Femenino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | **Edad:** 24                           |
| **Instante en el que inicia:**  32 minutos y 37 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | **Duración:**  4 minutos y 56 segundos |
| **Imagen del entrevistado:**<br>![imagen de entrevistado](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Entrevistdo7.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                                        |
| **Resumen de la entrevista:**<br>Cristi Karen Callata Álvarez vive desde hace menos de un año en un departamento, elegido por el espacio y la cantidad de habitaciones necesarias para compartir. Valora principalmente la tranquilidad de la zona, lo que le permite descansar, aunque reconoce como principal frustración la distancia hacia su centro laboral, que le implica viajes de hasta una hora y veinte minutos. Su rutina diaria transcurre mayormente fuera de casa, por lo que busca que ciertas tareas domésticas se realicen de forma más automática y práctica, como el encendido y apagado de luces. Actualmente no cuenta con dispositivos inteligentes, pero muestra interés en incorporarlos para simplificar su día a día y mejorar la seguridad.<br>Callata considera útil una aplicación que permita controlar luces, cámaras y accesos de manera remota, ya que mejoraría su comodidad y seguridad dentro del hogar. Valora especialmente que la app sea fácil de usar, intuitiva y accesible. Puntúa con un 6 o 7 sobre 10 la influencia de estas funcionalidades en la decisión de adquirir un nuevo apartamento. Reconoce que la principal preocupación sería la seguridad de sus datos personales al usar una aplicación de este tipo. Además, estaría dispuesta a pagar una suscripción mensual por funciones avanzadas, siempre que estas ofrezcan mayores facilidades y control en su vivienda.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows <br>**Dispositivo usado con mas frecuencia:** Laptop<br>**Dispositivo movil prefereido:** Android<br>**Principal medio de contacto:** Apps de colaboración <br>**Personalidad tecnológica:** Interesada, pero aún sin adopción.<br>**Objetivos principales:** Tranquilidad, comodidad y seguridad en el hogar.<br>**Tecnologías inteligentes de interés:** Automatización de luces, cámaras de seguridad conectadas al celular, control de accesos.<br>**Motivaciones:** Ahorrar tiempo, simplificar tareas y reforzar seguridad.<br>**Frustraciones:** Larga distancia al trabajo y tiempo de traslado.<br>**Preocupaciones:** Seguridad y privacidad de datos personales.<br>**Disposición de pago:** Sí, suscripción mensual por funciones avanzadas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                        |


### 2.2.3. Análisis de entrevistas.

|Segemento|Caracteristicas|Objetivos comunes|Caracteristicas subjetivas comunes|
|-|-|-|-|
|Segmento #1: Ingenieros/Arquitectos|**Sexo:** Masculino<br>**Edad:** 29-59 años<br>**Dispositivos:** Laptop/PC con software especializado<br>**Programas:** Revit, AutoCAD, software de diseño arquitectónico, coordinación de planos eléctricos<br>**Canales de información:** Actualización constante en tendencias tecnológicas, uso de correo de forma empresarial<br>**Canales de trabajo:** Colaboración con equipos multidisciplinarios, comunicación y liderazgo|Garantizar eficiencia y calidad en el diseño y ejecución de proyectos residenciales<br><br>Incorporar tecnologías inteligentes y sostenibles en sus proyectos<br><br> Adaptarse a las tendencias del mercado y necesidades del usuario final<br><br>Mejorar procesos constructivos mediante software especializado<br><br>Escalar profesionalmente y/o fundar su propia empresa<br><br> Superar retos técnicos y de coordinación entre especialidades|**Motivación:** Usar tecnología para optimizar proyectos, mostrarlos a más público, personalizar funciones y recibir retroalimentación.<br>**Frustración:** Falta de plataformas flexibles, baja exposición de diseños y trabas técnicas que dificultan la integración tecnológica.|
|Segmento #2: Propietarios de apartamentos|**Sexo:** Mixto <br>**Edad:** 24-63 años <br>**Dispositivos:** Laptop, smartphone, televisores, computadoras<br>**Programas:** Apps de noticias, organización y movilidad , no uso de software profesional<br>**Canales de información:** Redes sociales, aplicaciones móviles, medios digitales<br>**Marcas preferidas:** Samsung, HP, Lenovo, Android, Apple|Priorizar comodidad y seguridad en el hogar<br><br>Optimizar el uso de tecnología para facilitar la vida diaria<br><br>Garantizar privacidad y control de datos personales<br><br>Disposición a pagar por suscripción si aporta valor <br><br>Mejorar la eficiencia y el control de dispositivos en el hogar|**Motivación:** Mejorar la experiencia en el hogar con tecnología interactiva, gestionar dispositivos de forma personalizada, optimizar comodidad y seguridad, y recibir retroalimentación por el uso eficiente.<br>**Frustración:** Carencia de plataformas atractivas y flexibles, limitaciones en dispositivos inteligentes, dificultad de adaptación a cada hogar y barreras técnicas que complican su integración.|

<div style="page-break-before: always;"></div>

## 2.3. Needfinding.

El Needfinding, como proceso de investigación, se enfocó en descubrir las necesidades y frustraciones subyacentes de dos segmentos de usuario clave: arquitectos e ingenieros civiles, representados por Miguel Veramendi; y dueños de apartamentos, representados por Carla Flores. A través de entrevistas cualitativas, se identificaron patrones comunes y específicos que revelaron la necesidad de herramientas tecnológicas para optimizar la colaboración y la gestión de proyectos en el sector de la construcción, así como la demanda de control intuitivo y centralizado en el hogar, priorizando la seguridad y la funcionalidad para el usuario final. Este entendimiento profundo de los deseos y expectativas de los usuarios fue fundamental para sentar las bases de una solución que responda genuinamente a sus requerimientos.

### 2.3.1. User Personas.

En esta sección se elaboraron perfiles representativos, denominados "User Personas", que compilan los rasgos esenciales de los usuarios a partir del estudio cualitativo de entrevistas. Este recurso permite transformar los datos de los individuos en arquetipos comprensibles que guían la estrategia de diseño, facilitando decisiones clave sobre funcionalidades y experiencia de usuario. Se crearon dos perfiles principales para el proyecto: uno correspondiente a arquitectos e ingenieros civiles, y otro vinculado a los dueños de apartamentos.

**Segmento 1: Arquitectos e Ingenieros Civiles**  
<img src="https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/UserPersona_Segmento1.png" width="85%" alt="Imagen User Persona 1">

**Segmento 2: Dueños de apartamentos**
<img src="https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/UserPersona_Segmento2.png" width="85%" alt="Imagen User Persona 2">

<div style="page-break-before: always;"></div>

### 2.3.2. User Task Matrix.

A continuación se presenta el User Task Matrix, elaborado a partir del análisis de las entrevistas realizadas a los dos segmentos clave para el proyecto. Este artefacto permite visualizar las actividades principales que realiza cada tipo de usuario, así como entender la frecuencia con la que las llevan a cabo y el valor que les otorgan. La información obtenida en este análisis resulta fundamental para priorizar las funcionalidades en el desarrollo de la solución digital, garantizando que el diseño responda a las necesidades genuinas de quienes la utilizarán.

| N° | Tarea (Task) | Segmento 1 | Miguel Veramendi | Segmento 2 | Carla Flores |
| --- | ------ | ----------- | ------------ | ----------- | ------------ |
| | Titulo | Importancia | Frecuencia | Importancia | Frecuencia |
| U01 | Revisar el consumo eléctrico en recibos mensuales | Alta | Mensual | Alta | Mensual |
| U02 | Estimar el gasto de dispositivos y equipos utilizados | Alta | Semanal | Media | Ocasionalmente |
| U03 | Coordinar con proveedores o servicios de mantenimiento | Alta | Mensual | Media | Mensual |
| U04 | Supervisar el uso responsable de equipos y recursos | Alta | Semanal | Media | Semanal |
| U05 | Identificar picos de consumo y momentos de mayor gasto | Alta | Semanal | Alta | Semanal |
| U06 | Buscar alternativas de sostenibilidad y eficiencia | Alta | Semanal | Alta | Semanal |
| U07 | Establecer metas de ahorro | Alta | A veces | Alta | Siempre |
| U08 | Comparar consumo entre periodos | Alta | A veces | Media | A veces |
| U09 | Revisar gastos generales del hogar o del proyecto | Alta | Mensual | Alta | Mensual |
| U10 | Asistir a capacitaciones o talleres de actualización | Media | Trimestral | Media | Trimestral |

### 2.3.3. User Journey Mapping.
Con el propósito de obtener una comprensión integral de las necesidades, comportamientos, emociones y principales dificultades de nuestros segmentos de usuario, elaboramos un User Journey Map empleando la herramienta especializada UXPressia. Este ejercicio facilitó la representación clara y empática del recorrido que cada perfil de usuario experimenta, desde la detección de una necesidad inicial hasta la interacción final con el producto o servicio, permitiéndonos identificar oportunidades de mejora y optimización en su experiencia.

La actividad se centró en dos segmentos clave:

1. **Miguel Veramendi:** Arquitecto e ingeniero civil que busca garantizar la viabilidad técnica de los proyectos mediante la integración de tecnologías para lograr diseños más innovadores.
2. **Carla Flores:** Dueña de apartamento que busca soluciones que le permitan automatizar sus rutinas y tener un control sencillo y centralizado sobre sus dispositivos.

Para ambos perfiles se diseñó un mapa que incluye:

- Las fases del proceso.
- Los objetivos del usuario en cada etapa.
- El detalle de acciones realizadas, canales utilizados y emociones experimentadas.
- Los problemas identificados y las oportunidades de mejora a lo largo del recorrido.

Mediante el uso de UXPressia se obtuvo una representación visual clara y dinámica que favorece la toma de decisiones con un enfoque centrado en el usuario. Este proceso no solo profundiza en la comprensión de sus motivaciones y retos, sino que también orienta el diseño de soluciones más pertinentes, empáticas y funcionales para cada perfil identificado.


**Segmento Objetivo #1: Arquitectos e Ingenieros Civiles**  
![Imagen User Journey Mapping 1](assets/UserJourneyMap_Segmento1.png)

**Segmento Objetivo #2: Dueños de apartamentos**  
![Imagen User Journey Mapping 2](assets/UserJourneyMap_Segmento2.png)
### 2.3.4. Empathy Mapping.

Como parte del enfoque de diseño centrado en el usuario, se desarrollaron mapas de empatía (Empathy Maps) para los dos segmentos principales identificados: Propietarios y Constructoras. Esta técnica, introducida por Dave Gray, permite plasmar de manera visual lo que los usuarios piensan, sienten, expresan y hacen en relación con el producto o servicio, facilitando una comprensión más profunda de su experiencia tanto emocional como cognitiva.

Objetivo del Empathy Mapping
El mapa de empatía tiene como finalidad ampliar la visión sobre el usuario más allá de sus conductas observables, explorando sus motivaciones, temores, frustraciones y aspiraciones implícitas. Se trata de una herramienta clave para identificar oportunidades de mejora desde un enfoque cualitativo, complementando los hallazgos obtenidos a través de entrevistas, observaciones y análisis de comportamientos.

<div style="page-break-before: always;"></div>

**Segmento 1:**

<img src="assets/EmpathyMap_Segmento1.png" width="75%" alt="Imagen Empathy Map Segmento 1">

Desglose del Empathy Map 1

Piensa: “Quiero que mis proyectos sean innovadores, pero muchas tecnologías son demasiado costosas.”

Siente: “Me frustra que las regulaciones retrasen la implementación de soluciones sostenibles.”

Dice: “Quiero ofrecer espacios innovadores, sostenibles y seguros.”

Hace: Investiga constantemente nuevas tecnologías y tendencias del mercado.

<div style="page-break-before: always;"></div>

**Segmento 2:**

<img src="assets/EmpathyMap_Segmento2.png" width="75%" alt="Imagen Empathy Map Segmento 2">

Desglose del Empathy Map 2

Piensa: “Si esta solución es confiable, podría integrarla sin problema en mi rutina diaria.”

Siente: “Me frustra cuando una aplicación promete mucho y no cumple con lo que necesito.”

Dice: “Necesito algo fácil de usar, que no me complique más de lo que ya estoy.”

Hace: Prueba aplicaciones o servicios digitales para evaluar su utilidad.

<div style="page-break-before: always;"></div>

### 2.3.5. Big Picture Event Storming.

Para el desarrollo del Big Picture EventStorming, se utilizó la herramienta Miro, que facilitó la colaboración y visualización de los diferentes elementos del proceso. A continuación, se presenta un resumen de los principales componentes identificados durante la sesión de EventStorming:

Primero, se definierón las leyendas para los diferentes elementos que se van a usar en el EventStorming:
![Big-Picture-EventStorming-Leyenda](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-Leyenda.png)
<br>
- **Domain Events:** Representa un hecho del negocio que ya ocurrió y no puede cambiarse.<br>
- **Hotspot Question Improvement:** Señala un punto de incertidumbre, duda o posible conflicto en el proceso. Se utiliza para visibilizar preguntas que aún no tienen respuesta clara, de modo que el equipo pueda discutirlas y mejorarlas más adelante<br>
- **Definition:** Aporta una explicación breve y precisa de un concepto clave dentro del dominio.<br>
- **Actor:** Es la persona, rol u organización que interactúa con el sistema o provoca eventos.<br>
- **Command:** Expresa la intención de realizar una acción en el sistema.<br>
- **Comment:** Sirve para añadir notas, aclaraciones o hipótesis que enriquecen el contexto. No alteran el flujo, pero ayudan a documentar observaciones útiles para futuras discusiones.<br>
- **Policy:** Define una regla de negocio que conecta automáticamente un evento con un comando.<br>
- **External System:** Representa servicios o plataformas externas que interactúan con tu sistema, aunque no las controles directamente.<br>

El event storming permitió identificar de forma colaborativa los eventos clave que marcan el flujo del sistema, desde las interacciones principales de los usuarios hasta los procesos internos que sostienen la experiencia. El proceso se desarrolló siguiendo pasos como el reconocimiento de los domain events, la incorporación de los actores que desencadenan acciones, la definición de los comandos que impulsan dichos eventos y la identificación de las políticas o reglas que guían la dinámica del sistema. A partir de esto se generaron ideas que ayudaron a visualizar cómo se conectan las acciones, qué actores participan en cada etapa y qué resultados se esperan, lo que facilitó comprender mejor la dinámica general y detectar oportunidades de mejora o innovación.
<br>

**Big Picture EventStorming 1:**<br>
Para el desarrollo del primer EventStorming se identifican los domain events, como la creación de un nuevo usuario o la asignación de un departamento. Luego se reconocen los pasos que ejecuta el actor principal (la constructora), como iniciar sesión, acceder a la sección de usuarios y registrar la información. También se muestran las validaciones del sistema, por ejemplo, cuando un departamento ya está asignado, lo que genera una notificación. Finalmente, se plantean preguntas para mejorar el flujo, como cómo mostrar únicamente los departamentos disponibles.
<br>
![Big-Picture-EventStorming-1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-1.png)
<br><br>
**Big Picture EventStorming 2:**<br>
Para el desarrollo del segundo EventStorming se identifican los domain events relacionados con la selección y contratación de un plan, como el inicio del proceso de pago, la confirmación o rechazo del mismo y la activación del plan. El actor principal (la constructora) realiza acciones como acceder al catálogo, elegir un plan y completar el contrato. El sistema interviene validando el pago a través de pasarelas externas y actualizando la cuenta según el resultado. Además, se incluyen notificaciones para informar al usuario y preguntas clave para manejar casos especiales, como qué sucede si el pago falla después de activar el plan.
<br>
![Big-Picture-EventStorming-2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-2.png)
<br><br>
**Big Picture EventStorming 3:**<br>
Para el desarrollo del tercer EventStorming se identifican los domain events relacionados con la gestión de un nuevo proyecto de construcción en la plataforma. El actor principal (la constructora) inicia con la recepción de los requerimientos del cliente, registra el proyecto y carga planos y especificaciones técnicas. Posteriormente, se seleccionan los módulos inteligentes y se realiza la validación con el cliente final. El sistema interviene en la integración con software BIM y dispositivos IoT, así como en la modificación y configuración del proyecto en IoBuild. Finalmente, se aborda la implementación en obra con soporte técnico y se concluye con la transferencia de control al propietario, asegurando que este reciba la gestión de su proyecto.
<br>
![Big-Picture-EventStorming-3](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-3.png)
<br><br>
**Big Picture EventStorming 4:**<br>
Para el desarrollo del cuarto EventStorming se identifican los domain events de monitoreo y configuración de dispositivos, como la generación de reportes, la configuración de parámetros y el envío de alertas. El actor principal (propietario) realiza acciones como iniciar sesión, visualizar el dashboard, seleccionar dispositivos y configurarlos. El sistema valida el estado de los equipos, emite sugerencias y notifica fallas. Finalmente, surgen preguntas clave sobre métricas a considerar, detección de fallas y definición de soluciones.
<br>
![Big-Picture-EventStorming-4](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-4.png)

**Big Picture EventStorming 5**<br>
Para el desarrollo del quinto EventStorming se identifican los domain events de vinculación de dispositivos, como el inicio del emparejamiento, la confirmación o el fallo de la vinculación. El actor principal (propietario) inicia sesión, navega a la sección de dispositivos, selecciona añadir uno nuevo y sigue el proceso de emparejamiento. El sistema valida la vinculación, notifica el resultado y actualiza el panel de control. Surgen preguntas clave sobre cómo manejar errores de emparejamiento y qué información incluir en las notificaciones.
<br>
![Big-Picture-EventStorming-5](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-5.png)


### 2.3.6. Ubiquitous Language.


| Ubiquitous Term | Definición del Dominio Funcional |
| -------- | --------- |
| Client | Empresa constructora o inmobiliaria que contrata la suscripción SaaS para gestionar propiedades y dispositivos. |
| Property Manager | Usuario con rol de administrador de una o varias edificaciones, responsable de la configuración general y supervisión. |
| Resident | Usuario final (dueño o inquilino) que interactúa y controla los dispositivos IoT asignados a su unidad o cuarto específico. |
| Platform Administrator | Operador interno del SaaS, responsable del mantenimiento del sistema, gestión de clientes y configuraciones globales. |
| Property / Building | Edificación física (ej. edificio de apartamentos, condominio) que agrupa múltiples unidades y dispositivos gestionados. |
| Unit | Espacio individual dentro de una propiedad (ej. apartamento, oficina) al cual se le asignan dispositivos y residentes. |
| Device | Cualquier dispositivo físico IoT (termostato, cerradura, sensor) instalado en una unidad y conectado a la plataforma. |
| Device Profile | Plantilla de configuración predefinida para un tipo de dispositivo, que facilita su instalación y aprovisionamiento en masa. |
| Subscription | El plan de servicio contratado por el Cliente que define el acceso a funcionalidades, número de propiedades y dispositivos. |
| Provisioning | Proceso de registrar, configurar y activar un nuevo dispositivo en la plataforma para que sea operativo. |
| Alert | Notificación automática generada por un dispositivo ante un evento predefinido (ej. batería baja, puerta abierta, etc.). |
| Command | Instrucción enviada desde la plataforma a un dispositivo para ejecutar una acción específica (ej. "apagar luz", "ajustar T°"). |
| Telemetry | Flujo de datos y mediciones (ej. temperatura, consumo energético) enviado por un dispositivo hacia la plataforma. |
| Scene / Routine | Conjunto de comandos preconfigurados que se ejecutan sobre uno o varios dispositivos de forma simultánea o programada. |
| Dashboard | Interfaz visual principal que muestra el estado en tiempo real de los dispositivos, alertas y datos relevantes. |
| Device State | El estado operativo actual de un dispositivo, como 'En línea', 'Fuera de línea', 'Batería baja' o 'Error'. |
| Billing Cycle | Periodo recurrente en el que se factura al Cliente por el servicio de la suscripción. |

---
## 2.4. Requirements Specification
### 2.4.1. User Stories.

#### 2.4.1.1. Epics

| Epic ID | Título | Descripción |
|---|---|---|
| EP01 | Landing page informativa | Como visitante del sitio, quiero tener acceso a una plataforma web, para conocer los servicios que brinda la aplicación. |
| EP02 | Gestión de cuentas y acceso | Como ingeniero quiero crear una cuenta para acceder a las funcionalidades de la aplicación |
| EP03 | Internacionalización de la plataforma | Como arquitecto, quiero que la aplicación esté disponible en más de un idioma para seleccionar el idioma de mi preferencia. |
| EP04 | Personalización de espacios inteligentes | Como propietario, quiero personalizar la configuración de mi vivienda y/o edificio, para adaptar el espacio a mis necesidades. |
| EP05 | Gestión de notificaciones | Como propietario, quiero recibir notificaciones relevantes sobre mis proyectos o configuraciones, para mantenerme informado en tiempo real. |
| EP06 | Gestión de perfil de usuario | Como usuario propietario, quiero actualizar la información de mi perfil, para personalizar mi experiencia en la plataforma. |
| EP07 | Dashboard de personalización del espacio | Como propietario, quiero acceder a un dashboard, para supervisar los dispositivos de mi departamento. |
| EP08 | Gestión de clientes y entregables | Como ingeniero, quiero gestionar la información de mis clientes, para mantener un control organizado de los proyectos. |
| EP09 | Gestión de proyectos inteligentes | Como arquitecto, quiero gestionar proyectos de construcción en la plataforma, para integrar funcionalidades inteligentes desde la planificación. |
| EP10 | Seguridad y Privacidad de Datos | Como desarrollador, quiero implementar protocolos de seguridad y privacidad de datos, para proteger la información de los usuarios. |
| EP11 | Gestión de dispositivos inteligentes | Como Desarrollador, quiero implementar un sistema de gestión de dispositivos inteligentes, para que permita registrar, modificar y asignar dispositivos disponibles dentro de un espacio. |
| EP12 | Gestión de energía en tiempo real | Como Desarrollador, quiero implementar un sistema de monitoreo energético, para que los usuarios puedan consultar el uso de energía en sus espacios. |
| EP13 | Gestión de usuarios | Como desarrollador, quiero gestionar a los usuarios de la plataforma, para asegurar un control adecuado de accesos, roles y permisos |
| EP14 | Asistente Inteligente | Como usuario, quiero acceder a un chatbot impulsado por IA para resolver dudas y obtener asistencia sobre la plataforma IoBuild. |
| EP15 | Integración con IA para Dispositivos | Como usuario, quiero utilizar herramientas de IA para facilitar la gestión y optimización de dispositivos conectados, incluyendo escaneo y automatización. |

#### 2.4.1.2. User Stories

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US01</td><td>visitante del sitio</td><td>Alta</td><td>EP01</td></tr>
    <tr><th>Title</th><td colspan="3">Conocer la sección "Sobre Nosotros"</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero conocer la historia y valores de la aplicación, para tener mayor conexión y confianza con la empresa.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Llega a la sección “Sobre Nosotros”</strong><br>Dado que el visitante está explorando la landing page,<br> Cuando llega a la sección “Sobre Nosotros”, <br>Entonces debe visualizar una descripción breve de la historia de IoBuild, su equipo y valores, acompañada de imágenes.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US02</td><td>visitante del sitio</td><td>Media</td><td>EP01</td></tr>
    <tr><th>Title</th><td colspan="3">Consultar los testimonios de clientes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero consultar testimonios de otros clientes, para generar confianza en la propuesta de valor de la start up</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta la sección de testimonios</strong><br>Dado que el visitante accede al sitio web<br>Cuando consulta la sección de testimonios<br>Entonces visualiza opiniones de clientes<br>Y percibe la experiencia de otros usuarios.<br><br><strong>Escenario 2: El visitante desea revisar más testimonios</strong><br>Dado que existen varios testimonios disponibles<br>Cuando el visitante desea revisar más testimonios<br>Entonces el sistema le muestra todos los testimonios</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US03</td><td>visitante del sitio</td><td>Alta</td><td>EP01</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder a la información de contacto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero acceder fácilmente a la información de contacto de IoBuild, para comunicarme en caso de dudas</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta la sección de contacto</strong><br>Dado que el visitante accede a la landing page<br>Cuando consulta la sección de contacto<br>Entonces visualiza información clara como correo y teléfono <br>Y puede identificar rápidamente los medios de comunicación disponibles.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US04</td><td>visitante del sitio</td><td>Alta</td><td>EP01</td></tr>
    <tr><th>Title</th><td colspan="3">Visualizar los servicios principales</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero conocer los servicios que ofrece IoBuild, para entender su propuesta de valor.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Navega a la sección de servicios</strong><br>Dado que el visitante accede a la landing page<br>Cuando navega a la sección de servicios<br>Entonces visualiza una lista de los servicios principales<br><br><strong>Escenario 2: Quiere conocer más sobre un servicio de su interés</strong><br>Dado que el visitante accede a la landing page <br>Cuando quiere conocer más sobre un servicio de su interés<br>Entonces selecciona la opción de “ver más”<br>Y se muestra un texto más completo sobre el servicio seleccionado</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US05</td><td>visitante del sitio</td><td>Alta</td><td>EP02</td></tr>
    <tr><th>Title</th><td colspan="3">Registrarse en la aplicación</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero registrarme en la aplicación, para tener acceso a las funcionalidades de la aplicación</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Se dirige a la parte superior de la página</strong><br>Dado que el visitante accede a la landing page<br>Cuando se dirige a la parte superior de la página<br>Y selecciona la opción registrarse<br>Entonces la aplicación lo redirige al formulario de registro</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US06</td><td>visitante del sitio</td><td>Media</td><td>EP01</td></tr>
    <tr><th>Title</th><td colspan="3">Consultar las preguntas frecuentes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero consultar una sección de preguntas frecuentes, para resolver dudas comunes sin necesidad de contactar a la start up</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Entra a la sección de preguntas frecuentes</strong><br>Dado que el visitante accede a la landing page<br>Cuando entra a la sección de preguntas frecuentes<br>Entonces puede desplegar las respuestas a cada pregunta común<br>Y encuentra información organizada y clara.<br><br><strong>Escenario 2: Revisa la lista de preguntas disponibles</strong><br>Dado que el visitante accede a la sección de preguntas frecuentes<br>Cuando revisa la lista de preguntas disponibles<br>Entonces el sistema debe mostrar múltiples preguntas frecuentes <br>Y cada pregunta debe poder expandirse para visualizar su respuesta correspondiente.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US07</td><td>visitante del sitio</td><td>Media</td><td>EP03</td></tr>
    <tr><th>Title</th><td colspan="3">Seleccionar el idioma de la landing page</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como visitante del sitio, quiero poder encontrar más de un idioma disponible, para poder elegir el idioma de mi preferencia.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Selecciona un idioma distinto</strong><br>Dado que el visitante accede a la landing page<br>Cuando selecciona un idioma distinto<br>Entonces todo el contenido de la landing page debe mostrarse automáticamente en el idioma seleccionado.<br><br><strong>Escenario 2: Vuelve a ingresar al sitio</strong><br>Dado que el visitante seleccionó un idioma previamente<br>Cuando vuelve a ingresar al sitio<br>Entonces la landing page debe mostrarse en el último idioma elegido, sin necesidad de volver a configurarlo.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US08</td><td>usuario</td><td>Alta</td><td>EP07</td></tr>
    <tr><th>Title</th><td colspan="3">Visualizar el dashboard personalizado</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero tener un dashboard personalizado, para visualizar la información relevante de manera rápida y eficiente.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El dashboard se carga</strong><br>Dado que el usuario accede al sistema,<br>Cuando el dashboard se carga,<br>Entonces verá una interfaz con widgets configurables (gráficos, estadísticas, alertas) según sus preferencias.<br><br><strong>Escenario 2: Elige personalizar su dashboard</strong><br>Dado que el usuario tiene acceso a múltiples secciones,<br>Cuando elige personalizar su dashboard,<br>Entonces podrá agregar, eliminar o reorganizar los widgets.<br><br><strong>Escenario 3: Vuelva a acceder</strong><br>Dado que el usuario guarda los cambios en su dashboard,<br>Cuando vuelva a acceder,<br>Entonces verá el dashboard con las configuraciones guardadas.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US09</td><td>ingeniero</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder a los proyectos activos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero tener acceso a los proyectos que se encuentran activos, para poder realizar un seguimiento de su progreso y gestionar los recursos necesarios.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta la lista de proyectos</strong><br>Dado que el ingeniero accede al sistema,<br>Cuando consulta la lista de proyectos,<br>Entonces verá solo los proyectos con estado "activo".<br><br><strong>Escenario 2: Selecciona un proyecto</strong><br>Dado que el ingeniero tiene acceso a los proyectos activos,<br>Cuando selecciona un proyecto,<br>Entonces puede acceder a detalles como el progreso, recursos y métricas del proyecto.<br><br><strong>Escenario 3: Hay cambios en el estado de algún proyecto (e.g., transición a "completado")</strong><br>Dado que el ingeniero está visualizando proyectos activos,<br>Cuando hay cambios en el estado de algún proyecto (e.g., transición a "completado"),<br>Entonces la lista se actualiza automáticamente.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US10</td><td>usuario</td><td>Alta</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder a los dispositivos conectados</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero tener acceso a los dispositivos conectados, para poder monitorear su estado y uso.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta los dispositivos conectados</strong><br>Dado que el usuario accede a la aplicación,<br>Cuando consulta los dispositivos conectados,<br>Entonces verá una lista de dispositivos con su estado actual (activo, inactivo, etc.).<br><br><strong>Escenario 2: Selecciona un dispositivo</strong><br>Dado que el usuario tiene acceso a los dispositivos,<br>Cuando selecciona un dispositivo,<br>Entonces puede ver información detallada sobre su configuración, tipo y uso.<br><br><strong>Escenario 3: Un dispositivo cambia su estado</strong><br>Dado que hay dispositivos conectados,<br>Cuando un dispositivo cambia su estado,<br>Entonces la interfaz se actualiza automáticamente.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US11</td><td>ingeniero</td><td>Media</td><td>EP12</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder a la capacidad de ocupación por proyecto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero tener acceso a la capacidad de ocupación de cada proyecto, para poder analizar el uso de los recursos y planificar de manera eficiente.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta la información de ocupación</strong><br>Dado que el ingeniero accede al sistema,<br>Cuando consulta la información de ocupación,<br>Entonces verá la capacidad de ocupación de cada proyecto, expresada como porcentaje o número de espacios ocupados.<br><br><strong>Escenario 2: Selecciona un proyecto</strong><br>Dado que el ingeniero tiene acceso a los proyectos,<br>Cuando selecciona un proyecto,<br>Entonces puede ver su capacidad de ocupación histórica y proyectada.<br><br><strong>Escenario 3: Cambia su ocupación</strong><br>Dado que un proyecto tiene capacidad de ocupación variable,<br>Cuando cambia su ocupación,<br>Entonces la información se actualiza en tiempo real.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US12</td><td>ingeniero</td><td>Media</td><td>EP12</td></tr>
    <tr><th>Title</th><td colspan="3">Visualizar el gráfico de consumo de energía por hora</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver un gráfico sobre la energía que se consume por hora, para poder evaluar el rendimiento energético de los proyectos en tiempo real.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Visualiza los datos</strong><br>Dado que el ingeniero accede a la sección de consumo energético,<br>Cuando visualiza los datos,<br>Entonces verá un gráfico que muestra el consumo de energía de cada proyecto por hora.<br><br><strong>Escenario 2: Se actualizan los datos de consumo</strong><br>Dado que el gráfico muestra el consumo energético,<br>Cuando se actualizan los datos de consumo,<br>Entonces el gráfico se refresca en tiempo real.<br><br><strong>Escenario 3: Selecciona un rango de tiempo específico</strong><br>Dado que el ingeniero necesita analizar tendencias,<br>Cuando selecciona un rango de tiempo específico,<br>Entonces el gráfico ajusta el intervalo de horas.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US13</td><td>ingeniero</td><td>Media</td><td>EP12</td></tr>
    <tr><th>Title</th><td colspan="3">Visualizar el gráfico de registro de ocupación</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver un gráfico sobre el registro de ocupación, para poder analizar la evolución de la ocupación a lo largo del tiempo.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta los datos históricos</strong><br>Dado que el ingeniero accede a la sección de ocupación,<br>Cuando consulta los datos históricos,<br>Entonces verá un gráfico que representa la evolución de la ocupación de los proyectos a lo largo del tiempo.<br><br><strong>Escenario 2: El ingeniero selecciona diferentes proyectos</strong><br>Dado que el gráfico de ocupación está disponible,<br>Cuando el ingeniero selecciona diferentes proyectos,<br>Entonces puede visualizar la ocupación de cada uno por separado.<br><br><strong>Escenario 3: Se produce un cambio en la ocupación</strong><br>Dado que los datos de ocupación se actualizan con frecuencia,<br>Cuando se produce un cambio en la ocupación,<br>Entonces el gráfico se actualiza automáticamente.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US14</td><td>ingeniero</td><td>Media</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Ver el resumen del proyecto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver un resumen sobre cada proyecto, para saber si está activo, su ubicación y cuántos departamentos están ocupados.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Selecciona un proyecto</strong><br>Dado que el ingeniero accede a los proyectos,<br>Cuando selecciona un proyecto,<br>Entonces verá un resumen con la información clave: estado (activo/inactivo), ubicación y número de departamentos ocupados.<br><br><strong>Escenario 2: Se actualiza algún dato clave del proyecto (e.g., cambio de ubicación o estado)</strong><br>Dado que el ingeniero puede ver el resumen,<br>Cuando se actualiza algún dato clave del proyecto (e.g., cambio de ubicación o estado),<br>Entonces el resumen se actualiza automáticamente.<br><br><strong>Escenario 3: Consulta la lista</strong><br>Dado que el ingeniero tiene acceso a múltiples proyectos,<br>Cuando consulta la lista,<br>Entonces puede ver una visión general de todos los proyectos activos con esta información resumida.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US15</td><td>ingeniero</td><td>Media</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Visualizar los dispositivos y su distribución por tipo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver cuáles son los dispositivos y cómo están distribuidos por tipo, para realizar un análisis más detallado de los recursos disponibles.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta los dispositivos</strong><br>Dado que el ingeniero accede a la sección de dispositivos,<br>Cuando consulta los dispositivos,<br>Entonces verá una lista detallada de todos los dispositivos conectados, clasificados por tipo.<br><br><strong>Escenario 2: Selecciona un tipo específico</strong><br>Dado que los dispositivos están clasificados por tipo,<br>Cuando selecciona un tipo específico,<br>Entonces verá solo los dispositivos de ese tipo.<br><br><strong>Escenario 3: Se agrega o elimina un dispositivo</strong><br>Dado que el ingeniero puede ver la distribución de dispositivos,<br>Cuando se agrega o elimina un dispositivo,<br>Entonces la distribución se actualiza automáticamente.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US16</td><td>usuario</td><td>Media</td><td>EP06</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder al perfil del usuario</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero tener acceso a mi perfil, para ver datos como mi nombre, email, número de teléfono y mi dirección.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta su perfil</strong><br>Dado que el usuario accede a la aplicación,<br>Cuando consulta su perfil,<br>Entonces verá una página o sección con la siguiente información: nombre, email, número de teléfono y dirección.<br><br><strong>Escenario 2: La información de contacto está desactualizada</strong><br>Dado que el usuario está visualizando su perfil,<br>Cuando la información de contacto está desactualizada,<br>Entonces puede identificar qué datos están desactualizados (si es el caso).<br><br><strong>Escenario 3: Realiza un cambio en la información personal</strong><br>Dado que el usuario accede a su perfil,<br>Cuando realiza un cambio en la información personal,<br>Entonces la información se guarda correctamente y se actualiza en la base de datos.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US17</td><td>usuario</td><td>Alta</td><td>EP06</td></tr>
    <tr><th>Title</th><td colspan="3">Edición de Información del Perfil</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero poder editar alguna parte de mi información, como mi email, número de teléfono o dirección, para mantener mis datos actualizados.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Selecciona la opción para editar su información</strong><br>Dado que el usuario accede a su perfil,<br>Cuando selecciona la opción para editar su información,<br>Entonces podrá modificar los siguientes campos: email, número de teléfono y dirección.<br><br><strong>Escenario 2: Hace un cambio en uno de estos campos</strong><br>Dado que el usuario está editando su información,<br>Cuando hace un cambio en uno de estos campos,<br>Entonces la aplicación valida que el formato del email y número de teléfono sea correcto antes de guardar los cambios.<br><br><strong>Escenario 3: Guarda los cambios</strong><br>Dado que el usuario ha editado la información,<br>Cuando guarda los cambios,<br>Entonces recibirá una confirmación de que los datos fueron actualizados exitosamente.<br><br>**Escenario 4: Validación**<br>Dado que el usuario intenta editar un campo,<br>Cuando el campo es obligatorio (por ejemplo, dirección),<br>Entonces se mostrará un mensaje de error si el campo está vacío.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US18</td><td>usuario</td><td>Baja</td><td>EP06</td></tr>
    <tr><th>Title</th><td colspan="3">Ver Imagen que Representa al Usuario</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero poder ver una imagen que me represente, para tener una experiencia más personalizada.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Visualiza la información personal</strong><br>Dado que el usuario accede a su perfil,<br>Cuando visualiza la información personal,<br>Entonces verá una imagen o avatar asociado a su cuenta (si está disponible).<br><br><strong>Escenario 2: Selecciona la opción para editar la foto de perfil</strong><br>Dado que el usuario desea cambiar su imagen,<br>Cuando selecciona la opción para editar la foto de perfil,<br>Entonces podrá cargar una nueva imagen desde su dispositivo.<br><br><strong>Escenario 3: La nueva imagen se guarda</strong><br>Dado que el usuario cambia su imagen de perfil,<br>Cuando la nueva imagen se guarda,<br>Entonces se actualiza correctamente en el perfil y se refleja en todas las pantallas donde se visualiza el avatar del usuario.<br><br>**Escenario 4: Validación**<br>Dado que el usuario no ha subido una imagen de perfil,<br>Cuando no se encuentra una imagen,<br>Entonces se muestra una imagen predeterminada (por ejemplo, un ícono de usuario genérico).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US19</td><td>usuario</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Ver el Rol de la Cuenta</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero poder ver el rol de mi cuenta, para entender qué permisos tengo dentro de la aplicación.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Consulta los detalles de su cuenta</strong><br>Dado que el usuario accede a su perfil,<br>Cuando consulta los detalles de su cuenta,<br>Entonces verá un campo que indica su rol (por ejemplo: "Administrador", "Usuario", "Invitado").<br><br><strong>Escenario 2: El sistema identifica un cambio en el rol</strong><br>Dado que el usuario tiene un rol específico,<br>Cuando el sistema identifica un cambio en el rol,<br>Entonces actualizará la información visible en el perfil en tiempo real.<br><br><strong>Escenario 3: Accede a secciones de la aplicación</strong><br>Dado que el usuario ve su rol,<br>Cuando accede a secciones de la aplicación,<br>Entonces verá solo las opciones que correspondan a su nivel de acceso (por ejemplo, un "Administrador" verá opciones de configuración, mientras que un "Usuario" verá solo las opciones básicas).<br><br>**Escenario 4: Validación**<br>Dado que el rol puede cambiar,<br>Cuando un administrador o un usuario con permisos lo actualiza,<br>Entonces la modificación se refleja inmediatamente en el perfil del usuario.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US20</td><td>ingeniero</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Ver lista de proyectos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver una lista de todos mis proyectos para poder conocer el estado y detalles de cada uno.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El constructor accede a la vista de “Proyectos”</strong><br>Dado que existen proyectos registrados para el constructor,<br>Cuando el constructor accede a la vista de “Proyectos”,<br>Entonces el sistema muestra una lista con todos los proyectos incluyendo imagen, nombre, estado, tasa de ocupación y fecha de creación.<br><br><strong>Escenario 2: El constructor accede a la vista de “Proyectos”</strong><br>Dado que no existen proyectos registrados para el constructor,<br>Cuando el constructor accede a la vista de “Proyectos”,<br>Entonces el sistema muestra un mensaje indicando que no hay proyectos disponibles.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US21</td><td>arquitecto</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Agregar un nuevo proyecto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como arquitecto, quiero agregar un nuevo proyecto para poder registrar nuevos desarrollos inmobiliarios.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El constructor envía la solicitud para agregar el proyecto</strong><br>Dado que el constructor proporciona datos válidos (nombre, imagen, estado, unidades totales, fecha de creación, etc.),<br>Cuando el constructor envía la solicitud para agregar el proyecto,<br>Entonces el sistema crea el proyecto y lo muestra en la lista de proyectos.<br><br><strong>Escenario 2: El constructor envía la solicitud para agregar el proyecto</strong><br>Dado que el constructor proporciona datos inválidos (por ejemplo, nombre vacío o formato incorrecto),<br>Cuando el constructor envía la solicitud para agregar el proyecto,<br>Entonces el sistema rechaza la creación y muestra un mensaje de error.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US22</td><td>arquitecto</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Ver detalles de un proyecto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como arquitecto, quiero ver los detalles de un proyecto específico para poder revisar su información completa.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El constructor selecciona la opción “Ver Detalles” de ese proyecto</strong><br>Dado que el proyecto existe en el sistema,<br>Cuando el constructor selecciona la opción “Ver Detalles” de ese proyecto,<br>Entonces el sistema muestra la información completa del proyecto seleccionado.<br><br><strong>Escenario 2: El constructor intenta acceder a los detalles del proyecto</strong><br>Dado que el proyecto no existe en el sistema,<br>Cuando el constructor intenta acceder a los detalles del proyecto,<br>Entonces el sistema muestra un mensaje de error indicando que el proyecto no se encuentra disponible.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US23</td><td>Arquitecto</td><td>Alta</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Ver Lista de Clientes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Arquitecto, quiero ver una lista de todos los clientes para poder gestionar sus proyectos asociados y el estado de su cuenta.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Arquitecto solicita la lista de clientes</strong><br>Dado que hay clientes en el sistema,<br>Cuando el Arquitecto solicita la lista de clientes,<br>Entonces el sistema devuelve todos los clientes con su Nombre Completo, Proyecto Asociado y Estado de Cuenta,<br>Y el sistema muestra las Acciones disponibles (Ver Perfil e ícono de Configuración/Engranaje).<br><br><strong>Escenario 2: El Arquitecto solicita la lista de clientes</strong><br>Dado que no hay clientes en el sistema,<br>Cuando el Arquitecto solicita la lista de clientes,<br>Entonces el sistema devuelve una lista vacía (o un mensaje indicando "No se encontraron clientes").<br><br><strong>Escenario 3: El Arquitecto ve la lista</strong><br>Dado que hay más clientes que el límite de visualización (ej., 10),<br>Cuando el Arquitecto ve la lista,<br>Entonces el sistema muestra los controles de paginación (número de página, botones siguiente/anterior).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US24</td><td>Ingeniero</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Buscar/Ordenar Clientes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Ingeniero, quiero poder ordenar la lista de clientes por columnas (Nombre Completo, Proyecto Asociado, Estado de Cuenta) para poder encontrar u organizar clientes rápidamente según criterios específicos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Ingeniero hace clic en el ícono de ordenar junto a Nombre Completo</strong><br>Dado que se muestra la lista de clientes,<br>Cuando el Ingeniero hace clic en el ícono de ordenar junto a Nombre Completo,<br>Entonces el sistema ordena la lista alfabéticamente por nombre del cliente (ascendente o descendente).<br><br><strong>Escenario 2: El Ingeniero hace clic en el ícono de ordenar junto a Proyecto Asociado</strong><br>Dado que se muestra la lista de clientes,<br>Cuando el Ingeniero hace clic en el ícono de ordenar junto a Proyecto Asociado,<br>Entonces el sistema ordena la lista por el nombre del proyecto asociado (ascendente o descendente).<br><br><strong>Escenario 3: El Ingeniero hace clic en el ícono de ordenar junto a Estado de Cuenta</strong><br>Dado que se muestra la lista de clientes,<br>Cuando el Ingeniero hace clic en el ícono de ordenar junto a Estado de Cuenta,<br>Entonces el sistema ordena la lista por el estado de la cuenta (ej., Activo, Stand by, Suspendido).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US25</td><td>Arquitecto</td><td>Alta</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Agregar un Nuevo Cliente</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Arquitecto, quiero poder agregar un nuevo cliente para poder registrarlo en el sistema.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Arquitecto proporciona los datos válidos requeridos (ej., Nombre Completo)</strong><br>Dado que el Arquitecto hace clic en el botón + Add Client (Agregar Cliente),<br>Cuando el Arquitecto proporciona los datos válidos requeridos (ej., Nombre Completo),<br>Entonces el sistema crea el nuevo cliente y lo muestra en la lista.<br><br><strong>Escenario 2: El Arquitecto envía el formulario con datos obligatorios faltantes o inválidos</strong><br>Dado que el Arquitecto hace clic en el botón + Add Client (Agregar Cliente),<br>Cuando el Arquitecto envía el formulario con datos obligatorios faltantes o inválidos,<br>Entonces el sistema rechaza la creación y proporciona un mensaje de error.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US26</td><td>Ingeniero</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Ver Perfil del Cliente</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Ingeniero, quiero ver el perfil detallado de un cliente para poder acceder a toda su información y opciones de gestión.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Ingeniero hace clic en el botón de acción View Profile (Ver Perfil)</strong><br>Dado que un cliente existente se muestra en la lista,<br>Cuando el Ingeniero hace clic en el botón de acción View Profile (Ver Perfil),<br>Entonces el sistema navega a la vista detallada del perfil para ese cliente específico.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US27</td><td>Arquitecto</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder a la Configuración del Cliente</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Arquitecto, quiero acceder a la configuración específica de un cliente para poder realizar acciones de gestión como editar o gestionar el estado de su cuenta.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Arquitecto hace clic en el botón de acción ícono de Configuración/Engranaje</strong><br>Dado que un cliente existente se muestra en la lista,<br>Cuando el Arquitecto hace clic en el botón de acción ícono de Configuración/Engranaje,<br>Entonces el sistema muestra un menú o navega a una pantalla con opciones de gestión para ese cliente (ej., Editar, Suspender, Activar, Eliminar).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US28</td><td>ingeniero</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Ver Plan de Suscripción Actual</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver mi plan de suscripción actual y su estado para confirmar los beneficios que tengo y el costo mensual.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El sistema carga la vista</strong><br>Dado que el ingeniero accede a la sección de suscripción,<br>Cuando el sistema carga la vista,<br>Entonces el sistema muestra el nombre del plan actual (Enterprise), su costo total, el estado de la suscripción (Active) y una lista detallada de todos los beneficios incluidos.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US29</td><td>ingeniero</td><td>Baja</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Ver Planes de Suscripción Alternativos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero ver planes de suscripción alternativos (Professional y Starter) para poder comparar sus precios y beneficios con mi plan actual.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El sistema carga la vista</strong><br>Dado que el ingeniero accede a la sección de suscripción,<br>Cuando el sistema carga la vista,<br>Entonces el sistema muestra, junto al plan actual, las tarjetas informativas de los planes Professional y Starter, incluyendo sus costos y sus listas de beneficios específicos.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US30</td><td>arquitecto</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Iniciar Cambio de Plan</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como arquitecto, quiero iniciar el proceso de cambio de plan para poder seleccionar un nivel de servicio diferente que se ajuste mejor a mis necesidades.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El arquitecto hace clic en el botón Change Plan (Cambiar Plan)</strong><br>Dado que el arquitecto se encuentra en la sección de suscripción,<br>Cuando el arquitecto hace clic en el botón Change Plan (Cambiar Plan),<br>Entonces el sistema inicia el flujo para seleccionar un nuevo plan (ej., navegando a una nueva página o mostrando un modal de selección).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US31</td><td>arquitecto</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Renovar Plan Activo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como arquitecto, quiero renovar mi plan actual para asegurar la continuidad del servicio si estoy cerca de la fecha de expiración o si mi plan no está configurado para renovación automática.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El arquitecto hace clic en el botón Renew Plan (Renovar Plan)</strong><br>Dado que el arquitecto tiene un plan activo,<br>Cuando el arquitecto hace clic en el botón Renew Plan (Renovar Plan),<br>Entonces el sistema inicia el proceso de renovación del plan actual (ej., mostrando un resumen de la transacción o confirmando la fecha de renovación).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US32</td><td>ingeniero</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Cancelar Plan Actual</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como ingeniero, quiero cancelar mi plan actual para finalizar mi suscripción al término del ciclo de facturación.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El ingeniero hace clic en el botón Cancel Plan (Cancelar Plan)</strong><br>Dado que el ingeniero tiene un plan activo,<br>Cuando el ingeniero hace clic en el botón Cancel Plan (Cancelar Plan),<br>Entonces el sistema muestra una ventana de confirmación o inicia el flujo de cancelación (ej., pidiendo un motivo de la cancelación antes de confirmarla).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US33</td><td>propietario</td><td>Alta</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Ver Lista de Dispositivos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como propietario, quiero ver una lista de todos los dispositivos registrados para poder monitorear su estado y ubicación.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Ingeniero/Arquitecto accede a la vista de Gestión de Dispositivos</strong><br>Dado que hay dispositivos registrados en el sistema,<br>Cuando el Ingeniero/Arquitecto accede a la vista de Gestión de Dispositivos,<br>Entonces el sistema muestra una lista con el Name (Nombre), Type (Tipo), Location (Ubicación) y Real-time Status (Estado en Tiempo Real) de cada dispositivo.<br>Y el sistema muestra las Actions (Acciones) disponibles (Configuración y Eliminar).<br><br><strong>Escenario 2: El Ingeniero/Arquitecto ve la lista</strong><br>Dado que hay dispositivos con estado "Offline",<br>Cuando el Ingeniero/Arquitecto ve la lista,<br>Entonces el sistema resalta claramente el estado "Offline" (ej., en color rojo) para esos dispositivos.<br><br><strong>Escenario 3: El Ingeniero/Arquitecto hace clic en los íconos de ordenar (flechas) junto a las columnas Name, Type o Location</strong><br>Dado que se muestra la lista de dispositivos,<br>Cuando el Ingeniero/Arquitecto hace clic en los íconos de ordenar (flechas) junto a las columnas Name, Type o Location,<br>Entonces el sistema ordena la lista según el campo seleccionado (ascendente o descendente).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US34</td><td>propietario</td><td>Alta</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Agregar un Nuevo Dispositivo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como propietario, quiero agregar un nuevo dispositivo al sistema para expandir la cobertura de monitoreo y control.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Ingeniero/Arquitecto hace clic en el botón + Add Device (Agregar Dispositivo)</strong><br>Dado que el Ingeniero/Arquitecto está en la vista de Gestión de Dispositivos,<br>Cuando el Ingeniero/Arquitecto hace clic en el botón + Add Device (Agregar Dispositivo),<br>Entonces el sistema presenta un formulario o flujo para ingresar los detalles del nuevo dispositivo (ej., Nombre, Tipo, Ubicación y credenciales de conexión).<br><br><strong>Escenario 2: El formulario es enviado</strong><br>Dado que el Ingeniero/Arquitecto proporciona todos los datos requeridos y válidos,<br>Cuando el formulario es enviado,<br>Entonces el sistema registra el dispositivo, y este aparece en la lista con su estado inicial.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US35</td><td>propietario</td><td>Media</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Editar/Configurar Ajustes de Dispositivo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como propietario, quiero acceder a la configuración específica de un dispositivo para modificar sus parámetros o revisar su información detallada.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Ingeniero hace clic en el ícono de Configuración en la columna de Acciones</strong><br>Dado que un dispositivo está listado,<br>Cuando el Ingeniero hace clic en el ícono de Configuración en la columna de Acciones,<br>Entonces el sistema navega a una vista detallada o abre un modal con la información editable del dispositivo (ej., cambiar nombre, ubicación, parámetros técnicos).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US36</td><td>propietario</td><td>Media</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Eliminar un Dispositivo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como propietario, quiero poder eliminar un dispositivo que ya no está en uso o está defectuoso, para mantener la lista limpia y precisa.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Arquitecto hace clic en el ícono de Eliminar</strong><br>Dado que un dispositivo está listado,<br>Cuando el Arquitecto hace clic en el ícono de Eliminar,<br>Entonces el sistema solicita una confirmación de eliminación.<br><br><strong>Escenario 2: El sistema procesa la solicitud</strong><br>Dado que el Arquitecto ha solicitado la eliminación y confirma la acción,<br>Cuando el sistema procesa la solicitud,<br>Entonces el dispositivo es removido de la lista y se confirma la acción.<br><br><strong>Escenario 3: El Arquitecto solicita la eliminación</strong><br>Dado que un dispositivo está asociado a una función crítica o un tutorial (si aplicara),<br>Cuando el Arquitecto solicita la eliminación,<br>Entonces el sistema rechaza la eliminación y proporciona un mensaje de error indicando la dependencia.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US37</td><td>Usuario</td><td>Media</td><td>EP05</td></tr>
    <tr><th>Title</th><td colspan="3">Gestionar Notificaciones</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero poder activar o desactivar varios tipos de notificaciones para controlar qué alertas recibo del sistema.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Usuario alterna el switch de *Expiration Alerts (Alertas de Expiración)*</strong><br>Dado que la Alerta de Expiración está en un estado (ej., activada),<br>Cuando el Usuario alterna el switch de *Expiration Alerts (Alertas de Expiración)*,<br>Entonces el sistema actualiza el estado de la alerta y guarda la preferencia del Usuario.<br><br><strong>Escenario 2: El Usuario alterna el switch de *System Updates (Actualizaciones del Sistema)*</strong><br>Dado que el Usuario está en la configuración de notificaciones,<br>Cuando el Usuario alterna el switch de *System Updates (Actualizaciones del Sistema)*,<br>Entonces el sistema activa o desactiva las notificaciones de actualizaciones del sistema.<br><br><strong>Escenario 3: El Usuario alterna el switch de *Push Notifications (Notificaciones Push)*</strong><br>Dado que el Usuario está en la configuración de notificaciones,<br>Cuando el Usuario alterna el switch de *Push Notifications (Notificaciones Push)*,<br>Entonces el sistema activa o desactiva las notificaciones que se envían directamente al dispositivo o navegador del Usuario.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US38</td><td>Usuario</td><td>Alta</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Cambiar Contraseña de la Cuenta</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero poder cambiar mi contraseña periódicamente para mantener la seguridad de mi cuenta.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Usuario hace clic en el ícono de configuración junto a *Change Password (Cambiar Contraseña)*</strong><br>Dado que el Usuario está en la sección de Seguridad y Privacidad,<br>Cuando el Usuario hace clic en el ícono de configuración junto a *Change Password (Cambiar Contraseña)*,<br>Entonces el sistema presenta un formulario o flujo para ingresar la contraseña actual y la nueva contraseña (con confirmación).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US39</td><td>Usuario</td><td>Alta</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Gestionar Autenticación de Dos Factores</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero activar o gestionar la Autenticación de Dos Factores (2FA) para añadir una capa extra de seguridad a mi cuenta.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Usuario hace clic en el ícono de configuración junto a *Two-Factor Authentication*</strong><br>Dado que el Usuario está en la sección de Seguridad y Privacidad,<br>Cuando el Usuario hace clic en el ícono de configuración junto a *Two-Factor Authentication*,<br>Entonces el sistema navega a la pantalla de configuración de 2FA (para activarla, desactivarla o generar códigos de respaldo).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US40</td><td>Usuario</td><td>Media</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Gestionar Sesiones Activas</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero ver y gestionar mis sesiones activas para poder cerrar la sesión en dispositivos que ya no uso o que han sido comprometidos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Usuario hace clic en el ícono de configuración junto a *Session Management (Gestión de Sesiones)*</strong><br>Dado que el Usuario está en la sección de Seguridad y Privacidad,<br>Cuando el Usuario hace clic en el ícono de configuración junto a *Session Management (Gestión de Sesiones)*,<br>Entonces el sistema muestra una lista de los dispositivos o ubicaciones con sesiones activas y una opción para cerrarlas individualmente o todas.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US41</td><td>Usuario</td><td>Media</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Añadir Correo Electrónico Alternativo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero añadir una dirección de correo electrónico alternativa para recuperación de cuenta o notificaciones secundarias.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Usuario hace clic en el ícono de configuración junto a *Add Alternate Mail Address*</strong><br>Dado que el Usuario está en la sección de Seguridad y Privacidad,<br>Cuando el Usuario hace clic en el ícono de configuración junto a *Add Alternate Mail Address*,<br>Entonces el sistema presenta un formulario para ingresar la nueva dirección de correo y un proceso de verificación (ej., envío de un enlace de confirmación).</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US42</td><td>Usuario</td><td>Media</td><td>EP06</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder a Ayuda y Soporte</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero acceder rápidamente a las secciones de Soporte para resolver mis dudas o contactar con el equipo de soporte.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El Usuario hace clic en *FAQs*</strong><br>Dado que el Usuario está en la sección de Soporte y Ayuda,<br>Cuando el Usuario hace clic en *FAQs*,<br>Entonces el sistema navega a la página de preguntas frecuentes.<br><br><strong>Escenario 2: El Usuario hace clic en *Contact Support*</strong><br>Dado que el Usuario está en la sección de Soporte y Ayuda,<br>Cuando el Usuario hace clic en *Contact Support*,<br>Entonces el sistema navega a la página o abre un formulario para contactar directamente al equipo de soporte.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US43</td><td>Usuario</td><td>Alta</td><td>EP02</td></tr>
    <tr><th>Title</th><td colspan="3">Registrarse en la plataforma</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero crear una cuenta nueva proporcionando mis datos básicos y seleccionando mi rol, para poder acceder a las funcionalidades de la plataforma.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Hace clic en el botón "Registrarse"</strong><br>Dado que el visitante se encuentra en el formulario de registro y proporciona un correo válido, una contraseña segura y selecciona su rol.<br>Cuando hace clic en el botón "Registrarse".<br>Entonces el sistema crea la cuenta, inicia la sesión automáticamente y redirige al usuario a la pantalla principal.<br><br><strong>Escenario 2: Envía el formulario</strong><br>Dado que el visitante intenta registrarse con un correo electrónico que ya existe en el sistema.<br>Cuando envía el formulario.<br>Entonces el sistema muestra un mensaje de error indicando que el correo ya está en uso.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US44</td><td>Usuario</td><td>Alta</td><td>EP02</td></tr>
    <tr><th>Title</th><td colspan="3">Iniciar Sesión (Login)</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero ingresar mis credenciales (correo y contraseña) para acceder a mi cuenta y utilizar las funciones protegidas.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Hace clic en el botón "Ingresar"</strong><br>Dado que el usuario ingresa un correo y contraseña correctos.<br>Cuando hace clic en el botón "Ingresar".<br>Entonces el sistema valida las credenciales, le otorga acceso y lo redirige al Dashboard correspondiente a su rol.<br><br><strong>Escenario 2: Intenta iniciar sesión</strong><br>Dado que el usuario ingresa un correo no registrado o una contraseña errónea.<br>Cuando intenta iniciar sesión.<br>Entonces el sistema deniega el acceso y muestra un mensaje genérico de error ("Usuario o contraseña incorrectos").</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US45</td><td>Usuario</td><td>Alta</td><td>EP02</td></tr>
    <tr><th>Title</th><td colspan="3">Cerrar Sesión (Logout)</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como Usuario, quiero cerrar mi sesión actual para proteger mi cuenta, especialmente si estoy en un dispositivo compartido.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Selecciona la opción "Cerrar Sesión"</strong><br>Dado que el usuario tiene una sesión activa.<br>Cuando selecciona la opción "Cerrar Sesión".<br>Entonces el sistema invalida su acceso actual y lo redirige a la página de inicio o login pública.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US46</td><td>usuario</td><td>Media</td><td>EP14</td></tr>
    <tr><th>Title</th><td colspan="3">Acceder al Chatbot de Asistencia</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero acceder a un chatbot impulsado por IA para resolver dudas sobre la plataforma IoBuild de manera rápida y eficiente.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Selecciona la opción de chatbot</strong><br>Dado que el usuario accede a la plataforma,<br>Cuando selecciona la opción de chatbot,<br>Entonces se abre una interfaz de chat donde puede escribir preguntas.<br><br><strong>Escenario 2: Envía el mensaje</strong><br>Dado que el usuario escribe una pregunta,<br>Cuando envía el mensaje,<br>Entonces la IA responde con información precisa basada en la documentación de IoBuild.<br><br><strong>Escenario 3: La IA lo detecta</strong><br>Dado que el chatbot no puede resolver una duda compleja,<br>Cuando la IA lo detecta,<br>Entonces sugiere contactar al soporte humano.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US47</td><td>usuario</td><td>Alta</td><td>EP15</td></tr>
    <tr><th>Title</th><td colspan="3">Escanear Dispositivo con Cámara</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero usar la cámara de mi dispositivo para escanear un dispositivo físico y que la IA extraiga automáticamente los parámetros necesarios.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Selecciona la opción de escanear con cámara</strong><br>Dado que el usuario está agregando un dispositivo,<br>Cuando selecciona la opción de escanear con cámara,<br>Entonces se activa la cámara y permite tomar una foto.<br><br><strong>Escenario 2: La IA procesa la imagen mediante OCR</strong><br>Dado que el usuario toma una foto del dispositivo,<br>Cuando la IA procesa la imagen mediante OCR,<br>Entonces extrae parámetros como modelo, serie y configuración inicial.<br><br><strong>Escenario 3: Ocurre</strong><br>Dado que la IA no puede extraer todos los parámetros,<br>Cuando ocurre,<br>Entonces solicita al usuario completar manualmente los campos faltantes.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>US48</td><td>usuario</td><td>Alta</td><td>EP15</td></tr>
    <tr><th>Title</th><td colspan="3">Optimizar automáticamente los dispositivos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como usuario, quiero que el sistema optimice automáticamente los dispositivos conectados para mejorar su rendimiento y eficiencia energética.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: El usuario activa la optimización</strong><br>Dado que hay dispositivos conectados,<br>Cuando el usuario activa la optimización,<br>Entonces la IA analiza el uso y ajusta configuraciones automáticamente.<br><br><strong>Escenario 2: Se completa</strong><br>Dado que la optimización se aplica,<br>Cuando se completa,<br>Entonces el usuario recibe un reporte de los cambios realizados y beneficios obtenidos.<br><br><strong>Escenario 3: El usuario aprueba</strong><br>Dado que la optimización requiere confirmación,<br>Cuando el usuario aprueba,<br>Entonces se aplican los cambios definitivos.</td></tr>
</table>

#### 2.4.1.3. Technical Stories

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS01</td><td>desarrollador</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Listar proyectos por Constructor</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que liste todos los proyectos asociados a un constructor específico, para poder mostrar la vista principal de Proyectos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para listar proyectos filtrados por el identificador del constructor (ej. *builderId*),<br>Cuando la API encuentra uno o más recursos de proyecto que coinciden,<br>Entonces la API responde con **200 OK** y devuelve un arreglo no vacío de recursos de proyecto, cada uno incluyendo los campos: *id, imagen, nombre, estado, tasaDeOcupacion y fechaDeCreacion.*<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para listar proyectos de un constructor,<br>Cuando la API no encuentra recursos que coincidan,<br>Entonces la API responde con **200 OK** y devuelve un arreglo vacío.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS02</td><td>desarrollador</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Crear un Proyecto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero añadir un nuevo proyecto a través de la API para poder implementar la funcionalidad de registro de nuevos desarrollos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud de creación que incluye todos los campos obligatorios y válidos (ej. *nombre, unidadesTotales, fechaDeCreacion*),<br>Cuando la API valida y persiste el nuevo recurso de proyecto exitosamente,<br>Entonces la API responde con **201 Created**, y devuelve la representación del recurso creado (incluyendo *id* y los datos proporcionados).<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud de creación con campos obligatorios faltantes o con valores inválidos (ej. un campo numérico incorrecto),<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload de error que describe los errores de validación específicos.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS03</td><td>desarrollador</td><td>Alta</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Recuperar un Proyecto por ID</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar un proyecto por su *{id}* para poder mostrar la vista de detalles del proyecto.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para un proyecto identificado por *{id}*,<br>Cuando la API encuentra el recurso,<br>Entonces la API responde con **200 OK** y devuelve el recurso de proyecto completo (con todos sus atributos detallados).<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para un proyecto identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error indicando que el proyecto no existe.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS04</td><td>desarrollador</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Actualizar la información de un cliente</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero enviar a la API una solicitud para modificar los datos de un cliente existente, para poder implementar la edición de su perfil y la gestión de su estado de cuenta.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud **PUT** o **PATCH** para actualizar el cliente identificado por *{id}* con datos válidos (ej. un nuevo *accountStatement*),<br>Cuando la API valida y persiste los cambios exitosamente,<br>Entonces la API responde con **200 OK** y devuelve la representación del recurso de cliente actualizado.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud de actualización con campos obligatorios faltantes o que contienen valores inválidos,<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload de error que describe los errores de validación.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para actualizar un cliente con un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS05</td><td>desarrollador</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Eliminar un cliente</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API la eliminación de un cliente por su *{id}*, para poder implementar la funcionalidad de dar de baja clientes que ya no se utilizarán.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud **DELETE** para eliminar un cliente identificado por *{id}*,<br>Cuando la API elimina el recurso exitosamente,<br>Entonces la API responde con **204 No Content** (estándar para eliminación exitosa).<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para eliminar un cliente identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para eliminar un cliente identificado por *{id}* que tiene proyectos activos o dependencias críticas,<br>Cuando la API detecta una restricción de dependencia,<br>Entonces la API responde con **409 Conflict** y un payload de error explicando que la acción fue rechazada debido a dependencias.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS06</td><td>desarrollador</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Soportar ordenación en la lista de clientes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero poder enviar parámetros de ordenación a la API (nombre de columna y dirección), para poder implementar las funcionalidades de Buscar/Ordenar Clientes.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para listar clientes incluyendo parámetros de ordenación válidos (ej. *sort=fullName,desc* o *sort=accountStatement,asc*),<br>Cuando la API procesa los datos y aplica la ordenación,<br>Entonces la API responde con **200 OK** y los clientes son devueltos en el orden especificado.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para listar clientes incluyendo un parámetro de ordenación inválido o una columna no soportada,<br>Cuando la API valida los parámetros de entrada,<br>Entonces la API responde con **400 Bad Request** y un payload de error indicando que el parámetro de ordenación es incorrecto o no está permitido.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS07</td><td>desarrollador</td><td>Alta</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Listar clientes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que liste los clientes, opcionalmente filtrados por estado o nombre, para poder mostrar la vista de la lista de clientes.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para listar clientes, potencialmente incluyendo parámetros de paginación (*límite*, *offset*) y ordenamiento,<br>Cuando la API encuentra uno o más clientes,<br>Entonces la API responde con **200 OK** y devuelve un arreglo de recursos de cliente, incluyendo *id*, *fullName*, *associatedProject* y *accountStatement*, junto con metadatos de paginación.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para listar clientes,<br>Cuando la API no encuentra recursos que coincidan,<br>Entonces la API responde con **200 OK** y devuelve un arreglo vacío.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS08</td><td>desarrollador</td><td>Alta</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Crear un cliente</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero añadir un nuevo cliente a través de la API para poder implementar la funcionalidad de creación de clientes.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud de creación que incluye campos obligatorios (ej. *fullName*),<br>Cuando la API valida y persiste el nuevo cliente exitosamente,<br>Entonces la API responde con **201 Created** y devuelve la representación del recurso de cliente creado (incluyendo *id*).<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud de creación con campos obligatorios faltantes o que contienen valores inválidos,<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload de error que describe los errores de validación.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud de creación para un *fullName* que ya existe,<br>Cuando la API detecta la violación de la restricción de duplicado,<br>Entonces la API responde con **409 Conflict** y un payload de error explicativo.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS09</td><td>desarrollador</td><td>Media</td><td>EP08</td></tr>
    <tr><th>Title</th><td colspan="3">Recuperar un cliente por id</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar un recurso de cliente por su *{id}* para poder implementar la vista detallada del perfil.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para un cliente identificado por *{id}*,<br>Cuando la API encuentra el recurso,<br>Entonces la API responde con **200 OK** y devuelve el recurso de cliente completo.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para un cliente identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS10</td><td>desarrollador</td><td>Alta</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Listar dispositivos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que liste todos los dispositivos, filtrados por ubicación o estado, para poder mostrar la lista de Gestión de Dispositivos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para listar dispositivos,<br>Cuando la API encuentra uno o más recursos de dispositivo,<br>Entonces la API responde con **200 OK** y devuelve un arreglo no vacío de recursos de dispositivo, cada uno incluyendo *id*, *name*, *type*, *location* y *realTimeStatus*.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para listar dispositivos,<br>Cuando la API no encuentra recursos que coincidan,<br>Entonces la API responde con **200 OK** y devuelve un arreglo vacío.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para listar dispositivos filtrados por un parámetro de *status* (ej. “Offline”),<br>Cuando la API filtra los recursos,<br>Entonces la API responde con **200 OK** y devuelve solo los dispositivos que coinciden con el estado solicitado.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS11</td><td>desarrollador</td><td>Media</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Eliminar un dispositivo por id</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que elimine un dispositivo por su *{id}* para poder retirar hardware que ya no se utiliza del sistema.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para eliminar un dispositivo identificado por *{id}*,<br>Cuando la API elimina el recurso exitosamente,<br>Entonces la API responde con **204 No Content** (estándar para eliminación exitosa).<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud para eliminar un dispositivo identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para eliminar un dispositivo identificado por *{id}* que está actualmente en uso o vinculado a datos críticos,<br>Cuando la API detecta una restricción de dependencia,<br>Entonces la API responde con **409 Conflict** y un payload de error explicando la dependencia.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS12</td><td>desarrollador</td><td>Media</td><td>EP09</td></tr>
    <tr><th>Title</th><td colspan="3">Actualizar información de un proyecto</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que actualice la información de un proyecto (nombre, ubicación y descripción) para mantener los datos actualizados en la vista de gestión de proyectos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para actualizar un proyecto identificado por *{id}*, incluyendo campos válidos como *name*, *location* y *description*,<br>Cuando la API valida y persiste los cambios correctamente,<br>Entonces la API responde con **200 OK** y devuelve la representación actualizada del recurso de proyecto.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud de actualización con campos faltantes o valores inválidos,<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload que describe los errores de validación.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para actualizar un proyecto identificado por un *{id}* inexistente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un mensaje de error apropiado.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS13</td><td>desarrollador</td><td>Media</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Actualizar información de un dispositivo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que actualice la información de un dispositivo (nombre y ubicación) para reflejar los cambios en la gestión de dispositivos.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud para actualizar un dispositivo identificado por *{id}*, incluyendo campos válidos como *name* y *location*,<br>Cuando la API valida y persiste los cambios exitosamente,<br>Entonces la API responde con **200 OK** y devuelve el recurso de dispositivo actualizado.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud con campos inválidos o formatos incorrectos,<br>Cuando la API valida la información y detecta errores,<br>Entonces la API responde con **400 Bad Request** y un payload con los detalles del error.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para actualizar un dispositivo con un *{id}* inexistente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un mensaje de error.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS14</td><td>desarrollador</td><td>Alta</td><td>EP11</td></tr>
    <tr><th>Title</th><td colspan="3">Crear un nuevo dispositivo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar a la API que cree un nuevo dispositivo especificando su nombre, tipo y ubicación, para registrar nuevos equipos en el sistema.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud de creación de un dispositivo con los campos obligatorios (*name*, *type*, *location*),<br>Cuando la API valida y persiste el nuevo recurso,<br>Entonces la API responde con **201 Created** y devuelve la representación del dispositivo creado, incluyendo su *id*.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe una solicitud con campos faltantes o datos inválidos,<br>Cuando la API detecta errores de validación,<br>Entonces la API responde con **400 Bad Request** y un payload con los mensajes de error.<br><br><strong>Escenario 3: Variación</strong><br>Dado que se recibe una solicitud para crear un dispositivo con un *name* duplicado,<br>Cuando la API detecta una violación de unicidad,<br>Entonces la API responde con **409 Conflict** y un mensaje explicativo.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS15</td><td>desarrollador</td><td>Alta</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Crear ruta segura y mostrar datos específicos</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero proteger el dashboard de fabricantes para que solo los fabricantes puedan visualizarlo</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que el desarrollador configura una ruta protegida para el rol de fabricante<br>Cuando un usuario con rol válido accede al dashboard<br>Entonces el sistema permite la visualización del contenido del dashboard.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que el desarrollador implementa validación de roles en la ruta protegida<br>Cuando un usuario sin el rol de fabricante intenta acceder al dashboard<br>Entonces el sistema redirige al usuario a una vista alternativa</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS16</td><td>desarrollador</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Obtener suscripción actual</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar la información de la suscripción activa del usuario actual, para mostrar el plan, costo y beneficios en la vista principal de suscripciones.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud GET para recuperar la suscripción del usuario autenticado<br>Cuando la API encuentra una suscripción activa asociada al usuario.<br>Entonces la API responde con **200 OK** y devuelve un objeto con los detalles del plan.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que el usuario no cuenta con una suscripción vigente.<br>Cuando la API procesa la solicitud.<br>Entonces la API responde con **404 Not Found** indicando que no hay plan contratado.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS17</td><td>desarrollador</td><td>Baja</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Listar catálogo de planes</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar la lista de todos los planes de suscripción disponibles en el sistema, para mostrarlos como alternativas en la interfaz de comparación.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud GET al endpoint de catálogo de planes.<br>Cuando la API recupera la configuración de planes disponibles en la base de datos.<br>Entonces la API responde con **200 OK** y devuelve un arreglo de objetos, donde cada uno contiene el nombre del plan, precio mensual y la lista de beneficios específicos.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS18</td><td>desarrollador</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Cambiar plan de suscripción</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero enviar una solicitud para actualizar el plan de suscripción del usuario, para hacer efectivo el cambio de nivel de servicio seleccionado en la interfaz.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud PUT con el identificador del nuevo plan seleccionado.<br>Cuando la API valida que el plan existe y procesa la actualización de la suscripción.<br>Entonces la API responde con **200 OK** y devuelve los detalles de la suscripción actualizada con el nuevo plan.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se intenta cambiar a un plan inválido o no disponible.<br>Cuando la validación de la API falla.<br>Entonces la API responde con **400 Bad** Request indicando que el plan seleccionado no es válido para la transición.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS19</td><td>desarrollador</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Renovar suscripción</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar la renovación de la suscripción actual, para extender la vigencia del servicio cuando el usuario confirma la acción.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud POST al endpoint de renovación para la suscripción actual.<br>Cuando la API procesa el pago o extiende la fecha de expiración exitosamente.<br>Entonces la API responde con **200 OK** y devuelve la suscripción con la nueva fecha de vencimiento actualizada.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que hay un problema con el método de pago o el estado de la cuenta.<br>Cuando el proceso de renovación falla en el backend.<br>Entonces la API responde con **402 Payment Required** o **400 Bad Request** con el detalle del error.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS20</td><td>desarrollador</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Cancelar suscripción</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero solicitar la cancelación de la suscripción activa, para detener la renovación automática y finalizar el servicio al terminar el ciclo.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud DELETE sobre la suscripción activa.o<br>Cuando la API registra la solicitud de cancelación y actualiza el estado a "Cancelled" o "Pending Cancellation".<br>Entonces la API responde con **200 OK** confirmando que la suscripción no se renovará, pero manteniendo el acceso hasta el final del periodo actual si aplica.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS21</td><td>desarrollador</td><td>Alta</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Cambiar contraseña del usuario</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero enviar la contraseña actual y la nueva contraseña del usuario a la API, para actualizar sus credenciales de acceso de forma segura.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud PUT al endpoint de cambio de contraseña que incluye currentPassword y newPassword.<br>Cuando la API verifica que la currentPassword coincide con la almacenada y la newPassword cumple con los requisitos de complejidad.<br>Entonces la API actualiza la contraseña (hashing), responde con **200 OK** y opcionalmente invalida otras sesiones activas o genera un nuevo token.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se intenta cambiar la contraseña proporcionando una currentPassword errónea.<br>Cuando la API detecta que la contraseña actual no coincide con la registrada.<br>Entonces la API responde con **400 Bad Request** con un mensaje indicando que la contraseña actual es inválida.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS22</td><td>desarrollador</td><td>Media</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Solicitar adición de correo alternativo</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero enviar una solicitud para agregar un correo electrónico secundario, para que el backend inicie el proceso de validación y verificación de dicha cuenta.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud POST con un email válido que no está registrado previamente.<br>Cuando la API registra el correo en estado "Pendiente" y dispara el servicio de envío de emails con el código o enlace de verificación.<br>Entonces la API responde con **200 OK** indicando que se ha enviado el correo de confirmación al usuario.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se intenta agregar un correo con formato incorrecto o que ya está en uso por otro usuario.<br>Cuando la API valida la unicidad y el formato del correo.<br>Entonces la API responde con **400 Bad Request**.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS23</td><td>desarrollador</td><td>Alta</td><td>EP02</td></tr>
    <tr><th>Title</th><td colspan="3">Registrar nuevo usuario</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero enviar los datos de registro (nombre, email, password, rol) a la API, para crear una nueva identidad en el sistema y permitir el acceso futuro.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se recibe una solicitud POST con payload válido (email único, password cumple requisitos).<br>Cuando la API persiste el nuevo usuario y encripta la contraseña.<br>Entonces la API responde con **201 Created** y devuelve los datos del usuario creado o un token de acceso inicial.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que se recibe un email que ya está registrado en la base de datos.<br>Cuando la API valida la unicidad del usuario.<br>Entonces la API responde con **409 Conflict** indicando que el recurso ya existe.</td></tr>
</table>

---

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>TS24</td><td>desarrollador</td><td>Alta</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Validar token de sesión</td></tr>
    <tr><th colspan="4">Description</th></tr>
    <tr><td colspan="4">Como desarrollador, quiero que la API valide que el token enviado en los headers es legítimo y no ha expirado, para proteger las rutas privadas.</td></tr>
    <tr><th colspan="4">Acceptance Criteria</th></tr>
    <tr><td colspan="4"><strong>Escenario 1: Flujo principal</strong><br>Dado que se realiza una petición a un recurso protegido con un header Authorization: Bearer {token}.<br>Cuando la API verifica la firma y fecha del token.<br>Entonces la API permite el acceso y devuelve el recurso solicitado.<br><br><strong>Escenario 2: Flujo alterno</strong><br>Dado que el token está caducado o malformado.<br>Cuando la API intenta decodificarlo.<br>Entonces la API responde con **401 Unauthorized** o **403 Forbidden**.</td></tr>
</table>

---

#### 2.4.1.4. Spike Stories

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP01</td><td>Arquitecto de Software</td><td>Alta</td><td>EP12</td></tr>
    <tr><th>Title</th><td colspan="3">Investigar el uso de MQTT vs WebSockets para la telemetría en tiempo real</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Determinar cuál protocolo (MQTT o WebSockets) es más eficiente y escalable en nuestra arquitectura actual para mostrar el consumo de energía en el Dashboard en tiempo real.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Comparativa de latencia, consumo de recursos del servidor y facilidad de integración con el backend actual en ASP.NET Core.<br><strong>Excluye:</strong> Implementación final en producción o el diseño de la interfaz visual del gráfico.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">16 horas / 2 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos (cuadro comparativo de latencia y recursos).</li>
            <li>PoC / prototipo (un script sencillo enviando y recibiendo datos con ambos protocolos).</li>
            <li>Recomendación / decisión técnica.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre cuál protocolo usar.</li>
            <li>[ ] Se entrega evidencia (link al repositorio del PoC / archivo comparativo).</li>
            <li>[ ] Se define la decisión o siguiente paso para la arquitectura.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US08 (Dashboard Personalizado), US12 (Gráfico de Consumo de Energía por Hora).</td></tr>
</table>

<br>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP02</td><td>Desarrollador Backend</td><td>Alta</td><td>EP14</td></tr>
    <tr><th>Title</th><td colspan="3">Evaluar proveedores de LLM para el Asistente Inteligente (Smart Assistant)</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Definir qué proveedor (la API de OpenAI u otros modelos externos) ofrece la mejor relación costo/beneficio y tiempos de respuesta para integrarlo al AssistantAIService.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Evaluación de la API de OpenAI y al menos una alternativa, análisis de costos por token y latencia en respuestas.<br><strong>Excluye:</strong> Entrenamiento de modelos de IA propios o diseño de la interfaz del chat en la aplicación móvil.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">24 horas / 3 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos (cuadro comparativo de tiempos, costos y calidad de respuesta).</li>
            <li>Recomendación / decisión del proveedor a contratar.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre la viabilidad y costos de los proveedores.</li>
            <li>[ ] Se entrega evidencia (link al documento comparativo).</li>
            <li>[ ] Se define la decisión o siguiente paso para integrar la API.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US46 (Acceder al Chatbot de Asistencia), US48 (Optimización Automática de Dispositivos).</td></tr>
</table>

<br>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP03</td><td>Desarrollador Móvil</td><td>Media</td><td>EP15</td></tr>
    <tr><th>Title</th><td colspan="3">Analizar librerías de OCR para el escaneo de dispositivos en Android</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Asegurar que la funcionalidad de extraer parámetros del hardware (MAC address, número de serie) mediante la cámara sea viable usando librerías OCR gratuitas o accesibles en Kotlin.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Búsqueda, prueba y análisis de rendimiento de al menos 2 librerías de OCR compatibles con Android.<br><strong>Excluye:</strong> Integración directa con el backend o diseño final de la pantalla de la cámara en la app.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">16 horas / 2 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos sobre la precisión de las librerías probadas.</li>
            <li>PoC / prototipo (aplicación móvil básica que abra la cámara, lea un texto y lo imprima en pantalla).</li>
            <li>Recomendación / decisión de la librería a usar.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre la viabilidad técnica en Android.</li>
            <li>[ ] Se entrega evidencia (link al repositorio del prototipo móvil).</li>
            <li>[ ] Se define la decisión o siguiente paso para la app de Kotlin.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US47 (Escanear Dispositivo con Cámara).</td></tr>
</table>

<br>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP04</td><td>Desarrollador Backend</td><td>Media</td><td>EP13</td></tr>
    <tr><th>Title</th><td colspan="3">Explorar la integración de Webhooks de Stripe para la gestión de suscripciones</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Entender cómo Stripe maneja los eventos asíncronos mediante Webhooks para actualizar automáticamente en el sistema el estado de los planes (ej. cancelado por falta de pago).</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Revisión de la documentación de Stripe y prueba de recepción de un evento de pago (exitoso/fallido) en un endpoint local usando herramientas como ngrok o Stripe CLI.<br><strong>Excluye:</strong> Creación del frontend de pagos o implementación del entorno de producción definitivo de facturación.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">16 horas / 2 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos (flujo documentado y diagrama de secuencia simple).</li>
            <li>PoC / prototipo (Endpoint en ASP.NET Core que reciba e imprima el payload de Stripe).</li>
            <li>Recomendación / decisión sobre la estructura final del controlador.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre el formato y seguridad del Webhook.</li>
            <li>[ ] Se entrega evidencia (link al código del endpoint de prueba).</li>
            <li>[ ] Se define la decisión o siguiente paso para la gestión de base de datos.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US31 (Renovar Plan Activo), US32 (Cancelar Plan Actual).</td></tr>
</table>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP05</td><td>Arquitecto de Software</td><td>Alta</td><td>EP12</td></tr>
    <tr><th>Title</th><td colspan="3">Analizar la viabilidad de RabbitMQ vs Apache Kafka para el manejo masivo de telemetría IoT</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Determinar qué message broker (RabbitMQ o Kafka) es más adecuado para procesar ráfagas de millones de lecturas de sensores por minuto de manera asíncrona, sin bloquear la operación de los dispositivos en el sistema de Energy Management.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Pruebas de rendimiento (throughput) simulando lecturas de sensores, evaluación de la latencia y consumo desde el backend en ASP.NET Core.<br><strong>Excluye:</strong> La configuración de clústeres de alta disponibilidad para el entorno de producción final.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">24 horas / 3 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos (cuadro comparativo de rendimiento y escalabilidad).</li>
            <li>PoC / prototipo (un productor simulando sensores y un consumidor procesando mensajes).</li>
            <li>Recomendación / decisión arquitectónica.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre qué broker utilizar para la arquitectura orientada a eventos.</li>
            <li>[ ] Se entrega evidencia (link al repositorio del PoC).</li>
            <li>[ ] Se define la decisión o siguiente paso para integrar el bus de eventos en el backend.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US12 (Gráfico de Consumo de Energía por Hora).</td></tr>
</table>

<br>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP06</td><td>Desarrollador Móvil</td><td>Media</td><td>EP05</td></tr>
    <tr><th>Title</th><td colspan="3">Investigar la implementación de Firebase Cloud Messaging (FCM) para notificaciones push en Android</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Entender cómo integrar FCM nativamente en la aplicación de Kotlin para garantizar la recepción de alertas críticas operativas (ej. umbral de energía superado) incluso con la app en segundo plano.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Configuración básica de un proyecto en Firebase, integración del SDK en Android Studio y recepción de una notificación de prueba.<br><strong>Excluye:</strong> El diseño visual personalizado de las notificaciones o la lógica completa del sistema de alertas en el backend.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">16 horas / 2 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos sobre la configuración necesaria y manejo del ciclo de vida de la app.</li>
            <li>PoC / prototipo (app móvil básica que reciba y muestre una notificación enviada desde la consola de Firebase).</li>
            <li>Recomendación / decisión técnica sobre el manejo de tokens de dispositivos.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre cómo manejar las notificaciones push en Kotlin.</li>
            <li>[ ] Se entrega evidencia (link al repositorio móvil).</li>
            <li>[ ] Se define la decisión o siguiente paso para la conexión con el `Sistema de Alertas` del backend.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US37 (Gestionar Notificaciones).</td></tr>
</table>

<br>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP07</td><td>Desarrollador Backend</td><td>Media</td><td>EP10</td></tr>
    <tr><th>Title</th><td colspan="3">Evaluar alternativas para la implementación de Autenticación de Dos Factores (2FA)</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Definir la mejor estrategia y librería (TOTP estándar como Google Authenticator o servicios de API externos) para añadir la capa extra de seguridad 2FA solicitada en las cuentas de usuario.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Evaluación técnica de generación de claves secretas (Secret Keys), códigos QR y validación de códigos temporales de 6 dígitos en ASP.NET Core.<br><strong>Excluye:</strong> La integración de las pantallas de configuración 2FA en el frontend (web/móvil) o el envío de códigos por SMS/Email.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">16 horas / 2 días</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos (comparativa de librerías .NET para TOTP).</li>
            <li>PoC / prototipo (Endpoint que genere una semilla secreta y valide un código ingresado).</li>
            <li>Recomendación / decisión sobre el flujo de seguridad final.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre qué estándar y librería usar.</li>
            <li>[ ] Se entrega evidencia (link al código del endpoint de prueba).</li>
            <li>[ ] Se define la decisión o siguiente paso para actualizar la entidad User.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US39 (Gestionar Autenticación de Dos Factores).</td></tr>
</table>

<br>

<table>
    <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr>
    <tr><td>SP08</td><td>Desarrollador Frontend</td><td>Baja</td><td>EP06</td></tr>
    <tr><th>Title</th><td colspan="3">Explorar la integración del SDK de Cloudinary para optimización de imágenes</td></tr>
    <tr><th colspan="4">Objetivo</th></tr>
    <tr><td colspan="4"><strong>¿Qué queremos aprender?</strong> Validar cómo integrar directamente el servicio de Cloudinary para cargar fotos (ej. de perfil o proyectos) optimizadas al vuelo, de manera eficiente en la plataforma.</td></tr>
    <tr><th colspan="4">Alcance</th></tr>
    <tr><td colspan="4"><strong>Incluye:</strong> Pruebas del widget/SDK de subida directa de archivos a Cloudinary y recuperación de la URL optimizada para ser guardada en la base de datos MySQL.<br><strong>Excluye:</strong> La configuración de cuotas, roles de seguridad complejos o facturación de la cuenta en producción de Cloudinary.</td></tr>
    <tr><th colspan="4">Timebox</th></tr>
    <tr><td colspan="4">8 horas / 1 día</td></tr>
    <tr><th colspan="4">Entregables</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>Documento de hallazgos sobre la facilidad de uso del SDK y el formato de respuesta.</li>
            <li>PoC / prototipo (Aplicación web/móvil simple con un botón para cargar una imagen local y mostrarla renderizada desde Cloudinary).</li>
            <li>Recomendación / decisión sobre flujos de subida.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Criterios de aceptación</th></tr>
    <tr><td colspan="4">
        <ul>
            <li>[ ] Se responde la pregunta principal sobre el flujo óptimo para carga de archivos.</li>
            <li>[ ] Se entrega evidencia (link al prototipo frontend).</li>
            <li>[ ] Se define la decisión o siguiente paso para los formularios de registro de proyectos y perfiles.</li>
        </ul>
    </td></tr>
    <tr><th colspan="4">Resultado (al cerrar)</th></tr>
    <tr><td colspan="4"><strong>Hallazgos:</strong><br><strong>Decisión:</strong><br><strong>Próximas US impactadas:</strong> US18 (Ver Imagen que Representa al Usuario), US21 (Agregar un nuevo proyecto).</td></tr>
</table>


### 2.4.2. Impact Mapping.

El Impact Mapping es una metodología visual que permite alinear los objetivos estratégicos de un negocio con las acciones concretas de los usuarios y las funcionalidades de un producto digital. A través de una estructura jerárquica en forma de árbol, esta técnica evidencia cómo las metas empresariales se traducen en cambios de comportamiento esperados en los actores clave, así como en los entregables que hacen posible dichos cambios.

En el desarrollo de este proyecto, esta herramienta se empleó para organizar de manera clara la relación entre las metas SMART del modelo digital, los User Personas previamente definidos y las funcionalidades necesarias para alcanzar los objetivos. El trabajo consideró los siguientes elementos:

* Business Goals SMART: metas específicas, medibles y con plazos definidos, orientadas tanto a la adquisición de usuarios como a su retención a largo plazo.

* Actores principales: representados por Miguel Veramendi y Carla Flores, definidos a partir de sus motivaciones y del rol que desempeñan en el uso de la solución.

* Impactos esperados: formulados como comportamientos observables que cada actor debe adoptar para contribuir al logro de los objetivos (por ejemplo, integrar la solución en propuestas de diseño o personalizar espacios del hogar).

* Deliverables funcionales: características o componentes del producto diseñados para generar dichos impactos, como plantillas de propuestas, paneles de métricas o notificaciones guiadas.

El mapa se elaboró bajo un enfoque de diseño centrado en el usuario, apoyado en dinámicas visuales colaborativas que facilitan la alineación entre los objetivos de negocio y el desarrollo técnico de la solución.

"Anexo: Impact Mapping"

https://drive.google.com/drive/folders/1EJW8bNS65Z4DgjwuNBIIRwbDrMOgehws?usp=sharing

**Business Goal 1: Alcanzar 600 suscripciones activas al plan inicial en un periodo de 8 meses.**

Este objetivo constituye el primer hito estratégico para consolidar el modelo de negocio digital. Su enfoque principal está en la captación de usuarios iniciales que permitan validar la propuesta de valor y establecer un flujo de ingresos sostenible durante la fase temprana del proyecto. La meta de alcanzar 600 suscripciones en 8 meses no solo es concreta y medible, sino también viable según el análisis de mercado, y responde a la necesidad de lograr un punto de equilibrio en el corto plazo, asegurando una rápida tracción de la solución.

Además, este objetivo se encuentra alineado con el rol de los actores clave identificados, Miguel Veramendi y Carla Flores, quienes, mediante comportamientos estratégicos como integrar la solución en sus proyectos, utilizarla de manera constante y recomendarla activamente, impulsan el crecimiento de la base de usuarios. En este sentido, se busca evidenciar que el producto aporta valor desde sus primeras etapas, incentivando tanto a profesionales como a usuarios finales a convertirse en promotores orgánicos de la plataforma.

![Impact-Mapping-1](/Assets/Impact-Mapping-1.png)

**Business Goal 2: Automatizar el 70 % de los procesos de personalización en un periodo de 6 meses y aumentar la retención de clientes recurrentes en un 25 % en 9 meses**

Este objetivo está orientado a fortalecer la eficiencia operativa y la sostenibilidad del negocio en el mediano plazo. Tras consolidar una base inicial de usuarios, el siguiente paso consiste en reducir la fricción en la interacción con la solución mediante la implementación de automatizaciones que hagan la experiencia más ágil, intuitiva y atractiva. Alcanzar un 70 % de automatización en los procesos de personalización en un periodo de 6 meses permitirá a los usuarios percibir mayor comodidad y ahorro de tiempo, incrementando así su satisfacción y confianza en la plataforma.

De forma complementaria, se plantea aumentar la retención de clientes recurrentes en un 25 % en 9 meses, con el objetivo de consolidar relaciones a largo plazo y disminuir la tasa de abandono. Este crecimiento en la retención se sustenta en la mejora continua de la experiencia del usuario, el acompañamiento constante y la entrega de valor tangible a lo largo del tiempo.

En conjunto, este objetivo no solo impulsa la optimización de los procesos internos, sino que también refuerza la viabilidad del modelo de negocio a largo plazo, promoviendo la fidelización de los clientes y su evolución hacia usuarios recurrentes.

![Impact-Mapping-2](/Assets/Impact-Mapping-2.png)




### 2.4.3. Product Backlog.
A continuación, se presenta el Product Backlog, el cual reúne las historias de usuario y las tareas técnicas priorizadas para el desarrollo del proyecto. Cada elemento incluye su identificador, título, descripción y la estimación correspondiente en puntos de historia.

Para la gestión y organización del backlog se utilizó la herramienta Trello, la cual permitió estructurar y visualizar las tareas de forma clara, dinámica y colaborativa. Este backlog se organizó en columnas que representan las distintas etapas del proceso de desarrollo, lo que facilita el seguimiento del avance, la identificación de bloqueos y la adecuada priorización de actividades.

Link de colaboración en trello: https://shorturl.at/FrDjk

![Product-Backlog](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Product_Backlog.png)


| #Orden | User Story ID | Titulo | Descripción | Story Points (1/2/3/5/8) |
|--------|---------------|--------|-------------|--------------------------|
| 1 | TS23 | Registrar nuevo usuario | Como desarrollador, quiero enviar los datos de registro (nombre, email, password, rol) a la API, para crear una nueva identidad en el sistema y permitir el acceso futuro [1]. | 5 |
| 2 | TS24 | Validar token de sesión | Como desarrollador, quiero que la API valide que el token enviado en los headers es legítimo y no ha expirado, para proteger las rutas privadas [1]. | 3 |
| 3 | US43 | Registrarse en la plataforma | Como Usuario, quiero crear una cuenta nueva proporcionando mis datos básicos y seleccionando mi rol, para poder acceder a las funcionalidades de la plataforma [8]. | 5 |
| 4 | US44 | Iniciar Sesión (Login) | Como Usuario, quiero ingresar mis credenciales (correo y contraseña) para acceder a mi cuenta y utilizar las funciones protegidas [9]. | 3 |
| 5 | US45 | Cerrar Sesión (Logout) | Como Usuario, quiero cerrar mi sesión actual para proteger mi cuenta, especialmente si estoy en un dispositivo compartido [9]. | 2 |
| 6 | US05 | Registrarse en la aplicación | Como visitante del sitio, quiero registrarme en la aplicación, para tener acceso a las funcionalidades de la aplicación [10]. | 3 |
| 7 | TS21 | Cambiar contraseña del usuario | Como desarrollador, quiero enviar la contraseña actual y la nueva contraseña del usuario a la API, para actualizar sus credenciales de acceso de forma segura [2]. | 5 |
| 8 | US38 | Cambiar Contraseña de la Cuenta | Como Usuario, quiero poder cambiar mi contraseña periódicamente para mantener la seguridad de mi cuenta [11]. | 5 |
| 9 | SP07 | Evaluar alternativas para la implementación de Autenticación de Dos Factores (2FA) | Como desarrollador backend, quiero definir la mejor estrategia y librería para añadir la capa extra de seguridad 2FA solicitada en las cuentas de usuario. | 3 |
| 10 | US39 | Gestionar Autenticación de Dos Factores | Como Usuario, quiero activar o gestionar la Autenticación de Dos Factores (2FA) para añadir una capa extra de seguridad a mi cuenta [11]. | 3 |
| 11 | TS22 | Solicitar adición de correo alternativo | Como desarrollador, quiero enviar una solicitud para agregar un correo electrónico secundario, para que el backend inicie el proceso de validación y verificación de dicha cuenta [1]. | 5 |
| 12 | US41 | Añadir Correo Electrónico Alternativo | Como Usuario, quiero añadir una dirección de correo electrónico alternativa para recuperación de cuenta o notificaciones secundarias [8]. | 5 |
| 13 | US40 | Gestionar Sesiones Activas | Como Usuario, quiero ver y gestionar mis sesiones activas para poder cerrar la sesión en dispositivos que ya no uso o que han sido comprometidos [11]. | 8 |
| 14 | US16 | Acceder al perfil del usuario | Como usuario, quiero tener acceso a mi perfil, para ver datos como mi nombre, email, número de teléfono y mi dirección [17]. | 3 |
| 15 | US17 | Editar la información del perfil | Como usuario, quiero poder editar alguna parte de mi información, como mi email, número de teléfono o dirección, para mantener mis datos actualizados [17]. | 3 |
| 16 | SP08 | Explorar la integración del SDK de Cloudinary para optimización de imágenes | Como desarrollador frontend, quiero validar cómo integrar directamente el servicio de Cloudinary para cargar fotos optimizadas al vuelo, de manera eficiente en la plataforma. | 2 |
| 17 | US18 | Ver Imagen que Representa al Usuario | Como usuario, quiero poder ver una imagen que me represente, para tener una experiencia más personalizada [17]. | 3 |
| 18 | US19 | Ver el Rol de la Cuenta | Como usuario, quiero poder ver el rol de mi cuenta, para entender qué permisos tengo dentro de la aplicación [12]. | 5 |
| 19 | US42 | Acceder a Ayuda y Soporte | Como Usuario, quiero acceder rápidamente a las secciones de Soporte para resolver mis dudas o contactar con el equipo de soporte [8]. | 8 |
| 20 | TS02 | Crear un Proyecto | Como desarrollador, quiero añadir un nuevo proyecto a través de la API para poder implementar la funcionalidad de registro de nuevos desarrollos [3]. | 2 |
| 21 | TS03 | Recuperar un Proyecto por ID | Como desarrollador, quiero solicitar un proyecto por su {id} para poder mostrar la vista de detalles del proyecto [3]. | 5 |
| 22 | TS01 | Listar proyectos por Constructor | Como desarrollador, quiero solicitar a la API que liste todos los proyectos asociados a un constructor específico, para poder mostrar la vista principal de Proyectos [4]. | 5 |
| 23 | TS12 | Actualizar información de un proyecto | Como desarrollador, quiero solicitar a la API que actualice la información de un proyecto (nombre, ubicación y descripción) para mantener los datos actualizados en la vista de gestión de proyectos [19]. | 8 |
| 24 | US20 | Ver lista de proyectos | Como ingeniero, quiero ver una lista de todos mis proyectos para poder conocer el estado y detalles de cada uno [12]. | 5 |
| 25 | US21 | Agregar un nuevo proyecto | Como arquitecto, quiero agregar un nuevo proyecto para poder registrar nuevos desarrollos inmobiliarios [12]. | 8 |
| 26 | US22 | Ver detalles de un proyecto | Como arquitecto, quiero ver los detalles de un proyecto específico para poder revisar su información completa [12]. | 5 |
| 27 | US14 | Ver el resumen del proyecto | Como ingeniero, quiero ver un resumen sobre cada proyecto, para saber si está activo, su ubicación y cuántos departamentos están ocupados [22]. | 5 |
| 28 | US09 | Acceder a los proyectos activos | Como ingeniero, quiero tener acceso a los proyectos que se encuentran activos, para poder realizar un seguimiento de su progreso y gestionar los recursos necesarios [13]. | 5 |
| 29 | US11 | Acceder a la capacidad de ocupación por proyecto | Como ingeniero, quiero tener acceso a la capacidad de ocupación de cada proyecto, para poder analizar el uso de los recursos y planificar de manera eficiente [16]. | 5 |
| 30 | US13 | Visualizar el gráfico de registro de ocupación | Como ingeniero, quiero ver un gráfico sobre el registro de ocupación, para poder analizar la evolución de la ocupación a lo largo del tiempo [22]. | 5 |
| 31 | US15 | Visualizar los dispositivos y su distribución por tipo | Como ingeniero, quiero ver cuáles son los dispositivos y cómo están distribuidos por tipo, para realizar un análisis más detallado de los recursos disponibles [22]. | 8 |
| 32 | TS08 | Crear un cliente | Como desarrollador, quiero añadir un nuevo cliente a través de la API para poder implementar la funcionalidad de creación de clientes [5]. | 8 |
| 33 | TS07 | Listar clientes | Como desarrollador, quiero solicitar a la API que liste los clientes, opcionalmente filtrados por estado o nombre, para poder mostrar la vista de la lista de clientes [6]. | 5 |
| 34 | TS09 | Recuperar un cliente por id | Como desarrollador, quiero solicitar un recurso de cliente por su {id} para poder implementar la vista detallada del perfil [5]. | 5 |
| 35 | TS04 | Actualizar la información de un cliente | Como desarrollador, quiero enviar a la API una solicitud para modificar los datos de un cliente existente, para poder implementar la edición de su perfil y la gestión de su estado de cuenta [3]. | 8 |
| 36 | TS05 | Eliminar un cliente | Como desarrollador, quiero solicitar a la API la eliminación de un cliente por su {id}, para poder implementar la funcionalidad de dar de baja clientes que ya no se utilizarán [6]. | 5 |
| 37 | TS06 | Soportar ordenación en la lista de clientes | Como desarrollador, quiero poder enviar parámetros de ordenación a la API (nombre de columna y dirección), para poder implementar las funcionalidades de Buscar/Ordenar Clientes [6]. | 8 |
| 38 | US23 | Ver Lista de Clientes | Como Arquitecto, quiero ver una lista de todos los clientes para poder gestionar sus proyectos asociados y el estado de su cuenta [14]. | 5 |
| 39 | US25 | Agregar un Nuevo Cliente | Como Arquitecto, quiero poder agregar un nuevo cliente para poder registrarlo en el sistema [14]. | 3 |
| 40 | US24 | Buscar/Ordenar Clientes | Como Ingeniero, quiero poder ordenar la lista de clientes por columnas (Nombre Completo, Proyecto Asociado, Estado de Cuenta) para poder encontrar u organizar clientes rápidamente según criterios específicos [14]. | 5 |
| 41 | US26 | Ver Perfil del Cliente | Como Ingeniero, quiero ver el perfil detallado de un cliente para poder acceder a toda su información y opciones de gestión [21]. | 8 |
| 42 | US27 | Acceder a la Configuración del Cliente | Como Arquitecto, quiero acceder a la configuración específica de un cliente para poder realizar acciones de gestión como editar o gestionar el estado de su cuenta [21]. | 5 |
| 43 | TS14 | Crear un nuevo dispositivo | Como desarrollador, quiero solicitar a la API que cree un nuevo dispositivo especificando su nombre, tipo y ubicación, para registrar nuevos equipos en el sistema [7]. | 8 |
| 44 | TS10 | Listar dispositivos | Como desarrollador, quiero solicitar a la API que liste todos los dispositivos, filtrados por ubicación o estado, para poder mostrar la lista de Gestión de Dispositivos [5]. | 5 |
| 45 | TS13 | Actualizar información de un dispositivo | Como desarrollador, quiero solicitar a la API que actualice la información de un dispositivo (nombre y ubicación) para reflejar los cambios en la gestión de dispositivos [19]. | 5 |
| 46 | TS11 | Eliminar un dispositivo por id | Como desarrollador, quiero solicitar a la API que elimine un dispositivo por su {id} para poder retirar hardware que ya no se utiliza del sistema [19]. | 3 |
| 47 | US33 | Ver Lista de Dispositivos | Como propietario, quiero ver una lista de todos los dispositivos registrados para poder monitorear su estado y ubicación [15]. | 5 |
| 48 | US34 | Agregar un Nuevo Dispositivo | Como propietario, quiero agregar un nuevo dispositivo al sistema para expandir la cobertura de monitoreo y control [15]. | 8 |
| 49 | US35 | Editar/Configurar Ajustes de Dispositivo | Como propietario, quiero acceder a la configuración específica de un dispositivo para modificar sus parámetros o revisar su información detallada [23]. | 5 |
| 50 | US36 | Eliminar un Dispositivo | Como propietario, quiero poder eliminar un dispositivo que ya no está en uso o está defectuoso, para mantener la lista limpia y precisa [23]. | 8 |
| 51 | US10 | Acceder a los dispositivos conectados | Como usuario, quiero tener acceso a los dispositivos conectados, para poder monitorear su estado y uso [16]. | 5 |
| 52 | SP03 | Analizar librerías de OCR para el escaneo de dispositivos en Android | Como desarrollador móvil (Kotlin), quiero analizar librerías de reconocimiento óptico de caracteres (OCR) compatibles con Android, para asegurar que la funcionalidad de extraer parámetros del hardware mediante la cámara sea viable. | 3 |
| 53 | US47 | Escanear Dispositivo con Cámara | Como usuario, quiero usar la cámara de mi dispositivo para escanear un dispositivo físico y que la IA extraiga automáticamente los parámetros necesarios [9]. | 8 |
| 54 | SP06 | Investigar la implementación de Firebase Cloud Messaging (FCM) para notificaciones | Como desarrollador móvil, quiero entender cómo integrar FCM nativamente en la aplicación de Kotlin para garantizar la recepción de alertas críticas operativas incluso con la app en segundo plano. | 3 |
| 55 | US37 | Gestionar Notificaciones | Como Usuario, quiero poder activar o desactivar varios tipos de notificaciones para controlar qué alertas recibo del sistema [23]. | 5 |
| 56 | TS17 | Listar catálogo de planes | Como desarrollador, quiero solicitar la lista de todos los planes de suscripción disponibles en el sistema, para mostrarlos como alternativas en la interfaz de comparación [20]. | 3 |
| 57 | TS16 | Obtener suscripción actual | Como desarrollador, quiero solicitar la información de la suscripción activa del usuario actual, para mostrar el plan, costo y beneficios en la vista principal de suscripciones [7]. | 3 |
| 58 | US28 | Ver Plan de Suscripción Actual | Como ingeniero, quiero ver mi plan de suscripción actual y su estado para confirmar los beneficios que tengo y el costo mensual [21]. | 8 |
| 59 | US29 | Ver Planes de Suscripción Alternativos | Como ingeniero, quiero ver planes de suscripción alternativos (Professional y Starter) para poder comparar sus precios y beneficios con mi plan actual [24]. | 5 |
| 60 | US30 | Iniciar Cambio de Plan | Como arquitecto, quiero iniciar el proceso de cambio de plan para poder seleccionar un nivel de servicio diferente que se ajuste mejor a mis necesidades [24]. | 2 |
| 61 | SP04 | Explorar la integración de Webhooks de Stripe para la gestión de suscripciones | Como desarrollador backend, quiero explorar cómo Stripe maneja los eventos asíncronos mediante Webhooks, para garantizar que el sistema actualice automáticamente el estado de los planes cuando ocurran cobros exitosos o fallidos. | 3 |
| 62 | TS18 | Cambiar plan de suscripción | Como desarrollador, quiero enviar una solicitud para actualizar el plan de suscripción del usuario, para hacer efectivo el cambio de nivel de servicio seleccionado en la interfaz [20]. | 5 |
| 63 | TS19 | Renovar suscripción | Como desarrollador, quiero solicitar la renovación de la suscripción actual, para extender la vigencia del servicio cuando el usuario confirma la acción [20]. | 3 |
| 64 | TS20 | Cancelar suscripción | Como desarrollador, quiero solicitar la cancelación de la suscripción activa, para detener la renovación automática y finalizar el servicio al terminar el ciclo [2]. | 3 |
| 65 | US31 | Renovar Plan Activo | Como arquitecto, quiero renovar mi plan actual para asegurar la continuidad del servicio si estoy cerca de la fecha de expiración o si mi plan no está configurado para renovación automática [24]. | 5 |
| 66 | US32 | Cancelar Plan Actual | Como ingeniero, quiero cancelar mi plan actual para finalizar mi suscripción al término del ciclo de facturación [15]. | 8 |
| 67 | SP01 | Investigar el uso de MQTT vs WebSockets para la telemetría en tiempo real | Como arquitecto de software, quiero investigar y comparar protocolos de comunicación en tiempo real, para determinar cuál es el más eficiente y escalable para mostrar el consumo de energía en el Dashboard de los proyectos. | 3 |
| 68 | SP05 | Analizar la viabilidad de RabbitMQ vs Apache Kafka para el manejo masivo de telemetría | Como arquitecto de software, quiero determinar qué message broker (RabbitMQ o Kafka) es más adecuado para procesar ráfagas de millones de lecturas de sensores por minuto de manera asíncrona, sin bloquear la operación de los dispositivos. | 5 |
| 69 | TS15 | Crear ruta segura y mostrar datos específicos | Como desarrollador, quiero proteger el dashboard de fabricantes para que solo los fabricantes puedan visualizarlo [7]. | 8 |
| 70 | US08 | Visualizar el dashboard personalizado | Como usuario, quiero tener un dashboard personalizado, para visualizar la información relevante de manera rápida y eficiente [13]. | 5 |
| 71 | US12 | Visualizar el gráfico de consumo de energía por hora | Como ingeniero, quiero ver un gráfico sobre la energía que se consume por hora, para poder evaluar el rendimiento energético de los proyectos en tiempo real [16]. | 8 |
| 72 | US48 | Optimizar automáticamente los dispositivos | Como usuario, quiero que el sistema optimice automáticamente los dispositivos conectados para mejorar su rendimiento y eficiencia energética [4]. | 8 |
| 73 | SP02 | Evaluar proveedores de LLM para el Asistente Inteligente (Smart Assistant) | Como desarrollador backend, quiero evaluar la API de OpenAI y otros modelos externos (ExternalLLMAdapter), para definir qué proveedor ofrece la mejor relación costo/beneficio en la generación de planes de acción y recomendaciones de ahorro energético. | 5 |
| 74 | US46 | Acceder al Chatbot de Asistencia | Como usuario, quiero acceder a un chatbot impulsado por IA para resolver dudas sobre la plataforma IoBuild de manera rápida y eficiente [9]. | 8 |
| 75 | US01 | Conocer la sección "Sobre Nosotros" | Como visitante del sitio, quiero conocer la historia y valores de la aplicación, para tener mayor conexión y confianza con la empresa [18]. | 2 |
| 76 | US02 | Consultar los testimonios de clientes | Como visitante del sitio, quiero consultar testimonios de otros clientes, para generar confianza en la propuesta de valor de la start up [18]. | 5 |
| 77 | US03 | Acceder a la información de contacto | Como visitante del sitio, quiero acceder fácilmente a la información de contacto de IoBuild, para comunicarme en caso de dudas [10]. | 5 |
| 78 | US04 | Visualizar los servicios principales | Como visitante del sitio, quiero conocer los servicios que ofrece IoBuild, para entender su propuesta de valor [10]. | 3 |
| 79 | US06 | Consultar las preguntas frecuentes | Como visitante del sitio, quiero consultar una sección de preguntas frecuentes, para resolver dudas comunes sin necesidad de contactar a la start up [10]. | 5 |
| 80 | US07 | Seleccionar el idioma de la landing page | Como visitante del sitio, quiero poder encontrar más de un idioma disponible, para poder elegir el idioma de mi preferencia [13]. | 3 |

## 2.5. Strategic-Level Domain-Driven Design

El enfoque de **Strategic-Level Domain-Driven Design** sirve como pilar esencial en el desarrollo de la aplicación **IoBuild**. Gracias a esta metodología, es posible identificar y delimitar los distintos contextos del dominio, definir cómo se relacionan entre sí y construir una arquitectura de software robusta que responda a los objetivos del negocio.

En esta etapa estratégica, se prioriza:

- Un entendimiento profundo del dominio, mediante la identificación de los procesos clave del negocio.
- La definición de bounded contexts, estableciendo límites claros entre las distintas áreas funcionales.
- El modelado de las relaciones, determinando cómo interactúan los diferentes contextos.
- El diseño de una arquitectura de alto nivel, que estructura de forma integral el sistema.

### 2.5.1. EventStorming

El EventStorming es una técnica de modelado colaborativo que permite analizar y entender en profundidad el dominio complejo de IoBuild. A través de sesiones de trabajo conjunto con expertos del dominio, esta metodología ayuda a identificar elementos clave como eventos de dominio, comandos, agregados y bounded contexts.

#### 2.5.1.1. Candidate Context Discovery
La Candidate Context Discovery es el proceso mediante el cual identificamos los posibles bounded contexts dentro del dominio de LevelUpJourney. Este proceso se basa en el análisis de los eventos, comandos y agregados identificados durante las sesiones de EventStorming.<br><br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%209.jpg?raw=true)<br>
Representa la frontera administrativa inicial de la plataforma. El flujo muestra a la **Constructora** ejecutando comandos para crear propietarios y asignar apartamentos, estableciendo el evento crítico de **Apartamento Asignado**. Además, define la regla de negocio para adquirir unidades adicionales condicionada a la validación de **Fondos Suficientes**.

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2010.jpg?raw=true)<br>
Define el límite de seguridad y autenticación. El diagrama expone el proceso donde un usuario inicia un intento de sesión, el sistema verifica las credenciales y, tras validarlas, genera un **Token Acceso**, marcando la sesión como iniciada de forma segura.

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2011.jpg?raw=true)<br>
Agrupa todas las interacciones operativas directas con el hardware. El flujo refleja al **Propietario** vinculando nuevos equipos, y ejecutando comandos para encender, apagar o modificar parámetros, lo que genera los eventos de **Estado de Dispositivo Cambio** en el mundo físico.
<br>
![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2012.jpg?raw=true)<br>
Aísla el núcleo de cálculo matemático y procesamiento pasivo. Se observa al **Sistema de Monitoreo** registrando lecturas de voltaje para calcular el gasto energético acumulado. El evento pivotal aquí es el **Limite de Energia Superado**, el cual actúa como el detonante para emitir alertas automáticas.

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2013.jpg?raw=true)<br>
Delimita el módulo encargado de las consultas (Queries) del sistema. Ilustra cómo el **Propietario** y la **Constructora** solicitan métricas y datos históricos, lo cual desencadena la generación de un **Reporte de Consumo** y culmina con el evento de **Dashboard Presentado**.

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2014.jpg?raw=true)<br>
Muestra un módulo transversal dedicado a la comunicación saliente. El flujo detalla cómo el sistema formatea mensajes de alerta y utiliza canales externos como **Email Provider** y **Push Notification** para despachar la información hasta que la notificación es leída por el usuario.

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2015.jpg?raw=true)<br>
Representa la capa de valor agregado y optimización autónoma. El diagrama muestra al **Motor IA** recibiendo consultas, analizando patrones de consumo y generando sugerencias de ahorro. Finaliza con un evento de alto impacto donde la IA ejecuta la **Sugerencia Aplicada al Dispositivo** de forma directa.

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2016.jpg?raw=true)<br>
Enmarca el modelo de negocio financiero de la plataforma. La imagen ilustra a la **Constructora** ingresando un método de pago para procesar el **Cobro Mensual**. El evento de **Subscripción Activada** es la frontera comercial que permite la renovación del acceso premium al sistema.

<br>

#### 2.5.1.2. Domain Message Flows Modeling
El Domain Message Flows Modeling mapea cómo los mensajes (eventos, comandos) fluyen entre los diferentes bounded contexts identificados. Este modelado es crucial para entender las dependencias y patrones de comunicación del sistema.<br><br>

![Domain Message Flows Modeling](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2017.jpg?raw=true)<br>
Este diagrama ilustra el flujo inicial de habilitación de un usuario en el sistema. Comienza con la **Constructora** ejecutando el comando síncrono para **Asignar Apartamento** dentro del contexto de **Smart Project Setup**. Esto detona un evento asíncrono **Apartamento Asignado** que viaja hacia **Service Execution**, dándole luz verde al **Propietario** para ejecutar el comando de **Vincular dispositivo**. El ciclo concluye cuando Service Execution emite el evento **Dispositivo Vinculado Integration** hacia Energy Management, preparándolo para recibir futuras métricas de ese nuevo hardware.

![Domain Message Flows Modeling](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2018.jpg?raw=true)<br>
Este diagrama representa el comportamiento reactivo y autónomo del sistema frente a un pico de consumo. Se inicia cuando un **Sensor IoT** envía continuamente el comando **Registrar Lectura** hacia **Energy Management**. Al detectarse una anomalía, este contexto publica el evento **Limite Energía Superado Integration** para despertar al **Smart Assistant**. La IA evalúa la situación y envía un comando de ejecución directa **Aplicar Optimización** hacia Service Execution **Monitoring**, el cual apaga o regula el equipo y avisa de vuelta a **Energy Management** mediante un evento de cambio de estado.

![Domain Message Flows Modeling](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2019.jpg?raw=true)<br>
Esta imagen detalla cómo el usuario humano interactúa con el hardware utilizando la IA como intermediario. El flujo muestra al **Propietario** usando la Mobile App para enviar comandos de **Consultar Asistente** y posteriormente **Aceptar Sugerencia** hacia el **Smart Assistant**. Una vez autorizado, el asistente toma el control y manda el comando imperativo de **Modificar Parametros** hacia **Service Execution and Monitoring**. Finalmente, el hardware ejecuta el cambio y emite un evento de **Parametros Configurados Integration** hacia **Energy Management** para que ajuste sus cálculos de consumo eléctrico


#### 2.5.1.3. Bounded Context Canvases
Los Bounded Context Canvases proporcionan una visión detallada de cada contexto delimitado, documentando sus responsabilidades, interfaces, eventos y relaciones con otros contextos.
<br><br>

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Smart%20Project%20Setup.jpg?raw=true)<br>
Esta imagen representa el contrato formal del módulo administrativo e inmobiliario. Se clasifica como un Supporting Domain cuyo rol es gestionar la infraestructura física. El diagrama central mapea su comunicación entrante (los comandos **Asignar Apartamento** de la Constructora y **Adquirir Apartamento** del Propietario) y su comunicación saliente (el evento **Apartamento Asignado Integration Event** dirigido hacia **Service Execution**). En la parte inferior, se documentan las reglas de negocio estrictas, como la validación de fondos y la restricción de que un usuario no puede operar dispositivos sin un departamento formalmente asignado.

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Service%20Execution%20and%20Monitoring.jpg?raw=true)<br>
Este lienzo expone la arquitectura del núcleo operativo en tiempo real de la plataforma IoT (un **Core Domain**). Define sus roles como **Orquestador de Hardware** y **Ejecutor de Órdenes**. El mapa de dependencias ilustra una alta interacción: recibe comandos físicos (**Vincular**, **Encender/Apagar**) tanto del Propietario como órdenes directas de la IA (**Aplicar Optimización**), y a su vez publica los eventos de **Estado Dispositivo Cambio** hacia los medidores. Sus decisiones de negocio garantizan que todo cambio físico se notifique inmediatamente para no perder precisión en el sistema.

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Energy%20Management.jpg?raw=true)<br>
Este diagrama delimita el motor analítico y cuantitativo del sistema (también un **Core Domain**). El lienzo muestra que su comunicación entrante se basa puramente en telemetría (**Registrar Lectura Command**) proveniente de los sensores y en los cambios de estado del hardware. Visualmente, destaca que su única y más importante salida es la emisión del evento **Limite Energía Superado Integration Event** hacia el **asistente inteligente**. Entre sus políticas documentadas se subraya que el cálculo matemático debe ser estrictamente asíncrono para evitar cuellos de botella en la red de los condominios.

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Smart%20Assistant.jpg?raw=true)<br>
Este lienzo detalla el módulo de Inteligencia Artificial que aporta el valor agregado a la plataforma (**Core Domain**). Establece sus roles como **Optimizador** y **Agente Autónomo**. El diagrama central mapea cómo la IA se alimenta de las alertas de **Energy Management** y de las consultas a demanda del usuario, para luego emitir el comando imperativo de **Aplicar Optimización** hacia Service Execution. En la base del lienzo, consolida decisiones críticas del negocio, como la capacidad del sistema para enviar órdenes de apagado directo en **Modo Autónomo** sin tener que esperar la aprobación manual del dueño del departamento.


### 2.5.2. Context Mapping

##### Resumen del Proceso
El Context Mapping es la fase donde definimos las relaciones estructurales y los contratos de comunicación entre nuestros Bounded Contexts. En IoBuild, este proceso se realizó mediante un análisis crítico de dependencias, buscando maximizar la autonomía de los microservicios y proteger el lenguaje ubicuo de cada uno.

##### Análisis de Alternativas (Exploración de Diseño)

Para llegar a la arquitectura final, el equipo evaluó diversas configuraciones respondiendo a las siguientes preguntas críticas:

###### 1. ¿Qué pasaría si movemos la capacidad de "Monitoreo de Umbrales" a Smart Assistant?
* **Análisis:** Si el motor de IA procesara directamente las lecturas de voltaje, se generaría un acoplamiento masivo de datos innecesarios hacia la IA.
* **Decisión:** Mantenerlo en **Energy Management**. Esto permite que la IA sea reactiva y solo "despierte" cuando ocurre un evento de negocio relevante (Límite Superado), siguiendo el principio de segregación de responsabilidades.

###### 2. ¿Qué pasaría si creamos un Shared Kernel para la entidad "Propietario"?
* **Análisis:** Aunque todos los contextos usan el concepto de "Propietario", su definición cambia: en *Smart Project Setup* es un titular legal con fondos; en *Service Execution* es un operador de hardware.
* **Decisión:** Rechazado. Un Shared Kernel crearía un acoplamiento rígido en la base de datos. Se optó por duplicar el ID del propietario y usar una capa de traducción para mantener la autonomía de los modelos.

###### 3. ¿Qué pasaría si aislamos los Core Capabilities y movemos los otros a un contexto aparte?
* **Análisis:** Identificamos que *Smart Project Setup* es un dominio de soporte (SaaS B2B).
* **Decisión:** Se aisló completamente. Al ser Upstream, permite que el "Core IoT" (Execution, Energy, Assistant) evolucione técnicamente sin verse afectado por cambios en las reglas de negocio administrativas de la constructora.

##### Patrones de Relación y Mapa de Contextos

La arquitectura de IoBuild se define bajo una arquitectura orientada a eventos (EDA). A continuación se detallan las relaciones y patrones DDD establecidos:

###### A. Smart Project Setup (Upstream) -> Service Execution (Downstream)
* **Patrón:** **Customer-Supplier / Anti-Corruption Layer (ACL)**.
* **Motivo:** *Service Execution* depende de la información de departamentos asignados. Implementamos una ACL en *Service Execution* para evitar que cambios en el modelo de datos inmobiliario contaminen la lógica de control de dispositivos.

###### B. Service Execution (Upstream) -> Energy Management (Downstream)
* **Patrón:** **Published Language (PL)**.
* **Motivo:** La comunicación es asíncrona y masiva. *Service Execution* publica eventos de telemetría en un lenguaje estándar (JSON) que *Energy Management* consume para sus cálculos sin que ambos necesiten conocerse íntimamente.

###### C. Energy Management (Upstream) -> Smart Assistant (Downstream)
* **Patrón:** **Published Language (PL)**.
* **Motivo:** El asistente se suscribe a eventos de alerta de consumo. La relación es de bajo acoplamiento, permitiendo que el motor de IA pueda ser reemplazado o actualizado sin afectar los medidores de energía.

###### D. Smart Assistant (Upstream) -> Service Execution (Downstream)
* **Patrón:** **Customer-Supplier**.
* **Motivo:** En este flujo de comando, el asistente actúa como el cliente que solicita una acción de ahorro. *Service Execution* actúa como el proveedor de la capacidad física de apagar o regular el hardware.

##### Discusión de Alternativas y Conclusión
Tras evaluar modelos de *Conformist* (donde todos se adaptan al modelo de la constructora), el equipo decidió rechazarlo por el alto riesgo de deuda técnica. La aproximación elegida de **Customer-Supplier con ACL** y **Published Language** garantiza que IoBuild sea escalable, permitiendo manejar miles de dispositivos simultáneamente sin que una falla en un módulo administrativo afecte la inteligencia operativa de la IA o el monitoreo de energía.

### 2.5.3. Software Architecture
La arquitectura de software de IoBuild se ha diseñado utilizando el modelo C4, ya que este permite representar el sistema en diferentes niveles de abstracción como Contexto, Contenedores y Despliegue. Gracias a este enfoque, es más fácil entender cómo funciona el sistema en general, cómo interactúan los usuarios con la plataforma y cómo se relaciona con otros sistemas externos.

Para el diseño de la arquitectura, se han considerado algunos principios clave. En primer lugar, la separación de responsabilidades, donde cada parte del sistema tiene funciones específicas. También se busca un bajo acoplamiento, para evitar dependencias innecesarias entre los módulos, y una alta cohesión, agrupando elementos que tienen relación entre sí. Finalmente, se toma en cuenta la escalabilidad, permitiendo que el sistema pueda crecer sin problemas, y la mantenibilidad, facilitando realizar cambios o mejoras en el futuro.

#### 2.5.3.1. Software Architecture Context Level Diagrams
El diagrama de contexto presenta el sistema IoBuild como una plataforma central, mostrando cómo interactúa con los usuarios y con distintos sistemas externos. Este nivel permite entender de manera general el alcance del sistema y cómo se integra con otros servicios.

"Context Level Diagram": <https://shorturl.at/EbWzU>
![Context Level Diagrams](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Software%20Architecture%20Context%20Diagram.png)

**Explicación del Diagrama**

Sistema Central (IoBuild):
Es la plataforma principal encargada de gestionar proyectos de construcción inteligente. Permite a los usuarios configurar entornos, administrar dispositivos conectados y consultar información relevante como reportes y datos del sistema.

**Usuarios:**

- Builder: Es el usuario encargado de diseñar y configurar entornos inteligentes. Interactúa con IoBuild para registrar dispositivos mediante escaneo (QR) y gestionar proyectos a través de una interfaz web.
- Landlord: Es el usuario que utiliza la plataforma para supervisar y administrar sus propiedades. Consulta reportes y realiza seguimiento mediante un dashboard.

**Sistemas Externos:**

- Cloudinary: Servicio utilizado para la gestión y almacenamiento de archivos multimedia relacionados con los proyectos.
- AI Chatbot Service: Proporciona asistencia inteligente a los usuarios, resolviendo dudas y brindando soporte dentro de la plataforma.
- Stripe: Sistema encargado de procesar pagos y gestionar suscripciones dentro de IoBuild.

**Interacciones:**

- El Builder interactúa con IoBuild para registrar dispositivos y gestionar configuraciones de proyectos.
- El Landlord utiliza IoBuild para consultar reportes y monitorear el estado de sus propiedades.
- IoBuild se integra con Cloudinary para almacenar y administrar contenido multimedia.
- IoBuild se comunica con el AI Chatbot Service para brindar soporte y asistencia a los usuarios.
- IoBuild utiliza Stripe para gestionar pagos y suscripciones dentro de la plataforma.

En conjunto, este diagrama permite entender cómo IoBuild se posiciona como el núcleo del sistema, conectando a los usuarios con distintos servicios externos para ofrecer una solución completa.

#### 2.5.3.2. Software Architecture Container Level Diagrams
El siguiente diagrama de contenedores muestra la arquitectura de alto nivel del sistema IoBuild, permitiendo entender cómo se organizan sus principales componentes, qué tecnologías se utilizan y cómo interactúan entre sí. Este nivel de detalle ayuda a visualizar la estructura interna del sistema y cómo se distribuyen las responsabilidades entre los distintos contenedores.

"Container Level Diagram": <https://shorturl.at/FEOTa>
![Container Level Diagrams](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Software%20Architecture%20Container%20Diagram.png)

**Descripción del Container Diagram**

El sistema IoBuild está compuesto por varios contenedores que trabajan de manera conjunta para ofrecer sus funcionalidades:

**Capa de Presentación:**

- Landing Page: Es la página pública del sistema. Funciona como punto de entrada para los usuarios, brindando información general y redirigiendo hacia la aplicación web.
- Web App: Es la aplicación web principal donde los usuarios (Builder y Landlord) interactúan con el sistema para gestionar dispositivos, proyectos y visualizar información relevante.
- Mobile Application: Aplicación móvil que permite a los usuarios acceder a las funcionalidades principales de IoBuild desde sus smartphones, facilitando la gestión remota de sus propiedades y dispositivos.
- Single Page Application: Representa la lógica del lado del cliente dentro de la web app, permitiendo una experiencia dinámica e interactiva en el navegador sin recargar la página.

**Capa de Backend:**

- Web Service: Es el backend del sistema. Se encarga de procesar la lógica de negocio, exponer endpoints mediante una API y gestionar la comunicación entre el frontend, la base de datos y los servicios externos.

**Capa de Persistencia:**

- Database: Almacena toda la información del sistema, como datos de usuarios, proyectos, dispositivos y configuraciones.

**Sistemas Externos:**

- Cloudinary: Servicio utilizado para el almacenamiento y gestión de archivos multimedia.
- Stripe: Plataforma encargada de procesar pagos y manejar suscripciones dentro del sistema.

**Interacciones y Comunicación**

- Los usuarios acceden al sistema a través de la Landing Page, la cual los redirige hacia la Web App.
- La Web App utiliza una arquitectura SPA para gestionar la interacción del usuario de manera dinámica.
- Tanto la Web App como la Mobile Application consumen la API expuesta por el Web Service mediante solicitudes HTTP.
- El Web Service se encarga de procesar la lógica del sistema, acceder a la Database para almacenar o recuperar información, y comunicarse con servicios externos.
- IoBuild utiliza Cloudinary para gestionar archivos multimedia y Stripe para el manejo de pagos y suscripciones.

**Decisiones Tecnológicas Principales:**

- Uso de SPA para mejorar la experiencia de usuario en la web.
- Separación entre frontend y backend para facilitar el desarrollo y mantenimiento.
- Backend centralizado con ASP.NET Core, que actúa como punto de acceso a la lógica del sistema.
- Uso de una base de datos relacional (MySQL) para garantizar consistencia de la información.
- Integración con servicios externos especializados como Cloudinary y Stripe para funcionalidades específicas.

En conjunto, esta arquitectura permite que IoBuild sea un sistema escalable, mantenible y flexible, donde cada componente cumple una función específica y puede evolucionar de manera independiente.

#### 2.5.3.3. Software Architecture Deployment Diagrams
El siguiente diagrama de despliegue muestra cómo los diferentes componentes del sistema IoBuild se distribuyen en la infraestructura, tanto en el cliente como en la nube. Este tipo de diagrama permite entender dónde se ejecuta cada parte del sistema, cómo se comunican entre sí y qué tecnologías o servicios se utilizan en el entorno real de producción.

"Deployment Level Diagram": <https://shorturl.at/2DSHw>
![Deployment Level Diagrams](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Software%20Architecture%20Deployment%20Diagram.png)

**Descripción del Deployment Diagram**

El sistema IoBuild está organizado en varias capas de despliegue que separan claramente el frontend, los clientes, el backend y la base de datos:

**Client Tier (Clientes):**

- Web Clients (Browser): Representa a los usuarios que acceden desde un navegador web. Aquí se carga la Landing Page y la Web Application (SPA), permitiendo la interacción con el sistema sin necesidad de instalar software adicional.
- Mobile Clients (Mobile Device): Incluye dispositivos móviles donde se ejecuta la Mobile App, permitiendo a los usuarios gestionar sus propiedades y dispositivos desde cualquier lugar.

**Cloud Tier (Infraestructura en la Nube):**

- Frontend Hosting:
    - GitHub Pages: Se utiliza para alojar la Landing Page, que es un sitio estático informativo accesible públicamente.
    - Vercel: Plataforma donde se despliega la Web Application (SPA), optimizada para aplicaciones modernas y con buen rendimiento.
- Backend Layer:
    - Application Server: Servidor donde se ejecuta la lógica del sistema.
    - Docker Container: Contenedor que encapsula el API Backend (API REST), permitiendo portabilidad, escalabilidad y facilidad de despliegue.
- Data Layer:
    - Database Server: Nodo donde se encuentra la base de datos.
    - MySQL Database: Sistema de gestión de base de datos relacional que almacena toda la información del sistema.

**Interacciones y Comunicación**

- Los usuarios acceden a la Landing Page desde el navegador, la cual redirige hacia la Web Application (SPA).
- Tanto la Web App como la Mobile App se comunican con el API Backend mediante solicitudes HTTPS, enviando y recibiendo datos en formato JSON.
- El API Backend, desplegado en un contenedor Docker, procesa la lógica del sistema y se encarga de gestionar las peticiones de los clientes.
- El backend se comunica con la MySQL Database mediante consultas SQL para almacenar y recuperar información.

**Decisiones de Despliegue y Justificación**

- Separación por capas: Se divide el sistema en cliente, frontend, backend y base de datos para facilitar el mantenimiento y escalabilidad.
- Uso de servicios cloud: GitHub Pages y Vercel permiten un despliegue sencillo y eficiente del frontend sin necesidad de gestionar servidores.
- Contenerización con Docker: Facilita la portabilidad del backend y permite desplegarlo en distintos entornos sin problemas de compatibilidad.
- Comunicación segura: Se utiliza HTTPS para proteger la información que viaja entre clientes y servidor.
- Base de datos centralizada: MySQL asegura la persistencia y consistencia de los datos del sistema.

En conjunto, este diagrama muestra una arquitectura moderna basada en servicios en la nube y contenedores, que permite a IoBuild ser un sistema escalable, accesible desde múltiples dispositivos y fácil de mantener.


## 2.6. Tactical-Level Domain-Driven Design

### Introduccion al Diseno Tactico
El Tactical-Level Domain-Driven Design de **IoBuild** representa la materializacion concreta del diseno estrategico definido previamente. En esta seccion se detalla como cada bounded context implementa sus capas Domain, Interface, Application e Infrastructure, asi como sus componentes internos, contratos y mecanismos de persistencia. Este enfoque tactico asegura que las decisiones de negocio se traduzcan en una arquitectura modular, desacoplada, mantenible y lista para evolucionar conforme crezca la plataforma.

Para IoBuild se han identificado cuatro bounded contexts principales que cubren las capacidades nucleares de la solucion: **Smart Project Setup** para la configuracion inicial de proyectos, zonas y perfiles IoT; **Service Execution and Monitoring** para la orquestacion de servicios y el monitoreo operativo en tiempo real; **Smart Assistant** para la asistencia inteligente y contextual a los usuarios de la plataforma; y **Energy Management** para la medicion, analisis y optimizacion del consumo energetico en edificios inteligentes.

### 2.6.1. Bounded Context: Smart Project Setup
#### 2.6.1.1. Domain Layer
En **IoBuild**, este bounded context define como se prepara un proyecto inteligente antes de su ejecucion operativa. El dominio cubre modelado del sitio, seleccion de perfiles IoT y configuracion de conectividad para dejar el proyecto listo para despliegue.

**Entities y Aggregates**
- **SmartProjectSetup (Aggregate Root):** representa la configuracion principal del proyecto (id, ownerId, nombre del proyecto, tipo de edificio, estado del setup, zonas y perfiles asignados).
- **SiteZone:** representa un espacio fisico del proyecto (piso, ambiente o sector) donde se desplegaran dispositivos.
- **DeviceProfile:** representa la configuracion funcional de un tipo de dispositivo IoT (sensor, intervalo de lectura, umbrales y protocolo).
- **ConnectivityProfile:** representa la configuracion de conectividad del proyecto (gateway, protocolo, credenciales y politicas de reconexion).

**Value Objects**
- **SetupId, OwnerId, ZoneId, DeviceProfileId, ConnectivityProfileId:** identificadores unicos del dominio.
- **SetupStatus:** estado del setup (DRAFT, VALIDATED, PROVISIONED, ARCHIVED).
- **BuildingType:** tipo de edificio (RESIDENTIAL, COMMERCIAL, INDUSTRIAL, EDUCATIONAL).
- **SensorType:** tipo de sensor (TEMPERATURE, HUMIDITY, OCCUPANCY, ENERGY_METER, AIR_QUALITY).
- **ProtocolType:** protocolo de comunicacion (MQTT, HTTP, MODBUS, BACNET).

**Commands**
- CreateSmartProjectSetupCommand
- UpdateSmartProjectSetupCommand
- DefineSiteZoneCommand
- UpdateSiteZoneCommand
- AssignDeviceProfileCommand
- ConfigureConnectivityProfileCommand
- ValidateSmartProjectSetupCommand
- ProvisionSmartProjectSetupCommand

**Queries**
- GetSmartProjectSetupByIdQuery
- GetSmartProjectSetupsByOwnerIdQuery
- GetSetupChecklistByIdQuery
- GetZonesBySetupIdQuery
- GetAvailableDeviceProfilesQuery
- GetConnectivityProfileBySetupIdQuery

**Domain Services (Contratos)**
- SmartProjectSetupCommandService
- SmartProjectSetupQueryService
- ZoneConfigurationCommandService
- DeviceProfileConfigurationService
- SetupValidationService

#### 2.6.1.2. Interface Layer
La capa de interfaz expone endpoints REST para crear y configurar proyectos IoBuild, registrar zonas del sitio y asignar perfiles tecnicos.

**Controllers**
- **SmartProjectSetupsController:** create, update, validate, provision y consultas principales del setup.
- **SetupZonesController:** define y actualiza zonas fisicas del proyecto.
- **SetupProfilesController:** asigna perfiles de dispositivo y configura conectividad.

**Resources (Request/Query DTOs)**
- **Setup:** CreateSmartProjectSetupResource, UpdateSmartProjectSetupResource, ValidateSmartProjectSetupResource, ProvisionSmartProjectSetupResource.
- **Zones:** DefineSiteZoneResource, UpdateSiteZoneResource.
- **Profiles:** AssignDeviceProfileResource, ConfigureConnectivityProfileResource.
- **Queries:** GetSmartProjectSetupByIdResource, GetSmartProjectSetupsByOwnerIdResource, GetSetupChecklistByIdResource, GetZonesBySetupIdResource.

**Smart Project Setup Interface Diagram**
![Smart Project Setup Interface Diagram](https://instasize.com/api/image/ac46962e9edde3cbfc8e372f387b207c489713181446b1a16f8ce49facd5b3b2.png)

#### 2.6.1.3. Application Layer
La capa de aplicacion orquesta comandos y queries para preparar el proyecto IoBuild y validar que la configuracion cumpla requisitos minimos antes del aprovisionamiento.

**Command Handlers**
- **SmartProjectSetupCommandServiceImpl:** CreateSmartProjectSetupCommand, UpdateSmartProjectSetupCommand, ValidateSmartProjectSetupCommand, ProvisionSmartProjectSetupCommand.
- **ZoneConfigurationCommandServiceImpl:** DefineSiteZoneCommand, UpdateSiteZoneCommand.
- **DeviceProfileConfigurationServiceImpl:** AssignDeviceProfileCommand, ConfigureConnectivityProfileCommand.

**Query Handlers**
- **SmartProjectSetupQueryServiceImpl:** GetSmartProjectSetupByIdQuery, GetSmartProjectSetupsByOwnerIdQuery, GetSetupChecklistByIdQuery, GetZonesBySetupIdQuery.
- **SetupCatalogQueryServiceImpl:** GetAvailableDeviceProfilesQuery, GetConnectivityProfileBySetupIdQuery.

**Smart Project Setup Application Diagram**
![Smart Project Setup Application Diagram](https://instasize.com/api/image/e9c9db4b1c8d1417d7243363b80201317c2b75e261099bf4500fee76ca9d9dea.png)

#### 2.6.1.4. Infrastructure Layer
La capa de infraestructura implementa persistencia del setup de IoBuild, incluyendo zonas, perfiles de dispositivos y configuracion de conectividad.

**Repositories**
- **SmartProjectSetupRepository:** busquedas por ownerId, status y validaciones por nombre del proyecto.
- **SiteZoneRepository:** consultas de zonas por setup y validacion de nombres repetidos por setup.
- **DeviceProfileRepository:** catalogo de perfiles por sensor y tipo de edificio.
- **ConnectivityProfileRepository:** obtencion y reemplazo de configuracion de conectividad por setup.

**Smart Project Setup Infrastructure Diagram**
![Smart Project Setup Infrastructure Diagram](https://instasize.com/api/image/7b5799c5a59f8baa058ce64b7ac8c866100f4a3f54a18da83b6da5bd5d9c55f4.png)

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
<!--
workspace "IoBuild - Smart Project Setup (Component Diagram)" "C4 Component Diagram del bounded context Smart Project Setup" {
    model {
        builder  = person "Builder"   "Configura proyectos y perfiles IoT."
        landlord = person "Landlord"  "Supervisa el setup del proyecto."

        iobuild = softwareSystem "IoBuild" {

            spsApi = container "Smart Project Setup API" "Gestiona setup, zonas y perfiles." "ASP.NET Core Web API" {
                spsController      = component "SmartProjectSetupsController"         "Endpoints de setup."                  "ASP.NET Core MVC Controller"
                zonesController    = component "SetupZonesController"                  "Endpoints de zonas."                  "ASP.NET Core MVC Controller"
                profilesController = component "SetupProfilesController"               "Endpoints de perfiles y conectividad." "ASP.NET Core MVC Controller"
                cmdService         = component "SmartProjectSetupCommandServiceImpl"   "Casos de uso de comando."             "Application Service (C#)"
                qryService         = component "SmartProjectSetupQueryServiceImpl"     "Casos de uso de consulta."            "Application Service (C#)"
                zoneCmdService     = component "ZoneConfigurationCommandServiceImpl"   "Reglas de zonas."                     "Application Service (C#)"
                profileCmdService  = component "DeviceProfileConfigurationServiceImpl" "Reglas de perfiles IoT."              "Application Service (C#)"
                aggregate          = component "SmartProjectSetup Aggregate"           "Invariantes del dominio."             "Domain Model (DDD)"
                validation         = component "SetupValidationService"                "Validaciones de negocio."             "Domain Service"
                setupRepo          = component "SmartProjectSetupRepository"          "Persistencia de setup."               "Repository"
                zoneRepo           = component "SiteZoneRepository"                    "Persistencia de zonas."               "Repository"
                profileRepo        = component "DeviceProfileRepository"              "Persistencia de perfiles."            "Repository"
                connectivityRepo   = component "ConnectivityProfileRepository"         "Persistencia de conectividad."        "Repository"
            }

            mysql    = container "MySQL Database" "Persistencia transaccional."       "MySQL 8"
            eventBus = container "Event Bus"      "Publicación de eventos de dominio." "RabbitMQ / Kafka"
        }

        builder  -> spsApi "Usa"      "HTTPS/JSON"
        landlord -> spsApi "Consulta" "HTTPS/JSON"

        spsController      -> cmdService        "Envía comandos"
        spsController      -> qryService        "Envía queries"
        zonesController    -> zoneCmdService    "Envía comandos"
        profilesController -> profileCmdService "Envía comandos"

        cmdService        -> aggregate "Orquesta"
        qryService        -> aggregate "Lee"
        zoneCmdService    -> aggregate "Modifica"
        profileCmdService -> aggregate "Modifica"

        aggregate -> validation "Valida reglas"

        cmdService        -> setupRepo        "Persiste"
        qryService        -> setupRepo        "Consulta"
        zoneCmdService    -> zoneRepo         "Persiste"
        profileCmdService -> profileRepo      "Persiste"
        profileCmdService -> connectivityRepo "Persiste"

        setupRepo        -> mysql "CRUD" "SQL/TCP"
        zoneRepo         -> mysql "CRUD" "SQL/TCP"
        profileRepo      -> mysql "CRUD" "SQL/TCP"
        connectivityRepo -> mysql "CRUD" "SQL/TCP"

        aggregate -> eventBus "Publica eventos" "AMQP/Kafka"
    }

    views {
        component spsApi "SPS-Component" {
            include *
            autolayout lr
        }

        styles {
            element "Person" {
                background #08427b
                color #ffffff
                shape person
            }
            element "Software System" {
                background #1168bd
                color #ffffff
            }
            element "Container" {
                background #438dd5
                color #ffffff
            }
            element "Component" {
                background #85bbf0
                color #000000
            }
        }
    }
}

-->

![Diagram C4](https://i.imgur.com/EZ0QtVR.png)

#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
En esta seccion se presentan los diagramas de nivel codigo para **Smart Project Setup**, cubriendo el modelo del Domain Layer y su persistencia relacional.

##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
El siguiente diagrama UML muestra clases, interfaces, enumeraciones, atributos, metodos, scopes y relaciones con multiplicidad del dominio.


<div style="display:none">
    ```mermaid
    classDiagram
    direction LR

    class SmartProjectSetup {
        -SetupId id
        -OwnerId ownerId
        -string projectName
        -BuildingType buildingType
        -SetupStatus status
        -DateTime createdAt
        -DateTime updatedAt
        +renameProject(name:string) void
        +changeBuildingType(type:BuildingType) void
        +addZone(zone:SiteZone) void
        +assignDeviceProfile(profile:DeviceProfile) void
        +configureConnectivity(profile:ConnectivityProfile) void
        +validate() void
        +provision() void
    }

    class SiteZone {
        -ZoneId id
        -string name
        -int floor
        -string areaType
        -float areaM2
        +rename(name:string) void
        +updateArea(areaM2:float) void
    }

    class DeviceProfile {
        -DeviceProfileId id
        -SensorType sensorType
        -int samplingIntervalSec
        -float minThreshold
        -float maxThreshold
        -ProtocolType protocol
        +changeSamplingInterval(seconds:int) void
        +updateThresholds(min:float,max:float) void
    }

    class ConnectivityProfile {
        -ConnectivityProfileId id
        -ProtocolType protocol
        -string gatewayHost
        -int gatewayPort
        -string credentialsRef
        -int reconnectPolicySec
        +updateGateway(host:string,port:int) void
        +rotateCredentials(ref:string) void
    }

    class SetupStatus {
        <<enumeration>>
        DRAFT
        VALIDATED
        PROVISIONED
        ARCHIVED
    }

    class BuildingType {
        <<enumeration>>
        RESIDENTIAL
        COMMERCIAL
        INDUSTRIAL
        EDUCATIONAL
    }

    class SensorType {
        <<enumeration>>
        TEMPERATURE
        HUMIDITY
        OCCUPANCY
        ENERGY_METER
        AIR_QUALITY
    }
    ```
</div>

![Diagrama plantUML](https://i.imgur.com/aqFCKUf.png)


##### 2.6.1.6.2. Bounded Context Database Design Diagram
El siguiente diagrama relacional muestra tablas, columnas y constraints para la persistencia del bounded context.

<div style="display:none">

    ```mermaid
    erDiagram
            SMART_PROJECT_SETUPS {
            string setup_id PK
            string owner_id
            string project_name
            string building_type
            string setup_status
                    datetime created_at
                    datetime updated_at
            }

            SITE_ZONES {
            string zone_id PK
            string setup_id FK
            string name
                    int floor
            string area_type
            float area_m2
                    datetime created_at
            }

            DEVICE_PROFILES {
            string device_profile_id PK
            string setup_id FK
            string sensor_type
                    int sampling_interval_sec
            float min_threshold
            float max_threshold
            string protocol
                    datetime created_at
            }

            CONNECTIVITY_PROFILES {
            string connectivity_profile_id PK
            string setup_id FK
            string protocol
            string gateway_host
                    int gateway_port
            string credentials_ref
                    int reconnect_policy_sec
                    datetime updated_at
            }

            SMART_PROJECT_SETUPS ||--o{ SITE_ZONES : "has zones"
            SMART_PROJECT_SETUPS ||--o{ DEVICE_PROFILES : "has profiles"
            SMART_PROJECT_SETUPS ||--o| CONNECTIVITY_PROFILES : "has connectivity"
    ```
</div>

![Diagrama lucidchart](https://i.imgur.com/szDoLl0.png)

### 2.6.2. Bounded Context: Service Execution and Monitoring
#### 2.6.2.1. Domain Layer
En **IoBuild**, este bounded context gestiona la ejecucion operativa de servicios y el monitoreo continuo de su comportamiento. El dominio cubre la orquestacion de ejecuciones, el registro de metricas de observabilidad y la gestion de alertas operativas.

**Entities y Aggregates**
- **ServiceExecution (Aggregate Root):** representa una ejecucion de servicio (id, projectId, serviceId, triggerType, estado, inicio, fin y resultado).
- **ExecutionTask:** representa una tarea interna ejecutada dentro de un flujo de servicio (orden, comando, estado y duracion).
- **MonitoringMetric:** representa una medicion tecnica asociada a una ejecucion o servicio (tipo, valor, unidad y timestamp).
- **ServiceAlert:** representa una alerta operativa generada por fallos, degradacion o umbrales excedidos.

**Value Objects**
- **ExecutionId, TaskId, ProjectId, ServiceId, MetricId, AlertId:** identificadores unicos del dominio.
- **ExecutionStatus:** estado de ejecucion (QUEUED, RUNNING, SUCCESS, FAILED, CANCELLED, TIMEOUT).
- **TaskStatus:** estado de tarea (PENDING, RUNNING, COMPLETED, FAILED, SKIPPED).
- **HealthStatus:** salud del servicio (HEALTHY, DEGRADED, OFFLINE).
- **MetricType:** tipo de metrica (CPU_USAGE, MEMORY_USAGE, LATENCY, ERROR_RATE, THROUGHPUT).
- **AlertSeverity:** severidad de alerta (INFO, WARNING, CRITICAL).

##### Domain Behavior and Invariants

Los aggregates del dominio encapsulan reglas de negocio y comportamiento operativo.

**ServiceExecution Behavior**
- startExecution()
- stopExecution()
- retryExecution()
- completeExecution()
- failExecution(reason)
- registerMonitoringMetric(metric)
- evaluateServiceHealth()

**Domain Invariants**
- Una ejecución solo puede estar RUNNING si posee startTime.
- Una ejecución finalizada no puede reiniciarse sin crear una nueva instancia.
- Las métricas solo pueden registrarse para ejecuciones activas.

##### Domain Events

El bounded context publica eventos del dominio para permitir integración desacoplada con otros contextos.

- ServiceExecutionStarted
- ServiceExecutionCompleted
- ServiceExecutionFailed
- MonitoringMetricRegistered
- ServiceHealthDegraded
- ServiceAlertRaised
- ServiceAlertResolved

**Commands**
- StartServiceExecutionCommand
- StopServiceExecutionCommand
- RetryServiceExecutionCommand
- CancelServiceExecutionCommand
- RegisterMonitoringMetricCommand
- UpdateServiceHealthStatusCommand
- RaiseServiceAlertCommand
- ResolveServiceAlertCommand

**Queries**
- GetExecutionByIdQuery
- GetExecutionsByProjectIdQuery
- GetActiveExecutionsQuery
- GetMetricsByExecutionIdQuery
- GetServiceHealthByProjectIdQuery
- GetOpenAlertsByProjectIdQuery

**Domain Services (Contratos)**
- ServiceExecutionCommandService
- ServiceExecutionQueryService
- MonitoringCommandService
- MonitoringQueryService
- AlertManagementService
- AlertQueryService

#### 2.6.2.2. Interface Layer
La capa de interfaz expone endpoints REST para ejecutar servicios, consultar estado operativo y administrar alertas del proyecto.

**Controllers**
- **ServiceExecutionsController:** start, stop, retry, cancel y consultas de ejecuciones.
- **ServiceMonitoringController:** registro de metricas y consulta de salud operativa.
- **ServiceAlertsController:** apertura, resolucion y consulta de alertas activas.

**Resources (Request/Query DTOs)**
- **Execution:** StartServiceExecutionResource, StopServiceExecutionResource, RetryServiceExecutionResource, CancelServiceExecutionResource.
- **Monitoring:** RegisterMonitoringMetricResource, UpdateServiceHealthStatusResource.
- **Alerts:** RaiseServiceAlertResource, ResolveServiceAlertResource.
- **Queries:** GetExecutionByIdResource, GetExecutionsByProjectIdResource, GetMetricsByExecutionIdResource, GetServiceHealthByProjectIdResource, GetOpenAlertsByProjectIdResource.

**Service Execution and Monitoring Interface Diagram**
![Service Execution and Monitoring Interface Diagram](https://instasize.com/api/image/d237f139e3bd29eea6ef5698a4e4f57140679000ed1d00c23baaec4157afae78.png)

#### 2.6.2.3. Application Layer
La capa de aplicacion orquesta la ejecucion de servicios y los procesos de observabilidad para garantizar trazabilidad y control operativo del sistema.

**Command Handlers**
- **ServiceExecutionCommandServiceImpl:** StartServiceExecutionCommand, StopServiceExecutionCommand, RetryServiceExecutionCommand, CancelServiceExecutionCommand.
- **MonitoringCommandServiceImpl:** RegisterMonitoringMetricCommand, UpdateServiceHealthStatusCommand.
- **AlertManagementServiceImpl:** RaiseServiceAlertCommand, ResolveServiceAlertCommand.

**Query Handlers**
- **ServiceExecutionQueryServiceImpl:** GetExecutionByIdQuery, GetExecutionsByProjectIdQuery, GetActiveExecutionsQuery.
- **MonitoringQueryServiceImpl:** GetMetricsByExecutionIdQuery, GetServiceHealthByProjectIdQuery.
- **AlertQueryServiceImpl:** GetOpenAlertsByProjectIdQuery.

**Service Execution and Monitoring Application Diagram**
![Service Execution and Monitoring Application Diagram](https://instasize.com/api/image/20b81bd5a2eecdf45ebe39b3305e475644b4581e030069c24911def098e3a3c8.png)

#### 2.6.2.4. Infrastructure Layer
La capa de infraestructura implementa persistencia de ejecuciones, metricas y alertas para soportar monitoreo historico y operacion en tiempo real.

**Repositories**
- **ServiceExecutionRepository:** busquedas por projectId, estado de ejecucion y ejecuciones activas.
- **ExecutionTaskRepository:** tareas por executionId y estado de tarea.
- **MonitoringMetricRepository:** metricas por executionId y por tipo de metrica.
- **ServiceAlertRepository:** alertas por projectId, severidad y estado de resolucion.

**Service Execution and Monitoring Infrastructure Diagram**
![Service Execution and Monitoring Infrastructure Diagram](https://instasize.com/api/image/6c9a8603ca4cac961870fdedc0c763647510ccd982a43e0e2128bb56cbe5cdd4.png)

#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams
<!--
workspace "IoBuild - Service Execution & Monitoring (Component Diagram)" "C4 Component Diagram del bounded context Service Execution and Monitoring" {

    model {
        builder  = person "Builder"  "Opera servicios."
        landlord = person "Landlord" "Monitorea estado operativo."

        iobuild = softwareSystem "IoBuild" {

            semApi = container "Service Execution & Monitoring API" "Ejecuta servicios, monitorea métricas y alertas." "ASP.NET Core Web API" {
                execController    = component "ServiceExecutionsController"        "Endpoints de ejecución."     "ASP.NET Core MVC Controller"
                monitorController = component "ServiceMonitoringController"        "Endpoints de métricas/salud." "ASP.NET Core MVC Controller"
                alertsController  = component "ServiceAlertsController"            "Endpoints de alertas."       "ASP.NET Core MVC Controller"

                execCmd    = component "ServiceExecutionCommandServiceImpl" "Comandos de ejecución."  "Application Service (C#)"
                execQry    = component "ServiceExecutionQueryServiceImpl"   "Queries de ejecución."   "Application Service (C#)"
                monitorCmd = component "MonitoringCommandServiceImpl"       "Comandos de monitoreo."  "Application Service (C#)"
                monitorQry = component "MonitoringQueryServiceImpl"         "Queries de monitoreo."   "Application Service (C#)"
                alertCmd   = component "AlertManagementServiceImpl"         "Comandos de alertas."    "Application Service (C#)"
                alertQry   = component "AlertQueryServiceImpl"              "Queries de alertas."     "Application Service (C#)"

                executionAgg = component "ServiceExecution Aggregate" "Ciclo de vida de ejecuciones y tareas." "Domain Model (DDD)"
                alertEntity  = component "ServiceAlert Entity"        "Modelo de alertas."                     "Domain Entity"
                healthSvc    = component "HealthEvaluationService"    "Evalúa estado de salud."                "Domain Service"

                executionRepo = component "ServiceExecutionRepository" "Persistencia de ejecuciones." "Repository"
                taskRepo      = component "ExecutionTaskRepository"    "Persistencia de tareas."      "Repository"
                metricRepo    = component "MonitoringMetricRepository" "Persistencia de métricas."    "Repository"
                alertRepo     = component "ServiceAlertRepository"     "Persistencia de alertas."     "Repository"
            }

            mysql         = container "MySQL Database"      "Persistencia operativa." "MySQL 8"
            observability = container "Observability Stream" "Eventos/telemetría."     "Kafka / OpenTelemetry"
        }

        builder  -> semApi "Usa"      "HTTPS/JSON"
        landlord -> semApi "Consulta" "HTTPS/JSON"

        execController    -> execCmd    "Comandos"
        execController    -> execQry    "Queries"
        monitorController -> monitorCmd "Comandos"
        monitorController -> monitorQry "Queries"
        alertsController  -> alertCmd   "Comandos"
        alertsController  -> alertQry   "Queries"

        execCmd    -> executionAgg "Orquesta"
        execQry    -> executionAgg "Consulta"
        monitorCmd -> executionAgg "Registra métricas"
        monitorQry -> executionAgg "Consulta métricas"
        alertCmd   -> alertEntity  "Gestiona"
        alertQry   -> alertEntity  "Consulta"
        executionAgg -> healthSvc  "Evalúa salud"

        execCmd    -> executionRepo "Persiste"
        execQry    -> executionRepo "Consulta"
        execCmd    -> taskRepo      "Persiste tareas"
        monitorCmd -> metricRepo    "Persiste métricas"
        monitorQry -> metricRepo    "Consulta métricas"
        alertCmd   -> alertRepo     "Persiste alertas"
        alertQry   -> alertRepo     "Consulta alertas"

        executionRepo -> mysql "CRUD" "SQL/TCP"
        taskRepo      -> mysql "CRUD" "SQL/TCP"
        metricRepo    -> mysql "CRUD" "SQL/TCP"
        alertRepo     -> mysql "CRUD" "SQL/TCP"

        executionAgg -> observability "Publica eventos" "Kafka/OTel"
    }

    views {
        component semApi "SEM-Component" {
            include *
            autolayout lr
        }

        styles {
            element "Person" {
                background #08427b
                color #ffffff
                shape person
            }
            element "Software System" {
                background #1168bd
                color #ffffff
            }
            element "Container" {
                background #438dd5
                color #ffffff
            }
            element "Component" {
                background #85bbf0
                color #000000
            }
        }
    }
}
-->
![Diagrama C4](https://i.imgur.com/p8nHO38.png)


#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams
En esta seccion se presenta el detalle de implementacion para **Service Execution and Monitoring**, incluyendo estructura de dominio y modelo de persistencia.

##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams
 <div style="display:none">
    ```mermaid
    classDiagram
    direction LR

    class ServiceExecution {
        -ExecutionId id
        -ProjectId projectId
        -ServiceId serviceId
        -ExecutionStatus status
        -DateTime startedAt
        -DateTime finishedAt
        -string resultSummary
        +startExecution() void
        +stopExecution() void
        +retryExecution() void
        +completeExecution() void
        +failExecution(reason:string) void
        +registerMonitoringMetric(metric:MonitoringMetric) void
    }

    class ExecutionTask {
        -TaskId id
        -ExecutionId executionId
        -int taskOrder
        -string command
        -TaskStatus status
        -int durationMs
        +start() void
        +complete() void
        +fail(reason:string) void
    }

    class MonitoringMetric {
        -MetricId id
        -ExecutionId executionId
        -MetricType type
        -float value
        -string unit
        -DateTime timestamp
    }

    class ServiceAlert {
        -AlertId id
        -ProjectId projectId
        -AlertSeverity severity
        -string message
        -bool resolved
        -DateTime createdAt
        +resolve() void
    }

    class ExecutionStatus {
        <<enumeration>>
        QUEUED
        RUNNING
        SUCCESS
        FAILED
        CANCELLED
        TIMEOUT
    }

    class TaskStatus {
        <<enumeration>>
        PENDING
        RUNNING
        COMPLETED
        FAILED
        SKIPPED
    }

    class MetricType {
        <<enumeration>>
        CPU_USAGE
        MEMORY_USAGE
        LATENCY
        ERROR_RATE
        THROUGHPUT
    }

    class AlertSeverity {
        <<enumeration>>
        INFO
        WARNING
        CRITICAL
    }

    class ServiceExecutionRepository {
        <<interface>>
        +save(exec:ServiceExecution) ServiceExecution
        +findById(id:ExecutionId) ServiceExecution
        +findActiveByProjectId(projectId:ProjectId) List~ServiceExecution~
    }

    class AlertManagementService {
        <<interface>>
        +raiseAlert(alert:ServiceAlert) ServiceAlert
        +resolveAlert(alertId:AlertId) void
    }

    ServiceExecution "1" --> "1..*" ExecutionTask : orchestrates
    ServiceExecution "1" --> "0..*" MonitoringMetric : emits
    ServiceExecution "1" --> "1" ExecutionStatus : has
    ExecutionTask "1" --> "1" TaskStatus : has
    MonitoringMetric "1" --> "1" MetricType : classifies
    ServiceAlert "1" --> "1" AlertSeverity : has
    AlertManagementService ..> ServiceAlert : manages
    ServiceExecutionRepository ..> ServiceExecution : persists
    ```
 </div>   

![Diagrama plantUML](https://i.imgur.com/Ngsgh4D.png)

##### 2.6.2.6.2. Bounded Context Database Design Diagram

<div style="display:none">
    ```mermaid
        erDiagram
        SERVICE_EXECUTIONS {
        string execution_id PK
        string project_id
        string service_id
        string status
                datetime started_at
                datetime finished_at
        string result_summary
        }

        EXECUTION_TASKS {
        string task_id PK
        string execution_id FK
                int task_order
        string command
        string status
                int duration_ms
        }

        MONITORING_METRICS {
        string metric_id PK
        string execution_id FK
        string metric_type
        float metric_value
        string unit
                datetime measured_at
        }

        SERVICE_ALERTS {
        string alert_id PK
        string project_id
        string severity
        string message
        boolean resolved
                datetime created_at
                datetime resolved_at
        }

        SERVICE_EXECUTIONS ||--|{ EXECUTION_TASKS : "contains tasks"
        SERVICE_EXECUTIONS ||--o{ MONITORING_METRICS : "registers metrics"
    ```
</div>

![Diagrama Lucidchart](https://i.imgur.com/xtReovF.png)

### 2.6.3. Bounded Context: Smart Assistant
#### 2.6.3.1. Domain Layer
En **IoBuild**, este bounded context implementa la asistencia inteligente contextual para apoyar decisiones operativas. El dominio cubre conversaciones asistidas, generacion de recomendaciones tecnicas y construccion de planes de accion sobre eventos del proyecto.

**Entities y Aggregates**
- **AssistantConversation (Aggregate Root):** representa una sesion conversacional asociada a un proyecto (id, projectId, userId, canal, estado y timestamps).
- **AssistantMessage:** representa cada mensaje de una conversacion (rol, contenido, metadatos y momento de emision).
- **AssistantRecommendation:** representa una recomendacion accionable generada por el asistente para optimizar operacion, mantenimiento o rendimiento.
- **AssistantActionPlan:** representa el plan de accion derivado de una recomendacion, con pasos, prioridad y estado de ejecucion sugerido.

**Value Objects**
- **ConversationId, MessageId, RecommendationId, ActionPlanId, ProjectId, UserId:** identificadores unicos del dominio.
- **ConversationStatus:** estado de conversacion (OPEN, WAITING_CONTEXT, RESOLVED, CLOSED).
- **MessageRole:** rol del mensaje (USER, ASSISTANT, SYSTEM).
- **AssistantChannel:** canal de interaccion (WEB_CHAT, MOBILE_CHAT, API).
- **RecommendationType:** tipo de recomendacion (ALERT_TRIAGE, SERVICE_TUNING, ENERGY_OPTIMIZATION, MAINTENANCE).
- **RecommendationPriority:** prioridad (LOW, MEDIUM, HIGH, CRITICAL).

**Commands**
- StartAssistantConversationCommand
- SendUserMessageCommand
- GenerateAssistantResponseCommand
- CloseAssistantConversationCommand
- CreateAssistantRecommendationCommand
- AcceptAssistantRecommendationCommand
- DismissAssistantRecommendationCommand
- GenerateAssistantActionPlanCommand

**Queries**
- GetConversationByIdQuery
- GetConversationsByProjectIdQuery
- GetConversationMessagesQuery
- GetRecommendationsByProjectIdQuery
- GetPendingRecommendationsQuery
- GetActionPlanByRecommendationIdQuery

**Domain Services (Contratos)**
- AssistantConversationCommandService
- AssistantConversationQueryService
- AssistantRecommendationCommandService
- AssistantRecommendationQueryService
- AssistantActionPlanCommandService
- AssistantActionPlanQueryService

#### 2.6.3.2. Interface Layer
La capa de interfaz expone endpoints REST para interactuar con el asistente, administrar recomendaciones y consultar planes de accion.

**Controllers**
- **AssistantConversationsController:** inicio de conversacion, envio de mensajes, cierre y consultas de historial.
- **AssistantRecommendationsController:** creacion, aceptacion, descarte y consulta de recomendaciones.
- **AssistantActionPlansController:** generacion y consulta de planes de accion asociados a recomendaciones.

**Resources (Request/Query DTOs)**
- **Conversations:** StartAssistantConversationResource, SendUserMessageResource, GenerateAssistantResponseResource, CloseAssistantConversationResource.
- **Recommendations:** CreateAssistantRecommendationResource, AcceptAssistantRecommendationResource, DismissAssistantRecommendationResource.
- **Action Plans:** GenerateAssistantActionPlanResource.
- **Queries:** GetConversationByIdResource, GetConversationsByProjectIdResource, GetConversationMessagesResource, GetRecommendationsByProjectIdResource, GetPendingRecommendationsResource, GetActionPlanByRecommendationIdResource.

**Smart Assistant Interface Diagram**
![Smart Assistant Interface Diagram](https://instasize.com/api/image/f00d4edcae97cb8e384659f46342e12d43ad825eec9ea7cdeaf51d53e584f900.png)

#### 2.6.3.3. Application Layer
La capa de aplicacion orquesta la interaccion del asistente con el contexto del proyecto para responder consultas, generar recomendaciones y proponer planes accionables.

**Command Handlers**
- **AssistantConversationCommandServiceImpl:** StartAssistantConversationCommand, SendUserMessageCommand, GenerateAssistantResponseCommand, CloseAssistantConversationCommand.
- **AssistantRecommendationCommandServiceImpl:** CreateAssistantRecommendationCommand, AcceptAssistantRecommendationCommand, DismissAssistantRecommendationCommand.
- **AssistantActionPlanCommandServiceImpl:** GenerateAssistantActionPlanCommand.

**Query Handlers**
- **AssistantConversationQueryServiceImpl:** GetConversationByIdQuery, GetConversationsByProjectIdQuery, GetConversationMessagesQuery.
- **AssistantRecommendationQueryServiceImpl:** GetRecommendationsByProjectIdQuery, GetPendingRecommendationsQuery.
- **AssistantActionPlanQueryServiceImpl:** GetActionPlanByRecommendationIdQuery.

**Smart Assistant Application Diagram**
![Smart Assistant Application Diagram](https://instasize.com/api/image/c1e93fdfadf169bc27b0c35f392c880a7e7cf8277875b5ca32146081bf2f4cae.png)

#### 2.6.3.4. Infrastructure Layer
La capa de infraestructura implementa persistencia de conversaciones, mensajes, recomendaciones y planes de accion para asegurar trazabilidad de la asistencia inteligente.

**Repositories**
- **AssistantConversationRepository:** consultas por projectId, estado de conversacion y usuario.
- **AssistantMessageRepository:** historial de mensajes por conversationId y orden cronologico.
- **AssistantRecommendationRepository:** recomendaciones por proyecto, prioridad y estado de aceptacion.
- **AssistantActionPlanRepository:** planes de accion por recommendationId.

##### Aggregate Persistence Rule

ExecutionTask es una entidad interna del aggregate ServiceExecution y su persistencia se gestiona a través de ServiceExecutionRepository para mantener consistencia transaccional del aggregate.

**Smart Assistant Infrastructure Diagram**
![Smart Assistant Infrastructure Diagram](https://instasize.com/api/image/30c135e534c0d290f7f1eb2b52a4639e2d8ea4d833724136d9d91420f37e6c99.png)
#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

<!--
workspace "IoBuild - Smart Assistant (Component Diagram)" "C4 Component Diagram del bounded context Smart Assistant" {

    model {
        builder = person "Builder" "Usa asistencia contextual."
        landlord = person "Landlord" "Solicita recomendaciones."

        llm = softwareSystem "External LLM Provider" "Proveedor IA externo (OpenAI u otro)."

        iobuild = softwareSystem "IoBuild" {

            mysql = container "MySQL Database" "Persistencia conversacional." "MySQL 8"

            saApi = container "Smart Assistant API" "Conversaciones, recomendaciones y planes de acción." "ASP.NET Core Web API" {
                convController = component "AssistantConversationsController" "Endpoints de conversación." "ASP.NET Core MVC Controller"
                recController = component "AssistantRecommendationsController" "Endpoints de recomendaciones." "ASP.NET Core MVC Controller"
                planController = component "AssistantActionPlansController" "Endpoints de planes." "ASP.NET Core MVC Controller"

                convCmd = component "AssistantConversationCommandServiceImpl" "Comandos de conversación." "Application Service (C#)"
                convQry = component "AssistantConversationQueryServiceImpl" "Queries de conversación." "Application Service (C#)"
                recCmd = component "AssistantRecommendationCommandServiceImpl" "Comandos de recomendación." "Application Service (C#)"
                recQry = component "AssistantRecommendationQueryServiceImpl" "Queries de recomendación." "Application Service (C#)"
                planCmd = component "AssistantActionPlanCommandServiceImpl" "Comandos de plan." "Application Service (C#)"
                planQry = component "AssistantActionPlanQueryServiceImpl" "Queries de plan." "Application Service (C#)"

                conversationAgg = component "AssistantConversation Aggregate" "Reglas de conversación y contexto." "Domain Model (DDD)"
                recommendationEntity = component "AssistantRecommendation Entity" "Recomendaciones accionables." "Domain Entity"
                actionPlanEntity = component "AssistantActionPlan Entity" "Planes accionables." "Domain Entity"

                aiPort = component "AssistantAIService" "Puerto de dominio para IA (ACL)." "Domain Interface"
                aiAdapter = component "OpenAIAssistantAdapter / ExternalLLMAdapter" "Adaptador infraestructura a proveedor externo." "Infrastructure Adapter"

                convRepo = component "AssistantConversationRepository" "Persistencia de conversaciones." "Repository"
                msgRepo = component "AssistantMessageRepository" "Persistencia de mensajes." "Repository"
                recRepo = component "AssistantRecommendationRepository" "Persistencia de recomendaciones." "Repository"
                planRepo = component "AssistantActionPlanRepository" "Persistencia de planes." "Repository"
            }
        }

        builder -> saApi "Usa" "HTTPS/JSON"
        landlord -> saApi "Usa" "HTTPS/JSON"

        convController -> convCmd "Comandos"
        convController -> convQry "Queries"
        recController -> recCmd "Comandos"
        recController -> recQry "Queries"
        planController -> planCmd "Comandos"
        planController -> planQry "Queries"

        convCmd -> conversationAgg "Orquesta"
        convQry -> conversationAgg "Consulta"
        recCmd -> recommendationEntity "Gestiona"
        recQry -> recommendationEntity "Consulta"
        planCmd -> actionPlanEntity "Gestiona"
        planQry -> actionPlanEntity "Consulta"

        convCmd -> aiPort "Solicita generación"
        recCmd -> aiPort "Solicita recomendaciones"
        aiAdapter -> aiPort "Implementa"
        aiAdapter -> llm "Invoca API" "HTTPS"

        convCmd -> convRepo "Persiste"
        convQry -> convRepo "Consulta"
        convCmd -> msgRepo "Persiste"
        recCmd -> recRepo "Persiste"
        recQry -> recRepo "Consulta"
        planCmd -> planRepo "Persiste"
        planQry -> planRepo "Consulta"

        convRepo -> mysql "CRUD" "SQL/TCP"
        msgRepo -> mysql "CRUD" "SQL/TCP"
        recRepo -> mysql "CRUD" "SQL/TCP"
        planRepo -> mysql "CRUD" "SQL/TCP"
    }

    views {
        component saApi "SA-Component" {
            include *
            autolayout lr
        }

        styles {
            element "Person" {
                background #08427b
                color #ffffff
                shape person
            }
            element "Software System" {
                background #1168bd
                color #ffffff
            }
            element "Container" {
                background #438dd5
                color #ffffff
            }
            element "Component" {
                background #85bbf0
                color #000000
            }
        }
    }
}
-->

![Diagrama C4](https://i.imgur.com/AQmKgPv.png)

#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams
En esta seccion se presenta el nivel de codigo del bounded context **Smart Assistant**, incluyendo su modelo de dominio y esquema de base de datos.

##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

<div style="display:none">
    ```mermaid
    classDiagram
    direction LR

    class AssistantConversation {
        -ConversationId id
        -ProjectId projectId
        -UserId userId
        -AssistantChannel channel
        -ConversationStatus status
        -DateTime startedAt
        -DateTime closedAt
        +startConversation() void
        +receiveUserMessage(content:string) void
        +generateAssistantResponse() AssistantMessage
        +closeConversation() void
    }

    class AssistantMessage {
        -MessageId id
        -ConversationId conversationId
        -MessageRole role
        -string content
        -string metadataJson
        -DateTime sentAt
    }

    class AssistantRecommendation {
        -RecommendationId id
        -ConversationId conversationId
        -RecommendationType type
        -RecommendationPriority priority
        -string summary
        -bool accepted
        +accept() void
        +dismiss() void
    }

    class AssistantActionPlan {
        -ActionPlanId id
        -RecommendationId recommendationId
        -string stepsJson
        -string executionStatus
        +createFromRecommendation(rec:AssistantRecommendation) AssistantActionPlan
    }

    class ConversationStatus {
        <<enumeration>>
        OPEN
        WAITING_CONTEXT
        RESOLVED
        CLOSED
    }

    class MessageRole {
        <<enumeration>>
        USER
        ASSISTANT
        SYSTEM
    }

    class AssistantChannel {
        <<enumeration>>
        WEB_CHAT
        MOBILE_CHAT
        API
    }

    class RecommendationType {
        <<enumeration>>
        ALERT_TRIAGE
        SERVICE_TUNING
        ENERGY_OPTIMIZATION
        MAINTENANCE
    }

    class RecommendationPriority {
        <<enumeration>>
        LOW
        MEDIUM
        HIGH
        CRITICAL
    }

    class AssistantConversationRepository {
        <<interface>>
        +save(conversation:AssistantConversation) AssistantConversation
        +findById(id:ConversationId) AssistantConversation
        +findByProjectId(projectId:ProjectId) List~AssistantConversation~
    }

    class AssistantAIService {
        <<interface>>
        +generateResponse(context:string) string
        +generateRecommendations(context:string) List~AssistantRecommendation~
    }

    AssistantConversation "1" --> "1..*" AssistantMessage : contains
    AssistantConversation "1" --> "0..*" AssistantRecommendation : generates
    AssistantRecommendation "1" --> "0..1" AssistantActionPlan : derives
    AssistantConversation "1" --> "1" ConversationStatus : has
    AssistantMessage "1" --> "1" MessageRole : has
    AssistantConversation "1" --> "1" AssistantChannel : uses
    AssistantRecommendation "1" --> "1" RecommendationType : classifies
    AssistantRecommendation "1" --> "1" RecommendationPriority : has
    AssistantAIService ..> AssistantConversation : assists
    AssistantConversationRepository ..> AssistantConversation : persists
    ```
</div>

![Diagrama plantUML](https://i.imgur.com/nHDNIB3.png)

##### 2.6.3.6.2. Bounded Context Database Design Diagram
<div style="display:none">

    ```mermaid
    erDiagram
            ASSISTANT_CONVERSATIONS {
            string conversation_id PK
            string project_id
            string user_id
            string channel
            string status
                    datetime started_at
                    datetime closed_at
            }

            ASSISTANT_MESSAGES {
            string message_id PK
            string conversation_id FK
            string role
                    text content
            string metadata_json
                    datetime sent_at
            }

            ASSISTANT_RECOMMENDATIONS {
            string recommendation_id PK
            string conversation_id FK
            string recommendation_type
            string priority
                    text summary
            boolean accepted
                    datetime created_at
            }

            ASSISTANT_ACTION_PLANS {
            string action_plan_id PK
            string recommendation_id FK
            string steps_json
            string execution_status
                    datetime created_at
            }

            ASSISTANT_CONVERSATIONS ||--|{ ASSISTANT_MESSAGES : "stores messages"
            ASSISTANT_CONVERSATIONS ||--o{ ASSISTANT_RECOMMENDATIONS : "produces recommendations"
            ASSISTANT_RECOMMENDATIONS ||--o| ASSISTANT_ACTION_PLANS : "derives plan"
    ```
</div>

![Diagrama lucidchart](https://i.imgur.com/2b7dggg.png)

### 2.6.4. Bounded Context: Energy Management
#### 2.6.4.1. Domain Layer
En **IoBuild**, este bounded context gestiona la medicion, analisis y optimizacion del consumo energetico de los edificios inteligentes. El dominio cubre planes de optimizacion, registro de consumo, deteccion de anomalias y eventos de respuesta a la demanda.

**Entities y Aggregates**
- **EnergyOptimizationPlan (Aggregate Root):** representa el plan de optimizacion energetica de un proyecto (id, projectId, baseline, objetivo de reduccion, ventana de aplicacion y estado).
- **EnergyConsumptionRecord:** representa una lectura de consumo energetico por zona, medidor y periodo de tiempo.
- **EnergyAnomaly:** representa una desviacion del patron esperado de consumo (pico, sobrecarga, consumo fuera de horario o caida abrupta).
- **DemandResponseEvent:** representa un evento operativo para ajustar carga electrica en periodos criticos.

**Value Objects**
- **EnergyPlanId, ConsumptionRecordId, AnomalyId, ResponseEventId, ProjectId, ZoneId, MeterId:** identificadores unicos del dominio.
- **OptimizationStatus:** estado del plan (DRAFT, ACTIVE, PAUSED, COMPLETED, CANCELLED).
- **ConsumptionPeriod:** granularidad de lectura (HOURLY, DAILY, WEEKLY, MONTHLY).
- **EnergyUnit:** unidad de energia (WH, KWH, MWH).
- **AnomalySeverity:** severidad de anomalia (LOW, MEDIUM, HIGH, CRITICAL).
- **DemandResponseStatus:** estado del evento de respuesta (CREATED, IN_PROGRESS, EXECUTED, FAILED, CLOSED).

##### Domain Behavior and Invariants

**AssistantConversation Behavior**
- startConversation()
- receiveUserMessage()
- generateAssistantResponse()
- closeConversation()
- createRecommendation()

**Domain Invariants**
- Una conversación en estado CLOSED no acepta nuevos mensajes.
- Toda recomendación debe estar asociada a una conversación activa.
- Los planes de acción solo pueden generarse desde recomendaciones existentes.

##### Domain Events

- AssistantConversationStarted
- AssistantMessageReceived
- AssistantResponseGenerated
- AssistantRecommendationGenerated
- AssistantActionPlanCreated

**Commands**
- CreateEnergyOptimizationPlanCommand
- ActivateEnergyOptimizationPlanCommand
- PauseEnergyOptimizationPlanCommand
- RegisterEnergyConsumptionCommand
- DetectEnergyAnomalyCommand
- AcknowledgeEnergyAnomalyCommand
- CreateDemandResponseEventCommand
- CompleteDemandResponseEventCommand

**Queries**
- GetOptimizationPlanByIdQuery
- GetOptimizationPlansByProjectIdQuery
- GetConsumptionByProjectIdQuery
- GetConsumptionByZoneIdQuery
- GetEnergyAnomaliesByProjectIdQuery
- GetActiveDemandResponseEventsQuery
- GetEnergySavingsSummaryByProjectIdQuery

**Domain Services (Contratos)**
- EnergyOptimizationCommandService
- EnergyOptimizationQueryService
- EnergyMonitoringCommandService
- EnergyMonitoringQueryService
- DemandResponseCommandService
- DemandResponseQueryService
- EnergySavingsAnalysisService

#### 2.6.4.2. Interface Layer
La capa de interfaz expone endpoints REST para crear planes de optimizacion, registrar consumo, gestionar anomalias y ejecutar eventos de respuesta a la demanda.

**Controllers**
- **EnergyOptimizationPlansController:** creacion, activacion, pausa y consultas de planes de optimizacion.
- **EnergyMonitoringController:** registro de consumo, deteccion/revision de anomalias y consultas operativas.
- **DemandResponseController:** apertura, cierre y consulta de eventos de respuesta a la demanda.

**Resources (Request/Query DTOs)**
- **Optimization:** CreateEnergyOptimizationPlanResource, ActivateEnergyOptimizationPlanResource, PauseEnergyOptimizationPlanResource.
- **Monitoring:** RegisterEnergyConsumptionResource, DetectEnergyAnomalyResource, AcknowledgeEnergyAnomalyResource.
- **Demand Response:** CreateDemandResponseEventResource, CompleteDemandResponseEventResource.
- **Queries:** GetOptimizationPlanByIdResource, GetOptimizationPlansByProjectIdResource, GetConsumptionByProjectIdResource, GetConsumptionByZoneIdResource, GetEnergyAnomaliesByProjectIdResource, GetActiveDemandResponseEventsResource, GetEnergySavingsSummaryByProjectIdResource.

**Energy Management Interface Diagram**
![Energy Management Interface Diagram](https://instasize.com/api/image/3be25a2e254b035f27c7ecdb7b05bb59883da84db0dbb2b70a1b26ef89bff79b.png)

#### 2.6.4.3. Application Layer
La capa de aplicacion orquesta comandos y consultas para convertir datos de consumo en decisiones operativas de eficiencia energetica.

**Command Handlers**
- **EnergyOptimizationCommandServiceImpl:** CreateEnergyOptimizationPlanCommand, ActivateEnergyOptimizationPlanCommand, PauseEnergyOptimizationPlanCommand.
- **EnergyMonitoringCommandServiceImpl:** RegisterEnergyConsumptionCommand, DetectEnergyAnomalyCommand, AcknowledgeEnergyAnomalyCommand.
- **DemandResponseCommandServiceImpl:** CreateDemandResponseEventCommand, CompleteDemandResponseEventCommand.

**Query Handlers**
- **EnergyOptimizationQueryServiceImpl:** GetOptimizationPlanByIdQuery, GetOptimizationPlansByProjectIdQuery.
- **EnergyMonitoringQueryServiceImpl:** GetConsumptionByProjectIdQuery, GetConsumptionByZoneIdQuery, GetEnergyAnomaliesByProjectIdQuery, GetEnergySavingsSummaryByProjectIdQuery.
- **DemandResponseQueryServiceImpl:** GetActiveDemandResponseEventsQuery.

**Energy Management Application Diagram**
![Energy Management Application Diagram](https://instasize.com/api/image/5bb792141cfabc4249c13bd8e17c84a6a90107bd2fd33d9f018e89a5e9a35127.png)

#### 2.6.4.4. Infrastructure Layer
La capa de infraestructura implementa persistencia de planes de optimizacion, lecturas de consumo, anomalias y eventos de respuesta para soportar analitica historica y operacion en tiempo real.

**Repositories**
- **EnergyOptimizationPlanRepository:** planes por projectId, estado de optimizacion y planes activos.
- **EnergyConsumptionRecordRepository:** lecturas por projectId, zoneId, meterId y rango temporal.
- **EnergyAnomalyRepository:** anomalias por proyecto, severidad y estado abierto/cerrado.
- **DemandResponseEventRepository:** eventos por proyecto, estado y eventos activos.

**Energy Management Infrastructure Diagram**
![Energy Management Infrastructure Diagram](https://instasize.com/api/image/ebde2d543f68889ecb0ca0460f113851d31f2dafc5549e80d83402882b863d54.png)

##### AI Integration Anti-Corruption Layer

Para evitar acoplamiento directo con proveedores externos de inteligencia artificial, el sistema define:

- AssistantAIService (Domain Interface)

Implementaciones en infraestructura:

- OpenAIAssistantAdapter
- ExternalLLMAdapter

Este patrón protege el dominio frente a cambios tecnológicos del proveedor IA.

#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

<!--

workspace "IoBuild - Energy Management (Component Diagram)" "C4 Component Diagram del bounded context Energy Management" {

    model {
        builder = person "Builder" "Configura planes energéticos."
        landlord = person "Landlord" "Monitorea consumo y ahorros."

        iobuild = softwareSystem "IoBuild" {

        emApi = container "Energy Management API" "Optimización energética, consumo, anomalías y demand response." "ASP.NET Core Web API" {
            plansController = component "EnergyOptimizationPlansController" "Endpoints de planes energéticos." "ASP.NET Core MVC Controller"
            monitoringController = component "EnergyMonitoringController" "Endpoints de consumo y anomalías." "ASP.NET Core MVC Controller"
            drController = component "DemandResponseController" "Endpoints de eventos de demanda." "ASP.NET Core MVC Controller"

            optCmd = component "EnergyOptimizationCommandServiceImpl" "Comandos de optimización." "Application Service (C#)"
            optQry = component "EnergyOptimizationQueryServiceImpl" "Queries de optimización." "Application Service (C#)"
            monCmd = component "EnergyMonitoringCommandServiceImpl" "Comandos de monitoreo energético." "Application Service (C#)"
            monQry = component "EnergyMonitoringQueryServiceImpl" "Queries de monitoreo energético." "Application Service (C#)"
            drCmd = component "DemandResponseCommandServiceImpl" "Comandos de demand response." "Application Service (C#)"
            drQry = component "DemandResponseQueryServiceImpl" "Queries de demand response." "Application Service (C#)"

            planAgg = component "EnergyOptimizationPlan Aggregate" "Reglas del plan de optimización." "Domain Model (DDD)"
            consumptionEntity = component "EnergyConsumptionRecord Entity" "Lecturas de consumo." "Domain Entity"
            anomalyEntity = component "EnergyAnomaly Entity" "Detección de anomalías." "Domain Entity"
            demandEntity = component "DemandResponseEvent Entity" "Eventos de respuesta a demanda." "Domain Entity"
            savingsSvc = component "EnergySavingsAnalysisService" "Cálculo de ahorro energético." "Domain Service"

            planRepo = component "EnergyOptimizationPlanRepository" "Persistencia de planes." "Repository"
            consumptionRepo = component "EnergyConsumptionRecordRepository" "Persistencia de consumo." "Repository"
            anomalyRepo = component "EnergyAnomalyRepository" "Persistencia de anomalías." "Repository"
            demandRepo = component "DemandResponseEventRepository" "Persistencia de eventos DR." "Repository"
        }

        mysql = container "MySQL Database" "Persistencia energética." "MySQL 8"
        eventStream = container "Event Stream" "Eventos energéticos." "Kafka / RabbitMQ"
    }

        builder -> emApi "Usa" "HTTPS/JSON"
        landlord -> emApi "Consulta" "HTTPS/JSON"

        plansController -> optCmd "Comandos"
        plansController -> optQry "Queries"
        monitoringController -> monCmd "Comandos"
        monitoringController -> monQry "Queries"
        drController -> drCmd "Comandos"
        drController -> drQry "Queries"

        optCmd -> planAgg "Orquesta"
        optQry -> planAgg "Consulta"
        monCmd -> consumptionEntity "Registra"
        monCmd -> anomalyEntity "Detecta"
        monQry -> consumptionEntity "Consulta"
        monQry -> anomalyEntity "Consulta"
        drCmd -> demandEntity "Orquesta"
        drQry -> demandEntity "Consulta"
        monQry -> savingsSvc "Calcula ahorro"

        optCmd -> planRepo "Persiste"
        optQry -> planRepo "Consulta"
        monCmd -> consumptionRepo "Persiste"
        monQry -> consumptionRepo "Consulta"
        monCmd -> anomalyRepo "Persiste"
        monQry -> anomalyRepo "Consulta"
        drCmd -> demandRepo "Persiste"
        drQry -> demandRepo "Consulta"

        planRepo -> mysql "CRUD" "SQL/TCP"
        consumptionRepo -> mysql "CRUD" "SQL/TCP"
        anomalyRepo -> mysql "CRUD" "SQL/TCP"
        demandRepo -> mysql "CRUD" "SQL/TCP"

        planAgg -> eventStream "Publica eventos" "AMQP/Kafka"
        demandEntity -> eventStream "Publica eventos DR" "AMQP/Kafka"
    }

    views {
        component emApi "EM-Component" {
            include *
            autolayout lr
        }

        styles {
            element "Person" {
                background #08427b
                color #ffffff
                shape person
            }
            element "Software System" {
                background #1168bd
                color #ffffff
            }
            element "Container" {
                background #438dd5
                color #ffffff
            }
            element "Component" {
                background #85bbf0
                color #000000
            }
        }
    }
}

-->

![Diagrama C4](https://i.imgur.com/XKGyZ20.png)

#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams
En esta seccion se presenta el detalle de implementacion de **Energy Management** a nivel de clases de dominio y persistencia relacional.

##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams
<div style="display:none">
    ```mermaid
    classDiagram
    direction LR

    class EnergyOptimizationPlan {
        -EnergyPlanId id
        -ProjectId projectId
        -float baselineKwh
        -float reductionTargetPercent
        -DateRange applicationWindow
        -OptimizationStatus status
        +activate() void
        +pause() void
        +complete() void
    }

    class EnergyConsumptionRecord {
        -ConsumptionRecordId id
        -ProjectId projectId
        -ZoneId zoneId
        -MeterId meterId
        -float value
        -EnergyUnit unit
        -ConsumptionPeriod period
        -DateTime recordedAt
    }

    class EnergyAnomaly {
        -AnomalyId id
        -ProjectId projectId
        -ZoneId zoneId
        -AnomalySeverity severity
        -string detectedPattern
        -bool acknowledged
        +acknowledge() void
    }

    class DemandResponseEvent {
        -ResponseEventId id
        -ProjectId projectId
        -string eventName
        -DemandResponseStatus status
        -DateTime startsAt
        -DateTime endsAt
        +start() void
        +complete() void
    }

    class OptimizationStatus {
        <<enumeration>>
        DRAFT
        ACTIVE
        PAUSED
        COMPLETED
        CANCELLED
    }

    class ConsumptionPeriod {
        <<enumeration>>
        HOURLY
        DAILY
        WEEKLY
        MONTHLY
    }

    class EnergyUnit {
        <<enumeration>>
        WH
        KWH
        MWH
    }

    class AnomalySeverity {
        <<enumeration>>
        LOW
        MEDIUM
        HIGH
        CRITICAL
    }

    class DemandResponseStatus {
        <<enumeration>>
        CREATED
        IN_PROGRESS
        EXECUTED
        FAILED
        CLOSED
    }

    class EnergyOptimizationPlanRepository {
        <<interface>>
        +save(plan:EnergyOptimizationPlan) EnergyOptimizationPlan
        +findById(id:EnergyPlanId) EnergyOptimizationPlan
        +findByProjectId(projectId:ProjectId) List~EnergyOptimizationPlan~
    }

    class EnergySavingsAnalysisService {
        <<interface>>
        +calculateSavings(projectId:ProjectId,period:ConsumptionPeriod) float
    }

    EnergyOptimizationPlan "1" --> "0..*" EnergyConsumptionRecord : analyzes
    EnergyOptimizationPlan "1" --> "0..*" EnergyAnomaly : reacts to
    EnergyOptimizationPlan "1" --> "0..*" DemandResponseEvent : triggers
    EnergyOptimizationPlan "1" --> "1" OptimizationStatus : has
    EnergyConsumptionRecord "1" --> "1" ConsumptionPeriod : has
    EnergyConsumptionRecord "1" --> "1" EnergyUnit : has
    EnergyAnomaly "1" --> "1" AnomalySeverity : has
    DemandResponseEvent "1" --> "1" DemandResponseStatus : has
    EnergySavingsAnalysisService ..> EnergyConsumptionRecord : analyzes
    EnergyOptimizationPlanRepository ..> EnergyOptimizationPlan : persists
    ```
</div>

![Diagrama plantUML](https://i.imgur.com/VxFxqqC.png)

##### 2.6.4.6.2. Bounded Context Database Design Diagram
<div style="display:none">
    ```mermaid
        erDiagram
            ENERGY_OPTIMIZATION_PLANS {
            string energy_plan_id PK
            string project_id
            float baseline_kwh
            float reduction_target_percent
                    datetime window_start
                    datetime window_end
            string status
                    datetime created_at
            }

            ENERGY_CONSUMPTION_RECORDS {
            string consumption_record_id PK
            string energy_plan_id FK
            string project_id
            string zone_id
            string meter_id
            float value
            string unit
            string period
                    datetime recorded_at
            }

            ENERGY_ANOMALIES {
            string anomaly_id PK
            string energy_plan_id FK
            string project_id
            string zone_id
            string severity
            string detected_pattern
            boolean acknowledged
                    datetime detected_at
            }

            DEMAND_RESPONSE_EVENTS {
            string response_event_id PK
            string energy_plan_id FK
            string project_id
            string event_name
            string status
                    datetime starts_at
                    datetime ends_at
            }

            ENERGY_OPTIMIZATION_PLANS ||--o{ ENERGY_CONSUMPTION_RECORDS : "contains records"
            ENERGY_OPTIMIZATION_PLANS ||--o{ ENERGY_ANOMALIES : "detects anomalies"
            ENERGY_OPTIMIZATION_PLANS ||--o{ DEMAND_RESPONSE_EVENTS : "schedules events"
    ```
</div>

![Diagrama LucidChart](https://i.imgur.com/bxwcuZp.png)

## Capítulo III: Solution UI/UX Design

### 3.1. Product design
#### 3.1.1. Style Guidelines
##### 3.1.1.1. General Style Guidelines
#### **Tipografía**
La tipografía seleccionada para los encabezados de nuestra marca es **Poppins**, debido a su estilo moderno. Su diseño elegante permite destacar títulos y secciones importantes, generando un impacto claro y atractivo para los usuarios. Esto la convierte en una elección ideal para comunicar innovación y profesionalismo dentro de la identidad visual.

Para el cuerpo de texto, se eligió **Roboto**, una tipografía ampliamente reconocida por su legibilidad en entornos digitales. Su diseño asegura una experiencia de lectura cómoda incluso en párrafos extensos. Al combinarse con Poppins, se logra un contraste armónico que refuerza la jerarquía tipográfica y facilita la comprensión del contenido.

Los tamaños tipográficos definidos, desde los **12px (0.75rem)** para detalles secundarios hasta los **36px (2.25rem)** para títulos principales, garantizan una estructura clara y ordenada. En conjunto, las elecciones tipográficas y de tamaños consolidan una comunicación visual coherente y funcional.

#### **Colores**
La elección de la paleta de colores en nuestro proyecto obedece a una estrategia visual cuidadosamente planificada, orientada a reflejar tecnología, confianza y sofisticación, valores fundamentales en la propuesta de CcaritaTech.

- **Landing Page** <br>
  ![Imagen de la paleta de colores del landing page](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Paleta_Colores.png)

En la identidad visual, el color **verde menta primario (#10B981)** cumple el rol principal como color distintivo de la marca. Su tono fresco y vibrante transmite innovación y confianza, características que refuerzan la propuesta de valor de nuestro proyecto. Al mismo tiempo, este color genera una sensación positiva y cercana, lo que ayuda a establecer una conexión emocional con el usuario desde el primer contacto.

Para lograr versatilidad y equilibrio, se incorporan dos variaciones del color primario. El color **menta claro (#ECFDF5)** se utiliza en fondos y áreas de descanso visual, ofreciendo luminosidad y amplitud sin perder coherencia cromática. Por su parte, el color **menta oscuro (#059669)** se reserva para realizar el contraste en los botones ya que para estos se usa el color menta claro. Este color aporta estructura y profesionalismo, asegurando que la información crítica sea fácilmente distinguible.

En cuanto a la gama neutra, el **gris muy claro (#F9FAFB)** funciona como base para pantallas y secciones de contenido. Su neutralidad transmite orden y simplicidad, garantizando legibilidad y claridad al dar protagonismo a los elementos interactivos. En contraste, el **gris muy oscuro (#111827)** se emplea en títulos, encabezados y áreas que requieren solidez visual. Este color aporta estructura y profesionalismo, asegurando que la información crítica sea fácilmente distinguible.

Para complementar la lectura, el sistema tipográfico integra dos niveles de color en los textos. El **texto primario (#111827)**, de alto contraste sobre fondos claros, asegura una comprensión inmediata y sin esfuerzo. En paralelo, el **texto secundario (#6B7280)** se aplica en descripciones, anotaciones o contenidos de menor jerarquía. Este gris intermedio suaviza la presentación de la información y evita la saturación visual, manteniendo un estilo moderno y equilibrado.

En conjunto, esta paleta de verdes menta combinados con grises neutros y acentos bien definidos construye una interfaz clara, fresca y profesional. La coherencia cromática no solo mejora la experiencia de usuario, sino que también refuerza los valores de accesibilidad, confianza y modernidad que nuestra marca desea transmitir.

#### **Lenguaje**
En IoBuild, utilizaremos un lenguaje que refleje nuestra visión de transformar la construcción residencial mediante la integración inteligente de tecnología desde el diseño. Queremos conectar tanto con constructoras y desarrolladores como con los futuros propietarios, manteniendo siempre una comunicación clara, cercana y profesional. La combinación de tonos que emplearemos es la siguiente:

1. **Profesional pero accesible:** Nuestro objetivo es transmitir seriedad y conocimiento en la aplicación de soluciones tecnológicas a la construcción, sin dejar de ser comprensibles para todos los actores involucrados. Nuestro lenguaje estará planteado de manera clara y cercana, de modo que tanto expertos como clientes puedan comprender el valor de nuestra propuesta sin barreras.

2. **Formal pero cálido:** Si bien mantenemos un tono formal que exprese compromiso, seguridad y confiabilidad, también buscamos acercarnos a nuestros usuarios de una manera humana y auténtica. Queremos que desarrolladores y propietarios sientan que IoBuild no solo ofrece tecnología, sino también acompañamiento y confianza en cada etapa del proceso.

3. **Respetuoso y empático:** Reconocemos la diversidad de necesidades en el sector, desde constructoras que buscan eficiencia hasta propietarios que desean hogares adaptables y modernos. Nuestro lenguaje transmitirá respeto, promoviendo una relación colaborativa y de apoyo mutuo.

4. **Inspirador y optimista:** En IoBuild creemos que el futuro de la construcción es más sostenible, adaptable y tecnológico. Por ello, nos comunicaremos con entusiasmo y convicción, motivando a nuestros usuarios a visualizar y construir una nueva forma de habitar hogares inteligentes.

#### 3.1.2. Information Architecture

UX Heuristics & Principles Evaluation<br>
Usability – Inclusive Design – Information Architecture<br>
CARRERA: Ingeniería de Software<br>
CURSO: Aplicaciones para Dispositivos Móviles<br>
NRC: 3687<br>
PROFESOR: David Gerardo Quevedo Velazco<br>
CLIENTE(S): Javier Maximo Ordoñez Cordova, Christy Karen Callata Alvarez<br>
SITE o APP A EVALUAR: CcaritaTech

TAREAS A EVALUAR:<br>
El alcance de esta evaluación contempla el análisis de la usabilidad en la ejecución de las siguientes tareas:<br>

Segmento Objetivo #1: Arquitectos e Ingenieros Civiles
- **Configurar funcionalidades inteligentes:** Claridad y facilidad para integrar automatización (iluminación, climatización, seguridad, riego, etc.) dentro de la plataforma.
- **Gestionar proyectos y roles técnicos:** Facilidad para asignar permisos y colaborar con otros profesionales dentro del mismo entorno.
- **Acceder a documentación y guías técnicas:** Disponibilidad, organización y comprensión de recursos de soporte (manuales, tutoriales, BIM).

Segmento Objetivo #2: Dueños de Apartamentos (Usuarios Finales)
- **Controlar dispositivos desde un único panel:** Usabilidad de la interfaz centralizada para manejar iluminación, clima, seguridad y energía.
- **Recibir notificaciones y alertas personalizadas:** Facilidad para activar, modificar y entender las notificaciones sobre consumo energético o seguridad.
- **Acceder a reportes de consumo y eficiencia:** Claridad de la información mostrada y utilidad para la toma de decisiones sobre ahorro energético.


##### 3.1.2.1. Organization Systems

Dentro del diseño de interfaces digitales enfocadas en el usuario, el Organization System funciona como la base de la arquitectura de información, definiendo cómo se ordenan, agrupan y muestran los contenidos en la plataforma. Su propósito es facilitar la comprensión y la navegación, permitiendo que los usuarios encuentren de manera sencilla la propuesta de valor y los recursos más importantes. Este sistema ayuda a disminuir la carga mental, dirigir la atención hacia lo esencial y mejorar la experiencia general de interacción con el producto.

En el caso de IoBuild, la Landing Page implementa un sistema de organización jerárquico y temático, pensado para comunicar de forma clara el propósito de la aplicación y dirigir la acción del visitante. La estructura se organiza en bloques que siguen una lógica de prioridad: en primer lugar, se despliega un hero section con un mensaje directo sobre la propuesta de valor y un llamado a la acción destacado (“Explora IoBuild”), seguido de secciones que detallan los beneficios de la plataforma para arquitectos, ingenieros y propietarios de viviendas. Posteriormente, se integran apartados complementarios como la presentación del equipo, los objetivos del proyecto y los canales de contacto.

Tanto el header como el footer refuerzan esta organización al centralizar los accesos principales de navegación (inicio, características, contacto) y los secundarios (redes sociales y enlaces informativos). Esta disposición garantiza que los usuarios comprendan de manera inmediata qué es IoBuild, para quién está dirigido y cómo pueden empezar a interactuar con la solución. Además, la página aplica principios como la progressive disclosure y el diseño responsivo, asegurando una experiencia fluida y clara en dispositivos móviles y de escritorio.

##### 3.1.2.2. Labelling Systems

En el marco del diseño de la arquitectura de información, los Labeling Systems cumplen la función de comunicar de forma clara, coherente y predecible los elementos de interacción presentes en la interfaz. En IoBuild, cada etiqueta textual utilizada en botones, menús, enlaces y secciones está orientada a guiar al usuario en su recorrido por la Landing Page, facilitando la comprensión del propósito del proyecto y motivando la interacción con los elementos principales.

La siguiente tabla resume las etiquetas implementadas, su ubicación y su función en la experiencia de usuario:

| Etiqueta | Ubicación/Componente | Función |
|----------|----------------------|---------|
| Inicio | Header | Enlace a la página principal. Término estándar y familiar para usuarios. |
| Sobre Nosotros | Header | Presentación del propósito y misión del proyecto. Genera cercanía y confianza. |
| Equipo | Header | Sección dedicada al grupo desarrollador, destacando transparencia y credibilidad. |
| Contacto | Header | Canal directo para comunicación con el equipo. Claro y orientado a la acción. |
| Explora IoBuild | Hero Section (CTA principal) | Llamada a la acción inmediata para iniciar interacción con la plataforma. Imperativo motiva al usuario. |
| Objetivos | Sección informativa | Describe las metas del proyecto. Etiqueta concisa y orientada al valor. |
| Proyecto | Sección informativa | Explica en detalle la propuesta tecnológica. Término claro y descriptivo. |
| Contáctanos | Footer | Refuerzo del canal de comunicación, mantiene consistencia semántica. |
| Síguenos | Footer / Redes sociales | Agrupa accesos a redes sociales. Etiqueta convencional y reconocida globalmente. |
| IoBuild | Marca | Nombre distintivo en mayúsculas. Actúa como ancla visual e identitaria del sitio. |

El sistema de etiquetado en la Landing Page de IoBuild refleja una aplicación consistente de principios de usabilidad y arquitectura de información. Las etiquetas emplean un lenguaje simple, reconocible y orientado a la acción, lo que facilita tanto la navegación como la comprensión inmediata de los contenidos. Asimismo, existe una coherencia semántica entre el header, el cuerpo de la página y el footer, acompañada de un uso de imperativos y sustantivos comunes que refuerzan la accesibilidad cognitiva. Este Labeling System contribuye a la claridad, consistencia y escalabilidad de la experiencia web, garantizando que tanto profesionales técnicos como usuarios finales puedan interactuar sin fricciones con la plataforma.

##### 3.1.2.3. SEO Tags and Meta Tags

Los meta tags y etiquetas SEO son elementos esenciales dentro de la sección <head> de cualquier página web, ya que permiten definir cómo es interpretado, indexado y presentado el contenido de un sitio por parte de los motores de búsqueda (como Google) y las redes sociales (como Facebook, Twitter o LinkedIn). Aunque estos elementos no son visibles de forma directa para los usuarios, desempeñan un papel crucial en el posicionamiento orgánico, en la forma en que los enlaces se muestran al compartirse y en la claridad con la que se comunica la propuesta de valor del sitio.

En el caso de la Landing Page de IoBuild, se han incorporado meta etiquetas específicas con el objetivo de optimizar la indexación y visibilidad de la plataforma. La meta descripción resume de manera breve y clara la propuesta de IoBuild como una solución tecnológica orientada a la gestión y personalización de espacios inteligentes. Asimismo, se han definido meta keywords que incluyen términos relevantes como IoT, domótica, arquitectura inteligente, automatización de espacios y gestión de hogares inteligentes, lo que refuerza la capacidad del sitio para aparecer en búsquedas relacionadas.

#### 1. Index
La página principal de IoBuild incorpora un conjunto de etiquetas SEO que fortalecen su posicionamiento y presencia digital. Se incluyen una meta descripción clara sobre la propuesta de valor, palabras clave relacionadas con IoT y automatización residencial, así como etiquetas Open Graph y Twitter Card que aseguran una visualización atractiva y coherente al compartir el sitio en redes sociales. Estas configuraciones, junto con el ajuste de vista responsiva y la codificación adecuada, contribuyen a una experiencia accesible, profesional y optimizada para buscadores y usuarios.
![Imagen de Meta Tags Index](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Meta_Tags_Index.png)

#### 2. About Us
La página Sobre Nosotros de IoBuild incluye etiquetas SEO básicas que refuerzan su propósito informativo y de marca. Se define un título claro y directo, junto con una meta descripción que comunica la misión del proyecto y presenta al equipo como motor de la propuesta de innovación en la industria de la construcción mediante tecnología IoT. Además, se configuran los parámetros técnicos de codificación (UTF-8) y de vista responsiva, asegurando accesibilidad, correcta interpretación del contenido y una experiencia de navegación óptima en distintos dispositivos.
![Imagen de Meta Tags About-Us](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Meta_Tags_AboutUs.png)

#### 3. FAQ
La página FAQ - Preguntas Frecuentes de IoBuild incorpora etiquetas SEO orientadas a brindar claridad y accesibilidad al usuario. Se define un título descriptivo y directo que comunica de inmediato el propósito de la sección, acompañado de una meta descripción que resume su función como espacio de resolución de dudas sobre la plataforma SaaS y sus aplicaciones en proyectos de construcción con IoT. Asimismo, se incluyen configuraciones técnicas esenciales como la codificación UTF-8 y la vista responsiva, garantizando una correcta interpretación del contenido y una experiencia de navegación fluida en diversos dispositivos.
![Imagen de Meta Tags FAQ](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Meta_Tags_FAQ.png)

##### 3.1.2.4. Searching Systems

Al ingresar a la landing page de IoBuild, el usuario será recibido con una sección principal que introduce la propuesta de valor de la plataforma, acompañada de un botón destacado que invita a conocer más sobre sus funcionalidades. En la parte superior, la navegación se organiza mediante un menú claro y accesible que permite desplazarse hacia las secciones clave, como Sobre Nosotros, Preguntas Frecuentes y Contacto. Esta estructura busca brindar una experiencia fluida y ordenada, evitando confusiones y facilitando el acceso a la información más relevante.

La navegación está reforzada con etiquetas descriptivas, jerarquía visual y un diseño responsivo, de manera que el usuario siempre tenga claridad sobre en qué parte del sitio se encuentra y cómo puede avanzar o retroceder dentro del flujo. El enfoque de la interfaz prioriza la simplicidad y la claridad, asegurando que el visitante pueda comprender rápidamente la misión de IoBuild y decidir explorar más a fondo sus soluciones tecnológicas.

##### 3.1.2.5. Navigation Systems

La navegación es un elemento central en la landing page de IoBuild, ya que estructura el recorrido del usuario y facilita el acceso a la información clave sobre la plataforma. Bajo principios de simplicidad, accesibilidad y jerarquía visual, el sistema de navegación ha sido diseñado para garantizar una experiencia clara e intuitiva, tanto en dispositivos de escritorio como en móviles.

IoBuild implementa un sistema de navegación global, persistente y horizontal, ubicado en la parte superior de la página. Este está compuesto por siete elementos principales:
- **Home:** vinculado al logotipo de IoBuild, que permite regresar a la página de inicio desde cualquier sección.
- **Beneficios:** apartado que resalta las ventajas concretas para constructoras y propietarios.
- **Características:** detalle funcional de la plataforma.
- **Planes:** presenta las opciones comerciales y niveles de servicio adecuados para distintos tamaños de proyecto.
- **Sobre Nosotros:** ofrece información acerca de la misión, visión y equipo detrás del proyecto.
- **FAQ:** presenta un apartado de preguntas frecuentes que resuelve las dudas más comunes de los usuarios.
- **Empezar ahora (CTA):** botón destacado que impulsa la conversión (registro o contacto para proyecto), visualmente diferenciado del resto de enlaces.

El diseño del header utiliza un fondo uniforme y elementos textuales de alto contraste, siguiendo un estilo minimalista que evita distracciones y centra la atención en las decisiones de navegación. La organización de los enlaces sigue una estructura en tres zonas: el logotipo alineado a la izquierda, las secciones principales al centro y las acciones de contacto alineadas a la derecha.

En cuanto a adaptabilidad, la barra de navegación está construida bajo un enfoque mobile-first, ajustándose dinámicamente a distintas resoluciones. En pantallas pequeñas, el menú horizontal se convierte en un menú tipo hamburguesa, asegurando que todas las secciones permanezcan accesibles sin comprometer la usabilidad.

Finalmente, la navegación en IoBuild cumple con principios fundamentales de usabilidad:
- **Claridad:** los enlaces son directos y fácilmente identificables.
- **Consistencia:** la barra se mantiene visible y uniforme en todo momento.
- **Jerarquía:** las secciones más consultadas están ubicadas estratégicamente en el centro de la navegación.
- **Retroalimentación visual:** se incluyen estados hover y focus que refuerzan la interacción del usuario.

#### 3.1.3. Landing Page UI Design

La sección de Landing Page UI Design busca definir, estructurar y validar la interfaz visual de la página principal de IoBuild, garantizando una experiencia clara, accesible y centrada en los distintos perfiles de usuario interesados en soluciones IoT para la construcción. Para esta fase se diseñaron los primeros wireframes, los cuales permitieron organizar los contenidos clave como la propuesta de valor de la plataforma, los beneficios, características principales, planes de servicio, sección “Sobre Nosotros”, preguntas frecuentes y un footer con enlaces a contacto y redes sociales. Posteriormente, se elaboraron mockups de alta fidelidad aplicando un sistema de diseño minimalista y funcional, priorizando la jerarquía informativa, la coherencia visual y la consistencia entre dispositivos.


El sitio web de "lobuild" está construido como un viaje lógico y persuasivo, diseñado para guiar a un potencial cliente desde la primera impresión hasta la conversión final, construyendo valor y confianza en cada paso.

El recorrido comienza en la sección de inicio, que capta la atención de inmediato con un titular audaz: "Revoluciona Tus Proyectos Residenciales". Esta primera sección establece la propuesta de valor central, explicando que la plataforma beneficia tanto a los administradores (con gestión centralizada) como a los futuros propietarios (con control personalizado), posicionándose como una solución integral desde el principio.

A continuación, la sección "¿Por qué elegir ioBuild?" profundiza en esta promesa inicial, desglosándola en seis beneficios claros y tangibles. Aborda directamente las motivaciones del cliente, hablando de valor agregado para el proyecto, ahorro de energía, y una integración desde la construcción que evita costos futuros. Esta parte responde a la pregunta fundamental del cliente: "¿Qué gano yo con esto?".

Una vez que el cliente entiende los beneficios, el sitio pasa a demostrar su capacidad técnica en la sección de "Características Técnicas Avanzadas". Aquí se muestra cómo se cumplen las promesas, presentando el dashboard intuitivo, la compatibilidad con un amplio ecosistema de dispositivos y las herramientas especializadas para la gestión de áreas comunes. Esta sección es crucial para generar credibilidad y demostrar que la plataforma es robusta y bien diseñada.

Con el valor y la tecnología ya establecidos, el enfoque se desplaza hacia la construcción de confianza a un nivel más humano. La sección de "Testimonios de clientes" utiliza la prueba social, mostrando a líderes de otras empresas constructoras que validan el éxito, la fiabilidad y el retorno de inversión de la plataforma. Poco después, la página "Sobre Nosotros" complementa esto humanizando la marca, presentando la misión, los valores y, más importante, al equipo de expertos detrás del proyecto. Juntas, estas secciones le dicen al cliente: "Somos expertos en lo que hacemos y otras empresas como la tuya ya confían en nosotros".

Finalmente, el sitio se enfoca en eliminar las últimas barreras para la compra. La página de "Preguntas Frecuentes" se anticipa a cualquier duda restante sobre implementación, precios o soporte, ofreciendo respuestas claras y transparentes. Esto conduce de forma natural a la sección de "Planes de la aplicación", donde la decisión se vuelve tangible. Con una estructura de precios escalable y un plan "Más Popular" claramente destacado, se facilita al cliente la elección de la opción que mejor se adapte a su escala. Por último, el "Footer" o pie de página actúa como una red de seguridad: ofrece un último llamado a la acción y un mapa completo del sitio para quienes necesiten más información, asegurando que ninguna pregunta quede sin respuesta y que el camino para empezar sea siempre accesible.


##### 3.1.3.1. Landing Page Wireframe

[Link ded Figma]<https://shorturl.at/ZkQuE>

#### 1. Home
- La interfaz sigue una estructura en Z con un header fijo con logo y menú principal, un hero section con título, subtítulo y un llamado a la acción destacado (“Empezar ahora”). En las secciones intermedias se presentan los beneficios en formato de tarjetas, seguidos de testimonios y planes de precios. El footer reúne enlaces organizados por categorías, accesos a redes sociales y aviso de copyright. El diseño es claro, escaneable y enfocado en la conversión, guiando al usuario de manera natural desde el primer contacto hasta la acción final.<br>

<img src="https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_Home_Wireframe.png" style="page-break-inside: auto; break-inside: auto; display: block;">
<br>

#### 1. About Us
- El wireframe de About se organiza en un esquema de columnas, a la izquierda se ubican el título y los párrafos descriptivos, mientras que a la derecha se reserva un espacio para la imagen. La página integra secciones jerarquizadas que construyen una narrativa clara sobre la identidad de la marca. En la parte inferior se disponen tarjetas con íconos y descripciones, seguidas de la presentación del equipo con un miembro destacado y cuatro integrantes adicionales. La composición se enmarca con una navegación principal en la parte superior y un footer completo al final, manteniendo coherencia visual y un flujo narrativo fluido.<br>

![Landing page About-us Wireframe](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_About-us_Wireframe.png)
<br>

#### 1. FAQ
- La sección adopta un acordeón vertical, donde cada pregunta se despliega para mostrar respuestas detalladas. Los contenidos abarcan temas clave como precios, diseño, edición y alianzas. En la parte superior, filtros por categoría facilitan la exploración del material, mientras que en la parte inferior un CTA “Didn’t Find Your Answer?” dirige a la página de contacto. El diseño mantiene un estilo minimalista y ordenado, y una jerarquía visual clara, optimizada para la legibilidad y una experiencia sin distracciones.<br>

![Landing page FAQ 1 Wireframe](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ_Wireframe.png)

![Landing page FAQ 2 Wireframe](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ2_Wireframe.png)
<br>

##### 3.1.3.2. Landing Page Mock-up

[Link ded Figma]<https://shorturl.at/ZkQuE>

#### 1. Home
- El mockup de la página principal presenta una estética moderna y minimalista, enfocada en la claridad y la atracción visual. En la parte superior, el header integra el logo junto con enlaces a Benefits, Features, Plans, About Us y FAQ, además de un botón de llamado a la acción “Get Started”. El hero section concentra la atención con un título llamativo y un botón CTA (“I want it!”) sobre un fondo verde claro. Más abajo, el contenido se organiza en bloques visuales con imágenes y una tipografía legible, destacando secciones como “Advanced Technical Features” y “Plans Designed for Your Scale”. Finalmente, el footer reúne enlaces estructurados (Home Page, Community, Legal, Company), íconos de redes sociales y un mensaje de marca que refuerza la identidad visual del sitio.

![Landing page Home Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_Home_Mock-up.png)
<br>

#### 2. About Us
- Esta sección presenta una introducción sobre la misión de CcaritaTech, destacando su enfoque en la innovación y el impacto social. Le siguen las secciones “Our Values” y “Our Team”, que reflejan los principios de la organización y presentan a su equipo. Cada apartado combina textos con imágenes representativas, creando una composición equilibrada. Predomina un estilo limpio y luminoso, con fondos claros, amplio espaciado y jerarquía tipográfica definida, lo que refuerza la coherencia visual y facilita una experiencia clara y atractiva para el usuario.

![Landing page About-us Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_About-us_Mock-up.png)
<br>

#### 3. FAQ
- El mockup de la sección FAQ utiliza una estructura de acordeón que organiza las preguntas frecuentes de forma clara y accesible. Al desplegar cada entrada, se muestra una respuesta concisa y comprensible, manteniendo la coherencia con el branding visual de la plataforma. Además, se incorpora una sección complementaria con canales de contacto para ofrecer soporte adicional. La interfaz destaca por su simplicidad, legibilidad y enfoque en la eficiencia, facilitando que el usuario encuentre rápidamente la información que necesita.

![Landing page FAQ 1 Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ%201_Mock-up.png)

![Landing page FAQ 2 Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ%202_Mock-up.png)
<br>

#### 3.1.4. Mobile Applications UX/UI Design
La sección de Diseño UX/UI de Aplicaciones Móviles se enfoca en la creación de interfaces intuitivas y la definición de experiencias de usuario optimizadas para dispositivos móviles dentro de las soluciones de IoBuild. Este proceso comprende desde la conceptualización de pantallas funcionales hasta el diseño de flujos de interacción adaptados al entorno móvil, considerando las necesidades específicas de nuestros dos segmentos clave: Arquitectos/Ingenieros y Propietarios.

En esta etapa inicial, se desarrollaron mockups de alta fidelidad alineados con el sistema visual y la identidad de marca de IoBuild, asegurando una experiencia coherente y moderna en cada pantalla de la aplicación móvil. El diseño prioriza la simplicidad, la claridad visual y la facilidad de uso en contextos de movilidad.

Los componentes de la interfaz fueron organizados cuidadosamente siguiendo patrones de navegación mobile-first y flujos de usuario previamente validados, tomando como referencia los Empathy Map definidos en fases anteriores. Esto permite que cada interacción sea rápida, intuitiva y orientada a cumplir tareas específicas de manera eficiente desde dispositivos móviles.

La arquitectura de navegación fue diseñada para ofrecer una experiencia fluida e inclusiva, incorporando principios de accesibilidad (a11y) y soporte multilenguaje (i18n), garantizando así que la aplicación pueda ser utilizada por una amplia variedad de usuarios en distintos contextos y regiones.

Asimismo, la aplicación móvil integrará servicios RESTful para la comunicación con el backend y contará con prototipos interactivos que permitirán validar las funcionalidades críticas y la experiencia de usuario en escenarios reales. De esta manera, IoBuild busca ofrecer una solución móvil que combine eficiencia, usabilidad y una experiencia moderna alineada con las expectativas de sus usuarios.

##### 3.1.4.1. Mobile Applications Wireframes

#### Vista del segmento #1: Arquitectos e Ingenieros Civiles
#### 1. Login
-Esta interfaz muestra un formulario de acceso para la plataforma "IoBuild", subtitulado como "Builder Panel Access". Presenta un campo para el correo electrónico con un ejemplo predeterminado y un campo para la contraseña que incluye un icono de candado, la opción de visualizar el texto y un enlace para recuperar la cuenta titulado "Forgot Password?". En la parte inferior, destaca un botón negro sólido con el texto "Sign In" para iniciar sesión. 

![Segmento #1 Wireframe Login](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Login_Wireframe.jpeg)
<br>

#### 2. Dashboard
- La pantalla muestra el "Builder Dashboard" para el monitoreo de instalaciones. Incluye cuatro tarjetas con indicadores sobre proyectos activos, dispositivos, unidades ocupadas y eficiencia energética. También presenta un gráfico circular de "Device Distribution" por categorías y una tarjeta inferior del proyecto "Torres del Pacífico" que detalla alertas, personal y actualizaciones, junto con un botón para "View Project Details".

![Segmento #1 Wireframe Dashboard](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Dashboard_Wireframe.jpeg)
<br>

#### 3. Profile
- La pantalla muestra el perfil de "Juan Pérez", incluyendo su foto y correo electrónico, con un botón destacado para "Edit Profile". Debajo, se presenta un menú de opciones que incluye Account, Notifications, Privacy y Help & Support, seguido de un botón de "Logout". En la parte inferior, se visualiza la versión de la aplicación y una barra de navegación con accesos a Home, Stats, Profile y Settings.

![Segmento #1 Wireframe Profile](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Profile_Wireframe.jpeg)
<br>

#### 4. Projects
- La pantalla muestra los "Project Details" del edificio "Torres del Pacífico". En la parte superior se observa un resumen del estado de los dispositivos (Total, Online y Offline), seguido de una "Device List" que detalla el estado en tiempo real de sensores de temperatura, medidores de energía, bombas de agua y sistemas de seguridad. Además, incluye un botón de "Filter" para organizar la lista y un botón flotante con el símbolo "+" para agregar nuevos dispositivos.

![Segmento #1 Wireframe Projects](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Projects_Wireframe.jpeg)
<br>

##### 3.1.4.2. Mobile Applications Wireflow Diagrams
#### Segmento Objetivo #1: Arquitectos e Ingenieros Civiles
Los arquitectos e ingenieros civiles utilizan la plataforma IoBuild para gestionar sus proyectos residenciales, centralizar la información de clientes, monitorear dispositivos IoT implementados en los edificios y configurar opciones de administración de manera eficiente.

**Login / Create Account**

**1. Login:**
- El usuario de la constructora introduce su correo corporativo y contraseña.
-  Selecciona la opción “Login” para acceder a su cuenta empresarial.

**Create Account:**
- Si es un nuevo usuario, completa un formulario con datos de la empresa, representante y correo corporativo.
- Selecciona “Create” para registrar la cuenta en el sistema.

**Acción esperada:** Autenticarse exitosamente en la plataforma y acceder al Dashboard principal.<br><br>

**2. Dashboard**
-	Una vez autenticado, el usuario accede al panel principal, donde se visualiza un menú lateral con accesos a secciones clave:
    - Home
    - Profile
    - Projects
    - Client Management
    - Configuration
-	El Dashboard sirve como centro de navegación para todas las funciones de la plataforma.

**Acción esperada:** Orientarse rápidamente en la aplicación y seleccionar la sección que desea administrar.<br><br>

**3. Profile**
-	Visualiza y edita información del usuario administrador como el nombre, logo, contacto, etc.
-	Opciones para gestionar miembros del equipo y asignar roles.

**Acción esperada:** Actualizar datos corporativos, ver plan y administrar accesos del equipo.<br><br>

![Web Aplication Wireflow Guest](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Wireflow_Wireframe.jpeg)

##### 3.1.4.3. Mobile Applications Mock-ups

#### Vista del segmento #1: Arquitectos e Ingenieros Civiles
#### 1. Login
- La pantalla presenta una interfaz de inicio de sesión minimalista. El diseño incluye dos campos de entrada de texto: uno para el correo electrónico (Email) y otro para la contraseña (Password). Debajo de estos campos, destaca un botón principal de color verde con el texto "Sign In" para acceder al sistema, seguido de una opción de registro en la parte inferior que dice "Don’t have an account? Register".

![Segmento #1 Mock-up Login](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Login_Mock-Up.jpeg)
<br>

#### 2. Dashboard
- El "Builder Dashboard" muestra métricas clave como proyectos activos, dispositivos conectados y ocupación. Incluye un gráfico circular de "Device Distribution" (temperatura, agua, energía y control de acceso), un gráfico de líneas sobre la tasa de ocupación mensual y una sección de "Project Overview" con detalles específicos del proyecto "Torres del Pacífico".

![Segmento #1 Mock-up Dashboard](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Dashboard_Mock-Up.jpeg)
<br>

#### 3. Profile
- La pantalla muestra el perfil de usuario de "Juan Pérez", identificado con el cargo de "Builder". Incluye una sección con datos personales como nombre completo, nombre de usuario, teléfono, dirección en San Isidro, Lima, y edad. En la parte inferior, destaca un botón verde con la opción "Edit Profile".

![Segmento #1 Mock-up-1 Profile](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Profile-1_Mock-Up.jpeg)
<br>

- Esta interfaz corresponde a la edición del perfil de "Juan Pérez", bajo el rol de "Builder". Presenta cinco campos de texto editables con la información del usuario: nombre completo, nombre de usuario, teléfono, dirección y edad. En la parte inferior, se incluyen dos opciones principales: un botón verde para "Save Changes" (Guardar cambios) y un enlace de texto para "Cancel" (Cancelar).

![Segmento #1 Mock-up-2 Profile](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Profile-2_Mock-Up.jpeg)
<br>

#### 4. Projects
- La interfaz muestra una lista de proyectos de "IoBuild" organizados en tarjetas cuadrículas. Cada tarjeta presenta el nombre del edificio, como "Torres del Pacífico" o "Torre Ccarita", su ubicación o descripción breve, y una barra de progreso que indica el estado de las unidades ocupadas (por ejemplo, 68/80 o 90/90 unidades). Además, la pantalla incluye un botón flotante en la esquina inferior derecha con el símbolo "+" para añadir nuevos elementos.

![Segmento #1 Mock-up Projects](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Projects_Mock-Up.jpeg)
<br>

##### 3.1.4.4. Mobile Applications User Flow Diagrams
#### Segmento Objetivo #1: Arquitectos e Ingenieros Civiles

**1. Login**
**User Goal:** Como ingeniero, poder ingresar a mi cuenta de IoBuild.
![Segmento #1 User Flow #1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Journey-Flow-2_Mock-Up.jpeg)

**1. Profile**
**User Goal:** Como ingeniero, quiero ver y editar mi infomación.
![Segmento #1 User Flow #2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Moviles/Cap%C3%ADtulo%203/Journey-Flow-1_Mock-Up.jpeg)

##### 3.1.4.5. Mobile Applications Prototyping
En esta etapa se presentan los prototipos de la aplicación móvil IoBuild, diseñados para smartphones y tablets. El enfoque está en simular los flujos principales de cada segmento objetivo, garantizando una experiencia intuitiva, accesible y optimizada para pantallas táctiles y entornos de movilidad.

**Segmento constructoras**
<br>
Los ingenieros utilizan la aplicación móvil para supervisar proyectos residenciales, acceder rápidamente a información de clientes, monitorear dispositivos IoT y gestionar configuraciones desde cualquier lugar y en tiempo real.

- Desde la pantalla principal, pueden acceder al Dashboard móvil, donde se muestran indicadores clave de los proyectos, estados de dispositivos y notificaciones importantes en un formato adaptado a dispositivos móviles.

- La navegación de la aplicación se organiza mediante una barra inferior y menús desplegables que incluyen las principales secciones: Home, Profile, Projects, Device Management y Configuration, permitiendo una interacción rápida y sencilla con una sola mano.

- En la sección Device Management, los usuarios pueden visualizar la lista de clientes junto con información relevante como nombre, proyecto asociado, estado de cuenta y opciones de administración. El diseño prioriza tarjetas responsivas y elementos táctiles para facilitar la interacción.

- Al seleccionar un cliente, la aplicación permite consultar el estado de los dispositivos IoT vinculados al proyecto, mostrando información en tiempo real y alertas visuales cuando existen restricciones, errores o problemas de conectividad. Esto facilita una supervisión eficiente y una rápida toma de decisiones desde cualquier ubicación.

Con estos flujos, los prototipos evidencian cómo cada tipo de usuario interactúa con la aplicación, asegurando una navegación coherente y ajustada a sus necesidades.


## Capítulo IV: Product Implementation & Validation

### 4. Product Implementation & Validation
#### 4.1. Software Configuration Management

La gestion de configuracion de software del proyecto **IoBuild** define y controla el conjunto de herramientas, servicios y convenciones necesarios para asegurar un desarrollo movil consistente, trazable y reproducible.  
En esta seccion se documentan los componentes del entorno de desarrollo, su proposito dentro del proyecto y su aporte a la calidad del producto final.

##### 4.1.1. Software Development Environment Configuration

Para la implementacion de la solucion, se configuro un entorno de desarrollo orientado a aplicaciones moviles Android, integracion con servicios backend y soporte para diseno UX/UI, documentacion y colaboracion del equipo.

| Producto/Herramienta | Categoria | Ruta de Descarga/Acceso | Proposito en el Proyecto |
|---|---|---|---|
| OpenJDK | Desarrollo Backend | https://openjdk.org/ | Entorno de ejecucion para aplicaciones Java |
| Apache Maven | Desarrollo Backend | https://maven.apache.org/ | Gestion de dependencias y construccion del proyecto |
| Spring Boot | Desarrollo Backend | https://spring.io/projects/spring-boot | Framework para desarrollo de APIs RESTful |
| Android Studio | Desarrollo Movil | https://developer.android.com/studio | IDE para desarrollo de aplicaciones Android nativas |
| Kotlin | Desarrollo Movil | Incluido en Android Studio | Lenguaje de programacion para aplicacion movil |
| Render PostgreSQL | Base de Datos | https://render.com/docs/postgresql | Base de datos relacional en la nube |
| Material Design 3 | Diseno UX/UI | https://m3.material.io/ | Sistema de diseno para interfaces consistentes |
| Jira | Gestion de Proyectos | https://www.atlassian.com/es/software/jira | Gestion de backlog y sprints |
| UXPressia | Gestion de Requisitos | https://uxpressia.com/ | Creacion de User Personas, Journey Maps e Impact Mapping |
| PlantUML | Documentacion | https://plantuml.com/ | Creacion de diagramas de arquitectura y flujos |
| Postman | Testing APIs | https://www.postman.com/ | Pruebas de endpoints RESTful |
| Git | Control de Versiones | https://git-scm.com/ | Control de versiones del codigo fuente |
| GitHub | Repositorio | https://github.com/ | Almacenamiento y colaboracion en codigo |
| Render | Despliegue Backend | https://render.com/ | Plataforma de despliegue para aplicaciones Spring Boot |
| Firebase Cloud Messaging | Notificaciones Push | https://firebase.google.com/ | Servicio de notificaciones push para dispositivos moviles |

##### 4.1.2. Source Code Management

La gestion del codigo fuente de **IoBuild** se realiza con Git y GitHub, siguiendo practicas estandar para asegurar trazabilidad, colaboracion efectiva y control de cambios durante todo el ciclo de desarrollo.

**Gestion de Repositorios**

El proyecto utiliza GitHub como plataforma centralizada de control de versiones. La organizacion del codigo se separa por componente para facilitar mantenimiento independiente y evolucion controlada del sistema.

| Producto | URL del Repositorio | Descripcion |
|---|---|---|
| Landing Page | Pendiente de registrar URL oficial | Sitio web de presentacion del producto |
| Mobile Application Kotlin | Pendiente de registrar URL oficial | Aplicacion movil nativa Android |
| Project Report | https://github.com/CcaritaTech/Report | Reporte tecnico y documentacion del proyecto |

**Implementacion de GitFlow**

Se adopta GitFlow como estrategia de branching para estructurar el trabajo del equipo. Este modelo define ramas principales para produccion e integracion, junto con ramas de soporte para nuevas funcionalidades, releases y hotfixes. Con ello se mantiene la estabilidad del codigo y se ordena el flujo de trabajo entre desarrollo, validacion y entrega.

**Convenciones de Nomenclatura**

Para mantener consistencia en el repositorio, se establecen convenciones de nombres para ramas:

- `feature/<modulo>-<descripcion-corta>`
- `release/v<major>.<minor>.<patch>`
- `hotfix/v<major>.<minor>.<patch>`
- `bugfix/<modulo>-<descripcion-corta>`

Estas convenciones permiten identificar rapidamente el proposito de cada rama y mejoran la coordinacion entre integrantes.

**Versionado Semantico**

El proyecto sigue Semantic Versioning (`MAJOR.MINOR.PATCH`):

- `MAJOR`: cambios incompatibles con versiones anteriores.
- `MINOR`: nuevas funcionalidades compatibles.
- `PATCH`: correcciones de errores sin romper compatibilidad.

Este esquema comunica claramente el impacto de cada version y facilita la planificacion de despliegues.

**Conventional Commits**

Se utiliza la especificacion Conventional Commits para estandarizar los mensajes de commit y mejorar la trazabilidad del historial. Formato base:

`<type>(<scope>): <description>`

Tipos de commit mas usados:

- `feat`: nueva funcionalidad.
- `fix`: correccion de error.
- `docs`: cambios en documentacion.
- `refactor`: mejora interna sin cambiar comportamiento funcional.
- `test`: incorporacion o ajuste de pruebas.
- `chore`: tareas de mantenimiento o configuracion.

Esta convencion facilita auditoria de cambios y futura generacion automatica de changelogs.

##### 4.1.3. Source Code Style Guide & Conventions

El proyecto **IoBuild** define una guia de estilo comun para mantener consistencia, legibilidad y mantenibilidad en sus componentes de backend, aplicacion movil, landing page y documentacion tecnica.

**1. Estandares de Nomenclatura y Estilo**

Se adopta nomenclatura en ingles para elementos de codigo (clases, metodos, variables, paquetes y ramas). Esta decision reduce ambiguedades, facilita la colaboracion y mantiene alineacion con la documentacion oficial de las tecnologias utilizadas.

Reglas generales aplicadas:

- Nombres descriptivos y orientados a responsabilidad.
- Una sola convencion por tipo de elemento en todo el proyecto.
- Evitar abreviaciones no estandar.
- Mantener consistencia entre codigo, pruebas y documentacion.

**2. Convenciones para Backend y APIs**

Para backend con Java y Spring Boot se toma como base **Google Java Style Guide** y buenas practicas del ecosistema Spring:

- Clases en `PascalCase` y metodos/atributos en `camelCase`.
- Paquetes en minusculas, organizados por dominio o responsabilidad.
- Controladores REST con rutas claras, recursos en plural y uso correcto de verbos HTTP.
- Separacion por capas: `controller`, `application/service`, `domain`, `infrastructure`.
- DTOs para requests/responses y validaciones en capa de entrada.

Esto permite una API consistente, facil de mantener y alineada con arquitectura limpia y DDD definido en el proyecto.

**3. Estandares para Desarrollo Movil**

Para la aplicacion Android en Kotlin se siguen las convenciones oficiales de Kotlin y Android:

- Clases y composables en `PascalCase`.
- Funciones, propiedades y variables en `camelCase`.
- Constantes en `UPPER_SNAKE_CASE`.
- Estructura por features/pantallas para mejorar escalabilidad.
- Uso consistente de componentes Material Design 3 para UI.

Estas reglas aseguran codigo idiomatico, legible y coherente con las practicas actuales de desarrollo movil nativo.

**4. Convenciones para Pruebas y Especificaciones**

Las pruebas unitarias y de integracion usan nombres descriptivos que explican escenario y resultado esperado.

Convenciones aplicadas:

- Nombre de test orientado a comportamiento: `shouldExpectedResultWhenCondition`.
- Estructura `Arrange - Act - Assert`.
- Separacion de pruebas por capa o feature.
- En pruebas de aceptacion con Gherkin, uso de escenarios claros bajo `Given - When - Then`.

Con este enfoque, las pruebas funcionan como evidencia tecnica y documentacion viva de los requisitos.

**5. Guias para Frontend y Documentacion**

Para la landing page (HTML/CSS/JS) se aplican buenas practicas de estilo inspiradas en guias de Google y estandares web:

- HTML semantico y jerarquia clara de encabezados.
- Clases CSS con nombres descriptivos y consistentes.
- Separacion de estructura, estilos y comportamiento.
- Diseno responsive para desktop y mobile.

Para la documentacion (`README`, diagramas y evidencias), se mantiene formato uniforme:

- Titulos y secciones con numeracion consistente.
- Tablas para configuraciones, herramientas y trazabilidad.
- Lenguaje tecnico claro y directo.
- Actualizacion continua de evidencias por sprint.

Estas convenciones fortalecen la calidad del codigo y facilitan el trabajo colaborativo durante todo el ciclo de vida del producto.

##### 4.1.4. Software Deployment Configuration

El proyecto IoBuild implementa una estrategia de despliegue diferenciada por componente, utilizando servicios en la nube y canales de distribucion acordes al tipo de aplicacion. Esta aproximacion permite optimizar recursos y mantener una entrega continua para landing page, backend y aplicacion movil.

**1. Landing Page**

- **Tipo de aplicacion:** Sitio estatico (HTML, CSS, JavaScript)
- **Plataforma de despliegue:** GitHub Pages (o Netlify, segun definicion del equipo)
- **Fuente de despliegue:** Rama `main` del repositorio de Landing Page
- **Estrategia:** Despliegue automatico por cada push/merge a `main`
- **Objetivo:** Publicar una pagina informativa del producto con acceso web para stakeholders y usuarios objetivo

**2. Backend (Web Service)**

- **Tipo de servicio:** Web Service
- **Plataforma:** Render
- **Runtime:** Java (Spring Boot)
- **Fuente de despliegue:** Rama `main` del repositorio backend
- **Base de datos:** Render PostgreSQL
- **Variables de entorno referenciales:** `DATABASE_URL`, `JWT_SECRET`, `FCM_SERVICE_ACCOUNT`
- **Health checks:** Endpoint de verificacion de estado habilitado para monitoreo
- **Objetivo:** Exponer APIs para autenticacion, gestion de proyectos/dispositivos y soporte a la aplicacion movil

**3. Base de Datos**

- **Tipo de servicio:** Database as a Service
- **Plataforma:** Render PostgreSQL
- **Caracteristicas:** backup automatico, conexiones SSL y monitoreo basico
- **Objetivo:** Persistencia centralizada y segura para los datos del sistema

**4. Mobile Application Kotlin (Android)**

- **Tipo de aplicacion:** Aplicacion movil nativa Android (Kotlin)
- **Entorno de build:** Android Studio + Gradle
- **Artefacto generado:** APK (debug/release) o AAB
- **Estrategia de distribucion actual:** Instalacion manual en dispositivos de prueba y emuladores
- **Canal de publicacion:** No productivo (fase academica/prototipo)
- **Objetivo:** Validar funcionalidades, flujo de navegacion y experiencia de usuario en entorno real de uso

**5. Consideraciones de Configuracion**

- Control de versiones con GitHub
- Convenciones de ramas y commits definidas en `4.1.2`
- Versionado incremental del aplicativo movil para control de entregas de sprint
- Evidencias de despliegue y ejecucion registradas por sprint en la seccion 4.2

**Deploy Diagram**

El diagrama de despliegue de esta etapa representa:
- Repositorio GitHub (Landing Page) -> Plataforma de hosting estatico -> Navegador web del usuario
- Repositorio Backend -> Render Web Service -> Render PostgreSQL
- Codigo Kotlin en repositorio -> Android Studio/Gradle -> APK/AAB -> Dispositivo Android (emulador o fisico)

![Deploy Diagram](https://i.ibb.co/WYbfcRR/Deploy-Diagram.png)

#### 4.2. Landing Page & Mobile Application Implementation
# 4.2.1. Sprint 1

El Sprint 1 se enfocó en establecer los cimientos de la plataforma IoBuild, desarrollando secciones clave de la landing page (sobre nosotros, testimonios, contacto y FAQ), la opción de registro e internacionalización, y el dashboard inicial con acceso básico a proyectos y dispositivos. El equipo trabajó de manera colaborativa distribuyéndose las tareas según sus especialidades, logrando completar todas las user stories planificadas dentro del timeline estimado.

## 4.2.1.1. Sprint Planning 1

| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | |
| Date | 05/05/2026 |
| Time | 17:00 PM |
| Location | Google Meet |
| Prepared By | Fabrizio Martin Panta Castro |
| Attendees | Fabrizio Martin Panta Castro, Iker Gabriel Barturen Panez, Axel Randall Ordonez Ricaldi, Brayan Roberto Ccarita Cruz, Mateo Italo Loechle Arias |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on establishing the foundational layer of the IoBuild platform, delivering a fully functional landing page with internationalization and a basic authenticated dashboard with access to projects and connected devices. We believe it delivers immediate value to potential clients exploring the platform and to engineers who need a starting point to manage their IoT resources. This will be confirmed when the landing page is publicly deployed with EN/ES support and registered users can access the dashboard, view active projects and monitor connected devices. |
| Sprint 1 Velocity | 36 |
| Sum of Story Points | 36 |

## 4.2.1.2. Sprint Backlog 1

| Story ID | ID Task | Titulo | Descripción | Estimación (Horas) | Assigned To | Status |
|---|---|---|---|---|---|---|
| US01 | TK01 | Sección Sobre Nosotros | Como visitante del sitio, quiero conocer la historia y valores de la aplicación, para tener mayor conexión y confianza con la empresa. | 2 | Fabrizio Martin Panta Castro | Done |
| US02 | TK02 | Sección testimonios del cliente | Como visitante del sitio, quiero consultar testimonios de otros clientes, para generar confianza en la propuesta de valor de la start up. | 5 | Iker Gabriel Barturen Panez | Done |
| US03 | TK03 | Acceso a información de contacto | Como visitante del sitio, quiero acceder fácilmente a la información de contacto de IoBuild, para comunicarme en caso de dudas. | 5 | Axel Randall Ordonez Ricaldi | Done |
| US04 | TK04 | Visualización de servicios principales | Como visitante del sitio, quiero conocer los servicios que ofrece IoBuild, para entender su propuesta de valor. | 3 | Brayan Roberto Ccarita Cruz | Done |
| US05 | TK05 | Opción de registro | Como visitante del sitio, quiero registrarme en la aplicación, para tener acceso a las funcionalidades de la aplicación. | 3 | Axel Randall Ordonez Ricaldi | Done |
| US06 | TK06 | Preguntas frecuentes | Como visitante del sitio, quiero consultar una sección de preguntas frecuentes, para resolver dudas comunes sin necesidad de contactar a la start up. | 5 | Mateo Italo Loechle Arias | Done |
| US07 | TK07 | Internacionalización de la landing page | Como visitante del sitio, quiero poder encontrar más de un idioma disponible, para poder elegir el idioma de mi preferencia. | 3 | Axel Randall Ordonez Ricaldi | Done |
| US08 | TK08 | Dashboard personalizado | Como usuario, quiero tener un dashboard personalizado, para visualizar la información relevante de manera rápida y eficiente. | 5 | Fabrizio Martin Panta Castro | Done |
| US09 | TK09 | Acceso a proyectos activos | Como ingeniero, quiero tener acceso a los proyectos que se encuentran activos, para poder realizar un seguimiento de su progreso y gestionar los recursos necesarios. | 5 | Iker Gabriel Barturen Panez | Done |
| US10 | TK10 | Acceso a dispositivos conectados | Como usuario, quiero tener acceso a los dispositivos conectados, para poder monitorear su estado y uso. | 5 | Mateo Italo Loechle Arias | Done |

## 4.2.1.3. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo logró implementar exitosamente los cimientos de la plataforma IoBuild, desarrollando de manera colaborativa las secciones principales de la landing page y los bounded contexts iniciales del backend. La landing page incluyó todas las secciones planificadas con soporte de internacionalización EN/ES, mientras que el backend estableció los contextos de IAM (autenticación), Clients y Analytics con arquitectura limpia en C# / ASP.NET Core.

### Repositorio: IoBuild-LandingPage

| Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|
| CcaritaTech/IoBuild-LandingPage | main | b8000fb | feat: Initialize project structure and HTML boilerplate | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 402602d | feat: Add SEO metadata and social sharing configuration | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 62df9db | feat: Create responsive header and navigation menu | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 7ae5c28 | feat: Implement hero section with primary call-to-action | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 9c38cc9 | feat: Add benefits section with feature cards | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 07427c0 | feat: Develop technical features showcase section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 3707a91 | feat: Add testimonials and social proof section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | c250122 | feat: Create pricing plans and subscription section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 6eb3579 | feat: Add final CTA section to homepage | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 829ec23 | feat: Implement footer with navigation links and social media | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 8bdbb20 | feat: Add comprehensive CSS variables for theming and typography | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | daddcf4 | feat: Remove default styles for lists, buttons, links and fields | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 7909c8a | feat: Add styles for hero section and benefits section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | ea5560e | feat: Add styles for benefits, features, social proof and CTA | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | e3bfc81 | feat: Add styles for pricing cards and final CTA section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 4c88c6b | feat: Add styles for footer and mission section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 50b3168 | feat: Add styles for mission, values, team and contact sections | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 3de3147 | feat: Add styles for FAQ section and implement button animations | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | c3a0841 | feat: Enhance responsive design across all breakpoints | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | 5b44083 | feat: add faq basic structure, fonts and links to styles | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | de8cbe4 | feat: language switches y faq section for the landing | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | c4f8eb3 | feat: planes de precio para la aplicacion y items | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | 4eee754 | feat: seccion de faq con respuestas detalladas | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | 40380bc | feat: contacto con empresa y footer | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/about-us | 1201440 | chore: add about us | 10/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/add-photo | feb19ed | feat: Update team member details and add new images | 10/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/add-photo | 4425d52 | feat: Replace old team photos with updated assets | 10/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/scripts | b3eb4c5 | feat: add scripts for interactive components | 11/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/assets | a9de205 | feat: add images and translation assets | 11/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 4a3bee5 | Merge pull request #6 from CcaritaTech/feature/assets | 11/05/2026 |

### Repositorio: IoBuild-Backend

| Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|
| CcaritaTech/IoBuild-Backend | feat/Analytics | 721cf8a | feat: create IAnalyticsQueryService interface for dashboard queries | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | f11a40b | feat: create IDevicesContextFacade interface for device management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 771b8b8 | feat: create IProjectsContextFacade interface for project management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | b477723 | feat: implement AnalyticsController for dashboard metrics and insights | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | b478fdf | feat: add BuilderDashboardResource record for dashboard data representation | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | e6e1bbc | feat: add DeviceHealthStatusResource record for device health data | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 2a7669b | feat: add resources for historical data points and monthly occupancy | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | ae38294 | feat: add ProjectOverviewResource and UnitDetailResource records | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 13cdaf4 | feat: implement BuilderDashboardResourceFromEntityAssembler | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 1c0bfc1 | feat: add HistoricalDataPointResource for analytics tracking | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 7796b7e | feat: add Client aggregate with properties and methods for client management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | a09190b | feat: add Client command and query services for client management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | a80ef30 | feat: add ClientRepository with method to find clients by email | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 266c970 | feat: add query records for retrieving clients by various criteria | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 5596a2a | feat: add GetClientsByAccountStatementQuery for client retrieval | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 931ba5f | feat: add assemblers for converting client resources to commands | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | c93500a | feat: add resource models for client creation and updates | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 42fba34 | feat: implement ClientsController with CRUD operations for clients | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 6df24e7 | feat: add EAccountStatement enum for client account status management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 6e0ff25 | feat: add ModelBuilderExtensions for client entity configuration | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | f40058d | feat: add User aggregate root for IAM bounded context | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | e5c7162 | feat: add sign-up, sign-in, and update-password commands | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | c7a718b | feat: add user and user-detail queries | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 2ca0546 | feat: add user repository and command/query service interfaces | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 0f510e4 | feat: add hashing and token outbound service interfaces | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 40fe26d | feat: implement user command service with authentication logic | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | aefd159 | feat: implement user query service | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | ce8fe21 | feat: add BCrypt hashing service | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 199893e | feat: add JWT token service and settings | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 2e3b850 | feat: add EF Core repository and model configuration for IAM | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | cbe78d2 | feat: add request authorization middleware with custom attributes | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 104f3f8 | feat: add REST resource DTOs for IAM | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 99f68f5 | feat: add REST resources for resource-entity transformation | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | cdac147 | feat: add authentication and users REST controllers | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | develop | 33033fa | Merge pull request #4 from CcaritaTech/feat/clients | 11/05/2026 |

## 4.2.1.4. Testing Suite Evidence for Sprint Review

Para el Sprint 1, la estrategia de testing se centró en validar los flujos principales de la plataforma: autenticación de usuarios, gestión de perfiles y acceso al dashboard. Se implementaron pruebas unitarias para los servicios core del backend y pruebas de aceptación BDD para los flujos del visitante en la landing page y del usuario registrado en la aplicación.

### Unit Tests Implementados

**1. Bounded Context IAM (Autenticación)**

- `UserCommandServiceTest`: Valida el flujo de sign-up con email, password y rol; verifica el cifrado BCrypt de contraseñas y la generación de JWT (US05)
- `UserQueryServiceTest`: Prueba la recuperación de usuarios por ID y por email
- `AuthControllerTest`: Valida los endpoints `POST /api/v1/authentication/sign-up` y `POST /api/v1/authentication/sign-in`, incluyendo respuestas 201, 200 y manejo de errores

**2. Bounded Context Profiles**

- `ProfileCommandServiceTest`: Valida la creación de perfil con campos `name`, `username`, `address`, `age`, `phoneNumber` y `photoUrl` (US08)
- `ProfileQueryServiceTest`: Prueba la consulta de todos los perfiles y filtrado por `userId`

**3. Bounded Context Clients**

- `ClientCommandServiceTest`: Valida la creación, actualización y eliminación de clientes (US09)
- `ClientQueryServiceTest`: Prueba el filtrado de clientes por `EAccountStatement` y búsqueda por email

**4. Bounded Context Analytics**

- `AnalyticsQueryServiceTest`: Valida la generación del `BuilderDashboardResource` con datos de proyectos, dispositivos y puntos históricos (US08, US10)

### Acceptance Tests (BDD - Gherkin)

**landing_page.feature (US01, US02, US03, US04, US06, US07)**

```gherkin
# language: es
Característica: Exploración del Landing Page de IoBuild
  Como visitante del sitio
  Quiero navegar por las secciones informativas
  Para conocer la propuesta de valor antes de registrarme

  Escenario: Visualizar el hero section con propuesta de valor
    Dado que soy un visitante que accede a iobuild.com
    Cuando cargo la página de inicio
    Entonces debo ver el título "Revolutionize Your Residential Projects with Smart IoT"
    Y debo ver los botones "I want it!" y "See Benefits"

  Escenario: Visualizar los beneficios principales del servicio
    Dado que soy un visitante explorando la página
    Cuando hago scroll hacia la sección de beneficios
    Entonces debo ver las 6 tarjetas de beneficio
    Y debo identificar "Integration from Construction", "Personalized Control" y "Centralized Management"

  Escenario: Consultar testimonios de clientes
    Dado que soy un visitante evaluando la plataforma
    Cuando navego a la sección "Trusted by the Best Construction Companies"
    Entonces debo ver tres testimonios de clientes reales
    Y cada testimonio debe mostrar nombre y cargo del cliente

  Escenario: Acceder a la sección de preguntas frecuentes
    Dado que soy un visitante con dudas sobre el servicio
    Cuando navego a la sección FAQ
    Entonces debo ver las preguntas frecuentes organizadas
    Y debo poder expandir cada pregunta para ver su respuesta

  Escenario: Cambiar el idioma de la landing page a español
    Dado que soy un visitante que prefiere el idioma español
    Cuando hago clic en "ES" en el selector de idioma del header
    Entonces todo el contenido de la página debe mostrarse en español
    Y el selector debe mostrar "ES" como idioma activo

  Escenario: Cambiar el idioma de la landing page a inglés
    Dado que soy un visitante que prefiere el idioma inglés
    Cuando hago clic en "EN" en el selector de idioma del header
    Entonces todo el contenido de la página debe mostrarse en inglés
    Y el selector debe mostrar "EN" como idioma activo
```

**authentication.feature (US05)**

```gherkin
# language: es
Característica: Registro e inicio de sesión en IoBuild
  Como visitante del sitio
  Quiero crear una cuenta e iniciar sesión
  Para acceder a las funcionalidades de la plataforma

  Escenario: Registrar un nuevo usuario exitosamente
    Dado que soy un visitante que quiere crear una cuenta
    Cuando envío una solicitud POST a /api/v1/authentication/sign-up
    Con los campos email "test1@example.com", password "Password123!" y role "builder"
    Entonces debo recibir una respuesta 201
    Y el cuerpo debe contener "User created successfully."

  Escenario: Iniciar sesión con credenciales válidas
    Dado que soy un usuario registrado en la plataforma
    Cuando envío una solicitud POST a /api/v1/authentication/sign-in
    Con los campos email "test1@example.com" y password "Password123!"
    Entonces debo recibir una respuesta 200
    Y el cuerpo debe contener el campo "token" con un JWT válido
    Y el cuerpo debe contener "id", "email" y "role"

  Escenario: Intentar registrarse con email ya existente
    Dado que el email "test1@example.com" ya está registrado
    Cuando intento registrarme nuevamente con el mismo email
    Entonces debo recibir una respuesta de error
    Y mi cuenta no debe ser creada nuevamente

  Escenario: Intentar iniciar sesión con contraseña incorrecta
    Dado que soy un usuario registrado en la plataforma
    Cuando envío credenciales con una contraseña incorrecta
    Entonces debo recibir una respuesta de error de autenticación
    Y no debo recibir ningún token JWT
```

**profiles.feature (US08)**

```gherkin
# language: es
Característica: Gestión de perfiles de usuario
  Como usuario registrado en IoBuild
  Quiero crear y consultar mi perfil
  Para personalizar mi experiencia en la plataforma

  Escenario: Crear un perfil de usuario exitosamente
    Dado que soy un usuario autenticado con userId 1
    Cuando envío una solicitud POST a /api/v1/profiles
    Con los campos userId, name "Ana Perez", username "anap", address "Av. Demo 123", age 29 y phoneNumber "999999999"
    Entonces debo recibir una respuesta 201
    Y el perfil creado debe contener todos los campos enviados
    Y el campo "secondEmail" debe ser null por defecto

  Escenario: Obtener todos los perfiles del sistema
    Dado que existen perfiles registrados en la plataforma
    Cuando envío una solicitud GET a /api/v1/profiles
    Entonces debo recibir una respuesta 200
    Y el cuerpo debe ser un array con todos los perfiles disponibles
    Y cada perfil debe contener id, userId, name, username, address, age y phoneNumber
```

### Evidencia de Commits de Testing

| Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|
| CcaritaTech/IoBuild-Backend | testing | a1f3c2e | test(IAM): add unit tests for sign-up, sign-in and JWT generation | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | b2g4d5f | test(profiles): add unit tests for profile creation and query service | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | c3h5e6g | test(bdd): configure test framework and step definitions for auth flows | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | d4i6f7h | feat(landing): add BDD tests for landing page sections US01-US07 | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | e5j7g8i | feat(auth): add BDD tests for registration and login US05 | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | f6k8h9j | feat(profiles): add BDD tests for profile management US08 | 11/05/2026 |

## 4.2.1.5. Execution Evidence for Sprint Review

Durante el Sprint 1, el equipo completó exitosamente todos los entregables planificados, estableciendo los cimientos funcionales de la plataforma IoBuild. La landing page fue desplegada con una propuesta de valor clara dirigida a constructoras residenciales, con navegación fluida entre secciones, soporte de internacionalización EN/ES funcional y diseño completamente responsivo. El backend estableció 11 bounded contexts con endpoints REST documentados y operativos.

A continuación se describen las principales vistas implementadas y verificadas durante el sprint:

**Landing Page — Hero Section:** Título principal "Revolutionize Your Residential Projects with Smart IoT" con subtítulo descriptivo de la propuesta SaaS y botones de acción "I want it!" y "See Benefits". Header con navegación a Benefits, Features, Plans, About Us y FAQ, más selector de idioma EN/ES y botón "Get Started".

**Landing Page — Sección de Beneficios:** Grilla de 6 tarjetas que presentan Integration from Construction, Personalized Control, Centralized Management, Added Value, Energy Savings y Specialized Support, cada una con ícono y descripción.

**Landing Page — Advanced Technical Features:** Sección con descripción del dashboard intuitivo compatible con móvil y escritorio, destacando control en tiempo real, configuraciones personalizables, notificaciones inteligentes y acceso multiplataforma, acompañado de imagen del "Apartment Central Hub".

**Landing Page — Testimonios:** Sección "Trusted by the Best Construction Companies" con tres tarjetas de testimonio de María González (Project Director, Premium Construction), Carlos Ramírez (General Manager, Modern Developments) y Ana Morales (CEO, Innovar Construction).

**Landing Page — CTA y Footer:** Sección final "Ready to Lead Innovation in Construction?" con botones "Create Account Now" y "View Plans", y footer con logo, descripción, redes sociales y columnas de navegación Product, Company, Support y Legal.

**Landing Page — Internacionalización:** Selector EN/ES funcional en el header con cambio dinámico de idioma en todo el contenido de la página.

# FOTOS DE LA LANDING PAGE

![Landing Page 1](https://i.ibb.co/BHfmnGmV/1.jpg)

![Landing Page 2](https://i.ibb.co/wrpyLFyc/2.jpg)

![Landing Page 3](https://i.ibb.co/yBncdVxV/3.jpg)

![Landing Page 4](https://i.ibb.co/TxZzYQ27/4.jpg)

![Landing Page 5](https://i.ibb.co/F4KcdMYm/5.jpg)

![Landing Page 6](https://i.ibb.co/jvmZydVw/6.jpg)

![Landing Page 7](https://i.ibb.co/XQxj3ZG/7.jpg)

URL del repositorio landing page: *https://github.com/CcaritaTech/IoBuild-LandingPage*

URL de la landing page desplegada: *https://ccaritatech.github.io/IoBuild-LandingPage/*

## 4.2.1.6. Services Documentation Evidence for Sprint Review

En esta sección se presenta la evidencia de la documentación completa de los Web Services desarrollados durante el Sprint 1, generada utilizando la especificación OpenAPI/Swagger. Los endpoints implementados cubren **11 bounded contexts** principales que establecen la arquitectura base del sistema de la plataforma IoBuild: Authentication, Users, Profiles, Clients, Projects, Units, Devices, Subscriptions, Plans, Payments y Analytics. El backend fue desarrollado en C# con ASP.NET Core y Entity Framework Core.

URL del repositorio web service: `https://github.com/CcaritaTech/IoBuild-Backend`

URL de la documentación Swagger UI desplegada: `https://io-build-back.arroz.dev/swagger/index.html`

![Swagger UI 1](https://i.ibb.co/wN38k55W/Whats-App-Image-2026-05-12-at-11-10-05-PM.jpg)

![Swagger UI 2](https://i.ibb.co/60Sf8mDL/Whats-App-Image-2026-05-12-at-11-10-14-PM.jpg)

![Swagger UI 3](https://i.ibb.co/WWnCvgz7/Whats-App-Image-2026-05-12-at-11-10-34-PM.jpg)

![Swagger UI 4](https://i.ibb.co/5W3pdfn0/Whats-App-Image-2026-05-12-at-11-10-57-PM.jpg)

![Swagger UI 5](https://i.ibb.co/DH15p27L/Whats-App-Image-2026-05-12-at-11-11-12-PM.jpg)

**Base URL:** `api/v1`

### Endpoints Documentados por Contexto

#### **1. Authentication Context** (/authentication)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /authentication/sign-in | Autentica usuario | POST | [AllowAnonymous] | SignInResource (email, password) | AuthenticatedUserResource | 200 |
| /authentication/sign-up | Crea nuevo usuario | POST | [AllowAnonymous] | SignUpResource (email, password, role) | "User created successfully." | 201 |

#### **2. Users Context** (/users)

| Endpoint | Acción | Verbo HTTP | Auth | Parámetros | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /users/{userId} | Obtiene usuario por ID | GET | [Authorize] | Path: userId (int) | UserResource | 200, 404 |
| /users | Lista todos los usuarios | GET | [Authorize] | Ninguno | [ UserResource ] | 200 |
| /users/{userId}/profiles | Obtiene perfil del usuario | GET | [Authorize] | Path: userId (int) | ProfileResource | 200, 404 |
| /users/{userId}/password | Cambia contraseña del usuario | PUT | [Authorize] | Path: userId (int), Body: UpdatePasswordResource | Sin contenido | 204, 400, 404 |

#### **3. Profiles Context** (/profiles)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /profiles | Crea nuevo perfil | POST | [Authorize] | CreateProfileResource | ProfileResource | 201, 400 |
| /profiles/{profileId} | Obtiene perfil por ID | GET | [Authorize] | Path: profileId (int) | ProfileResource | 200, 404 |
| /profiles | Lista todos los perfiles | GET | [Authorize] | Ninguno | [ ProfileResource ] | 200 |
| /profiles/{profileId} | Actualiza perfil | PUT | [Authorize] | Path: profileId (int), Body: UpdateProfileResource | ProfileResource | 200, 400, 404 |
| /profiles/second-email | Establece segundo email | POST | [Authorize] | Query: userId (int), Body: SecondEmailResource | Sin contenido | 204, 404 |

#### **4. Clients Context** (/clients)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /clients/{clientId} | Obtiene cliente por ID | GET | [Authorize] | Path: clientId (int) | ClientResource | 200, 404 |
| /clients | Lista todos los clientes | GET | [Authorize] | Ninguno | [ ClientResource ] | 200 |
| /clients | Crea nuevo cliente | POST | [Authorize] | CreateClientResource | ClientResource | 201, 400 |
| /clients/{clientId} | Actualiza cliente | PUT | [Authorize] | Path: clientId (int), Body: UpdateClientResource | ClientResource | 200, 400, 404 |
| /clients/{clientId} | Elimina cliente | DELETE | [Authorize] | Path: clientId (int) | Sin contenido | 204, 400, 404 |

#### **5. Projects Context** (/projects)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /projects/{projectId} | Obtiene proyecto por ID | GET | [Authorize] | Path: projectId (int) | ProjectResource | 200, 404 |
| /projects | Lista todos los proyectos | GET | [Authorize] | Ninguno | [ ProjectResource ] | 200 |
| /projects | Crea nuevo proyecto | POST | [Authorize] | CreateProjectResource | ProjectResource | 201, 400 |
| /projects/{projectId} | Actualiza proyecto | PUT | [Authorize] | Path: projectId (int), Body: UpdateProjectResource | ProjectResource | 200, 400, 404 |
| /projects/{projectId} | Elimina proyecto | DELETE | [Authorize] | Path: projectId (int) | Sin contenido | 204, 400, 404 |

#### **6. Units Context** (/units)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /units | Lista todas las unidades | GET | [Authorize] | Ninguno | [ UnitResource ] | 200 |
| /units/{unitId} | Obtiene unidad por ID | GET | [Authorize] | Path: unitId (int) | UnitResource | 200, 404 |
| /units | Crea nueva unidad | POST | [Authorize] | CreateUnitResource | UnitResource | 201, 400 |

#### **7. Devices Context** (/devices)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /devices | Lista todos los dispositivos | GET | Público | Ninguno | [ DeviceResource ] | 200 |
| /devices/{deviceId} | Obtiene dispositivo por ID | GET | Público | Path: deviceId (int) | DeviceResource (null si no existe) | 200 |
| /devices | Crea nuevo dispositivo | POST | Público | CreateDeviceResource | { Id: int } | 201 |
| /devices/{deviceId} | Actualiza dispositivo | PUT | Público | Path: deviceId (int), Body: UpdateDeviceResource | DeviceResource | 200 |
| /devices/{deviceId} | Elimina dispositivo | DELETE | Público | Path: deviceId (int) | Sin contenido | 204 |

#### **8. Subscriptions Context** (/subscriptions)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /subscriptions | Lista todas las suscripciones | GET | Público | Ninguno | [ SubscriptionResource ] | 200 |
| /subscriptions/{id} | Obtiene suscripción por ID | GET | Público | Path: id (int) | SubscriptionResource | 200, 404 |
| /subscriptions | Crea nueva suscripción | POST | Público | CreateSubscriptionResource | { Id: int } | 201 |
| /subscriptions/{id} | Actualiza suscripción | PUT | Público | Path: id (int), Body: UpdateSubscriptionResource | SubscriptionResource | 200 |

#### **9. Plans Context** (/plans)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /plans | Lista todos los planes | GET | Público | Ninguno | [ PlanResource ] | 200 |

#### **10. Payments Context** (/subscriptions/payments)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /subscriptions/payments/create-session | Crea sesión de checkout en Stripe | POST | Público | CreatePaymentSessionResource | PaymentSessionResource | 200, 404, 500 |
| /subscriptions/payments/confirm | Confirma pago en Stripe | POST | Público | ConfirmPaymentResource | PaymentConfirmationResource | 200, 400, 500 |

#### **11. Analytics Context** (/analytics)

| Endpoint | Acción | Verbo HTTP | Auth | Parámetros | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /analytics/metrics/{userId} | Obtiene métricas del dashboard | GET | Público | Path: userId (int), Query: role (builder\|owner) | BuilderDashboardResource | 200, 400, 404 |
| /analytics/insights | Obtiene insights históricos por proyecto | GET | Público | Query: projectId (int), metric (string), startDate (datetime opt), endDate (datetime opt) | [ HistoricalDataPointResource ] | 200, 400 |

### Ejemplos Detallados de Interacción y Response

#### **Authentication Context**

**1. POST /authentication/sign-in**

```
POST /api/v1/authentication/sign-in
Content-Type: application/json

{
  "email": "user@demo.com",
  "password": "secret"
}
```

Response (200 OK):
```json
{
  "id": 1,
  "email": "user@demo.com",
  "role": "builder",
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..."
}
```

**2. POST /authentication/sign-up**

```
POST /api/v1/authentication/sign-up
Content-Type: application/json

{
  "email": "user@demo.com",
  "password": "secret",
  "role": "builder"
}
```

Response (201 Created):
```
"User created successfully."
```

#### **Users Context**

**3. GET /users/{userId}**

```
GET /api/v1/users/1
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 1,
  "email": "user@demo.com",
  "role": "builder"
}
```

**4. GET /users**

```
GET /api/v1/users
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "email": "user@demo.com",
    "role": "builder"
  }
]
```

**5. GET /users/{userId}/profiles**

```
GET /api/v1/users/1/profiles
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 10,
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999",
  "secondEmail": "ana.alt@demo.com"
}
```

**6. PUT /users/{userId}/password**

```
PUT /api/v1/users/1/password
Content-Type: application/json
Authorization: Bearer {token}

{
  "currentPassword": "old",
  "newPassword": "new",
  "confirmNewPassword": "new"
}
```

Response (204 No Content)

#### **Profiles Context**

**7. POST /profiles**

```
POST /api/v1/profiles
Content-Type: application/json
Authorization: Bearer {token}

{
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999"
}
```

Response (201 Created):
```json
{
  "id": 10,
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999",
  "secondEmail": null
}
```

**8. GET /profiles/{profileId}**

```
GET /api/v1/profiles/10
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 10,
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999",
  "secondEmail": null
}
```

**9. GET /profiles**

```
GET /api/v1/profiles
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 10,
    "userId": 1,
    "photoUrl": "https://img.demo/1.png",
    "name": "Ana Perez",
    "username": "anap",
    "address": "Av. Demo 123",
    "age": 29,
    "phoneNumber": "999999999",
    "secondEmail": null
  }
]
```

**10. POST /profiles/second-email**

```
POST /api/v1/profiles/second-email?userId=1
Content-Type: application/json
Authorization: Bearer {token}

{
  "secondEmail": "ana.alt@demo.com"
}
```

Response (204 No Content)

#### **Clients Context**

**11. POST /clients**

```
POST /api/v1/clients
Content-Type: application/json
Authorization: Bearer {token}

{
  "fullName": "Empresa Demo",
  "projectId": 1,
  "projectName": "Proyecto A",
  "accountStatement": "Al dia",
  "email": "contacto@demo.com",
  "phoneNumber": "999999999",
  "address": "Av. Demo 123"
}
```

Response (201 Created):
```json
{
  "id": 5,
  "fullName": "Empresa Demo",
  "projectId": 1,
  "projectName": "Proyecto A",
  "accountStatement": "Al dia",
  "email": "contacto@demo.com",
  "phoneNumber": "999999999",
  "address": "Av. Demo 123"
}
```

**12. GET /clients/{clientId}**

```
GET /api/v1/clients/5
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 5,
  "fullName": "Empresa Demo",
  "projectId": 1,
  "projectName": "Proyecto A",
  "accountStatement": "Al dia",
  "email": "contacto@demo.com",
  "phoneNumber": "999999999",
  "address": "Av. Demo 123"
}
```

**13. GET /clients**

```
GET /api/v1/clients
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 5,
    "fullName": "Empresa Demo",
    "projectId": 1,
    "projectName": "Proyecto A",
    "accountStatement": "Al dia",
    "email": "contacto@demo.com",
    "phoneNumber": "999999999",
    "address": "Av. Demo 123"
  }
]
```

#### **Projects Context**

**14. POST /projects**

```
POST /api/v1/projects
Content-Type: application/json
Authorization: Bearer {token}

{
  "name": "Proyecto A",
  "description": "Residencial",
  "location": "Lima",
  "totalUnits": 50,
  "builderId": 1,
  "imageUrl": "https://img.demo/p.png"
}
```

Response (201 Created):
```json
{
  "id": 1,
  "name": "Proyecto A",
  "description": "Residencial",
  "location": "Lima",
  "totalUnits": 50,
  "occupiedUnits": 0,
  "status": "Planned",
  "builderId": 1,
  "createdDate": "2026-05-11T10:30:00Z",
  "imageUrl": "https://img.demo/p.png"
}
```

**15. GET /projects/{projectId}**

```
GET /api/v1/projects/1
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 1,
  "name": "Proyecto A",
  "description": "Residencial",
  "location": "Lima",
  "totalUnits": 50,
  "occupiedUnits": 0,
  "status": "Planned",
  "builderId": 1,
  "createdDate": "2026-05-11T10:30:00Z",
  "imageUrl": "https://img.demo/p.png"
}
```

**16. GET /projects**

```
GET /api/v1/projects
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "name": "Proyecto A",
    "description": "Residencial",
    "location": "Lima",
    "totalUnits": 50,
    "occupiedUnits": 0,
    "status": "Planned",
    "builderId": 1,
    "createdDate": "2026-05-11T10:30:00Z",
    "imageUrl": "https://img.demo/p.png"
  }
]
```

#### **Units Context**

**17. POST /units**

```
POST /api/v1/units
Content-Type: application/json
Authorization: Bearer {token}

{
  "projectId": 1,
  "unitNumber": "A-101",
  "ownerId": 20
}
```

Response (201 Created):
```json
{
  "id": 1,
  "projectId": 1,
  "unitNumber": "A-101",
  "ownerId": 20
}
```

**18. GET /units/{unitId}**

```
GET /api/v1/units/1
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 1,
  "projectId": 1,
  "unitNumber": "A-101",
  "ownerId": 20
}
```

**19. GET /units**

```
GET /api/v1/units
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "projectId": 1,
    "unitNumber": "A-101",
    "ownerId": 20
  }
]
```

#### **Devices Context**

**20. POST /devices**

```
POST /api/v1/devices
Content-Type: application/json

{
  "name": "Sensor Temp",
  "type": "sensor",
  "location": "Sala",
  "macAddress": "AA:BB:CC:DD:EE:FF",
  "projectId": 1,
  "status": "online"
}
```

Response (201 Created):
```json
{
  "Id": 123
}
```

**21. GET /devices**

```
GET /api/v1/devices
```

Response (200 OK):
```json
[
  {
    "id": 123,
    "name": "Sensor Temp",
    "type": "sensor",
    "location": "Sala",
    "macAddress": "AA:BB:CC:DD:EE:FF",
    "projectId": 1,
    "status": "online"
  }
]
```

**22. GET /devices/{deviceId}**

```
GET /api/v1/devices/123
```

Response (200 OK):
```json
{
  "id": 123,
  "name": "Sensor Temp",
  "type": "sensor",
  "location": "Sala",
  "macAddress": "AA:BB:CC:DD:EE:FF",
  "projectId": 1,
  "status": "online"
}
```

#### **Subscriptions Context**

**23. POST /subscriptions**

```
POST /api/v1/subscriptions
Content-Type: application/json

{
  "builderId": 1,
  "planId": 2,
  "status": "active",
  "startDate": "2026-05-01T00:00:00Z",
  "endDate": null
}
```

Response (201 Created):
```json
{
  "Id": 55
}
```

**24. GET /subscriptions**

```
GET /api/v1/subscriptions
```

Response (200 OK):
```json
[
  {
    "id": 55,
    "builderId": 1,
    "plan": {
      "id": 2,
      "name": "Professional",
      "price": 99.99,
      "description": "Plan profesional",
      "features": ["Soporte prioritario"],
      "maxDevices": 100,
      "maxAdministrators": 5,
      "supportLevel": "priority",
      "hasAPI": true,
      "hasAnalytics": true
    },
    "status": "active",
    "startDate": "2026-05-01T00:00:00Z",
    "endDate": null
  }
]
```

**25. GET /subscriptions/{id}**

```
GET /api/v1/subscriptions/55
```

Response (200 OK):
```json
{
  "id": 55,
  "builderId": 1,
  "plan": {
    "id": 2,
    "name": "Professional",
    "price": 99.99,
    "description": "Plan profesional",
    "features": ["Soporte prioritario"],
    "maxDevices": 100,
    "maxAdministrators": 5,
    "supportLevel": "priority",
    "hasAPI": true,
    "hasAnalytics": true
  },
  "status": "active",
  "startDate": "2026-05-01T00:00:00Z",
  "endDate": null
}
```

#### **Plans Context**

**26. GET /plans**

```
GET /api/v1/plans
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "name": "Starter",
    "price": 29.99,
    "description": "Plan basico",
    "features": ["Soporte email"],
    "maxDevices": 10,
    "maxAdministrators": 2,
    "supportLevel": "basic",
    "hasAPI": false,
    "hasAnalytics": false
  },
  {
    "id": 2,
    "name": "Professional",
    "price": 99.99,
    "description": "Plan profesional",
    "features": ["Soporte prioritario", "Analytics basico"],
    "maxDevices": 100,
    "maxAdministrators": 5,
    "supportLevel": "priority",
    "hasAPI": true,
    "hasAnalytics": true
  }
]
```

#### **Payments Context**

**27. POST /subscriptions/payments/create-session**

```
POST /api/v1/subscriptions/payments/create-session
Content-Type: application/json

{
  "builderId": 1,
  "planId": 2,
  "successUrl": "https://demo/success",
  "cancelUrl": "https://demo/cancel"
}
```

Response (200 OK):
```json
{
  "sessionId": "cs_test_123",
  "checkoutUrl": "https://checkout.stripe.com/...",
  "amountInCents": 2999,
  "currency": "pen",
  "planId": 2,
  "planName": "Subscription Plan"
}
```

**28. POST /subscriptions/payments/confirm**

```
POST /api/v1/subscriptions/payments/confirm
Content-Type: application/json

{
  "builderId": 1,
  "sessionId": "cs_test_123"
}
```

Response (200 OK):
```json
{
  "status": "active",
  "subscriptionId": 55,
  "isNewSubscription": true
}
```

#### **Analytics Context**

**29. GET /analytics/metrics/{userId}**

```
GET /api/v1/analytics/metrics/10?role=builder
```

Response (200 OK):
```json
{
  "totalDevices": 120,
  "onlineDevices": 110,
  "offlineDevices": 10,
  "alertsCount": 2,
  "activeProjectsCount": 5,
  "totalUnits": 200,
  "occupiedUnits": 160,
  "occupancyRate": 0.8,
  "energyEfficiencyAvg": 0.92,
  "temperatureHistory": [
    { "timestamp": "2026-05-01T00:00:00Z", "value": 22.5, "type": "temperature" }
  ],
  "energyHistory": [
    { "timestamp": "2026-05-01T00:00:00Z", "value": 15.2, "type": "energy" }
  ],
  "hourlyEnergyData": [
    { "timestamp": "2026-05-01T01:00:00Z", "value": 1.2, "type": "energy" }
  ],
  "monthlyOccupancy": [
    { "month": "May", "occupancyRate": 0.8, "year": 2026 }
  ],
  "devicesByType": { "sensor": 80, "camera": 40 },
  "projectsOverview": [
    {
      "id": 1,
      "name": "Proyecto A",
      "location": "Lima",
      "status": "Active",
      "totalUnits": 50,
      "occupiedUnits": 40,
      "occupancyRate": 0.8,
      "deviceCount": 25
    }
  ]
}
```

**30. GET /analytics/insights**

```
GET /api/v1/analytics/insights?projectId=1&metric=energy&startDate=2026-05-01&endDate=2026-05-11
```

Response (200 OK):
```json
[
  { "timestamp": "2026-05-01T00:00:00Z", "value": 12.3, "type": "energy" },
  { "timestamp": "2026-05-02T00:00:00Z", "value": 11.8, "type": "energy" }
]
```

### Modelos de Datos (Resources / DTOs)

#### **Authentication & Users**

- **SignInResource**: email, password
- **SignUpResource**: email, password, role
- **AuthenticatedUserResource**: id, email, role, token
- **UserResource**: id, email, role
- **UpdatePasswordResource**: currentPassword, newPassword, confirmNewPassword

#### **Profiles**

- **CreateProfileResource**: userId, photoUrl, name, username, address, age, phoneNumber
- **UpdateProfileResource**: photoUrl, name, username, address, age, phoneNumber
- **ProfileResource**: id, userId, photoUrl, name, username, address, age, phoneNumber, secondEmail
- **SecondEmailResource**: secondEmail

#### **Clients**

- **CreateClientResource**: fullName, projectId, projectName, accountStatement, email, phoneNumber, address
- **UpdateClientResource**: mismo que CreateClientResource
- **ClientResource**: id, fullName, projectId, projectName, accountStatement, email, phoneNumber, address

#### **Projects**

- **CreateProjectResource**: name, description, location, totalUnits, builderId, imageUrl
- **UpdateProjectResource**: name, description, location, totalUnits, occupiedUnits, status, builderId, imageUrl
- **ProjectResource**: id, name, description, location, totalUnits, occupiedUnits, status, builderId, createdDate, imageUrl

#### **Units**

- **CreateUnitResource**: projectId, unitNumber, ownerId
- **UnitResource**: id, projectId, unitNumber, ownerId

#### **Devices**

- **CreateDeviceResource**: name, type, location, macAddress, projectId, status
- **UpdateDeviceResource**: name, type, location, projectId, status
- **DeviceResource**: id, name, type, location, macAddress, projectId, status

#### **Subscriptions**

- **CreateSubscriptionResource**: builderId, planId, status, startDate, endDate
- **UpdateSubscriptionResource**: planId, status, startDate, endDate
- **SubscriptionResource**: id, builderId, plan (PlanResource), status, startDate, endDate

#### **Plans**

- **PlanResource**: id, name, price, description, features, maxDevices, maxAdministrators, supportLevel, hasAPI, hasAnalytics

#### **Payments**

- **CreatePaymentSessionResource**: builderId, planId, successUrl, cancelUrl
- **PaymentSessionResource**: sessionId, checkoutUrl, amountInCents, currency, planId, planName
- **ConfirmPaymentResource**: builderId, sessionId
- **PaymentConfirmationResource**: status, subscriptionId, isNewSubscription

#### **Analytics**

- **HistoricalDataPointResource**: timestamp, value, type
- **MonthlyOccupancyDataResource**: month, occupancyRate, year
- **ProjectOverviewResource**: id, name, location, status, totalUnits, occupiedUnits, occupancyRate, deviceCount
- **DeviceHealthStatusResource**: deviceId, deviceName, type, status, healthPercentage
- **UnitDetailResource**: unitId, unitNumber, projectName, activeDevices, connectionStatus
- **BuilderDashboardResource**: totalDevices, onlineDevices, offlineDevices, alertsCount, activeProjectsCount, totalUnits, occupiedUnits, occupancyRate, energyEfficiencyAvg, temperatureHistory, energyHistory, hourlyEnergyData, monthlyOccupancy, devicesByType, projectsOverview

**Estadísticas del Sprint**

- Total de endpoints documentados: **30**
- Bounded contexts cubiertos: **11** (Authentication, Users, Profiles, Clients, Projects, Units, Devices, Subscriptions, Plans, Payments, Analytics)
- Operaciones implementadas: GET, POST, PUT, DELETE
- Autenticación: JWT con [Authorize] en contextos de Users, Profiles, Clients, Projects, Units; Público en Devices, Subscriptions, Plans, Payments, Analytics
- Integración externa: Stripe para pagos y suscripciones
- Modelos de datos: 25+ recursos/DTOs bien tipados
- Cobertura de API: Base URL `api/v1`, respuestas HTTP correctas con códigos 200, 201, 204, 400, 404, 500

*Nota. Elaboración propia.*

## 4.2.1.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 1 se implementó el despliegue de los componentes web de la plataforma IoBuild, estableciendo un flujo de integración y entrega continua desde el inicio del proyecto.

La **Landing Page** (`IoBuild-LandingPage`) fue desplegada utilizando un servicio de hosting estático con integración directa al repositorio de GitHub, activando despliegues automáticos ante cada merge a la rama `main`. Esto permitió al equipo validar los cambios visuales en un entorno de producción real de manera inmediata durante el sprint, acelerando el ciclo de feedback entre los integrantes.

URL de despliegue de la landing page: `https://ccaritatech.github.io/IoBuild-LandingPage/`

El **backend** (`IoBuild-Backend`) fue desplegado en una plataforma cloud compatible con aplicaciones ASP.NET Core, configurando las variables de entorno necesarias para la cadena de conexión a la base de datos, la clave secreta para la firma de tokens JWT y los parámetros del servicio BCrypt. La base de datos fue provisionada como servicio administrado, eliminando la necesidad de gestión manual del servidor.

URL de despliegue del backend: `https://io-build-back.arroz.dev/swagger/index.html`

La **aplicación móvil** (`ioBuild-kotlin`) se encuentra en fase de desarrollo inicial durante este sprint y aún no ha sido distribuida en ningún servicio de distribución. Su despliegue está planificado para un sprint posterior.

Evidencia del despliegue:

- **Landing Page:** Sitio publicado y accesible públicamente con las secciones Hero, Benefits, Features, Testimonials, Plans, About Us, FAQ y Footer completamente funcionales, con selector de idioma EN/ES operativo.

- **Web Services:** API REST activa con URL pública, documentación Swagger/OpenAPI accesible, 32 endpoints de los 11 bounded contexts respondiendo correctamente con los códigos HTTP esperados (201, 200, 204, 404).

*Nota. Elaboración propia.*

## 4.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, el equipo de IoBuild trabajó de manera coordinada distribuyendo las responsabilidades según las especialidades de cada integrante. Se utilizó GitHub como plataforma central de control de versiones, organizando el trabajo mediante ramas por feature y pull requests para integración a las ramas principales. A continuación se detalla la contribución individual de cada miembro del equipo.

---

**Fabrizio Martin Panta Castro**

Contribución Principal:

- Inicializó la estructura base del proyecto HTML y la configuración de metadatos SEO del repositorio `IoBuild-LandingPage`.
- Implementó el header con navegación responsiva y el hero section con la propuesta de valor principal de la plataforma.
- Desarrolló las secciones de Benefits, Advanced Technical Features, Testimonials, Pricing Plans, CTA final y Footer completo con columnas de navegación y redes sociales.
- Lideró la arquitectura de contenido de la landing page, estableciendo la estructura visual y el flujo de conversión del sitio.

---

**Iker Gabriel Barturen Panez** *(GitHub: krxxg04)*

Contribución Principal:

- Implementó el sistema completo de estilos CSS del repositorio `IoBuild-LandingPage`, definiendo las variables de diseño para theming, tipografía y paleta de colores.
- Desarrolló los estilos para todas las secciones: hero, benefits, features, testimonials, pricing, FAQ y footer.
- Implementó el sistema de diseño responsivo para todos los breakpoints (móvil, tablet y escritorio).
- Actualizó las fotografías y detalles del equipo en la sección About Us.
- En el backend (`IoBuild-Backend`), implementó el bounded context de Analytics: interfaces de fachada para proyectos y dispositivos, `AnalyticsController`, recursos del dashboard (`BuilderDashboardResource`, `DeviceHealthStatusResource`, `ProjectOverviewResource`) y el assembler correspondiente.

---

**Mateo Italo Loechle Arias** *(GitHub: LowMath)*

Contribución Principal:

- Desarrolló la sección FAQ completa en `IoBuild-LandingPage` con estructura de acordeón, respuestas detalladas y planes de precio.
- Implementó el selector de idioma y la internacionalización de la landing page con soporte para español e inglés.
- En el backend (`IoBuild-Backend`), implementó el bounded context de Clients completo: aggregate root `Client`, comandos de creación/actualización/eliminación, repositorio con búsqueda por email, query service, assemblers de recursos y `ClientsController` con operaciones CRUD.

---

**Brayan Roberto Ccarita Cruz**

Contribución Principal:

- Agregó los assets de imágenes y scripts de interactividad al repositorio `IoBuild-LandingPage`.
- En el backend (`IoBuild-Backend`), implementó el bounded context de IAM completo: aggregate root `User`, comandos de sign-up/sign-in/update-password, servicios de hashing con BCrypt, servicio y configuración de JWT, repositorio con EF Core, middleware de autorización con atributos personalizados, DTOs REST y los controllers de autenticación y usuarios.

---

**Axel Randall Ordonez Ricaldi** *(GitHub: nOOmz / nOOmzzzz)*

Contribución Principal:

- Contribuyó al desarrollo de la sección About Us en el repositorio `IoBuild-LandingPage`.
- En el backend (`IoBuild-Backend`), participó en el desarrollo de múltiples bounded contexts: Profiles, Projects, Units, Devices y Payments, implementando controllers, servicios y modelos de datos para la gestión integral de recursos IoT y suscripciones.

---

*Colaboración en GitHub — IoBuild-LandingPage.*

![Commits Landing Page](https://i.ibb.co/b5sHZjSQ/commitslanding.png)

![Contribuidores Landing Page](https://i.ibb.co/nqyk8HXr/contribuidoreslanding.png)

*Colaboración en GitHub — IoBuild-Backend.*

![Commits Backend](https://i.ibb.co/SD1psTZN/commitsbackend.png)

![Contribuidores Backend](https://i.ibb.co/1SPbRrD/contribuidoresbackend.png)


# 4.2.2. Sprint 2

El Sprint 2 se enfoco en la aplicacion Flutter de IoBuild, orientada al Segmento Objetivo #2: propietarios de departamentos. Mientras la aplicacion en Kotlin esta pensada para arquitectos e ingenieros, este sprint priorizo la experiencia del usuario final que administra su espacio, revisa sus dispositivos inteligentes y personaliza su cuenta desde un entorno movil sencillo e intuitivo.

Durante este sprint se consolidaron las funcionalidades mas importantes del segundo segmento objetivo, poniendo primero las user stories de mayor valor para el usuario: ver la lista de dispositivos, agregar nuevos dispositivos, configurar su informacion, gestionar notificaciones y administrar la cuenta. Con esto se busca asegurar que el producto avance desde las tareas mas criticas hacia las complementarias, tal como recomendo el profesor.

## 4.2.2.1. Sprint Planning 2

| Sprint # | Sprint 2 |
|---|---|
| **Sprint Planning Background** | |
| Date | 02/06/2026 |
| Time | 17:00 PM |
| Location | Google Meet |
| Prepared By | Iker Gabriel Barturen Panez |
| Attendees | Fabrizio Martin Panta Castro, Iker Gabriel Barturen Panez, Axel Randall Ordonez Ricaldi, Brayan Roberto Ccarita Cruz, Mateo Italo Loechle Arias |
| **Sprint Goal & User Stories** | |
| Sprint 2 Goal | Our focus is on completing the mobile application experience for apartment owners by implementing device management, notifications, user profile management and smart home monitoring features. We believe this delivers immediate value to residents who need a centralized and intuitive platform to interact with their connected devices and apartment services. This will be confirmed when users can successfully access their dashboard, monitor devices, manage notifications and configure their personal preferences through the Flutter mobile application. |
| Sprint 2 Velocity | 40 |
| Sum of Story Points | 40 |

## 4.2.2.2. Sprint Backlog 2

| Story ID | ID Task | Titulo | Descripcion | Estimacion (Horas) | Assigned To | Status |
|----------|---------|--------|-------------|--------------------|-------------|--------|
| US33 | TK15 | Ver Lista de Dispositivos | Como propietario, quiero ver una lista de todos los dispositivos registrados para poder monitorear su estado y ubicacion. | 3 | Iker Gabriel Barturen Panez | Done |
| US34 | TK16 | Agregar un Nuevo Dispositivo | Como propietario, quiero agregar un nuevo dispositivo al sistema para expandir la cobertura de monitoreo y control. | 3 | Brayan Roberto Ccarita Cruz | Done |
| US35 | TK17 | Editar/Configurar Ajustes de Dispositivo | Como propietario, quiero acceder a la configuracion especifica de un dispositivo para modificar sus parametros o revisar su informacion detallada. | 4 | Axel Randall Ordonez Ricaldi | Done |
| US37 | TK19 | Gestionar Notificaciones | Como usuario, quiero poder activar o desactivar varios tipos de notificaciones para controlar que alertas recibo del sistema. | 3 | Mateo Italo Loechle Arias | Done |
| US38 | TK20 | Cambiar Contrasena de la Cuenta | Como usuario, quiero poder cambiar mi contrasena periodicamente para mantener la seguridad de mi cuenta. | 3 | Iker Gabriel Barturen Panez | Done |
| US16 | TK11 | Acceder al perfil del usuario | Como usuario, quiero tener acceso a mi perfil, para ver datos como mi nombre, email, numero de telefono y mi direccion. | 5 | Brayan Roberto Ccarita Cruz | Done |
| US17 | TK12 | Edicion de Informacion del Perfil | Como usuario, quiero poder editar alguna parte de mi informacion, como mi email, numero de telefono o direccion, para mantener mis datos actualizados. | 6 | Axel Randall Ordonez Ricaldi | Done |
| US18 | TK13 | Ver Imagen que Representa al Usuario | Como usuario, quiero poder ver una imagen que me represente, para tener una experiencia mas personalizada. | 4 | Fabrizio Martin Panta Castro | Done |
| US19 | TK14 | Ver el Rol de la Cuenta | Como usuario, quiero poder ver el rol de mi cuenta, para entender que permisos tengo dentro de la aplicacion. | 4 | Mateo Italo Loechle Arias | Done |
| US36 | TK18 | Eliminar un Dispositivo | Como propietario, quiero poder eliminar un dispositivo que ya no esta en uso o esta defectuoso, para mantener la lista limpia y precisa. | 5 | Fabrizio Martin Panta Castro | Done |

## 4.2.2.3. Development Evidence for Sprint Review

Durante el Sprint 2 se implementaron las pantallas principales de la aplicacion Flutter para el segundo segmento objetivo. La funcionalidad desarrollada se centro en la gestion de dispositivos inteligentes, el acceso al perfil del usuario, la edicion de datos personales, la administracion de notificaciones y el cambio de contrasena.

Las evidencias siguientes muestran las pantallas desarrolladas y los flujos mas importantes de la aplicacion Flutter. Se organizaron por recorrido de uso para que la lectura del sprint sea mas clara y para no separar capturas que pertenecen al mismo modulo.

| Evidencia | Descripcion |
|---|---|
| ![Login](https://i.ibb.co/JFszLjzL/Whats-App-Image-2026-06-20-at-2-24-00-PM.jpg) | Pantalla de inicio de sesion. Se coloca primero porque representa el punto de entrada a la experiencia de la aplicacion y el acceso inicial del usuario propietario. |
| ![Inicio - resumen general](https://i.ibb.co/twcdMmjv/Whats-App-Image-2026-06-20-at-2-11-38-PM.jpg) | Pantalla de inicio o panel del propietario. Muestra el resumen general de la cuenta, las unidades asociadas, los dispositivos en linea, el consumo energetico, la temperatura promedio y el numero de alertas. |
| ![Menu lateral](https://i.ibb.co/Z1dXTWVV/Whats-App-Image-2026-06-20-at-2-11-53-PM.jpg) | Menu lateral de navegacion. Esta vista resume las secciones principales de la app Flutter y permite moverse entre inicio, dispositivos, configuracion, perfil e idioma. |
| ![Inicio - analiticas](https://i.ibb.co/0yVzzdRr/Whats-App-Image-2026-06-20-at-2-15-22-PM.jpg) | Continuacion de la pantalla de inicio, con los paneles de consumo energetico diario, temperatura de 7 dias y consumo de agua semanal. |
| ![Inicio - estado de dispositivos](https://i.ibb.co/FkC4GqVD/Whats-App-Image-2026-06-20-at-2-15-22-PM-1.jpg) | Seccion de estado de dispositivos dentro del inicio, donde se visualiza el monitoreo de sensores y equipos registrados en distintas areas del proyecto. |
| ![Inicio - mis unidades](https://i.ibb.co/9m30ryWb/Whats-App-Image-2026-06-20-at-2-15-22-PM-2.jpg) | Seccion de unidades del propietario dentro del panel principal, donde se listan las unidades asociadas y la cantidad de dispositivos disponibles en cada una. |
| ![Dispositivos - gestion y registro](https://i.ibb.co/Kxwn4ZPb/Whats-App-Image-2026-06-20-at-1-38-33-PM.jpg) | Pantalla de gestion de dispositivos. Incluye el formulario para agregar un nuevo dispositivo y parte del listado general de equipos registrados. |
| ![Perfil del usuario](https://i.ibb.co/S492Jf07/Whats-App-Image-2026-06-20-at-1-38-33-PM-1.jpg) | Vista principal la opción agregar dispositivo, con informacion requisitos como el nombre, tipo, etc, para poder registrar nuevos dispositivos. |
| ![Configuracion](https://i.ibb.co/pvXKVHJG/Whats-App-Image-2026-06-20-at-2-14-19-PM.jpg) | Pantalla de configuracion, donde el usuario puede administrar notificaciones, seguridad y privacidad, correo alternativo y otros ajustes asociados a su cuenta. |
| ![Edicion de perfil](https://i.ibb.co/GfGzBHny/Whats-App-Image-2026-06-20-at-1-38-33-PM-2.jpg) | Flujo de edicion del perfil, donde el usuario puede modificar sus datos personales y guardar los cambios realizados. |
| ![Cambio de contrasena](https://i.ibb.co/kgWxqSH4/Whats-App-Image-2026-06-20-at-1-38-33-PM-4.jpg) | Modal de cambio de contrasena, utilizado para reforzar la seguridad de la cuenta del propietario. |

## 4.2.2.4. Testing Suite Evidence for Sprint Review

En esta iteracion del Sprint 2, la validacion se realizo a nivel funcional sobre la aplicacion Flutter, comprobando que los flujos principales del segundo segmento objetivo respondan correctamente dentro de la interfaz. Debido a que en esta fase no se ejecutaron pruebas automatizadas formales con `flutter test`, la evidencia presentada corresponde a pruebas manuales de uso sobre los modulos implementados.

| Evidencia | Descripcion |
|---|---|
| ![Eliminacion de dispositivo](https://i.ibb.co/qLD1Qzdg/Whats-App-Image-2026-06-20-at-5-00-39-PM.jpg) | Validacion funcional de eliminacion de dispositivo. La captura muestra el mensaje de confirmacion `Dispositivo eliminado correctamente`, evidenciando que la accion se ejecuto con exito en la interfaz. |
| ![Agregar dispositivo](https://i.ibb.co/0RpsMGTT/Whats-App-Image-2026-06-20-at-5-00-39-PM-1.jpg) | Flujo de registro de un nuevo dispositivo. En esta prueba se verifico el llenado del formulario con nombre, tipo, ubicacion y direccion MAC antes de guardar la informacion. |
| ![Dispositivo guardado en la lista](https://i.ibb.co/Hfpphytm/Whats-App-Image-2026-06-20-at-5-00-39-PM-2.jpg) | Resultado del registro del nuevo dispositivo. Se observa que `Ventilador` ya aparece en la lista, confirmando que el alta se reflejo correctamente en la interfaz de gestion. |
| ![Perfil antes de editar](https://i.ibb.co/235r1CmH/Whats-App-Image-2026-06-20-at-5-00-39-PM-3.jpg) | Estado inicial del perfil antes de la modificacion. Esta captura sirve como referencia de los datos originales del usuario antes de ejecutar la prueba de edicion. |
| ![Edicion del perfil](https://i.ibb.co/DgMN5L87/Whats-App-Image-2026-06-20-at-5-00-39-PM-4.jpg) | Flujo de edicion del perfil. Durante esta validacion se modificaron el numero telefonico y la direccion del propietario para comprobar que los campos acepten y procesen nuevos valores. |
| ![Perfil actualizado](https://i.ibb.co/848jtZyp/Whats-App-Image-2026-06-20-at-5-00-39-PM-5.jpg) | Resultado final de la prueba de perfil. La vista confirma que los nuevos datos fueron guardados y mostrados correctamente en la cuenta del usuario. |
| ![Cambio de configuracion](https://i.ibb.co/cKFXwCCP/Whats-App-Image-2026-06-20-at-5-06-26-PM.jpg) | Validacion funcional del modulo de configuracion. La captura evidencia que el usuario puede activar y desactivar opciones de notificaciones dentro de la interfaz de configuracion de la aplicacion. |

Estas validaciones permitieron comprobar que los modulos principales implementados en Flutter responden de forma coherente dentro del flujo de uso esperado para propietarios de departamentos. En consecuencia, la evidencia del Sprint 2 se presenta como validacion funcional manual de las historias asociadas a dispositivos, perfil y configuracion.

## 4.2.2.5. Execution Evidence for Sprint Review

La ejecucion del Sprint 2 se valido con una secuencia de capturas que muestra primero la preparacion del entorno con `flutter pub get`, luego la ejecucion de la aplicacion y finalmente la pantalla que se obtiene al abrir el enlace generado por Flutter DevTools. Esto permite evidenciar tanto la instalacion de dependencias como la puesta en marcha de la app Flutter.

| Evidencia | Descripcion |
|---|---|
| ![Flutter pub get](https://i.ibb.co/tMvjdTT9/Whats-App-Image-2026-06-20-at-2-09-01-PM.jpg) | Evidencia de la instalacion y resolucion de dependencias del proyecto mediante `flutter pub get`, paso necesario antes de ejecutar la aplicacion. |
| ![Ejecucion Flutter](https://i.ibb.co/sdkymj02/Whats-App-Image-2026-06-20-at-2-09-05-PM.jpg) | Inicio de la ejecucion de la aplicacion con `flutter run`, donde se observa la compilacion del proyecto y las advertencias tecnicas del entorno. |
| ![Ejecucion en progreso](https://i.ibb.co/mC2sgw3F/Whats-App-Image-2026-06-20-at-2-09-15-PM.jpg) | Ejecucion en curso de la app en dispositivo/emulador, mostrando el log de Flutter y la verificacion de que el proyecto se levanto correctamente. |
| ![Flutter DevTools](https://i.ibb.co/NdzvPtzX/Whats-App-Image-2026-06-20-at-2-03-56-PM.jpg) | Vista que aparece al abrir el enlace generado por la ejecucion, correspondiente a Flutter DevTools conectado a la app en tiempo real. |

## 4.2.2.6. Services Documentation Evidence for Sprint Review

La aplicacion Flutter del Sprint 2 consume un conjunto especifico de servicios REST del backend `IoBuild-Back`, todos expuestos bajo la base `https://io-build-back.arroz.dev/api/v1/`. A diferencia del Sprint 1, en esta seccion se documentan unicamente los endpoints realmente utilizados por la aplicacion movil orientada al segundo segmento objetivo: propietarios de departamentos.

Despues del inicio de sesion, la app guarda el token JWT y lo envia en las demas peticiones mediante el encabezado `Authorization: Bearer <token>`. Sobre esta base, el Sprint 2 consume servicios de autenticacion, dashboard, perfiles, usuarios y dispositivos.

| Modulo | Metodo | Endpoint | Uso dentro de la app Flutter |
|---|---|---|---|
| Authentication | `POST` | `/authentication/sign-in` | Permite el inicio de sesion del propietario y devuelve el token junto con los datos basicos del usuario. |
| Analytics | `GET` | `/analytics/metrics/{userId}?role=owner` | Alimenta el panel principal del propietario con metricas como unidades, dispositivos, alertas, energia, temperatura y consumo de agua. |
| Profiles | `GET` | `/users/{userId}/profiles` | Recupera la informacion del perfil del usuario para mostrar nombre, telefono, direccion, foto y correo secundario. |
| Profiles | `PUT` | `/profiles/{profileId}` | Permite actualizar la informacion editable del perfil desde la app Flutter. |
| Profiles | `POST` | `/profiles/second-email?userId={userId}` | Registra o actualiza el correo alternativo del usuario. |
| Users | `PUT` | `/users/{userId}/password` | Permite cambiar la contrasena desde la seccion de perfil y seguridad. |
| Devices | `GET` | `/devices` | Recupera la lista de dispositivos mostrada en la vista de gestion de dispositivos. |
| Devices | `GET` | `/devices/{deviceId}` | Permite consultar el detalle de un dispositivo especifico. |
| Devices | `POST` | `/devices` | Registra un nuevo dispositivo desde el formulario de alta. |
| Devices | `PUT` | `/devices/{deviceId}` | Actualiza la informacion de un dispositivo existente. |
| Devices | `DELETE` | `/devices/{deviceId}` | Elimina dispositivos registrados que ya no deben permanecer en la cuenta. |

Es importante precisar que, en esta version del Sprint 2, la pantalla de configuracion no consume un endpoint independiente de notificaciones. Las opciones visibles de notificaciones y soporte se presentan a nivel de interfaz, mientras que algunas acciones complementarias abren enlaces externos como FAQ y contacto. Por ello, no se incluyo una captura separada de un servicio de notificaciones en Swagger, ya que ese endpoint no forma parte del consumo real de la app Flutter en esta iteracion.

Las siguientes capturas de Swagger muestran los grupos de endpoints efectivamente utilizados por la aplicacion Flutter:

| Evidencia | Descripcion |
|---|---|
| ![Authentication endpoints](https://i.ibb.co/GvGwP6Jh/Whats-App-Image-2026-06-20-at-4-47-04-PM-2.jpg) | Endpoints del modulo `Authentication`, utilizados para el inicio de sesion de los propietarios mediante `POST /api/v1/authentication/sign-in`. |
| ![Analytics endpoints](https://i.ibb.co/tNSHCbg/Whats-App-Image-2026-06-20-at-4-47-04-PM-3.jpg) | Endpoints del modulo `Analytics`, donde destaca `GET /api/v1/analytics/metrics/{userId}` para poblar el panel principal del propietario. |
| ![Profiles endpoints](https://i.ibb.co/rL50qY6/Whats-App-Image-2026-06-20-at-4-47-04-PM-1.jpg) | Endpoints del modulo `Profiles`, utilizados para crear, consultar y actualizar la informacion del perfil, asi como registrar el correo secundario. |
| ![Users endpoints](https://i.ibb.co/XfkXbMqj/Whats-App-Image-2026-06-20-at-4-47-04-PM.jpg) | Endpoints del modulo `Users`, donde se documentan los servicios relacionados con recuperacion de perfil por usuario y cambio de contrasena. |
| ![Devices endpoints](https://i.ibb.co/WpGtg9BC/Whats-App-Image-2026-06-20-at-4-47-04-PM-4.jpg) | Endpoints del modulo `Devices`, utilizados para listar, registrar, consultar, actualizar y eliminar dispositivos desde la app Flutter. |

## 4.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se mantuvo el mismo despliegue del **backend** (`IoBuild-Backend`) utilizado por el proyecto, ya que la aplicacion Flutter del segundo segmento objetivo consume los mismos web services publicados en la nube. El backend se encuentra desplegado en una plataforma cloud compatible con aplicaciones ASP.NET Core, con la configuracion necesaria para la cadena de conexion a base de datos, firma de tokens JWT y servicios de seguridad.

URL de despliegue del backend: `https://io-build-back.arroz.dev/swagger/index.html`

Evidencia del despliegue del backend:

- **Web Services:** API REST activa con URL publica, documentacion Swagger/OpenAPI accesible y endpoints de los bounded contexts respondiendo correctamente con los codigos HTTP esperados (`201`, `200`, `204`, `404`), incluyendo los servicios consumidos por la aplicacion Flutter para autenticacion, dashboard, perfiles, usuarios y dispositivos.

En cuanto a la **aplicacion movil Flutter** (`ioBuild-flutter`), durante este sprint se realizo un despliegue local de tipo `debug build` para Android. Como parte del proceso, primero se resolvieron las dependencias del proyecto con `flutter pub get`, luego se genero exitosamente un artefacto instalable mediante `flutter build apk --debug` y finalmente se verifico la existencia del archivo APK en la ruta de salida del proyecto.

Comandos ejecutados durante el despliegue local:

```powershell
flutter pub get
flutter build apk --debug
Get-ChildItem .\build\app\outputs\flutter-apk\
```

Resultado del build:

```text
Built build\app\outputs\flutter-apk\app-debug.apk
```

Ruta del artefacto generado:

```text
build\app\outputs\flutter-apk\app-debug.apk
```

Nombre del artefacto:

```text
app-debug.apk
```

Tamano aproximado del APK:

```text
173,705,663 bytes
```

Entorno de despliegue:

- Sistema operativo: Windows
- Framework: Flutter
- Plataforma objetivo: Android
- Modo de compilacion: Debug
- Artefacto generado: APK instalable

Despues de generar el APK, este quedo disponible para instalacion en emulador Android o dispositivo fisico, permitiendo validar la ejecucion de la aplicacion y la navegacion principal del segundo segmento objetivo.

| Evidencia | Descripcion |
|---|---|
| ![Flutter pub get para despliegue](https://i.ibb.co/FL06NyLs/Whats-App-Image-2026-06-20-at-5-30-02-PM.jpg) | Resolucion de dependencias del proyecto mediante `flutter pub get`, paso previo necesario para compilar correctamente la aplicacion Flutter. |
| ![Build APK debug](https://i.ibb.co/8n2BWcLK/Whats-App-Image-2026-06-20-at-5-30-03-PM.jpg) | Ejecucion del comando `flutter build apk --debug`, evidenciando la compilacion local de la aplicacion para Android y la generacion del artefacto instalable. |
| ![Listado del APK generado](https://i.ibb.co/s9MHgwnG/Whats-App-Image-2026-06-20-at-5-30-03-PM-1.jpg) | Verificacion del contenido de la carpeta `build\app\outputs\flutter-apk\`, donde se confirma la generacion del archivo APK correspondiente al build debug. |
| ![Archivo APK generado](https://i.ibb.co/wFdbfG1S/Whats-App-Image-2026-06-20-at-5-30-03-PM-2.jpg) | Evidencia del archivo `app-debug.apk` dentro de la ruta de salida del proyecto, confirmando que la aplicacion fue empaquetada exitosamente como artefacto instalable. |
| ![APK listo para compartir](https://i.ibb.co/CKNtSGSB/Whats-App-Image-2026-06-20-at-5-47-43-PM.jpg) | Evidencia adicional del archivo APK desde el explorador de archivos, mostrando que el artefacto generado se encuentra disponible y listo para ser compartido o enviado para su instalacion en otros dispositivos. |

## 4.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2, el equipo trabajo de forma coordinada para avanzar en la aplicacion Flutter orientada a propietarios de departamentos. La distribucion de tareas se organizo segun las user stories mas importantes, priorizando primero las funciones que aportan mayor valor al usuario final y luego las funcionalidades complementarias. Se mantuvo una comunicacion fluida a traves de reuniones diarias de seguimiento, donde se discutian los avances, bloqueos y ajustes necesarios para cumplir con los objetivos del sprint.

**Evidencia visual de colaboracion**

![Commits Sprint 2](https://i.ibb.co/Pzv4Fky4/Chat-GPT-Image-20-jun-2026-01-37-47-p-m.png)

![Pull Requests Sprint 2](https://i.ibb.co/zWnXfwXR/Whats-App-Image-2026-06-20-at-1-44-51-PM.jpg)

![Organizacion en Trello Sprint 2](https://i.ibb.co/sdnwRWwt/Whats-App-Image-2026-06-20-at-2-01-38-PM.jpg)

*Colaboración en GitHub — IoBuild-Backend.*

![Commits Backend](https://i.ibb.co/SD1psTZN/commitsbackend.png)

![Contribuidores Backend](https://i.ibb.co/1SPbRrD/contribuidoresbackend.png)

#### 4.3. Validation Interviews

##### 4.3.1. Diseño de Entrevistas

Para validar la propuesta de IoBuild se realizó una entrevista semiestructurada a un usuario representativo del segundo segmento objetivo del proyecto. En el Sprint 2, el enfoque principal estuvo en los propietarios de departamentos, debido a que la aplicación Flutter está orientada a este grupo de usuarios.

El objetivo de la entrevista fue identificar si las funcionalidades desarrolladas responden a necesidades reales, comprender la percepción del usuario sobre la gestión de dispositivos inteligentes y recoger observaciones sobre la facilidad de uso de la aplicación.

La estructura de la entrevista fue sencilla:

- Presentación breve del proyecto.
- Preguntas de contexto sobre el usuario.
- Preguntas sobre sus necesidades actuales.
- Preguntas sobre la utilidad de IoBuild.
- Cierre con sugerencias y comentarios.

URL de la entrevista:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202215004_upc_edu_pe/IQB0wUmgIUlAQ5Qhd0xoGsypAQ8-fdFbPCivjLECi-FCrho?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=UJb35j

Preguntas guía utilizadas:

1. ¿Qué tipo de departamento o espacio administra actualmente y con qué frecuencia necesita supervisarlo?
2. ¿Cómo controla actualmente los dispositivos o servicios de su espacio y qué dificultades encuentra en ese proceso?
3. ¿Qué tan útil le parece contar con una aplicación móvil para visualizar el estado de sus dispositivos, consumo y alertas?
4. ¿Qué tan clara le resulta la navegación de la aplicación entre inicio, dispositivos, configuración y perfil?
5. ¿Qué tan sencillo le parece el proceso de agregar, visualizar o eliminar un dispositivo dentro de la aplicación?
6. ¿Qué tan útil le parece poder editar su información personal, cambiar su contraseña y configurar notificaciones desde la app?
7. ¿Considera que la información mostrada en el dashboard y en la lista de dispositivos es suficiente para tomar decisiones sobre su espacio? ¿Qué agregaría?
8. ¿Qué problemas, confusiones o dificultades cree que podría tener al usar esta aplicación por primera vez?
9. ¿Qué funcionalidad considera más valiosa dentro de la app y cuál mejoraría?
10. ¿Usaría una aplicación como IoBuild en su vida diaria? ¿Por qué?

##### 4.3.2. Registro de Entrevistas

La entrevista se registró en un formato simple para facilitar su posterior análisis. El registro incluye la fecha, el entrevistado, el segmento al que pertenece y los hallazgos principales.

| ID | Fecha | Entrevistado | Segmento | Modalidad | Hallazgos principales | Observaciones |
|------|------------|------------------|------------------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| E01 | 20/06/2026 | Julio Gómez | Propietario de departamento | Virtual | El entrevistado administra un departamento en alquiler con varios dispositivos IoT y actualmente debe supervisarlos con una frecuencia aproximada de un mes. Identificó como principal dificultad la falta de unificación entre dispositivos de distintas marcas, por lo que consideró muy valioso que IoBuild centralice en una sola aplicación el estado de los equipos, consumos, alertas y opciones de control. También indicó que la navegación le resultó clara, que los procesos de agregar, editar y eliminar dispositivos son sencillos y que la gestión de perfil, contraseña y notificaciones es útil para el uso cotidiano. | La funcionalidad que consideró más valiosa fue el sistema de alertas y monitoreo del estado de los dispositivos. Confirmó que utilizaría una aplicación como IoBuild en su vida diaria porque le permitiría ahorrar tiempo y gestionar mejor todos sus equipos desde un solo lugar. |

El registro permitió identificar hallazgos clave relacionados con la necesidad de una interfaz clara, acceso rápido a las funciones principales y una navegación sencilla dentro de la aplicación. Asimismo, confirmó que la propuesta de centralizar el control de dispositivos en una sola plataforma genera valor real para el segundo segmento objetivo.

##### 4.3.3. Evaluaciones según heurísticas

Esta sección contiene el proceso de evaluación de la sesión de validación basado en heurísticas, considerando principios de usabilidad, arquitectura de información e inclusive design de la experiencia propuesta. Para ello se utilizó como referencia el formato del Anexo E: Formato para Evaluación de User Experience según Heurísticas.

**UX Heuristics & Principles Evaluation**
**Usability - Inclusive Design - Information Architecture**

| Campo            | Detalle                                         |
| ---------------- | ----------------------------------------------- |
| Carrera          | Ingeniería de Software                          |
| Curso            | 1ACC0238 Aplicaciones para Dispositivos Móviles |
| Sección          | 3687                                            |
| Profesor         | David Gerardo Quevedo Velasco                   |
| Auditor          | CcaritaTech                                     |
| Cliente evaluado | Julio Gómez                                     |

**Nota:** Los contenidos de esta evaluación corresponden a la aplicación Flutter de IoBuild validada durante el Sprint 2. Se utiliza el formato del Anexo E como referencia para documentar hallazgos de usabilidad, arquitectura de información e inclusive design.

**Site o app a evaluar:** IoBuild Flutter - Segmento de propietarios de departamentos

**Tareas a evaluar**

El alcance de esta evaluación incluye la revisión de usabilidad de las siguientes tareas:

1. Inicio de sesión en la aplicación.
2. Revisión del panel del propietario.
3. Navegación entre inicio, dispositivos, configuración y perfil.
4. Visualización de la lista de dispositivos registrados.
5. Registro de un nuevo dispositivo.
6. Eliminación de un dispositivo.
7. Edición de información del perfil.
8. Cambio de contraseña.
9. Activación y desactivación de notificaciones.
10. Revisión del estado de dispositivos, alertas y métricas de consumo.

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Registro de nuevos usuarios.
2. Autenticación de dos factores.
3. Distribución externa del APK en tiendas o servicios públicos.
4. Gestión de soporte o contacto más allá de enlaces externos.
5. Integraciones avanzadas con dispositivos físicos reales en tiempo real.

**Escala de severidad**

Los errores fueron puntuados tomando en cuenta la siguiente escala de severidad:

| Nivel | Descripción                                                                                                                                                                                   |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Problema superficial: puede ser fácilmente superado por el usuario y ocurre con muy poca frecuencia. No necesita ser arreglado a menos que exista disponibilidad de tiempo.                   |
| 2     | Problema menor: puede ocurrir con poca frecuencia o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja para resolverlo de cara al siguiente release. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo con facilidad. Es importante que sea corregido y se le debe asignar una prioridad alta.                     |
| 4     | Problema crítico: error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                                  |

### Tabla resumen de evaluación

| # | Problema                                                                                                                                                                                                    | Escala de severidad | Heurística o principio violado                         |
| - | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------ |
| 1 | El formulario para agregar dispositivo aparece sobre la misma pantalla de listado y puede generar distracción visual o confusión durante la tarea.                                                          | 2                   | Usability: Libertad y control del usuario              |
| 2 | La lista de dispositivos muestra columnas o textos parcialmente recortados, lo que dificulta interpretar con claridad algunos datos del dispositivo.                                                        | 2                   | Usability: Consistencia y estándares                   |
| 3 | Algunas opciones de configuración, como autenticación de dos factores o dispositivos conectados, aparecen disponibles visualmente aunque no forman parte de la validación funcional del sprint.             | 3                   | Information Architecture: Is it usable?                |
| 4 | El cambio de notificaciones no muestra una confirmación explícita de guardado o persistencia, por lo que el usuario puede dudar si el cambio fue aplicado correctamente.                                    | 2                   | Usability: Visibilidad del estado del sistema          |
| 5 | La información del perfil y de ciertas vistas extensas puede quedar muy densa para algunos usuarios, especialmente cuando se muestran direcciones largas o múltiples bloques de datos en una sola pantalla. | 1                   | Inclusive Design: Proporciona experiencias comparables |

### Descripción de problemas

**Problema #1: El formulario para agregar dispositivo aparece sobre la misma pantalla de listado y puede generar distracción visual o confusión durante la tarea.**
**Severidad:** 2
**Heurística violada:** Usability - Libertad y control del usuario
**Problema:** Durante la validación se observó que el flujo de alta de dispositivos se presenta dentro de la misma vista de gestión, superpuesto al listado existente. Aunque el usuario entrevistado consideró que el proceso es sencillo, visualmente la pantalla mezcla el formulario con el contenido ya registrado, lo que puede dificultar la concentración o hacer menos evidente cómo cancelar la acción y volver al estado anterior.
**Recomendación:** Separar el alta de dispositivos en un modal más delimitado o en una pantalla independiente, incorporando además controles de cierre más visibles y una jerarquía visual más clara entre "Agregar", "Guardar" y "Cancelar".

**Problema #2: La lista de dispositivos muestra columnas o textos parcialmente recortados, lo que dificulta interpretar con claridad algunos datos del dispositivo.**
**Severidad:** 2
**Heurística violada:** Usability - Consistencia y estándares
**Problema:** En la vista de gestión de dispositivos algunos encabezados o valores quedan truncados por el ancho disponible, lo cual afecta la lectura del tipo, la ubicación u otros atributos del equipo. Este detalle no bloquea la tarea, pero puede generar errores de interpretación cuando la lista crezca o cuando el usuario necesite revisar información rápidamente.
**Recomendación:** Ajustar el diseño responsivo de la tabla o lista para priorizar campos clave, usar tarjetas por dispositivo, permitir scroll horizontal controlado o mostrar un detalle expandible cuando el contenido exceda el espacio disponible.

**Problema #3: Algunas opciones de configuración aparecen disponibles visualmente aunque no forman parte del flujo funcional validado en esta versión.**
**Severidad:** 3
**Heurística violada:** Information Architecture - Is it usable?
**Problema:** En la pantalla de configuración se muestran opciones como autenticación de dos factores o dispositivos conectados, pero no todas cuentan con una funcionalidad plenamente validada dentro del sprint. Esto puede generar expectativas incorrectas en el usuario, que percibe estas opciones como completamente operativas aunque aún formen parte de una evolución posterior.
**Recomendación:** Ocultar temporalmente las opciones no implementadas, marcarlas como "Próximamente" o deshabilitarlas visualmente con una explicación breve que aclare su disponibilidad futura.

**Problema #4: El cambio de notificaciones no muestra una confirmación explícita de guardado o persistencia.**
**Severidad:** 2
**Heurística violada:** Usability - Visibilidad del estado del sistema
**Problema:** Durante la validación funcional se comprobó que es posible activar y desactivar interruptores de notificación. Sin embargo, la interfaz no muestra un mensaje claro que confirme si el cambio fue almacenado, si se mantiene al salir de la pantalla o si solo se trata de un cambio visual temporal.
**Recomendación:** Agregar retroalimentación inmediata como un mensaje de confirmación, indicador de guardado automático o estado persistente visible para que el usuario tenga certeza de que la acción fue aplicada.

**Problema #5: La información del perfil y de ciertas vistas extensas puede resultar visualmente densa para algunos usuarios.**
**Severidad:** 1
**Heurística violada:** Inclusive Design - Proporciona experiencias comparables
**Problema:** Aunque la navegación fue valorada como intuitiva por el entrevistado, algunas pantallas concentran varios bloques de información, textos largos y controles en una sola vista. Esto puede afectar a usuarios con menor familiaridad digital o con dificultades de lectura rápida en dispositivos móviles.
**Recomendación:** Incrementar el espaciado visual, resumir datos secundarios, usar mejor jerarquía tipográfica y considerar ayudas visuales adicionales para que el contenido sea más fácil de escanear en pantallas pequeñas.

En conjunto, la evaluación heurística muestra que la aplicación ofrece una base sólida de navegación y utilidad para el segundo segmento objetivo, algo que además fue reforzado por la entrevista realizada. No obstante, también revela oportunidades claras de mejora en feedback visual, organización de opciones y claridad de algunas vistas antes de una versión más madura del producto.

# Conclusiones

El desarrollo del Sprint 2 permitió consolidar la experiencia móvil de IoBuild para el segundo segmento objetivo: propietarios de departamentos. A diferencia del Sprint 1, enfocado en la aplicación Kotlin para arquitectos e ingenieros, este sprint se orientó a construir una solución en Flutter pensada para usuarios finales que necesitan supervisar sus espacios, revisar información relevante y gestionar dispositivos inteligentes desde una interfaz sencilla.

La aplicación Flutter logró integrar funcionalidades centrales para el propietario, como el inicio de sesión, visualización del panel principal, gestión de dispositivos, edición de perfil, cambio de contraseña y configuración de notificaciones. Estas funcionalidades responden directamente a las necesidades identificadas durante la validación, especialmente la importancia de centralizar en una sola aplicación el monitoreo de equipos, alertas y datos del departamento.

El Sprint 2 también permitió validar la conexión entre la aplicación móvil y el backend compartido del proyecto. La app Flutter consume servicios de autenticación, perfiles, usuarios, métricas y dispositivos, utilizando la API REST desplegada y documentada mediante Swagger/OpenAPI. Esto demuestra que la solución mantiene trazabilidad entre frontend móvil, servicios backend y evidencia técnica del funcionamiento de los endpoints utilizados.

Como parte de la evidencia de ejecución y despliegue, se comprobó que el proyecto Flutter puede resolver dependencias, ejecutarse correctamente y generar un APK en modo debug para Android. La creación del archivo `app-debug.apk` confirma que la aplicación puede empaquetarse como artefacto instalable, lo cual representa un avance importante hacia la validación funcional en emuladores o dispositivos físicos.

La entrevista de validación realizada reforzó la relevancia de la propuesta para propietarios de departamentos. El usuario entrevistado valoró especialmente la posibilidad de unificar la gestión de dispositivos de distintas marcas, revisar alertas y acceder a información del estado del espacio desde una sola plataforma. Además, indicó que la navegación de la aplicación resulta clara y que los flujos principales, como agregar dispositivos o editar el perfil, son fáciles de comprender.

La evaluación heurística permitió identificar oportunidades de mejora antes de una versión más madura del producto. Aunque la aplicación presenta una base funcional sólida, se detectaron aspectos a optimizar en claridad visual, retroalimentación del sistema, organización de opciones y densidad de información en algunas pantallas. Estos hallazgos son útiles para priorizar ajustes de usabilidad en próximos releases.

En conclusión, el Sprint 2 fortaleció la propuesta de IoBuild al demostrar que la plataforma puede atender a dos segmentos diferenciados mediante aplicaciones móviles específicas. La app Flutter aporta valor directo a propietarios de departamentos al ofrecer una experiencia práctica, centralizada y orientada al control de dispositivos inteligentes, mientras que el backend común asegura continuidad técnica, reutilización de servicios y coherencia dentro del ecosistema del proyecto.

## Bibliografía
- CEELA. (2024). Perú – Proyecto CEELA – Eficiencia energética en edificios. Rescato de https://proyectoceela.com/
- Nexoinmobiliario. (2025). ¿Vale la pena comprar un departamento con certificación LEED Lima?. Rescato de https://shorturl.at/aRS1m
- JLL. (2024). Evolución sostenible: Edificios verdes en América Latina. Rescato de https://shorturl.at/QNYAH
- Digi. (2024). IoT Aplicaciones para edificios inteligentes: Casos de uso y principales ventajas. Rescato de https://shorturl.at/idxvo
- Domotec. (n.d.). Inicio. Rescato de https://www.domotecperu.com/
- MWF Solutions. (n.d.). Incio. Rescato de https://mwfsolutions.pe/
- Orbivo Perú. (n.d.). Inicio. Rescato de https://orviboperu.com.pe/
- Lucid Software Inc. (n.d.). Lucidchart. Rescatado de https://www.lucidchart.com/
- Structurizr Ltd. (n.d.). Structurizr. Rescatado de https://structurizr.com/
- Fowler, M. (2013). GivenWhenThen. Rescatado de https://shorturl.at/mqTb5
- Git SCM. (n.d.). Git. Rescatado de https://git-scm.com/

## Anexos

#### ANEXO A: Investigación y Análisis de Usuarios

Este anexo contiene la evidencia de la investigación que valida la necesidad de la plataforma IoBuild y sustenta las decisiones de diseño centradas en el usuario.

**Repositorio de la organización**
<https://github.com/CcaritaTech>

**URL de las entrevistas: upc-pre-2025200-1asi0730-7461-CcaritaTech-needfinding**
<>

<div style="page-break-before: always;"></div>

#### ANEXO B: Documentación del Diseño y la Experiencia de Usuario (UX/UI)

Este anexo incluye los artefactos visuales y la documentación del proceso de diseño que demuestran la planificación de la experiencia de usuario y la interfaz de la plataforma IoBuild.

**Lean UX Canvas**
<https://url-shortener.me/16XS>

**User Persona**
- Arquitectos e Ingenieros Civiles
<https://shorturl.at/u03eE>

- Propietaros de Apartamentos
<https://shorturl.at/6letU>

**Empathy Mapping**
- Arquitectos e Ingenieros Civiles
<https://shorturl.at/OweNc>

- Propietaros de Apartamentos
<https://url-shortener.me/16XB>

**User Journey Map**
- Arquitectos e Ingenieros Civiles
<https://url-shortener.me/16XF>

- Propietaros de Apartamentos
<https://url-shortener.me/16XI>

**Impact Mapping**
<https://tinyurl.com/ytzz3rdn>


