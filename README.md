<div align="center">

# FarmGuard-Tunix-Report 

  <h3>Universidad Peruana de Ciencias Aplicadas</h3>

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" height="150">

<h5>Ingeniería de Software - 7mo ciclo</h5>
  <h5>Desarrollo de Soluciones IOT - 1ASI0572</h5>
  <h5>
NRC: 3320</h5>
  <h5>Docente: Marco Antonio Leon Baca</h5>
  <h5>"Informe de Trabajo Final" <h5>
  <h5>Startup: Tunix</h5>
  <h5>Producto: FarmGuard</h5>
</div>

## Team Members 

<div align="center">

<table>
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Zarate Castro Jose Daniel</td><td>u202019128</td></tr>
    <tr><td>Brayan smith morales quispe</td><td>u20211f984</td></tr>
    <tr><td>Oscar nathaniel garayar mori</td><td>u202014115</td></tr>
    <tr><td>Jara Benites Quique Vladimir</td><td>u202022365</td></tr>
    <tr><td>Carlos Alberto Ochoa Colonio</td><td>u202315945</td></tr>
  </tbody>
</table>

</div>

<div align="center">
  <h5>Setiembre-2025</h5>
</div>

<div style="page-break-after: always;"></div>

### Registro de Informe

| Versión | Fecha    | Autor(es)                             | Descripción de modificación                                                             |
|---------|----------|----------------------------------------|-----------------------------------------------------------------------------------------|
| 0.1     | 03/09/25 | BrayanSmith Morales Quispe        | Inicio del documento                                                            |




### Project Report Collaboration Insights

**URL del repositorio para el reporte del proyecto:** https://acortar.link/CRGD3H
**Link de los repositorios de la oraganización:** https://github.com/upc-pre-202502-1ASI0572-3320-Unix

**TB1**

En esta primera entrega (TB1), el objetivo principal fue ...

| Integrante                        |Tarea|
| ----------------------------------|-----|
| Zarate Castro Jose Daniel         | | 
| Brayan Smith Morales Quispe       | |
| Oscar Nathaniel Garayar Mori      ||
| Jara Benites Quique Vladimir      ||
| Carlos Alberto Ochoa Colonio      ||

![TB1]()


Este gráfico muestra la cantidad de commits realizados por cada integrante durante el desarrollo del TB1 Tunix.

Estas evidencias reflejan una colaboración equilibrada y efectiva, con cada miembro aportando de manera significativa al avance y desarrollo de la solución.



# Contenido

## 📚 Tabla de Contenidos

#### [Capítulo I: Introducción](#introducción)
  - [1.1 Startup Profile](#startup-profile)
    - [1.1.1 Descripción de la Startup](#descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#solution-profile)
    - [1.2.1 Antecedentes y problemática](#antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#lean-ux-canvas)
  - [1.3 Segmentos Objetivo](#segmentos-objetivo)

#### [Capítulo II: Requirements Elicitation & Analysis](#requirements-elicitation--analysis)
  - [2.1 Competidores](#competidores)
    - [2.1.1 Análisis competitivo](#análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#entrevistas)
    - [2.2.1 Diseño de entrevistas](#diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#análisis-de-entrevistas)
  - [2.3 Needfinding](#needfinding)
    - [2.3.1 User Personas](#user-personas)
    - [2.3.2 User Task Matrix](#user-task-matrix)
    - [2.3.3 User Journey Mapping](#user-journey-mapping)
    - [2.3.4 Empathy Mapping](#empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#ubiquitous-language)

#### [Capítulo III: Requirements Specification](#requirements-specification)
  - [3.1 To-Be Scenario Mapping](#to-be-scenario-mapping)
  - [3.2 User Stories](#user-stories)
  - [3.3 Impact Mapping](#impact-mapping)
  - [3.4 Product Backlog](#product-backlog)

#### [Capítulo IV: Solution Software Design](#solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#strategic-level-domain-driven-design)
    - [4.1.1 EventStorming](#eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#bounded-context-canvases)
    - [4.1.2 Context Mapping](#context-mapping)
    - [4.1.3 Software Architecture](#software-architecture)
      - [4.1.3.1 System Landscape Diagram](#system-landscape-diagram)
      - [4.1.3.2 Context Level Diagrams](#context-level-diagrams)
      - [4.1.3.3 Container Level Diagrams](#container-level-diagrams)
      - [4.1.3.4 Deployment Diagrams](#deployment-diagrams)
  - [4.2 Tactical-Level Domain-Driven Design](#tactical-level-domain-driven-design)
    - [4.2.X Bounded Context: Nombre del Contexto](#bounded-context-nombre-del-contexto)
      - [4.2.X.1 Domain Layer](#domain-layer)
      - [4.2.X.2 Interface Layer](#interface-layer)
      - [4.2.X.3 Application Layer](#application-layer)
      - [4.2.X.4 Infrastructure Layer](#infrastructure-layer)
      - [4.2.X.5 Component Level Diagrams](#component-level-diagrams)
      - [4.2.X.6 Code Level Diagrams](#code-level-diagrams)
        - [4.2.X.6.1 Domain Layer Class Diagrams](#domain-layer-class-diagrams)
        - [4.2.X.6.2 Database Design Diagram](#database-design-diagram)

#### [Capítulo V: Solution UI/UX Design](#solution-uiux-design)
  - [5.1 Style Guidelines](#style-guidelines)
    - [5.1.1 General Style Guidelines](#general-style-guidelines)
    - [5.1.2 Web, Mobile and IoT Style Guidelines](#web-mobile-and-iot-style-guidelines)
  - [5.2 Information Architecture](#information-architecture)
    - [5.2.1 Organization Systems](#organization-systems)
    - [5.2.2 Labeling Systems](#labeling-systems)
    - [5.2.3 SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
    - [5.2.4 Searching Systems](#searching-systems)
    - [5.2.5 Navigation Systems](#navigation-systems)
  - [5.3 Landing Page UI Design](#landing-page-ui-design)
    - [5.3.1 Wireframe](#wireframe)
    - [5.3.2 Mock-up](#mock-up)
  - [5.4 Applications UX/UI Design](#applications-uxui-design)
    - [5.4.1 Wireframes](#wireframes)
    - [5.4.2 Wireflow Diagrams](#wireflow-diagrams)
    - [5.4.3 Mock-ups](#mock-ups)
    - [5.4.4 User Flow Diagrams](#user-flow-diagrams)
  - [5.5 Applications Prototyping](#applications-prototyping)

#### [Capítulo VI: Product Implementation, Validation & Deployment](#product-implementation-validation--deployment)
  - [6.1 Software Configuration Management](#software-configuration-management)
    - [6.1.1 Development Environment Configuration](#development-environment-configuration)
    - [6.1.2 Source Code Management](#source-code-management)
    - [6.1.3 Code Style Guide & Conventions](#code-style-guide--conventions)
    - [6.1.4 Deployment Configuration](#deployment-configuration)
  - [6.2 Landing Page, Services & Applications Implementation](#landing-page-services--applications-implementation)
    - [6.2.1 Sprint 1](#sprint-1)
      - [6.2.1.1 Sprint Planning 1](#sprint-planning-1)
      - [6.2.1.2 Sprint Backlog 1](#sprint-backlog-1)
      - [6.2.1.3 Development Evidence](#development-evidence)
      - [6.2.1.4 Testing Suite Evidence](#testing-suite-evidence)
      - [6.2.1.5 Execution Evidence](#execution-evidence)
      - [6.2.1.6 Services Documentation Evidence](#services-documentation-evidence)
      - [6.2.1.7 Software Deployment Evidence](#deployment-evidence)
      - [6.2.1.8 Team Collaboration Insights](#team-collaboration-insights)
    - [6.2.2 Sprint 2](#sprint-2)
      - [6.2.2.1 Sprint Planning 2](#sprint-planning-2)
      - [6.2.2.2 Sprint Backlog 2](#sprint-backlog-2)
      - [6.2.2.3 Development Evidence](#development-evidence)
      - [6.2.2.4 Testing Suite Evidence](#testing-suite-evidence)
      - [6.2.2.5 Execution Evidence](#execution-evidence)
      - [6.2.2.6 Services Documentation Evidence](#services-documentation-evidence)
      - [6.2.2.7 Software Deployment Evidence](#deployment-evidence)
      - [6.2.2.8 Team Collaboration Insights](#team-collaboration-insights)
    - [6.2.3 Sprint 3](#sprint-3)
      - [6.2.3.1 Sprint Planning 3](#sprint-planning-3)
      - [6.2.3.2 Sprint Backlog 3](#sprint-backlog-3)
      - [6.2.3.3 Development Evidence](#development-evidence)
      - [6.2.3.4 Testing Suite Evidence](#testing-suite-evidence)
      - [6.2.3.5 Execution Evidence](#execution-evidence)
      - [6.2.3.6 Services Documentation Evidence](#services-documentation-evidence)
      - [6.2.3.7 Software Deployment Evidence](#deployment-evidence)
      - [6.2.3.8 Team Collaboration Insights](#team-collaboration-insights)
  - [6.3 Validation Interviews](#validation-interviews)
    - [6.3.1 Diseño de Entrevistas](#diseño-de-entrevistas)
    - [6.3.2 Registro de Entrevistas](#registro-de-entrevistas)
    - [6.3.3 Evaluaciones según heurísticas](#evaluaciones-según-heurísticas)
  - [6.4 Video About-the-Product](#video-about-the-product)
  - [6.5 Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators)

### [Anexos](#anexos)

#### [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
  - [Conclusiones del Proyecto](#conclusiones-del-proyecto)
  - [Recomendaciones para trabajos futuros](#recomendaciones-para-trabajos-futuros)
  - [Video About-the-Team](#video-about-the-team)

# Student Outcome 

<table>
  <thead>
    <tr>
        <th>Criterio especifico</th>
        <th>Acciones realizadas</th>
        <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td><strong>Trabaja en equipo para 
      proporcionar liderazgo en 
      forma conjunta</strong></td>
      <td>
      <h6><strong>Brayan Smith Morales Quispe</strong></h6>
      TB1:<p>Ayude a organizar y repartir temas a  cada miembro del equipo aparte q ayude cualquier duda de mis compañeros respecto al trabajo.</p>
      <td>
      TB1: <p>
      </td>
  </tr>
   <tr>
      <td><strong>Crea un entorno colaborativo e 
      inclusivo, establece metas, planifica tareas 
      y cumple objetivos </strong></td>
      <td>
      <h6>Brayan Smith Morales Quispe</h6>
      TB1:<p>Como grupo nos establecimos metas claras hacia donde va nuestro trabajo, la planificacion considero que fue regular puesto que no todo el equipo tiene el tiempo para realizar juntas mas seguidas.</p>
      </td>
      <td>
      TB1:</p> 
      </td>
  </tr>

  </tbody>
</table>



# Capítulo I: Introducción  

## 1.1 Startup Profile  

### 1.1.1 Descripción de la Startup  

**Nombre de la startup:** Tunix

**Producto:** FarmGuard

**Sector:** Ganadería y Veterinaria

**Descripción:**

Somos Tunix, una startup universitaria que busca transformar la manera en que los ganaderos y veterinarios gestionan la salud y el bienestar de los animales. A través de soluciones tecnológicas innovadoras, ofrecemos herramientas que permiten un control eficiente y en tiempo real del estado de los animales, sus historiales médicos y tratamientos.

Nuestra propuesta se apoya en tecnologías emergentes como el Internet de las Cosas (IoT), que facilitan el monitoreo continuo, la automatización de procesos y la generación de alertas preventivas. Esto no solo optimiza la productividad y reduce costos, sino que también garantiza el cumplimiento de estándares de calidad y bienestar animal.

FarmGuard se posiciona como una solución integral, accesible y centrada en el usuario, diseñada para satisfacer las necesidades específicas de granjas y veterinarias, promoviendo una gestión más sostenible y responsable.

### 1.1.2 Perfiles de integrantes del equipo

<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th colspan="2">Perfiles de integrantes del equipo</th>
  </tr>
  <tr>
    <td>
      <strong>Carlos Alberto Ochoa Colonio</strong><br>
      Soy un estudiante y actualmente me encuentro en el octavo ciclo de la carrera de ingeniería de software.
    </td>
    <td align="center">
      <img src="assets/student/Carlos_Ochoa.jpg" alt="Carlos" style="max-height: 250px;">
    </td>
  </tr>
  <tr>
    <td>
      <strong>Zarate Castro Jose Daniel</strong>
        Descripcion
    </td>
    <td>
      <img src="assets/student/Me2.jpg" alt="Carlos" style="max-height: 250px;">
    </td>
  </tr>
  <tr>
    <td>
      <strong>Oscar Nathaniel Garayar Mori</strong>
        Descripcion
    </td>
    <td>
      <img src="assets/student/Me2.jpg" alt="Carlos" style="max-height: 250px;">
    </td>
  </tr>
  <tr>
    <td>
      <strong>Jara Benites Quique Vladimir</strong>
        Descripcion
    </td>
    <td>
      <img src="assets/student/Me2.jpg" alt="Carlos" style="max-height: 250px;">
    </td>
  </tr>
  <tr>
    <td>
      <strong>Brayan Smith Morales Quispe</strong><br>
      Soy estudiante de ingenieria de software de la upc 8vo ciclo que le gusta el desarrollo web, desarrollo de videojuegos y aplicaciones moviles.
    </td>
    <td>
      <img src="Assets/img/Integrantes/brayan.png" alt="Bryan" style="max-height:250px;">
    </td>
  </tr>
</table>


## 1.2 Solution Profile  

### 1.2.1 Antecedentes y problemática

### Descripcion de la problematica
Nuestro software esta enfocado en el sector veterinario y ganadero, este busca facilitar el control de estado de los animales en los diferentes rubros mencionados, evitar el riesgo de perder informacion critica, duplicar informacion u omitir tratamientos, lo que puede provocar problemas de salud en los animales y generando perdidas economicas. 

#### Técnica de las 5 ‘W’s y 2 ‘H’s

#### What?

**¿Cuál es el problema?**

El problema identificado es la falta de un sistema que permita llevar un control total y en tiempo real de la salud de los animales. Esto provoca dificulta el seguimiento preciso del estado de cada animal, historial de vacunas y tratamientos médicos. Como resultado, los ganaderos y veterinarios enfrentan riesgos como la duplicación de información, administración de tratamientos incorrectos o innecesarios y la omision de tratamientos especiales, lo que compromete la salud de los animales


#### When?

**¿Cuándo sucede el problema?**

Sucede al momento que una veterinaria o granja requiere monitorear una cantidad grande o selecta de animales, sin tener que recurrir a documentos fisicos o digitales que hacen el monitoreo mas lento y menos eficaz.  


#### Where?


**¿Dónde surge el problema?**

El problema surge en granjas y veterinarias que manejan múltiples registros de animales y carecen de un sistema adecuado para gestionarlos de manera eficiente.

#### Who?

**¿Quiénes están involucrados?**

Los principales afectados son los dueños de granjas o veterinarios que manejan multiples registros de animales sobre su estado de salud en tiempo real.


#### Why?

**¿Cuál es la causa del problema?**

La causa del problema esta en la complejidad de gestionar múltiples registros y monitorear a un gran número de animales en diferentes granjas y veterinarias. Esto dificulta mantener un control preciso y actualizado del estado de salud de cada animal, lo que es esencial para garantizar su bienestar.

#### How?

**¿Como se lleva a cabo los hechos?**

Los hechos se desarrollan cuando se utilizan diferentes métodos desconectados entre si, como registros en papel, hojas de cálculo o software no integrado, para gestionar la información de los animales en granjas y veterinarias. Esta falta de integración provoca que los datos estén dispersos y no se comuniquen entre sí, lo que complica mantener un control preciso y actualizado del estado de salud de cada animal.

#### How much?

**¿Cual es la magnitud del problema?**
 

La magnitud del problema es grande, ya que afecta a la capacidad de la granjas y/o veterinarias para llevar un control sobre la salud de los animales. Que trae como consecuencia la baja salud de los animales, reduccion de productividad, incrementos de los costos, cumplimientos regulatorios de cada pais.


### 1.2.2 Lean UX Process  

#### 1.2.2.1  Lean UX Problem Statements

Nuestro entorno evidencia problemas graves al llevar un registro de salud y monitoreo, sobre los animales que son parte de nuestra vida diaria como los domesticos atendidos en veterinarias y los de granjas.

Hemos observado un factor critico que afecta al control de la salud de los animales, el cual puede perjudicar tanto a los animales domesticos atendidos en veterinarias como animales de granjas. 

**¿Cómo pueden las veterinarias y granjas llevar a cabo un monitoreo y registro de salud adecuados y eficientes de los animales?**


#### 1.2.2.2  Lean UX Assumptions

### Business Assumptions
* Los usuarios necesitan una aplicación del control de estado de una granja, que destaque por su seguridad y soporte técnico continuo.
* La principal necesidad de mis clientes es gestionar de manera eficaz y óptima los distintos procesos que se requieren para mantener una granja.
* La aplicación será redituable gracias a que existirá una membresía que mejora los tiempos de respuesta de soporte técnico y el acceso a la totalidad de las funciones de la aplicación sin ninguna restricción.
* A través de distintas estrategias de marketing obtendré distintos usuarios dispuestos a utilizar la aplicación.
* La aplicación será facil de utilizar para los usuarios ya que integrará una interfaz intuitiva y agradable a la vista.
### User Assumptions
* Los usuarios aceptarán compartir cierta cantidad de información fundamental para el correcto control de la granja dentro de la aplicación. 
* Los usuarios pagarán una membresía que mejora la experiencia en la aplicación al desbloquear todas las funciones disponibles.
* Los usuarios más fieles tendrán la oportunidad de acceder a nuevas funciones antes de ser publicadas en las versiones oficiales de la aplicación.
* Los usuarios entregrán su confianza a la aplicación para poder aprovecharla al máximo, utilizando las distintas características para la gestión segura, eficaz y óptima de sus granjas.

#### 1.2.2.3  Lean UX Hypothesis Statements

* Si le ofrecemos una plataforma de control y gestión de granjas a usuuarios del sector interesados, podemos tener un grupo inicial de usuarios para poder experimentar nuevas funciones y brindarles beneficios exclusivos para fortalezar la fidelidad entre el usuario y nuestra startup.
* Si la membresía que ofrecemos contiene beneficios interesantes y atractivos, los usuarios accedarán a pagar la mensualidad a cambio de disfrutar de las funciones exclusivas.
* Si las decisiones de marketing son correctas, apropiadas y enfocadas en el sector correcto, el aumento de registros en la aplicación será mucho mayor a la prevista.
* Si el startup garantiza que la información de los usuarios estará encriptada y segura, la fidelidad de los usuarios aumentará. Como consecuencia, la aplicacion adquirirá una reputación positiva. 



#### 1.2.2.4  Lean UX Canvas

![Lean UX Canvas](/Assets/img/ChapterIII/Captura%20de%20pantalla%202024-08-29%20175651.png)

## 1.3 Segmentos objetivo 

El primer segmento objetivo en el que la aplicación va a enfocarse es en productos agropecuarios dispuestos a gestionar sus granjas utilizando la aplicación de nuestra startup.

De la Encuesta Nacional Agropecuaria realizada en 2022 por el INEI a 32992 unidades agropecuarias, se conoce que el 59,8% es menor a 60 años, dando un margen importante de granjeros que posiblemente poseen conocimiento de las cualidades de los diversos dispositivos tecnológicos en la actualidad y tenga el interés de trasladar sus gestiones a medios digitales. De este grupo, el 6,6% de los productos agropecuarios especializados han recibido capacitación, por lo que la aplicación también puede servir como herramienta de aprendizaje para los productores interesados en aprender más tópicos fundamentales acerca de la gestión y control de crianza de animales.

El segundo segmento objetivo son las veterinarias de todo el país. La razón de esta elección es porque en el Perú existe un sistema deficiente del manejo de historias médicas, un documento totalmente determinante para la obtención y emisión de información de la salud de cualquier animal. En consecuencia, la desinformación en estos documentos fundamentales pueden perjudicar aún más la salud de animales que ya se encuentran padeciendo algun mal.

---

# Capítulo II: Requirements Elicitation & Analysis  

## 2.1 Competidores  

### 2.1.1 Análisis competitivo  

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Este análisis es vital para identificar cómo tu startup puede diferenciarse en un mercado competitivo, permitiéndote ofrecer una solución más efectiva y destacada en la gestión y prevención de problemas de salud animal</td>
  </tr>
  <tr>
    <td colspan="5">.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        FarmGuard
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="/Assets/img/ChapterIII/DevDream-Logo.jpeg" alt="StartUp" width="60px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    FarmLogs
    <div style="text-align: center; margin-top: 20px;">
                <img src="/Assets/img/ChapterIII/FarmLogs-Logo.jpg" alt="" width="100px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      Herdwatch
      <div style="text-align: center; margin-top: 40px;">
                <img src="/Assets/img/ChapterIII/Herdwatch-Logo.png" alt="" width="200px">
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      AgriWebb
      <div style="text-align: center; margin-top: 20px;">
                <img src="/Assets/img/ChapterIII/AgriWebb-Logo.jpg" alt="" width="610px">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Tunix está enfocada en el sector veterinario y ganadero, proporcionando un software que facilita el control de la salud de los animales, evitando la pérdida de información crítica, la duplicación de datos y la omisión de tratamientos, lo que puede causar problemas de salud y pérdidas económicas.</td>
    <td colspan="1" valign="top">FarmLogs es una plataforma digital para la gestión agrícola, que permite a los agricultores monitorear cultivos, suelos y recursos, optimizando sus operaciones</td>
    <td colspan="1" valign="top">Herdwatch es una aplicación enfocada en la gestión de granjas, diseñada para rastrear la salud y productividad del ganado, cumpliendo con las regulaciones del sector</td>
    <td colspan="1" valign="top">AgriWebb proporciona un software de gestión de ganado con un fuerte enfoque en la trazabilidad, productividad y bienestar animal, utilizando datos en tiempo real para mejorar las decisiones agrícolas</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Nuestra solucion se destaca por su enfoque integral en la prevención y el monitoreo continuo de la salud animal, asegurando que toda la información esté centralizada y actualizada en tiempo real, lo que minimiza riesgos y optimiza la gestión</td>
    <td colspan="1" valign="top">Su enfoque en la gestión integral de recursos agrícolas lo convierte en una herramienta poderosa para operaciones más grandes que requieren un control total sobre sus cultivos y suelos</td>
    <td colspan="1" valign="top">Su mayor fortaleza es la conformidad regulatoria, permitiendo a los agricultores cumplir fácilmente con las normativas, mientras optimizan la eficiencia operativa y aseguran una trazabilidad completa del ganado</td>
    <td colspan="1" valign="top">Su ventaja competitiva radica en la trazabilidad y optimización de la producción, ayudando a los agricultores a maximizar la eficiencia y mejorar la salud y productividad del ganado</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Tunix se enfoca en veterinarias y granjas que necesitan una solución efectiva para el monitoreo y control de la salud de sus animales, así como en productores agropecuarios que buscan digitalizar sus procesos.</td>
    <td colspan="1" valign="top">FarmLogs se dirige a grandes operaciones agrícolas y agricultores que buscan optimizar la gestión de sus cultivos y recursos agrícolas</td>
    <td colspan="1" valign="top">Herdwatch se enfoca en agricultores y veterinarios que requieren un sistema eficaz para el seguimiento de la salud y la productividad del ganado</td>
    <td colspan="1" valign="top">AgriWebb se dirige a agricultores que buscan optimizar la trazabilidad, productividad y bienestar del ganado a través de una plataforma digital.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top"> La estrategia incluye campañas educativas y de capacitación, marketing digital en redes sociales, y alianzas con asociaciones del sector veterinario y ganadero</td>
    <td colspan="1" valign="top">FarmLogs utiliza marketing digital enfocado en contenido educativo sobre eficiencia agrícola y productividad, además de realizar alianzas con grandes distribuidores de productos agrícolas</td>
    <td colspan="1" valign="top">Herdwatch utiliza campañas dirigidas a través de asociaciones agrícolas y veterinarias, destacando su conformidad con normativas y su facilidad de uso</td>
    <td colspan="1" valign="top">AgriWebb se enfoca en marketing digital dirigido, destacando casos de éxito y la optimización de la producción como sus principales atractivos</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Ofrece un software integral para la gestión de la salud animal, con seguimiento de tratamientos, vacunaciones y monitoreo en tiempo real, junto con soporte técnico continuo y actualizaciones regulares.</td>
    <td colspan="1" valign="top">Ofrece una plataforma integral para el monitoreo de cultivos, gestión de suelos y recursos, incluyendo herramientas de planificación y análisis agrícola.</td>
    <td colspan="1" valign="top">Proporciona una aplicación que permite el registro y monitoreo del ganado, facilitando el cumplimiento de normativas y optimizando la productividad.</td>
    <td colspan="1" valign="top">Ofrece un software de gestión de ganado que permite a los agricultores rastrear y optimizar cada aspecto de la producción ganadera</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">Modelo freemium con una versión básica gratuita y una membresía premium que desbloquea todas las funcionalidades avanzadas, disponible con planes mensuales o anuales.</td>
    <td colspan="1" valign="top">Funciona bajo un modelo de suscripción, con diferentes niveles de servicio dependiendo del tamaño de la operación agrícola y las funcionalidades requeridas.</td>
    <td colspan="1" valign="top">Ofrece un modelo de suscripción con diferentes planes basados en la cantidad de ganado y las necesidades específicas de la granja.</td>
    <td colspan="1" valign="top">Funciona bajo un modelo de suscripción, con planes que varían según la cantidad de ganado y las funcionalidades adicionales requeridas</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">La plataforma está disponible tanto en web como en dispositivos móviles, garantizando accesibilidad y monitoreo desde cualquier lugar.</td>
    <td colspan="1" valign="top">Disponible tanto en web como en dispositivos móviles, permitiendo a los agricultores acceder a sus datos y gestionar sus operaciones desde cualquier lugar.</td>
    <td colspan="1" valign="top">Disponible tanto en web como en aplicaciones móviles, lo que permite a los usuarios registrar datos y monitorear el ganado en tiempo real desde cualquier lugar.</td>
    <td colspan="1" valign="top">Disponible en plataformas web y móviles, asegurando que los agricultores puedan gestionar sus operaciones ganaderas en tiempo real desde cualquier dispositivo.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Integración total de datos en tiempo real, enfoque preventivo para evitar problemas de salud animal, y accesibilidad desde múltiples dispositivos.</td>
    <td colspan="1" valign="top">Su enfoque integral en la gestión de recursos agrícolas y su capacidad para ofrecer análisis avanzados hacen de FarmLogs una herramienta poderosa para grandes agricultores</td>
    <td colspan="1" valign="top">Su capacidad para asegurar la conformidad regulatoria y su enfoque en la trazabilidad lo hace indispensable para granjas que necesitan cumplir con estrictas normativas.</td>
    <td colspan="1" valign="top">Su enfoque en la trazabilidad y la optimización de la producción permite a los usuarios maximizar la eficiencia y la rentabilidad de sus operaciones ganaderas</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Falta de reconocimiento inicial en el mercado y una posible curva de aprendizaje para usuarios menos familiarizados con la tecnología</td>
    <td colspan="1" valign="top">Puede no ser la mejor opción para pequeñas granjas o operaciones que se centran exclusivamente en la ganadería.</td>
    <td colspan="1" valign="top">Puede ser menos atractivo para agricultores que buscan una solución más completa que incluya otros aspectos de la gestión agrícola</td>
    <td colspan="1" valign="top">Puede ser menos útil para agricultores que buscan una solución más amplia que incluya la gestión de cultivos o recursos agrícolas además del ganado</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Creciente digitalización en el sector agropecuario y posibilidad de expansión internacional en mercados con necesidades similares</td>
    <td colspan="1" valign="top">Expansión en mercados internacionales con un enfoque en la agricultura de precisión y la adopción de tecnologías avanzadas</td>
    <td colspan="1" valign="top">Expansión en mercados donde las regulaciones son estrictas, pero la adopción tecnológica es baja, lo que crea una gran necesidad de soluciones como Herdwatch.</td>
    <td colspan="1" valign="top">Adopción en mercados emergentes donde la trazabilidad del ganado se está volviendo un requisito esencial, pero las herramientas tecnológicas aún son limitadas.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competidores que ofrecen soluciones más integradas que combinan el manejo de ganado con otras funciones agrícolas</td>
    <td colspan="1" valign="top">Competencia de otras plataformas de gestión agrícola que ofrecen herramientas más específicas para el manejo de ganado o integraciones más profundas con maquinaria agrícola</td>
    <td colspan="1" valign="top">Competidores que ofrecen soluciones más integradas que combinan el manejo de ganado con otras funciones agrícolas</td>
    <td colspan="1" valign="top">Competencia de soluciones más generalizadas que ofrecen una gama más amplia de funcionalidades, incluyendo la integración de cultivos y gestión de recursos.</td>
  </tr>
</table>

### 2.1.2 Estrategias y tácticas frente a competidores  

- *Diferenciación de la plataforma:* 
#### Ofrecer funcionalidades específicas para la gestión y monitoreo detallado de la salud animal, como alertas personalizadas para tratamientos y vacunas, así como integración con dispositivos de monitoreo en tiempo real. Esto permitirá a la startup destacarse frente a competidores que pueden tener un enfoque más generalista o menos especializado en ganadería.
- *Comunidad activa:* 
#### Construir y fomentar una comunidad de usuarios mediante foros en línea, grupos en redes sociales y eventos educativos. Promover la interacción entre usuarios para compartir mejores prácticas y experiencias puede mejorar la fidelidad y el compromiso, al mismo tiempo que proporciona retroalimentación valiosa para el desarrollo continuo del producto.
- *Marketing dirigido:* 
#### Implementar campañas de marketing dirigidas a productores agropecuarios específicos y veterinarios mediante la segmentación en redes sociales, publicaciones en revistas especializadas y asistencia a eventos del sector. Aprovechar los datos demográficos y las necesidades específicas del mercado objetivo para diseñar mensajes personalizados y efectivos.
- *Monetización creativa:*
#### Ofrecer un modelo de suscripción con diferentes niveles de membresía que proporcionen acceso a funciones exclusivas, soporte prioritario y capacitación adicional. Además, explorar opciones como servicios de consultoría personalizada o módulos adicionales que puedan ser adquiridos a la carta, brindando flexibilidad y valor añadido a los clientes.

## 2.2 Entrevistas  
En esta sección se han definido todas las preguntas que se plantearan en el momento de
realizar las preguntas a los diferentes segmentos objetivos

### 2.2.1 Diseño de entrevistas  


#### 1. Contexto Inicial – Gestión y monitoreo de animales

**1.1** ¿Cómo gestionas actualmente la salud y el bienestar de tus animales?
→ ¿Usas herramientas específicas o métodos tradicionales? (Registros en papel, Excel, software especializado)

**1.2** ¿Qué tan frecuente realizas un seguimiento del estado de salud de tus animales?
→ ¿Qué información consideras más importante monitorear?

#### 2. Motivaciones y deseos

**2.1** ¿Qué mejoras te gustaría implementar en la gestión de tus animales?
→ (Por ejemplo: reducir costos, optimizar tratamientos, mejorar la productividad)

**2.2** ¿Qué tan importante es para ti contar con datos en tiempo real sobre tus animales?
→ ¿Por qué?

#### 3. Sentimientos y frustraciones

**3.1** ¿Te ha pasado que pierdes información crítica sobre tus animales?
→ ¿Cómo te afecta esto en tu trabajo diario?

**3.2** ¿Qué dificultades encuentras al gestionar múltiples registros de animales?
→ ¿Qué impacto tienen estas dificultades en la salud de los animales y en tu productividad?

#### 4. Presentación de la Solución – FarmGuard

**4.1** ¿Qué te parece la idea de tener un sistema que automatice el monitoreo y registro de la salud de tus animales?
→ ¿Te suena útil o innecesario para ti en este momento?

**4.2** ¿Preferirías que el sistema te ofrezca reportes simples y directos, o con gráficos interactivos y análisis predictivos? ¿Por qué?

**4.3** ¿Te interesa recibir alertas preventivas sobre posibles problemas de salud en tus animales? ¿Por qué?

#### 5. Cierre – Evaluación personal

**5.1** De acuerdo a lo visto y hablado anteriormente:
→ ¿Qué características de FarmGuard te llamaron más la atención?

**5.2** Imagina que usas FarmGuard todos los días por seis meses:
→ ¿Qué cambios crees que notarías en la gestión y productividad de tu granja o veterinaria?


### 2.2.2 Registro de entrevistas  

### 2.2.3 Análisis de entrevistas  

## 2.3 Needfinding  

### 2.3.1 User Personas  

Se realiza un análisis de las respuestas brindadas por nuestros entrevistados, dividiéndose en los 2 segmentos definidos anteriormente por el equipo de trabajo.

*SEGMENTO 1: Cuidadores de animales en terrenos de productores agropecuarios*

![imagen de criaderos](/Assets/img/ChapterIII/Alejandra%20Garcia%20Gutierrez%20(2).png)

*SEGMENTO 2: Veterinarias*

<img src="Assets/img/ChapterIII/UserPersona1.png" alt="UP2">  

### 2.3.2 User Task Matrix  

A continuación se pueden apreciar los User Task Matrix de los segmentos objetivos.

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <td></td>
        <td colspan=2>
            <b>User Persona</b>
        </td>
    </tr>
    <tr>
        <td></td>
        <td colspan=2>
            Segmento Objetivo: Cuidadores de animales en terrenos de productores agropecuarios <br> <b></b> 
        </td>
    </tr>
    <tr>
        <td>
            <b>Task</b>
        </td>
        <td>
            <b>Frequency</b>
        </td>
        <td>
            <b>Importance</b>
        </td>
    </tr>
    <tr>
        <td>
            Tener información sobre los animales que se disponen
        </td>
        <td>
            Always
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Registrar novedades rápidas en el animal cuidado
        </td>
        <td>
            Sometimes
        </td>
        <td>
            Medium
        </td>
    </tr>
    <tr>
        <td>
            Registrar recetas de medicamentos
        </td>
        <td>
            Sometimes
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Gestión de dieta de animales
        </td>
        <td>
            Usually
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Consultar las guías/tutoriales de la aplicación
        </td>
        <td>
            Rarely
        </td>
        <td>
            Low
        </td>
    </tr>
    <tr>
        <td>
            Registro de costos operativos en la granja o terreno
        </td>
        <td>
            Usually
        </td>
        <td>
            High
        </td>
    </tr>
  </thead>
</table>

</br></br>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <td></td>
        <td colspan=2>
            <b>User Persona</b>
        </td>
    </tr>
    <tr>
        <td></td>
        <td colspan=2>
            Segmento Objetivo: Veterinarias<br> <b></b>  
        </td>
    </tr>
    <tr>
        <td>
            <b>Task</b>
        </td>
        <td>
            <b>Frequency</b>
        </td>
        <td>
            <b>Importance</b>
        </td>
    </tr>
    <tr>
        <td>
            Registro de la historia clínica del animal
        </td>
        <td>
            Always
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Gestión de vacunación del animal
        </td>
        <td>
            Always
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Programación de citas médicas y revisiones
        </td>
        <td>
            Sometimes
        </td>
        <td>
            High
        </td>
    </tr>
  </thead>
</table>

</br></br>

### 2.3.3 User Journey Mapping  

A continuación se pueden apreciar los User Journey Mapping de los segmentos objetivos.

*Cuidadores de animales en terrenos de productores agropecuarios*

<img src="Assets/img/ChapterIII/journey1.PNG" alt="journ1">  

*Veterinarias*

<img src="Assets/img/ChapterIII/journey-2.PNG" alt="journ2">  


### 2.3.4 Empathy Mapping  

A continuación se pueden apreciar los Empathy Mapping de los segmentos objetivos.

*Cuidadores de animales en terrenos de productores agropecuarios*
<img src="Assets/img/ChapterIII/empathy1.PNG" alt="empa1">

*Veterinarias*
<img src="Assets/img/ChapterIII/empathy2.PNG" alt="empa2">

## 2.4 Big Picture EventStorming  


## 2.5 Ubiquitous Language  

Este será el lenguaje que se utilizará para distintos elementos de la aplicación que encapsulan distintas funciones o permiten un mejor reconocimiento del significado.

***User:*** Professional animal caretaker looking for an animal management and control app

***User:*** Veterinarian with medical history record issues

***Member:*** User part of the premium membership that has different benefits

***Membership:*** Subscription that allows you to unlock benefits that will improve the user experience of the application

***Medical Record:*** Document that records all of an animal's medical history

***Management:*** Total animal control, with each of the elements that make up the application

Implementation example: When a **user** acquires a **membership**, he unlocks different benefits for being an exclusive **member** of the application.

---

# Capítulo III: Requirements Specification  

## 3.1 User Stories  

En la sección de historias de usuarios, detallaremos las diversas necesidades y requerimientos de nuestros usuarios y veterinarios. Cada historia de usuario representará un escenario o una función que la plataforma debe proporcionar para cumplir con nuestro objetivo principal: ofrecer una solución completa para la gestión de la salud animal.

Proporcionar a los usuarios herramientas efectivas para el monitoreo, registro y análisis de la salud de los animales en granjas y clínicas veterinarias es el objetivo principal. Esto permitirá a los dueños de granjas y veterinarios tomar decisiones informadas y reducir los riesgos asociados con la salud animal. Al detallar estas historias de usuario, podremos comprender mejor cómo la plataforma satisfará las necesidades de ambos grupos y ofrecer una solución completa y eficiente para la administración de la salud de los animales.

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Nombre del Epic</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-01</td>
      <td>Gestión de la Granja</td>
      <td>Digitalización y monitoreo de los animales, incluyendo registros, indicadores, sensores y control sanitario.</td>
    </tr>
    <tr>
      <td>EP-02</td>
      <td>Optimización de Recursos</td>
      <td>Gestión eficiente de insumos, visualización en mapas y delimitación de áreas para mejorar el uso de recursos.</td>
    </tr>
    <tr>
      <td>EP-03</td>
      <td>Notificaciones y Alertas</td>
      <td>Recepción de notificaciones y alertas inmediatas ante cambios en la información o emergencias de salud animal.</td>
    </tr>
    <tr>
      <td>EP-04</td>
      <td>Identidad y Acceso</td>
      <td>Registro, autenticación e inicio de sesión seguro de usuarios con validación institucional.</td>
    </tr>
    <tr>
      <td>EP-05</td>
      <td>Gestión de Perfiles de Usuario</td>
      <td>Creación, visualización y actualización de perfiles de usuarios para garantizar confianza y transparencia.</td>
    </tr>
    <tr>
      <td>EP-06</td>
      <td>Landing Page</td>
      <td>Diseño de la página de aterrizaje para mostrar beneficios, funcionalidades, testimonios y permitir contacto.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción (User Story)</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <!-- EP-01: Gestión de la Granja -->
    <tr>
      <td>EP-01-US01</td>
      <td>Gestión digital de los animales</td>
      <td>Como productor agropecuario quiero registrar y actualizar digitalmente mis animales para acceder a su información en cualquier dispositivo.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que el usuario está autenticado, Cuando agrega un nuevo animal con todos los datos requeridos, Entonces el sistema guarda el registro y lo muestra en la lista.<br>
        <strong>Escenario 2:</strong> Dado un animal registrado, Cuando edita sus datos, Entonces el sistema actualiza la información y confirma el cambio.
      </td>
      <td>EP-01 – Gestión de la Granja</td>
    </tr>
    <tr>
      <td>EP-01-US02</td>
      <td>Monitoreo de indicadores clave</td>
      <td>Como productor agropecuario quiero ver en tiempo real indicadores como temperatura y peso para tomar decisiones informadas sobre mi ganado.</td>
      <td>
        <strong>Escenario 1:</strong> Dado sensores conectados, Cuando el usuario abre el panel de monitoreo, Entonces se muestran los indicadores en tiempo real.<br>
        <strong>Escenario 2:</strong> Dado que un sensor falla, Cuando no envía datos, Entonces se muestra un mensaje “Sensor sin datos”.
      </td>
      <td>EP-01 – Gestión de la Granja</td>
    </tr>
    <tr>
      <td>EP-01-US03</td>
      <td>Integración con equipos y sensores</td>
      <td>Como productor agropecuario quiero conectar sensores y dispositivos a la plataforma para automatizar el monitoreo del ganado.</td>
      <td>
        <strong>Escenario 1:</strong> Dado sensores configurados, Cuando se conectan a la plataforma, Entonces los datos se actualizan automáticamente.<br>
        <strong>Escenario 2:</strong> Dado reglas predefinidas, Cuando ocurre un evento (p. ej., vacunación), Entonces la acción se registra automáticamente.
      </td>
      <td>EP-01 – Gestión de la Granja</td>
    </tr>
    <tr>
      <td>EP-01-US04</td>
      <td>Gestión digital de vacunas del ganado</td>
      <td>Como productor agropecuario quiero registrar y consultar las vacunas aplicadas a mis animales para llevar control sanitario de la granja.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un animal registrado, Cuando el usuario agrega una vacuna con fecha y tipo, Entonces se guarda en el historial.<br>
        <strong>Escenario 2:</strong> Dado que la fecha de revacunación se acerca, Cuando faltan 7 días, Entonces se envía una notificación automática.
      </td>
      <td>EP-01 – Gestión de la Granja</td>
    </tr>
    <!-- EP-02: Optimización de Recursos -->
    <tr>
      <td>EP-02-US01</td>
      <td>Gestión de insumos para los animales</td>
      <td>Como productor agropecuario quiero registrar insumos como alimento y medicinas para optimizar el uso y evitar desabastecimiento.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que el usuario registra un nuevo insumo, Cuando guarda los datos, Entonces se actualiza el inventario.<br>
        <strong>Escenario 2:</strong> Dado que un insumo alcanza nivel crítico, Cuando se detecta, Entonces se muestra alerta “Stock bajo”.
      </td>
      <td>EP-02 – Optimización de Recursos</td>
    </tr>
    <tr>
      <td>EP-02-US02</td>
      <td>Visualización de animales en un mapa</td>
      <td>Como productor agropecuario quiero ver la ubicación de mis animales en un mapa móvil para supervisar su distribución.</td>
      <td>
        <strong>Escenario 1:</strong> Dado animales con dispositivos de geolocalización, Cuando el usuario abre el mapa, Entonces se muestran sus ubicaciones en tiempo real.<br>
        <strong>Escenario 2:</strong> Dado que un animal no envía señal, Cuando no aparece en el mapa, Entonces se muestra “Animal sin localización”.
      </td>
      <td>EP-02 – Optimización de Recursos</td>
    </tr>
    <tr>
      <td>EP-02-US03</td>
      <td>Delimitar área de los animales (móvil)</td>
      <td>Como productor agropecuario quiero definir áreas de movimiento para mis animales y recibir alertas si salen de la zona.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que el usuario define un polígono en el mapa, Cuando guarda el área, Entonces se activa la supervisión.<br>
        <strong>Escenario 2:</strong> Dado un animal registrado en el área, Cuando cruza el límite, Entonces el sistema envía alerta inmediata al móvil.
      </td>
      <td>EP-02 – Optimización de Recursos</td>
    </tr>
    <!-- EP-03: Notificaciones y Alertas -->
    <tr>
      <td>EP-03-US01</td>
      <td>Notificaciones por cambios en información</td>
      <td>Como productor agropecuario quiero recibir notificaciones cuando se actualicen datos relevantes de mis animales para mantenerme informado.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que un animal cambia de estado, Cuando se actualiza su información, Entonces se envía una notificación al usuario.<br>
        <strong>Escenario 2:</strong> Dado que el usuario desactiva notificaciones, Cuando ocurre un cambio, Entonces no se envía alerta.
      </td>
      <td>EP-03 – Notificaciones y Alertas</td>
    </tr>
    <tr>
      <td>EP-03-US02</td>
      <td>Alertas de emergencia por salud animal</td>
      <td>Como productor agropecuario quiero recibir alertas inmediatas cuando un animal presente anomalías para tomar acciones rápidas.</td>
      <td>
        <strong>Escenario 1:</strong> Dado sensores conectados, Cuando se detecta una anomalía (p. ej., fiebre), Entonces el sistema envía alerta al dispositivo.<br>
        <strong>Escenario 2:</strong> Dado que se recibe alerta, Cuando el usuario la abre, Entonces se muestran pasos recomendados para atender al animal.
      </td>
      <td>EP-03 – Notificaciones y Alertas</td>
    </tr>
    <!-- EP-04: Identidad y Acceso -->
    <tr>
      <td>EP-04-US01</td>
      <td>Inicio de sesión</td>
      <td>Como usuario quiero iniciar sesión con mis credenciales para acceder de forma segura a la plataforma.</td>
      <td>
        <strong>Escenario 1:</strong> Dado usuario en la vista de login, Cuando ingresa credenciales válidas, Entonces accede al dashboard.<br>
        <strong>Escenario 2:</strong> Dado credenciales inválidas, Cuando intenta ingresar, Entonces se muestra “Credenciales incorrectas”.
      </td>
      <td>EP-04 – Identidad y Acceso</td>
    </tr>
    <tr>
      <td>EP-04-US02</td>
      <td>Creación de cuenta</td>
      <td>Como usuario quiero registrarme con mi correo institucional para garantizar que solo miembros autorizados accedan.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que el correo termina en “.edu”, Cuando se valida, Entonces se envía invitación de confirmación.<br>
        <strong>Escenario 2:</strong> Dado correo inválido, Cuando intenta registrarse, Entonces se muestra “Debe usar correo institucional”.
      </td>
      <td>EP-04 – Identidad y Acceso</td>
    </tr>
    <!-- EP-05: Gestión de Perfiles -->
    <tr>
      <td>EP-05-US01</td>
      <td>Completar perfil de usuario</td>
      <td>Como usuario quiero completar mi perfil con datos personales y académicos para generar confianza en la plataforma.</td>
      <td>
        <strong>Escenario 1:</strong> Dado correo validado, Cuando completa todos los campos obligatorios, Entonces el perfil se guarda.<br>
        <strong>Escenario 2:</strong> Dado campos faltantes, Cuando intenta guardar, Entonces se muestra “Faltan datos”.
      </td>
      <td>EP-05 – Gestión de Perfiles</td>
    </tr>
    <tr>
      <td>EP-05-US02</td>
      <td>Visualizar y editar mi perfil</td>
      <td>Como usuario quiero visualizar y actualizar mi perfil para mantener mi información precisa y actualizada.</td>
      <td>
        <strong>Escenario 1:</strong> Dado usuario autenticado, Cuando abre perfil, Entonces se muestran sus datos actuales.<br>
        <strong>Escenario 2:</strong> Dado cambios válidos, Cuando los guarda, Entonces el perfil se actualiza y confirma.
      </td>
      <td>EP-05 – Gestión de Perfiles</td>
    </tr>
    <!-- EP-06: Landing Page -->
    <tr>
      <td>EP-06-US37</td>
      <td>Explorar sección “Beneficios”</td>
      <td>Como visitante quiero explorar la sección de beneficios en la landing page para conocer las ventajas de usar la app.</td>
      <td>
        <strong>Escenario 1:</strong> Dado visitante en desktop, Cuando hace clic en “Beneficios”, Entonces la página desplaza a la sección y muestra íconos y descripciones.<br>
        <strong>Escenario 2:</strong> Dado visitante en móvil, Cuando abre el menú hamburguesa y selecciona “Beneficios”, Entonces se carga la sección correctamente.
      </td>
      <td>EP-06 – Landing Page</td>
    </tr>
    <tr>
      <td>EP-06-US39</td>
      <td>Ver sección “Sobre la App” y “Videos”</td>
      <td>Como visitante quiero ver la sección “Sobre la App” y reproducir videos para entender mejor el producto antes de usarlo.</td>
      <td>
        <strong>Escenario 1:</strong> Dado visitante desplaza la página, Cuando llega a “Sobre la App”, Entonces se muestra el texto descriptivo.<br>
        <strong>Escenario 2:</strong> Dado visitante en la sección “Videos”, Cuando hace clic en una miniatura, Entonces el video se reproduce en modal.
      </td>
      <td>EP-06 – Landing Page</td>
    </tr>
    <tr>
      <td>EP-06-US40</td>
      <td>Botones de descarga</td>
      <td>Como visitante quiero disponer de botones visibles de descarga (App Store y Play Store) para instalar la app fácilmente.</td>
      <td>
        <strong>Escenario 1:</strong> Dado visitante en la landing page, Cuando carga la sección final, Entonces se muestran botones claros de descarga.<br>
        <strong>Escenario 2:</strong> Dado visitante hace clic en el botón correspondiente, Cuando se procesa, Entonces redirige a la tienda correcta.
      </td>
      <td>EP-06 – Landing Page</td>
    </tr>
    <tr>
      <td>EP-06-US42</td>
      <td>Ver sección FAQ</td>
      <td>Como visitante quiero consultar la sección de preguntas frecuentes para resolver mis dudas comunes sin buscar soporte.</td>
      <td>
        <strong>Escenario 1:</strong> Dado visitante en desktop, Cuando expande una pregunta, Entonces se despliega la respuesta.<br>
        <strong>Escenario 2:</strong> Dado visitante en móvil, Cuando selecciona una pregunta, Entonces se despliega con animación suave.
      </td>
      <td>EP-06 – Landing Page</td>
    </tr>
    <tr>
      <td>EP-06-US43</td>
      <td>Formulario de contacto</td>
      <td>Como visitante quiero usar el formulario de contacto para enviar preguntas y recibir respuesta del equipo.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que el visitante completa los campos requeridos, Cuando pulsa “Enviar”, Entonces se muestra confirmación.<br>
        <strong>Escenario 2:</strong> Dado campos vacíos, Cuando pulsa “Enviar”, Entonces se resaltan y muestra “Por favor completa los campos”.
      </td>
      <td>EP-06 – Landing Page</td>
    </tr>
    <tr>
      <td>EP-06-US44</td>
      <td>Ver sección “Equipo”</td>
      <td>Como visitante quiero conocer al equipo detrás de la app para confiar en la profesionalidad del proyecto.</td>
      <td>
        <strong>Escenario 1:</strong> Dado visitante en desktop, Cuando llega a la sección “Equipo”, Entonces se muestran fotos, nombres y roles.<br>
        <strong>Escenario 2:</strong> Dado visitante en móvil, Cuando hace scroll, Entonces las tarjetas se ajustan correctamente a la pantalla.
      </td>
      <td>EP-06 – Landing Page</td>
    </tr>
  </tbody>
</table>





## 3.2 Impact Mapping  

La sección de Impact Mapping analizará las consecuencias más amplias y los objetivos estratégicos que buscamos lograr con la implementación de esta aplicación. En lugar de concentrarnos en detalles técnicos o funcionalidades específicas, el Impact Mapping nos ayudará a comprender cómo funciona.

Nuestro proyecto ayudará a lograr objetivos más grandes y cómo tendrá un impacto positivo en varios grupos de interés. Este Impact Mapping nos ayudará a identificar cómo las características de la aplicación se relacionan con los resultados deseados, lo que nos permitirá tomar decisiones informadas sobre qué aspectos priorizar y cómo medir el éxito a largo plazo.


![Impact Mapping](/Assets/img/ChapterIII/Impact_Mapping.png)


## 3.3 Product Backlog  

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 28%" />
<col style="width: 14%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th>#Orden</th>
<th>User Story ID</th>
<th>Titulo</th>
<th>Descripcion</th>
<th>Prioridad</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td>1</td>
<td>E1-US01</td>
<td>Gestión digital de la granja</td>
<td><p><strong>Como</strong> productor agropecuario familiarizado con la tecnología,</p>
<p><strong>quiero</strong> digitalizar la gestión de mis animales</p>
<p><strong>para</strong> poder acceder a toda la información desde cualquier dispositivo y agilizar mis operaciones.</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>2</td>
<td>E1-US02	</td>
<td>Monitoreo de indicadores clave</td>
<td><p><strong>Como</strong> productor agropecuario con expriencia tecnológica,</p>
<p><strong>quiero</strong> monitorear indicadores clave de salud de los animales en tiempo real.</p>
<p><strong>para</strong> tomar decisiones más informadas y mejorar la productividad de mi granja.</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>3</td>
<td>E1-US03	</td>
<td>Integración con Equipos y Sensores</td>
<td><p><strong>Como</strong> productor agropecuario interesado en la innovación,</p>
<p><strong>quiero</strong> integrar la plataforma con sensores y dispositivos en mi granja</p>
<p><strong>para</strong> automatizar el monitoreo de la salud de los animales y reducir la intervención manual.</p></td>
<td>Alta</td>
<td>13</td>
</tr>


<tr class="even">
<td>4</td>
<td>E2-US01</td>
<td>Herramientas de aprendizaje</td>
<td><p><strong>Como</strong> productor agropecuario con poca capacitación,</p>
<p><strong>quiero</strong> acceder a recursos educativos dentro de la plataforma</p>
<p><strong>para</strong> aprender más sobre la gestión efectiva de mi granja y mejorar el bienestar de mis animales.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="odd">
<td>5</td>
<td>E2-US02</td>
<td>Simplificación de tareas</td>
<td><p><strong>Como</strong> productor agropecuario sin experiencia tecnológica,</p>
<p><strong>quiero</strong> que la aplicación tenga una interfaz sencilla y fácil de usar</p>
<p><strong>para</strong> poder gestionar mi granja sin necesidad de conocimientos avanzados en tecnología.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="even">
<td>6</td>
<td>E2-US03</td>
<td>Guia Paso a Paso</td>
<td><p><strong>Como</strong> productor agropecuario que no ha recibido capacitacion,</p>
<p><strong>quiero</strong> seguir un proceso guiado paso a paso</p>
<p><strong>para</strong> registrar el estado de mis animales y recibir recomendaciones automáticas sobre sus cuidados, sin necesidad de entender términos complejos.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="odd">
<td>7</td>
<td>E3-US01</td>
<td>Predicción de necesidades alimenticias</td>
<td><p><strong>Como</strong> productor agropecuario interesado en en mejorar productividad y la salud del ganado,</p>
<p><strong>quiero</strong> que la plataforma ofresca predicciones de necesidades alimenticias basandose en las características del animal</p>
<p><strong>para</strong> poder optimizar el uso de los recursos disponibles y asegurar la salud de los animales.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="even">
<td>8</td>
<td>E3-US02</td>
<td>Alertas de emergencia por salud animal</td>
<td><p><strong>Como</strong> productor agropecuario interesado en la salud de mis animales,</p>
<p><strong>Quiero</strong> recibir alertas caundo alguno de mis animales presente anomalías en su salud</p>
<p><strong>Para</strong> poder tomar las acciones necesarias en la salud de mis animales</p>
</td>
<td>Alta</td>
<td>13</td>
</tr>


<tr class="odd">
<td>9</td>
<td>E4-US01</td>
<td>Gestión de inventarios de insumos</td>
<td><p><strong>Como</strong> productor agropecuario que desea tener control preciso de los insumos de la granja,</p>
<p><strong>Quiero</strong> gestionar el inventario de los insumos (alimentos, medicinas, etc) dentro de la plataforma</p>
<p><strong>para</strong> poder tener un mejor manejo de los recursos disponibles y evitar desabastecimiento.</p></td>
<td>Alta</td>
<td>8</td>
</tr>

<tr class="even">
<td>10</td>
<td>E4-US02</td>
<td>Planificacion de actividades agricolas</td>
<td><p><strong>Como</strong> productor agropecuario con actividades programadas,</p>
<p><strong>Quiero</strong> planificar las actividades diarias de mi granja (limpieza, alimentacion, vacunacion, etc.) dentro de la plataforma</p>
<p><strong>para</strong> poder garantizar un mejor manejo del tiempo para realizar exitosamente todas las actividades diarias.</p></td>
<td>Media</td>
<td>5</td>
</tr>
</table>

---

# Capítulo IV: Solution Software Design  

## 4.1 Strategic-Level Domain-Driven Design  

### 4.1.1 Design-Level EventStorming  

#### 4.1.1.1 Candidate Context Discovery  

#### 4.1.1.2 Domain Message Flows Modeling  

#### 4.1.1.3 Bounded Context Canvases  

### 4.1.2 Context Mapping  

### 4.1.3 Software Architecture  

#### 4.1.3.1 Software Architecture System Landscape Diagram  

#### 4.1.3.2 Software Architecture Context Level Diagrams  

#### 4.1.3.3 Software Architecture Container Level Diagrams  

#### 4.1.3.4 Software Architecture Deployment Diagrams  

## 4.2 Tactical-Level Domain-Driven Design  


### 4.2.X Bounded Context: <Bounded Context Name>  

#### 4.2.X.1 Domain Layer  

#### 4.2.X.2 Interface Layer  

#### 4.2.X.3 Application Layer  

#### 4.2.X.4 Infrastructure Layer  

#### 4.2.X.5 Bounded Context Software Architecture Component Level Diagrams  

#### 4.2.X.6 Bounded Context Software Architecture Code Level Diagrams  

##### 4.2.X.6.1 Bounded Context Domain Layer Class Diagrams  

##### 4.2.X.6.2 Bounded Context Database Design Diagram  

---

# Capítulo V: Solution UI/UX Design  

## 5.1 Style Guidelines  

### 5.1.1 General Style Guidelines  

### 5.1.2 Web, Mobile and IoT Style Guidelines  

## 5.2 Information Architecture  

### 5.2.1 Organization Systems  

### 5.2.2 Labeling Systems  

### 5.2.3 SEO Tags and Meta Tags  

### 5.2.4 Searching Systems  

### 5.2.5 Navigation Systems  

## 5.3 Landing Page UI Design  

### 5.3.1 Landing Page Wireframe  

### 5.3.2 Landing Page Mock-up  

## 5.4 Applications UX/UI Design  

### 5.4.1 Applications Wireframes  

### 5.4.2 Applications Wireflow Diagrams  

### 5.4.3 Applications Mock-ups  

### 5.4.4 Applications User Flow Diagrams  

## 5.5 Applications Prototyping  

---

# Capítulo VI: Product Implementation, Validation & Deployment  

## 6.1 Software Configuration Management  

### 6.1.1 Software Development Environment Configuration  

### 6.1.2 Source Code Management  

### 6.1.3 Source Code Style Guide & Conventions  

### 6.1.4 Software Deployment Configuration  

## 6.2 Landing Page, Services & Applications Implementation  

### 6.2.1 Sprint 1  

#### 6.2.1.1 Aspect Leaders and Collaborators  

#### 6.2.1.2 Sprint Backlog 1  

#### 6.2.1.3 Development Evidence for Sprint Review  

#### 6.2.1.4 Testing Suite Evidence for Sprint Review  

#### 6.2.1.5 Execution Evidence for Sprint Review  

#### 6.2.1.6 Services Documentation Evidence for Sprint Review  

#### 6.2.1.7 Software Deployment Evidence for Sprint Review  

#### 6.2.1.8 Team Collaboration Insights during Sprint  

#### 6.2.1.9 Validation Interviews  






## 6.3 Validation Interviews

A continuacion se muetras las Validation Interviews son ...

### 6.3.1. Diseño de Entrevistas

###  Segmento 1

###  Segmento 2


### 6.3.2. Registro de Entrevistas

A continuación se presentan los registros de las entrevistas realizadas a...

**Segmento1:**

Entrevista 1: 

Edad: 

Departamento: 

![Entrevista 1]()

Enlace: https://acortar.link/oE3tjw

Resumen:


**Segmento 2:**

Entrevista 1:  

Edad:  años

![Interview2]()

Enlace: https://acortar.link/OAlrEE

Resumen:



### 6.3.3. Evaluaciones segun heuristicas

<p align="center">
  <strong>UX Heuristics & Principles Evaluation</strong><br>
  <em>Usability – Inclusive Design – Information Architecture</em>
</p>

**CARRERA**: Ingeniería de Software  
**CURSO**: Desarrollo de Soluciones IoT  
**SECCIÓN**: 
**PROFESORES**:   
**AUDITOR**:  
**CLIENTE(S)**: 

---

**SITE o APP A EVALUAR**:  – Plataforma de gestión agrícola 

## TAREAS A EVALUAR:

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas en el sistema :

1. Registro de un agricultor en la plataforma (Web y Mobile)


No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Integración con módulos externos de analisis climática


## ESCALA DE SEVERIDAD:

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

| Nivel | Descripción |
|-------|-------------|
| **1** | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a menos que haya tiempo disponible. |
| **2** | Problema menor: ocurre con algo más de frecuencia o es un poco más difícil de resolver para el usuario. Debería corregirse con baja prioridad en la siguiente versión. |
| **3** | Problema mayor: ocurre con frecuencia o el usuario no puede resolverlo. Es importante corregirlo con alta prioridad. |
| **4** | Problema muy grave: impide al usuario continuar usando la herramienta. Debe corregerse antes del despliegue. |

## TABLA RESUMEN DE PROBLEMAS DETECTADOS



### PROBLEMA #1: No hay un control que permita regresar al panel principal desde la gestión de sensores

**Severidad:** 3  
**Heurística violada:** 

**Problema:**  


**Recomendación:**  


**Evidencia visual:**  
![]()



## 6.4.Video About-the-Product



El video adopta un tono cercano, claro y profesional, coherente con la identidad visual de WaruSmart. Se presenta una visión general del sistema, incluyendo su modelo de negocio, arquitectura modular (web, móvil, backend y edge), así como ejemplos reales de uso.

📺 **Captura del video**  
![Screenshot del Video]()

🔗 **Enlaces del video**
- Versión publicada en **Microsoft Stream**:  
  []()

- Versión publicada en **YouTube** (para incrustar en el Landing Page):  
  []()

⏱️ **Duración del video**: 9 minutos y 56 segundos

---


## Conclusiones


## Recomendaciones


### 📸 Captura del video:
![Captura del equipo]()

### 🔗 Enlaces del video:

- 📺 Versión en Microsoft Stream (entorno institucional):  
  []()

- 📺 Versión pública en YouTube (para insertar en Landing Page):  
  []()

### ⏱️ Duración total del video:
**8 minutos con 9 segundos**

# 📚 Bibliografía



# 📎 Anexos

### 🎬 Videos de Exposición

| Enlace                                             | Entregable                       |
|----------------------------------------------------|----------------------------------|
|                                                    | TB1                              |
---

### 💻 Repositorios del Proyecto WaruSmart

- **Landing Page**  
  []()

- **Frontend Web App**  
  []()

- **Backend Web Services**  
  []()

- **Mobile Application (Android - Kotlin)**  
  []()



