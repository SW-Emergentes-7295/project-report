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

#### Startup: **Nombre**

#### Product: **Nombre**

</center>

## Team  Members:

<div align="center">

|               Member                |    Code    |
| :---------------------------------: | :--------: |
| Rodriguez Vargas, Arian Martín  | U202212096 |
|   | U202|
|   | U202 |
|   | U202|



</div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

---

# Project Report Collaboration Insights

En esta sección, registraremos los cambios y logros que se completaron en cada entrega del reporte.

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
### 2.1.1. Análisis competitivo.
### 2.1.2. Estrategias y tácticas frente a competidores.

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
### 2.2.2. Registro de entrevistas.
### 2.2.3. Análisis de entrevistas.

## 2.3. Needfinding.
### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. Empathy Mapping.
### 2.3.4. As-is Scenario Mapping.

## 2.4. Ubiquitous Language.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.
## 3.3. Impact Mapping.
## 3.4. Product Backlog.

# Capítulo IV: Strategic-Level Software Design.
## 4.1. Strategic-Level Attribute-Driven Design.
### 4.1.1. Design Purpose.
### 4.1.2. Attribute-Driven Design Inputs.
#### 4.1.2.1. Primary Functionality (Primary User Stories).
#### 4.1.2.2. Quality attribute Scenarios.
#### 4.1.2.3. Constraints.
### 4.1.3. Architectural Drivers Backlog.
### 4.1.4. Architectural Design Decisions.
### 4.1.5. Quality Attribute Scenario Refinements.

## 4.2. Strategic-Level Domain-Driven Design.
### 4.2.1. EventStorming.
### 4.2.2. Candidate Context Discovery.
### 4.2.3. Domain Message Flows Modeling.
### 4.2.4. Bounded Context Canvases.
### 4.2.5. Context Mapping.

## 4.3. Software Architecture.
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
### 4.3.3. Software Architecture Deployment Diagrams.
