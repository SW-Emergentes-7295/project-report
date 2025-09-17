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
### 2.2.3. Análisis de entrevistas.

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
   </tbody>
</table>
    

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
