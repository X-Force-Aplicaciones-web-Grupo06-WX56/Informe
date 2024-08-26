**Universidad Peruana de Ciencias Aplicadas**

![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Carrera: Ingeniería de Software

Ciclo: 2024-02

Curso: Aplicaciones Web

Sección: WX53

Profesor: Alberto Wilmer Sanchez Seña

Informe del Trabajo Final

Startup: Law Connect

Producto: peer-to-peer

Integrantes:

- Alessandro Ramiro Condori Lozano (u20211a118)
- Ivan Jeanpierre La Madrid Lozano (u202113432)
- Jeremy Paucar Meneses (U201919449)
- Jimena Alessandra Cossio Jimenez (U202117854)
- Jose Manuel Pariona Lucas (U202119257)

Agosto del 2024

---
# Registro de Versiones del Informe


---
# Project Report Collaboration Insights


---
# Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET: **ABET – EAC - Student Outcome 3** <br> Criterio: *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| - | - | - |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Alessandro Ramiro Condori Lozano** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo I del trabajo final. <br><br> **Ivan Jeanpierre La Madrid Lozano** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo III del trabajo final. <br><br> **Jeremy Paucar Meneses** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo IV del trabajo final. <br><br> **Jimena Alessandra Cossio Jimenez** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo V del trabajo final. <br><br> **Jose Manuel Pariona Lucas** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo II del trabajo final. <br><br>| El Lean UX Process es una herramienta valiosa para desarrollar software basado en las necesidades del usuario. Al centrarse en usuarios y realizar iteraciones frecuentes, podremos desarrollar productos de software más útiles, atractivos y eficientes. <br> Gracias a experiencias previas de redacción de historias de usuario, algunas, referentes a funcionalidades básicas, han sido rescatadas y adaptadas de proyectos anteriores, lo que nos permitió seguir puliendo trabajos anteriores. <br> Debido a estas evaluaciones en las entrevistas se logró determinar las necesidades importantes de los usuarios desde una perspectiva ética y profesional. | 
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Alessandro Ramiro Condori Lozano** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo I del trabajo final. <br><br> **Ivan Jeanpierre La Madrid Lozano** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo III del trabajo final. <br><br> **Jeremy Paucar Meneses** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo IV del trabajo final. <br><br> **Jimena Alessandra Cossio Jimenez** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo V del trabajo final. <br><br> **Jose Manuel Pariona Lucas** <br> ***TB1:*** Mi principal avance fue realizar todo el capitulo II del trabajo final. <br><br> | Las entrevistas son una herramienta esencial para el needfinding en el desarrollo de software. Al hablar con los usuarios, hemos aprendido sobre dos nuevos segmentos objetivos definidos y pudimos identificar las necesidades en base a sus experiencias y opiniones. <br> Asimismo, conocer los competidores permiten la evaluación de un panorama más amplio en el desarrollo de la aplicación. |

---
# Contenido
## Tabla de contenidos

### [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-iii-requirements-specification)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
    - [Capítulo I: Introducción](#capítulo-i-introducción)
    - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
- [Capítulo I: Introducción](#capítulo-i-introducción-1)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
  - [2.1 Competidores](#21-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
  - [4.1. Style Guidelines](#41-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment-1)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1 Descripción de la Startup

Law Connect es un marketplace digital que conecta a personas que necesitan asesoría legal con abogados profesionales, facilitando un intercambio de servicios mutuamente beneficioso. Nuestra misión es descentralizar el mercado legal en Perú y democratizar el acceso a abogados de alta calidad, basándonos en las calificaciones de los usuarios.

Gracias a herramientas como videollamadas, chat en vivo y reuniones presenciales, podemos llegar a distintas partes del país, ofreciendo una plataforma accesible y eficiente. Además, en Law Connect nos comprometemos a apoyar a los abogados desempleados, conectándolos de manera efectiva con clientes potenciales.

En resumen, nuestra misión es facilitar la conexión entre clientes y abogados, brindando apoyo a quienes enfrentan problemas legales y asegurando que todos tengan acceso a asesoría legal de calidad.


### 1.1.2 Perfiles de integrantes del equipo

||Perfil|
| - | - |
| <img src="https://i.imgur.com/WJrkFy8.png" alt="Alessandro" width="1000" height="180"> |**Condori Lozano, Alessandro Ramiro** <br> *Ingeniería de Software* <br> Tengo 21 años, actualmente me encuentro matriculado en la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Poseo un nivel intermedio de habilidades en programación, con conocimientos adicionales en desarrollo web. Me considero una persona competitiva, responsable y que sabe trabajar en equipo.|

||Perfil|
| - | - |
|<img src="https://i.imgur.com/10nzkcz.png" alt="JeanPierre" width="1000" height="180">|**La Madrid Lozano, Ivan Jeanpierre** <br> *Ingeniería de Software* <br> Tengo 20 años. En estos momentos me encuentro estudiando la carrera de Ing. de Software en la Universidad Peruana de Ciencias Aplicadas. Cuento con conocimientos intermedios de programación y básicos en desarrollo web. Dicho esto, considero que soy una persona responsable que está en disposición de aportar al grupo.|

||Perfil|
| - | - |
|<img src="https://i.imgur.com/A8V9p0K.png" alt="Jeremy" width="1190" height="180">|**Paucar Meneses, Jeremy** <br> *Ingeniería de Software* <br> Tengo 22 años. En la actualidad estoy estudiando la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Albergo conocimientos intermedios en algunos lenguajes de programación, tales como C++, JavaScript y Python. Me considero una persona responsable con disposición de apoyar al grupo, también me gustan mucho los retos y así mismo poder cumplirlos.|

||Perfil|
| - | - |
|<img src="https://i.imgur.com/ObMgigR.png" alt="Jimena" width="1000" height="180">|**Cossio Jimenez, Jimena Alessandra** <br> *Ingeniería de Software* <br> Tengo 20 años. En estos momentos me encuentro estudiando la carrera de Ing. de Software en la Universidad Peruana de Ciencias Aplicadas. Cuento con conocimientos intermedios de programación y básicos en desarrollo web. Dicho esto, considero que soy una persona responsable que está en disposición de aportar al grupo.|

||Perfil|
| - | - |
|<img src="https://i.imgur.com/nNtnlel.png" alt="Jose" width="1010" height="180">|**Pariona Lucas, Jose Manuel** <br> *Ingeniería de Software* <br> Tengo 20 años. En la actualidad me encuentro cursando la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Cuento con conocimientos intermedios en programación. Me considero una persona flexible, comprometida con lo que hago y dispuesta a apoyar a mis compañeros en todo lo que pueda.|

## 1.2 Solution Profile
### 1.2.1 Antecedentes y problemática

Según Vallecilla (2024), hasta febrero del año 2024, la tasa de desempleo en Perú alcanzó el 7.30%. Esta situación afecta también a los egresados de la carrera de derecho, quienes enfrentan desafíos significativos para encontrar un empleo estable debido a la coyuntura actual. Además, las personas con problemas legales enfrentan dificultades para encontrar abogados de calidad, ya que carecen de orientación sobre dónde buscar o cómo encontrarlos.
| | |
|-|-|
|What(Que)| Se trata de abordar la problemática del desempleo entre los egresados de la carrera de derecho y la dificultad de las personas con problemas legales para encontrar abogados de calidad. |
|When (Cuándo)| Esta iniciativa se está llevando a cabo en el ciclo 2024-01. |
|Where (Dónde)|La acción se centra en Perú, donde se enfrentan desafíos específicos relacionados con el desempleo entre los egresados de derecho y la dificultad de acceso a servicios legales de calidad.|
|Who (Quién)|Egresados de la carrera de derecho que se encuentran en busca de empleo, personas que se encuentran con problemas legales que necesitan ayuda o asistencia legal y desarrolladores que trabajarán en la implementación de la solución.|
|Why (Por qué)|Ofrecer una solución para mitigar el desempleo entre los abogados y facilitar a las personas con problemas legales la búsqueda de asesoramiento legal de forma efectiva.|
|How (Cómo)|Se desarrollará una aplicación web que permita facilitar la búsqueda de abogados a los clientes que necesitan ayuda o asistencia legal, ofreciendo beneficios a los abogados. Esto se realizará mediante el uso de lenguajes de programación y patrones de desarrollo.|
|How much (Cuánto)|La falta de empleo en los abogados evita que estos generen ingresos y obtengan experiencia laboral, mientras que por otro lado, los clientes pierden mucho tiempo y dinero buscando un abogado adecuado para resolver sus problemas legales.|

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Actualmente, las personas que enfrentan problemas legales se encuentran con dificultades para acceder a servicios legales de calidad debido a la carencia de orientación sobre dónde buscar o cómo encontrar abogados. Por otro lado, el desempleo en el Perú ha causado la dificultad en los abogados para asegurar empleo permanente, lo que afecta tanto a su estabilidad financiera como a su desarrollo profesional. Ante esta situación, nuestro objetivo es intervenir para resolver estos problemas: brindar a las personas acceso fácil a una lista de abogados que pueda ayudar con sus problemas legales y brindar oportunidades a los abogados desempleados para encontrar clientes o empresas, permitiéndoles generar ingresos y acumular experiencia laboral de manera significativa.

#### 1.2.2.2. Lean UX Assumptions

Business Assumptions
-	Creo que mis clientes necesitan: Acceso a abogados calificados de forma rápida y una plataforma que les permita encontrar y contratar abogados.
-	Estas necesidades se pueden resolver con: Una aplicación web que conecte a personas con problemas legales con abogados dispuestos a ofrecer servicios.
-	Mis clientes iniciales son (o serán): Personas con problemas legales que buscan asistencia legal y abogados desempleados en busca de oportunidades laborales.
-	El valor #1 que el cliente requiere de mi servicio: La rápida y efectiva comunicación entre cliente - abogado.
-	Adquiriré la mayoría de mis clientes a través de: Estrategias de marketing digital dirigidas a personas con problemas legales y campañas de sensibilización entre abogados desempleados sobre la plataforma.
-	Mi principal competencia en el mercado será: Firmas de abogados tradicionales y plataformas en línea que ofrecen servicios legales.
-	Mi mayor riesgo de producto es: La aceptación por parte de los usuarios de la plataforma y la necesidad de establecer la confianza en la calidad de los servicios legales proporcionados a través de la plataforma.

User Assumptions
¿Quién es el usuario? 
El usuario es tanto personas con problemas legales en busca de asesoramiento legal como abogados desempleados en busca de oportunidades laborales.
¿Dónde encaja nuestro servicio en su trabajo o vida? 
Nuestro producto se integra en la búsqueda y contratación de servicios legales, mejorando la accesibilidad, la confianza y la eficiencia en la conexión entre personas con problemas legales y abogados desempleados.
¿Qué problema tiene nuestro servicio y cómo se resuelve?
Nuestro producto resuelve la dificultad de encontrar abogados calificados para las personas con problemas legales, así como la falta de oportunidades laborales para los abogados desempleados.

¿Cuándo y cómo es usado nuestro servicio?
El producto se utiliza cuando las personas enfrentan problemas legales y necesitan asistencia legal, así como cuando los abogados desempleados buscan oportunidades laborales. Se accede a través de la aplicación web tanto desde dispositivos móviles como desde computadoras.

Users outcomes
-	Los usuarios pueden acceder a servicios legales de calidad de forma rápida y efectiva.
-	Los abogados pueden encontrar clientes y generar ingresos, contribuyendo así a su estabilidad financiera y desarrollo profesional.

Business outcomes
-	Incrementar la contratación de abogados a través de la plataforma.
-	Brindar una plataforma fácil de usar e interactiva con una buena experiencia de usuario.
-	Asegurar que la comunicación entre el abogado y el cliente sea sencilla dentro de la plataforma.
-	Reducir la tasa de desempleo entre los abogados al proporcionarles oportunidades laborales.

Users:
-	Personas que buscan un abogado que pueda ayudarlos con sus problemas legales.
-	Abogados en busca de personas con problemas legales

Features
¿Qué características son importantes?
Características clave incluyen facilidad de búsqueda y contratación de abogados, transparencia en calificaciones, seguridad en la protección de datos personales, y oportunidades laborales para abogados desempleados.
¿Cómo debe verse y comportarse nuestro producto?
El producto debe tener una interfaz intuitiva y amigable, proporcionar acceso rápido a información relevante sobre abogados y servicios legales, y ofrecer una experiencia fluida tanto para personas con problemas legales como para abogados desempleados.

#### 1.2.2.3. Lean UX Hypothesis Statements

-	Creemos que al proporcionar una plataforma digital que conecte a personas con problemas legales con abogados calificados de forma rápida y efectiva, aumentaremos la contratación de servicios legales y mejoraremos la satisfacción de los usuarios. Sabremos que esto es cierto cuando observemos un incremento en el número de contrataciones de abogados a través de la aplicación web.
-	Creemos que al ofrecer una experiencia de búsqueda y contratación de abogados fácil de usar, transparente y confiable a través de una aplicación web, mejoramos la satisfacción del usuario y la eficiencia en la conexión entre personas con problemas legales y abogados desempleados. Sabremos que hemos tenido éxito cuando al menos el 20% de los usuarios que han utilizado nuestra aplicación recomienden el servicio.
-	Creemos que al facilitar una comunicación entre personas con problemas legales y abogados a través de la plataforma, mejoraremos la personalización de los servicios legales y cerraremos la brecha de comunicación entre ambas partes. Sabremos que hemos logrado esto cuando al menos el 50% de los usuarios reporten una mejora en la calidad de la comunicación y cuando registremos un aumento en la satisfacción general con los servicios legales proporcionados a través de la plataforma. 

#### 1.2.2.4. Lean UX Canvas

![Canva](https://i.imgur.com/MFxXR0F.png)

Link: https://miro.com/welcomeonboard/Q3BjUlhrajRPTkNhOGJGR1duVlk2Rk92UTNtQjY2Q2x5NVFTWkEzNlJUNHkxN3ptbTMxZUpHUms0N3R5cUpnM3wzNDU4NzY0NTkwMjkzNjIwNDE1fDI=?share_link_id=809745947453

## 1.3. Segmentos objetivo

Personas con Problemas Legales: Este segmento busca acceso rápido y fiable a servicios legales. Utilizan la plataforma para encontrar abogados calificados, beneficiándose de funciones que garantizan transparencia y eficiencia en la selección del abogado adecuado. Los usuarios pueden subir o requerir documentos las veces que sea necesario, gracias a la plataforma

Abogados Calificados: Este grupo utiliza la plataforma para buscar oportunidades laborales, ganar visibilidad en el mercado y conectarse con potenciales clientes. La plataforma les ofrece herramientas para gestionar sus perfiles y casos, incrementando sus posibilidades de empleo y experiencia profesional. Los abogados pueden quedar los días en los cuales se darán resultados para asi el intercambio de la transacción o documentos con el usuario, siempre con mutuo acuerdo

# Capítulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog
# Capítulo IV: Product Design
## 4.1. Style Guidelines
## 4.2. Information Architecture
## 4.3. Landing Page UI Design
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram
# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Sprint Backlog 1

#### 5.2.1.3. Development Evidence for Sprint Review

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones
### Conclusiones y recomendaciones
### Video About-the-Team

---
# Bibliografía

---
# Anexos