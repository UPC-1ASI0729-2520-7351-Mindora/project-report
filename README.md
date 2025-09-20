# Informe del Trabajo Final

<div>
  <p align="center"><img src="assets/md-images/upc-logo.png" alt="Logo UPC" width="150px" /></p>
  <p align="center"><b>Informe de Trabajo Final</b></p>
  <p align="center">Facultad de Ingeniería</p>
  <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
  <p align="center">Ingeniería de Software</p>
  <p align="center">Desarrollo de Aplicaciones Open Source - 1ASI0729</p>
  <p align="center">NRC: 7351</p>
  <p align="center">Profesor: Rafael Oswaldo Castro Veramendi</p>
  <p align="center">Startup: NeuroDora</p>
  <p align="center">Producto: MinDora</p>
</div>

---

## Team members:

| **Nombre**                         | **Código** |
| ---------------------------------- | ---------- |
| Manuel Fernando, Joao Castro Picón | U20231G159 |
| Sebastián De Las Casas Latour      | U202213553 |
| Eduardo Fabián Chacaliaza Minaya   | U202324129 |
| Fabricio Fabián Quispe Barzola     | U202320442 |
| Juan Jose Meza Huanacune           | U202320574 |

<div>
  <p align="center"><b>Ciclo 2025 - 2</b></p>
  <p align="center"><b>Septiembre 2025</b></p>
</div>

---

## Registro de Versiones del Informe
> (Se completará al cierre con la línea de tiempo real de cambios.)

## Project Report Collaboration Insights
> (Se añadirán capturas y enlaces a contribuciones: commits, PRs, issues por integrante.)

# Contenido

1. **[Capítulo I: Introducción](#1-capítulo-i-introducción)**  
   &nbsp;&nbsp;&nbsp;&nbsp;1.1. [Startup Profile](#11-startup-profile)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.1. [Descripción del startup](#111-descripción-del-startup)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2. [Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)  
   &nbsp;&nbsp;&nbsp;&nbsp;1.2. [Solution Profile](#12-solution-profile)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.1. [Antecedentes y Problemática](#121-antecedentes-y-problemática)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2. [Lean UX Process](#122-lean-ux-process)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.1. [Lean UX Problem Statement](#1221-lean-ux-problem-statement)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)  
   &nbsp;&nbsp;&nbsp;&nbsp;1.3. [Segmentos objetivos](#13-segmentos-objetivos)

2. **[Capítulo II: Requirements Elicitation & Analysis](#2-capítulo-ii-requirements-elicitation--analysis)**  
   &nbsp;&nbsp;&nbsp;&nbsp;2.1. [Competidores](#21-competidores)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1.1. [Análisis competitivo](#211-análisis-competitivo)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.2. [Entrevistas](#22-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.3. [Needfinding](#23-needfinding)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.1. [User Personas](#231-user-personas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.2. [User Task Matrix](#232-user-task-matrix)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.3. [User Journey Mapping](#233-user-journey-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.4. [Empathy Mapping](#234-empathy-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4. [Ubiquitous Language](#24-ubiquitous-language)

3. **[Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)**  
   &nbsp;&nbsp;&nbsp;&nbsp;3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.2. [User Stories](#32-user-stories)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.3. [Impact Mapping](#33-impact-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.4. [Product Backlog](#34-product-backlog)

4. **[Capítulo IV: Product Design](#4-capítulo-iv-product-design)**  
   &nbsp;&nbsp;&nbsp;&nbsp;4.1. [Style Guidelines](#41-style-guidelines)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.1. [General Style Guidelines](#411-general-style-guidelines)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.2. [Web Style Guidelines](#412-web-style-guidelines)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.2. [Information Architecture](#42-information-architecture)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.1. [Organization Systems](#421-organization-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.2. [Labeling Systems](#422-labeling-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.4. [Searching Systems](#424-searching-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.5. [Navigation Systems](#425-navigation-systems)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.3. [Landing Page UI Design](#43-landing-page-ui-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.5. [Web Applications Prototyping](#45-web-applications-prototyping)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.1. [Class Diagrams](#471-class-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.2. [Class Dictionary](#472-class-dictionary)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.8. [Database Design](#48-database-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.8.1. [Database Diagram](#481-database-diagram)

5. **[Capítulo V: Product Implementation, Validation & Deployment](#5-capítulo-v-product-implementation-validation--deployment)**  
   &nbsp;&nbsp;&nbsp;&nbsp;5.1. [Software Configuration Management](#51-software-configuration-management)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.2. [Source Code Management](#512-source-code-management)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)  
   &nbsp;&nbsp;&nbsp;&nbsp;5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1. [Sprint 1](#521-sprint-1)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)  
   &nbsp;&nbsp;&nbsp;&nbsp;5.3. [Validation Interviews](#53-validation-interviews)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.1. [Diseño de Entrevistas](#531-diseño-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.2. [Registro de Entrevistas](#532-registro-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.3. [Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  
   &nbsp;&nbsp;&nbsp;&nbsp;5.4. [Video About-the-Product](#54-video-about-the-product)

7. **[Conclusiones](#6-conclusiones)**  
   &nbsp;&nbsp;&nbsp;&nbsp;6.1. [Conclusiones](#61-conclusiones)  
   &nbsp;&nbsp;&nbsp;&nbsp;6.2. [Recomendaciones](#62-recomendaciones)

8. **[Bibliografía](#7-bibliografía)**

9. **[Anexos](#8-anexos)**

---
# Student Outcome

El curso contribuye al cumplimiento del **Student Outcome ABET – EAC – Outcome 3**  

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC – Student Outcome 3.

---

## Cuadro de Student Outcome 3 – Comunicación efectiva (TB1)

| **Criterio específico** | **Acciones realizadas (TB1)** | **Conclusiones (TB1)** |
|-------------------------|-------------------------------|-------------------------|
| **Comunica oralmente con efectividad a diferentes rangos de audiencia** | - *Manuel Castro*: Participó en la presentación oral del **Startup Profile** en la exposición grabada de TB1.<br>- *Sebastián De Las Casa*: Expuso la introducción y objetivos del proyecto en la presentación grupal.<br>- *Eduardo Chacaliaza*: Explicó el apartado de **Solution Profile** durante la exposición.<br>- *Fabricio Quispe*: Presentó la problemática y segmentos objetivos.<br>- *Juan Meza*: Colaboró en la sustentación de la parte metodológica. | Como grupo logramos estructurar y presentar de forma oral los fundamentos iniciales del proyecto, repartiendo roles y asegurando que cada integrante comunicara claramente su parte a la audiencia. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia** | - *Manuel Castro*: Redacción de la **carátula** y parte de la descripción del startup.<br>- *Sebastián De Las Casa*: Contribuyó en el **índice de contenidos** y organización del documento.<br>- *Eduardo Chacaliaza*: Coordinó la escritura en **Markdown** y la conversión a PDF.<br>- *Fabricio Quispe*: Redactó los apartados de antecedentes y problemática.<br>- *Juan Meza*: Revisó ortografía y estilo en el Student Outcome. | A través de la redacción colaborativa en Markdown, logramos elaborar un informe inicial claro y coherente, demostrando la capacidad de comunicar ideas técnicas y conceptuales por escrito a una audiencia académica. |


---
# 1. Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestro startup llamado NeuroDora está enfocado en la rápida detección y apoyo en el tratamiento del estrés en el ámbito laboral de personas entre 20 y 50 años de edad. La solución aborda temas relacionados con la salud mental, la presión laboral y la necesidad de contar con servicios accesibles y confiables para mejorar el bienestar de los trabajadores.  

A través de un test interactivo, la plataforma recopila información sobre el estado de salud, el comportamiento, las actitudes y los patrones de cada usuario, identificando tempranamente señales de estrés. Con base en estos resultados, el sistema facilita el contacto directo con un psicólogo especializado y ofrece diversas actividades de apoyo para complementar el tratamiento y la gestión del estrés.  

NeuroDora se proyecta como un modelo de negocio independiente y sostenible, ofreciendo un esquema de suscripción para usuarios individuales y convenios con empresas interesadas en promover la salud mental de sus colaboradores. De esta manera, el proyecto combina la tecnología con un enfoque de impacto social positivo, contribuyendo a mejorar la calidad de vida en el entorno laboral.


### 1.1.2. Perfiles de los integrantes del equipo

| Foto | Nombres y Apellidos | Código | Carrera | Descripción |
|------|---------------------|--------|---------|-------------|
| ![Joao](assets/md-images/joao.jpg) | Manuel Fernando Joao Castro Picón | U20231G159 | Ingeniería de Software | Posee conocimientos en programación con Java y bases de datos, además de experiencia en buenas prácticas de desarrollo. Aporta en la construcción de la lógica de negocio y en el soporte técnico del proyecto. |
| ![Sebastián](assets/md-images/sebastián.jpg) | Sebastián De Las Casa Latour | U202213553 | Ingeniería de Software | Tiene habilidades en programación web y diseño de software, con interés en el aprendizaje de nuevas tecnologías. Contribuye en la implementación de interfaces y en la mejora de la experiencia de usuario. |
| ![Eduardo](assets/md-images/eduardo.jpg) | Eduardo Fabian Chacaliaza Minaya | U202324129 | Ingeniería de Software | Se enfoca en el desarrollo frontend y la creación de interfaces intuitivas y accesibles. Maneja herramientas de control de versiones y trabajo colaborativo en GitHub, aportando organización y documentación técnica al equipo. |
| ![Fabricio](assets/md-images/fabricio.jpg) | Fabricio Fabián Quispe Barzola | U202320442 | Ingeniería de Software | Cuenta con experiencia en prototipado en Figma, validación de ideas y análisis de datos. Aporta en la investigación de usuarios y en la elaboración de artefactos de UX que guían el desarrollo del proyecto. |
| ![Juan](assets/md-images/juan.jpg) | Juan José Meza Huanacune | U202320574 | Ingeniería de Software | Tiene experiencia en desarrollo backend con Java, C# y Python, además de bases de datos relacionales. También posee conocimientos en pruebas de software, contribuyendo a la calidad del sistema y al desarrollo de componentes del proyecto. |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

El estrés laboral es reconocido como uno de los principales problemas que afectan a la población económicamente activa, impactando tanto en la salud mental y física de los trabajadores como en la productividad de las organizaciones. En particular, los adultos entre 20 y 50 años son el grupo más vulnerable, ya que se encuentran en plena etapa laboral, expuestos a altos niveles de exigencia, presión por resultados y prolongadas jornadas de trabajo.  

La problemática identificada es la falta de herramientas accesibles y efectivas que permitan a las personas detectar de manera temprana sus niveles de estrés y recibir orientación práctica para gestionarlo. En muchos casos, los trabajadores no cuentan con mecanismos de autoevaluación ni con recomendaciones inmediatas que puedan aplicar en su día a día, lo cual incrementa el riesgo de desarrollar problemas de salud asociados al estrés crónico.  

El proyecto mindora surge como respuesta a esta necesidad. La propuesta consiste en desarrollar un sistema de identificación y gestión del estrés laboral mediante la observación y registro de señales corporales visibles como postura, tensión muscular facial, cambios en la respiración, sudoración, temblores o rojeces en la piel. Estos datos se integran en una aplicación que permite a los usuarios autoevaluar sus niveles de estrés, recibir recomendaciones personalizadas y acceder a estrategias prácticas de manejo, contribuyendo así a mejorar el bienestar de los trabajadores y la productividad organizacional.

#### 1.2.1.1. What  

*¿Cuál es el problema?*  
El estrés laboral afecta negativamente la salud física y mental de los trabajadores adultos, reduciendo su productividad, aumentando el ausentismo y deteriorando su calidad de vida.  

*¿Cuál es la relación con la persona en cuestión?*  
La relación es directa, ya que el sistema permitirá a los usuarios identificar sus niveles de estrés mediante señales corporales observables y técnicas de respiración, facilitando la adopción de medidas preventivas y correctivas oportunas.  

---

#### 1.2.1.2. Who  

*¿Quiénes están involucrados?*  
Los trabajadores adultos de 20 a 50 años, así como las empresas interesadas en mejorar la salud ocupacional de sus empleados.  

*¿A quiénes les sucede el problema?*  
A profesionales en edad productiva que enfrentan presión laboral, especialmente en sectores con altas exigencias, responsabilidades o ambientes competitivos.  

*¿Quién lo utilizará?*  
Adultos entre 20 y 50 años con acceso a dispositivos móviles, interesados en monitorear y gestionar su estrés de forma proactiva.  

---

#### 1.2.1.3. Where  

*¿Dónde está el cliente cuando usa el producto?*  
Principalmente en su entorno laboral: oficinas, teletrabajo desde casa o espacios donde realice su actividad profesional.  

*¿A dónde se dirige?*  
Hacia un estado de mayor autoconocimiento y manejo del estrés, con el objetivo de mejorar su bienestar y calidad de vida laboral.  

*¿Dónde surge el problema?*  
En el entorno laboral, donde la carga de trabajo, las relaciones interpersonales y el clima organizacional generan situaciones de tensión.  

---

#### 1.2.1.4. When  

*¿Cuándo sucede el problema?*  
Durante la jornada laboral, en momentos de alta presión, plazos ajustados, conflictos interpersonales, sobrecarga de trabajo o desequilibrio entre exigencias y recursos disponibles.  

*¿Cuándo utiliza el cliente el producto?*  
Durante el trabajo, en evaluaciones programadas o cuando perciba síntomas de tensión.  

---

#### 1.2.1.5. Why  

*¿Cuál es la causa del problema?*  
Altas exigencias laborales, recursos insuficientes, inseguridad laboral, conflictos interpersonales, desequilibrio entre vida personal y profesional, falta de control sobre las tareas y ausencia de herramientas efectivas para detectar y gestionar el estrés tempranamente.  

---

#### 1.2.1.6. How  

*¿En qué condiciones los clientes usan el producto?*  
En momentos de calma para establecer una línea base, en situaciones de tensión para recibir orientación inmediata y como herramienta de seguimiento diario.  

*¿Cómo nos conocieron los compradores?*  
A través de campañas digitales, recomendaciones de profesionales de salud ocupacional, programas corporativos de bienestar y marketing en plataformas utilizadas por profesionales.  

*¿Cómo prefieren acceder al contenido?*  
Mediante una aplicación móvil intuitiva, con notificaciones personalizadas, panel visual simple y recomendaciones prácticas fáciles de aplicar.  

*¿Qué los llevó a esta situación?*  
Una combinación de factores externos (presión laboral, clima organizacional) e internos (hábitos personales, estrategias de afrontamiento), junto con la falta de herramientas para gestionar el estrés de manera preventiva.  

---

#### 1.2.1.7. How much  

Según un estudio en seis países de Latinoamérica, hasta el 63% de los trabajadores sufre estrés laboral, especialmente mujeres (Mejía, 2019). De acuerdo con la Organización Mundial de la Salud (2020), el estrés laboral es una de las principales causas de ausentismo y disminución de productividad en la población activa, además de aumentar el riesgo de enfermedades físicas y mentales. Este impacto genera altos costos tanto en salud pública como en la calidad de vida de los trabajadores.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statement

Nuestra aplicación busca ayudar a los trabajadores a identificar y gestionar su estrés laboral a través de un test de autoevaluación y la observación de señales físicas como la postura, la respiración y la tensión facial. Asimismo, ofrece acceso a psicólogos y actividades prácticas orientadas a mejorar el bienestar.  

Hemos observado que un gran número de adultos entre 20 y 50 años experimenta niveles elevados de estrés en sus entornos laborales, pero carece de herramientas simples, accesibles y efectivas que les permitan reconocer estos niveles a tiempo y actuar de manera adecuada.  

**Pregunta guía:**  
¿Cómo podemos facilitar que los trabajadores detecten y manejen su estrés de forma temprana y efectiva en su entorno laboral, mediante una solución accesible, intuitiva y que se integre en su rutina diaria?

#### 1.2.2.2. Lean UX Assumptions

**Feature:** Sistema de identificación y gestión del estrés laboral en mindora  

**Registro biométrico y perfil del usuario**  
Creemos que nuestros usuarios, adultos de 20 a 50 años en el ámbito laboral, necesitan una forma sencilla y segura de registrar sus parámetros biométricos (a través de la cámara o sensores de sus dispositivos móviles), junto con información de salud y comportamiento. Esto permitirá personalizar el seguimiento y la gestión del estrés en función de las características individuales.  

**Detección temprana de estrés mediante patrones físicos**  
Creemos que la identificación de señales biométricas observables (postura, tensión muscular, patrones de respiración y sudoración) permitirá detectar de forma temprana niveles de estrés. Esto facilitará la intervención oportuna antes de que los síntomas se agraven, impactando positivamente en la salud mental y física de los usuarios.  

**Integración de evaluaciones psicológicas y recomendaciones personalizadas**  
Creemos que los usuarios se beneficiarán al combinar la autoevaluación biométrica con tests emocionales y recomendaciones personalizadas (ejercicios de respiración, pausas activas y contacto con especialistas). Esta integración permitirá conocer el estado en tiempo real y acceder a soluciones prácticas adaptadas a su contexto.  

**Seguimiento y análisis de datos de estrés**  
Creemos que disponer de un registro histórico del nivel de estrés y obtener estadísticas personalizadas ayudará a los usuarios a identificar patrones y cambios en su salud, promoviendo acciones preventivas y mejoras en su entorno laboral y personal.  

**Business outcomes (resultados del negocio)**  
- Aumentar la productividad laboral y reducir el ausentismo, ya que los trabajadores podrán identificar y gestionar su estrés de manera proactiva.  
- Generar ingresos a través de planes de suscripción individuales y acuerdos corporativos con empresas interesadas en el bienestar de sus empleados.  
- Posicionar a mindora como una herramienta innovadora y confiable para la salud mental en el ámbito laboral, ampliando su alcance en el mercado latinoamericano.  

**Users (usuarios)**  
- Profesionales y empleados de 20 a 50 años que desarrollan sus actividades en ambientes laborales exigentes y de alta presión.  
- Personas que desean mejorar su bienestar integral mediante el monitoreo de señales físicas y emocionales.  
- Usuarios que utilizan dispositivos móviles y buscan soluciones digitales para la autogestión de su salud mental.  

**User outcomes (beneficios para el usuario)**  
- Identificar sus niveles de estrés de manera temprana y objetiva mediante el análisis de patrones biométricos.  
- Acceder a recomendaciones personalizadas que les ayuden a manejar y reducir los síntomas de estrés.  
- Visualizar estadísticas y tendencias de su bienestar, facilitando el seguimiento en el tiempo.  
- Mejorar su calidad de vida laboral y personal gracias a estrategias adaptadas a sus necesidades específicas.  

**Features (características de la solución)**  
- Registro de datos biométricos a través de la cámara y sensores del dispositivo móvil.  
- Autoevaluación integral que combine aspectos emocionales y físicos del estrés.  
- Recomendaciones personalizadas de ejercicios, pausas activas y consejos de salud mental basados en el perfil del usuario.  
- Historial y dashboard interactivo que muestre evolución, tendencias y alertas de niveles de estrés.  
- Integración con profesionales de la salud mental y bienestar para intervenciones personalizadas.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 01**  
**Creemos** que la implementación de un sistema de registro biométrico y autoevaluación permitirá a los usuarios identificar tempranamente sus niveles de estrés laboral.  
**Sabemos** que esta hipótesis es cierta cuando se observe una correlación significativa entre los datos biométricos capturados y las autoevaluaciones realizadas por los usuarios.  
**Cuando** al menos el 65% de los usuarios complete de forma regular las evaluaciones en la plataforma y se detecten cambios relevantes en sus patrones biométricos.  

---

**Hypothesis Statement 02**  
**Creemos** que al ofrecer recomendaciones personalizadas basadas en el análisis del estrés, los usuarios adoptarán prácticas de autogestión más efectivas para reducir sus síntomas.  
**Sabemos** que esta hipótesis es cierta cuando los usuarios reporten mejoras en su bienestar y se registre una disminución en los indicadores de estrés durante los seguimientos periódicos.  
**Cuando** se logre una reducción del 20% en la frecuencia e intensidad de síntomas reportados en los primeros seis meses de uso.  

---

**Hypothesis Statement 03**  
**Creemos** que la visualización de un historial interactivo y tendencias de estrés motivará a los usuarios a llevar un control continuo de su salud mental.  
**Sabemos** que esta hipótesis es cierta cuando se registre un aumento en la interacción con el dashboard y una mayor adherencia a las recomendaciones sugeridas.  
**Cuando** el uso constante de las herramientas de seguimiento genere datos que indiquen una mayor consciencia y un manejo más proactivo del estrés en el entorno laboral.


#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas es una de las herramientas empleadas para comprender mejor a los posibles usuarios y sus necesidades. Esta técnica, propia del diseño centrado en el usuario y de la metodología Lean, permite estructurar de manera clara el problema, las hipótesis y los resultados esperados. Además, facilita el trabajo colaborativo en equipos multidisciplinarios, asegurando que el desarrollo del producto se realice de forma eficiente y orientada a generar valor para los usuarios.  

<div>
  <p align="center"><img src="assets/md-images/ux_canvas.png" alt="Canvas" width="700px" /></p>
</div>

## 1.3. Segmentos Objetivos

#### Segmento objetivo #1: Personas activas en el ámbito laboral:

Este segmento está compuesto por personas con horario de trabajo extensos, de más de 8 horas laborales. Estos ciudadanos suelen experimentar una presión psicológica alta en sus trabajos lo cuál termina en generar un cuadro de estrés que puede perjudicar su rendimiento y su calidad de vida. Según estudios realizados en distintos campos laborales, un 70% del personal presenta un estrés
agudo en sus actividades personales y laborales (Estudio LATAM, 2020). Este grupo ves clave para el éxito de la plataforma, ya que son los principales beneficiarios de las capacidades que propone este startup

#### Segmento objetivo #2: Adultos entre 20 y 50 años de edad:

Este segmento incluye personas que no necesariamente sean trabajadores formales. A menudo, son las que más experimentan grados de estrés, ya que no se rigen a un horario de trabajo, sino que su trabajo está presente a todas horas del día. Según un estudio realizado a 250 trabajadores informales se expresa que el 56% de ellos muestran nivel medio de estrés, mientras que el 33.3% está en un nivel bajo y solo el 10.6% está en un nivel alto (Porcayo, 2022). Este grupo obtendrá los mismos beneficios que el otro segmento objetivo, pero este tiene más potencial de expandir el tema del estrés laboral y por consecuencia el uso de esta plataforma.

# 2. Capítulo II: Requirements Elicitation & Analysis

---

## 2.1 Competidores

En este apartado analizaremos las posibles competencias para nuestra página web,
viendo en ello sus descripciones y planes de negocios.

| Competidores | Características                                                                                                                                                                                                                                                                              | Diferencias                                                                                                                                                                                              | Limitaciones                                                                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Calm**     | - Contiene un ejercicio de respiración para reducir el estrés.<br>- Cursos de 10 minutos al día para reducir el estrés.<br>- Ejercicios físicos tipo meditaciones para relajar el cuerpo.<br>- Historias en audiolibro para dormir mejor.                                                    | - Enfoque multimedia de alta producción con audios narrados por celebridades y música profesional.<br>- Contenido especializado por necesidad (estrés, concentración, sueño).                            | - La mayoría del contenido requiere suscripción de pago.<br>- No tiene controles parentales para gestionar el uso infantil.                                           |
| **Wysa**     | - Chatbot de apoyo emocional impulsado por IA.<br>- Ejercicios como respiraciones guiadas, meditaciones y relajación muscular.<br>- Privacidad: no requiere nombre real y las conversaciones son anónimas.<br>- Versión de pago con acceso a terapeutas profesionales.                       | - Interfaz conversacional con IA (diferente a Calm con audio y Equoo con juegos).<br>- Incorpora técnicas de CBT y DBT guiadas.<br>- Modelo freemium claro (chatbot gratuito + coaching humano de pago). | - No puede atender emergencias de salud mental ni sustituir atención profesional.<br>- Limitaciones técnicas para comprender lenguaje complejo y matices emocionales. |
| **Equoo**    | - Usa Terapia Cognitiva Conductual y psicología positiva para enseñar habilidades emocionales.<br>- Juego con 52 niveles sobre neuroticismo, amabilidad y reciprocidad.<br>- Chatbot personalizado de apoyo.<br>- Estudios clínicos respaldan su eficacia para reducir ansiedad y depresión. | - Experiencia gamificada con misiones y recompensas.<br>- Orientación a jóvenes con narrativa adaptada.<br>- Progresión tipo “nivel” con estadísticas, ausente en Calm y Wysa.                           | - Variedad limitada de juegos emocionales, lo que puede volverse repetitivo.<br>- El enfoque gamificado puede no resonar con quienes prefieren métodos más directos.  |

### 2.1.1. Análisis competitivo

| Criterio                                          | Calm                                                                                                                                                                                                      | Wysa                                                                                                                                                                          | Equoo                                                                                                                             |
| :------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| **Perfil: Descripción**                           | Aplicación de bienestar mental para relajarse, dormir mejor y reducir el estrés. Ofrece meditaciones guiadas, historias para dormir, música relajante, ejercicios de respiración y clases de mindfulness. | Asistente de bienestar emocional basado en IA que ofrece terapia cognitivo-conductual (CBT), terapia dialéctica conductual (DBT), journaling y meditaciones, disponible 24/7. | Plataforma gamificada que desarrolla inteligencia emocional mediante juegos interactivos basados en psicología.                   |
| **Ventaja Competitiva**                           | Diversidad de maneras para relajarse; efectivo para cualquier necesidad.                                                                                                                                  | Combina un chatbot accesible 24/7 con técnicas terapéuticas validadas, y la opción de coaching humano para apoyo más profundo.                                                | Combina entretenimiento con técnicas psicológicas efectivas, aumentando la adherencia y el compromiso en el desarrollo emocional. |
| **Perfil de Marketing: Mercado Objetivo**         | Adultos entre 30 y 35 años con ingresos medio-altos que puedan pagar una suscripción.                                                                                                                     | Adultos jóvenes (18-35) y empresas que buscan herramientas de salud mental accesibles 24/7.                                                                                   | Adultos jóvenes (18-35), profesionales estresados, empresas e instituciones educativas.                                           |
| **Perfil de Marketing: Estrategias de marketing** | Modelo freemium, marketing con celebridades y alianzas con empresas.                                                                                                                                      | Marketing de contenidos, alianzas B2B y ASO con campañas en Instagram y LinkedIn.                                                                                             | Contenido educativo, partnerships B2B, campañas en redes sociales y pruebas gratuitas.                                            |
| **Perfil de Producto: Productos & Servicios**     | Meditaciones guiadas, historias para dormir, música relajante, ejercicios de respiración, clases de movimientos.                                                                                          | Chatbot gratuito con CBT/DBT y "pathways" temáticos; sesiones premium con coaches humanos.                                                                                    | App de entrenamiento emocional, versión empresarial y evaluaciones personalizadas.                                                |
| **Perfil de Producto: Precios & Costos**          | **Freemium**; plan mensual **15 USD**, anual **70 USD**, familiar **100 USD**, de por vida **400 USD**.                                                                                                   | **Freemium**; plan mensual **12 USD**, anual **19 USD**; tarifas corporativas variables.                                                                                      | **Freemium**; plan individual **$5-10/mes**, planes corporativos por volumen.                                                     |
| **Perfil de Producto: Canales de Distribución**   | App móvil (iOS/Android); plataforma web para empresas y coaching.                                                                                                                                         | App móvil (iOS/Android); plataforma web para empresas y coaching.                                                                                                             | Apps móviles (iOS/Android); plataforma web; integración con sistemas corporativos.                                                |
| **Análisis SWOT: Fortalezas**                     | Disponible 24/7, diversidad de opciones en la aplicación.                                                                                                                                                 | Disponible 24/7, técnicas terapéuticas validadas e interfaz intuitiva.                                                                                                        | Base científica sólida, formato atractivo, enfoque preventivo.                                                                    |
| **Análisis SWOT: Debilidades**                    | Precio elevado, no ofrece sesiones en vivo, enfoque principal para angloparlantes.                                                                                                                        | No reemplaza terapia presencial, contenido gratuito limitado, calidad dependiente de la IA.                                                                                   | Alta competencia, creación continua de contenido, percepción de ser una solución "ligera".                                        |
| **Análisis SWOT: Oportunidades**                  | Expansión internacional, integración con servicios de salud mental profesional.                                                                                                                           | Expansión en nuevos mercados, alianzas con telemedicina y wearables, localización cultural.                                                                                   | Creciente interés en salud mental, expansión internacional, integraciones tecnológicas.                                           |
| **Análisis SWOT: Amenazas**                       | Competencia intensa, precios más asequibles en otras apps.                                                                                                                                                | Competencia intensa, regulaciones de salud digital, preocupaciones por privacidad de datos.                                                                                   | Saturación del mercado, cambios en políticas de privacidad, escepticismo sobre la eficacia digital.                               |

## 2.1.2. Estrategias y tácticas frente a competidores

**FODA de nuestra empresa: "MinDora"**

F: Sistema de detección rápida de estrés laboral con test personalizados y conexión directa a
profesionales de salud mental.

O: Creciente conciencia sobre salud mental en empresas y mayor disposición a invertir en bienestar
laboral.

D: Posible resistencia de los usuarios a reconocer problemas de estrés y dependencia de la honestidad
en las respuestas al test.

A: Aparición de soluciones similares en el mercado y preocupaciones sobre confidencialidad de datos
sensibles de salud mental.

Para aprovechar las fortalezas y oportunidades de "MinDora", y al mismo tiempo enfrentar las
debilidades y contrarrestar las amenazas del entorno competitivo, podemos considerar las siguientes
estrategias y tácticas:

● Desarrollar programas de implementación corporativa que incluyan talleres de sensibilización
sobre la importancia de la salud mental.

● Establecer alianzas con empresas de seguros médicos para ofrecer descuentos a
organizaciones que implementen nuestro sistema preventivo.

● Implementar tecnología de análisis de comportamiento que complemente las respuestas
subjetivas del test con indicadores objetivos.

● Crear un sólido programa de certificación en privacidad de datos y comunicarlo claramente a
usuarios y empresas clientes.

● Generar reportes anónimos agregados para departamentos de RR.HH. que muestren el ROI en
términos de reducción de ausentismo y mejora de productividad.

## 2.2. Entrevistas.

---

## 2.2.1. Diseño de entrevistas.

**Segmento: Personas activas en el ámbito laboral con jornadas extendidas**

Para evaluar las necesidades y experiencias de profesionales con horarios laborales extensos que
enfrentan altos niveles de estrés, hemos desarrollado una serie de preguntas enfocadas en comprender
su rutina diaria, factores estresantes, y estrategias actuales para manejar la presión laboral. Esta
información nos permitirá identificar oportunidades para que nuestra plataforma ofrezca soluciones
efectivas que mejoren su calidad de vida y rendimiento profesional.

Introducción:

Buenos días/tardes, soy [...], representante de [Nombre del Proyecto]. Estamos
desarrollando una plataforma destinada a ayudar a profesionales con horarios laborales extensos a
manejar mejor el estrés y mejorar su calidad de vida. Nos gustaría conocer más sobre tu experiencia
laboral y los desafíos que enfrentas en tu día a día. Tu perspectiva será muy valiosa para desarrollar
una solución que realmente responda a las necesidades de personas como tú.

Preguntas:

1. Para comenzar, ¿podrías presentarte y contarnos brevemente sobre tu profesión y el sector en
   el que trabajas?
2. ¿Cómo describirías una jornada laboral típica para ti? ¿Cuántas horas trabajas habitualmente?
3. ¿Qué aspectos de tu trabajo consideras que generan mayor presión o estrés?
4. ¿Has notado cambios en tu salud física o mental que atribuyas al estrés laboral?
5. ¿Cómo suele afectar el estrés laboral a tu rendimiento en el trabajo y a tu vida personal?
6. ¿Qué estrategias utilizas actualmente para manejar el estrés relacionado con tu trabajo?
7. ¿Tu empresa o lugar de trabajo ofrece algún programa o recurso para ayudar a los empleados
   a manejar el estrés?
8. En los momentos de mayor presión laboral, ¿qué tipo de apoyo o herramientas te resultarían
   más útiles?
9. ¿Utilizas actualmente alguna aplicación o plataforma digital para gestionar el estrés o mejorar
   tu bienestar? Si es así, ¿cuál y qué te parece?
10. ¿Qué características o funcionalidades consideras importantes en una plataforma diseñada
    para ayudar a reducir el estrés laboral?

**Segmento: Adultos entre 20 y 50 años con trabajo informal o sin horarios definidos**

Para evaluar las necesidades y experiencias de adultos que trabajan en el sector informal o con
horarios no definidos, hemos desarrollado preguntas orientadas a comprender cómo manejan sus
tiempos, los factores estresantes específicos de su situación laboral y sus mecanismos actuales para
gestionar el estrés. Esta información nos permitirá adaptar nuestra plataforma para ofrecer soluciones
que respondan a las características particulares de este segmento, que según estudios, experimenta
niveles variables de estrés debido a la naturaleza omnipresente de su trabajo.

Introducción:

Buenos días/tardes, soy [...], representante de MinDora. Estamos desarrollando una
plataforma para ayudar a personas que trabajan sin horarios fijos o en el sector informal a manejar
mejor el estrés y mejorar su calidad de vida. Nos interesa conocer tu experiencia para crear una
solución que realmente funcione para personas como tú. Agradecemos mucho tu tiempo y sinceridad
en esta conversación.

Preguntas:

1. Para empezar, ¿podrías contarnos a qué te dedicas y cómo es tu rutina de trabajo habitual?
2. ¿Cómo organizas tu tiempo entre el trabajo y otras actividades? ¿Tienes algún método para
   establecer límites?
3. ¿Sientes que tu trabajo "te sigue a todas partes"? ¿Puedes describir cómo es esa experiencia?
4. ¿Cuáles son los principales factores que te generan estrés en tu trabajo?
5. ¿Cómo describirías el nivel de estrés que experimentas habitualmente (bajo, medio, alto)?
   ¿Varía mucho dependiendo de las temporadas o circunstancias?
6. ¿De qué manera crees que el no tener un horario fijo afecta tu nivel de estrés, en comparación
   con trabajos formales con horarios establecidos?
7. ¿Has notado algún impacto en tu salud física o mental debido al estrés relacionado con tu
   trabajo?
8. ¿Qué estrategias o métodos utilizas actualmente para manejar el estrés cuando sientes que el
   trabajo invade todos los aspectos de tu vida?
9. ¿Utilizas alguna aplicación, plataforma o recurso digital para ayudarte a organizar tu trabajo o
   manejar el estrés? ¿Cuál ha sido tu experiencia?
10. ¿Qué momentos del día considerarías más apropiados para dedicar tiempo a actividades para
    reducir el estrés?

## 2.2.2. Registro de entrevistas

**Segmento 1: Personas activas en el ámbito laboral con jornadas extendidas**

Entrevista N°1

● Nombre: Xin Yu Shi Lin

● Sexo: Masculino

● Edad: 25

● Estado Civil: Soltero

● Labor: Mesero

Detalles de la entrevista:
Xin Yu Shi Lin es un joven de 25 años que vive en Lima, Perú, junto a su familia. Está soltero y ha sido diagnosticado con epilepsia desde hace varios años. A lo largo de su experiencia, ha recibido tratamiento médico y consultas con neurólogos, aunque no de forma continua ni digitalizada. Normalmente depende de apuntes en papeles o de su memoria para registrar información sobre sus crisis, lo que considera un método poco confiable. Además, conoce y valora la existencia de grupos de apoyo, como la Asociación Peruana de Epilepsia, donde los pacientes comparten experiencias y reciben información útil.
Su rutina laboral está marcada por su empleo como mesero en un restaurante chifa, un trabajo físicamente exigente que requiere muchas horas de pie y trato directo con clientes. Una de sus mayores preocupaciones es sufrir una crisis en el trabajo y no poder avisar a nadie, lo cual también repercute en su familia, que vive con la angustia constante de que pueda ocurrirle algo en cualquier momento.
En cuanto al control de su enfermedad, Xin Yu Shi enfrenta dificultades para recordar datos importantes de cada crisis, como la hora de inicio, la duración o los síntomas específicos. Aunque intenta anotarlos, con frecuencia pierde la información, lo que impide tener un historial confiable que pueda compartir con sus médicos. Por eso considera que contar con un sistema que envíe alertas tempranas sería de gran ayuda, ya que le otorgaría mayor seguridad personal y permitiría que su familia o compañeros pudieran reaccionar de inmediato.
Respecto a sus competencias digitales, describe su nivel como básico en el uso de smartphones y medio en el manejo de laptops, aunque se desenvuelve con facilidad en aplicaciones de mensajería como WhatsApp y SMS. Generalmente se autentica en plataformas mediante su correo Gmail, mensajes SMS y WhatsApp. Su dispositivo principal es un celular Android, y también utiliza una laptop con Windows para actividades simples como navegar en internet o revisar correos electrónicos.
Cuando piensa en una aplicación que pueda apoyarlo en el manejo de su enfermedad, le gustaría que incluyera un registro digital sencillo y confiable de sus crisis, con información sobre fechas, duración y síntomas. También considera importante disponer de gráficos que reflejen su evolución y recordatorios de medicación que le ayuden a mantener la constancia en el tratamiento.
Está abierto al uso de dispositivos IoT como relojes inteligentes o sensores que puedan registrar información sobre su salud y compartirla con su médico. Ha escuchado sobre dispositivos como el Fitbit Ionic y cree que podrían ser útiles para mejorar el seguimiento de su condición. Sin embargo, expresa dos preocupaciones centrales: la posibilidad de que los dispositivos fallen en un momento crítico y la necesidad de que sus datos personales estén protegidos. Para él, la confianza y la seguridad son requisitos indispensables en cualquier tecnología que decida utilizar.

● Duración: 4 minutos con 23 segundos

[● Link: https://drive.google.com/file/d/1ZJEtWCAmNASaxGq7_rgHlA0-Sl0VK9p4/view?usp=sharing](https://drive.google.com/file/d/1ZJEtWCAmNASaxGq7_rgHlA0-Sl0VK9p4/view?usp=sharing)

Resumen de los puntos clave en la entrevista:
- El entrevistado se llama Xin Yu Shi Lin, tiene 25 años, vive en Lima con su familia y está diagnosticado con epilepsia desde hace varios años.
- Ha recibido tratamiento médico y consultas con neurólogos, aunque de manera intermitente y sin un registro digital confiable; suele depender de apuntes en papeles y conoce grupos de apoyo como la Asociación Peruana de Epilepsia.
- Trabaja como mesero en un chifa, lo que le genera preocupación por sufrir una crisis en el trabajo sin poder avisar a nadie, mientras su familia vive con la constante inquietud de que algo le ocurra.
- Sus principales dificultades para llevar un control de la enfermedad son recordar la hora, duración y síntomas de las crisis, ya que pierde la información fácilmente y carece de un historial confiable.
- Considera que un sistema de alertas tempranas sobre crisis sería muy útil, ya que le daría mayor seguridad y permitiría a su familia o compañeros actuar de inmediato.
- Su habilidad tecnológica es básica en smartphones y media en laptops, aunque maneja con soltura aplicaciones de mensajería como WhatsApp y SMS; suele autenticarse con correo Gmail, SMS y WhatsApp.
- Le gustaría contar con una aplicación que registre de manera simple y confiable sus crisis, incluya un historial digital con fechas, duración y síntomas, gráficos para seguir su evolución y recordatorios de medicación.
- Está dispuesto a usar dispositivos IoT como relojes inteligentes o sensores que registren datos y los compartan con su médico, y considera que eso le daría mayor tranquilidad.
- Sus principales preocupaciones respecto a esta tecnología son la posibilidad de fallas en momentos críticos y la falta de protección de sus datos personales, por lo que necesita que sea confiable y segura.

Entrevista N°2

● Nombre: Andrés Luján Carrión

● Sexo: Masculino

● Edad: 40

● Estado Civil: Soltero

● Labor: Rector(USL)

Detalles de la entrevista:
Andrés Luján Carrión tiene 40 años, es soltero y se desempeña como rector de la Universidad San Lorenzo. Su rutina laboral está marcada por una fuerte exigencia, ya que dedica entre diez y doce horas diarias a su trabajo. La mayor parte de ese tiempo lo invierte en reuniones, coordinación de equipos y toma de decisiones estratégicas para la institución. Esta carga de responsabilidad y extensión horaria le deja poco espacio para su vida personal.
En cuanto a la organización de su tiempo, Andrés comenta que intenta priorizar las tareas más urgentes, aunque reconoce que no cuenta con un método fijo para establecer límites claros entre lo laboral y lo personal. Esta dificultad provoca que el trabajo termine imponiéndose sobre otros aspectos de su vida. Incluso fuera de la oficina, se mantiene constantemente conectado al celular, respondiendo mensajes y pensando en asuntos pendientes, lo que le impide desconectarse realmente.
La principal fuente de estrés para él es la presión de obtener resultados inmediatos. Como rector, debe impulsar cambios académicos e institucionales que requieren tiempo para implementarse y consolidarse, pero las expectativas de ver avances rápidos generan un nivel de tensión constante. Según relata, su nivel de estrés es alto y sostenido en el tiempo, pues no depende de la temporada sino de la magnitud de sus responsabilidades.
La ausencia de un horario fijo contribuye a incrementar esta carga. A diferencia de otros trabajos en los que la jornada concluye al salir de la oficina, en su caso siempre hay algo pendiente, lo que refuerza la sensación de que nunca puede desconectarse completamente.
Este ritmo ha tenido un impacto significativo en su salud, ya que ha experimentado síntomas como fatiga mental, insomnio y tensión muscular, todos asociados al nivel constante de estrés. En un intento por manejarlo, Andrés recurre a pequeñas pausas, intenta desconectarse en ciertos momentos y conversa con personas de confianza. Sin embargo, reconoce que estas estrategias resultan insuficientes y que necesita métodos más efectivos para cuidar su bienestar.
Respecto al uso de tecnología, actualmente no utiliza aplicaciones específicas para el manejo del estrés, aunque considera que sería muy útil contar con plataformas digitales o coaching personalizado que le ofrezcan herramientas prácticas. En este sentido, identifica que los momentos más adecuados para actividades de autocuidado serían en la mañana, antes de iniciar su jornada, y al final del día, cuando puede reservar tiempo para sí mismo.
Finalmente, expresa lo que le gustaría encontrar en una aplicación enfocada en manejo del estrés: un servicio de coaching emocional, un sistema que le permita llevar un seguimiento de sus niveles de estrés y una comunidad de apoyo para compartir experiencias con otras personas en situaciones similares. Para él, estas características serían clave para mejorar su calidad de vida y encontrar un equilibrio más saludable entre su exigente rol profesional y su bienestar personal.

● Duración: 3 minutos con 34 segundos

[● Link: https://drive.google.com/file/d/1eKdY2-Hij9APvgmxEu2_W3FjyVKDvfZC/view ](https://drive.google.com/file/d/1eKdY2-Hij9APvgmxEu2_W3FjyVKDvfZC/view)

Resumen de los puntos clave en la entrevista:
- El entrevistado trabaja entre diez y doce horas diarias, principalmente en reuniones, coordinación de equipos y toma de decisiones.
- Tiene dificultades para equilibrar su vida personal y laboral, ya que el trabajo lo acompaña incluso fuera de la oficina mediante llamadas, mensajes y pendientes constantes.
- La principal fuente de estrés es la presión por obtener resultados inmediatos frente a procesos académicos e institucionales que requieren más tiempo para consolidarse.
- La falta de un horario fijo incrementa la sensación de no poder desconectarse y eleva aún más su nivel de estrés.
- Ha experimentado consecuencias físicas y mentales derivadas del estrés, como fatiga mental, insomnio y tensión muscular de manera recurrente.
- Reconoce que sus estrategias actuales, como tomar pausas breves o conversar con personas de confianza, no son suficientes y necesita métodos más efectivos.
- Considera que herramientas digitales podrían ser de gran ayuda, especialmente aquellas que ofrezcan coaching personalizado para el manejo del estrés.
- Identifica la mañana, antes de iniciar la jornada, y la noche, al finalizar el día, como los momentos más adecuados para realizar actividades de autocuidado y relajación.
- Le gustaría que una aplicación incluyera coaching emocional, un sistema de monitoreo de sus niveles de estrés y una comunidad de apoyo donde compartir experiencias con otras personas.

**Segmento 2: Adultos entre 20 y 50 años con trabajo informal o sin horarios definidos**

Entrevista N°3

● Nombre: 

● Sexo: 

● Edad: 

● Estado Civil: 

● Labor: 

Detalles de la entrevista:

● Duración: 

[● Link: ]()

Resumen de los puntos clave en la entrevista:



Entrevista N°4

● Nombre: Laura Méndez

● Sexo: Mujer

● Edad: 24 años

● Estado Civil: Soltera

● Labor: Freelancer diseñadora gráfica y fotógrafa de eventos

Detalles de la entrevista:

● Duración: 8 minutos con 39 segundos

[● Link: ]()

Resumen de los puntos clave en la entrevista:

La entrevista con Laura Méndez, una diseñadora gráfica freelance y fotógrafa de 24 años,
revela los desafíos únicos que enfrenta como trabajadora con horarios irregulares. Su
situación laboral se caracteriza por la ausencia de límites entre vida personal y profesional,
con un teléfono que funciona como "oficina móvil" y clientes que esperan disponibilidad
constante. Los principales factores de estrés identificados incluyen la inestabilidad económica
que la lleva a sobrecargarse de trabajo, las expectativas poco realistas de los clientes, y la
imposibilidad de desconectar completamente, resultando en un nivel de estrés medio-alto con
picos que afectan su salud física y creatividad. Aunque intenta implementar estrategias como
yoga o ejercicio, estas prácticas son inconsistentes debido a su carga laboral, por lo que
necesita soluciones flexibles que se adapten a su ritmo caótico: herramientas rápidas
accesibles desde el móvil, técnicas para establecer límites sin perder clientes y métodos
efectivos para "apagar" su mente al finalizar la jornada.

## 2.2.3. Análisis de entrevistas

**Segmento 1: Personas activas en el ámbito laboral con jornadas extendidas**

Hallazgos:

● Los profesionales experimentan jornadas laborales extendidas de 10-12 horas diarias,
sin límites claros entre vida laboral y personal.

● Enfrentan presión constante por resultados inmediatos ante cambios que requieren
tiempo.

● Presentan síntomas físicos y emocionales similares: fatiga mental, insomnio, tensión
muscular, irritabilidad y dolores de cabeza.

● Las empresas ofrecen poco o nulo apoyo real para el manejo del estrés laboral.

● Aunque intentan implementar técnicas de manejo del estrés, la carga laboral impide
ser constantes.

● Valoran soluciones digitales accesibles, rápidas y adaptables a sus horarios saturados.

Conclusión:

Los profesionales con jornadas extendidas constituyen un segmento vulnerable al estrés
crónico debido a la combinación de largas horas de trabajo, disponibilidad permanente y
presión por resultados inmediatos. Sus intentos individuales de manejar el estrés mediante
técnicas convencionales resultan insuficientes ante la falta de límites laborales claros y apoyo
institucional. Este grupo necesita soluciones tecnológicas personalizadas que se integren
fácilmente a su rutina, ofrezcan intervenciones breves pero efectivas, y proporcionen tanto
seguimiento automatizado como acceso a apoyo profesional cuando sea necesario. La
aplicación debe enfocarse en crear micro hábitos de bienestar que puedan sostenerse incluso
en entornos laborales exigentes, permitiéndoles recuperar el equilibrio sin comprometer su
desempeño profesional.

**Segmento 2: Adultos entre 20 y 50 años con trabajo informal o sin horarios definidos**

Hallazgos:

● Ausencia de límites trabajo-vida personal: Ambos experimentan una fusión entre su
vida laboral y personal, con el teléfono móvil como vínculo constante al trabajo.

● Horarios irregulares: Ninguno tiene un horario fijo, organizándose según demanda y
necesidades económicas.

● Principales factores de estrés: Comparten preocupaciones por la inestabilidad
económica, las expectativas de disponibilidad constante y la dificultad para
desconectar.

● Impacto en la salud: Ambos reportan efectos negativos como dolores físicos,
cansancio e irritabilidad.

● Estrategias de afrontamiento inconsistentes: Aunque intentan aplicar métodos para
manejar el estrés (música, ejercicio, yoga), no logran mantenerlos de forma regular.

● Necesidad de herramientas adaptables: Los dos expresan interés en explorar
soluciones que se ajusten a sus horarios variables.

Conclusión:

Los testimonios de --- y Laura revelan una realidad laboral cada vez más común:
trabajadores con horarios flexibles que enfrentan una constante disponibilidad laboral
mediada por dispositivos móviles, generando una difuminación de límites entre trabajo y vida
personal que impacta negativamente su bienestar. Esta situación crea un ciclo donde la
inestabilidad económica los impulsa a aceptar más trabajo, intensificando el estrés y
deteriorando su salud física y mental. Sus casos evidencian la necesidad urgente de
desarrollar herramientas y estrategias específicamente diseñadas para trabajadores con
horarios irregulares, que sean accesibles desde dispositivos móviles, requieran poco tiempo
de implementación y ayuden efectivamente a establecer límites saludables sin comprometer
su sustento económico.

## 2.3. Needfinding

Al recopilar toda la información de los segmentos objetivo y realizar las entrevistas se hará
un análisis de estos mismos haciendo uso de User Persona, Task Matrix, Journey Mapping,
Empathy Mapping y As-Is Scenario Mapping.

### 2.3.1. User Personas.

<div>
  <p align="center"><img src="assets/md-images/user laura.png" alt="User persona for Laura" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/user andres.png" alt="User persona for Andres" width="700px" /></p>
</div>


### 2.3.2. User Task Matrix.

| Tareas                                                     | Laura Méndez |             | Andrés Luján |             |
| :--------------------------------------------------------- | :----------- | :---------- | :----------- | :---------- |
|                                                            | Frecuencia   | Importancia | Frecuencia   | Importancia |
| **Registrar señales corporales de estrés**                 | Media        | Media       | Alta         | Alta        |
| **Completar autoevaluación de niveles de estrés**          | Media        | Alta        | Alta         | Media       |
| **Consultar análisis de patrones de estrés**               | Alta         | Media       | Media        | Alta        |
| **Acceder a recomendaciones personalizadas**               | Media        | Alta        | Alta         | Alta        |
| **Registrar seguimiento de implementación de estrategias** | Media        | Alta        | Alta         | Alta        |

### 2.3.3. User Journey Mapping.

<div>
  <p align="center"><img src="assets/md-images/Journey-1.png" alt="Journey mapping part 1" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/Journey-2.png" alt="Journey mapping part 2" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/Journey-3.png" alt="Journey mapping part 3" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/Journey-4.png" alt="Journey mapping part 4" width="700px" /></p>
</div>

### 2.3.4. Empathy Mapping.

<div>
  <p align="center"><img src="assets/md-images/Empathy-1.png" alt="Empathy mapping part 1" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/Empathy-2.png" alt="Empathy mapping part 2" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/Empathy-3.png" alt="Empathy mapping part 3" width="700px" /></p>
</div>

<div>
  <p align="center"><img src="assets/md-images/Empathy-4.png" alt="Empathy mapping part 4" width="700px" /></p>
</div>

### 2.3.5. As-is Scenario Mapping.

**As-is Scenario Mapping de Laura Méndez**

| Phases       | Registrar señales corporales de estrés                | Completar autoevaluación de niveles de estrés   | Consultar análisis de patrones de estrés            | Acceder a recomendaciones personalizadas                         | Registrar seguimiento de implementación de estrategias                |
| :----------- | :---------------------------------------------------- | :---------------------------------------------- | :-------------------------------------------------- | :--------------------------------------------------------------- | :-------------------------------------------------------------------- |
| **Doing**    | Toma fotos de su postura durante horas de trabajo.    | Completa cuestionarios rápidos entre proyectos. | Revisa los gráficos semanales de estrés.            | Accede a recomendaciones desde su teléfono móvil.                | Registra la efectividad de las técnicas implementadas.                |
| **Thinking** | Duda si está estresada o solo cansada.                | Evalúa si está aceptando demasiados proyectos.  | Busca patrones relacionados con ciertos clientes.   | Cuestiona si las recomendaciones se adaptan a su estilo de vida. | Se pregunta si está siendo constante con las técnicas.                |
| **Feeling**  | Se siente abrumada al notar signos físicos de estrés. | Siente alivio al cuantificar su estrés.         | Muestra curiosidad al descubrir patrones de estrés. | Experimenta esperanza al recibir nuevas estrategias.             | Siente orgullo cuando logra implementar estrategias consistentemente. |

**As-is Scenario Mapping de Andrés Luján**

| Phases       | Registrar señales corporales de estrés                          | Completar autoevaluación de niveles de estrés                            | Consultar análisis de patrones de estrés                                | Acceder a recomendaciones personalizadas                                   | Registrar seguimiento de implementación de estrategias                   |
| :----------- | :-------------------------------------------------------------- | :----------------------------------------------------------------------- | :---------------------------------------------------------------------- | :------------------------------------------------------------------------- | :----------------------------------------------------------------------- |
| **Doing**    | Documenta su tensión muscular después de reuniones prolongadas. | Realiza evaluaciones al final de su jornada laboral.                     | Analiza tendencias de estrés durante diferentes períodos académicos.    | Revisa el coaching emocional personalizado entre reuniones.                | Registra diariamente la efectividad de las estrategias implementadas.    |
| **Thinking** | Se pregunta si su fatiga es visible para su equipo.             | Considera cómo los cambios institucionales afectan su nivel de estrés.   | Reflexiona sobre la relación entre sus horas de trabajo y su bienestar. | Evalúa qué recomendaciones son viables con su apretada agenda.             | Analiza qué técnicas funcionan mejor durante temporadas de alta presión. |
| **Feeling**  | Se siente frustrado al reconocer signos físicos de agotamiento. | Experimenta preocupación al constatar altos niveles de estrés sostenido. | Siente determinación al identificar patrones problemáticos.             | Muestra optimismo al encontrar soluciones adaptadas a su rol de liderazgo. | Siente satisfacción cuando logra incorporar nuevos hábitos a su rutina.  |

## 2.4. Ubiquitous Language.

Este glosario define los términos clave que usamos en el proyecto para mantener un lenguaje común entre el equipo de desarrollo y los expertos en salud mental.

| Término                            | Definición                                                                                                                     |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Usuario**                        | Persona adulta (20–50 años) que utiliza la app para evaluar, monitorear y gestionar su estrés laboral.                         |
| **Perfil biométrico**              | Conjunto de datos físicos iniciales del usuario (postura, rostro, respiración) que sirven como línea base.                     |
| **Test de autoevaluación**         | Cuestionario digital que mide síntomas y sensaciones de estrés percibidas por el usuario.                                      |
| **Análisis biométrico**            | Proceso de escaneo mediante la cámara/sensores para detectar señales físicas de estrés.                                        |
| **Síntomas físicos**               | Manifestaciones registradas por el usuario, como dolores de cabeza, insomnio, tensión muscular.                                |
| **Nivel de estrés**                | Clasificación automática (bajo, medio, alto) que combina datos de tests y biometría.                                           |
| **Recomendaciones personalizadas** | Consejos, ejercicios o pausas sugeridas por la app en base al estado actual del usuario.                                       |
| **Ejercicios de respiración**      | Actividad guiada por la app para reducir la tensión y ansiedad en pocos minutos.                                               |
| **Pausas activas**                 | Recordatorios programados que invitan al usuario a descansar o hacer micro ejercicios durante la jornada laboral.              |
| **Dashboard personal**             | Panel con estadísticas, tendencias y patrones de estrés en el tiempo.                                                          |
| **Desencadenante de estrés**       | Evento o situación registrada por el usuario que provoca incremento de su estrés (ej. exceso de trabajo, conflictos, tráfico). |
| **Informe de progreso**            | Documento generado con evolución de estrés y hábitos del usuario, que puede compartirse con un psicólogo.                      |
| **Especialista en salud mental**   | Psicólogo disponible en la plataforma para consultas y tratamiento profesional.                                                |
| **Cita**                           | Agendamiento de una sesión con un especialista, virtual o presencial.                                                          |
| **Grupo de apoyo**                 | Comunidad virtual de usuarios que comparten experiencias y consejos sobre el manejo del estrés.                                |
| **Biblioteca de recursos**         | Colección digital de artículos, videos o guías relacionadas al bienestar laboral y manejo del estrés.                          |

# Capítulo III: Requirements Specification

---

## 3.1. To-Be Scenario Mapping

**User Journey Mapping – Laura Méndez**

| Fases                                         | Doing                                                    | Thinking                                                                | Feeling                                             |
| --------------------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------- |
| Registrar señales corporales de estrés        | La app detecta automáticamente postura y signos faciales | “Es útil que el sistema registre señales sin que yo tenga que hacerlo.” | Tranquilidad por el monitoreo pasivo                |
| Completar autoevaluación de niveles de estrés | Recibe notificaciones de autoevaluación guiada con IA    | “Ahora sé si lo que siento es estrés o solo cansancio.”                 | Alivio por entender rápidamente su estado emocional |
| Consultar análisis de patrones de estrés      | Visualiza resúmenes visuales con predicción de picos     | “Ya puedo ver cómo ciertos clientes o días afectan mi bienestar.”       | Curiosidad y sensación de control                   |
| Acceder a recomendaciones personalizadas      | Recibe sugerencias integradas a su rutina diaria         | “Esto se adapta a mí y no interrumpe mi día.”                           | Esperanza al ver opciones viables                   |
| Registrar seguimiento de estrategias          | Ve sus avances con ayuda de recordatorios motivacionales | “Estoy logrando mantener el hábito, y se nota en mi bienestar.”         | Orgullo y motivación al ver progresos               |

**User Journey Mapping – Andrés Luján**

| Fases                                         | Doing                                                  | Thinking                                                   | Feeling                                      |
| --------------------------------------------- | ------------------------------------------------------ | ---------------------------------------------------------- | -------------------------------------------- |
| Registrar señales corporales de estrés        | El sistema registra tensión y postura automáticamente  | “El sistema me ayuda a notar lo que mi cuerpo expresa.”    | Alivio al no depender solo de su percepción  |
| Completar autoevaluación de niveles de estrés | Usa voz o toques rápidos para autoevaluarse            | “Esta evaluación se adapta a mis tiempos.”                 | Comodidad y sensación de autonomía           |
| Consultar análisis de patrones de estrés      | El sistema anticipa picos de estrés según su agenda    | “Puedo prever cuándo debo cuidarme más o delegar.”         | Seguridad al planificar estratégicamente     |
| Acceder a recomendaciones personalizadas      | Recibe recomendaciones justo después de momentos clave | “Estas estrategias están hechas para mi rol de liderazgo.” | Optimismo por la personalización del sistema |
| Registrar seguimiento de estrategias          | Revisa un resumen mensual con IA                       | “Sé qué funcionó y qué debo ajustar para el próximo mes.”  | Satisfacción por tener una guía continua     |

---

## 3.2. User Stories

**Epic**

| **EPIC ID** | **Nombre del Epic**                        | **Descripción**                                                                                                                                                                                                  |
| ----------- | ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01        | Registro y Configuración de Cuenta         | Como usuario nuevo, quiero registrarme, configurar mi perfil biométrico y completar un cuestionario inicial de salud, para acceder a la plataforma con un perfil personalizado y preciso.                        |
| EP02        | Detección y Evaluación del Estrés          | Como usuario, quiero evaluar mi nivel de estrés mediante autoevaluaciones, análisis biométricos y registro de síntomas, para obtener un diagnóstico completo de mi estado actual.                                |
| EP03        | Recomendaciones y Gestión del Estrés       | Como usuario diagnosticado con estrés, quiero recibir recomendaciones personalizadas, acceder a ejercicios de respiración y programar pausas activas, para reducir mis niveles de estrés y mejorar mi bienestar. |
| EP04        | Seguimiento y Análisis del Progreso        | Como usuario, quiero visualizar un dashboard personal, generar informes de progreso y registrar desencadenantes de estrés, para dar seguimiento a mi evolución y entender mis patrones de estrés.                |
| EP05        | Conexión con Especialistas en Salud Mental | Como usuario con necesidad de apoyo profesional, quiero buscar psicólogos, agendar citas y compartir informes, para recibir tratamiento especializado dentro de la plataforma.                                   |
| EP06        | Comunidad y Soporte Social                 | Como usuario, quiero participar en grupos de apoyo, acceder a una biblioteca de recursos y unirme a desafíos antiestrés, para sentir acompañamiento social y mantener la motivación en la gestión de mi estrés.  |
| EP07        | Integración con Entorno Laboral            | Como trabajador, quiero analizar mi carga laboral y recibir recordatorios de ergonomía, para prevenir sobrecarga y mejorar mi productividad sin comprometer mi bienestar.                                        |

**EP01 - Registro y Configuración de Cuenta**

| User Story ID | Título                                  |
| ------------: | --------------------------------------- |
|          US01 | Registrar cuenta de usuario             |
|          US02 | Configurar perfil biométrico            |
|          US03 | Completar cuestionario inicial de salud |

**EP02 - Detección y Evaluación del Estrés**

| User Story ID | Título                                    |
| ------------: | ----------------------------------------- |
|          US04 | Realizar test de autoevaluación de estrés |
|          US05 | Análisis biométrico de señales de estrés  |
|          US06 | Registro de síntomas físicos              |

**EP03 - Recomendaciones y Gestión del Estrés**

| User Story ID | Título                                     |
| ------------: | ------------------------------------------ |
|          US07 | Recibir recomendaciones personalizadas     |
|          US08 | Realizar ejercicios de respiración guiados |
|          US09 | Programar pausas activas laborales         |

**EP04 - Seguimiento y Análisis del Progreso**

| User Story ID | Título                                  |
| ------------: | --------------------------------------- |
|          US10 | Visualizar dashboard personal de estrés |
|          US11 | Generar informes de progreso            |
|          US12 | Registrar desencadenantes de estrés     |

**EP05 - Conexión con Especialistas en Salud Mental**

| User Story ID | Título                               |
| ------------: | ------------------------------------ |
|          US13 | Buscar psicólogos especializados     |
|          US14 | Agendar cita con psicólogo           |
|          US15 | Compartir informes con especialistas |

**EP06 - Comunidad y Soporte Social**

| User Story ID | Título                            |
| ------------: | --------------------------------- |
|          US16 | Participar en grupos de apoyo     |
|          US17 | Acceder a biblioteca de recursos  |
|          US18 | Participar en desafíos antiestrés |

**EP07 - Integración con Entorno Laboral**

| User Story ID | Título                             |
| ------------: | ---------------------------------- |
|          US19 | Analizar carga laboral             |
|          US20 | Recibir recordatorios de ergonomía |

| ID Épica | Épica                              | ID HU | Título HU                               | Descripción HU                                                                                                                     | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                            |
| -------- | ---------------------------------- | ----- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01     | Registro y Configuración de Cuenta | US01  | Registrar cuenta de usuario             | Como nuevo usuario, quiero registrar una cuenta con mi correo o número de teléfono, para acceder a las funciones de la aplicación. | **Escenario 1: Registro exitoso**<br>Dado que el usuario no tiene cuenta,<br>Cuando ingresa sus datos obligatorios y acepta términos,<br>Entonces el sistema crea la cuenta y envía verificación.<br><br>**Escenario 2: Registro fallido**<br>Dado que el usuario ingresa datos inválidos,<br>Cuando intenta registrarse,<br>Entonces el sistema muestra mensaje de error y no crea cuenta.        |
| EP01     | Registro y Configuración de Cuenta | US02  | Configurar perfil biométrico            | Como usuario, quiero registrar mis datos biométricos para personalizar el análisis de estrés.                                      | **Escenario 1: Configuración inicial**<br>Dado que el usuario tiene cuenta activa,<br>Cuando registra o sincroniza datos biométricos,<br>Entonces el sistema los guarda y usa en futuros análisis.<br><br>**Escenario 2: Error de sincronización**<br>Dado que el usuario conecta un dispositivo,<br>Cuando ocurre un error,<br>Entonces el sistema muestra advertencia y permite reintentar.      |
| EP01     | Registro y Configuración de Cuenta | US03  | Completar cuestionario inicial de salud | Como usuario nuevo, quiero completar un cuestionario de salud para generar mi plan inicial.                                        | **Escenario 1: Cuestionario completado**<br>Dado que el usuario accede al cuestionario inicial,<br>Cuando responde todas las preguntas,<br>Entonces el sistema guarda respuestas y genera perfil.<br><br>**Escenario 2: Cuestionario incompleto**<br>Dado que el usuario abandona el cuestionario,<br>Cuando vuelve a ingresar,<br>Entonces el sistema permite retomar desde el progreso guardado. |

| ID Épica | Épica                             | ID HU | Título HU                                 | Descripción HU                                                                                      | Criterios de Aceptación                                                                                                                                                                                                                                                                                                             |
| -------- | --------------------------------- | ----- | ----------------------------------------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP02     | Detección y Evaluación del Estrés | US04  | Realizar test de autoevaluación de estrés | Como usuario, quiero realizar un test de estrés para conocer mi nivel actual.                       | **Escenario 1: Test completado**<br>Dado que el usuario accede al test,<br>Cuando responde todas las preguntas,<br>Entonces el sistema muestra resultado inmediato.<br><br>**Escenario 2: Test incompleto**<br>Dado que el usuario abandona el test,<br>Cuando regresa,<br>Entonces el sistema guarda progreso y permite retomarlo. |
| EP02     | Detección y Evaluación del Estrés | US05  | Análisis biométrico de señales de estrés  | Como usuario, quiero que la app analice mis datos biométricos para detectar estrés automáticamente. | **Escenario 1: Análisis exitoso**<br>Dado que el usuario sincronizó su dispositivo,<br>Cuando los datos se reciben,<br>Entonces el sistema calcula nivel de estrés.<br><br>**Escenario 2: Datos insuficientes**<br>Dado que faltan datos,<br>Cuando se intenta analizar,<br>Entonces el sistema notifica al usuario.                |
| EP02     | Detección y Evaluación del Estrés | US06  | Registro de síntomas físicos              | Como usuario, quiero registrar manualmente mis síntomas físicos para complementar el análisis.      | **Escenario 1: Registro exitoso**<br>Dado que el usuario accede a “Síntomas”,<br>Cuando ingresa información,<br>Entonces el sistema guarda los datos.<br><br>**Escenario 2: Validación**<br>Dado que el usuario omite un campo obligatorio,<br>Cuando intenta guardar,<br>Entonces el sistema solicita completar el campo.          |

| ID Épica | Épica                                | ID HU | Título HU                                  | Descripción HU                                                                | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                           |
| -------- | ------------------------------------ | ----- | ------------------------------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP03     | Recomendaciones y Gestión del Estrés | US07  | Recibir recomendaciones personalizadas     | Como usuario, quiero recibir recomendaciones basadas en mi perfil de estrés.  | **Escenario 1: Recomendaciones generadas**<br>Dado que el usuario completó cuestionario y biometría,<br>Cuando accede a recomendaciones,<br>Entonces el sistema muestra sugerencias personalizadas.<br><br>**Escenario 2: Falta de datos**<br>Dado que el usuario no completó su perfil,<br>Cuando intenta ver recomendaciones,<br>Entonces el sistema muestra mensaje indicando datos faltantes. |
| EP03     | Recomendaciones y Gestión del Estrés | US08  | Realizar ejercicios de respiración guiados | Como usuario, quiero realizar ejercicios guiados para reducir el estrés.      | **Escenario 1: Ejercicio completado**<br>Dado que el usuario selecciona un ejercicio,<br>Cuando lo finaliza,<br>Entonces el sistema registra la actividad.<br><br>**Escenario 2: Interrupción**<br>Dado que el usuario abandona el ejercicio,<br>Cuando regresa,<br>Entonces el sistema permite reiniciar o continuar.                                                                            |
| EP03     | Recomendaciones y Gestión del Estrés | US09  | Programar pausas activas laborales         | Como usuario, quiero programar pausas para reducir mi carga laboral y estrés. | **Escenario 1: Pausa programada**<br>Dado que el usuario accede a la agenda,<br>Cuando programa una pausa,<br>Entonces el sistema guarda recordatorio.<br><br>**Escenario 2: Notificación**<br>Dado que se acerca la pausa,<br>Cuando llega la hora,<br>Entonces el sistema envía recordatorio.                                                                                                   |

| ID Épica | Épica                               | ID HU | Título HU                               | Descripción HU                                                                     | Criterios de Aceptación                                                                                                                                                                                                                                                                                                               |
| -------- | ----------------------------------- | ----- | --------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP04     | Seguimiento y Análisis del Progreso | US10  | Visualizar dashboard personal de estrés | Como usuario, quiero ver mi estado actual de estrés en un dashboard.               | **Escenario 1: Dashboard con datos**<br>Dado que el usuario tiene registros,<br>Cuando ingresa al dashboard,<br>Entonces el sistema muestra sus métricas.<br><br>**Escenario 2: Sin datos**<br>Dado que no hay registros,<br>Cuando accede,<br>Entonces el sistema indica que aún no hay información.                                 |
| EP04     | Seguimiento y Análisis del Progreso | US11  | Generar informes de progreso            | Como usuario, quiero generar informes para evaluar mis avances.                    | **Escenario 1: Informe generado**<br>Dado que el usuario selecciona un periodo,<br>Cuando solicita un informe,<br>Entonces el sistema genera reporte descargable.<br><br>**Escenario 2: Falta de datos**<br>Dado que el usuario no tiene registros,<br>Cuando intenta generar,<br>Entonces el sistema muestra advertencia.            |
| EP04     | Seguimiento y Análisis del Progreso | US12  | Registrar desencadenantes de estrés     | Como usuario, quiero registrar situaciones que detonan mi estrés para analizarlas. | **Escenario 1: Registro exitoso**<br>Dado que el usuario accede a “Desencadenantes”,<br>Cuando ingresa información,<br>Entonces el sistema guarda el registro.<br><br>**Escenario 2: Registro incompleto**<br>Dado que el usuario no llena campos obligatorios,<br>Cuando intenta guardar,<br>Entonces el sistema solicita completar. |

| ID Épica | Épica                      | ID HU | Título HU                            | Descripción HU                                                                | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                  |
| -------- | -------------------------- | ----- | ------------------------------------ | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP05     | Conexión con Especialistas | US13  | Buscar psicólogos especializados     | Como usuario, quiero buscar psicólogos según especialidad para recibir apoyo. | **Escenario 1: Búsqueda exitosa**<br>Dado que el usuario accede a la búsqueda,<br>Cuando ingresa criterios,<br>Entonces el sistema muestra psicólogos disponibles.<br><br>**Escenario 2: Sin resultados**<br>Dado que no hay coincidencias,<br>Cuando busca,<br>Entonces el sistema muestra mensaje indicando que no hay psicólogos.     |
| EP05     | Conexión con Especialistas | US14  | Agendar cita con psicólogo           | Como usuario, quiero agendar una cita en línea con un psicólogo.              | **Escenario 1: Cita agendada**<br>Dado que el usuario selecciona especialista y horario,<br>Cuando confirma,<br>Entonces el sistema guarda la cita.<br><br>**Escenario 2: Conflicto de horario**<br>Dado que ya existe una cita en ese horario,<br>Cuando intenta reservar,<br>Entonces el sistema muestra error y solicita otra opción. |
| EP05     | Conexión con Especialistas | US15  | Compartir informes con especialistas | Como usuario, quiero compartir mis informes de progreso con un psicólogo.     | **Escenario 1: Informe compartido**<br>Dado que el usuario selecciona un informe,<br>Cuando lo envía,<br>Entonces el especialista recibe acceso.<br><br>**Escenario 2: Error de envío**<br>Dado que ocurre una falla,<br>Cuando intenta compartir,<br>Entonces el sistema muestra mensaje de error.                                      |

| ID Épica | Épica                      | ID HU | Título HU                         | Descripción HU                                                               | Criterios de Aceptación                                                                                                                                                                                                                                                                                                   |
| -------- | -------------------------- | ----- | --------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP06     | Comunidad y Soporte Social | US16  | Participar en grupos de apoyo     | Como usuario, quiero unirme a grupos de apoyo para compartir experiencias.   | **Escenario 1: Unión exitosa**<br>Dado que el usuario accede a grupos,<br>Cuando selecciona uno,<br>Entonces el sistema lo agrega.<br><br>**Escenario 2: Grupo cerrado**<br>Dado que el grupo requiere aprobación,<br>Cuando solicita unirse,<br>Entonces el sistema notifica que debe esperar confirmación.              |
| EP06     | Comunidad y Soporte Social | US17  | Acceder a biblioteca de recursos  | Como usuario, quiero acceder a artículos y videos sobre manejo del estrés.   | **Escenario 1: Acceso exitoso**<br>Dado que el usuario accede a la biblioteca,<br>Cuando selecciona un recurso,<br>Entonces el sistema lo abre.<br><br>**Escenario 2: Recurso no disponible**<br>Dado que un recurso fue eliminado,<br>Cuando el usuario lo selecciona,<br>Entonces el sistema notifica indisponibilidad. |
| EP06     | Comunidad y Soporte Social | US18  | Participar en desafíos antiestrés | Como usuario, quiero unirme a retos que me ayuden a mejorar mi salud mental. | **Escenario 1: Unión a desafío**<br>Dado que el usuario accede a desafíos,<br>Cuando selecciona uno,<br>Entonces el sistema lo registra.<br><br>**Escenario 2: Desafío finalizado**<br>Dado que el reto ya concluyó,<br>Cuando intenta unirse,<br>Entonces el sistema notifica que no está disponible.                    |

| ID Épica | Épica                           | ID HU | Título HU                          | Descripción HU                                                                                | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------- | ----- | ---------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| EP07     | Integración con Entorno Laboral | US19  | Analizar carga laboral             | Como empleado, quiero registrar y analizar mi carga laboral para identificar estrés laboral.  | **Escenario 1: Registro exitoso**<br>Dado que el usuario ingresa horas trabajadas,<br>Cuando guarda la información,<br>Entonces el sistema calcula carga laboral.<br><br>**Escenario 2: Validación**<br>Dado que el usuario omite datos requeridos,<br>Cuando intenta guardar,<br>Entonces el sistema solicita completarlos.                           |
| EP07     | Integración con Entorno Laboral | US20  | Recibir recordatorios de ergonomía | Como usuario, quiero recibir recordatorios de ergonomía para cuidar mi postura en el trabajo. | **Escenario 1: Recordatorio enviado**<br>Dado que el usuario configuró notificaciones,<br>Cuando llega el horario programado,<br>Entonces el sistema envía recordatorio.<br><br>**Escenario 2: Notificaciones desactivadas**<br>Dado que el usuario desactiva recordatorios,<br>Cuando llega el horario,<br>Entonces el sistema no envía notificación. |

---

## 3.3. Impact Mapping

Impact Mapping - Segmento 1

<div>
  <p align="center"><img src="assets/md-images/ImpactMapping_s1.png" alt="Impact mapping segmento 1" width="700px" /></p>
</div>

Impact Mapping - Segmento 2

<div>
  <p align="center"><img src="assets/md-images/ImpactMapping_s2.png" alt="Impact mapping segmento 2" width="700px" /></p>
</div>

---

## 3.4. Product Backlog

| Prioridad | User Story ID | Título HU                                  | Story Points |
| --------- | ------------- | ------------------------------------------ | ------------ |
| 1         | US01          | Registrar cuenta de usuario                | 3            |
| 2         | US02          | Configurar perfil biométrico               | 5            |
| 3         | US03          | Completar cuestionario inicial de salud    | 3            |
| 4         | US04          | Realizar test de autoevaluación de estrés  | 5            |
| 5         | US05          | Análisis biométrico de señales de estrés   | 8            |
| 6         | US06          | Registro de síntomas físicos               | 3            |
| 7         | US07          | Recibir recomendaciones personalizadas     | 5            |
| 8         | US08          | Realizar ejercicios de respiración guiados | 3            |
| 9         | US09          | Programar pausas activas laborales         | 3            |
| 10        | US10          | Visualizar dashboard personal de estrés    | 5            |
| 11        | US11          | Generar informes de progreso               | 5            |
| 12        | US12          | Registrar desencadenantes de estrés        | 3            |
| 13        | US13          | Buscar psicólogos especializados           | 3            |
| 14        | US14          | Agendar cita con psicólogo                 | 5            |
| 15        | US15          | Compartir informes con especialistas       | 3            |
| 16        | US16          | Participar en grupos de apoyo              | 3            |
| 17        | US17          | Acceder a biblioteca de recursos           | 2            |
| 18        | US18          | Participar en desafíos antiestrés          | 3            |
| 19        | US19          | Analizar carga laboral                     | 5            |
| 20        | US20          | Recibir recordatorios de ergonomía         | 2            |

---
# 4. Capítulo IV: Product Design  

## 4.1. Style Guidelines  

Las *Style Guidelines* de **MinDora** funcionan como un repositorio central para el equipo, donde se concentran **assets, tipografías, colores y componentes**. Su propósito es mantener una presentación consistente en todos los productos (web y móvil).  

Este apartado se divide en:  
- **4.1.1 General Style Guidelines:** lineamientos de branding, tipografía, colores, spacing y tono de comunicación.  
- **4.1.2 Web Style Guidelines:** estándares visuales e interacción para interfaces web responsivas.  

---

### 4.1.1 General Style Guidelines  

En esta sección se definen las bases visuales y de comunicación de *MinDora*. Se establecen los principios de **branding, tipografía, colores, spacing y tono de comunicación**, los cuales guiarán todo el diseño de la plataforma.  

#### Branding  
El logo de *MinDora* combina un perfil humano con un cerebro estilizado y ondas suaves, representando la unión entre ciencia, tecnología y bienestar emocional.  

<p align="center">
  <img src="assets/md-images/MINDORALOGO.png" alt="MINDORALOGO" width="500px" />
</p>  

#### Tipografía  
- Fuentes **sans-serif**, modernas y legibles en cualquier dispositivo.  
- Jerarquía visual clara: títulos en seminegrita y tamaño destacado, subtítulos medianos, texto base en peso regular.  

#### Paleta de colores  

- **Turquesa Oscuro (#1B6F77):** innovación y confianza.  
<p align="center"><img src="assets/md-images/1styleguidelines.png" alt="Turquesa Oscuro" width="500px" /></p>  

- **Azul Celeste (#4DB6C3):** calma y frescura.  
<p align="center"><img src="assets/md-images/2styleguidelines.png" alt="Azul Celeste" width="500px" /></p>  

- **Verde Azulado (#2E8B92):** equilibrio emocional.  
<p align="center"><img src="assets/md-images/3styleguidelines.png" alt="Verde Azulado" width="500px" /></p>  

- **Degradado Azul–Turquesa:** dinamismo y fluidez.  
<p align="center"><img src="assets/md-images/4styleguidelines.png" alt="Degradado Azul-Turquesa" width="500px" /></p>  

- **Fondo Oscuro (#0F1F21):** contraste y profesionalismo.  
<p align="center"><img src="assets/md-images/5styleguidelines.png" alt="Fondo Oscuro" width="500px" /></p>  

#### Spacing  
- Uso de espacios en blanco para evitar saturación visual.  
- Márgenes amplios: **40px en desktop, 24px en móvil**.  
- Separación entre párrafos: **16–20px**.  
- Paddings uniformes en botones y tarjetas.  

#### Tono de comunicación  
Las dimensiones adoptadas en *MinDora* son:  
- **Serio (no divertido):** transmite profesionalismo y confianza en un tema sensible como el estrés laboral.  
- **Formal (no casual):** mantiene rigurosidad científica sin perder claridad.  
- **Respetuoso (no irreverente):** cuida el trato con los usuarios, evitando minimizar sus emociones.  
- **Sereno (más que entusiasta):** busca inspirar calma y tranquilidad en lugar de euforia.  

---

### 4.1.2 Web Style Guidelines  

Las guías de estilo web de *MinDora* definen cómo se aplican los **estándares visuales e interactivos** en interfaces responsivas (desktop, tablet y móvil), asegurando coherencia y accesibilidad.  

#### Logo y branding  
- Posición en la esquina superior izquierda.  
- Área de seguridad que evita comprometer la visibilidad.  

#### Colores en la interfaz  
- **Turquesa Oscuro:** barra de navegación.  
- **Azul Celeste:** botones principales.  
- **Verde Azulado:** detalles secundarios.  
- **Fondo Oscuro:** base de la interfaz.  

#### Tipografía  
- Fuentes sans-serif en toda la web.  
- Jerarquía visual clara:  
  - Títulos en mayúscula o seminegrita.  
  - Botones con texto centrado.  
  - Texto base en peso regular.  

#### Spacing  
- Márgenes amplios para resaltar secciones clave.  
- Consistencia en paddings de contenedores y botones.  
- Espacios uniformes entre texto e imágenes.  

#### Navegación  
- Menú fijo en la parte superior con enlaces simples.  
- Ícono hamburguesa para dispositivos móviles.  

#### Botones e interacción  
- Botones rectangulares redondeados en **Azul Celeste**.  
- *Hover* con un tono más intenso del mismo color.  
- Tamaños amplios, accesibles en pantallas táctiles.  

#### Fondo e identidad visual  
- Fondo en **degradado azul–turquesa sobre negro**, transmitiendo calma y tecnología.  
- Elementos gráficos abstractos (ondas y cerebro iluminado) como parte de la identidad neurocientífica.  

<p align="center">
  <img src="assets/md-images/fondostyleguidelines.png" alt="Fondo Style Guidelines" width="700px" />
</p>  


## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

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

---

# 5. Capítulo V: Product Implementation, Validation & Deployment

En esta sección se mencionan las decisiones y convenciones las cuales permitirán mantener una consistencia durante el desarrollo del proyecto. 

### 5.1.1 Software Development Environment Configuration

**Project Management:**

La gestión de los proyectos tiene como objetivo mejorar los procesos y su entorno para alcanzar los resultados esperados.

* **Trello:** Es una herramienta visual que permite gestionar cualquier tipo de proyecto y el flujo de trabajo que el equipo desarrollador seguirá para implementar correctamente las tareas de código para el Landing Page y el web Application.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://trello.com/es </td>
        </tr>
    </tbody>
</table>

**Requirements Management:**

Es el proceso de garantizar que una organización documente verifique y satisfaga las necesidades, expectativas de sus clientes con las partes interesadas internas o externas.

* **Pivotal Tracker:** Esta herramienta se define como una plataforma en la que se realiza la gestión de user stories, agrupándolos en epics y clasificando su presencia en el programa, por puntaje. Se usó porque permite que cada miembro del equipo comparta la misma vista en tiempo real de lo que está sucediendo con cada proyecto, ya sea aportando con diferentes secciones o corrigiendo el flujo del proyecto.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.pivotaltracker.com/  </td>
        </tr>
    </tbody>
</table>

**Product UX/UI Design:**

Nos permite desarrollar el modelo en nuestro producto de manera digital y forme parte de la vida del consumidor. En este caso realizar un modelo de sitio web para computadoras y celulares.

* **Uxpressia:** es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://uxpressia.com/ </td>
        </tr>
    </tbody>
</table>

* **MIRO:** es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, la creación de lluvias de ideas, mapas mentales y una variedad de otras actividades colaborativas.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.miro.com/</td>
        </tr>
    </tbody>
</table>

* **Figma:** es una herramienta de prototipo web y editor de gráficos vectorial, que, a diferencia de las otras herramientas, se aloja en la web, permitiendo establecer los modelos para versión en Web Browser y Landing Page.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.figma.com/ </td>
        </tr>
    </tbody>
</table>

* **LucidChart:** es una herramienta de diagramación basada en la web, que permite a los usuarios colaborar y trabajar juntos en tiempo real, creando diseños UML, mapas mentales, prototipos de software y muchos otros tipos de diagrama. 

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.lucidchart.com </td>
        </tr>
    </tbody>
</table>

* **Structurizr:** es una herramienta de diseño que soporta el modelo C4, para visualizar la arquitectura de software de nuestra solución. 

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://structurizr.com/ </td>
        </tr>
    </tbody>
</table>

**Software Development:**

Es una estructura aplicada al desarrollo de un producto de software. Se utiliza para el establecimiento de un proceso para el desarrollo de software, cada uno de los cuales describe un enfoque diferente para diferentes actividades que tienen lugar durante el proceso. 

* **Github:** Es un repositorio comunitario cuya función es almacenar los avances de un proyecto elaborado por un grupo de personas.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://github.com/  </td>
        </tr>
    </tbody>
</table>

* **WebStorm:** Es un entorno de JetBrains, empresa desarrolladora de Software. Este nos ofrece facilidad en probar nuestro entorno web en navegadores web. Para el proyecto se implementará la ayuda de los lenguajes HTML, CSS y TypeScript.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://www.jetbrains.com/webstorm/ 
            </td>
        </tr>
    </tbody>
</table>

* **HTML:** Es un lenguaje que sirve como desarrollador de plataformas web que trabaja con hipertextos, que enlace a otros documentos. Este lenguaje ofrece herramientas para el diseño del sitio web.


<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://www.jetbrains.com/help/webstorm/editing-html-files.html 
             </td>
        </tr>
    </tbody>
</table>

* **CSS:** Es un lenguaje de diseño para el entorno web. Permite elaborar el interfaz de usuario diseñada anteriormente, agregando colores, tamaños entre otros elementos. 

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion 
             </td>
        </tr>
    </tbody>
</table>


* **TypeScript:** Es un superconjunto de JavaScript, que esencialmente añade tipos estáticos y objetos basados en clases

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://www.typescriptlang.org/ 
             </td>
        </tr>
    </tbody>
</table>

* **Angular:**  Framework de TypeScript, de código abierto, utilizado para desarrollar SPA(Single Page Application). 

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://angular.io  </td>
        </tr>
    </tbody>
</table>

**Software Testing:**

 Es el acto de examinar los artefactos y el comportamiento del software bajo prueba  mediante validación y verificación.

* **Lenguaje Gherkins:** Es un DSL o Lenguaje Específico de Dominio (Domain-Specific Language), es decir, un lenguaje que está creado para resolver un problema. Además de ser interpretado en código, se puede agregar los users stories del programa con sus respectivas partes: Feature, Scenario, Example, Scenario Outline, Given, When, Then y And.

**Software Development:**

* **Github pages:** Servicio de Github que nos permitió alojar nuestra landing page y nos permitirá alojar nuestro web applications.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td> https://pages.github.com/ </td>
        </tr>
    </tbody>
</table>

### 5.1.2. Source Code Management
En esta sección se presenta la gestión de código fuente o como es conocido por sus siglas en inglés SCM (Source Code Management). Su función principal es realizar un seguimiento de las modificaciones que el equipo realizará a lo largo del desarrollo de sus proyectos en los repositorios de código fuente. Se emplea como un sistema de control de versiones que permite dar seguimiento a los cambios que cada integrante o desarrollador realice en el proyecto. Asimismo, cabe resaltar que para el sistema de control de versiones emplearemos GitHub.

**GitFlow**

Es el modelo alternativo de creación de ramas en Git que en los últimos años se ha vuelto una herramienta indispensable para muchos desarrolladores. Este flujo de trabajo de control de versiones utiliza ramas y fue publicado y popularizado por Vincent Driessen. Su principal función es ayudar en la organización de la versión de un código, permitiendo la creación de nuevos Features y Hotfixes de manera organizada.

**Main Branches:**

* **main:** es la rama principal, a partir de ella se recorrerán todas las ramas y contendrá la última versión y las anteriores creadas por los desarrolladores.

* **Develop:** Esta rama puede ser creada a partir de la rama main(master) y contará con todos los Features estables. Esto significa que a través de esta rama el equipo podrá integrar las funciones.

**Support Branches:**

* **Feature:** se ramifica de developer y al finalizar debe fusionarse de nuevo en develop. Se emplea para desarrollar nuevas funciones que se integrarán en versiones posteriores. 

* **Release:** también se ramifica de develop, es la rama que admite la preparación de una nueva versión de producción. 

* **Hotfix:** también está destinado a una nueva versión de producción, pero esta se ramifica de main. Su función es reparar rápidamente las publicaciones de producción.

**Conventional Commits:**

Son una convención para nombrar mensajes de commit en Git de forma estructurada, clara y semántica.

* feat: Se añade una nueva funcionalidad.
* fix: Se corrige un error.
* docs: Cambios en la documentación.
* style: Cambios de formato o estilo de código (sin impacto en la lógica).
* refactor: Mejoras en el código que no añaden nuevas funcionalidades ni corrigen errores.
* test: Añadir o modificar tests.
* chore: Cambios menores sin impacto en el código de producción (actualización de dependencias, configuración, etc.).

### 5.1.4 Software Deployment Configuration

Como se mencionó previamente, la gestión de nuestro código fuente se realizará a través de GitHub. Asimismo, se utilizará GitHub Pages para la publicación y despliegue de la página. 

Para el desarrollo del Landing Page de MindFlix se han usado las siguientes herramientas:

* HTML: lenguaje con el cual está estructurado nuestro landing page.

* CSS: diseño y formato para el html desarrollado.

El despliegue de nuestro landing page es posible gracias a la herramienta de Github Pages. El cual es un servicio que nos permite alojar nuestro landing directamente desde el 
repositorio de GitHub. 

Para lograr el despliegue seguimos lo siguientes pasos:

1. Dirigirnos al repositorio de la página y entrar en la sección de configuración. 

2. Ir a la opción de “Pages”, donde se encontrarán todas las opciones de publicación de página.

3. Se debe seleccionar la rama la cual se va a publicar en el vínculo. También se debe seleccionar la carpeta donde se localizara la publicación. 

4. Finalmente, el link vínculo de nuestra página aparecerá en la parte superior. 

<table>
    <tbody>
        <tr>
            <td>Link </td>
            <td>  https://mindora.github.io/Landing-Page/  
             </td>
        </tr>
    </tbody>
</table>

5. Evidencia de deployment

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

# 6. Conclusiones

## 6.1. Conclusiones
## 6.2. Recomendaciones

# 7. Bibliografía

# 8. Anexos
