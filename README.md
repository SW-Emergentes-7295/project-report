# <center>Informe del Trabajo Final</center>

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>1ASI0728 - Arquitecturas de Software Emergentes - 7295</strong><br>
    <strong>Profesor: Royer Edelwer Rojas Malasquez</strong><br>
    <br>INFORME FINAL
</p>

<center>

#### Startup: **HomeSense**
#### Product: **VisualGuide**

</center>

## Team  Members:

<div align="center">

|               Member                |    Code    |
| :---------------------------------: | :--------: |
| Rodriguez Vargas, Arian Martín  | U202212096 |
| Perez Pizarro, Pedro Jeremy  | U202022237 |
| More Rondon, Christopher Sebastian  | U202212199 |
| Ramos Najar, Tony Alexander  | U20211A153 |



</div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6">V1</td>
      <td>20/09/2025</td>
      <td>Ramos Najar, Tony Alexander</td>
      <td>
        <ul>
          <li>Antecedentes y Problemática</li>
          <li>User stories</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>20/09/2025</td>
      <td>More Rondon, Christopher Sebastian</td>
      <td>
        <ul>
          <li>Lean UX Process</li>
          <li>Product Backlog</li>
          <li>Ubiquitous Language</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>20/09/2025</td>
      <td>Perez Pizarro, Pedro Jeremy </td>
      <td>
        <ul>
          <li>User Journey Mapping</li>
          <li>Impact Mapping</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>20/09/2025</td>
      <td>Arian Martín Rodriguez Vargas</td>
      <td>
        <ul>
          <li>Análisis Competitivo</li>
          <li>Estrategias Frente a Competidores</li>
          <li>Empathy Mapping</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
  </tbody>
</table>

# Project Report Collaboration Insights

En esta sección, registraremos los cambios y logros que se completaron en cada entrega del reporte.

TB1
La entrega TB1 finalizó con éxito y están documentadas en el siguiente repositorio de Github perteneciente a la organización del equipo: https://github.com/SW-Emergentes-7295/project-report Durante el desarrollo del informe se tuvieron en cuenta los siguientes aspectos:

- Se definió la startup y el producto a desarrollar.
- Se establecieron los segmentos objetivo.
- Se aplicó el proceso de Lean UX para definir problem statements, assumptions e hipótesis.
- Se realizó un análisis competitivo de los principales competidores en el mercado.
- Se diseñaron entrevistas semiestructuradas para recolectar datos cualitativos.
- Se llevaron a cabo entrevistas con personas no videntes y sus cuidadores.
- Se crearon user personas para representar a los segmentos objetivo.
- Se desarrollaron user task matrix, empathy maps y as-is scenario maps para comprender mejor a los usuarios.
- Mediante el eventstorming se definió el ubiquitous language del dominio.
- Se establecieron las primeras versiones de la arquitectura del sistema.
- Se documentaron todas las actividades y hallazgos en el repositorio de Github.


Imagen 1: Gráfico general de commits y contribuciones hechas por cada miembros del equipo de VisualGuide. Incluye tambien los pull requests activos y aceptados. 
<img src="./images/pulse-tb1.PNG " alt="Gráfico de contribuciones del equipo" width="800">

<img src="./images/network-graph-tb1.PNG " alt="Gráfico de contribuciones del equipo" width="800">


# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Capítulo I: Introducción](#capítulo-i-introducción)
   * [1.1. Startup Profile](#11-startup-profile)
      + [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      + [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   * [1.2. Solution Profile](#12-solution-profile)
      + [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      + [1.2.2. Lean UX Process](#122-lean-ux-process)
         - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
         - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
         - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
         - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
   * [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-analysis)
   * [2.1. Competidores](#21-competidores)
      + [2.1.1. Análisis competitivo](#211-análisis-competitivo)
      + [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
   * [2.2. Entrevistas](#22-entrevistas)
      + [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      + [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
      + [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
   * [2.3. Needfinding](#23-needfinding)
      + [2.3.1. User Personas](#231-user-personas)
      + [2.3.2. User Task Matrix](#232-user-task-matrix)
      + [2.3.3. User Journey Mapping](#233-user-journey-mapping)
      + [2.3.4. Empathy Mapping](#234-empathy-mapping)
      + [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
   * [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
   * [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
   * [3.2. User Stories](#32-user-stories)
   * [3.3. Impact Mapping](#33-impact-mapping)
   * [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Domain-Driven Design](#capítulo-iv-strategic-level-domain-driven-design)
   * [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
      + [4.1.1. Design Purpose](#411-design-purpose)
      + [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
         - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
         - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
         - [4.1.2.3. Constraints](#4123-constraints)
      + [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
      + [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
      + [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
   * [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
      + [4.2.1. EventStorming](#421-eventstorming)
      + [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
      + [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
      + [4.2.4. Bounded Context Canvases](#424-bounded-context-canvas)
      + [4.2.5. Context Mapping](#425-context-mapping)
   * [4.3. Software Architecture](#43-software-architecture)
      + [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
      + [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
      + [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
      + [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)


# Student Outcome
En Ingeniería de Software, el logro de curso contribuye a alcanzar el:

ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

<table>
  <tr>
    <th>Criterio Especifico</th>
    <th>Acciones Realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Comunica oralmente sus ideas
y/o resultados con objetividad a
público de diferentes
especialidades y niveles
jerarquicos, en el marco del
desarrollo de un proyecto en
ingeniería.</td>
    <td></td>
        <td></td>

  </tr>

  <tr>
    <td>Comunica en forma escrita ideas
y/o resultados con objetividad a
público de diferentes
especialidades y niveles
jerarquicos, en el marco del
desarrollo de un proyecto en
ingeniería..</td>
      <td></td>
    <td></td>

  </tr>
</table>


# Capítulo I: Introducción
## 1.1. Startup Profile

A continuación, presentamos la startup <strong>“HomeSense”</strong>, dedicada a desarrollar soluciones tecnológicas de asistencia para personas con discapacidad visual, así como el equipo de desarrollo del producto, software presentado anteriormente, <strong>“VisualGuide”</strong>.

### 1.1.1. Descripción de la Startup

<p> 
      <strong>HomeSense</strong> es una startup tecnológica enfocada en crear soluciones inteligentes para mejorar la autonomía y seguridad de personas no videntes dentro del hogar. Nuestra misión es proporcionar herramientas que permitan a los usuarios interactuar con su entorno de manera segura y eficiente mediante el uso       de tecnologías avanzadas de inteligencia artificial. 
    </p> 
    <p> 
      El primer producto de HomeSense es <strong>"VisualGuide"</strong>, una aplicación móvil que funciona como un asistente visual inteligente para personas no videntes. La aplicación interpreta el entorno del hogar mediante IA, reconoce objetos, muebles, electrodomésticos, personas, textos y colores, y guía al usuario           en tiempo real según sus necesidades específicas. Para garantizar seguridad, la aplicación opera sobre un mapeo previo del hogar, realizado mediante fotografías y escaneos en un ambiente controlado, evitando riesgos asociados al uso en espacios públicos. 
    </p> 
      <h4><strong>Misión</strong></h4> 
      <p> Facilitar la autonomía y seguridad de personas no videntes dentro del hogar mediante soluciones inteligentes basadas en inteligencia artificial, que interpreten su entorno y guíen sus movimientos de forma precisa y confiable.
    </p>
      <h4><strong>Visión</strong></h4>
      <p> Ser líderes en América Latina en soluciones tecnológicas de asistencia para personas con discapacidad visual, ofreciendo productos innovadores que promuevan la independencia y seguridad dentro del hogar.
    </p>

### 1.1.2. Perfiles de integrantes del equipo

<img src="./images/team/1.png" alt="Foto del equipo de HomeSense" width="600">

<img src="./images/team/2.png" alt="Foto del equipo de HomeSense" width="600">

<img src="./images/team/3.png" alt="Foto del equipo de HomeSense" width="600">

<img src="./images/team/4.png" alt="Foto del equipo de HomeSense" width="600">

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

<div>
<h3>Antecedente</h3>
  <p>
    Hoy en día, las personas con discapacidad visual tienen muchos retos para moverse con seguridad y autonomía dentro de su propia casa. Aunque existen algunas herramientas de ayuda, muchas requieren contacto directo con el entorno o no están diseñadas para reconocer los detalles específicos de un hogar. Esto limita la independencia de los usuarios y aumenta el riesgo de accidentes domésticos.
  </p>

<h3>Problemática – Enfoque con las 5W + 2H</h3>
<ul>
    <li><strong>What?</strong> Las personas no videntes tienen problemas para reconocer y desplazarse dentro de su hogar de manera segura, lo que afecta su autonomía diaria.</li>   
    <li><strong>Why?</strong> Porque no cuentan con un asistente inteligente capaz de interpretar el entorno, identificar muebles, electrodomésticos, objetos o personas, y guiarlos de forma clara y en tiempo real según sus necesidades.</li> 
    <li><strong>Who?</strong> Personas con discapacidad visual que desean tener más independencia y sentirse seguras dentro de su casa.</li>
    <li><strong>When?</strong> En su vida cotidiana, al moverse entre habitaciones, usar electrodomésticos, o identificar personas y objetos en su hogar.</li>
    <li><strong>Where?</strong> Dentro del hogar, especialmente en casas con espacios complejos o muebles que puedan representar algún riesgo.</li>  
    <li><strong>How?</strong> Actualmente dependen de bastones, ayuda de otras personas o aplicaciones básicas que no ofrecen orientación contextualizada ni reconocimiento completo del entorno.</li>    
    <li><strong>How Much?</strong> La falta de herramientas adecuadas genera dependencia, riesgo de accidentes, estrés y sensación de inseguridad, afectando directamente su calidad de vida y la tranquilidad de sus familias.</li>
</ul>

</div>

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

**Domain:**  
Asistencia para personas no videntes dentro del hogar, proporcionando autonomía y seguridad mediante tecnología de reconocimiento del entorno.  

**Customer Segments:**  
- Personas no videntes que desean moverse con independencia dentro de su hogar.  
- Familias y cuidadores que buscan seguridad y tranquilidad para sus seres queridos no videntes.  

**Pain Points:**  
- Dificultad para desplazarse de forma segura y autónoma dentro del hogar.  
- Dependencia de terceros para realizar tareas cotidianas.  
- Riesgo de accidentes domésticos debido a obstáculos o falta de orientación.  
- Las soluciones existentes no ofrecen reconocimiento contextualizado del entorno.  

**Gap:**  
Actualmente no existen muchas aplicaciones funcionales que combinen mapeo previo del hogar, reconocimiento de objetos y muebles, y guía en tiempo real adaptada a personas no videntes.  

**Visión / Strategy:**  
Proveer una solución basada en inteligencia artificial que permita a las personas no videntes moverse con seguridad y autonomía dentro de su hogar, reduciendo riesgos y dependencia de terceros.  

**Initial Segment:**  
Personas no videntes con acceso a smartphones y hogares con espacios complejos que requieren asistencia para navegar de manera segura.  

**Problem Statements:**  
1. Las personas no videntes necesitan moverse dentro de su hogar con seguridad, pero las herramientas actuales no reconocen objetos ni guían de manera contextualizada.  
2. Los cuidadores buscan tranquilidad y control, pero no tienen manera de supervisar de forma segura la movilidad de sus familiares dentro del hogar.  

---

#### 1.2.2.2. Lean UX Assumptions.

**Supuestos de negocio**  
- Las personas con discapacidad visual buscan soluciones que les permitan mayor autonomía y seguridad en su hogar.  
- Una aplicación móvil con inteligencia artificial que mapee previamente el hogar y reconozca objetos, muebles, electrodomésticos y personas puede satisfacer esta necesidad.  
- Los usuarios estarán dispuestos a interactuar mediante indicaciones de voz y recibir feedback en tiempo real.  
- El entrenamiento de la IA en un entorno controlado permitirá minimizar errores y garantizar precisión en el reconocimiento de objetos y espacios.  
- La mayoría de los usuarios valorará la confiabilidad, facilidad de uso y la capacidad de la aplicación de integrarse con otros dispositivos domésticos, si los tuviera.  

**Supuestos de usuario**  
- Los usuarios desean moverse con seguridad y sin depender de terceros dentro de su hogar.  
- Valoran la privacidad y la protección de sus datos personales.   
- Esperan que la aplicación sea fácil de usar, intuitiva y que proporcione opciones claras para recibir orientación y feedback.  
- Desean alternativas de acceso seguro ante posibles fallos, como indicaciones redundantes o modos de ayuda remota.  

---

#### 1.2.2.3. Lean UX Hypothesis Statements.

1. **Hipótesis de seguridad y autonomía:**  
Si desarrollamos una aplicación que mapee previamente el hogar y use IA para reconocer objetos, muebles y personas, entonces los usuarios podrán moverse con mayor seguridad y autonomía.  

2. **Hipótesis de interacción:**  
Si la aplicación proporciona indicaciones de voz claras y feedback en tiempo real, los usuarios podrán interactuar con su entorno de manera confiable y sin depender de terceros.  

3. **Hipótesis de confianza y respaldo:**  
Si la aplicación ofrece reconocimiento preciso del entorno y alternativas ante fallos, los usuarios se sentirán más seguros y confiados, mejorando su calidad de vida.  

4. **Hipótesis de privacidad:**  
Si aseguramos la seguridad y privacidad de los datos mediante encriptación y auditorías, los usuarios confiarán en la tecnología y la adoptarán de forma sostenida.  

5. **Hipótesis de integración domótica:**  
Si la aplicación se integra con otros dispositivos inteligentes del hogar, los usuarios podrán optimizar la seguridad y comodidad, obteniendo una experiencia más completa y satisfactoria.  

---

#### 1.2.2.4. Lean UX Canvas.

<img src="./images/leanuxcanvas.png" width="auto">

## 1.3. Segmentos objetivo.

<section id="segmentos-usuarios">

  <article>
    <h4>Personas No Videntes</h4>
    <p>
Este segmento está compuesto por individuos con discapacidad visual que desean moverse con seguridad y autonomía dentro de su hogar. Buscan soluciones que les permitan reconocer objetos, muebles, electrodomésticos y personas, y recibir guía en tiempo real para evitar riesgos y accidentes domésticos.
    </p>
    <h4>Características clave:</h4>
    <ul>
      <li> Necesidad de mayor autonomía dentro del hogar.</li>
      <li> Preocupación por la seguridad y la reducción de accidentes.</li>
      <li> Interés en soluciones tecnológicas intuitivas y confiables.</li>
      <li> Usan smartphones o dispositivos que les permitan interactuar con aplicaciones de asistencia.</li>
    </ul>
  </article>

  <article>
    <h4>Familias y Cuidadores</h4>
    <p>
Este segmento incluye a familiares o cuidadores de personas no videntes que desean garantizar la seguridad de sus seres queridos dentro del hogar. Buscan soluciones que les permitan supervisar y apoyar de manera indirecta, sin invadir la independencia del usuario.
    </p>
    <h4>Características clave:</h4>
    <ul>
      <li> Necesidad de tranquilidad y control del usuario sobre la seguridad del hogar.</li>
      <li> Valoran herramientas que ayuden a prevenir accidentes o incidentes domésticos.</li>
      <li> Buscan soluciones confiables, fáciles de usar y que no interfieran con la autonomía del usuario principal.</li>
      <li> Interés en sistemas que ofrezcan notificaciones o feedback sobre la actividad dentro del hogar.</li>
    </ul>
  </article>
</section>

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.

<table> <thead> 
    <tr> <th>Nombre del Competidor</th> <th>Descripción</th> </tr> </thead> <tbody> <tr> <td rowspan="2" align="center"> <img src="./images/beMyEyes.png" alt="Be My Eyes Logo" style="width: 250px; height: auto;"> <br>Be My Eyes </td> <td>Be My Eyes conecta a personas ciegas o con baja visión con voluntarios a través de videollamadas en tiempo real. También cuenta con la función AI “Be My AI” para describir imágenes automáticamente mediante inteligencia artificial.</td> </tr> <tr> <td>Página web: <a href="https://www.bemyeyes.com/" target="_blank">https://www.bemyeyes.com/</a></td> </tr> <tr> <td rowspan="2" align="center"> <img src="./images/envision.png" alt="Envision AI Logo" style="width: 250px; height: auto;"> <br>Envision AI </td> <td>Envision AI es una app basada en inteligencia artificial que convierte texto y objetos capturados por la cámara del móvil en descripciones habladas. Reconoce texto en más de 60 idiomas y permite interacción por voz.</td> </tr> <tr> <td>Página web: <a href="https://www.letsenvision.com/" target="_blank">https://www.letsenvision.com/</a></td> </tr> 
    <tr> <td rowspan="2" align="center"> <img src="./images/lookoutByGoogle.png" alt="Lookout By Google" style="width: 250px; height: auto;"> <br>Lookout by Google</td> <td>Lookout es una app diseñada por Google para personas con discapacidad visual. Utiliza IA y la cámara del dispositivo para leer texto, identificar objetos, detectar monedas y proporcionar descripciones audibles del entorno.</td> </tr> <tr> <td>Página web: <a href="https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.reveal&hl=es_PE" target="_blank"> Disponible en Google Play (app Lookout by Google)</a></td> </tr> </tbody> </table>

### 2.1.1. Análisis competitivo.


<table style="width: 100%;">
  <tr>
    <th colspan="6" style="padding: 8px; text-align: center;"> Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Este análisis permite identificar fortalezas, debilidades, oportunidades y amenazas de HomeSense frente a competidores establecidos, con el fin de diferenciar a VisualGuide, definir su propuesta de valor única y diseñar estrategias de crecimiento sostenibles.</td>
</td>
  </tr>
  <tr>
    <td colspan="2"></td>
  <td align="center"><br><img src="./images/beMyEyes.png" alt="Be My Eyes"></td>
  <td align="center"><br><img src="./images/envision.png" alt="Envision"></td>
  <td align="center"><br><img src="./images/lookoutByGoogle.png" alt="Lookout By Google"></td>
  <td align="center"><br><img src="./images/lentesia.jpg" alt="VisualGuide (HomeSense)"></td>
  </tr>
<tr>
  <td rowspan="2" align="center">Perfil</td>
  <td align="center">Overview</td>
    <td>Conecta a personas ciegas con voluntarios o IA para asistencia visual en tiempo real.</td>
    <td>Convierte texto y objetos en descripciones habladas con IA.</td>
    <td>App de Google que identifica objetos, lee texto, detecta billetes y describe entornos.</td>
    <td>Asistente visual para el hogar: mapeo del entorno y guía segura en tiempo real.</td>
  </tr>
<tr>
  <td>Ventaja competitiva<br>¿Qué valor ofrece a los clientes?</td>
    <td>Gran comunidad global de voluntarios + soporte IA gratuito.</td>
    <td>OCR en más de 60 idiomas e interacción por voz.</td>
    <td>Respaldo de Google, confiabilidad y gratuidad.</td>
    <td>Enfoque exclusivo en seguridad doméstica, personalización y autonomía.</td>
  </tr>
 <tr>
  <td rowspan="2" align="center">Perfil de Marketing</td>
  <td>Mercado objetivo</td>
    <td>Personas con discapacidad visual que requieren ayuda inmediata en todo el mundo.</td>
    <td>Usuarios con discapacidad visual que necesitan leer texto o identificar objetos en múltiples contextos.</td>
    <td>Usuarios ciegos o con baja visión que utilizan Android en entornos cotidianos.</td>
    <td>Personas no videntes en América Latina que buscan independencia y seguridad dentro del hogar.</td>
  </tr>
<tr>
  <td>Estrategias de marketing</td>
    <td>Comunidad global + alianzas con ONGs.</td>
    <td>Promoción en comunidades inclusivas; enfoque multilingüe.</td>
    <td>Distribución masiva vía Google Play.</td>
    <td>Alianzas locales con asociaciones, campañas inclusivas en LATAM.</td>
  </tr>

<tr>
  <td rowspan="3" align="center">Perfil del Producto</td>
  <td>Productos & Servicios</td>
    <td>Videollamadas con voluntarios y soporte IA (Be My AI).</td>
    <td>Lectura de texto, reconocimiento de objetos y escenas.</td>
    <td>Lectura de texto, identificación de objetos, reconocimiento de billetes.</td>
    <td>Asistente de guía en el hogar con mapeo y navegación segura.</td>
  </tr>
<tr>
  <td>Precios & Costos</td>
    <td>Gratuito.</td>
    <td>Freemium: funciones básicas gratis, versión premium de pago.</td>
    <td>Gratuito.</td>
    <td>Freemium: acceso básico gratis, premium con funciones avanzadas (mapas personalizados, alertas).</td>
  </tr>
<tr>
  <td>Canales de distribución (Web y/o Móvil)</td>
    <td>App móvil (iOS/Android).</td>
    <td>App móvil (iOS/Android).</td>
    <td>App móvil (Android).</td>
    <td>App móvil (iOS/Android) + integración IoT en el hogar.</td>
  </tr>

<tr>
  <td rowspan="4" align="center">Análisis SWOT</td>
  <td>Fortalezas</td>
    <td>Gran base de usuarios y comunidad activa.</td>
    <td>OCR potente, multilingüe y versátil.</td>
    <td>Respaldo de Google, alta confiabilidad.</td>
    <td>Propuesta diferenciada enfocada en el hogar; seguridad y personalización.</td>
  </tr>
<tr>
  <td>Debilidades</td>
    <td>Dependencia de voluntarios; requiere internet estable.</td>
    <td>Suscripción de pago limita accesibilidad.</td>
    <td>Solo Android; enfoque genérico.</td>
    <td>Baja visibilidad inicial de marca como startup emergente.</td>
  </tr>
<tr>
  <td>Oportunidades</td>
    <td>Expandir funciones de IA.</td>
    <td>Alianzas con wearables y dispositivos accesibles.</td>
    <td>Mayor integración con ecosistema Google.</td>
    <td>Alta necesidad en LATAM; integración con hogares inteligentes.</td>
  </tr>
<tr>
  <td>Amenazas</td>
    <td>Competencia con soluciones IA más avanzadas.</td>
    <td>Riesgo por presencia de Google y Be My Eyes.</td>
    <td>Competidores especializados con mayor personalización.</td>
    <td>Entrada de grandes empresas en accesibilidad doméstica.</td>
  </tr>
<table>


### 2.1.2. Estrategias y tácticas frente a competidores.

**Estrategias:**

- **Diferenciación por enfoque en el hogar:** Mientras los competidores se centran en espacios públicos o funciones generales de accesibilidad, VisualGuide se especializa en seguridad y autonomía dentro del hogar, ofreciendo mapeo personalizado y navegación segura.
- **Segmentación regional en LATAM:** Enfocarse en un mercado poco atendido por gigantes como Google y Envision, adaptando las soluciones a las necesidades reales y específicas de los hogares en América Latina (precio accesible, fácil instalación y soporte local).
- **Propuesta de valor inclusiva y escalable:** Ofrecer un modelo freemium que garantice accesibilidad básica gratuita, con funciones premium adaptadas a necesidades avanzadas, asegurando inclusión y sostenibilidad del negocio.
- **Innovación constante con feedback de usuarios:** Mantener un ciclo de mejoras basadas en la retroalimentación directa de usuarios no videntes y sus familias, generando una solución más empática y adaptada que la de grandes corporaciones.

**Tácticas:**

- **Pruebas piloto en hogares de confianza:** Implementar VisualGuide en casas de familiares o conocidos con discapacidad visual para recoger feedback real, documentar casos de éxito y generar testimonios iniciales.
- **Campañas educativas en redes sociales propias:** Usar TikTok, Instagram y Facebook con videos cortos y testimonios que muestren cómo VisualGuide resuelve problemas cotidianos, diferenciándose de apps genéricas.
- **Convenios con universidades y ONGs locales:** Contactar a la UPC, PUCP u ONGs pequeñas que trabajen con personas con discapacidad para validar el producto y sumar usuarios iniciales sin grandes costos.
- **Integración básica con dispositivos IoT accesibles:** Conectar VisualGuide con dispositivos económicos como Alexa o Google Home (que ya existen en muchos hogares) para demostrar su valor agregado frente a competidores.


## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
Para la recolección de datos cualitativos, se diseñaron entrevistas semiestructuradas dirigidas a personas no videntes y sus cuidadores. Las entrevistas se enfocaron en comprender las necesidades, desafíos y expectativas de los usuarios en relación con la movilidad dentro del hogar y el uso de tecnologías de asistencia. Se elaboraron preguntas abiertas para fomentar la expresión libre y detallada de experiencias personales, así como preguntas específicas para obtener información sobre el uso actual de herramientas tecnológicas y las características deseadas en una solución ideal.

**Segmento objetivo 1**: Personas no videntes.
##### Preguntas básicas
1. ¿Cuál es su nombre?
2. ¿Dónde reside actualmente? (ciudad/distrito)
3. ¿Cuál es su edad?
4. ¿Desde cuándo es no vidente? (nacimiento o adquirido, y desde qué año)
5. ¿Vive solo/a o con familiares?

##### Preguntas principales

1. ¿Qué actividades dentro de su hogar le resultan más complicadas o riesgosas actualmente?
2. ¿Cómo suele identificar y ubicar objetos o muebles dentro de su casa?
3. ¿Qué nivel de confianza siente con las soluciones tecnológicas que usa hoy en día?
4. ¿En qué situaciones del hogar cree que una aplicación como VisualGuide podría ayudarle más?
5. ¿Cuáles son sus principales preocupaciones en cuanto a su seguridad dentro del hogar?
6. ¿Qué características considera indispensables en una aplicación de asistencia visual?
7. ¿Le resultaría cómodo realizar un mapeo previo de su hogar con ayuda de un familiar o tercero?
8. ¿Prefiere recibir la guía en formato de audio, vibración u otro medio? ¿Por qué?
9. ¿Qué tanto valora la privacidad de su información y del mapeo de su hogar?
10. ¿Qué barreras ha tenido al usar otras tecnologías o aplicaciones de accesibilidad?
11. ¿Qué situaciones le generan más independencia actualmente y cómo cree que se podrían mejorar?
12. ¿Le gustaría que la aplicación también reconociera personas cercanas o solo objetos?
13. ¿Cuánto tiempo estaría dispuesto a invertir en aprender a usar una nueva aplicación?
14. ¿Qué emociones le genera la idea de contar con un asistente visual inteligente en casa?
15. ¿Qué expectativas tendría del soporte técnico o acompañamiento de la aplicación?

**Segmento objetivo 2**: Familiares o cuidadores de personas no videntes.
##### Preguntas básicas

1. ¿Cuál es su nombre?
2. ¿Dónde reside actualmente? (ciudad/distrito)
3. ¿Cuál es su edad?
4. ¿Quién es la persona no vidente en su familia? (ejemplo: hijo/a, padre/madre, hermano/a)
5. ¿Convive actualmente con su familiar no vidente?

##### Preguntas principales

1. ¿Qué situaciones en el hogar le generan más preocupación respecto a la seguridad de su familiar no vidente?
2. ¿Qué medidas actuales utiliza para ayudarle a desenvolverse de forma independiente?
3. ¿Qué tan cómodo/a se siente con el uso de tecnología como apoyo en la vida diaria de su familiar?
4. ¿Qué expectativas tendría de una aplicación como VisualGuide en términos de seguridad?
5. ¿Cuáles cree que serían los principales beneficios para su familiar al usar esta solución?
6. ¿Qué nivel de supervisión o acompañamiento cree que sería necesario al usar la aplicación?
7. ¿Cómo se sentiría respecto al mapeo digital del hogar? ¿Le genera confianza o preocupación?
8. ¿Qué importancia le da a que la aplicación mantenga la privacidad de los datos del hogar?
9. ¿Qué dificultades cree que su familiar podría tener al usar la aplicación?
10. ¿Le gustaría recibir notificaciones o alertas sobre el uso de la app para monitorear la seguridad?
11. ¿Qué tipo de soporte técnico esperaría como familiar (ej. capacitación, tutoriales, soporte remoto)?
12. ¿Qué situaciones específicas cree que deberían priorizarse en la asistencia (ej. evitar tropiezos, ubicar electrodomésticos, leer etiquetas)?
13. ¿Qué tanto valora que su familiar gane autonomía frente a depender de su ayuda constante?
14. ¿Cómo describiría el balance ideal entre autonomía y supervisión para su ser querido?
15. ¿Qué mejoras o funciones adicionales le gustaría ver en una aplicación como esta?

### 2.2.2. Registro de entrevistas.

**Segmento objetivo 1: Personas no videntes**

// EJEMPLO DE ENTREVISTA

**Entrevista 1: Persona no vidente -**
- Nombre: Marco Méndez
- Edad: 35 años
- Residencia: Lima, Perú
- Desde cuándo es no vidente: Desde nacimiento
- Vive con familiares

<img src="./images/Chapter2/Entrevistas/Marco Mendez.png" alt="Foto de Marco Méndez" width="200">

**Resumen de la entrevista:**
Marco Méndez, de 35 años y no vidente desde nacimiento, reside en Lima y vive con su familia. Durante la entrevista, Marco compartió que las actividades más complicadas dentro de su hogar incluyen moverse entre habitaciones y ubicar objetos pequeños como llaves o el control remoto. Actualmente, utiliza un bastón para desplazarse y depende en gran medida de la ayuda de sus familiares para tareas cotidianas.

**Segmento objetivo 2: Familiares o cuidadores de personas no videntes**

**Entrevista 1: Familiar de persona no vidente - Carlos Chavez**
- Nombre: Carlos Sebastián Chavez Morales
- Edad: 21 años
- Residencia: La Perla, Callao, Perú
- Familiar no vidente: Primo
- Convive con su familiar no vidente: No, pero lo visita frecuentemente.

<img src="./images/interviews/carlos-chavez-interview.PNG" alt="Foto de Carlos Chavez" width="100%">

**URL de la entrevista:** [https://acortar.link/c6DJAQ](https://acortar.link/c6DJAQ)

**Resumen de la entrevista:**
Carlos Chávez, de 21 años, es primo de una persona no vidente y reside en La Perla, Callao. Aunque no convive con su primo, lo visita frecuentemente y se preocupa por su seguridad dentro del hogar. Carlos mencionó que las principales preocupaciones incluyen la posibilidad de accidentes domésticos y la dependencia constante de ayuda para moverse y realizar tareas básicas. Actualmente, su familia utiliza un bastón y la ayuda de otros familiares para asistir a su primo.

Mencionó que una aplicación como VisualGuide podría ser muy beneficiosa, ya que permitiría a su primo ganar más autonomía y reducir la necesidad de supervisión constante. Carlos también expresó interés en recibir notificaciones sobre el uso de la aplicación para monitorear la seguridad de su primo.

### 2.2.3. Análisis de entrevistas.

// aqui se debe hacer un analisis con GOOGLE FORMS con preguntas a personas anónimas, y sacando captura de pantalla de los resultados


## 2.3. Needfinding.
### 2.3.1. User Personas.

Los user personas son usados para definir los segmentos objetivos, asignando cualidades a cada uno de ellos y representandolos como personas

##### Personas no videntes:

<img src="./images/Chapter2/UserPersona/Marco Mendez.png" alt="User persona no videntes" width="auto">

##### Familias y cuidadores:

<img src="./images/Chapter2/UserPersona/María Mendoza.png" alt="User persona familiares y cuidadores" width="auto">

### 2.3.2. User Task Matrix.

El user task matrix muestra las acciones realizadas por los usuarios, junto con su importancia y frecuencia realizada

|-----------------|------------|-----------|--------------|-----------|
|-|-|-|-|-|
| Tarea           | Importancia No Videntes | Frecuencia No Videntes | Importancia Familiares y Cuidadores | Frecuencia Familiares y Cuidadores |
| Moverse por su casa | alta | media | alta | alta |
| Hablar con sus familiares | alta | alta | alta | alta |
| Ayudar a otras personas en su dia a dias | alta | baja | alta | alta |
| Cocinar | alta | baja | alta | alta |
| Limpiar la casa | media | baja | alta | alta |
| Sacar la basura | alta | baja | alta | alta |


### 2.3.3. Empathy Mapping.
El empathy map esta diseñado para mostrar las opiniones de nuestros usuarios ante el problema

**Perosnas no videntes:**

<img src="./images/Chapter2/Needfinding/Empathy map Marco.png" alt="Empathy map 1" width="auto">

**Familiares y cuidadores:**

<img src="./images/Chapter2/Needfinding/Empathy map Maria.png" alt="Empathy map 1" width="auto">

### 2.3.4. As-is Scenario Mapping.

El As-Is map es usado para mostrar la situación actual del usuario, evidenciando sus problemas sin usar nuestra aplicación

**Perosnas no videntes:**

<img src="./images/Chapter2/Needfinding/AsIsSegmento1.png" alt="Empathy map 1" width="auto">

**Familiares y cuidadores:**

<img src="./images/Chapter2/Needfinding/AsIsSegmento2.png" alt="Empathy map 1" width="auto">

## 2.4. Ubiquitous Language.

**Source Data:** Datos almacenados por el modelo de object detection usado por la aplicación, sirven para definir el tipo de objeto.

**House Map:** Mapa del hogar del usuario, usado por la aplicación para recordar la distribución de la casa.

**Home path:** Camino trazado en el mapa, el cual el usuario deberá seguir para llegar a su destino.

**Home obstacle:** Obstáculo en el camino que puede provocar que el usuario se tropiece, la aplicación advierte cuando hay uno en el suelo.

**Object data:** Datos sobre los objetos detectados, usados por la aplicación para determinar la zona en la que se encuentra y si los objetos son peligrosos.

**Helpers:** Familiares o cuidadores inscritos para recibir notificaciones de su familiar cuando necesita ayuda.

**Help Notification:** Notificación enviada cuando el usuario no vidente necesita ayuda de una persona.

**Visual Model:** Modelo de inteligencia artificial centrado en la detección de objetos, usa la Source Data para clasificar objetos.

**Visual Voice:** Voz creada por inteligencia artificial para comunicarse con el usuario, puede personalizarse según sus necesidades.


# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

El To-Be map es usado para mostrar la situación futura del usuario, evidenciando los cambios tras usar nuestra aplcación

**Perosnas no videntes:**

<img src="./images/Chapter2/Needfinding/ToBeSegmento1.png" alt="Empathy map 1" width="auto">

**Familiares y cuidadores:**

<img src="./images/Chapter2/Needfinding/ToBeSegmento2.png" alt="Empathy map 1" width="auto">

## 3.2. User Stories.
Redactamos las historias de usuario para el sistema de "VisualGuide", basándonos en las necesidades y expectativas de los usuarios no videntes y sus cuidadores. Estas historias reflejan las funcionalidades clave que el sistema debe ofrecer para mejorar la autonomía y seguridad dentro del hogar.

<!-- Tabla de épicas -->
<table>
   <thead>
      <tr>
         <th>Epic ID</th>
         <th>Título</th>
         <th>Descripción</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>EP01</td>
         <td>Reconocimiento de objetos y muebles</td>
         <td>Implementar un sistema de reconocimiento de objetos y muebles en la aplicación para ayudar a los usuarios no videntes a identificar su entorno.</td>
      </tr>
      <tr>
         <td>EP02</td>
         <td>Mapeo del hogar</td>
         <td>Desarrollar una funcionalidad que permita a los usuarios mapear su hogar mediante fotografías y escaneos en un entorno controlado.</td>
      </tr>
      <tr>
         <td>EP03</td>
         <td>Guía en tiempo real</td>
         <td>Crear un sistema de guía en tiempo real que proporcione indicaciones de voz claras y precisas para que los usuarios puedan moverse con seguridad dentro de su hogar.</td>
      </tr>
      <tr>
         <td>EP04</td>
         <td>Notificaciones a cuidadores</td>
         <td>Implementar una funcionalidad que permita a los cuidadores recibir notificaciones sobre la actividad del usuario no vidente para asegurar su seguridad.</td>
      </tr>
      <tr>
         <td>EP05</td>
         <td>Acceso a la información de la aplicación</td>
         <td>Desarrollar una funcionalidad que permita a los usuarios no videntes acceder a la información de la aplicación mediante comandos de voz.</td>
      </tr>
      <tr>
         <td>EP06</td>
         <td>Configuración de preferencias</td>
         <td>Crear una sección de configuración que permita a los usuarios no videntes personalizar sus preferencias en la aplicación.</td>
      </tr>
      <tr>
         <td>EP07</td>
         <td>Información de la empresa</td>
         <td>Proporcionar información relevante sobre la empresa a cargo del producto en la sección de HomeSense.</td>
      </tr>
      <tr>
         <td>EP08</td>
         <td>Asociación de usuario no vidente y familiar</td>
         <td>Desarrollar funcionalidad para, como familiar del usuario no vidente, ver alertas y detalles sobre el usuario.</td>
      </tr>
      <tr>
         <td>EP09</td>
         <td>Monitoreo y soporte</td>
         <td>Desarrollar logs, métricas y notificaciones de acuerdo a errores o bugs que pueda presentar el sistema.</td>
      </tr>
      <tr>
         <td>EP10</td>
         <td>Gestión de usuarios y perfiles</td>
         <td>Implementar un registro y gestión de usuarios de forma segura y sencilla.</td>
      </tr>
   </tbody>

<table>
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HU01</td>
      <td>Obtener información de la empresa</td>
      <td>Como visitante del sitio web, quiero obtener información adicional sobre la empresa a cargo del producto.</td>
      <td><b>Given</b> el visitante se encuentra en la sección de HomeSense.<br/><b>When</b> observa la información relevante sobre la empresa. <br><b>Then</b> se interesa en saber más sobre el producto.<br><b>Y</b> se redirecciona a la descarga directa de la aplicación móvil.
      </td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>HU02</td>
      <td>Uso de la aplicación móvil</td>
      <td>Como usuario no vidente, quiero utilizar la aplicación móvil para recibir asistencia en la navegación dentro de mi hogar.</td>
      <td><b>Given</b> el usuario ha descargado e instalado la aplicación móvil.<br/><b>When</b> abre la aplicación y sigue las instrucciones para mapear su hogar.<br><b>Then</b> puede recibir indicaciones de voz en tiempo real para moverse de manera segura dentro de su casa.<br><br><b>Given</b> el usuario está utilizando la aplicación dentro de su hogar.<br/><b>When</b> la aplicación detecta objetos y muebles a través de la cámara.<br><b>Then</b> proporciona indicaciones de voz claras sobre la ubicación y características de los objetos cercanos.</td>
      <td>EP03</td>
   </tr>
   <tr>
      <td>HU03</td>
      <td>Mapeo del hogar</td>
      <td>Como usuario no vidente, quiero mapear mi hogar utilizando la aplicación para que pueda reconocer objetos y muebles.</td>
      <td><b>Given</b> el usuario ha iniciado el proceso de mapeo en la aplicación.<br/><b>When</b> sigue las instrucciones para capturar imágenes y escanear su entorno.<br><b>Then</b> la aplicación crea un mapa detallado de su hogar que puede utilizar para navegación futura.<br><br><b>Given</b> el usuario ha descargado e instalado la aplicación móvil.<br/><b>When</b> abre la aplicación y sigue las instrucciones para mapear su hogar.<br><b>Then</b> puede recibir indicaciones de voz en tiempo real para moverse de manera segura dentro de su casa.</td>
      <td>EP02</td>
   </tr>
   <tr>
      <td>HU04</td>
      <td>Reconocimiento de objetos y muebles</td>
      <td>Como usuario no vidente, quiero que la aplicación reconozca objetos y muebles en mi hogar para recibir indicaciones precisas.</td>
      <td><b>Given</b> el usuario está utilizando la aplicación dentro de su hogar.<br/><b>When</b> la aplicación detecta objetos y muebles a través de la cámara.<br><b>Then</b> proporciona indicaciones de voz claras sobre la ubicación y características de los objetos cercanos.<br><br><b>Given</b> el usuario ha completado el mapeo de su hogar.<br/><b>When</b> utiliza la aplicación para navegar.<br><b>Then</b> la aplicación reconoce objetos y muebles previamente mapeados y proporciona indicaciones precisas para evitar obstáculos y moverse con seguridad.</td>
      <td>EP01</td>
   </tr>
   <tr>
      <td>HU05</td>
      <td>Notificaciones a cuidadores</td>
      <td>Como cuidador, quiero recibir notificaciones sobre la actividad del usuario no vidente para asegurarme de su seguridad.</td>
      <td><b>Given</b> el cuidador ha configurado las notificaciones en la aplicación.<br/><b>When</b> el usuario realiza movimientos significativos o se encuentra en situaciones potencialmente peligrosas.<br><b>Then</b> el cuidador recibe alertas en tiempo real para tomar las acciones necesarias.<br><br><b>Given</b> el cuidador ha configurado las notificaciones en la aplicación.<br/><b>When</b> el usuario no vidente se mueve dentro de su hogar.<br><b>Then</b> el cuidador recibe notificaciones sobre la actividad del usuario para asegurar su seguridad.</td>
      <td>EP04</td>
   </tr>
   <tr>
      <td>HU06</td>
      <td>Acceso a la información de la aplicación</td>
      <td>Como usuario no vidente, quiero acceder a la información de la aplicación a través de comandos de voz para facilitar su uso.</td>
      <td><b>Given</b> el usuario está utilizando la aplicación.<br/><b>When</b> solicita información sobre una función específica mediante un comando de voz.<br><b>Then</b> la aplicación proporciona una respuesta clara y concisa a través de la síntesis de voz.</td>
      <td>EP05</td>
   </tr>
   <tr>
      <td>HU07</td>
      <td>Configuración de preferencias</td>
      <td>Como usuario no vidente, quiero configurar mis preferencias en la aplicación para personalizar mi experiencia.</td>
      <td><b>Given</b> el usuario ha accedido a la sección de configuración en la aplicación.<br/><b>When</b> ajusta las opciones de voz, notificaciones y otros parámetros según sus necesidades.<br><b>Then</b> la aplicación guarda las preferencias y las aplica durante su uso.</td>
      <td>EP06</td>
   </tr>
   <tr>
      <td>HU08</td>
      <td>Reconocimiento de voz</td>
      <td>Como usuario no vidente, quiero que la aplicación registre y reconozca mis comandos de voz para facilitar la interacción.</td>
      <td><b>Given</b> el usuario está utilizando la aplicación.<br/><b>When</b> el usuario configura sus comandos de voz personalizados.<br><b>Then</b> la aplicación reconoce y responde a estos comandos de manera efectiva durante su uso.<br><br><b>Given</b> el usuario está utilizando la aplicación.<br/><b>When</b> emite un comando de voz.<br><b>Then</b> la aplicación reconoce el comando y responde adecuadamente para facilitar la interacción.</td>
      <td>EP03</td>
   </tr>
   <tr>
      <td>HU09</td>
      <td>Reconocer objetos básicos</td>
      <td>Como usuario no vidente, quiero que la app me diga qué objeto tengo enfrente, para orientarme en mi casa.</td>
      <td><b>Given</b> el usuario abre la cámara, <br/><b>When</b> la IA detecta un objeto, <br><b>Then</b> la app anuncia por voz el nombre del objeto. <br><br><b>Given</b> el objeto no se reconoce, <br/><b>When</b> la IA no tiene certeza, <br><b>Then</b> la app indica “objeto no identificado”. </td>
      <td>EP01</td>
   </tr>
   <tr>
      <td>HU10</td>
      <td>Guardar mapa simple del hogar</td>
      <td>Como usuario no vidente, quiero que la app guarde un mapa sencillo de mi casa, para usarlo después en la navegación.</td>
      <td><b>Given</b> el usuario inicia el mapeo <br/><b>When</b> recorre los espacios y toma fotos, <br><b>Then</b> la app guarda un mapa básico. <br><br><b>Given</b> el usuario ya mapeó antes, <br/><b>When</b> actualiza el mapeo, <br><b>Then</b> la app reemplaza el mapa antiguo por el nuevo. </td>
      <td>EP02</td>
   </tr>
   <tr>
      <td>HU11</td>
      <td>Guía con voz paso a paso</td>
      <td>Como usuario no vidente, quiero que la app me indique con voz hacia dónde moverme, para llegar a un lugar de mi casa.</td>
      <td><b>Given</b> el usuario selecciona un destino, <br/><b>When</b> inicia la navegación, <br><b>Then</b> la app da instrucciones de voz paso a paso. <br><br><b>Given</b> el usuario se equivoca de camino <br/><b>When</b> la app detecta que salió de la ruta, <br><b>Then</b> recalcula y actualiza la guía. </td>
      <td>EP03</td>
   </tr>
   <tr>
      <td>HU12</td>
      <td>Notificación rápida al cuidador</td>
      <td>Como cuidador, quiero recibir una alerta si el usuario tiene un problema en casa, para poder ayudarlo rápido.</td>
      <td><b>Given</b> el usuario está en casa, <br/><b>When</b> la app detecta falta de movimiento, <br><b>Then</b> envía una notificación al cuidador. <br><br><b>Given</b> la app detecta movimiento brusco, <br/><b>When</b> interpreta posible caída, <br><b>Then</b> envía una alerta inmediata al cuidador. </td>
      <td>EP04</td>
   </tr>
<tr>
  <td>HU13</td>
  <td>Historial de recorridos</td>
  <td>Como usuario no vidente, quiero que la aplicación guarde un historial de mis recorridos dentro del hogar, para poder revisar rutas frecuentes y optimizar mi movilidad.</td>
  <td>
    <b>Given</b> el usuario ha realizado recorridos guiados en la aplicación, <br/>
    <b>When</b> accede a la sección de historial, <br/>
    <b>Then</b> puede visualizar mediante síntesis de voz las rutas más utilizadas.<br/><br/>
    <b>Given</b> el usuario consulta una ruta del historial, <br/>
    <b>When</b> selecciona “repetir recorrido”, <br/>
    <b>Then</b> la aplicación activa la guía paso a paso de esa ruta específica.
  </td>
  <td>EP05</td>
</tr>

   <tr>
      <td>HU14</td>
      <td>Ajustar velocidad de voz</td>
      <td>Como usuario no vidente, quiero cambiar la velocidad de la voz de la app, para que me sea más cómodo escucharla.</td>
      <td><b>Given</b> el usuario entra a configuración, <br/><b>When</b> ajusta la velocidad de voz, <br><b>Then</b> la app guarda la preferencia. <br><br><b>Given</b> el usuario cambia entre velocidades rápidas y lentas, <br/><b>When</b> confirma la opción, <br><b>Then</b> la app aplica el cambio inmediato en las siguientes instrucciones. </td>
      <td>EP06</td>
   </tr>
<tr>
  <td>HU15</td>
  <td>Recordatorio de batería baja</td>
  <td>Como usuario no vidente, quiero que la aplicación me avise cuando la batería de mi dispositivo esté baja, para no quedarme sin asistencia inesperadamente.</td>
  <td>
    <b>Given</b> la batería del dispositivo baja al 20%, <br/>
    <b>When</b> el usuario está utilizando la aplicación, <br/>
    <b>Then</b> la app emite una alerta de voz indicando “batería baja, conecte el cargador”.<br/><br/>
    <b>Given</b> la batería llega al 10%, <br/>
    <b>When</b> la app sigue en uso, <br/>
    <b>Then</b> se activa un recordatorio de voz más insistente cada 2 minutos.
  </td>
  <td>EP06</td>
</tr>
   <tr>
      <td>HU16</td>
      <td>Perfil de usuario básico</td>
      <td>Como usuario no vidente, quiero tener un perfil sencillo en la app con mi nombre y preferencias de voz, para que la aplicación recuerde mis configuraciones automáticamente.</td>
      <td><b>Given</b> el usuario crea un perfil, <br/><b>When</b> guarda su nombre y preferencias de voz, <br><b>Then</b> la app aplica esa configuración cada vez que inicia. <br><br><b>Given</b> el usuario cambia de dispositivo <br/><b>When</b> inicia sesión con su perfil, <br><b>Then</b> la app carga las mismas configuraciones.</td>
      <td>EP06</td>
   </tr>
   <tr>
      <td>HU17</td>
      <td>Perfil de usuario básico</td>
      <td>Como usuario no vidente, quiero tener un perfil sencillo en la app con mi nombre y preferencias de voz, para que la aplicación recuerde mis configuraciones automáticamente.</td>
      <td><b>Given</b> el usuario crea un perfil, <br/><b>When</b> guarda su nombre y preferencias de voz, <br><b>Then</b> la app aplica esa configuración cada vez que inicia. <br><br><b>Given</b> el usuario cambia de dispositivo <br/><b>When</b> inicia sesión con su perfil, <br><b>Then</b> la app carga las mismas configuraciones.</td>
      <td>EP06</td>
   </tr>
   <tr>
      <td>HU18</td>
      <td>Perfil de usuario básico</td>
      <td>Como usuario no vidente, quiero tener un perfil sencillo en la app con mi nombre y preferencias de voz, para que la aplicación recuerde mis configuraciones automáticamente.</td>
      <td><b>Given</b> el usuario crea un perfil, <br/><b>When</b> guarda su nombre y preferencias de voz, <br><b>Then</b> la app aplica esa configuración cada vez que inicia. <br><br><b>Given</b> el usuario cambia de dispositivo <br/><b>When</b> inicia sesión con su perfil, <br><b>Then</b> la app carga las mismas configuraciones.</td>
      <td>EP06</td>
   </tr>
   <tr>
      <td>HU19</td>
      <td>Cambiar tipo de voz</td>
      <td>Como usuario no vidente, quiero contar con distintas voces, para poder elegir la que enteinda mejor.</td>
      <td><b>Given</b> que el uusario esta configurando la aplicación, <br/><b>When</b> el usuario pida cambiar el tipo de voz, <br><b>Then</b> la aplicación le mostrará posibles alternativas. <br><br><br> <b>Given</b> que el uusario esta configurando la aplicación, <br/><b>When</b> el usuario elija un tipo de voz, <br><b>Then</b> la aplicación cambiará la voz usada al guiarlo.</td>
      <td>EP06</td>
   </tr>
   <tr>
      <td>HU20</td>
      <td>Reconocimiento de obstáculos</td>
      <td>Como usuario no vidente, quiero que la aplicación me advierta de objetos pequeños en el suelo, para evitar tropezarme</td>
      <td><b>Given</b> que el usuario este siendo guiado por la aplicación, <br/><b>When</b> halla un obstáculo en el suelo, <br><b>Then</b> la aplicación le advertirá que camine con cuidado</td>
      <td>EP01</td>
   </tr>
   <tr>
      <td>HU21</td>
      <td>Reconocimiento de escaleras</td>
      <td>Como usuario no vidente, quiero que la aplicación me advierta cuando me acerca a unas escalera, para evitar chocar con ellas</td>
      <td><b>Given</b> que el usuario camina hacia unas escalera , <br/><b>When</b> esté a menos de un metro , <br><b>Then</b> la aplicación le dirá que hay escaleras enfrente</td>
      <td>EP01</td>
   </tr>
   <tr>
      <td>HU22</td>
      <td>Reconocimiento del nivel del suelo</td>
      <td>Como usuario no vidente, quiero que la aplicación me avise ante desniveles, para evitar caerme</td>
      <td><b>Given</b> el usuario camina cerca a un desnivel , <br/><b>When</b> esté a menos de un metro de este , <br><b>Then</b> la aplicación advertirá que hay un desnivel</td>
      <td>EP02</td>
   </tr>
   <tr>
      <td>HU23</td>
      <td>Ajustar volúmen de voz</td>
      <td>Como usuario no vidente, quiero poder elegir distintos volumenes de voz, para poder seleccionar el que escuche mejor</td>
      <td><b>Given</b> que el usuario esté configurando la aplicación, <br/><b>When</b> pida cambiar el volumen, <br><b>Then</b> la aplicación le indicará si aumentar o subirlo. <br><br><br> <b>Given</b> que el usuario esté configurando la aplicación, <br/><b>When</b> pida subir el volumen, <br><b>Then</b> la aplicación aumentará el volumen de la voz usada para guiarlo.</td>
      <td>EP06</td>
   </tr>
   <tr>
      <td>HU24</td>
      <td>Opiniones en la página</td>
      <td>Como visitante de la página web, quiero poder visualizar las opiniones de la aplicación, para saber que opinan los usuarios</td>
      <td><b>Given</b> que el usuario esta en la página web, <br/><b>When</b> avanze hasta la parte inferior, <br><b>Then</b> podrá ver cards con opiniones de usuario</td>
      <td>EP07</td>
   </tr>
   <tr>
      <td>HU25</td>
      <td>Guía en la página</td>
      <td>Como visitante de la página web, quiero poder visualizar una guía de la aplicación móvil, para poder explicarle a mi familiar como funciona</td>
      <td><b>Given</b> que el usuario esta en la página web, <br/><b>When</b> avanze hasta la sección de guía, <br><b>Then</b> podrá ver ejemplos de la aplicación</td>
      <td>EP05</td>
   </tr>
   <tr>
      <td>HU26</td>
      <td>Registro de logs</td>
      <td>Como backend, quiero registrar logs de cada interacción, para detectar fallos y mejorar el sistema.</td>
      <td><b>Given</b> que la aplicación móvil interactúa con el asistente,<br/><b>When</b> se realiza una solicitud (ej. búsqueda de objeto, guía de movimiento),<br><b>Then</b> el backend debe guardar un log con el detalle de la acción.</td>
      <td>EP09</td>
   </tr>
   <tr>
      <td>HU27</td>
      <td>Métricas de uso</td>
      <td>Como administrador, quiero ver métricas de uso del asistente (frecuencia, funciones más usadas), para identificar mejoras necesarias.</td>
      <td><b>Given</b> que el sistema está en funcionamiento,<br/><b>When</b> los usuarios realizan interacciones frecuentes, <br><b>Then</b> el backend debe generar métricas de uso (ej. cantidad de consultas, funciones más usadas).</td>
      <td>EP09</td>
   </tr>
   <tr>
      <td>HU28</td>
      <td>Manejo de errores críticos</td>
      <td>Como backend, quiero manejar notificaciones de errores críticos, para garantizar la estabilidad del servicio.</td>
      <td><b>Given</b> que ocurre un fallo grave en el sistema,<br/><b>When</b> el backend detecta el error,<br><b>Then</b> debe generar una alerta o notificación al administrador para tomar acción inmediata.</td>
      <td>EP09</td>
   </tr>
   <tr>
      <td>HU29</td>
      <td>Inicio de sesión</td>
      <td>Como usuario, quiero poder iniciar sesión de forma segura, para acceder a mis datos y configuraciones.</td>
      <td><b>Given</b> que un usuario ya está registrado en el sistema,<br/><b>When</b> ingresa sus credenciales correctamente,<br><b>Then</b> el backend valida sus datos y permite el acceso a su información personal.</td>
      <td>EP10</td>
   </tr>
   <tr>
      <td>HU30</td>
      <td>Actualización de preferencias</td>
      <td>Como usuario, quiero poder actualizar mis preferencias (ej. idioma, velocidad de voz), para personalizar mi experiencia.</td>
      <td><b>Given</b> que un usuario ya está autenticado,<br/><b>When</b> solicita cambiar configuraciones como idioma o velocidad de voz, <br><b>Then</b> el backend guarda y aplica esos cambios en su perfil.</td>
      <td>EP10</td>
   </tr>
   <tr>
      <td>HU31</td>
      <td>Gestión por administrador</td>
      <td>Como administrador, quiero poder gestionar usuarios (bloquear, desbloquear, soporte), para garantizar el correcto uso de la app.</td>
      <td><b>Given</b> que un administrador necesita dar soporte,<br/><b>When</b> accede a la información de usuarios desde el panel de gestión,<br><b>Then</b> el backend debe permitir ver, bloquear o desbloquear usuarios según sea necesario.</td>
      <td>EP10</td>
   </tr>
   <tr>
      <td>HU32</td>
      <td>Historial de objetos reconocidos</td>
      <td>Como persona relacionada con el usuario no vidente, quiero poder ver un historial de objetos buscados por el usuario, para poder tomar medidas futuras para la comodidad del usuario.</td>
      <td><b>Given</b> que el usuario no vidente pida a la aplicación móvil buscar un objeto,<br/><b>When</b> la aplicación móvil termine con dicha tarea,<br><b>Then</b> guardará detalles sobre el caso para revisiones futuras.</td>
      <td>EP08</td>
   </tr>
   <tr>
      <td>HU33</td>
      <td>Alertas de problemas con el usuario</td>
      <td>Como persona relacionada con el usuario, quiero poder recibir alerrtas de la aplicación móvil, para saber si el usuario tiene algún problema que no pueda solucionar con la aplicación.</td>
      <td><b>Given</b> que el usuario no vidente tenga algún problema grave,<br/><b>When</b> el aplicativo detecte que la situación es crítica, <br><b>Then</b> mandará una alerta a la persona relacionada con el usuario.</td>
      <td>EP08</td>
   </tr>
   </tbody>
</table>
    

## 3.3. Impact Mapping.
## 3.4. Product Backlog.

# Capítulo IV: Strategic-Level Software Design.
## 4.1. Strategic-Level Attribute-Driven Design.
En esta sección se presenta el proceso de Attribute-Driven Design (ADD) aplicado al proyecto de la aplicación móvil asistente visual inteligente para personas no videntes. El enfoque estratégico de ADD permite transformar los requisitos funcionales y no funcionales en decisiones arquitectónicas que guiarán el diseño del sistema.

El objetivo es evidenciar cómo los atributos de calidad más relevantes —como la seguridad física del usuario, privacidad, latencia de respuesta, precisión de la detección, robustez y mantenibilidad— influyen directamente en la arquitectura propuesta.
### 4.1.1. Design Purpose.
El propósito del proceso de diseño de la solución es garantizar que la arquitectura del sistema responda de forma efectiva a la problemática identificada: la necesidad de las personas no videntes de desenvolverse de manera segura y autónoma en su entorno doméstico.
La aplicación móvil se concibe como un asistente visual inteligente, capaz de interpretar el entorno del hogar mediante técnicas de inteligencia artificial y visión por computadora, reconociendo objetos, muebles, electrodomésticos, personas, textos y colores, para guiar al usuario en tiempo real.

El diseño estratégico busca:

- Satisfacer las necesidades de los segmentos objetivo (usuarios no videntes y sus cuidadores), priorizando la seguridad, privacidad y accesibilidad.
- Ofrecer valor al negocio al posicionarse como una solución innovadora de transformación digital orientada a la inclusión, con potencial de escalar hacia diferentes hogares y dispositivos móviles.
- Asegurar la viabilidad tecnológica mediante decisiones arquitectónicas que permitan baja latencia, procesamiento local de datos sensibles, actualizaciones seguras de modelos de IA y facilidad de mantenimiento.

De esta manera, el proceso de diseño no solo se enfoca en los requerimientos técnicos, sino también en la experiencia del usuario final y en la creación de una solución confiable, sostenible y alineada con los objetivos de accesibilidad e inclusión social.
A continuación, en la sección 4.1.2 Attribute-Driven Design Inputs, se presentan los insumos principales que guían el diseño estratégico, incluyendo la funcionalidad prioritaria, los escenarios de atributos de calidad y las restricciones del sistema.
### 4.1.2. Attribute-Driven Design Inputs.
El proceso de Attribute-Driven Design (ADD) requiere identificar de manera explícita los inputs fundamentales que orientan la arquitectura de la solución. Estos insumos permiten transformar los objetivos del proyecto y las necesidades del usuario en decisiones arquitectónicas claras y justificadas.

En el caso de la aplicación móvil asistente visual inteligente para personas no videntes, los inputs iniciales reflejan tanto la funcionalidad prioritaria del sistema, como los atributos de calidad críticos que deben garantizarse (seguridad, privacidad, latencia, precisión y robustez), además de las restricciones técnicas y contextuales que condicionan el diseño.

De este modo, la definición temprana y sistemática de los inputs asegura que la arquitectura resultante esté alineada con la problemática identificada, las expectativas de los usuarios y los objetivos del negocio.
#### 4.1.2.1. Primary Functionality (Primary User Stories).
En esta sección se especifican los Epics y User Stories que poseen mayor relevancia en términos de requisitos funcionales, dado que impactan de manera directa en las decisiones arquitectónicas de la solución. Estas funcionalidades constituyen la base del sistema, ya que aseguran que la aplicación cumpla con su propósito principal: asistir a personas no videntes en la navegación y comprensión de su entorno doméstico de forma segura y accesible.

| Epic / User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| -------------------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| HU01                 | Obtener información de la empresa        | Como visitante del sitio web, quiero obtener información adicional sobre la empresa a cargo del producto.                     | **Given** el visitante se encuentra en la sección de HomeSense.<br>**When** observa la información relevante sobre la empresa.<br>**Then** se interesa en saber más sobre el producto.<br>**Y** se redirecciona a la descarga directa de la aplicación móvil.                                                                                                                                                                                           | EP07                      |
| HU02                 | Uso de la aplicación móvil               | Como usuario no vidente, quiero utilizar la aplicación móvil para recibir asistencia en la navegación dentro de mi hogar.     | **Given** el usuario ha descargado e instalado la aplicación móvil.<br>**When** abre la aplicación y sigue las instrucciones para mapear su hogar.<br>**Then** puede recibir indicaciones de voz en tiempo real para moverse de manera segura dentro de su casa.<br><br>**Given** el usuario está utilizando la aplicación dentro de su hogar.<br>**When** la aplicación detecta objetos y muebles.<br>**Then** proporciona indicaciones de voz claras. | EP03                      |
| HU03                 | Mapeo del hogar                          | Como usuario no vidente, quiero mapear mi hogar utilizando la aplicación para que pueda reconocer objetos y muebles.          | **Given** el usuario ha iniciado el proceso de mapeo.<br>**When** captura imágenes y escanea su entorno.<br>**Then** la aplicación crea un mapa detallado.<br><br>**Given** el usuario ha descargado la aplicación.<br>**When** realiza el mapeo.<br>**Then** puede recibir indicaciones de voz en tiempo real.                                                                                                                                         | EP02                      |
| HU04                 | Reconocimiento de objetos y muebles      | Como usuario no vidente, quiero que la aplicación reconozca objetos y muebles en mi hogar para recibir indicaciones precisas. | **Given** el usuario utiliza la aplicación.<br>**When** la aplicación detecta objetos y muebles.<br>**Then** proporciona indicaciones de voz claras.<br><br>**Given** el usuario ha completado el mapeo.<br>**When** navega con la aplicación.<br>**Then** reconoce objetos previamente mapeados y guía al usuario para evitar obstáculos.                                                                                                              | EP01                      |
| HU05                 | Notificaciones a cuidadores              | Como cuidador, quiero recibir notificaciones sobre la actividad del usuario no vidente para asegurarme de su seguridad.       | **Given** el cuidador configuró las notificaciones.<br>**When** el usuario realiza movimientos significativos o riesgosos.<br>**Then** recibe alertas en tiempo real.<br><br>**Given** el cuidador configuró notificaciones.<br>**When** el usuario se desplaza.<br>**Then** recibe información de su actividad para garantizar su seguridad.                                                                                                           | EP04                      |
| HU06                 | Acceso a la información de la aplicación | Como usuario no vidente, quiero acceder a la información de la aplicación a través de comandos de voz.                        | **Given** el usuario está en la aplicación.<br>**When** solicita información con un comando de voz.<br>**Then** la aplicación responde con voz de manera clara y concisa.                                                                                                                                                                                                                                                                               | EP05                      |
| HU07                 | Configuración de preferencias            | Como usuario no vidente, quiero configurar mis preferencias en la aplicación para personalizar mi experiencia.                | **Given** el usuario accede a la configuración.<br>**When** ajusta voz, notificaciones y parámetros.<br>**Then** la aplicación guarda y aplica las preferencias.                                                                                                                                                                                                                                                                                        | EP06                      |
| HU08                 | Reconocimiento de voz                    | Como usuario no vidente, quiero que la aplicación registre y reconozca mis comandos de voz para facilitar la interacción.     | **Given** el usuario configura comandos de voz personalizados.<br>**When** los utiliza.<br>**Then** la aplicación los reconoce y responde.<br><br>**Given** el usuario emite un comando.<br>**When** la aplicación lo recibe.<br>**Then** lo interpreta y responde adecuadamente.                                                                                                                                                                       | EP03                      |

#### 4.1.2.2. Quality attribute Scenarios.
En esta sección se describen los escenarios de atributos de calidad que impactan directamente en la arquitectura de la aplicación. Se priorizan aquellos que aseguran que el asistente visual inteligente cumpla con su propósito principal: brindar asistencia confiable, en tiempo real y accesible a personas no videntes dentro de un entorno controlado (el hogar).

Los atributos considerados en esta primera versión son:
- Precisión / Exactitud, para garantizar que el reconocimiento de objetos y muebles sea confiable.
- Latencia / Rendimiento, para que las respuestas de la aplicación se produzcan en tiempo real y sin retrasos.
- Usabilidad / Accesibilidad, para asegurar que la interacción con el sistema sea clara, sencilla y efectiva mediante comandos y retroalimentación por voz.

| Atributo | Fuente | Estímulo | Artefacto | Entorno | Respuesta | Medida |
| -------------------------- | ------------------ | ---------------------------------------------------------------------------- | ----------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Precisión / Exactitud      | Usuario no vidente | El usuario solicita identificar un objeto o mueble en el entorno.            | Módulo de reconocimiento de objetos | El sistema está operando en el hogar con mapeo previamente configurado. | El sistema procesa la imagen y emite una identificación de objeto clara y correcta.      | ≥ 90% de acierto en la detección de objetos mapeados.           |
| Latencia / Rendimiento     | Usuario no vidente | El usuario solicita indicaciones para moverse dentro del hogar.              | Módulo de guía en tiempo real       | El usuario está desplazándose en una habitación del hogar.              | El sistema genera y comunica la instrucción de voz en menos de un segundo.               | Tiempo de respuesta ≤ 1 segundo desde la solicitud del usuario. |
| Usabilidad / Accesibilidad | Usuario no vidente | El usuario da un comando de voz para acceder a información de la aplicación. | Módulo de interacción por voz       | El sistema está en uso normal, en ambiente hogareño.                    | El sistema reconoce el comando y responde con una instrucción de voz clara y entendible. | ≥ 95% de comandos de voz reconocidos correctamente.             |

#### 4.1.2.3. Constraints.
En esta sección se especifican las restricciones que no pueden ser negociadas en el diseño de la solución. Estas restricciones son impuestas por la naturaleza del proyecto y las necesidades del negocio, y deben cumplirse obligatoriamente en la implementación de la aplicación. En particular, se consideran los siguientes aspectos: el uso exclusivo en entornos controlados como el hogar, la obligatoriedad del mapeo previo del entorno, la accesibilidad completa mediante voz, la compatibilidad multiplataforma (Android e iOS) y la protección de los datos sensibles de los usuarios.

| Technical Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| ------------------ | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| C01                | Uso exclusivo en entornos controlados | La aplicación solo debe funcionar en espacios previamente mapeados del hogar y no en espacios públicos, garantizando seguridad del usuario. | **Given** que el usuario intente usar la app fuera del hogar, **When** no existe un mapa validado, **Then** la aplicación bloquea el uso y muestra un mensaje de advertencia por voz. | EP02, EP03                |
| C02                | Mapeo previo obligatorio              | Para habilitar la guía en tiempo real, es necesario realizar un mapeo previo del hogar mediante fotos y escaneos controlados.               | **Given** que el usuario no ha completado el mapeo, **When** intente activar la guía, **Then** la aplicación le solicita completar el proceso de mapeo antes de continuar.            | EP02, EP03                |
| C03                | Accesibilidad 100% por voz            | Toda la interacción debe estar disponible mediante comandos de voz, sin depender de la visión del usuario.                                  | **Given** que el usuario emite un comando de voz, **When** el sistema lo procesa, **Then** la aplicación responde de forma clara por voz, sin requerir acciones visuales.             | EP05, EP06                |
| C04                | Compatibilidad multiplataforma        | La aplicación debe funcionar en dispositivos móviles Android e iOS para asegurar la cobertura de usuarios.                                  | **Given** un dispositivo con Android o iOS, **When** el usuario descarga la aplicación, **Then** esta debe instalarse y ejecutarse correctamente en ambas plataformas.                | EP03, EP05                |
| C05                | Seguridad y privacidad de datos       | Los datos de mapeo, imágenes y voz deben ser procesados localmente o en entornos seguros, sin ser compartidos sin autorización del usuario. | **Given** que el sistema captura imágenes o voz, **When** se procesa la información, **Then** la aplicación garantiza que no se comparte sin consentimiento explícito del usuario.    | EP02, EP05                |

### 4.1.3. Architectural Drivers Backlog.
El conjunto de Architectural Drivers fue definido a partir del proceso iterativo realizado durante el Quality Attribute Workshop (QAW). En este proceso, nuestro equipo identificó y priorizó los requerimientos funcionales clave (Functional Drivers), los escenarios de atributos de calidad de mayor impacto (Quality Attribute Drivers) y las restricciones no negociables (Constraints). El resultado es un backlog que orienta directamente las decisiones de arquitectura, priorizando aquellos drivers de mayor importancia para los stakeholders y mayor impacto en la complejidad técnica de la solución.

| Driver ID | Título de Driver | Descripción | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
| --------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | -------------------------------------------- |
| FD01      | Guía en tiempo real                   | Permitir que el usuario reciba indicaciones de voz en tiempo real para moverse de manera segura en su hogar.                  | High                          | High                                         |
| FD02      | Mapeo del hogar                       | Crear un mapa del hogar a partir de fotografías y escaneos, base para el reconocimiento y la navegación.                      | High                          | High                                         |
| FD03      | Reconocimiento de objetos y muebles   | Detectar e identificar con precisión objetos y muebles en el entorno del usuario.                                             | High                          | Medium                                       |
| QAD01     | Precisión / Exactitud                 | El sistema debe reconocer objetos y muebles con al menos 90% de acierto en entornos controlados.                              | High                          | High                                         |
| QAD02     | Latencia / Rendimiento                | El sistema debe emitir respuestas en menos de 1 segundo para garantizar asistencia en tiempo real.                            | High                          | High                                         |
| QAD03     | Usabilidad / Accesibilidad            | La aplicación debe reconocer ≥95% de comandos de voz y responder de manera clara, sin requerir acciones visuales.             | High                          | Medium                                       |
| C01       | Uso exclusivo en entornos controlados | La aplicación no puede usarse en espacios públicos, solo en el hogar mapeado.                                                 | High                          | Medium                                       |
| C02       | Mapeo previo obligatorio              | El usuario debe completar el mapeo antes de acceder a la guía en tiempo real.                                                 | High                          | Medium                                       |
| C03       | Accesibilidad 100% por voz            | Toda la interacción debe realizarse mediante comandos y respuestas por voz.                                                   | High                          | Medium                                       |
| C04       | Compatibilidad multiplataforma        | La aplicación debe funcionar tanto en Android como en iOS.                                                                    | Medium                        | High                                         |
| C05       | Seguridad y privacidad de datos       | Los datos de imágenes, voz y mapeo deben procesarse localmente o de manera segura, evitando su exposición sin consentimiento. | High                          | High                                         |

### 4.1.4. Architectural Design Decisions.
El proceso de diseño arquitectónico se realizó siguiendo los stages del Quality Attribute Workshop (QAW). Para cada iteración, nuestro equipo revisó los drivers más relevantes, analizó posibles tácticas y patrones de diseño, y finalmente se seleccionó las alternativas más adecuadas considerando los criterios de precisión, rendimiento, seguridad y accesibilidad.

A continuación, se resumen las decisiones de diseño para los drivers priorizados, incluyendo la evaluación de patrones candidatos:

| Driver ID | Título de Driver | Pattern 1: **Event-Driven Architecture (EDA)** | | Pattern 2: **Microservices** | | Pattern 3: **Layered Architecture** | |
| --------- | ------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------- | -------------------------------------------------------------- |
| | | **Pro** | **Con** | **Pro** | **Con** | **Pro** | **Con** |
| FD01      | Guía en tiempo real             | Bajo acoplamiento, adecuado para manejar eventos en tiempo real.       | Mayor complejidad en el manejo de eventos concurrentes.  | Escalabilidad por servicios independientes.                        | Mayor esfuerzo de despliegue y comunicación entre servicios. | Simplicidad en la organización por capas.                     | Latencia más alta por pasos adicionales entre capas.           |
| QAD01     | Precisión / Exactitud           | Integración fácil de motores de IA como microservicios independientes. | Puede requerir más recursos y procesamiento distribuido. | Permite aislar el módulo de IA y escalarlo según demanda.          | Incrementa la complejidad de la arquitectura.                | Arquitectura conocida y simple de implementar.                | Riesgo de poca flexibilidad ante cambios en los modelos de IA. |
| QAD02     | Latencia / Rendimiento          | Procesamiento rápido de eventos en tiempo real.                        | Requiere infraestructura optimizada.                     | Microservicios especializados pueden reducir carga en cada módulo. | Sobrecarga de comunicación inter-servicios.                  | Simplicidad al procesar en capas secuenciales.                | Tiempo de respuesta mayor a lo esperado.                       |
| C05       | Seguridad y privacidad de datos | Control granular de flujos de datos mediante eventos seguros.          | Complejidad en encriptar y auditar eventos.              | Servicios aislados con control de acceso independiente.            | Necesidad de mayor gestión de seguridad distribuida.         | Claridad en manejo de datos en una capa dedicada a seguridad. | Difícil escalar seguridad en sistemas distribuidos.            |

### 4.1.5. Quality Attribute Scenario Refinements.
Al concluir el Quality Attribute Workshop, nuestro equipo priorizó los escenarios relacionados con la precisión en la detección de distracciones de los taxistas, la latencia y rendimiento en la respuesta en tiempo real y la usabilidad/accesibilidad de la aplicación móvil. Estos atributos fueron refinados en detalle para asegurar su alineación con los objetivos de negocio y guiar el diseño arquitectónico de la solución.

A continuación se presentan los escenarios refinados en orden de prioridad:

### Scenario Refinement for Scenario 1 – Precisión en la detección de distracciones
| **Scenario(s):**                 | El sistema debe detectar distracciones del taxista con un nivel de exactitud superior al 90%. |
| -------------------------------- | --------------------------------------------------------------------------------------------- |
| **Business Goals:**              | Reducir accidentes de tránsito y mejorar la seguridad vial en taxis mediante IA confiable.    |
| **Relevant Quality Attributes:** | Precisión / Exactitud                                                                         |
| **Stimulus:**                    | Una distracción del conductor (ej. mirar el celular, bostezar, cerrar los ojos).              |
| **Stimulus Source:**             | Taxista monitoreado a través de cámara del celular.                                           |
| **Environment:**                 | Entorno urbano con variaciones de luz y movimiento del vehículo.                              |
| **Components:**                  | Módulo de visión por computadora (modelo IA) y cámara del dispositivo.                        |
| **Artifact (if Known):**         | Motor de IA de detección de rostros y patrones de distracción.                                |
| **Response:**                    | El sistema identifica la distracción y genera una alerta.                                     |
| **Response Measure:**            | Precisión ≥ 90% en pruebas con dataset representativo.                                        |
| **Questions:**                   | ¿Cómo se garantiza la precisión en condiciones de baja iluminación?                           |
| **Issues:**                      | Necesidad de entrenar el modelo con datasets balanceados de distracciones reales.             |


### Scenario Refinement for Scenario 2 – Latencia en la detección y alerta
| **Scenario(s):**                 | El sistema debe generar una alerta en menos de 1 segundo desde que ocurre la distracción. |
| -------------------------------- | ----------------------------------------------------------------------------------------- |
| **Business Goals:**              | Garantizar una reacción inmediata para prevenir riesgos de accidente.                     |
| **Relevant Quality Attributes:** | Rendimiento / Latencia                                                                    |
| **Stimulus:**                    | Evento de distracción detectado por el modelo IA.                                         |
| **Stimulus Source:**             | Procesamiento de video en tiempo real.                                                    |
| **Environment:**                 | Aplicación corriendo en smartphone Android/iOS de gama media.                             |
| **Components:**                  | Motor de IA optimizado para dispositivos móviles, módulo de notificaciones.               |
| **Artifact (if Known):**         | Framework de inferencia (ej. TensorFlow Lite).                                            |
| **Response:**                    | Mostrar alerta visual y sonora al taxista.                                                |
| **Response Measure:**            | Tiempo de respuesta ≤ 1 segundo en al menos el 95% de los casos.                          |
| **Questions:**                   | ¿Qué pasa si el procesamiento excede el tiempo por sobrecarga del dispositivo?            |
| **Issues:**                      | Balance entre precisión del modelo y tiempo de inferencia.                                |

### Scenario Refinement for Scenario 3 – Usabilidad y accesibilidad de la aplicación
| **Scenario(s):**                 | La aplicación debe ser fácil de usar y accesible para taxistas de distintos perfiles.                  |
| -------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Business Goals:**              | Maximizar adopción de la solución y asegurar que los taxistas puedan usarla sin capacitación compleja. |
| **Relevant Quality Attributes:** | Usabilidad / Accesibilidad                                                                             |
| **Stimulus:**                    | El taxista inicia y usa la aplicación mientras conduce.                                                |
| **Stimulus Source:**             | Interacción directa del usuario.                                                                       |
| **Environment:**                 | Conducción en tránsito real con necesidad de mínima distracción.                                       |
| **Components:**                  | Interfaz de usuario móvil (Android/iOS).                                                               |
| **Artifact (if Known):**         | UI/UX con accesibilidad (botones grandes, alertas claras, soporte de voz).                             |
| **Response:**                    | La aplicación se puede usar de forma intuitiva y sin desviar la atención de la conducción.             |
| **Response Measure:**            | Tiempo de aprendizaje ≤ 5 minutos; error de interacción ≤ 5%.                                          |
| **Questions:**                   | ¿Cómo garantizar la accesibilidad para taxistas con limitaciones visuales o auditivas?                 |
| **Issues:**                      | Equilibrar simplicidad de UI con la inclusión de funcionalidades críticas.                             |


## 4.2. Strategic-Level Domain-Driven Design.
### 4.2.1. EventStorming.
### 4.2.2. Candidate Context Discovery.
### 4.2.3. Domain Message Flows Modeling.
### 4.2.4. Bounded Context Canvases.
### 4.2.5. Context Mapping.

## 4.3. Software Architecture.
Los diagramas de arquitectura de software se han creado utilizando el enfoque C4 Model, que proporciona una manera clara y estructurada de representar la arquitectura del sistema en diferentes niveles de detalle. A continuación, se presentan los diagramas correspondientes a cada nivel del modelo C4 para la aplicación "VisualGuide".
URL Structurizr: https://structurizr.com/workspace/101375

### 4.3.1. Software Architecture System Landscape Diagram.
A continuación se demuestra el System Landscape Diagram de la solución propuesta "VisualGuide", una aplicación móvil diseñada para asistir a personas no videntes en la navegación segura dentro de sus hogares mediante el uso de inteligencia artificial y reconocimiento de objetos.

En este diagrama, se ilustran los principales componentes y su interacción dentro del ecosistema de la aplicación:
- **Usuario (Persona No Vidente):** El usuario principal de la aplicación, que interactúa con la interfaz móvil para recibir indicaciones y feedback en tiempo real.
- **Familiar o Cuidador:** Un usuario secundario que puede supervisar y apoyar al usuario principal, recibiendo notificaciones sobre su actividad.
- **Sistema de VisualGuide:** La aplicación móvil que utiliza inteligencia artificial para mapear el hogar, reconocer objetos y proporcionar guía en tiempo real.
- **Servicios externos:** Incluye servicios de email y pagos para la gestión de cuentas y suscripciones.

<img src="./images/c4-model/landscape-diagram.png" alt="System Landscape Diagram" width="auto">

### 4.3.1. Software Architecture Context Level Diagrams.

Nuestro diagrama de contexto de la arquitectura de software para la aplicación "VisualGuide" muestra cómo interactúa el sistema con sus usuarios y otros sistemas externos. En el centro del diagrama se encuentra el sistema principal, "VisualGuide", que es una aplicación móvil diseñada para asistir a personas no videntes en la navegación segura dentro de sus hogares mediante inteligencia artificial y reconocimiento de objetos.

<img src="./images/c4-model/context-diagram.png" alt="Context Level Diagram" width="auto">

### 4.3.2. Software Architecture Container Level Diagrams.

A continuación, se presenta el diagrama de nivel de contenedores para la aplicación "VisualGuide". Este diagrama detalla los principales contenedores que componen el sistema y cómo interactúan entre sí para proporcionar la funcionalidad necesaria a los usuarios.

Como protagonistas de este sistema se encuentran los usuarios no videntes y sus cuidadores, quienes interactúan principalmente con la aplicación móvil "VisualGuide". Esta aplicación es el contenedor principal que ofrece la interfaz de usuario y la lógica de negocio para mapear el hogar, reconocer objetos y proporcionar guía en tiempo real.

VisualGuide estará servida en el dispositivo móvil del usuario, bajo el framework de Flutter, que permite una experiencia de usuario fluida y accesible. La aplicación se comunica con varios servicios backend a través de APIs RESTful para gestionar datos, autenticación y procesamiento de inteligencia artificial.

Nuestro backend está construido con Python 3.11 y Flask, alojado en un servidor Linux Ubuntu 22.04 LTS. Este backend maneja la lógica de negocio, el procesamiento de datos y la integración con servicios externos como bases de datos y servicios de pago. Asimismo, nuestro modelo de inteligencia artificial, desarrollado con Pytorch, YOLOv8 y OpenCV, se encarga del reconocimiento de objetos y la interpretación del entorno del hogar, proporcionando la información necesaria para guiar al usuario, comunicándose con el backend a través de APIs RESTful.

Nuestro sistema utiliza una base de datos MySQL 8.0 para almacenar información del usuario, configuraciones y datos de mapeo del hogar. Además, se integra una base de datos de objetos S3 Bucket para almacenar imágenes y datos relacionados con el reconocimiento de objetos.

<img src="./images/c4-model/container-diagram.png" alt="Container Level Diagram" width="auto">

### 4.3.3. Software Architecture Deployment Diagrams.

A continuación, se presenta el diagrama de despliegue para la aplicación "VisualGuide". Este diagrama ilustra cómo los diferentes componentes del sistema están distribuidos en el entorno de producción y cómo interactúan entre sí para ofrecer una experiencia fluida y segura a los usuarios.

La aplicación móvil "VisualGuide" se ejecuta en dispositivos móviles de los usuarios, quienes son principalmente personas no videntes y sus cuidadores. Se encuentra desplegado mediante Firebase App Distribution, lo que facilita la distribución y actualización de la aplicación en los dispositivos de los usuarios.

Nuestra landing page se encuentra servido en Vercel, proporcionando información sobre la aplicación y facilitando el acceso a la descarga de la misma. Esta página web está diseñada para ser accesible y fácil de navegar, asegurando que los usuarios puedan encontrar rápidamente la información que necesitan.

El backend de la aplicación está alojado en un servidor Linux Ubuntu 22.04 LTS, utilizando EC2 Instance AWS como servidor de aplicaciones y Docker containers como servidor web. Este backend maneja la lógica de negocio, la gestión de datos y la integración con servicios externos, asegurando una comunicación eficiente y segura con la aplicación móvil a través de APIs RESTful. Nuestro modelo entrenado de inteligencia artificial, desarrollado con Pytorch, YOLOv8 y OpenCV, está desplegado en un servidor local con Windows 10, Ryzen 7 5700G / Intel I7 y 16GB / 32GB RAM, y se comunica con el backend para proporcionar capacidades de reconocimiento de objetos y análisis del entorno.

La base de datos MySQL 8.0 está alojada como contenedor dentro del servidor backend, gestionando la información del usuario, configuraciones y datos de mapeo del hogar. Además, utilizamos un S3 Bucket AWS para almacenar imágenes y datos relacionados con el reconocimiento de objetos, asegurando un acceso rápido y seguro a estos recursos.

<img src="./images/c4-model/deployment-diagram.PNG" alt="Deployment Level Diagram" width="auto">
