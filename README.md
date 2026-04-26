<div align="center">

![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Universidad Peruana de Ciencias Aplicadas

Carrera: Ingeniería de Software

Ciclo: 2026-10

Curso: Arquitecturas De Software Emergentes

Sección: 11806

Profesor: Christian Luis De Los Rios Fernandez

Informe de TB1 

Startup: OnControl Team

Producto: OnControl

### Team Members:

| Member                          | Code       |
|---------------------------------|------------|
| Barrutia Vaez, Ricardo Andree   | U201714765 |
| Espinoza Inoñan, Fabiola Ximena | U202214784 |
| Holguin Gamarra, Hardie Alfonso | U202220250 |
| Espejo Gamarra, Bryan Ronnald   | U202213278 |
| Ramos Mendoza, Juan Pablo       | U202019545 |


**Abril del 2026**

</div>



# Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| Versión | Fecha | Autor | Descripción de modificación |
| :-----: | :---: | :---: | --------------------------- |
|    0.0    |   12/04/26   |   Grupo   | Creación del repositorio |
|    1.0    |   26/04/26   |   Grupo   | Desarrollo del TB1       |


# Project Report Collaboration Insights

URL del repositorio para el reporte del proyecto: 

**TB1**

<div align="center">
  <img src="https://github.com/user-attachments/assets/1de75326-c8d6-448d-9c95-85009f775fc3" alt="insights">
</div>


**Github Collaboration Insights**

Github también presenta un timeline de las ramas principales y los procesos de merge a los que se han sometido. Todas las ramas se crearon tomando en cuenta el diseño de GitFlow para una buena organización cuando se usa un software de control de versiones.

| Integrante                       | User       |
|----------------------------------|------------|
| Holguin Gamarra, Hardie Alfonso  | HOLGUINUPC |
|Espejo Gamarra, Bryan Ronald      | SAEBRYXN|
| NOMBRE                           | USER       |
| NOMBRE                           | USER       |
| Ramos Mendoza, Juan Pablo        | JJPPRRMM   |



# Contenido

1. [**Capítulo I: Introducción**](#1.) <br>
   1.1. [Startup Profile](#1.1.) <br>
   1.1.1. [Descripción de la Startup](#1.1.1.)<br>
   1.1.2. [Perfiles de integrantes del equipo](#1.1.2.)<br>
   1.2. [Solution Profile](#1.2.)<br>
   1.2.1. [Antecedentes y problemática](#1.2.1.)<br>
   1.2.2. [Lean UX Process.](#1.2.2.)<br>
   1.2.2.1. [Lean UX Problem Statements.](#1.2.2.1.)<br>
   1.2.2.2. [Lean UX Assumptions.](#1.2.2.2.)<br>
   1.2.2.3. [Lean UX Hypothesis Statements.](#1.2.2.3.)<br>
   1.2.2.4. [Lean UX Canvas.](#1.2.2.4.)<br>
   1.3. [Segmentos objetivo.](#1.3.)<br>

2. [**Capítulo II: Requirements Elicitation & Analysis**](#2.)<br>
   2.1. [Competidores.](#2.1.)<br>
   2.1.1. [Análisis competitivo.](#2.1.1.)<br>
   2.1.2. [Estrategias y tácticas frente a competidores.](#2.1.2.)<br>
   2.2. [Entrevistas.](#2.2.)<br>
   2.2.1. [Diseño de entrevistas.](#2.2.1.)<br>
   2.2.2. [Registro de entrevistas.](#2.2.2.)<br>
   2.2.3. [Análisis de entrevistas.](#2.2.3.)<br>
   2.3. [Needfinding.](#2.3.)<br>
   2.3.1. [User Personas.](#2.3.1.)<br>
   2.3.2. [User Task Matrix.](#2.3.2.)<br>
   2.3.3. [Empathy Mapping.](#2.3.3.)<br>
   2.3.4. [As-is Scenario Mapping.](#2.3.4.)<br>
   2.4. [Ubiquitous Language.](#2.4.)<br>

3. [**Capítulo III: Requirements Specification**](#3.)<br>
   3.1. [To-Be Scenario Mapping.](#3.1.)<br>
   3.2. [User Stories.](#3.2.)<br>
   3.3. [Impact Mapping.](#3.3.)<br>
   3.4. [Product Backlog.](#3.4.)<br>

4. [**Capítulo IV: Strategic-Level Software Design.**](#4.)<br>
   4.1. [Strategic-Level Attribute-Driven Design.](#4.1.)<br>
   4.1.1. [Design Purpose.](#4.1.1.)<br>
   4.1.2. [Attribute-Driven Design Inputs.](#4.1.2.)<br>
   4.1.2.1. [Primary Functionality (Primary User Stories).](#4.1.2.1.)<br>
   4.1.2.2. [Quality attribute Scenarios.](#4.1.2.2.)<br>
   4.1.2.3. [Constraints.](#4.1.2.3.)<br>
   4.1.3. [Architectural Drivers Backlog.](#4.1.3.)<br>
   4.1.4. [Architectural Design Decisions.](#4.1.4.)<br>
   4.1.5. [Quality Attribute Scenario Refinements.](#4.1.5.)<br>
   4.2. [Strategic-Level Domain-Driven Design.](#4.2.)<br>
   4.2.1. [EventStorming.](#4.2.1.)<br>
   4.2.2. [Candidate Context Discovery.](#4.2.2.)<br>
   4.2.3. [Domain Message Flows Modeling.](#4.2.3.)<br>
   4.2.4. [Bounded Context Canvases.](#4.2.4.)<br>
   4.2.5. [Context Mapping.](#4.2.5.)<br>
   4.3. [Software Architecture.](#4.3.)<br>
   4.3.1. [Software Architecture System Landscape Diagram.](#4.3.1.)<br>
   4.3.2. [Software Architecture Context Level Diagrams.](#4.3.2.)<br>
   4.3.3. [Software Architecture Container Level Diagrams.](#4.3.3.)<br>
   4.3.4. [Software Architecture Deployment Diagrams.](#4.3.4.)<br>

7. [**Conclusiones.**](#7.)<br>
8. [**Bibliografía.**](#8.)<br>
9. [**Anexo.**](#9.)<br>

# STUDENT OUTCOME

**ABET – EAC - Student Outcome 3** <br><br>
**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias*

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="font-weight:bold">Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.</td>
      <td>
      <strong>NOMBRE</strong> <br>
      <strong>TB1:</strong> <p align="justify">Contenido </p><br>
      <strong>NOMBRE</strong> <br>
      <strong>TB1:</strong> <p align="justify">Contenido </p><br>
      <strong>NOMBRE</strong> <br>
      <strong>TB1:</strong> <p align="justify">Contenido </p><br>
      <strong>NOMBRE</strong> <br>
      <strong>TB1:</strong> <p align="justify">Contenido </p><br>
      <strong>Ramos Mendoza, Juan Pablo</strong> <br>
      <strong>TB1:</strong> <p align="justify">Contenido </p><br>
      </td>
      <td>
        <strong>TB1:</strong><br>
        Contenido
      </td>
    </tr>
    <tr>
      <td  style="font-weight:bold">Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería..</td>
      <td>
        <strong>Nombre</strong> <br>
         <strong>TB1:</strong> <p align="justify">Contenido </p><br>
         <strong>Nombre</strong> <br>
         <strong>TB1:</strong> <p align="justify">Contenido </p><br>
         <strong>Nombre</strong> <br>
         <strong>TB1:</strong> <p align="justify">Contenido </p><br>
         <strong>Nombre</strong> <br>
         <strong>TB1:</strong> <p align="justify">Contenido </p><br>
         <strong>Ramos Mendoza, Juan Pablo</strong> <br>
         <strong>TB1:</strong> <p align="justify">Contenido </p><br>
      </td>
      <td>
        <strong>TB1:</strong><br>
        Contenido
      </td>
    </tr>
  </tbody>
</table>

<div id='1.'><h2>1. Capítulo I: Introducción</h2></div>

<div id='1.1.'><h3>1.1. Startup Profile</h3></div>
<div id='1.1.1.'><h4>1.1.1. Descripción del startup</h4></div>
OnControl es una aplicación creada por alumnos de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC), con el objetivo de ofrecer apoyo y organización tanto a pacientes oncológicos como a médicos oncólogos en el sector de la salud peruano. Reconocemos las complejidades y desafíos que enfrentan estos dos grupos en el proceso de tratamiento del cáncer, por lo que buscamos darles la importancia debida.

OnControl ofrece una plataforma integral que facilita la gestión de pacientes y la organización de su información. Los médicos pueden administrar eficientemente los datos y horarios de sus pacientes, asignar tratamientos y procedimientos, y visualizar la evolución clínica mediante un dashboard especializado. Los pacientes, por su parte, pueden acceder a un calendario digital para consultar sus citas médicas, procedimientos y tratamientos.

Como valor diferencial, OnControl integra sensores IoT que permiten medir parámetros vitales como saturación de oxígeno, ritmo cardíaco y temperatura corporal. Estos datos se registran y muestran en la aplicación del paciente y en la plataforma web del médico, generando alertas cuando se exceden los rangos saludables y contribuyendo a una atención más segura y oportuna.

- **Misión:** Mejorar la calidad de vida de pacientes oncológicos y optimizar el seguimiento médico mediante herramientas tecnológicas innovadoras.

- **Visión:** Ser la plataforma líder en salud oncológica digital en el Perú, reconocida por nuestra innovación, accesibilidad y compromiso con la atención integral.

</ul>
<div id='1.1.2.'><h4>1.1.2. Perfiles de los integrantes del equipo</h4></div>

<table>
  <tr>
    <th>Miembro del equipo</th>
    <th>Descripción</th>
    <th>Codigo de usuario</th>
  </tr>

  <tr>
    <td><img width="288" height="288" alt="image" src="https://github.com/user-attachments/assets/e272e82b-1c01-47f4-94fd-0113fef356f4" />
</td>
    <td>Soy estudiante de la carrera de ingeneria de software Ingeniero Full Stack Multilingüe: Especialista en el desarrollo de ecosistemas digitales complejos utilizando un stack robusto que incluye C# para arquitecturas empresariales, Kotlin y Flutter para movilidad nativa/híbrida, y frameworks modernos como Vue.js, Angular y React para interfaces de usuario de alta interactividad. Arquitecto de Datos y Persistencia: Experto en el diseño y optimización de bases de datos utilizando SQL Server (Management Studio) para entornos a gran escala y SQLite para soluciones de almacenamiento local y offline-first en dispositivos móviles. Especialista en Infraestructura y Contenedores: Dominio de Docker para la contenedorización de microservicios, asegurando que el sistema sea portable, escalable y fácil de desplegar en cualquier entorno cloud.Líder Ágil y Coordinador Técnico: Certificado en la práctica de metodologías Scrum, liderando la coordinación técnica del equipo para asegurar entregas incrementales de valor y una integración perfecta entre el hardware IoT y el software transaccional. Entornos de Desarrollo: Manejo experto de IDEs profesionales como Eclipse, VS Code y Android Studio para la gestión eficiente del ciclo de vida del software.</td>
    <td>U202213278</td>
  </tr> 
  <tr>
    <td><img src=""></td>
    <td>Descripcion</td>
    <td>Codigo</td>
  </tr>  
  <tr>
    <td><img src=""></td>
    <td>Descripcion</td>
    <td>Codigo</td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/fb07e471-36a2-4fa7-9234-178869d3d3b7"></td>
    <td>Soy Juan Pablo Ramos, me encuentro en el quinto ciclo de Ingeniería de Software. En términos de programación tengo precedente en C++. Al momento de trabajar en grupos siempre trato de mantener el orden entre las partes de los miembros y apoyar en el desarrollo de las presentaciones.</td>
    <td>U202019545</td>
  </tr>
  <tr>
    <td><img src=""></td>
    <td>Dexcripcion</td>
    <td>Codigo</td>
  </tr>
</table>
<div id='1.2.'><h3>1.2. Solution Profile</h3></div>
<div id='1.2.1.'><h4>1.2.1. Antecedentes y Problemática</h4></div>

* **What – ¿Cuál es el problema?** <br>
  El cuidado oncológico en el Perú presenta deficiencias en la gestión de citas médicas, el seguimiento de tratamientos y la organización de la información clínica, generando ineficiencia en la atención y disminuyendo la calidad del servicio.

* **When – ¿Cuándo sucede el problema?** <br>
  El problema es recurrente y persistente, ya que los pacientes y médicos deben enfrentarlo diariamente debido a la falta de herramientas digitales de soporte en el proceso oncológico.

* **Where – ¿Dónde surge el problema?** <br>
  Esta situación se presenta en hospitales, clínicas y centros oncológicos tanto públicos como privados del país, donde la demanda supera la capacidad de organización de los sistemas actuales.

* **Who – ¿Quiénes son afectados?** <br>
  Los principales afectados son los pacientes oncológicos y sus familias, quienes experimentan mayor ansiedad y desinformación; y los médicos oncólogos, que enfrentan sobrecarga laboral y riesgo de agotamiento profesional. También repercute en el desempeño de equipos médicos multidisciplinarios.

* **Why – ¿Cuál es la causa?** <br>
  La raíz del problema se encuentra en la ausencia de soluciones tecnológicas integrales y procesos optimizados que permitan centralizar la información, facilitar el seguimiento del tratamiento y mejorar la comunicación entre los distintos actores del cuidado oncológico.

* **How – ¿Cómo ocurre?** <br>
  La gestión continúa realizándose mediante métodos manuales o fragmentados, lo que conlleva a retrasos, duplicación de esfuerzos, errores en la administración de medicamentos y dificultades para mantener una comunicación fluida entre médicos y pacientes.

* **How much – ¿Cuál es la magnitud?** <br>
  La magnitud es considerable: en Perú, más del 60 % de los casos de cáncer son diagnosticados en etapas avanzadas (MINSA, 2023), lo que refleja la falta de seguimiento temprano. Además, más del 45 % de oncólogos reportan síntomas de agotamiento profesional (Shanafelt et al., 2014), lo que evidencia el impacto negativo tanto en la calidad de vida de los pacientes como en la capacidad operativa del personal de salud.
  <br>

<div align="center">
  <img width="685" height="445" alt="image" src="https://github.com/user-attachments/assets/627df46e-20ae-4c06-821a-8c41eb801218" />
  <p><em>Grafica 1: Tendencias de mortalidad por cáncer en el Perú.</em></p>
</div>

<div id='1.2.2.'><h4>1.2.2. Lean UX Process</h4></div>

<div id='1.2.2.1.'><h5>1.2.2.1. Lean UX Problem Statements</h5></div>

El tratamiento y cuidado de los pacientes con cáncer suele ser un proceso agotador y complejo. La falta de información clara, organización adecuada y comprensión del proceso terapéutico incrementa significativamente la ansiedad y el estrés tanto en los pacientes como en sus familiares. En el Perú, más del 60 % de los casos son diagnosticados en etapas avanzadas, lo que agrava aún más esta situación (MINSA, 2023).

Al mismo tiempo, los médicos oncólogos enfrentan una elevada carga asistencial, gestionando múltiples pacientes con horarios y tratamientos altamente específicos que requieren un seguimiento constante. Esta realidad contribuye a la sobrecarga laboral y al desgaste profesional, con estudios que señalan que más del 45 % de oncólogos presentan síntomas de agotamiento (Shanafelt et al., 2014).

Frente a la falta de herramientas que faciliten el acceso a información sobre medicamentos, la organización de citas y la coordinación del tratamiento, surge una interrogante fundamental:

<br><br><div align="center">
**¿Qué soluciones tecnológicas pueden contribuir a mejorar la coordinación en la atención oncológica y garantizar un proceso más claro y menos estresante para pacientes, familiares y médicos?**

</div>

<div id='1.2.2.2.'><h5>1.2.2.2. Lean UX Assumptions</h5></div>

**Features (Características):**

* Interfaz intuitiva y de fácil acceso para médicos y pacientes.
* Aplicación móvil gratuita para pacientes.
* Calendario digital para visualizar citas y tratamientos.
* Herramientas de planificación para el seguimiento clínico.
* Monitoreo de signos vitales mediante sensores IoT (ritmo cardíaco, temperatura y oxigenación).
* Alertas automáticas cuando los parámetros vitales sobrepasen los rangos saludables.

**Business Assumptions (Supuestos de negocio):**

* Creemos que los pacientes oncológicos valoran una plataforma que centralice información confiable sobre sus citas, tratamientos y monitoreo de salud.
* Creemos que los familiares se beneficiarán de una mayor claridad sobre el estado del paciente, lo que generará confianza y reducirá su ansiedad.
* Creemos que la digitalización del seguimiento y el monitoreo de parámetros vitales permitirá a los médicos optimizar su tiempo y reducir su carga laboral.

**Business Outcomes (Resultados esperados):**

* Los usuarios incrementarán el uso de la aplicación al percibir mayor facilidad de acceso a información y a su estado de salud.
* Los pacientes experimentarán una mejor gestión y seguimiento de sus citas y tratamientos.
* Se contribuirá a mejorar el estado emocional de pacientes y familiares, lo que impactará positivamente en la adherencia al tratamiento.

**User Benefits (Beneficios para el usuario):**

* Mayor seguridad y confianza al contar con un monitoreo constante de signos vitales.
* Reducción del estrés y la ansiedad de pacientes y familiares gracias a un sistema más claro y organizado.
* Organización más eficiente para los médicos tratantes, al poder gestionar múltiples casos y recibir alertas tempranas.

<div id='1.2.2.3.'><h5>1.2.2.3. Lean UX Hypothesis Statements</h5></div>

* **Hypothesis 1:**
  Creemos que el monitoreo de signos vitales (ritmo cardíaco, temperatura y oxigenación) mediante sensores IoT ayudará a los pacientes a sentirse más protegidos y permitirá a los médicos detectar posibles alertas tempranas. Será exitoso cuando al menos el 65 % de los usuarios expresen que la aplicación les da una sensación de mayor seguridad en su cuidado.

* **Hypothesis 2:**
  Creemos que los médicos oncólogos mejorarán la organización de sus pacientes al centralizar en una sola plataforma la información de citas, tratamientos y parámetros vitales. Consideraremos alcanzado el objetivo cuando, en entrevistas posteriores, al menos el 70 % de los médicos reporten una disminución en los errores organizativos o en la duplicidad de esfuerzos.

* **Hypothesis 3:**
  Creemos que el envío de alertas automáticas cuando los parámetros vitales sobrepasen los rangos saludables permitirá reaccionar con mayor rapidez ante situaciones de riesgo. Será considerado un éxito cuando al menos el 60 % de los usuarios reconozcan que las alertas les ayudaron a tomar decisiones preventivas oportunas.

<div id='1.2.2.4.'><h5>1.2.2.4. Lean UX Canvas</h5></div>
En esta sección se presenta el Lean UX Canvas de la propuesta, donde se detallan los supuestos clave del proyecto, las necesidades de los usuarios, las posibles soluciones y las hipótesis que guiarán el proceso de validación.
<br>
<br>

<div align="center">
  <img alt="Lean UX Canvas" src="https://github.com/user-attachments/assets/2815bd95-18a2-484d-bb0f-f26c9a17959b"/>
</div>
  <p><em>Grafica 2: Lean UX Canvas Control</em></p>


<div id='1.3.'><h3>1.3. Segmentos objetivo</h3></div>


Nuestra aplicación está dirigida a **médicos oncólogos y pacientes oncológicos en el Perú**, creando un espacio digital que facilite la organización, el seguimiento del tratamiento y la comunicación en la atención oncológica.

Los **médicos oncólogos** requieren herramientas para **optimizar la gestión de citas, el registro de historias clínicas y el monitoreo del progreso de sus pacientes**, lo que les permite reducir la carga administrativa y mejorar la calidad de la atención.

Por su parte, los **pacientes oncológicos** necesitan un canal confiable para **agendar citas, recibir recordatorios, registrar sus signos vitales y consultar su historial médico**, además de contar con un apoyo digital que los acompañe en su proceso terapéutico.

| Segmento                  | Característica principal                              | Rango de edad | Necesidades clave                                                                                     | Nivel tecnológico                                                                    |
| ------------------------- | ----------------------------------------------------- | ------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Médicos oncólogos**     | Profesionales de la salud especializados en oncología | 30 – 55 años  | Gestión de pacientes y citas, registro de historias clínicas, monitoreo del progreso de pacientes     | Familiarizados con dispositivos móviles y computadoras                               |
| **Pacientes oncológicos** | Personas en tratamiento o seguimiento oncológico      | 25 – 65 años  | Reserva de citas, recordatorios de tratamiento, registro de signos vitales, acceso a historial médico | Varía según el caso, pero en general utilizan smartphones como principal dispositivo |

<div id='2.'><h2>2. Capítulo II: Requirements Elicitation & Analysis</h2></div>

<div id='2.1.'><h3>2.1. Competidores</h3></div>

<div id='2.1.1.'><h4>2.1.1. Análisis competitivo</h4></div>

<table>
  <tr>
    <th colspan="6" valign="top"><b>Análisis Competitivo</b></th>
  </tr>
  <tr>
    <td colspan="1" rowspan="2" valign="top">¿Por qué llevar a cabo este Análisis?</td>
    <td colspan="5" valign="top">Este análisis nos ayudará a comprender mejor a nuestra competencia, identificando sus debilidades y fortalezas. Esto nos permitirá desarrollar estrategias para mejorar nuestro producto.</td>
  </tr>
  <tr></tr>
 <tr>
  <td colspan="2" valign="top"></td>
  <td colspan="1" valign="top" style="vertical-align: middle; text-align: center;">
    <img src="https://github.com/user-attachments/assets/c3077ee6-d023-483c-91f4-df3c7e19239d"/>
  </td>
  <td colspan="1" valign="top" style="vertical-align: middle; text-align: center;">
    <img src="https://github.com/user-attachments/assets/34b15363-fc7b-481f-949d-168c867739b7"/>
  </td>
  <td colspan="1" valign="top" style="vertical-align: middle; text-align: center;">
    <img src="https://github.com/user-attachments/assets/b612f6a1-24d5-41ba-bfad-310987addd8e"/>
  </td>
  <td colspan="1" valign="top" style="vertical-align: middle; text-align: center;">
    <img src="https://github.com/user-attachments/assets/4d4bcfd7-0cf5-4b0d-82f8-ba4968255948"/>
  </td>
</tr>

  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Aplicación móvil que ofrece información y consejos de cuidado emocional, nutricional y físico para pacientes con cáncer.</td>
    <td valign="top">Aplicación que brinda apoyo personalizado a pacientes con cáncer.</td>
    <td valign="top">Aplicación que permite a los médicos monitorear pacientes mediante encuestas diarias.</td>
    <td valign="top">Aplicación móvil para pacientes y aplicación web para médicos, con herramientas de organización y planificación de tratamientos oncológicos.</td>
  </tr>
  <tr>
    <td valign="top">¿Qué valor ofrece a los clientes?</td>
    <td valign="top">Brinda consejos y ejercicios para la salud física y mental durante el tratamiento.</td>
    <td valign="top">Ofrece seguimiento de la salud del paciente y recomienda clínicas para exámenes y tratamientos.</td>
    <td valign="top">Proporciona herramientas para el monitoreo continuo del estado del paciente.</td>
    <td valign="top">Facilita la organización de citas y tratamientos, así como calendarios personalizados que reducen la carga de pacientes y médicos.</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">Personas que inician o continúan tratamiento oncológico.</td>
    <td valign="top">Pacientes que buscan o ya reciben tratamiento.</td>
    <td valign="top">Pacientes que requieren acompañamiento en todo su tratamiento.</td>
    <td valign="top">Médicos oncólogos con alta carga laboral y pacientes que necesitan una mejor organización.</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Promoción en su sitio web.</td>
    <td valign="top">Webinars y videos en su sitio web.</td>
    <td valign="top">Prueba gratuita para luego migrar a planes pagos.</td>
    <td valign="top">Landing page informativa y difusión en canales digitales de salud.</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Consejos de nutrición, ejercicios físicos y apoyo emocional durante el tratamiento.</td>
    <td valign="top">Monitoreo del paciente y acceso a información sobre tipos de cáncer y clínicas recomendadas.</td>
    <td valign="top">Monitoreo diario, consejos de nutrición, ejercicio y manejo del estrés.</td>
    <td valign="top">Calendarios de citas, alarmas y recordatorios, además de una plataforma web para médicos y móvil para pacientes.</td>
  </tr>
  <tr>
    <td valign="top">Precios y costos</td>
    <td valign="top">Gratuita.</td>
    <td valign="top">De uso gratuito y sin restricciones.</td>
    <td valign="top">Modelos de suscripción con opciones gratuitas y de pago.</td>
    <td valign="top">Planes Free, Premium y Pro Service.</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución</td>
    <td valign="top">Aplicación móvil (Google Play y App Store).</td>
    <td valign="top">Aplicación móvil (Google Play y App Store) + Web App.</td>
    <td valign="top">Aplicación móvil (Google Play y App Store).</td>
    <td valign="top">Aplicación móvil (pacientes), Aplicación web (médicos) y landing page de acceso.</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">Variedad de información científica validada.</td>
    <td valign="top">Apoyo de especialistas y amplia información de clínicas.</td>
    <td valign="top">Gran variedad de herramientas, gestión de síntomas e información de tratamientos.</td>
    <td valign="top">Facilita la comunicación y organización de citas con un calendario interactivo.</td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">Carece de interacción directa con usuarios.</td>
    <td valign="top">Limitada a ciertos tipos de cáncer.</td>
    <td valign="top">No ofrece comunicación directa con un médico.</td>
    <td valign="top">Carece de videollamadas integradas para consultas.</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">Pocas apps consideran la salud física y mental al mismo nivel.</td>
    <td valign="top">Respaldo de inversionistas en oncología.</td>
    <td valign="top">Posible adopción en hospitales como complemento.</td>
    <td valign="top">Escasa competencia en plataformas médico-paciente integradas.</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">Aparición de apps multiplataforma.</td>
    <td valign="top">Usuarios con tipos de cáncer no cubiertos.</td>
    <td valign="top">Nuevas apps con funcionalidades similares.</td>
    <td valign="top">Competencia indirecta de apps generales como WhatsApp, Telegram o Google Calendar.</td>
  </tr>
</table>


<div id='2.1.2.'><h4>2.1.2. Estrategias y tácticas frente a competidores</h4></div>

**1. Experiencia diferenciada por perfil**

* **Estrategia:** Diseñar una experiencia optimizada para cada segmento: médicos (plataforma web) y pacientes (aplicación móvil).
* **Táctica:** Implementar dashboards clínicos para médicos y una app ligera para pacientes con funciones de accesibilidad, recordatorios y registro de signos vitales.

**2. Modelo de negocio sostenible y escalable**

* **Estrategia:** Garantizar la sostenibilidad financiera mediante un esquema freemium y servicios premium.
* **Táctica:** Ofrecer suscripciones para médicos que incluyan reportes avanzados, integración con historias clínicas y soporte técnico; mantener funciones básicas gratuitas para pacientes.

**3. Posicionamiento especializado en oncología**

* **Estrategia:** Diferenciarse como la primera plataforma digital enfocada en oncología en el Perú.
* **Táctica:** Generar alianzas con instituciones médicas y campañas dirigidas a especialistas para impulsar confianza y adopción.

**4. Seguridad y cumplimiento normativo**

* **Estrategia:** Cumplir con regulaciones de protección de datos médicos y asegurar la confidencialidad.
* **Táctica:** Implementar cifrado de extremo a extremo, políticas estrictas de manejo de datos y auditorías periódicas.

**5. Innovación continua con retroalimentación**

* **Estrategia:** Evolucionar constantemente el producto en base a las necesidades reales de médicos y pacientes.
* **Táctica:** Aplicar metodologías ágiles y recoger feedback continuo para mejorar usabilidad, escalabilidad y relevancia de la solución.

<div id='2.2.'><h3>2.2. Entrevistas</h3></div>
En esta sección se presentan las entrevistas diseñadas para médicos oncólogos, con el objetivo de comprender en profundidad sus necesidades, frustraciones y expectativas en relación con la gestión de pacientes oncológicos. Estas entrevistas permitirán identificar los principales desafíos en su práctica diaria y explorar cómo una solución digital podría optimizar la organización de citas, tratamientos y seguimientos, contribuyendo a reducir la sobrecarga laboral y mejorar la calidad del servicio.
<div id='2.2.1.'><h4>2.2.1. Diseño de entrevistas</h4></div>

### PREGUNTAS GENERALES

#### Información Demográfica
<ul>
<li>¿Podría decirme su edad y distrito de residencia?</li>
<li>¿Cuál es su estado civil y composición familiar (número de hijos, personas a cargo, etc.)?</li>
<li>¿A qué se dedica actualmente? (Estudiante, profesión, jubilado, etc.)</li>
</ul>

#### Hábitos y Preferencias Digitales
<ul>
<li>¿Qué dispositivos digitales utiliza con más frecuencia (smartphone, tablet, computadora, etc.)?</li>
<li>¿Cuáles son sus aplicaciones o servicios en línea favoritos y por qué?</li>
<li>¿Cómo prefiere comunicarse digitalmente con profesionales de la salud o servicios médicos (correo electrónico, mensajes de texto, llamadas, videoconferencias)?</li>
</ul>

#### Objetivos y Frustraciones
<ul>
<li>¿Cuáles son sus principales objetivos al buscar una aplicación relacionada con la salud o el cuidado oncológico?</li>
<li>¿Ha experimentado frustraciones o dificultades al usar aplicaciones o servicios en línea de salud? Por favor, descríbalas.</li>
</ul>

#### Experiencia Personal
<ul>
<li>Relacionado con su salud o la gestión del cuidado oncológico, ¿podría compartir alguna experiencia positiva o negativa que haya tenido?</li>
<li>¿Qué características considera indispensables en una aplicación de salud?</li>
</ul>

#### Expectativas y Necesidades Específicas
<ul>
<li>En términos de ayuda y organización para el cuidado oncológico, ¿qué es lo que más valora o necesitaría?</li>
<li>¿Cómo cree que una aplicación podría mejorar su experiencia o la gestión del cuidado oncológico?</li>
</ul>

### PREGUNTAS ESPECÍFICAS PARA MÉDICOS ONCÓLOGOS

#### Gestión de Pacientes
<ul>
<li>¿Cuál es su método actual para organizar la información y los horarios de sus pacientes?</li>
<li>¿Qué desafíos enfrenta al asignar y hacer seguimiento de los medicamentos y procedimientos para sus pacientes?</li>
</ul>

#### Comunicación y Recordatorios
<ul>
<li>¿Cómo se comunica actualmente con sus pacientes para recordatorios o información importante?</li>
<li>¿Qué funcionalidades considera clave en una aplicación para mejorar la comunicación con sus pacientes?</li>
</ul>

#### Herramientas Digitales
<ul>
<li>¿Utiliza actualmente alguna herramienta o software de gestión de pacientes? Si es así, ¿qué le gusta y qué le falta a estas herramientas?</li>
</ul>

### PREGUNTAS ESPECÍFICAS PARA PACIENTES ONCOLÓGICOS Y SUS FAMILIARES

#### Gestión de la Información Médica
<ul>
<li>¿Cómo lleva registro de los medicamentos, citas y procedimientos actualmente?</li>
<li>¿Cuáles son las principales fuentes de información que utiliza para obtener información sobre su cáncer y su tratamiento?</li>
<li>¿Qué recursos y servicios de apoyo le han sido útiles durante el tratamiento y recuperación?</li>
<li>¿Ha tenido dificultades para entender o recordar las indicaciones médicas y los detalles de los medicamentos?</li>
</ul>

#### Comunicación con Profesionales de la Salud
<ul>
<li>¿Qué tan fácil o difícil ha sido para usted comunicarse con su médico oncólogo o encontrar nuevos especialistas cuando lo necesita?</li>
<li>¿Qué características valoraría en una aplicación que le facilite el contacto con profesionales de la salud o servicios de apoyo oncológico?</li>
</ul>

#### Experiencias y Mejoras
<ul>
<li>¿Qué información te hubiera gustado tener cuando usted o su familiar pasó por el proceso de tratamiento oncológico?</li>
<li>¿Qué recomendaciones tiene para mejorar la experiencia de los pacientes con cáncer en el sistema de atención médica?</li>
<li>Basándose en su experiencia, ¿qué aspectos cree que podrían mejorar en la gestión del cuidado oncológico a través de una aplicación?</li>
<li>¿Cómo cree que una aplicación podría ayudarle a sentirse más apoyado y menos abrumado en su proceso de cuidado oncológico?</li>
</ul>

<div id='2.2.2.'><h4>2.2.2. Registro de entrevistas</h4></div>


**Enlace al video: [Registro de entrevistas.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221e734_upc_edu_pe/EaQxW83LreNLg6xH_n5nAmEB0Ura-UXBJVreD38ecBwcnw?e=7eddS4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7fX0%3D)** <br>
**Duración total:** 1:11:35

**Entrevistado N°1 :** Ramos Calagua Sebastian Alexander <br>
**Segmento objetivo :** Paciente oncológicos y sus familiares <br>
<img src="https://github.com/user-attachments/assets/af804ed3-098f-4eef-b9c9-cad16fca50e4"/> <br>
**Sexo:** Masculino <br>
**Edad:** 22 años <br>
**Ubicación en la que vive:** Surco <br>
**Acerca de la entrevista:** Estudiante Ing de software de la UPC <br>
**Estado y Composición familiar:** Soltero y actualmente vive con sus padres y hermanos <br>
**Instante en el que inicia:** 0:00 <br>
**Duración:** 10:42 <br>
**Resumen:** <br>
Se destaca la importancia de la certificación y confianza en los profesionales de la salud, así como la necesidad de respuestas rápidas y actualizadas. El impacto emocional del cáncer en el paciente y su familia resalta la necesidad de apoyo psicológico. Además, se demanda una mayor personalización, incluyendo recordatorios específicos y acceso a información confiable sobre restricciones alimentarias. La simplicidad y facilidad de uso son esenciales, junto con una comunicación efectiva y regular entre pacientes y profesionales de la salud, incluido el reporte de estado de paciente. También se resalta la importancia de la seguridad y confidencialidad de la información médica, garantizando que la aplicación y servicio de salud sean seguros y protejan la privacidad de los usuarios. <br> <br>

**Entrevistado N°2 :** Raymundo Sernaque <br>
**Segmento objetivo :** Médico Oncólogo <br>
<img src="https://github.com/user-attachments/assets/1e52a795-e63e-427f-bbe6-e46b46cb9f72"> <br>
**Sexo:** Masculino   
**Edad:** 45 años <br>
**Acerca del entrevistado:** Médico radiólogo, jefe de la división de oncología en Resocentro, jefe de radiología del Hospital Nacional de Neoplásicas <br>
**Instante en el que inicia:** 14:21 <br>
**Duración:** 8:22 <br>
**Resumen:** <br>
El doctor explica un énfasis en una aplicación que sea de fácil uso y con información clara y útil sobre los medicamentos, tratamientos, etc. de los pacientes que presente información bibliográfica para demostrar su validez. Para los pacientes, el doctor explicó que una aplicación sobre los procesos de tratamiento oncológico debe tener a los pacientes como precedencia y mayor enfoque, con la información sobre sus medicamentos y la opción de declarar citas rápidamente siendo de gran importancia. <br>
Con respecto a las herramientas que utiliza actualmente, los programas que brinda Resocentro son de gran ayuda ya que son altamente editables en respecto a la ubicación de la información sobre cada paciente, pero muchas de las ventajas que presenta actualmente solo aparecieron luego de muchas actualizaciones. Además de esto, no presenta formas de comunicarse con los pacientes, los médicos deben buscar el número del paciente en cada informe y luego utilizar herramientas externas para su comunicación, por lo que el doctor muestra interés en que nuestra aplicación permita el contacto directo a los pacientes a través de un solo botón. <br>

**Entrevistado N°3 :** Verónica Mendoza Ibarra <br>
**Segmento objetivo :** Pariente de paciente oncológico <br>
<img src="https://github.com/user-attachments/assets/27689286-450d-4c32-ae64-50b1d9ffd7ae"/> <br>
**Sexo:** Femenino <br>
**Edad:** 51 años <br>
**Acerca de la entrevistada:** Profesora de contabilidad en la UPC  
**Instante en el que inicia:** 22:43 <br>
**Duración:** 10:26 <br>
**Resumen:** <br>
La entrevistada explica que, a pesar de la falta de problemas para comunicarse con los médicos principales, esto se hacía por métodos externos a una aplicación dedicada a la salud. Además, hubo mucho problema para encontrar especialistas a parte de los médicos tratantes principales. La profesora muestra un gran interés en una aplicación que sirva para controlar y organizar la gran cantidad de información presentada por los tratamientos y medicamentos, los cuales causaron mucho estrés y confusión durante el tratamiento del familiar. La información adicional, como de los efectos secundarios de medicamentos, fue obtenida por páginas web, pero tuvo que buscar páginas de calidad ya que herramientas como Google muestran muchas páginas de baja fidelidad. <br>
El aplicativo de la clínica donde el paciente fue internado fue de gran ayuda a la hora de recordatorios, pero este no se encontraba disponible durante la mayor parte del tratamiento y no presentaba más funcionalidades además de esta. <br>
Finalmente, la entrevistada considera que una aplicación que sea rápida y de fácil uso, que permita el contacto directo con médicos y presente información de los tratamientos que el paciente está llevando hubiera sido de gran ayuda y le hubiera permitido evitar grandes momentos de estrés. <br>

**Entrevistado N°4 :** Manuel Luis Ramos Silva <br>
**Segmento objetivo :** Pariente de paciente oncológico <br>
<img src="https://github.com/user-attachments/assets/f9866e97-d5dd-4176-8d27-7e1337773ae7"/> <br>
**Sexo:** Masculino <br>
**Edad:** 52 años <br>
**Acerca de la entrevistada:** Asistente médico en Resocentro  
**Instante en el que inicia:** 33:08 <br>
**Duración:** 17:41 <br>
**Resumen:** El entrevistado menciona un gran interés e importancia sobre la comunicación directa con los médicos, explicando que la falta de esta usualmente se daba por la falta de conocimiento sobre la disponibilidad de los doctores. Además, el entrevistado repitió varias veces lo valioso que es la información durante el tratamiento del paciente, como el estado en el que se encuentra, la información sobre efectos negativos de los medicamentos y cómo impactan al paciente, los estados de disponibilidad de los médicos explicado anteriormente y las fechas aproximadas de duración de las etapas del tratamiento. <br>
El entrevistado menciona la gran falta de aplicaciones centradas en el tratamiento oncológico como uno de los mayores problemas, ya que el aplicativo de la clínica solo tenía funcionalidades básicas y fallaba varias veces al inicio del tratamiento. La aplicación de la clínica tampoco mostraba el estado de los medicamentos presentes dentro de la clínica, por lo que ocurrían mayores problemas al no conocer si es que se debería buscar lugares externos para conseguir los medicamentos requeridos. <br>
El entrevistado explica que el estrés generado por la falta de conocimiento podría haber sido eliminado si es que se tuviera acceso directo a la información real del estado del pariente, ya que él solo podía buscar información por internet que no mostraba el estado real del pariente mientras no podría darle compañía debido a la pandemia. <br>

**Entrevistado N°5 :** Rafael Ramirez <br>
**Segmento objetivo :** Médico Oncólogo <br>
<img src="https://github.com/user-attachments/assets/bd9952e8-3959-4ee7-89d5-a77b308336b8"/> <br>
**Sexo:** Masculino   
**Edad:** 34 años   
**Acerca de la entrevistada:** Médico Radiólogo en Oncosalud <br>
**Instante en el que inicia:** 50:57   
**Duración:** 14:48   
**Resumen:** Una de las funcionalidades principales que el doctor menciona que una aplicación de salud que funcione entre los pacientes y médicos es que debería ser similar a una red social en el sentido que varios médicos puedan comunicarse entre sí sobre la información de un paciente, que los pacientes puedan reservar tiempos específicos para llamadas o videollamadas con los médicos y que puedan revisar los tiempos en los que los médicos estén utilizando el aplicativo. Además, el doctor resalta la importancia de que los pacientes puedan registrar información propia de los medicamentos y tratamientos que han recibido, como reacciones adversas a ciertos medicamentos para mostrarle a los médicos o incluso una línea de tiempo de los tratamientos recibidos por el paciente para que los médicos tratantes se encuentren actualizados. <br>
El doctor menciona que las herramientas actuales que utiliza son de las clínicas en sí, pero toda comunicación con los pacientes es o con herramientas externas como llamadas telefónicas o a través de correos, con los pacientes requiriendo enviar correos a la cuenta de la empresa en sí para que luego sea enviado a los médicos. <br>
Finalmente, el doctor vuelve a resaltar la importancia de que los datos como tratamientos anteriores y futuros que el paciente haya tenido y tendrá debería ser de fácil acceso para los médicos. <br>

**Entrevistado N°6 :** Karina Rojas <br>
**Segmento objetivo :** Médico Oncólogo <br>
<img src="https://github.com/user-attachments/assets/2ed72355-b0a9-4000-a8cd-a79b02b213a6"/> <br>
**Edad:** 52 años   
**Acerca de la entrevistada:** Médica oncóloga especializada en hematología   
**Instante en el que inicia:** 1:05:40 <br>
**Duración:** 9:37 <br>
**Resumen:** La doctora muestra un gran interés en que los pacientes oncológicos obtuvieran alertas y recordatorios de sus tratamientos y citas y en mejorar la facilidad en la que ellos pueden ingresar a dichas citas y tratamientos, usando como ejemplo que un médico simplemente encargue un análisis de sangre al paciente y que dicho paciente pueda obtener el análisis simplemente mostrando la cita del doctor. La doctora menciona que los pacientes oncológicos no presentan mucho apoyo actualmente, con la aplicación que utiliza al momento presentando una falta de opciones especiales en los pagos y citas para pacientes oncológicos. <br>
La doctora también menciona que, actualmente, su única forma de tomar notas para todos los pacientes a quienes trata es con un cuaderno y con su asistente, quien se encarga de realizar llamadas como recordatorios y con quien comparte el cuaderno, causando mucho estrés por su parte al no conocer exactamente si es que los pacientes han recibido sus recordatorios o, incluso, si es que ambas tienen la misma información anotada, por lo que considera que una aplicación enfocada a la organización de los médicos oncólogos con comunicaciones directas a los pacientes ayudaría bastante en su trabajo. <br>
Finalmente, menciona la importancia en que los pacientes puedan ver un cronograma de las fechas mostradas por los médicos, además de permitirle a los doctores un poco de privacidad, al realizar la comunicación entre ellos con los pacientes a través de la aplicación, ya que actualmente, usando los números personales, la comunicación convierte “el teléfono personal a uno no personal” al ser usado para contactar a todos los pacientes. <br>


<div id='2.2.3.'><h4>2.2.3. Análisis de entrevistas</h4></div>

Las entrevistas realizadas revelan que tanto médicos oncólogos como pacientes oncológicos enfrentan limitaciones en la gestión y organización de sus procesos de atención.

Los **médicos oncólogos** destacaron la dificultad de manejar citas y tratamientos de manera eficiente, ya que muchos aún dependen de métodos manuales como agendas físicas o archivos dispersos. Coincidieron en la necesidad de una plataforma que centralice **historias clínicas**, facilite **recordatorios automáticos** y permita un **seguimiento más ordenado del paciente**.

Los **pacientes oncológicos**, por su parte, señalaron que suelen olvidar citas o medicamentos durante su tratamiento y que requieren un espacio confiable para registrar su **información médica**, acceder a **orientación clara** y llevar un **seguimiento de síntomas y progresos**. El uso extendido del smartphone entre ellos confirma la viabilidad de una aplicación móvil.

En conjunto, ambos grupos validan la necesidad de una solución digital con **interfaz diferenciada** (web para médicos y móvil para pacientes), que integre las siguientes funcionalidades:

* Gestión de citas y recordatorios.
* Registro y consulta de información clínica.
* Seguimiento de tratamientos y evolución del paciente.
* Acceso a información confiable y organizada.
* Proyección futura hacia el **monitoreo de signos vitales**.

<div id='2.3.'><h3>2.3. Needfinding</h3></div>
<div id='2.3.1.'><h4>2.3.1. User Personas</h4></div>

La construcción de los User Personas se basa en la información recopilada a partir de entrevistas con médicos oncólogos y pacientes oncológicos, así como en el análisis de soluciones digitales disponibles en el sector salud. Estos arquetipos permiten representar de manera clara las características, motivaciones y necesidades de los principales segmentos objetivos, asegurando que el diseño de la aplicación responda a expectativas reales.

* **Segmento objetivo: Paciente Oncológico**

Link de UXPressia: https://uxpressia.com/w/mDdvz/p/tViVP
![Image](https://github.com/user-attachments/assets/6dbdda41-00e7-451d-89fe-52a59f5610b2)

* **Segmento objetivo: Médico Oncólogo**

Link de UXPressia: https://uxpressia.com/w/mDdvz/p/mxqb4

![Image](https://github.com/user-attachments/assets/30ae05da-dc88-4c75-b28d-14d5e2c33ed6)

<div id='2.3.2.'><h4>2.3.2. User Task Matrix</h4></div>


En esta sección se presenta el **User Task Matrix**, que resume las tareas principales realizadas por los dos segmentos objetivo: **pacientes oncológicos** y **médicos oncólogos**. Estas tareas fueron identificadas a partir del análisis de entrevistas y no dependen de la existencia de la aplicación, sino de las actividades reales que cada segmento debe realizar para alcanzar sus objetivos.

| **Tareas**                              | **Paciente: Frecuencia** | **Paciente: Importancia** | **Médico: Frecuencia** | **Médico: Importancia** |
| --------------------------------------- | ------------------------ | ------------------------- | ---------------------- | ----------------------- |
| Buscar información sobre el cáncer      | Alta                     | Alta                      | Media                  | Alta                    |
| Gestionar citas médicas                 | Alta                     | Alta                      | Alta                   | Alta                    |
| Comunicarse con especialistas           | Alta                     | Alta                      | Alta                   | Alta                    |
| Registrar y monitorear medicamentos     | Alta                     | Alta                      | Alta                   | Alta                    |
| Seguimiento del progreso del paciente   | Media                    | Alta                      | Alta                   | Alta                    |
| Coordinar con otros especialistas       | Baja                     | Media                     | Alta                   | Alta                    |
| Gestionar pagos y citas especiales      | Media                    | Media                     | Media                  | Media                   |
| Buscar apoyo psicológico                | Media                    | Alta                      | Baja                   | Media                   |
| Revisar tratamientos anteriores         | Baja                     | Alta                      | Alta                   | Alta                    |
| Acceder a recordatorios de tratamientos | Alta                     | Alta                      | Alta                   | Alta                    |

#### Análisis

* **Coincidencias:** Tanto pacientes como médicos consideran de **alta frecuencia e importancia** tareas como la **gestión de citas, comunicación con especialistas, registro de medicamentos y recordatorios de tratamientos**, lo que refleja la necesidad de mantener una coordinación constante.
* **Diferencias:**

    * Los **pacientes** otorgan más relevancia a la **búsqueda de información confiable y apoyo psicológico**, mientras que para los **médicos** estas actividades tienen un peso menor.
    * Los **médicos** priorizan más el **seguimiento del progreso del paciente y la coordinación con otros especialistas**, lo que corresponde a su rol clínico.
* **Hallazgos clave:**

    * Las tareas de **alta frecuencia y alta importancia en ambos segmentos** (citas, recordatorios, comunicación, medicamentos) deben ser el **foco central del diseño de la aplicación**.
    * Las tareas diferenciadoras (apoyo psicológico en pacientes, coordinación entre especialistas en médicos) pueden considerarse como **funcionalidades de valor agregado** que aumenten la utilidad de la plataforma.

<div id='2.3.3.'><h4>2.3.3. Empathy Mapping</h4></div>
En esta sección se presentan los Empathy Maps desarrollados para cada User Persona, con el propósito de profundizar en su experiencia, emociones y necesidades. El proceso de elaboración se llevó a cabo en la herramienta indicada, colocando en el centro a cada User Persona previamente definido (médico oncólogo y paciente oncológico).

* **Segmento objetivo: Paciente Oncológico**

![Image](https://github.com/user-attachments/assets/ff466ca2-f8cf-4104-a34f-ac26e0de71aa)

* **Segmento objetivo: Médico Oncólogo**

![Image](https://github.com/user-attachments/assets/6c72ffd7-e044-41e6-85a4-af57b6bcdab4)

<div id='2.3.4.'><h4>2.3.4. As-Is Scenario Mapping</h4></div>

**Segmento:Pacientes**
<img src="https://github.com/user-attachments/assets/04b2cd9f-230d-4d1b-a708-24eb68268ea0"/>

**Segmento:Doctor Oncólogo**
<img src="https://github.com/user-attachments/assets/9dda18e4-26e8-47da-a80e-d4524f99bb9d"/>

<div id='2.4.'><h3>2.4. Ubiquitous Language</h3></div>

En esta sección se presenta un glosario de términos que forman parte del dominio de la aplicación. El objetivo es asegurar que tanto el equipo como los stakeholders tengan un entendimiento común y sin ambigüedades de los conceptos principales.

#### Glosario de términos

* **Oncologist (Oncólogo)**
  Médico especialista en la prevención, diagnóstico y tratamiento del cáncer.

* **Oncological Patient (Paciente oncológico)**
  Persona que ha sido diagnosticada con cáncer y se encuentra en tratamiento o en seguimiento médico.

* **Medical Appointment (Cita médica)**
  Encuentro programado entre un paciente y un oncólogo con el fin de diagnóstico, tratamiento o seguimiento.

* **Treatment Plan (Plan de tratamiento)**
  Conjunto de procedimientos, medicamentos y cuidados definidos por el oncólogo para atender la condición del paciente.

* **Medication Reminder (Recordatorio de medicación)**
  Notificación que ayuda al paciente a cumplir con la toma puntual de sus medicamentos.

* **Clinical History (Historia clínica)**
  Registro estructurado de los antecedentes, diagnósticos, tratamientos y evolución de un paciente.

* **Treatment Adherence (Adherencia al tratamiento)**
  Grado en que el paciente sigue las recomendaciones y el plan terapéutico indicado por el oncólogo.

* **Emotional Support (Apoyo emocional)**
  Acompañamiento que recibe el paciente en su proceso, destinado a reducir ansiedad, miedo y estrés relacionados al tratamiento.

* **Follow-up Consultation (Consulta de seguimiento)**
  Evaluación periódica realizada por el oncólogo para medir la efectividad del tratamiento y ajustar el plan si es necesario.

* **Early Detection (Detección temprana)**
  Identificación oportuna de signos y síntomas de cáncer para mejorar la eficacia del tratamiento.

<div id='3.'><h2>3. Capítulo III: Requirements Specification</h2></div>
En esta sección se presentan los requisitos del producto digital a partir del análisis de la información recopilada en las investigaciones previas. El objetivo es transformar las necesidades de los usuarios y de los stakeholders en requisitos claros y estructurados que guíen el diseño y desarrollo de la solución. Para ello, se incluyen artefactos que permiten comprender la situación futura deseada, las tareas clave de los usuarios y la priorización del trabajo.

<div id='3.1.'><h3>3.1. To-Be Scenario Mapping</h3></div>

**Segmento:Paciente**

<img src="https://github.com/user-attachments/assets/722f6143-5adc-4082-9710-0d25b0de0ee0"/>

**Segmento:Doctor Oncólogo**

<img src="https://github.com/user-attachments/assets/80fc1295-1436-41cd-ad5f-8fed75e4695e"/>

<div id='3.2.'><h3>3.2. User Stories</h3></div>

| Epic ID | Título | Descripción |
|---------|--------|-------------|
| **EP01** | **Gestión de Cuenta y Autenticación** | Como usuario general<br>Quiero gestionar mi cuenta y credenciales<br>Para acceder y mantener segura mi información |
| **EP02** | **Gestión de Perfil** | Como usuario general<br>Quiero gestionar mi información personal<br>Para mantener mi perfil actualizado y seguro |
| **EP03** | **Gestión de Tratamientos y Citas** | Como paciente y médico<br>Quiero gestionar tratamientos, citas y procedimientos<br>Para coordinar la atención médica efectivamente |
| **EP04** | **Monitoreo de Salud en Tiempo Real (IoT)** | Como paciente y sistema<br>Quiero monitorear signos vitales mediante sensores<br>Para detectar y alertar sobre condiciones críticas |
| **EP05** | **Comunicación y Soporte** | Como usuario general<br>Quiero comunicarme con médicos y soporte<br>Para resolver dudas y recibir atención |
| **EP06** | **Seguimiento de Síntomas y Medicamentos** | Como paciente y médico<br>Quiero gestionar síntomas y medicamentos<br>Para realizar seguimiento clínico adecuado |
| **EP07** | **Información y Marketing** | Como usuario general<br>Quiero acceder a información de la aplicación<br>Para conocer sus beneficios y funcionalidades |


<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>StoryID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Epic ID</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Registrar cuenta</td>
      <td>Como usuario general<br>Quiero registrarme<br>Para acceder a la aplicación OnControl</td>
      <td><strong>E01 – Registro exitoso:</strong> Dado que el usuario está en el formulario de registro Cuando completa todos los campos obligatorios con datos válidos Entonces el sistema crea su cuenta y lo redirige al dashboard.<br><br><strong>E02 – Datos inválidos:</strong> Dado que el usuario está en el formulario de registro Cuando falta algún campo obligatorio o el formato es incorrecto Entonces el sistema muestra un mensaje de validación y no crea la cuenta.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Configurar pagos</td>
      <td>Como usuario general<br>Quiero añadir métodos de pago<br>Para acceder a servicios adicionales</td>
      <td><strong>E01 – Añadir método válido:</strong> Dado que el usuario está en la sección de pagos Cuando ingresa los datos de tarjeta válidos Entonces el sistema registra el método y lo muestra en la lista.<br><br><strong>E02 – Método inválido:</strong> Dado que el usuario intenta añadir un método Cuando los datos son incorrectos o caducados Entonces el sistema muestra un error y no guarda el método.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Iniciar sesión</td>
      <td>Como usuario general<br>Quiero iniciar sesión<br>Para acceder a las funciones de la app</td>
      <td><strong>E01 – Autenticación exitosa:</strong> Dado que el usuario está en la pantalla de login Cuando ingresa credenciales válidas Entonces el sistema lo autentica y muestra el dashboard.<br><br><strong>E02 – Credenciales inválidas:</strong> Dado que el usuario está en la pantalla de login Cuando ingresa credenciales incorrectas Entonces el sistema muestra un mensaje de error.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Cerrar sesión</td>
      <td>Como usuario general<br>Quiero cerrar mi sesión<br>Para proteger mi cuenta tras usar la app</td>
      <td><strong>E01 – Cierre exitoso:</strong> Dado que el usuario está autenticado Cuando selecciona "Cerrar sesión" Entonces el sistema lo redirige a la landing page.<br><br><strong>E02 – Prevención de acceso:</strong> Dado que el usuario cierra sesión Cuando intenta navegar con la sesión cerrada Entonces el sistema lo obliga a loguearse de nuevo.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Recuperación de cuenta</td>
      <td>Como usuario general<br>Quiero recuperar mi cuenta<br>Para no perder mis datos registrados</td>
      <td><strong>E01 – Recuperación por email:</strong> Dado que el usuario no recuerda su contraseña Cuando elige "Recuperar por email" Entonces el sistema envía un enlace de restablecimiento.<br><br><strong>E02 – Recuperación por SMS:</strong> Dado que el usuario no recuerda su contraseña Cuando elige "Recuperar por SMS" Entonces el sistema envía un código de verificación al móvil.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Cambio de número telefónico</td>
      <td>Como usuario general<br>Quiero actualizar mi número de teléfono<br>Para recibir notificaciones correctamente</td>
      <td><strong>E01 – Cambio exitoso:</strong> Dado que el usuario está en su perfil Cuando ingresa un número válido Entonces el sistema actualiza el teléfono.<br><br><strong>E02 – Número inválido:</strong> Dado que el usuario ingresa un formato incorrecto Cuando guarda cambios Entonces el sistema muestra un error y no lo actualiza.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Cambio de contraseña</td>
      <td>Como usuario general<br>Quiero cambiar mi contraseña<br>Para mantener segura mi cuenta</td>
      <td><strong>E01 – Contraseña actualizada:</strong> Dado que el usuario está en su perfil Cuando ingresa la contraseña actual y una nueva válida Entonces el sistema la actualiza y confirma el cambio.<br><br><strong>E02 – Parámetros no cumplidos:</strong> Dado que la nueva contraseña no cumple requisitos Cuando intenta guardarla Entonces el sistema muestra un mensaje de error.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Actualizar foto de perfil</td>
      <td>Como usuario general<br>Quiero cambiar mi foto de perfil<br>Para mantener mi información al día</td>
      <td><strong>E01 – Subida exitosa:</strong> Dado que el usuario selecciona una imagen válida Cuando la sube Entonces el sistema la guarda como avatar.<br><br><strong>E02 – Formato no permitido:</strong> Dado que el archivo no cumple el formato Cuando intenta subirlo Entonces el sistema muestra un error.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Mandar solicitud de cita</td>
      <td>Como médico<br>Quiero registrar fecha y hora de cita<br>Para coordinar atención con mis pacientes</td>
      <td><strong>E01 – Solicitud registrada:</strong> Dado que el médico elige fecha y hora válidas Cuando envía la petición Entonces la cita queda en el calendario y el paciente recibe notificación.<br><br><strong>E02 – Datos incompletos:</strong> Dado que falta fecha u hora Cuando intenta enviar Entonces el sistema muestra un error.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Aceptar cita</td>
      <td>Como paciente<br>Quiero aceptar una cita<br>Para confirmar mi disponibilidad</td>
      <td><strong>E01 – Cita confirmada:</strong> Dado que el paciente recibe la solicitud Cuando pulsa "Aceptar" Entonces la cita se añade a su calendario.<br><br><strong>E02 – Cita expirada:</strong> Dado que la fecha ya pasó Cuando intenta aceptar Entonces el sistema informa que no es posible.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Cancelar cita</td>
      <td>Como paciente<br>Quiero cancelar una cita confirmada<br>Para reorganizar mi agenda</td>
      <td><strong>E01 – Cancelación exitosa:</strong> Dado que la cita está activa Cuando pulsa "Cancelar" Entonces se elimina y el médico recibe notificación.<br><br><strong>E02 – Cita no cancelable:</strong> Dado que la cita ya fue atendida o cancelada Cuando intenta cancelarla de nuevo Entonces el sistema muestra un mensaje de error.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Reprogramar cita</td>
      <td>Como paciente<br>Quiero reprogramar una cita<br>Para ajustarla a mi disponibilidad</td>
      <td><strong>E01 – Nueva fecha válida:</strong> Dado que hay disponibilidad en la fecha elegida Cuando selecciona y guarda Entonces se actualiza la cita y notifica al médico.<br><br><strong>E02 – Sin disponibilidad:</strong> Dado que no hay huecos en esa fecha Cuando intenta reprogramar Entonces el sistema sugiere otras fechas.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Mandar solicitud de tratamiento</td>
      <td>Como médico<br>Quiero enviar una solicitud de tratamiento<br>Para iniciar o modificar el plan del paciente</td>
      <td><strong>E01 – Solicitud enviada:</strong> Dado que el médico completa el formulario Cuando pulsa "Enviar" Entonces el paciente recibe notificación con detalles.<br><br><strong>E02 – Campos vacíos:</strong> Dado que faltan datos obligatorios Cuando intenta enviar Entonces el sistema bloquea la acción y muestra error.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Aceptar/Rechazar cambios en tratamiento</td>
      <td>Como paciente<br>Quiero decidir sobre cambios en mi tratamiento<br>Para mantener control de mi plan</td>
      <td><strong>E01 – Aceptar cambio:</strong> Dado que recibe la solicitud Cuando pulsa "Aceptar" Entonces el cambio se aplica y notifica al médico.<br><br><strong>E02 – Rechazar cambio:</strong> Dado que revisa la solicitud Cuando pulsa "Rechazar" Entonces el cambio no se aplica y el médico recibe notificación.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Personalizar fecha de inicio</td>
      <td>Como paciente<br>Quiero definir la fecha de inicio de mi tratamiento<br>Para adaptarlo a mi rutina</td>
      <td><strong>E01 – Fecha válida:</strong> Dado que el paciente elige una fecha futura Cuando guarda Entonces el sistema actualiza el inicio y genera recordatorios.<br><br><strong>E02 – Fecha inválida:</strong> Dado que elige una fecha pasada Cuando intenta guardar Entonces muestra un mensaje de error.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Marcar cumplimiento de tratamiento</td>
      <td>Como paciente<br>Quiero marcar mi cumplimiento diario<br>Para llevar seguimiento de mi progreso</td>
      <td><strong>E01 – Registro diario:</strong> Dado que sigue su tratamiento Cuando marca el día Entonces el sistema guarda el progreso.<br><br><strong>E02 – Registro retroactivo:</strong> Dado que olvida marcar un día Cuando lo hace después Entonces el sistema permite la fecha pasada y actualiza su historial.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Asignar especialista</td>
      <td>Como médico<br>Quiero derivar a un paciente a un especialista<br>Para asegurar la mejor atención</td>
      <td><strong>E01 – Especialista existente:</strong> Dado que el médico elige un especialista del listado Cuando asigna Entonces el paciente recibe notificación para agendar cita.<br><br><strong>E02 – Especialista no listado:</strong> Dado que no encuentra al especialista Cuando ingresa nombre y contacto Entonces el sistema guarda la referencia y notifica al paciente.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Enviar síntomas</td>
      <td>Como paciente<br>Quiero reportar mis síntomas<br>Para que el doctor haga seguimiento clínico</td>
      <td><strong>E01 – Reporte exitoso:</strong> Dado que el paciente completa el formulario Cuando envía Entonces el síntoma queda registrado en el panel del médico.<br><br><strong>E02 – Sin tratamiento activo:</strong> Dado que no hay tratamiento asociado Cuando intenta reportar Entonces el sistema muestra un mensaje para seleccionar uno.<br><br><strong>E03 – Síntomas con datos IoT:</strong> Dado que el paciente reporta síntomas Cuando envía el reporte Entonces el sistema incluye automáticamente los datos de los sensores del momento.</td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Revisar síntomas</td>
      <td>Como doctor<br>Quiero ver los síntomas reportados<br>Para evaluar la evolución del tratamiento</td>
      <td><strong>E01 – Síntomas disponibles:</strong> Dado que el paciente ha reportado síntomas Cuando el doctor accede al historial Entonces ve la lista ordenada por fecha.<br><br><strong>E02 – Sin reportes:</strong> Dado que no hay registros Cuando el doctor accede Entonces el sistema muestra un mensaje indicándolo.<br><br><strong>E03 – Correlación con sensores:</strong> Dado que hay síntomas reportados Cuando el doctor los revisa Entonces puede ver los valores de los sensores en el momento del reporte.</td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Consultar medicamento</td>
      <td>Como paciente<br>Quiero consultar composición y reacciones<br>Para identificar efectos adversos</td>
      <td><strong>E01 – Detalles mostrados:</strong> Dado que el paciente selecciona un medicamento asignado Cuando abre su ficha Entonces ve ingredientes, dosis y advertencias.<br><br><strong>E02 – Reportar reacción:</strong> Dado que detecta un efecto adverso Cuando pulsa "Reportar" Entonces el sistema notifica al médico con detalles.</td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Notificaciones de cambios en tratamiento</td>
      <td>Como paciente<br>Quiero recibir avisos de cambios<br>Para estar siempre informado</td>
      <td><strong>E01 – Cambio propuesto:</strong> Dado que el médico envía una modificación Cuando el paciente abre la app Entonces recibe notificación con los detalles.<br><br><strong>E02 – Historial de cambios:</strong> Dado que hay notificaciones previas Cuando accede a notificaciones Entonces puede revisar todas las propuestas anteriores.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Notificación de fin de tratamiento</td>
      <td>Como doctor<br>Quiero recibir aviso de finalización<br>Para agendar cita de cierre</td>
      <td><strong>E01 – Marcado completado:</strong> Dado que el paciente marca el fin de tratamiento Cuando eso ocurre Entonces el sistema notifica al doctor.<br><br><strong>E02 – Agendar post-tratamiento:</strong> Dado que el doctor recibe la notificación Cuando accede al perfil del paciente Entonces puede programar la cita de evaluación.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Consulta a doctor</td>
      <td>Como paciente<br>Quiero hacer consultas via chat<br>Para resolver dudas sobre mi tratamiento</td>
      <td><strong>E01 – Envío de mensaje:</strong> Dado que el paciente redacta un mensaje Cuando pulsa "Enviar" Entonces el doctor recibe la consulta y queda registrada.<br><br><strong>E02 – Respuesta en tiempo real:</strong> Dado que el doctor responde Cuando publica la respuesta Entonces el paciente la ve inmediatamente.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US24</td>
      <td>Agregar paciente</td>
      <td>Como doctor<br>Quiero invitar a un paciente por usuario<br>Para añadirlo a mi lista y asignarle tratamiento</td>
      <td><strong>E01 – Usuario válido:</strong> Dado que el doctor introduce un username existente Cuando envía la invitación Entonces el paciente recibe notificación y puede aceptar.<br><br><strong>E02 – Usuario inexistente:</strong> Dado que el username no está registrado Cuando intenta enviar Entonces el sistema muestra un mensaje de error.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Crear procedimiento</td>
      <td>Como doctor<br>Quiero definir procedimientos médicos<br>Para estructurar el plan de tratamiento</td>
      <td><strong>E01 – Procedimiento guardado:</strong> Dado que el doctor completa todos los datos Cuando guarda Entonces el procedimiento queda asociado al tratamiento.<br><br><strong>E02 – Campos obligatorios vacíos:</strong> Dado que falta información Cuando intenta guardar Entonces el sistema advierte y no registra.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Resumen de tratamiento</td>
      <td>Como paciente<br>Quiero ver un resumen de mi tratamiento<br>Para conocer fechas, medicación y procedimientos</td>
      <td><strong>E01 – Vista previa completa:</strong> Dado que el paciente accede antes de aceptar Cuando abre el resumen Entonces ve todos los detalles del plan.<br><br><strong>E02 – Aceptar desde resumen:</strong> Dado que revisa el contenido Cuando pulsa "Aceptar" Entonces el tratamiento se activa en su cuenta.</td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US27</td>
      <td>Configurar procedimiento</td>
      <td>Como doctor<br>Quiero ajustar duración y frecuencia<br>Para adaptar cada procedimiento al caso</td>
      <td><strong>E01 – Parámetros válidos:</strong> Dado que define duración y repeticiones dentro de rango Cuando guarda Entonces el sistema los registra correctamente.<br><br><strong>E02 – Valores fuera de rango:</strong> Dado que ingresa datos inválidos Cuando intenta guardar Entonces se bloquea la operación y muestra error.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Modificar fecha de inicio</td>
      <td>Como paciente<br>Quiero cambiar la fecha de inicio<br>Para disponer de tiempo para prepararme</td>
      <td><strong>E01 – Cambio válido:</strong> Dado que selecciona una fecha futura Cuando guarda Entonces la fecha se actualiza y notifica al doctor.<br><br><strong>E02 – Fecha pasada:</strong> Dado que elige un día anterior Cuando intenta guardar Entonces el sistema muestra un error.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US29</td>
      <td>Configurar recordatorios</td>
      <td>Como usuario general<br>Quiero personalizar mis notificaciones<br>Para adaptarlas a mi rutina diaria</td>
      <td><strong>E01 – Ajuste exitoso:</strong> Dado que modifica tono y frecuencia Cuando guarda Entonces los recordatorios se actualizan.<br><br><strong>E02 – Horario no seleccionado:</strong> Dado que no define hora alguna Cuando intenta guardar Entonces el sistema indica que debe elegir al menos un horario.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US30</td>
      <td>Aviso de cambios en el sistema</td>
      <td>Como usuario general<br>Quiero recibir notificaciones de cambios<br>Para estar al tanto de reprogramaciones y ajustes</td>
      <td><strong>E01 – Notificación inmediata:</strong> Dado que se reprograma o cancela una cita Cuando ocurre el cambio Entonces el usuario recibe alerta en la app.<br><br><strong>E02 – Historial de avisos:</strong> Dado que hay varios cambios Cuando consulta el buzón de notificaciones Entonces ve el listado cronológico.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US31</td>
      <td>Eliminar paciente</td>
      <td>Como médico<br>Quiero eliminar pacientes finalizados<br>Para mantener organizada mi lista</td>
      <td><strong>E01 – Eliminación exitosa:</strong> Dado que el paciente marcó tratamiento como completo Cuando el doctor pulsa "Eliminar" Entonces se remueve de su lista.<br><br><strong>E02 – Paciente activo:</strong> Dado que aún hay un tratamiento en curso Cuando intenta eliminar Entonces el sistema deniega la acción.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US32</td>
      <td>Contactar con soporte</td>
      <td>Como usuario general<br>Quiero contactar con el equipo de soporte<br>Para resolver dudas o reportar errores</td>
      <td><strong>E01 – Mensaje enviado:</strong> Dado que completa el formulario de contacto Cuando pulsa "Enviar" Entonces llega al equipo y el usuario recibe confirmación.<br><br><strong>E02 – Campos vacíos:</strong> Dado que faltan datos obligatorios Cuando intenta enviar Entonces el sistema muestra error y bloquea envío.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US33</td>
      <td>Lista de pacientes</td>
      <td>Como médico<br>Quiero ver mi lista de pacientes<br>Para acceder a sus tratamientos y progreso</td>
      <td><strong>E01 – Lista poblada:</strong> Dado que hay pacientes asignados Cuando el doctor accede Entonces ve la lista con nombres y estado de tratamiento.<br><br><strong>E02 – Lista vacía:</strong> Dado que no tiene pacientes aún Cuando accede Entonces se muestra un mensaje indicándolo.<br><br><strong>E03 – Estado de monitoreo:</strong> Dado que el paciente tiene sensores conectados Cuando el doctor ve la lista Entonces puede identificar qué pacientes tienen alertas activas.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US34</td>
      <td>Revisar historial de tratamientos</td>
      <td>Como médico<br>Quiero ver el historial de tratamientos<br>Para tener visión cronológica de la evolución</td>
      <td><strong>E01 – Historial disponible:</strong> Dado que el paciente tiene registros anteriores Cuando el doctor abre su perfil Entonces ve la lista ordenada cronológicamente.<br><br><strong>E02 – Sin historial:</strong> Dado que no hay registros Cuando intenta ver el historial Entonces el sistema muestra un mensaje de ausencia de datos.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US35</td>
      <td>Lista de procedimientos</td>
      <td>Como paciente<br>Quiero ver los procedimientos del día<br>Para cumplir correctamente mi tratamiento</td>
      <td><strong>E01 – Procedimientos mostrados:</strong> Dado que hay procedimientos asignados hoy Cuando el paciente accede Entonces ve la lista detallada.<br><br><strong>E02 – Ninguno asignado:</strong> Dado que no hay procedimientos para la fecha Cuando consulta Entonces el sistema informa que no hay tareas.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US36</td>
      <td>Visualizar landing page</td>
      <td>Como usuario general<br>Quiero ver la landing page<br>Para entender la propuesta de valor</td>
      <td><strong>E01 – Contenido cargado:</strong> Dado que accede al sitio Cuando entra en la landing Entonces ve descripción clara y beneficios.<br><br><strong>E02 – Error de carga:</strong> Dado que falla el servidor Cuando entra Entonces el sistema muestra mensaje de indisponibilidad.</td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US37</td>
      <td>Acceso a la app</td>
      <td>Como usuario<br>Quiero ser redirigido a la tienda de apps<br>Para descargar fácilmente OnControl</td>
      <td><strong>E01 – Redirección válida:</strong> Dado que pulsa el botón de descarga Cuando está en la landing Entonces va a App Store o Play Store según dispositivo.<br><br><strong>E02 – Enlace roto:</strong> Dado que el enlace falla Cuando pulsa el botón Entonces el sistema muestra un error y ofrece contacto con soporte.</td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US38</td>
      <td>Recibir información por correo</td>
      <td>Como usuario general<br>Quiero recibir mis registros por email<br>Para conservar un respaldo de mis actividades</td>
      <td><strong>E01 – Envío exitoso:</strong> Dado que introduce un correo válido Cuando solicita el envío Entonces el sistema envía el resumen de actividad.<br><br><strong>E02 – Correo inválido:</strong> Dado que el formato no es correcto Cuando confirma Entonces el sistema muestra un error y no envía el email.</td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US39</td>
      <td>Medir parámetros vitales (IoT)</td>
      <td>Como paciente<br>Quiero que el sistema tome mis parámetros vitales mediante sensores<br>Para monitorear mi temperatura, oxígeno en sangre y ritmo cardíaco en tiempo real</td>
      <td><strong>E01 – Lectura exitosa:</strong> Dado que los sensores están conectados al dispositivo Cuando se inicia la medición Entonces el sistema registra los valores actuales de temperatura, oxígeno y ritmo cardíaco.<br><br><strong>E02 – Error de sensor:</strong> Dado que un sensor no responde Cuando se intenta leer datos Entonces el sistema muestra un mensaje de error indicando el dispositivo afectado.<br><br><strong>E03 – Calibración de sensores:</strong> Dado que los sensores requieren calibración Cuando se inicia el sistema Entonces el dispositivo ejecuta una secuencia de autocomprobación antes de medir.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US40</td>
      <td>Enviar datos de sensores al sistema</td>
      <td>Como sistema IoT<br>Quiero enviar los datos de los sensores al servidor<br>Para que los médicos y pacientes puedan ver los resultados en la app</td>
      <td><strong>E01 – Envío exitoso:</strong> Dado que se capturan los parámetros Cuando el módulo IoT los transmite Entonces el servidor los recibe y los almacena correctamente.<br><br><strong>E02 – Fallo de comunicación:</strong> Dado que hay pérdida de conexión Cuando el módulo intenta enviar datos Entonces el sistema reintenta o muestra una advertencia.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US41</td>
      <td>Detectar umbrales anormales</td>
      <td>Como sistema IoT<br>Quiero comparar los valores obtenidos con los umbrales normales<br>Para detectar condiciones críticas de salud</td>
      <td><strong>E01 – Valor fuera de rango:</strong> Dado que un valor excede el umbral superior o inferior Cuando se realiza la medición Entonces el sistema genera una alerta interna.<br><br><strong>E02 – Valor normal:</strong> Dado que los parámetros están dentro del rango Cuando se registra la medición Entonces no se genera ninguna alerta.<br><br><strong>E03 – Umbrales personalizados por paciente:</strong> Dado que el médico configuró umbrales específicos Cuando se evalúan los parámetros Entonces el sistema usa los valores personalizados en lugar de los generales.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US42</td>
      <td>Activar LED indicador</td>
      <td>Como sistema IoT<br>Quiero encender un LED de advertencia<br>Para alertar visualmente cuando un parámetro vital sale del rango normal</td>
      <td><strong>E01 – Umbral superado:</strong> Dado que se detecta un valor anormal Cuando el sistema lo confirma Entonces el LED se enciende (rojo si es alto, azul si es bajo).<br><br><strong>E02 – Valor estabilizado:</strong> Dado que el parámetro vuelve al rango normal Cuando se actualiza la lectura Entonces el LED se apaga.<br><br><strong>E03 – Patrón de parpadeo por gravedad:</strong> Dado que múltiples parámetros están fuera de rango Cuando se activa la alerta Entonces el LED parpadea más rápido indicando mayor urgencia.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US43</td>
      <td>Visualizar lecturas en la app</td>
      <td>Como paciente<br>Quiero ver mis parámetros vitales en tiempo real<br>Para conocer mi estado de salud desde el panel de control</td>
      <td><strong>E01 – Visualización en tiempo real:</strong> Dado que los sensores están transmitiendo Cuando el usuario accede al dashboard Entonces los valores se actualizan en pantalla cada pocos segundos.<br><br><strong>E02 – Historial de datos:</strong> Dado que se realizan mediciones continuas Cuando el usuario abre su historial Entonces puede ver los registros de temperatura, oxígeno y ritmo cardíaco.<br><br><strong>E03 – Tendencias y análisis:</strong> Dado que hay datos históricos suficientes Cuando el usuario visualiza las métricas Entonces el sistema muestra tendencias y cambios significativos.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US44</td>
      <td>Notificación de emergencias a médicos</td>
      <td>Como sistema<br>Quiero notificar automáticamente al médico cuando un paciente tiene valores críticos<br>Para permitir una intervención rápida</td>
      <td><strong>E01 – Notificación push inmediata:</strong> Dado que se detecta un parámetro crítico Cuando se confirma la alerta Entonces el médico recibe una notificación push con los detalles del paciente.<br><br><strong>E02 – Escalación de alertas:</strong> Dado que la alerta no es atendida en 5 minutos Cuando pasa el tiempo límite Entonces el sistema notifica a un segundo médico o contacto de emergencia.</td>
      <td>EP04</td>
    </tr>
  </tbody>
</table>


<div id='3.3.'><h3>3.3. Impact Mapping</h3></div>

En esta sección se elaboró el impact mapping, tomando como punto de partida las metas comerciales definidas para cada user persona. A partir de ello, se identificaron los impactos esperados, los entregables requeridos y se estableció la relación con las historias de usuario correspondientes.

Segmento objetivo: Pacientes y familiares

<img src="https://github.com/user-attachments/assets/3aa5f839-07f7-4c58-80f3-f4f6b9d007b7" >


Segmento objetivo: Oncólogos


<img src="https://github.com/user-attachments/assets/59b450d1-59c0-4f12-9870-d5696374a1b0">

<div id='3.4.'><h3>3.4. Product Backlog</h3></div>

| Orden | User Story ID | Título | Descripción | Story Points | Epic |
|-------|---------------|--------|-------------|--------------|------|
| 1 | US01 | Registrar cuenta | Como usuario general quiero registrarme para acceder a la aplicación OnControl | 5 | EP01 |
| 2 | US03 | Iniciar sesión | Como usuario general quiero iniciar sesión para acceder a las funciones de la app | 3 | EP01 |
| 3 | US04 | Cerrar sesión | Como usuario general quiero cerrar mi sesión para proteger mi cuenta tras usar la app | 2 | EP01 |
| 4 | US05 | Recuperación de cuenta | Como usuario general quiero recuperar mi cuenta para no perder mis datos registrados | 5 | EP01 |
| 5 | US02 | Configurar pagos | Como usuario general quiero añadir métodos de pago para acceder a servicios adicionales | 8 | EP01 |
| 6 | US06 | Cambio de número telefónico | Como usuario general quiero actualizar mi número de teléfono para recibir notificaciones | 3 | EP02 |
| 7 | US07 | Cambio de contraseña | Como usuario general quiero cambiar mi contraseña para mantener segura mi cuenta | 3 | EP02 |
| 8 | US08 | Actualizar foto de perfil | Como usuario general quiero cambiar mi foto de perfil para mantener mi información al día | 2 | EP02 |
| 9 | US39 | Medir parámetros vitales (IoT) | Como paciente quiero que el sistema tome mis parámetros vitales mediante sensores para monitorear mi salud en tiempo real | 13 | EP04 |
| 10 | US40 | Enviar datos de sensores | Como sistema IoT quiero enviar los datos de los sensores al servidor para que los médicos y pacientes puedan ver los resultados | 8 | EP04 |
| 11 | US41 | Detectar umbrales anormales | Como sistema IoT quiero comparar los valores obtenidos con los umbrales normales para detectar condiciones críticas de salud | 8 | EP04 |
| 12 | US42 | Activar LED indicador | Como sistema IoT quiero encender un LED de advertencia para alertar visualmente cuando un parámetro vital sale del rango normal | 5 | EP04 |
| 13 | US43 | Visualizar lecturas en la app | Como paciente quiero ver mis parámetros vitales en tiempo real para conocer mi estado de salud desde el panel de control | 8 | EP04 |
| 14 | US44 | Notificación de emergencias | Como sistema quiero notificar automáticamente al médico cuando un paciente tiene valores críticos para permitir una intervención rápida | 5 | EP04 |
| 15 | US09 | Mandar solicitud de cita | Como médico quiero registrar fecha y hora de cita para coordinar atención con mis pacientes | 5 | EP03 |
| 16 | US10 | Aceptar cita | Como paciente quiero aceptar una cita para confirmar mi disponibilidad | 3 | EP03 |
| 17 | US11 | Cancelar cita | Como paciente quiero cancelar una cita confirmada para reorganizar mi agenda | 3 | EP03 |
| 18 | US12 | Reprogramar cita | Como paciente quiero reprogramar una cita para ajustarla a mi disponibilidad | 5 | EP03 |
| 19 | US13 | Mandar solicitud de tratamiento | Como médico quiero enviar una solicitud de tratamiento para iniciar o modificar el plan | 5 | EP03 |
| 20 | US14 | Aceptar/Rechazar tratamiento | Como paciente quiero decidir sobre cambios en mi tratamiento para mantener control de mi plan | 5 | EP03 |
| 21 | US15 | Personalizar fecha de inicio | Como paciente quiero definir la fecha de inicio de mi tratamiento para adaptarlo a mi rutina | 3 | EP03 |
| 22 | US16 | Marcar cumplimiento | Como paciente quiero marcar mi cumplimiento diario para llevar seguimiento de mi progreso | 5 | EP03 |
| 23 | US17 | Asignar especialista | Como médico quiero derivar a un paciente a un especialista para asegurar la mejor atención | 8 | EP03 |
| 24 | US21 | Notificaciones de cambios | Como paciente quiero recibir avisos de cambios para estar siempre informado | 5 | EP03 |
| 25 | US22 | Notificación de fin | Como doctor quiero recibir aviso de finalización para agendar cita de cierre | 3 | EP03 |
| 26 | US25 | Crear procedimiento | Como doctor quiero definir procedimientos médicos para estructurar el plan de tratamiento | 5 | EP03 |
| 27 | US27 | Configurar procedimiento | Como doctor quiero ajustar duración y frecuencia para adaptar cada procedimiento al caso | 5 | EP03 |
| 28 | US28 | Modificar fecha de inicio | Como paciente quiero cambiar la fecha de inicio para prepararme | 3 | EP03 |
| 29 | US29 | Configurar recordatorios | Como usuario general quiero personalizar mis notificaciones para adaptarlas a mi rutina | 5 | EP03 |
| 30 | US30 | Aviso de cambios en sistema | Como usuario general quiero recibir notificaciones de cambios en citas y ajustes | 5 | EP03 |
| 31 | US31 | Eliminar paciente | Como médico quiero eliminar pacientes finalizados para mantener organizada mi lista | 3 | EP03 |
| 32 | US33 | Lista de pacientes | Como médico quiero ver mi lista de pacientes para acceder a sus tratamientos y progreso | 3 | EP03 |
| 33 | US34 | Revisar historial de tratamientos | Como médico quiero ver el historial de tratamientos para tener visión cronológica | 5 | EP03 |
| 34 | US35 | Lista de procedimientos | Como paciente quiero ver los procedimientos del día para cumplir mi tratamiento | 3 | EP03 |
| 35 | US18 | Enviar síntomas | Como paciente quiero reportar mis síntomas para que el doctor haga seguimiento clínico | 5 | EP06 |
| 36 | US19 | Revisar síntomas | Como doctor quiero ver los síntomas reportados para evaluar la evolución del tratamiento | 3 | EP06 |
| 37 | US20 | Consultar medicamento | Como paciente quiero consultar composición y reacciones para identificar efectos adversos | 5 | EP06 |
| 38 | US26 | Resumen de tratamiento | Como paciente quiero ver un resumen de mi tratamiento para conocer fechas y medicación | 5 | EP06 |
| 39 | US23 | Consulta a doctor | Como paciente quiero hacer consultas via chat para resolver dudas sobre mi tratamiento | 8 | EP05 |
| 40 | US24 | Agregar paciente | Como doctor quiero invitar a un paciente por usuario para añadirlo a mi lista | 5 | EP05 |
| 41 | US32 | Contactar con soporte | Como usuario general quiero contactar con el equipo de soporte para resolver dudas o errores | 3 | EP05 |
| 42 | US36 | Visualizar landing page | Como usuario general quiero ver la landing page para entender la propuesta de valor | 2 | EP07 |
| 43 | US37 | Acceso a la app | Como usuario quiero ser redirigido a la tienda de apps para descargar OnControl | 2 | EP07 |
| 44 | US38 | Recibir info por correo | Como usuario general quiero recibir mis registros por email para tener respaldo | 3 | EP07 |

<div id='4.'><h2>4. Capítulo IV: Solution Software Design</h2></div>

<div id='4.1.'><h3>4.1. Strategic-Level Domain-Driven Design</h3></div>


<div id='4.1.1.'><h4>4.1.1. Design Purpose.</h4></div>

El propósito del proceso de diseño de OnControl es desarrollar una plataforma integral que mejore la calidad de vida de los pacientes oncológicos y optimice el seguimiento médico a través de herramientas tecnológicas innovadoras. El diseño no solo busca la digitalización de procesos, sino crear un ecosistema interconectado que facilite la comunicación y la gestión clínica en el sector de la salud peruano.

#### Relación con la problemática identificada:
El diseño responde directamente a las deficiencias actuales en el cuidado oncológico, caracterizadas por métodos manuales y fragmentados que generan ineficiencia, retrasos y errores en la gestión de información. Al proveer una solución tecnológica que centraliza los datos médicos, el diseño busca mitigar el alto nivel de estrés de los pacientes, considerando que más del 60 % de los casos en Perú se diagnostican en etapas avanzadas, y aliviar la sobrecarga laboral que causa síntomas de agotamiento en más del 45 % de los oncólogos.

#### Orientación a las necesidades de los segmentos objetivo:

* **Pacientes oncológicos**: El diseño se centra en ofrecer una aplicación móvil gratuita y de fácil acceso que incluye un calendario digital para la visualización de citas y tratamientos. Además, la arquitectura de la solución integra sensores IoT para monitorear constantemente signos vitales clave (ritmo cardíaco, temperatura y oxigenación), lo cual atiende su necesidad de sentirse más seguros, protegidos y con un mayor control sobre su estado de salud.

* **Médicos oncólogos**: La plataforma ha sido diseñada con un dashboard web especializado que permite a los profesionales administrar de forma eficiente los datos, historias clínicas y horarios de sus pacientes. El diseño cubre la necesidad de reacción rápida al incorporar alertas automáticas que notifican al médico cuando los parámetros vitales del paciente sobrepasan los rangos saludables, optimizando así su tiempo y reduciendo errores organizativos.

#### Orientación a los resultados de negocio:
Desde una perspectiva estratégica, el propósito del diseño es posicionar a OnControl como la plataforma líder en salud oncológica digital en el país. Al diseñar una experiencia que reduce la ansiedad de las familias e incrementa la sensación de seguridad en el cuidado, el modelo de negocio asegura una alta adopción y retención por parte de los usuarios. Simultáneamente, esto fomenta una mayor adherencia a los tratamientos oncológicos, garantizando una atención médica integral y sostenible a largo plazo.


<div id='4.1.2.'><h4>4.1.2. Attribute-Driven Design Inputs.</h4></div>


<div id='4.1.2.1.'><h5>4.1.2.1. Primary Functionality (Primary User Stories).</h5></div>

En esta sección se especifican los Epics y User Stories que tienen mayor relevancia en términos de requisitos funcionales y que generan un impacto significativo sobre la arquitectura de la solución OnControl. 

Los requisitos seleccionados para este detalle representan el "core" (núcleo) operativo del sistema. Se ha priorizado la **Gestión de Cuenta y Autenticación (EP01)** y la **Gestión de Perfil (EP02)** debido a sus implicancias en la seguridad y privacidad de los datos médicos. Asimismo, la **Gestión de Tratamientos y Citas (EP03)** junto con el **Seguimiento de Síntomas (EP06)** y la **Comunicación (EP05)**, dictan la arquitectura transaccional y de bases de datos relacionales. Finalmente, el **Monitoreo de Salud en Tiempo Real mediante IoT (EP04)** representa el mayor desafío arquitectónico, requiriendo un diseño que soporte alta disponibilidad, procesamiento de flujo de datos en tiempo real (streaming), baja latencia y comunicación bidireccional (hardware-software) para la gestión de alertas críticas.

A continuación, se detallan estas historias de usuario agrupadas por su respectivo Epic utilizando el siguiente cuadro:

| StoryID | Título | Descripción | Criterios de aceptación | Epic ID |
| :--- | :--- | :--- | :--- | :--- |
| **US01** | Registrar cuenta | Como usuario general<br>Quiero registrarme<br>Para acceder a la aplicación OnControl | **E01 – Registro exitoso:** Dado que el usuario está en el formulario de registro Cuando completa todos los campos obligatorios con datos válidos Entonces el sistema crea su cuenta y lo redirige al dashboard.<br><br>**E02 – Datos inválidos:** Dado que el usuario está en el formulario de registro Cuando falta algún campo obligatorio o el formato es incorrecto Entonces el sistema muestra un mensaje de validación y no crea la cuenta. | EP01 |
| **US02** | Configurar pagos | Como usuario general<br>Quiero añadir métodos de pago<br>Para acceder a servicios adicionales | **E01 – Añadir método válido:** Dado que el usuario está en la sección de pagos Cuando ingresa los datos de tarjeta válidos Entonces el sistema registra el método y lo muestra en la lista.<br><br>**E02 – Método inválido:** Dado que el usuario intenta añadir un método Cuando los datos son incorrectos o caducados Entonces el sistema muestra un error y no guarda el método. | EP01 |
| **US03** | Iniciar sesión | Como usuario general<br>Quiero iniciar sesión<br>Para acceder a las funciones de la app | **E01 – Autenticación exitosa:** Dado que el usuario está en la pantalla de login Cuando ingresa credenciales válidas Entonces el sistema lo autentica y muestra el dashboard.<br><br>**E02 – Credenciales inválidas:** Dado que el usuario está en la pantalla de login Cuando ingresa credenciales incorrectas Entonces el sistema muestra un mensaje de error. | EP01 |
| **US04** | Cerrar sesión | Como usuario general<br>Quiero cerrar mi sesión<br>Para proteger mi cuenta tras usar la app | **E01 – Cierre exitoso:** Dado que el usuario está autenticado Cuando selecciona "Cerrar sesión" Entonces el sistema lo redirige a la landing page.<br><br>**E02 – Prevención de acceso:** Dado que el usuario cierra sesión Cuando intenta navegar con la sesión cerrada Entonces el sistema lo obliga a loguearse de nuevo. | EP01 |
| **US05** | Recuperación de cuenta | Como usuario general<br>Quiero recuperar mi cuenta<br>Para no perder mis datos registrados | **E01 – Recuperación por email:** Dado que el usuario no recuerda su contraseña Cuando elige "Recuperar por email" Entonces el sistema envía un enlace de restablecimiento.<br><br>**E02 – Recuperación por SMS:** Dado que el usuario no recuerda su contraseña Cuando elige "Recuperar por SMS" Entonces el sistema envía un código de verificación al móvil. | EP01 |
| **US06** | Cambio de número telefónico | Como usuario general<br>Quiero actualizar mi número de teléfono<br>Para recibir notificaciones correctamente | **E01 – Cambio exitoso:** Dado que el usuario está en su perfil Cuando ingresa un número válido Entonces el sistema actualiza el teléfono.<br><br>**E02 – Número inválido:** Dado que el usuario ingresa un formato incorrecto Cuando guarda cambios Entonces el sistema muestra un error y no lo actualiza. | EP02 |
| **US07** | Cambio de contraseña | Como usuario general<br>Quiero cambiar mi contraseña<br>Para mantener segura mi cuenta | **E01 – Contraseña actualizada:** Dado que el usuario está en su perfil Cuando ingresa la contraseña actual y una nueva válida Entonces el sistema la actualiza y confirma el cambio.<br><br>**E02 – Parámetros no cumplidos:** Dado que la nueva contraseña no cumple requisitos Cuando intenta guardarla Entonces el sistema muestra un mensaje de error. | EP02 |
| **US08** | Actualizar foto de perfil | Como usuario general<br>Quiero cambiar mi foto de perfil<br>Para mantener mi información al día | **E01 – Subida exitosa:** Dado que el usuario selecciona una imagen válida Cuando la sube Entonces el sistema la guarda como avatar.<br><br>**E02 – Formato no permitido:** Dado que el archivo no cumple el formato Cuando intenta subirlo Entonces el sistema muestra un error. | EP02 |
| **US09** | Mandar solicitud de cita | Como médico<br>Quiero registrar fecha y hora de cita<br>Para coordinar atención con mis pacientes | **E01 – Solicitud registrada:** Dado que el médico elige fecha y hora válidas Cuando envía la petición Entonces la cita queda en el calendario y el paciente recibe notificación.<br><br>**E02 – Datos incompletos:** Dado que falta fecha u hora Cuando intenta enviar Entonces el sistema muestra un error. | EP03 |
| **US10** | Aceptar cita | Como paciente<br>Quiero aceptar una cita<br>Para confirmar mi disponibilidad | **E01 – Cita confirmada:** Dado que el paciente recibe la solicitud Cuando pulsa "Aceptar" Entonces la cita se añade a su calendario.<br><br>**E02 – Cita expirada:** Dado que la fecha ya pasó Cuando intenta aceptar Entonces el sistema informa que no es posible. | EP03 |
| **US11** | Cancelar cita | Como paciente<br>Quiero cancelar una cita confirmada<br>Para reorganizar mi agenda | **E01 – Cancelación exitosa:** Dado que la cita está activa Cuando pulsa "Cancelar" Entonces se elimina y el médico recibe notificación.<br><br>**E02 – Cita no cancelable:** Dado que la cita ya fue atendida o cancelada Cuando intenta cancelarla de nuevo Entonces el sistema muestra un mensaje de error. | EP03 |
| **US12** | Reprogramar cita | Como paciente<br>Quiero reprogramar una cita<br>Para ajustarla a mi disponibilidad | **E01 – Nueva fecha válida:** Dado que hay disponibilidad en la fecha elegida Cuando selecciona y guarda Entonces se actualiza la cita y notifica al médico.<br><br>**E02 – Sin disponibilidad:** Dado que no hay huecos en esa fecha Cuando intenta reprogramar Entonces el sistema sugiere otras fechas. | EP03 |
| **US13** | Mandar solicitud de tratamiento | Como médico<br>Quiero enviar una solicitud de tratamiento<br>Para iniciar o modificar el plan del paciente | **E01 – Solicitud enviada:** Dado que el médico completa el formulario Cuando pulsa "Enviar" Entonces el paciente recibe notificación con detalles.<br><br>**E02 – Campos vacíos:** Dado que faltan datos obligatorios Cuando intenta enviar Entonces el sistema bloquea la acción y muestra error. | EP03 |
| **US14** | Aceptar/Rechazar cambios en tratamiento | Como paciente<br>Quiero decidir sobre cambios en mi tratamiento<br>Para mantener control de mi plan | **E01 – Aceptar cambio:** Dado que recibe la solicitud Cuando pulsa "Aceptar" Entonces el cambio se aplica y notifica al médico.<br><br>**E02 – Rechazar cambio:** Dado que revisa la solicitud Cuando pulsa "Rechazar" Entonces el cambio no se aplica y el médico recibe notificación. | EP03 |
| **US15** | Personalizar fecha de inicio | Como paciente<br>Quiero definir la fecha de inicio de mi tratamiento<br>Para adaptarlo a mi rutina | **E01 – Fecha válida:** Dado que el paciente elige una fecha futura Cuando guarda Entonces el sistema actualiza el inicio y genera recordatorios.<br><br>**E02 – Fecha inválida:** Dado que elige una fecha pasada Cuando intenta guardar Entonces muestra un mensaje de error. | EP03 |
| **US16** | Marcar cumplimiento de tratamiento | Como paciente<br>Quiero marcar mi cumplimiento diario<br>Para llevar seguimiento de mi progreso | **E01 – Registro diario:** Dado que sigue su tratamiento Cuando marca el día Entonces el sistema guarda el progreso.<br><br>**E02 – Registro retroactivo:** Dado que olvida marcar un día Cuando lo hace después Entonces el sistema permite la fecha pasada y actualiza su historial. | EP03 |
| **US17** | Asignar especialista | Como médico<br>Quiero derivar a un paciente a un especialista<br>Para asegurar la mejor atención | **E01 – Especialista existente:** Dado que el médico elige un especialista del listado Cuando asigna Entonces el paciente recibe notificación para agendar cita.<br><br>**E02 – Especialista no listado:** Dado que no encuentra al especialista Cuando ingresa nombre y contacto Entonces el sistema guarda la referencia y notifica al paciente. | EP03 |
| **US18** | Enviar síntomas | Como paciente<br>Quiero reportar mis síntomas<br>Para que el doctor haga seguimiento clínico | **E01 – Reporte exitoso:** Dado que el paciente completa el formulario Cuando envía Entonces el síntoma queda registrado en el panel del médico.<br><br>**E02 – Sin tratamiento activo:** Dado que no hay tratamiento asociado Cuando intenta reportar Entonces el sistema muestra un mensaje para seleccionar uno.<br><br>**E03 – Síntomas con datos IoT:** Dado que el paciente reporta síntomas Cuando envía el reporte Entonces el sistema incluye automáticamente los datos de los sensores del momento. | EP06 |
| **US19** | Revisar síntomas | Como doctor<br>Quiero ver los síntomas reportados<br>Para evaluar la evolución del tratamiento | **E01 – Síntomas disponibles:** Dado que el paciente ha reportado síntomas Cuando el doctor accede al historial Entonces ve la lista ordenada por fecha.<br><br>**E02 – Sin reportes:** Dado que no hay registros Cuando el doctor accede Entonces el sistema muestra un mensaje indicándolo.<br><br>**E03 – Correlación con sensores:** Dado que hay síntomas reportados Cuando el doctor los revisa Entonces puede ver los valores de los sensores en el momento del reporte. | EP06 |
| **US20** | Consultar medicamento | Como paciente<br>Quiero consultar composición y reacciones<br>Para identificar efectos adversos | **E01 – Detalles mostrados:** Dado que el paciente selecciona un medicamento asignado Cuando abre su ficha Entonces ve ingredientes, dosis y advertencias.<br><br>**E02 – Reportar reacción:** Dado que detecta un efecto adverso Cuando pulsa "Reportar" Entonces el sistema notifica al médico con detalles. | EP06 |
| **US21** | Notificaciones de cambios en tratamiento | Como paciente<br>Quiero recibir avisos de cambios<br>Para estar siempre informado | **E01 – Cambio propuesto:** Dado que el médico envía una modificación Cuando el paciente abre la app Entonces recibe notificación con los detalles.<br><br>**E02 – Historial de cambios:** Dado que hay notificaciones previas Cuando accede a notificaciones Entonces puede revisar todas las propuestas anteriores. | EP03 |
| **US22** | Notificación de fin de tratamiento | Como doctor<br>Quiero recibir aviso de finalización<br>Para agendar cita de cierre | **E01 – Marcado completado:** Dado que el paciente marca el fin de tratamiento Cuando eso ocurre Entonces el sistema notifica al doctor.<br><br>**E02 – Agendar post-tratamiento:** Dado que el doctor recibe la notificación Cuando accede al perfil del paciente Entonces puede programar la cita de evaluación. | EP03 |
| **US23** | Consulta a doctor | Como paciente<br>Quiero hacer consultas via chat<br>Para resolver dudas sobre mi tratamiento | **E01 – Envío de mensaje:** Dado que el paciente redacta un mensaje Cuando pulsa "Enviar" Entonces el doctor recibe la consulta y queda registrada.<br><br>**E02 – Respuesta en tiempo real:** Dado que el doctor responde Cuando publica la respuesta Entonces el paciente la ve inmediatamente. | EP05 |
| **US24** | Agregar paciente | Como doctor<br>Quiero invitar a un paciente por usuario<br>Para añadirlo a mi lista y asignarle tratamiento | **E01 – Usuario válido:** Dado que el doctor introduce un username existente Cuando envía la invitación Entonces el paciente recibe notificación y puede aceptar.<br><br>**E02 – Usuario inexistente:** Dado que el username no está registrado Cuando intenta enviar Entonces el sistema muestra un mensaje de error. | EP05 |
| **US25** | Crear procedimiento | Como doctor<br>Quiero definir procedimientos médicos<br>Para estructurar el plan de tratamiento | **E01 – Procedimiento guardado:** Dado que el doctor completa todos los datos Cuando guarda Entonces el procedimiento queda asociado al tratamiento.<br><br>**E02 – Campos obligatorios vacíos:** Dado que falta información Cuando intenta guardar Entonces el sistema advierte y no registra. | EP03 |
| **US26** | Resumen de tratamiento | Como paciente<br>Quiero ver un resumen de mi tratamiento<br>Para conocer fechas, medicación y procedimientos | **E01 – Vista previa completa:** Dado que el paciente accede antes de aceptar Cuando abre el resumen Entonces ve todos los detalles del plan.<br><br>**E02 – Aceptar desde resumen:** Dado que revisa el contenido Cuando pulsa "Aceptar" Entonces el tratamiento se activa en su cuenta. | EP06 |
| **US27** | Configurar procedimiento | Como doctor<br>Quiero ajustar duración y frecuencia<br>Para adaptar cada procedimiento al caso | **E01 – Parámetros válidos:** Dado que define duración y repeticiones dentro de rango Cuando guarda Entonces el sistema los registra correctamente.<br><br>**E02 – Valores fuera de rango:** Dado que ingresa datos inválidos Cuando intenta guardar Entonces se bloquea la operación y muestra error. | EP03 |
| **US28** | Modificar fecha de inicio | Como paciente<br>Quiero cambiar la fecha de inicio<br>Para disponer de tiempo para prepararme | **E01 – Cambio válido:** Dado que selecciona una fecha futura Cuando guarda Entonces la fecha se actualiza y notifica al doctor.<br><br>**E02 – Fecha pasada:** Dado que elige un día anterior Cuando intenta guardar Entonces el sistema muestra un error. | EP03 |
| **US29** | Configurar recordatorios | Como usuario general<br>Quiero personalizar mis notificaciones<br>Para adaptarlas a mi rutina diaria | **E01 – Ajuste exitoso:** Dado que modifica tono y frecuencia Cuando guarda Entonces los recordatorios se actualizan.<br><br>**E02 – Horario no seleccionado:** Dado que no define hora alguna Cuando intenta guardar Entonces el sistema indica que debe elegir al menos un horario. | EP03 |
| **US30** | Aviso de cambios en el sistema | Como usuario general<br>Quiero recibir notificaciones de cambios<br>Para estar al tanto de reprogramaciones y ajustes | **E01 – Notificación inmediata:** Dado que se reprograma o cancela una cita Cuando ocurre el cambio Entonces el usuario recibe alerta en la app.<br><br>**E02 – Historial de avisos:** Dado que hay varios cambios Cuando consulta el buzón de notificaciones Entonces ve el listado cronológico. | EP03 |
| **US31** | Eliminar paciente | Como médico<br>Quiero eliminar pacientes finalizados<br>Para mantener organizada mi lista | **E01 – Eliminación exitosa:** Dado que el paciente marcó tratamiento como completo Cuando el doctor pulsa "Eliminar" Entonces se remueve de su lista.<br><br>**E02 – Paciente activo:** Dado que aún hay un tratamiento en curso Cuando intenta eliminar Entonces el sistema deniega la acción. | EP03 |
| **US32** | Contactar con soporte | Como usuario general<br>Quiero contactar con el equipo de soporte<br>Para resolver dudas o reportar errores | **E01 – Mensaje enviado:** Dado que completa el formulario de contacto Cuando pulsa "Enviar" Entonces llega al equipo y el usuario recibe confirmación.<br><br>**E02 – Campos vacíos:** Dado que faltan datos obligatorios Cuando intenta enviar Entonces el sistema muestra error y bloquea envío. | EP05 |
| **US33** | Lista de pacientes | Como médico<br>Quiero ver mi lista de pacientes<br>Para acceder a sus tratamientos y progreso | **E01 – Lista poblada:** Dado que hay pacientes asignados Cuando el doctor accede Entonces ve la lista con nombres y estado de tratamiento.<br><br>**E02 – Lista vacía:** Dado que no tiene pacientes aún Cuando accede Entonces se muestra un mensaje indicándolo.<br><br>**E03 – Estado de monitoreo:** Dado que el paciente tiene sensores conectados Cuando el doctor ve la lista Entonces puede identificar qué pacientes tienen alertas activas. | EP03 |
| **US34** | Revisar historial de tratamientos | Como médico<br>Quiero ver el historial de tratamientos<br>Para tener visión cronológica de la evolución | **E01 – Historial disponible:** Dado que el paciente tiene registros anteriores Cuando el doctor abre su perfil Entonces ve la lista ordenada cronológicamente.<br><br>**E02 – Sin historial:** Dado que no hay registros Cuando intenta ver el historial Entonces el sistema muestra un mensaje de ausencia de datos. | EP03 |
| **US35** | Lista de procedimientos | Como paciente<br>Quiero ver los procedimientos del día<br>Para cumplir correctamente mi tratamiento | **E01 – Procedimientos mostrados:** Dado que hay procedimientos asignados hoy Cuando el paciente accede Entonces ve la lista detallada.<br><br>**E02 – Ninguno asignado:** Dado que no hay procedimientos para la fecha Cuando consulta Entonces el sistema informa que no hay tareas. | EP03 |
| **US36** | Visualizar landing page | Como usuario general<br>Quiero ver la landing page<br>Para entender la propuesta de valor | **E01 – Contenido cargado:** Dado que accede al sitio Cuando entra en la landing Entonces ve descripción clara y beneficios.<br><br>**E02 – Error de carga:** Dado que falla el servidor Cuando entra Entonces el sistema muestra mensaje de indisponibilidad. | EP07 |
| **US37** | Acceso a la app | Como usuario<br>Quiero ser redirigido a la tienda de apps<br>Para descargar fácilmente OnControl | **E01 – Redirección válida:** Dado que pulsa el botón de descarga Cuando está en la landing Entonces va a App Store o Play Store según dispositivo.<br><br>**E02 – Enlace roto:** Dado que el enlace falla Cuando pulsa el botón Entonces el sistema muestra un error y ofrece contacto con soporte. | EP07 |
| **US38** | Recibir información por correo | Como usuario general<br>Quiero recibir mis registros por email<br>Para conservar un respaldo de mis actividades | **E01 – Envío exitoso:** Dado que introduce un correo válido Cuando solicita el envío Entonces el sistema envía el resumen de actividad.<br><br>**E02 – Correo inválido:** Dado que el formato no es correcto Cuando confirma Entonces el sistema muestra un error y no envía el email. | EP07 |
| **US39** | Medir parámetros vitales (IoT) | Como paciente<br>Quiero que el sistema tome mis parámetros vitales mediante sensores<br>Para monitorear mi temperatura, oxígeno en sangre y ritmo cardíaco en tiempo real | **E01 – Lectura exitosa:** Dado que los sensores están conectados al dispositivo Cuando se inicia la medición Entonces el sistema registra los valores actuales de temperatura, oxígeno y ritmo cardíaco.<br><br>**E02 – Error de sensor:** Dado que un sensor no responde Cuando se intenta leer datos Entonces el sistema muestra un mensaje de error indicando el dispositivo afectado.<br><br>**E03 – Calibración de sensores:** Dado que los sensores requieren calibración Cuando se inicia el sistema Entonces el dispositivo ejecuta una secuencia de autocomprobación antes de medir. | EP04 |
| **US40** | Enviar datos de sensores al sistema | Como sistema IoT<br>Quiero enviar los datos de los sensores al servidor<br>Para que los médicos y pacientes puedan ver los resultados en la app | **E01 – Envío exitoso:** Dado que se capturan los parámetros Cuando el módulo IoT los transmite Entonces el servidor los recibe y los almacena correctamente.<br><br>**E02 – Fallo de comunicación:** Dado que hay pérdida de conexión Cuando el módulo intenta enviar datos Entonces el sistema reintenta o muestra una advertencia. | EP04 |
| **US41** | Detectar umbrales anormales | Como sistema IoT<br>Quiero comparar los valores obtenidos con los umbrales normales<br>Para detectar condiciones críticas de salud | **E01 – Valor fuera de rango:** Dado que un valor excede el umbral superior o inferior Cuando se realiza la medición Entonces el sistema genera una alerta interna.<br><br>**E02 – Valor normal:** Dado que los parámetros están dentro del rango Cuando se registra la medición Entonces no se genera ninguna alerta.<br><br>**E03 – Umbrales personalizados por paciente:** Dado que el médico configuró umbrales específicos Cuando se evalúan los parámetros Entonces el sistema usa los valores personalizados en lugar de los generales. | EP04 |
| **US42** | Activar LED indicador | Como sistema IoT<br>Quiero encender un LED de advertencia<br>Para alertar visualmente cuando un parámetro vital sale del rango normal | **E01 – Umbral superado:** Dado que se detecta un valor anormal Cuando el sistema lo confirma Entonces el LED se enciende (rojo si es alto, azul si es bajo).<br><br>**E02 – Valor estabilizado:** Dado que el parámetro vuelve al rango normal Cuando se actualiza la lectura Entonces el LED se apaga.<br><br>**E03 – Patrón de parpadeo por gravedad:** Dado que múltiples parámetros están fuera de rango Cuando se activa la alerta Entonces el LED parpadea más rápido indicando mayor urgencia. | EP04 |
| **US43** | Visualizar lecturas en la app | Como paciente<br>Quiero ver mis parámetros vitales en tiempo real<br>Para conocer mi estado de salud desde el panel de control | **E01 – Visualización en tiempo real:** Dado que los sensores están transmitiendo Cuando el usuario accede al dashboard Entonces los valores se actualizan en pantalla cada pocos segundos.<br><br>**E02 – Historial de datos:** Dado que se realizan mediciones continuas Cuando el usuario abre su historial Entonces puede ver los registros de temperatura, oxígeno y ritmo cardíaco.<br><br>**E03 – Tendencias y análisis:** Dado que hay datos históricos suficientes Cuando el usuario visualiza las métricas Entonces el sistema muestra tendencias y cambios significativos. | EP04 |
| **US44** | Notificación de emergencias a médicos | Como sistema<br>Quiero notificar automáticamente al médico cuando un paciente tiene valores críticos<br>Para permitir una intervención rápida | **E01 – Notificación push inmediata:** Dado que se detecta un parámetro crítico Cuando se confirma la alerta Entonces el médico recibe una notificación push con los detalles del paciente.<br><br>**E02 – Escalación de alertas:** Dado que la alerta no es atendida en 5 minutos Cuando pasa el tiempo límite Entonces el sistema notifica a un segundo médico o contacto de emergencia. | EP04 |




<div id='4.1.2.2.'><h5>4.1.2.2. Quality attribute Scenarios.</h5></div>


<div id='4.1.2.3.'><h5>4.1.2.3. Constraints.</h5></div>


<div id='4.1.3.'><h4>4.1.3. Architectural Drivers Backlog.</h4></div>


<div id='4.1.4.'><h4>4.1.4. Architectural Design Decisions.</h4></div>


<div id='4.1.5.'><h4>4.1.5. Quality Attribute Scenario Refinements.</h4></div>




<div id='4.2.'><h3>4.2. Strategic-Level Domain-Driven Design</h3></div>
<div id='4.2.1.'><h4>4.2.1. EventStorming</h4></div>

Mediante la tecnica del event storming definimos los siguientes bounded context los cuales son principales dentro del proyecto:

### Account Managed
![Image](https://github.com/user-attachments/assets/e8c31e5f-ddf1-4f51-8720-32d5cc9e9bb4)

### Treatment Managed
![Image](https://github.com/user-attachments/assets/5417e257-4acc-466d-b7d8-509a1f600e26)

### Comunication Managed
![Image](https://github.com/user-attachments/assets/67954401-a663-456e-8722-e1dc9c94fec4)

### Calendar Managed
![Image](https://github.com/user-attachments/assets/44e2a840-14dd-4aeb-8d7d-dda4fc9c9da8)

### Monitoring Managed

![IoT - Frame 1](https://github.com/user-attachments/assets/5dce869e-6253-479c-875c-8b03e3b7d470)


<div id='4.2.2.'><h4>4.2.2. Candidate Context Discovery</a></h4></il>

![Image](https://github.com/user-attachments/assets/da3b2c4d-c1e2-4145-b18d-00eb8eabea3c)
![Image](https://github.com/user-attachments/assets/3b42a571-4390-4384-8248-5f6669ed6baa)
![Image](https://github.com/user-attachments/assets/2345dc02-02de-470a-ac7e-c9bf62284858)
![Image](https://github.com/user-attachments/assets/61c191c6-c639-4453-97fe-4839723c4f1b)
![Image](https://github.com/user-attachments/assets/b5e97564-f933-4e30-8d8d-f5f1601215e9)
![Image](https://github.com/user-attachments/assets/3df6939c-074c-4d7a-a1b3-59d2e10491ca)
![Image](https://github.com/user-attachments/assets/7db7c4c1-3db6-44a2-82c7-7b5431bcc452)
![Image](https://github.com/user-attachments/assets/9d7ffc30-46f7-4b4b-a758-49bd589379dd)
![Image](https://github.com/user-attachments/assets/8728d14a-62d4-41df-b90c-56659314a272)
![Image](https://github.com/user-attachments/assets/9b205f02-f2c5-43eb-a142-6ae2f5966fbb)

<div id='4.2.3.'><h4>4.2.3. Domain Message Flows Modeling</h4></div>

![Image](https://github.com/user-attachments/assets/3378b7b6-3c84-4351-a539-7f44a1fd6a3f)

<div id='4.2.4.'><h4>4.2.4. Bounded Context Canvases</h4></div>

![Image](https://github.com/user-attachments/assets/3c109b5c-a841-4528-9cb5-05c983d72542)
![Image](https://github.com/user-attachments/assets/c0397f26-4ca8-4724-a253-37aff347773a)
![Image](https://github.com/user-attachments/assets/536090e4-3561-47f9-9359-8d07bfc660a5)
![Image](https://github.com/user-attachments/assets/3c727884-49ea-49e4-9771-ad4b2a34e3ca)

<div id='4.2.5.'><h4>4.2.5. Context Mapping</h4></div>

En este diagrama se muestran las relaciones estructurales entre los Bounded Contexts de Tratamiento, User, Calendar y Communicate. Cada contexto se interconecta según las reglas de Domain-Driven Design para garantizar una correcta coordinación y eficiencia en el sistema.

- **Tratamiento y User**: El contexto de User proporciona la información necesaria sobre los pacientes (datos personales, historial médico, etc.), la cual es utilizada por el contexto de Tratamiento para asignar y gestionar los tratamientos adecuados. Esta relación sigue el patrón Customer/Supplier, donde User actúa como un Supplier que provee la información al contexto de Tratamiento.

- **Tratamiento y Calendar**: El contexto de Calendar gestiona los recordatorios y citas relacionadas con los tratamientos. Los recordatorios de citas y procedimientos son generados a partir de los datos de Tratamiento. Aquí, Calendar es un Supplier que recibe la información de Tratamiento para crear y actualizar los recordatorios correspondientes, asegurando que el paciente y el doctor sean notificados a tiempo.

- **Tratamiento y Communicate**: Existe una relación de Shared Kernel (SK) entre Tratamiento y Communicate, ya que ambos contextos comparten la funcionalidad de notificaciones y mensajes. El contexto de Communicate es responsable de gestionar la comunicación entre los pacientes y los doctores, enviando notificaciones sobre el progreso del tratamiento o recordatorios importantes relacionados con el mismo.

- **Calendar y Communicate**: La relación entre Calendar y Communicate es de tipo Customer/Supplier, donde Calendar actúa como un Supplier al proveer a Communicate con los datos necesarios para enviar las notificaciones correspondientes a los pacientes sobre sus citas o procedimientos programados.

![Image](https://github.com/user-attachments/assets/f6a1aeb4-6dbc-433b-886d-2bf967cf2ae8)

<div id='4.3.'><h3>4.3. Software Architecture</h3></div>

Este workspace contiene el modelo completo de arquitectura C4 para el sistema **OnControl Platform**, una plataforma de monitoreo de salud oncológica con IoT.

### Servicios de Negocio
- **Gestión de Pacientes**: Lista y perfil de pacientes para médicos
- **Tratamientos**: Planes de tratamiento y seguimiento
- **Citas**: Agendamiento y gestión de citas médicas
- **Medicamentos**: Prescripciones y recordatorios
- **Síntomas**: Registro y seguimiento de síntomas
- **Monitoreo**: Dashboard de parámetros vitales en tiempo real
- **Alertas**: Generación de alertas médicas basadas en umbrales
- **Notificaciones**: Envío multicanal de notificaciones

### Flujo de Datos IoT
```
Sensores → Dispositivo IoT → Servidor Edge → IoT Gateway → Monitoreo → Alertas → Notificaciones
```

### Parámetros Monitoreados
- Temperatura corporal
- Oxígeno en sangre (SpO2)
- Ritmo cardíaco (BPM)

### Vistas Disponibles

| Vista | ID | Descripción |
|-------|-----|-------------|
| System Landscape | `SystemLandscape` | Vista completa de todos los sistemas |
| System Context | `SystemContext` | Contexto general del sistema |
| Patient Context | `PatientContext` | Vista desde perspectiva del paciente |
| Doctor Context | `DoctorContext` | Vista desde perspectiva del médico |
| Container Diagram | `ContainerDiagram` | Arquitectura interna completa |
| Patient Journey | `PatientJourneyContainer` | Recorrido del paciente |
| Doctor Workflow | `DoctorWorkflowContainer` | Flujo de trabajo del médico |
| IoT Flow | `IoTFlowContainer` | Flujo de datos IoT |
| Notification Flow | `NotificationFlowContainer` | Sistema de notificaciones |
| Deployment | `DeploymentDiagram` | Infraestructura de producción |

<div id='4.3.1.'><h4>4.3.1. Software Architecture System Landscape Diagram</h4></div>

En este diagrama podemos observar el contexto de nuestra aplicación, identificando el sistema y las relaciones con los diferentes tipos de usuarios que este presenta, además de otros sistemas externos y de terceros que son de ayuda para el desarrollo.

Vista de alto nivel que muestra todos los sistemas, usuarios y sus interacciones:
- **Usuarios**: Pacientes, Médicos, Familiares
- **Sistema Principal**: OnControl Health Platform
- **Sistemas Externos**: Dispositivos IoT, Servidor Edge Local

<img width="3050" height="1400" alt="structurizr-106662-SystemLandscape" src="https://github.com/user-attachments/assets/47c4f0fc-f9a6-4ad5-a861-5a00521fa852" />

<div id='4.3.2.'><h4>4.3.2. Software Architecture Context Level Diagrams</h4></div>

En este diagrama podemos observar el contexto de nuestra aplicación, identificando el sistema y las relaciones con los diferentes tipos de usuarios que este presenta, además de otros sistemas externos y de terceros que son de ayuda para el desarrollo.

Diagramas de contexto que muestran cómo el sistema interactúa con usuarios y sistemas externos:
- **SystemContext**: Vista general de todas las interacciones
- **PatientContext**: Perspectiva del paciente (gestión de tratamientos, visualización de datos IoT)
- **DoctorContext**: Perspectiva del médico (gestión de pacientes, monitoreo de alertas)

**SystemContext:**
<img width="1575" height="2100" alt="structurizr-106662-SystemContext" src="https://github.com/user-attachments/assets/e1b1abed-4fb7-48bd-9f26-c11a9f250d8b" />

**PatientContext:**
<img width="1575" height="2000" alt="structurizr-106662-PatientContext" src="https://github.com/user-attachments/assets/616bfd0c-acf2-46c4-9386-1a46dbbb6c86" />

**DoctorContext:**
<img width="907" height="1400" alt="structurizr-106662-DoctorContext" src="https://github.com/user-attachments/assets/d529af9a-24b5-46e2-ad1d-2ea58a243292" />


<div id='4.3.3.'><h4>4.3.3. Software Architecture Container Level Diagrams</h4></div>

Este diagrama muestra los contenedores dentro del sistema de nuestra aplicación, con componentes de alto nivel que centra el enfoque hacia la arquitectura de nuestro software.

Arquitectura interna del sistema OnControl con servicios especializados:
- **ContainerDiagram**: Vista completa de todos los contenedores
    - Aplicación Web
    - Aplicación Móvil
    - API Gateway
    - Servicio de Autenticación
    - Servicio de Gestión de Pacientes
    - Servicio de Tratamientos
    - Servicio de Citas
    - Servicio de Medicamentos
    - Servicio de Síntomas
    - Servicio de Monitoreo
    - Servicio de Alertas
    - Servicio de Notificaciones
    - IoT Gateway
    - Base de Datos

- **PatientJourneyContainer**: Flujo del recorrido del paciente
- **DoctorWorkflowContainer**: Flujo de trabajo del médico
- **IoTFlowContainer**: Flujo de datos IoT desde sensores hasta alertas médicas
- **NotificationFlowContainer**: Sistema de notificaciones y alertas

**ContainerDiagram:**
<img width="8038" height="5215" alt="structurizr-106662-ContainerDiagram" src="https://github.com/user-attachments/assets/431f26c6-805b-4188-9034-01a3ad1b4480" />
**DoctorWorkflowContainer:**
<img width="3205" height="3365" alt="structurizr-106662-DoctorWorkflowContainer" src="https://github.com/user-attachments/assets/8d3ebac1-5b6d-4375-8407-67b27e6cc547" />
**PatientJourneyContainer:**
<img width="3205" height="3365" alt="structurizr-106662-PatientJourneyContainer" src="https://github.com/user-attachments/assets/57cf9ef6-7300-43fd-9138-ba08980ce1b1" />
**IoTFlowContainer:**
<img width="5300" height="1515" alt="structurizr-106662-IoTFlowContainer" src="https://github.com/user-attachments/assets/4d06d4d9-ce3f-443f-a2d8-b1d67bf57eb8" />


<div id='4.3.4.'><h4>4.3.4. Software Architecture Deployment Diagrams</h4></div>

Finalmente, se presenta un diagrama de componentes, en este caso, centrado al componente de Login de nuestro sistema, mostrando las implementaciones de los distintos servicios y responsabilidades de cada uno de ellos.

Infraestructura de despliegue en producción:
- **Dispositivos de Usuario**: Navegadores web y dispositivos móviles
- **Red Local del Paciente**:
    - Servidor Edge (computadora local)
    - Dispositivos IoT con sensores (temperatura, oxígeno, ritmo cardíaco)
    - Indicador visual de alertas
- **Proveedor Cloud**:
    - Red de distribución (CDN) para frontend
    - Cluster de aplicación con orquestador de contenedores
    - Base de datos con réplicas de lectura
    - Servicios de terceros (notificaciones push, email, SMS)

<img width="11497" height="5154" alt="structurizr-106662-DeploymentDiagram" src="https://github.com/user-attachments/assets/5e00acf5-c6f8-40ec-a342-dc7377e94956" />



<div id='7.'><h2>7. Conclusiones</h2></div>


1. **Ecosistema Integral con Modelo Sostenible:** OnControl trasciende una simple aplicación al integrar gestión médica, acompañamiento emocional y herramientas de autocontrol bajo un modelo freemium que balancea accesibilidad para pacientes con valor tangible para profesionales, asegurando viabilidad económica.

2. **Experiencia de Usuario Empática y Técnicamente Sólida:** El diseño prioriza interfaces intuitivas y reducción de carga cognitiva para pacientes oncológicos, respaldado por una arquitectura escalable con Flutter, microservicios en Spring Boot e infraestructura cloud que garantiza seguridad, rendimiento y cumplimiento normativo.

3. **Desarrollo Ágil con Enfoque Estratégico:** La metodología Scrum permite entregas incrementales validadas continuamente, mientras que el backlog priorizado mediante story points asegura que el desarrollo avance sobre funcionalidades críticas primero, manteniendo flexibilidad y enfoque en el valor central.

4. **Seguridad Integrada y Confianza del Usuario:** La protección de datos médicos sensibles se incorpora desde el diseño inicial mediante cifrado y adherencia a estándares HIPAA y GDPR, generando la confianza necesaria para que pacientes y médicos adopten la plataforma.

5. **Impacto Transformador en Telemedicina Oncológica:** La plataforma democratiza el acceso a especialistas y optimiza el manejo de tratamientos mediante tecnología, equilibrando soluciones técnicas avanzadas con sensibilidad humana para mejorar genuinamente la calidad de vida durante el proceso oncológico.

<div id='8.'><h2>8. Bibliografía</h2></div>

- Congreso de la República del Perú. (2011, 3 de julio). Ley N.° 29733, Ley de Protección de Datos Personales. Diario Oficial El Peruano. https://www.gob.pe/institucion/congreso-de-la-republica/normas-legales/243470-29733


- Presidencia de la República del Perú. (2013, 22 de marzo). Decreto Supremo N.° 003-2013-JUS que aprueba el Reglamento de la Ley N.° 29733, Ley de Protección de Datos Personales. Diario Oficial El Peruano. https://www.minjus.gob.pe/wp-content/uploads/2013/04/LEY-29733.pdf


- Congreso de la República del Perú. (1997, 20 de julio). Ley N.° 26842, Ley General de Salud. Diario Oficial El Peruano. https://www.minsa.gob.pe/Recursos/OGTI/SINADEF/Ley-29733.pdf
