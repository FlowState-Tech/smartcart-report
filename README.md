<div style="text-align: center;">
  <img src="./assets/logos/upc-logo.png" alt="UPC Logo" style="width: 250px; height: auto;">
</div>

<h2 style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas </h2>

<h4 style="text-align: center"> Ingeniería de Software </h4>

<h4 style="text-align: center"> Periodo: 202610 </h4>

<h4 style="text-align: center"> 1ACC0238 | Aplicaciones para Dispositivos Móviles </h4>

<h4 style="text-align: center"> NRC: 3646  </h4>

<h4 style="text-align: center"> Docente: Jorge Luis Mayta Guillermo </h4>

<br>

<h3 style="text-align: center;"> Informe del Trabajo Final </h3>

<h4 style="text-align: center"> Startup: FlowState Tech </h4>

<h4 style="text-align: center"> Producto: SmartCart</h4>

<h4 style="text-align: center">Integrantes:</h4>

<div style="text-align:center; margin-top: 10px; font-size: 90%; line-height: 1.6;">
  <p>U20221G044 — Amaro Villar, Anjali</p>
  <p>U202314019 — Chavez Viera, Joseph Manuel</p>
  <p>U20221A118 — Mejia Aliaga, Katherine Maryory</p>
  <p>U20221A525 — Pardo Chumpitazi, Kevin Patrick</p>
  <p>U202311294 — Valdivia Quispe, Stephano Renan</p>
</div>

<br>

<h5 style="text-align: center; font-style: italic;"> Abril 2026 </h5>

<hr class="page-break">

# Registro de Versiones del Informe

| Versión | Fecha    | Autor        | Descripción de modificación      |
| ------- | -------- | ------------ | -------------------------------- |
| 1.0     | 09/04/26 | Anjali Amaro | Organización inicial del informe |


<hr class="page-break">

# Project Report Collaboration Insights

Enlace para acceder al repositorio del reporte del proyecto: [*Ver en GitHub*](https://github.com/FlowState-Tech/smartcart-report)

**GitHub Collaboration Insights**

En GitHub se presenta un timeline de las principales ramas creadas por cada integrante del equipo, así como los procesos de _merge_ realizados.
Todas las ramas fueron gestionadas siguiendo el flujo de trabajo GitFlow, adaptado para una organización que utiliza un sistema de control de versiones.

Los integrantes son: 

| Integrante                      | Usuario GitHub        |
| ------------------------------- | --------------------- |
| Amaro Villar, Anjali            | njlmrvllr             |
| Chavez Viera, Joseph Manuel     | u202314019-MrOsoPanda |
| Mejia Aliaga, Katherine Maryory | KathMJ                |
| Pardo Chumpitazi, Kevin Patrick | Kevinyin11            |
| Valdivia Quispe, Stephano Renan | steph-ano             |

Las principales ramas del repositorio son las siguientes:

* `main`: Rama principal que contiene la versión estable del proyecto.
* `develop`: Rama de desarrollo donde se integran las nuevas características antes de ser fusionadas a `main`.
* `feature/X-anjali`: Rama utilizada por Anjali para el desarrollo de la tareas correspondientes a una determinada entrega. (av1,tb1,av2,tb2)
* `feature/X-(joseph)`: Rama utilizada por Joseph para el desarrollo de la tareas correspondientes a una determinada entrega. (av1,tb1,av2,tb2)
* `feature/X-katherine`: Rama utilizada por Katherine para el desarrollo de la tareas correspondientes a una determinada entrega. (av1,tb1,av2,tb2)
* `feature/X-kevin`: Rama utilizada por Kevin para el desarrollo de la tareas correspondientes a una determinada entrega. (av1,tb1,av2,tb2)
* `feature/X-stephano`: Rama utilizada por Stephano para el desarrollo de la tareas correspondientes a una determinada entrega. (av1,tb1,av2,tb2)
* `realese/vX.X.X`: Rama creada para preparar versiones candidatas al reporte final, siguiendo Semantic Versioning 2.0.0. En esta rama se realizan ajustes finales como correcciones menores y revisiones antes de integrarla a `main`.
* `hotfix/urgent-fix`: Rama utilizada para aplicar correcciones urgentes a la rama `main` en caso de detectar errores críticos.



<hr class="page-break">

# Contenido

- [Capítulo I: Presentación](#capítulo-i-presentación)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis](#1223-lean-ux-hypothesis)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
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
        - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
        - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
    - [2.4. Requirements specification](#24-requirements-specification)
        - [2.4.1. User Stories](#241-user-stories)
        - [2.4.2. Impact Mapping](#242-impact-mapping)
        - [2.4.3. Product Backlog](#243-product-backlog)
    - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
        - [2.5.1. EventStorming](#251-eventstorming)
            - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
            - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
            - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
        - [2.5.2. Context Mapping](#252-context-mapping)
        - [2.5.3. Software Architecture](#253-software-architecture)
            - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
            - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
            - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
    - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
        - [2.6.1. Bounded Context: IAM](#261-bounded-context-iam)
            - [2.6.1.1. Domain Layer](#2611-domain-layer)
            - [2.6.1.2. Interface Layer](#2612-interface-layer)
            - [2.6.1.3. Application Layer](#2613-application-layer)
            - [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
            - [2.6.1.5. Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.1.6. Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.2. Bounded Context: Verification](#262-bounded-context-verification)
            - [2.6.2.1. Domain Layer](#2621-domain-layer-1)
            - [2.6.2.2. Interface Layer](#2622-interface-layer-1)
            - [2.6.2.3. Application Layer](#2623-application-layer-1)
            - [2.6.2.4. Infrastructure Layer](#2624-infrastructure-layer-1)
            - [2.6.2.5. Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.2.6. Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.3. Bounded Context: Store Management](#263-bounded-context-store-management)
            - [2.6.3.1. Domain Layer](#2631-domain-layer)
            - [2.6.3.2. Interface Layer](#2632-interface-layer)
            - [2.6.3.3. Application Layer](#2633-application-layer)
            - [2.6.3.4. Infrastructure Layer](#2634-infrastructure-layer)
            - [2.6.3.5. Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.3.6. Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.4. Bounded Context: Notification](#264-bounded-context-notification)
            - [2.6.4.1. Domain Layer](#2641-domain-layer)
            - [2.6.4.2. Interface Layer](#2642-interface-layer)
            - [2.6.4.3. Application Layer](#2643-application-layer)
            - [2.6.4.4. Infrastructure Layer](#2644-infrastructure-layer)
            - [2.6.4.5. Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.4.6. Code Level Diagrams](#2646-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.5. Bounded Context: Shopping Planning](#265-bounded-context-shopping-planning)
            - [2.6.5.1. Domain Layer](#2651-domain-layer)
            - [2.6.5.2. Interface Layer](#2652-interface-layer)
            - [2.6.5.3. Application Layer](#2653-application-layer)
            - [2.6.5.4. Infrastructure Layer](#2654-infrastructure-layer)
            - [2.6.5.5. Component Level Diagrams](#2655-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.5.6. Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.6. Bounded Context: Shopping Journey](#266-bounded-context-shopping-journey)
            - [2.6.6.1. Domain Layer](#2661-domain-layer)
            - [2.6.6.2. Interface Layer](#2662-interface-layer)
            - [2.6.6.3. Application Layer](#2663-application-layer)
            - [2.6.6.4. Infrastructure Layer](#2664-infrastructure-layer)
            - [2.6.6.5. Component Level Diagrams](#2665-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.6.6. Code Level Diagrams](#2666-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.7. Bounded Context: Experience](#267-bounded-context-experience)
            - [2.6.7.1. Domain Layer](#2671-domain-layer)
            - [2.6.7.2. Interface Layer](#2672-interface-layer)
            - [2.6.7.3. Application Layer](#2673-application-layer)
            - [2.6.7.4. Infrastructure Layer](#2674-infrastructure-layer)
            - [2.6.7.5. Component Level Diagrams](#2675-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.7.6. Code Level Diagrams](#2676-bounded-context-software-architecture-code-level-diagrams)
    - [Conclusiones](#conclusiones)
        - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Bibliografía](#bibliografía)
    - [Anexos](#anexos)

<hr class="page-break">

# Student Outcome

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7

| Criterio específico                                                                                                                                                                 | Acciones realizadas                                                                                                                                                                                                                                                                   | Conclusiones |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| **Actualiza conceptos y**<br> **conocimientos necesarios**<br> **para su desarrollo**<br> **profesional y en especial**<br> **para su proyecto en**<br> **soluciones de software.** | **Amaro Villar, Anjali** <br> *AV1:*:      <br> **Chavez Viera, Joseph Manueli** <br> *AV1:*:      <br>**Mejia Aliaga, Katherine Maryory** <br> *AV1:*:      <br>**Pardo Chumpitazi, Kevin Patrick** <br> *AV1:*:      <br>**Valdivia Quispe, Stephano Renan** <br> *AV1:*:      <br> | *AV1:*       |
| **Reconoce la necesidad del**<br> **aprendizaje permanente**<br> **para el desempeño**<br> **profesional y el desarrollo de**<br> **proyectos en soluciones de**<br> **software.**  | **Amaro Villar, Anjali** <br> *AV1:*:      <br> **Chavez Viera, Joseph Manueli** <br> *AV1:*:      <br>**Mejia Aliaga, Katherine Maryory** <br> *AV1:*:      <br>**Pardo Chumpitazi, Kevin Patrick** <br> *AV1:*:      <br>**Valdivia Quispe, Stephano Renan** <br> *AV1:*:      <br> | *AV1:*       |

<hr class="page-break">

# Objetivos SMART

A continuación, cada miembro del equipo expone sus objetivos SMART, orientados a su desarrollo profesional tras finalizar la carrera universitaria.

**Integrante 1: Anjali Amaro**  
**Objetivo 1:**
**Objetivo 2:**

**Integrante 2: Joseph Manuel Chavez Viera**
* **Objetivo 1:** Obtener una certificación oficial en lenguaje Python o C++ de nivel intermedio-avanzado en un plazo máximo de 6 meses tras el egreso, con el fin de validar técnicamente sus habilidades y aumentar su competitividad laboral.
* **Objetivo 2:** Realizar un curso de especialización o certificación técnica en el extranjero durante el primer año post-graduación para fortalecer su perfil internacional en ingeniería de software.

**Integrante 3: Katherine Mejia**  
**Objetivo 1:**
**Objetivo 2:**

**Integrante 4: Kevin Pardo**  
**Objetivo 1:**
**Objetivo 2:**

**Integrante 5: Stephano Valdivia**  
**Objetivo 1:**
**Objetivo 2:**


<hr class="page-break">

# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup


La startup FlowState Tech es un equipo conformado por estudiantes de la carrera de Ingeniería de Software. Se tiene como objetivo principal desarrollar herramientas tecnológicas prácticas que ayuden a las familias de Lima a gestionar mejor sus gastos diarios frente al alza de precios. Mediante la aplicación **SmartCart** se busca facilitar la comparación de precios en tiempo real y la creación de rutas de compra eficientes, permitiendo que los usuarios ahorren dinero y tiempo en su compras cotidianas.

**Misión:** Ayudar a las familias limeñas a optimizar su presupuesto mensual mediante una aplicación móvil que simplifique la búsqueda de los mejores precios y las rutas de compra más rápidas.

**Visión:** Ser la plataforma de referencia para el ahorro inteligente en el Perú, destacando por nuestra facilidad de uso y por el impacto directo y positivo en la economía de nuestros usuarios.

### 1.1.2. Perfiles de los integrantes del equipo

| Foto | Nombres y Apellidos            | Código de Estudiante |        Carrera         | Resumen de Conocimientos y Habilidades |
| :--: | :----------------------------- | :------------------: | :--------------------: | :------------------------------------- |
|      | Anjali Amaro Villar            |      U20221G044      | Ingeniería de Software |                                        |
|![Joseph Chavez](./assets/perfiles/Joseph.jpg)| Joseph Manuel Chavez Viera     |      U202314019      | Ingeniería de Software | Mi nombre es Joseph Chavez, tengo 19 años y actualmente curso el séptimo ciclo de la carrera de Ingeniería de Software en la UPC. Poseo habilidades en los lenguajes C++, Python y conocimientos básicos de JavaScript. Considero que el desempeño académico se refleja directamente en la vida profesional; por ello, me esfuerzo en obtener todas las experiencias necesarias para mi formación técnica y profesional. |
|      | Katherine Maryory Mejia Aliaga |      U20221A118      | Ingeniería de Software |                                        |
|      | Kevin Patrick Pardo Chumpitazi |      U20221A525      | Ingeniería de Software |                                        |
|      | Stephano Renan Valdivia Quispe |      U202311294      | Ingeniería de Software |                                        |

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

#### What? (¿Qué?)

**¿Cuál es el problema?**

El problema central es la asincronía informativa y la ineficiencia logística en el consumo masivo dentro del canal moderno (supermercados y tiendas de conveniencia) en Lima. A pesar de la digitalización, existe una brecha crítica entre los precios/promociones anunciados en plataformas corporativas y la realidad física en las góndolas, sumada a la incapacidad de los consumidores para comparar canastas completas entre distintos competidores de proximidad.

Esta ineficiencia se ve respaldada por investigaciones que identifican la dispersión de precios como una falla de mercado crítica en el sector minorista peruano, donde productos idénticos presentan variaciones de costo significativas dependiendo del canal de venta y la ubicación geográfica del establecimiento (Banco Central de Reserva del Perú [BCRP], 2025). En el canal moderno, esta problemática se agrava por el "incumplimiento de oferta" en punto de venta, donde la falta de stock o el etiquetado erróneo anula el beneficio del consumidor. A esto se suma la ineficiencia en la movilidad, incurriendo en gastos innecesarios de transporte y una pérdida de tiempo considerable al no contar con una secuencia organizada de visitas (ResearchGate, 2024). Esta falta de transparencia logística impide que las familias logren un beneficio neto real frente a la inflación acumulada en el rubro de alimentos básicos (Instituto Nacional de Estadística e Informática [INEI], 2026).

#### When? (¿Cuándo?)

**¿Cuándo ocurre el problema?**

Se manifiesta recurrentemente durante la planificación de compras semanales o de reposición inmediata (compras de impulso o conveniencia). El problema se intensifica durante los fines de semana o campañas de "ofertas relámpago", donde la alta rotación de productos genera discrepancias rápidas entre el stock real de la tienda y la información disponible para el usuario.

#### Where? (¿Dónde?)
**¿Dónde surge el problema?**

Surge en las zonas de alta densidad comercial de Lima Metropolitana, donde conviven múltiples cadenas de conveniencia (Tambo, Oxxo, Listo) y supermercados (Mass, Plaza Vea, Metro).

**¿A dónde se dirige?**

Esta propuesta se dirige a consumidores jóvenes (estudiantes y profesionales) que buscan eficiencia tecnológica, y a gestores de tiendas del canal moderno que necesitan herramientas de analítica y geofencing para atraer tráfico cualificado a sus sedes y reducir el margen de error en sus precios exhibidos.

#### Who? (¿Quién?)

**¿Quiénes están involucrados?**

* **Consumidores:** Estudiantes universitarios y jóvenes profesionales responsables de su propio abastecimiento que valoran el tiempo tanto como el ahorro.
* **Comerciantes (Retailers):** Administradores y jefes de tienda de cadenas de conveniencia y supermercados que buscan optimizar su alcance local y reducir la pérdida de ventas por precios desactualizados.

**¿Quién lo utilizará?**

El producto será utilizado por compradores con alta adopción tecnológica que planifican sus rutas de compra mediante smartphones. Por otro lado, será utilizado por los gestores de retail como un panel de control para actualizar ofertas locales, gestionar eventos promocionales y recibir métricas sobre el comportamiento y engagement de los consumidores en su zona de influencia.

#### Why? (¿Por qué?)
**¿Cuál es la causa del problema?**

La causa principal es la rigidez de los sistemas corporativos de retail, que no permiten una comunicación fluida entre el precio en estante y el consumidor cercano en tiempo real. Esto genera un alto "costo de búsqueda" y una frustración del usuario al encontrar ofertas inexistentes, mientras que el comerciante sufre de "ceguera de datos" al no saber cuántas ventas pierde frente a competidores directos situados a pocos metros de distancia.

#### How? (¿Cómo?)

**¿En qué condiciones los usuarios usarán nuestro producto?**

Los consumidores lo usarán en una modalidad mixta: desde casa para comparar la canasta total y en exteriores para seguir la ruta optimizada hacia las tiendas seleccionadas. Los comerciantes lo emplearán de manera dinámica en sus estaciones de trabajo para validar alertas de inconsistencias reportadas por usuarios y para activar promociones de proximidad (geofencing) que incentiven la visita inmediata al local cuando detecten baja rotación de stock.

**¿Cómo nos conocieron nuestros compradores?**

A través de estrategias de marketing digital enfocadas en comunidades universitarias, alianzas estratégicas con cadenas de conveniencia interesadas en visibilidad de marca y la integración de códigos QR en los puntos de venta físicos para validar la veracidad de los precios.

**¿Cómo prefieren nuestros consumidores acceder a nuestro producto?**

Mediante una aplicación móvil nativa que permita la integración de mapas en tiempo real, notificaciones push personalizadas según sus hábitos de consumo y acceso rápido al panel de control para el perfil del comerciante.

#### How much? (¿Cuánto?)

**Estadísticas que sustentan la problemática.**

La problemática económica en Lima Metropolitana se ve agravada por una inflación que registró un incremento del 2.38% en marzo de 2026 (INEI, 2026). Esta situación impacta severamente la economía doméstica, considerando que el gasto promedio para cubrir una canasta básica familiar ya supera significativamente los ingresos percibidos por los trabajadores (BCRP, 2025), incluso con la Remuneración Mínima Vital de S/ 1,130 (Infobae, 2025). Ante este panorama, el 41% de los responsables de compra prioriza la búsqueda de ofertas (Kantar Worldpanel, 2025). Finalmente, la falta de planificación logística genera sobrecostos de hasta un 20% en transporte y tiempo de desplazamiento (ResearchGate, 2024), una cifra crítica para el segmento de jóvenes que operan con presupuestos ajustados y tiempos limitados.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

La declaración del problema es un enunciado claro y conciso que describe los síntomas de la problemática a tratar. Siguiendo los lineamientos de la unidad, este punto se compone de tres elementos fundamentales que delimitan el alcance del trabajo:

**1. Los objetivos actuales del sistema/producto:**

El producto **SmartCart** busca facilitar herramientas tecnológicas prácticas que ayuden a los integrantes del hogar a gestionar mejor sus gastos diarios y optimizar sus recorridos de abastecimiento.Simultáneamente, el sistema tiene como objetivo proporcionar a los **establecimientos de consumo masivo** una plataforma ágil para la visibilidad de sus precios, la gestión de ofertas relámpago para reducir mermas y la obtención de métricas de conversión real del entorno digital al piso de venta[cite: 13, 17].

**2. El problema que las partes interesadas quieren abordar:**
* **Perspectiva del usuario (Consumidor):** Los miembros del hogar enfrentan una ineficiencia económica y pérdida de tiempo debido a la asimetría de información de precios y la falta de una logística organizada en sus compras.
* **Perspectiva del negocio (Establecimientos):** Los gerentes de sede carecen de autonomía para actualizar ofertas locales en tiempo real, dependiendo de procesos manuales o de oficinas centrales que no viven el día a día[cite: 5, 24]. Esto genera una falta de sincronización de stock que destruye la confianza del cliente [cite: 7] y una "caja negra" informativa, donde se desconoce si el alcance digital realmente atrae "pies a la tienda"[cite: 9, 15].

**3. Una solicitud explícita de mejora:**
¿Cómo mejorar la eficacia en el acceso a la información de precios para el consumidor y, al mismo tiempo, brindar a los gerentes de establecimientos herramientas de **trazabilidad de conversión** y gestión de stock en tiempo real  para optimizar sus recursos, reducir desperdicios y asegurar la satisfacción de ambos segmentos?

**Oportunidades y restricciones:**
La oportunidad radica en un mercado que carece de herramientas que integren el factor económico del hogar con la inteligencia de mercado para el vendedor[cite: 19]. [Entre las principales restricciones identificadas se encuentran la dependencia de sistemas centrales corporativos (SAP/Marketing Central), la veracidad de los datos actualizados por la comunidad y la necesidad de conectividad constante para reflejar el stock en tiempo real[cite: 7, 16].

#### 1.2.2.2. Lean UX Assumptions

En esta etapa inicial del proceso, se identifican y declaran los supuestos fundamentales que sustentan la propuesta de valor de **SmartCart**. Este ejercicio permite reconocer los riesgos críticos del proyecto para priorizar su validación experimental antes de proceder con el desarrollo. 

**Assumptions Worksheet**

1. **¿Quién es el usuario?**
   * El ecosistema de usuarios está compuesto por dos segmentos clave: por un lado, **jefes de hogar, familias y jóvenes** que buscan optimizar su presupuesto frente a la inflación ; y por otro, **gerentes y administradores de establecimientos masivos** (supermercados y tiendas de conveniencia) que necesitan gestionar su oferta local de forma ágil.

2. **¿Dónde encaja nuestro producto en su trabajo o vida?**
   * Para el consumidor, se integra en su rutina de planificación financiera y ejecución de compras semanales[cite: 1]. Para el gerente de tienda, encaja en su gestión operativa diaria, permitiéndole liquidar sobrestock y atraer clientes digitales al piso de venta físico.

3. **¿Qué problemas resuelve nuestro producto?**
   * Resuelve la ineficiencia logística y el "costo de búsqueda" de precios para los consumidores[cite: 1]. Simultáneamente, soluciona la falta de trazabilidad digital ("caja negra" de visitas) y la dependencia de oficinas centrales para la actualización de ofertas en los grandes establecimientos.

4. **¿Cuándo y cómo es usado el producto?**
   * Es usado de forma secuencial: el consumidor lo utiliza en el hogar para planificar y en exteriores para navegar[cite: 1]. El gerente de tienda lo utiliza durante su turno laboral para publicar "ofertas relámpago" y monitorear el alcance de sus productos en la zona.

5. **¿Qué características son importantes?**
   * La comparación multicanal de precios y generación de rutas optimizadas para el ahorro[cite: 1]. Asimismo, son críticos el dashboard de analítica para tiendas (conversión de visitas), la sincronización con inventarios locales y el sistema de validación comunitaria.

6. **¿Cómo debe verse nuestro producto y cómo comportarse?**
   * Debe presentar una interfaz intuitiva y rápida, optimizada para la alta movilidad de los usuarios en calle[cite: 1]. Para el perfil corporativo, debe ofrecer una visualización de datos profesional y robusta que facilite la toma de decisiones comerciales inmediatas.
---

#### Business Assumptions

1. **Necesidad del cliente:** Existe una carencia de herramientas que centralicen la información de precios locales para combatir el alza del costo de vida y una falta de autonomía en gerentes de tienda para comunicar ofertas locales y reducir mermas de productos perecibles.
2. **Propuesta de solución:** Estas necesidades se resuelven mediante una plataforma de comparación de costos y optimización logística para usuarios, junto con un panel de gestión ágil y analítica de conversión para establecimientos masivos.
3. **Clientes iniciales:** Familias y responsables de compras en zonas urbanas con acceso a dispositivos móviles y gerentes de sedes de supermercados o tiendas de conveniencia que buscan agilidad comercial.
4. **Valor principal esperado:** El ahorro neto real de dinero y tiempo en la canasta básica familiar y la eliminación de la "caja negra" informativa mediante la trazabilidad del mundo digital al piso de venta para el establecimiento.
5. **Beneficios adicionales:** Mayor claridad en la planificación del presupuesto y capacidad de los gerentes de sede para justificar ajustes de precios agresivos ante sus gerencias regionales basados en datos de mercado.
6. **Estrategia de adquisición:** Mayoritariamente a través de campañas en redes sociales enfocadas en economía doméstica y alianzas directas con administradores de sedes que buscan mejorar su visibilidad digital.
7. **Generación de ingresos:** Mediante una versión premium para establecimientos que requieran análisis de tendencias, reportes de "carritos abandonados" físicos y mapas de calor de búsqueda.
8. **Competencia principal:** Métodos tradicionales de búsqueda manual, aplicaciones de catálogos de una sola marca y la inercia de los procesos burocráticos de marketing central.
9. **Ventaja competitiva:** Capacidad de integrar tanto el ahorro logístico del transporte como la necesidad de rotación de stock en tiempo real del establecimiento en una sola interfaz.
10. **Mayor riesgo de producto:** Resistencia de las oficinas centrales corporativas a permitir que los gerentes de sede utilicen herramientas externas de actualización de precios locales.
11. **Estrategia de mitigación:** Implementación de herramientas de gestión simplificadas que demuestren resultados inmediatos en conversión de ventas para ganar el respaldo de las gerencias regionales.
12. **Suposición crítica de viabilidad:** Se asume que los gerentes de establecimientos valorarán la trazabilidad digital lo suficiente como para mantener sus precios actualizados de forma constante.


#### 1.2.2.3. Lean UX Hypothesis

**Hipótesis 1: Optimización del presupuesto familiar**
Creemos que facilitar la comparación de precios en tiempo real entre diversos establecimientos permitirá que los integrantes del hogar reduzcan significativamente su gasto mensual en la canasta básica. 
* **Sabremos que hemos tenido éxito:** Cuando veamos que el 75 % de los usuarios activos reporta un ahorro de al menos el 15 % en sus compras totales tras completar su primer mes de uso recurrente en la plataforma.

**Hipótesis 2: Eficiencia en la logística de compra**
Creemos que proporcionar rutas de compra optimizadas mediante geolocalización reducirá el tiempo y dinero invertido por los usuarios en traslados innecesarios entre mercados y supermercados.
* **Sabremos que hemos tenido éxito:** Cuando las métricas de navegación de la aplicación muestren una reducción promedio del 25 % en el tiempo total de desplazamiento registrado por los usuarios para completar una lista de compras multicanal.

**Hipótesis 3: Veracidad de la información comunitaria**
Creemos que implementar un sistema de validación de precios basado en la comunidad (crowdsourcing) garantizará que la información del ecosistema se mantenga veraz y competitiva frente a los cambios del mercado.
* **Sabremos que hemos tenido éxito:** Cuando el 80 % de los precios consultados por los usuarios en la plataforma coincidan con el valor real verificado en el establecimiento físico al momento de la compra.

**Hipótesis 4: Autonomía y reducción de mermas (Segmento Corporativo)**
Creemos que brindar a los gerentes de sede herramientas para publicar ofertas relámpago de forma autónoma permitirá reducir la merma de productos perecibles[cite: 5, 24].
* **Sabremos que hemos tenido éxito:** Cuando los establecimientos aliados reporten una disminución del 20 % en el desperdicio de productos frescos identificados como sobrestock local tras implementar la actualización de precios en tiempo real.

**Hipótesis 5: Trazabilidad de conversión digital a tienda**
Creemos que proporcionar métricas sobre el "alcance digital vs. entradas a tienda" permitirá que los gerentes justifiquen cambios de precios agresivos ante sus gerencias regionales basados en datos reales de comportamiento de zona.

* **Sabremos que hemos tenido éxito:** Cuando el 70 % de los gerentes de sede utilicen los reportes de SmartCart para ejecutar ajustes estratégicos en sus "productos gancho" para evitar el abandono de la canasta física.



#### 1.2.2.4. Lean UX Canvas
![Lean UX Canvas](./assets/imagenes/lean-ux-canvas.png)

## 1.3. Segmentos objetivo

### Segmentación del Dominio del Problema

Esta sección analiza los dos pilares fundamentales del ecosistema de **SmartCart**. Se contextualiza la necesidad de una solución tecnológica basada en el comportamiento del consumidor peruano frente a la inflación y la evolución de las estrategias de venta en el canal moderno de retail.

#### 1. Consumidores Finales (Shoppers Planificadores)
El segmento de consumidores finales en el Perú actual se define por una marcada transición hacia la omnicanalidad y la búsqueda estratégica de eficiencia presupuestaria. Compuesto principalmente por una población urbana de entre 25 y 50 años perteneciente a los niveles socioeconómicos B y C —quienes representan el 54.6% del gasto en consumo masivo—, este perfil ha fragmentado su proceso de compra realizando un promedio de 8 visitas trimestrales a distintos canales de venta (Kantar, 2025). 

Ante una inflación de alimentos estabilizada en 1.97% hacia finales de 2024, el comportamiento económico de este grupo ha priorizado las compras de tipo "despensa" (más de 10 categorías), las cuales ya constituyen el 21.5% del gasto total del hogar (BCRP, 2025). En consecuencia, surge una necesidad tecnológica crítica por herramientas que reduzcan la asimetría de información entre establecimientos, facilitando una planificación que podría generar un ahorro directo de hasta un 7.1% en el valor de la canasta trimestral mediante la selección optimizada del canal de venta (Kantar, 2025).

#### 2. Establecimientos de Retail (Supermercados y Tiendas de Conveniencia)
Este segmento abarca a los actores del canal moderno, sector que ha experimentado una recuperación notable y se divide estratégicamente en formatos de proximidad y de volumen que compiten por la frecuencia de visita del usuario. 

* **Formatos de Proximidad:** Liderados por marcas como Tambo+ y Mass, las tiendas de conveniencia y discounters han triplicado su participación de mercado recientemente, capturando el 29.1% del gasto en compras de proximidad de pocas categorías (Euromonitor, 2024). 
* **Formatos de Volumen:** Las cadenas de supermercados han reforzado su lealtad mediante marcas blancas, las cuales son preferidas por el 61% de los peruanos para mitigar el alza de precios en productos tradicionales (KPMG, 2025). 

Para estos establecimientos, la plataforma **SmartCart** actúa como un dinamizador de tráfico esencial: mientras las tiendas de conveniencia ganan visibilidad para sus ofertas relámpago, los supermercados logran posicionar su competitividad en compras de volumen, elevando el ticket promedio frente a un consumidor que hoy gasta de forma mucho más consciente y planificada.

---
<hr class="page-break">

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
### 2.1.1. Análisis competitivo

El entorno retail en Perú se ha digitalizado, pero sigue existiendo una brecha: las apps actuales son canales de venta (quieren que compres en su tienda), no herramientas de ahorro (que te ayudan a comprar donde sea más barato).
# Competitive Analysis Landscape - SmartCart

| **¿Por qué llevar a cabo este análisis?** | **Identificar las ventajas competitivas de SmartCart frente a soluciones de delivery y catálogos estáticos, permitiendo posicionarnos como la única herramienta que integra ahorro real con logística de rutas optimizadas en el mercado peruano.** |

| Perfil | Atributo | SmartCart | Rappi / Fazil | Tiendeo / Ofertia | Apps Supermercados |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Perfil** | **Overview** | Optimizador de rutas y comparador de precios presenciales. | Ecosistema de delivery y servicios "on-demand". | Agregador digital de encartes y folletos en PDF. | Canal de venta digital directo de cada cadena retail. |
| | **Ventaja competitiva ¿Qué valor ofrece a los clientes?** | Nuestra propuesta se basa en un algoritmo de rutas multi-tienda y una transparencia total de precios que permite comparar el costo real de góndola entre distintos establecimientos. Gracias a esto, ofrecemos al cliente un ahorro monetario máximo y una eficiencia superior en el tiempo de compra presencial, permitiéndole optimizar su presupuesto al elegir siempre la opción más económica y la ruta más corta. | Este competidor basa su éxito en una logística masiva de repartidores y una gran rapidez de entrega, lo que les permite dominar el mercado del delivery inmediato. El valor principal que ofrece a sus usuarios es la comodidad absoluta de recibir el mercado en la puerta de su casa sin necesidad de salir, priorizando el ahorro de esfuerzo físico sobre el ahorro monetario de la canasta. | Su ventaja competitiva reside en gestionar un gran volumen de catálogos digitales de diversos sectores comerciales, centralizando la publicidad en un solo lugar. Ofrecen al cliente información detallada de las promociones semanales, permitiéndoles planificar sus compras con antelación, aunque sin herramientas de movilidad o cálculo de rutas para ejecutar dicha compra de forma eficiente. | Estas plataformas aprovechan su ecosistema cerrado para ofrecer ofertas exclusivas vinculadas al uso de las tarjetas de crédito del grupo (como Oh! o Cencosud). El valor que entregan se centra en descuentos por lealtad y la acumulación de puntos, incentivando al cliente a realizar compras recurrentes dentro de su propia cadena bajo la promesa de beneficios bancarios y promociones dirigidas. |
| **Perfil de Marketing** | **Mercado Objetivo** | Familias y ahorradores de distritos con alta densidad comercial. | Usuarios de NSE A/B que priorizan tiempo sobre dinero. | Personas que planifican compras mediante folletos tradicionales. | Clientes bancarizados fieles a una marca específica. |
| | **Estrategias de marketing** | Growth hacking por ahorro real y validación comunitaria. | Marketing agresivo basado en cupones y suscripciones. | SEO basado en términos de búsqueda de "ofertas" y "catálogos". | Publicidad BTL en tiendas físicas y promociones por tarjeta. |
| **Perfil de Producto** | **Productos & Servicios** | App con listas inteligentes, mapas y comparador. | App de delivery, courier y servicios financieros. | Visualizador web y móvil de catálogos estáticos. | E-commerce con opción de despacho o recojo en tienda. |
| | **Precios & Costos** | Gratuito (Monetización vía B2B y Data). | Comisiones por producto + Tarifa de envío + Service Fee. | Gratuito para el usuario (Monetización vía marcas). | Precios de góndola; costos de envío variables. |
| | **Canales de distribución** | Móvil (Android/iOS). | Web y Móvil. | Web y Móvil. | Web y Móvil. 
| **SWOT** | SmartCart | Rappi / Fazil | Tiendeo / Ofertia | Apps Supermercados |
| **Fortalezas** |Algoritmo propietario para optimización de rutas multi-tienda (TSP); transparencia total de precios de góndola; modelo de crowdsourcing para validación inmediata. | Logística robusta y red de repartidores consolidada; gran presupuesto para marketing y adquisición de usuarios. | Amplia cobertura de catálogos digitales de diversos sectores; plataforma intuitiva para visualización de folletos. | Control total sobre su stock y precios; programas de puntos y lealtad vinculados a tarjetas de crédito. |
| **Debilidades** | Marca nueva sin posicionamiento previo; base de datos dependiente de la masa crítica inicial de usuarios. | Precios inflados y altas comisiones de servicio; imposibilidad de optimizar compras físicas multi-tienda. | Información estática (PDF) que no permite cálculos dinámicos; falta de herramientas de geolocalización de rutas. | Sesgo de marca (jamás mostrarán ofertas de la competencia); experiencia de usuario limitada a su propio ecosistema.| 
|**Oportunidades** | Crecimiento de la inflación que aumenta la sensibilidad al precio; expansión del sector retail de conveniencia (Mass, Tambo, Oxxo). | Diversificación hacia servicios financieros y pagos digitales. | Alianza con pequeños comercios para digitalizar sus volantes de ofertas. | Uso de Inteligencia Artificial para ofrecer ofertas personalizadas según el historial del cliente. |
| **Amenazas** | Acciones legales o bloqueos de datos por parte de grandes supermercados; entrada de gigantes tecnológicos al nicho de comparación de precios. | Regulaciones gubernamentales sobre los derechos laborales de los repartidores que podrían aumentar sus costos operativos. | DUsuarios jóvenes que prefieren datos dinámicos y en tiempo real sobre la lectura de catálogos tradicionales. | Crecimiento de supermercados de descuento (Hard Discount) que atraen a sus clientes con precios base más bajos. |
### 2.1.2. Estrategias y tácticas frente a competidores
En base al análisis previamente realizado proponemos las estrategias para neutralizar a la competencia y mejorar las oportunidades 

**A. Estrategia para afrontar las fortalezas de los Supermercados (Sesgo)**

Implementar el "Comparador de Canasta Universal". Mientras ellos se encierran en su marca, nosotros expondremos sus precios frente a otros. Si un supermercado tiene una fortaleza en precios de lealtad, nuestra táctica será demostrarle al usuario que, incluso con esos puntos, comprar productos en la tienda de enfrente sigue siendo más barato.

**B. Estrategia para aprovechar las debilidades del Delivery (Costos)**

Campaña de "Ahorro Transparente" Publicaremos comparativas del costo de una lista de compras en Rappi vs. la Smart-Ruta de nuestra app. Al contrastar el sobrecosto de las comisiones de delivery frente al ahorro del 20% al comprar presencialmente, capturaremos al usuario que busca optimizar su economía familiar.

**C. Estrategia para afrontar la estaticidad de los Catálogos Digitales**

Validación comunitaria en tiempo real (Crowdsourcing). Mientras Tiendeo ofrece un PDF semanal, SmartCart permitirá que los usuarios reporten precios de último minuto. Esto nos permite mantener una ventaja competitiva en velocidad de información y precisión de datos de góndola.

**D. Estrategia ante la amenaza de Bloqueo de Datos**

Gamificación y recompensas. Para asegurar que los datos fluyan incluso si los supermercados restringen su información pública, motivaremos a los usuarios (los propios clientes de las tiendas) a ser nuestros informantes mediante un sistema de puntos e insignias por cada precio validado en tienda.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Esta sección presenta el banco de preguntas estructurado para los dos segmentos identificados. Las preguntas han sido diseñadas para extraer información no solo sobre la problemática, sino también sobre el perfil conductual, tecnológico y demográfico necesario para la construcción de los arquetipos de usuario.

#### Segmento 1: Usuarios Consumidores

#### A. Información Demográfica y Antecedentes 

¿Podría indicarnos su edad, ocupación actual y en qué distrito reside?

¿Cómo está compuesta su familia y quién es el principal responsable de realizar las compras del hogar?

¿Cómo describiría su personalidad al momento de comprar? (Ej. metódico, impulsivo, buscador de ofertas, práctico).

#### B. Objetivos y Frustraciones

¿Qué es lo que más le genera malestar o pérdida de tiempo al momento de hacer las compras de la semana?

¿Cuál es su objetivo principal al planificar sus compras: ahorrar dinero, ahorrar tiempo o encontrar calidad premium?

¿Qué marcas de productos o supermercados prefiere y por qué siente afinidad hacia ellos?

#### C. Tecnología y Canales de Interacción

¿Qué dispositivos utiliza con mayor frecuencia en su día a día (Smartphone, Laptop) y qué sistema operativo prefiere?

¿Qué aplicaciones móviles utiliza con regularidad para informarse o realizar gestiones del hogar?

¿A través de qué canales digitales prefiere recibir información sobre ofertas o precios (WhatsApp, Redes Sociales, Email)?

#### D. Comportamiento frente a la solución

Si existiera una herramienta que le permitiera armar una ruta de compra optimizada para ahorrar, ¿qué funciones serían indispensables para que usted la descargue?

#### Segmento 2: Establecimientos de Consumo Masivo

#### A. Gestión de Catálogo y Visibilidad Digital
¿Qué tan complejo es hoy para su sede actualizar sus ofertas en plataformas digitales externas para que el cliente las vea antes de salir de casa?

¿De qué manera se aseguran de que el catálogo de productos que ofrecen en línea sea lo suficientemente atractivo para competir con otros locales de la zona?

#### B. Atracción y Eventos Promocionales
Cuando lanzan un "evento" (oferta relámpago, cierre de puertas), ¿cómo miden cuántas personas nuevas atrajeron específicamente por esa promoción?

¿Qué herramientas utilizan para incentivar que un usuario que está comparando precios decida finalmente venir a esta tienda y no a la competencia?

#### C. Engagement y Analítica de Datos
¿Qué tan valioso sería para su gestión saber exactamente cuántos usuarios pusieron un producto de su tienda en su "canasta de compra" pero al final no vinieron a comprarlo?

¿Actualmente cuentan con datos sobre el "alcance" real de su tienda (cuánta gente los ve en el mapa vs. cuántos entran)?

#### D. Objetivos de Conversión y SmartPrice
¿En qué medida cree que mostrar sus precios en tiempo real en una plataforma de comparación directa impactaría en su meta de atraer clientes de otros distritos o zonas?

¿Qué tipo de estadísticas sobre el comportamiento del consumidor (qué buscan, qué comparan) le ayudarían a tomar mejores decisiones sobre sus ofertas semanales?

### 2.2.2. Registro de entrevistas

#### Segmento de Consumidores: 

#### Entrevista 1:
|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| :---------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|               Nombre                | Jorge Retuerto                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|                Edad                 | 20 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|              Distrito               | La Victoria                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|              Ocupación              | Estudiante                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|         Fecha de entrevista         | 15 de abril del 2026                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Captura de pantalla de la grabación | ![]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|               Resumen               | Jorge comenta que vive como estudiante foráneo en Lima junto a su hermano y cuenta con un presupuesto mensual limitado para los gastos del hogar, lo que lo obliga a ser muy metódico y buscar siempre el establecimiento que le permita ahorrar. Su mayor molestia es la pérdida de tiempo que implica preguntar precios en múltiples puestos de manera presencial. Al comprar, prioriza la calidad sobre el precio y no tiene lealtad a marcas específicas, optando usualmente por productos genéricos, a menos que una marca ofrezca un valor único. Actualmente, no utiliza ninguna herramienta digital más allá de una aplicación de notas básica y señala que le gustaría recibir ofertas directamente a través de sus redes sociales. Para Jorge, sería indispensable que una aplicación incluya métricas sobre la calidad de los productos, ya sea mediante reseñas de otros usuarios o indicadores de confianza del establecimiento, para reducir la incertidumbre al momento de elegir dónde comprar. |

#### Entrevista 2:
|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| :---------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|               Nombre                | Samuel Quintanilla                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|                Edad                 | 20 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|              Distrito               | San juan de miraflores                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|              Ocupación              | Estudiante                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|         Fecha de entrevista         | 15 de abril del 2026                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Captura de pantalla de la grabación | ![]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|               Resumen               | El entrevistado refiere que realiza trabajos esporádicos y participa activamente en las compras del hogar, definiéndose a sí mismo como un "cazador de ofertas". Debido a que debe balancear el trabajo con sus estudios, manifiesta que su mayor frustración es perder tiempo y dinero durante el proceso de abastecimiento. No tiene preferencias por marcas y su criterio de elección se basa exclusivamente en encontrar el menor precio posible para productos similares. Para organizar su compra semanal, utiliza únicamente el bloc de notas de su celular. Considera fundamental que una aplicación cuente con un apartado específico que le permita visualizar y cuantificar el dinero que ha logrado ahorrar a lo largo del tiempo, facilitándole el control de sus finanzas personales frente a sus ingresos variables |

#### Entrevista 3:
|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| :---------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|               Nombre                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|                Edad                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|              Distrito               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|              Ocupación              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|         Fecha de entrevista         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Captura de pantalla de la grabación | ![]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|               Resumen               | El entrevistado refiere que se desempeña profesionalmente en el sector administrativo y asume la responsabilidad principal de las compras y la logística del hogar, donde reside con su madre. Se define como un comprador metódico y práctico que prioriza el análisis de etiquetas y la comparación de precios sobre la compra impulsiva. Manifiesta que sus mayores frustraciones son la falta de stock de productos específicos y la ineficiencia en los tiempos de desplazamiento y espera. Aunque busca el ahorro, mantiene una afinidad por establecimientos que ofrecen productos saludables y transparencia en el etiquetado. Para gestionar su día a día, utiliza herramientas digitales en Android, principalmente aplicaciones de banca y listas de organización. Considera indispensable que una solución tecnológica no solo optimice su ruta de compra dentro del distrito para ahorrar tiempo, sino que garantice la disponibilidad real del stock y le permita importar sus listas para identificar el establecimiento con el mejor precio del día. |

#### Segmento de Comerciantes: 

#### Entrevista 1:
|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :---------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|               Nombre                | Carlos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|                Edad                 | 45 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|              Distrito               | San Borja                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|              Ocupación              | Gerente de Supermercado                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|         Fecha de entrevista         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Captura de pantalla de la grabación | ![]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|               Resumen               | El entrevistado refiere que la gestión de ofertas en plataformas externas es actualmente un proceso ineficiente y manual que depende de la oficina central, lo que impide reaccionar con agilidad ante situaciones de sobrestock o productos perecederos. Manifiesta que su mayor frustración es la pérdida de confianza del cliente cuando el stock digital no coincide con el físico ("quiebre de stock"). Al no contar con trazabilidad del mundo digital al piso de venta, califica como "revolucionario" el acceso a métricas de "carrito abandonado físico" para justificar cambios de precios ante la gerencia regional. Considera que una plataforma de comparación en tiempo real sería una vitrina de transparencia fundamental para atraer público de otros distritos, permitiéndole además identificar "productos gancho" mediante inteligencia de mercado para sacrificar márgenes estratégicamente y asegurar la compra de la canasta completa. |

#### Entrevista 2:
|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| :---------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|               Nombre                | Andrea                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|                Edad                 | 28 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|              Distrito               | Surco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|              Ocupación              | Administradora de Tienda de Conveniencia                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|         Fecha de entrevista         | 15 de abril del 2026                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Captura de pantalla de la grabación | ![]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|               Resumen               | La entrevistada indica que la administración local carece de autonomía para actualizar promociones en tiempo real, lo que genera frustración al no poder informar sobre el agotamiento de stock de ofertas populares. Define su estrategia actual como tradicional y basada en la inmediatez física (carteles en puerta), reconociendo una nula visibilidad sobre el alcance digital de su tienda. Señala que conocer cuántos usuarios la incluyeron en una canasta digital y finalmente no asistieron le permitiría evaluar si el problema radica en su competitividad de precios o en su ubicación logística. Considera fundamental la exposición en plataformas de comparación para capturar la "venta por impulso", especialmente en categorías de bebidas y snacks, utilizando la data de búsqueda de los usuarios para diseñar combos y exhibiciones más atractivas en el mostrador principal. |

#### Entrevista 3:
|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :---------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|               Nombre                | Luis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|                Edad                 | 35 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|              Distrito               | San Juan de Miraflores                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|              Ocupación              | Jefe de Tienda                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|         Fecha de entrevista         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Captura de pantalla de la grabación | ![]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|               Resumen               | El entrevistado sostiene que su modelo de negocio se basa exclusivamente en el ahorro operativo, lo que resulta en una presencia digital casi inexistente y una dependencia total de métodos tradicionales como el "boca a boca" o volantes de papel. Admite que operan "a ciegas" respecto al comportamiento del consumidor en el entorno digital, asumiendo que el cliente asiste solo por el precio de lista. Manifiesta que no aparecer en herramientas de comparación digital es una desventaja competitiva, ya que el usuario podría omitir la tienda al no visualizar su diferencial de ahorro. Considera que mostrar sus precios en tiempo real sería su principal "campo de batalla" para arrebatar clientes a las grandes cadenas, permitiéndole además usar estadísticas de comportamiento para posicionar sus marcas propias como la alternativa de ahorro inteligente frente a marcas líderes. |


### 2.2.3. Análisis de entrevistas

**Segmento:** Consumidores (Estudiantes y Jóvenes Profesionales)  
**Total de entrevistados:** 3  
**Edades:** 20, 20 y 30 años  
**Distritos:** La Victoria y San Juan de Miraflores  

#### **Características Objetivas**
* **Responsabilidad en el abastecimiento:** **100% (3/3)** asumen el rol principal o una participación activa en la logística y ejecución de las compras del hogar.
* **Uso de herramientas de organización básicas:** **100% (3/3)** emplean métodos digitales rudimentarios para planificar sus compras, específicamente aplicaciones de notas, listas de celular o bloc de notas, sin utilizar plataformas especializadas de comparación de precios.
* **Entorno tecnológico:** **100% (3/3)** son usuarios constantes de smartphones (predominancia de Android) y utilizan aplicaciones de banca móvil, delivery o redes sociales para gestionar sus actividades diarias.
* **Perfil de gasto:** **67% (2/3)** operan bajo un presupuesto limitado o ingresos variables (estudiantes), lo que condiciona sus decisiones de compra hacia el ahorro estricto.

#### **Características Subjetivas**
* **Psicología de compra metódica:** **100% (3/3)** se definen como compradores no impulsivos; prefieren comparar precios, revisar calidad o analizar ingredientes antes de realizar una adquisición.
* **Frustración por ineficiencia temporal:** **100% (3/3)** identifican la pérdida de tiempo como su mayor punto de dolor, ya sea por desplazamientos innecesarios, falta de stock en los puntos de venta o el proceso de consultar precios manualmente.
* **Baja fidelidad a marcas comerciales:** **67% (2/3)** priorizan el ahorro o la calidad del producto genérico sobre el prestigio de una marca, mostrando apertura a cambiar de opción si el beneficio económico o funcional es claro.
* **Preferencia por canales directos:** **100% (3/3)** manifiestan interés en recibir información, ofertas o métricas de calidad a través de canales digitales ágiles como WhatsApp o redes sociales, evitando medios saturados como el correo electrónico.
* **Expectativa de valor en la solución:** Los entrevistados valoran funciones específicas según su perfil: el profesional busca **optimización de rutas y stock**, el estudiante foráneo busca **validación de calidad (reseñas)** y el estudiante con ingresos variables busca la **cuantificación histórica de su ahorro**.

**Segmento:** Establecimientos de Consumo Masivo  
**Total de entrevistados:** 3  
**Edades:** 45, 28 y 35 años  
**Distritos:** San Borja, Surco y San Juan de Miraflores  

#### **Características Objetivas**
* **Responsabilidad en la gestión operativa:** **100% (3/3)** poseen autoridad directa sobre la supervisión de stock y la actualización de precios en el piso de venta, aunque bajo lineamientos de una central corporativa.
* **Brecha de actualización digital:** **100% (3/3)** operan con sistemas internos robustos (ERP/SAP) que carecen de una conexión en tiempo real con plataformas externas, obligándolos a procesos de verificación manuales.
* **Entorno tecnológico:** **100% (3/3)** utilizan sus dispositivos móviles personales como herramienta de apoyo crítica para monitorear la reputación digital de su sede (Google Maps) y las acciones de la competencia.
* **Perfil de competitividad local:** **100% (3/3)** centran su estrategia de atracción en un radio menor a 1 km, priorizando la rotación rápida de inventario y la visibilidad de ofertas de corto plazo (ofertas relámpago).

#### **Características Subjetivas**
* **Frustración por "Ceguera de Datos":** **100% (3/3)** manifiestan una alta frustración al no poder cuantificar el flujo de usuarios que consideran su tienda en el mundo digital pero no concretan la visita física (el "carrito abandonado" del retail físico).
* **Dolor por inconsistencia de información:** **100% (3/3)** identifican las discrepancias entre los precios anunciados en plataformas digitales y los flejes físicos como el principal generador de fricción con el cliente y estrés operativo para el equipo.
* **Valoración de la Inteligencia de Mercado:** **100% (3/3)** consideran que el mayor valor de una herramienta externa no es la publicidad, sino la obtención de métricas de intención de compra y comparativas directas de competitividad en la zona.
* **Apertura a la transparencia de precios:** **67% (2/3)** perciben la comparación directa de precios como una oportunidad para ganar mercado basándose en su eficiencia, mientras que el perfil más corporativo lo ve como un reto de agilidad operativa.
* **Expectativa de valor en la solución:** Los entrevistados proyectan beneficios específicos según su perfil: el gerente corporativo busca **trazabilidad de conversión y analítica avanzada**, la administradora de conveniencia busca **visibilidad inmediata y geofencing**, y el jefe de tienda de descuento busca **alcance masivo sin costos de marketing tradicional**.

## 2.3. Needfinding

A partir del análisis de las entrevistas realizadas y del Lean UX Canvas presentado en el capítulo 1, se han identificado las necesidades y motivaciones críticas de los segmentos objetivo. Los hallazgos confirman la problemática detectada: el impacto negativo de la inflación, la alta dispersión de precios y la ineficiencia logística en los traslados, lo cual genera un desperdicio de recursos económicos y temporales en los hogares.

De esta manera, se presentan a continuación los hallazgos clave que guiarán el desarrollo de la solución para maximizar el valor entregado al usuario:

#### Segmento #1: Consumidores (Hogares y Jefes de Familia)

* **Comparar precios en tiempo real** entre diversos establecimientos (mercados y supermercados) para combatir el alza del costo de vida.
* **Optimizar rutas de compra** para reducir el tiempo de desplazamiento y los costos de transporte por la ciudad.
* **Acceder a información veraz** mediante datos validados por la comunidad que reduzcan la incertidumbre antes de salir de casa.
* **Usar una herramienta móvil ágil** que sea fácil de navegar en entornos de alta movilidad como los mercados de abastos.

#### Segmento #2: Establecimientos de Consumo Masivo (Gerentes de Sede)

* **Lograr trazabilidad digital a tienda:** Necesidad de medir cuántas transacciones en caja fueron impulsadas por promociones visualizadas en la plataforma.
* **Sincronizar stock y liquidar mermas:** Capacidad de publicar ofertas relámpago de productos perecibles (como carnes o verduras) de forma autónoma sin depender de la oficina central.
* **Obtener inteligencia de mercado local:** Acceder a datos sobre "carritos abandonados" físicos (usuarios que compararon pero no visitaron) para justificar ajustes de precios ante la gerencia regional.
* **Eliminar procesos manuales:** Reducir la carga operativa de actualizar precios en plataformas externas mediante una integración ágil con sus sistemas de inventario.

### 2.3.1. User Personas
En esta sección se presentan los arquetipos de usuario diseñados a partir de la síntesis de datos obtenidos en las entrevistas. Estos perfiles representan los comportamientos, necesidades y frustraciones de los dos segmentos clave del proyecto.

##### Segmento #1: Consumidor - Jorge Retuerto

<p align="center">
  <img src="./assets/imagenes/Persona_Jorge_UXPressia.png" width="850">
</p>

##### Segmento #2: Establecimiento Masivo - Carlos Valdivia

<p align="center">
  <img src="./assets/imagenes/Persona_Carlos_Valdivia.png" width="850">
</p>

### 2.3.2. User Task Matrix


En esta sección se presenta la *User Task Matrix*, enfocado en los dos segmentos clave: consumidores (estudiantes y jefes de hogar) y comerciantes minoristas. Este instrumento permite identificar las tareas habituales, su nivel de importancia y frecuencia, asegurando que la solución se centre en los beneficios esperados por el usuario.

| Persona | Tarea | Importancia | Frecuencia | Beneficio / Outcome |
| :--- | :--- | :--- | :--- | :--- |
| **Jorge (Consumidor)** | Comparar precios de la canasta básica en tiempo real | Alta | Alta | Permite identificar el ahorro neto inmediato antes de realizar la compra. |
| | Generar ruta de compra optimizada por geolocalización | Alta | Media | Reduce el tiempo de desplazamiento y el gasto en transporte. |
| | Validar precios reportados por otros usuarios | Media | Alta | Aumenta la confianza en la veracidad de la información comunitaria. |
| | Consultar histórico de ahorros mensuales | Baja | Media | Permite visualizar el impacto positivo en el presupuesto personal. |
| **Carlos (Gerente)** | Sincronizar stock de perecibles para ofertas relámpago | Alta | Alta | Evita merma de productos y recupera la confianza del cliente[cite: 5, 7]. |
| | Analizar reportes de "pies en tienda" vs. alcance digital | Alta | Media | Permite medir el retorno real de la inversión en ofertas[cite: 15]. |
| | Justificar ajustes de precio locales ante la gerencia regional | Media | Baja | Permite reaccionar a la competencia del distrito en 24h. |
| | Identificar "productos gancho" mediante búsquedas de zona | Media | Media | Optimiza el margen de ganancia de la canasta total. |

### 2.3.3. User Journey Mapping

En esta sección se describen los procesos actuales y puntos de contacto de nuestros segmentos objetivo, identificando los momentos de frustración y las oportunidades de mejora que SmartCart resolverá.

#### Segmento #1: Consumidor - Jorge Retuerto

<p align="center">
  <img src="./assets/imagenes/Segmento_%20Consumidor%20(Jorge%20Retuerto).png" width="850">
</p>

#### Segmento #2: Establecimiento Masivo - Carlos Valdivia

<p align="center">
  <img src="./assets/imagenes/Journey_Carlos_UXPressia.png.png" width="850">
</p>


### 2.3.4. Empathy Mapping

#### Segmento #1: Consumidor - Jorge Retuerto

![empathy-map](./assets/artifacts/empathy-map-1.png)

#### Segmento #2: Establecimiento Masivo - Carlos Valdivia

![empathy-map](./assets/artifacts/empathy-map-2.png)

### 2.3.5. Big Picture EventStorming

En esta sección se introduce y resume el proceso realizado por el equipo para el Big Picture Event Storming, que fue realizado mediante una llamada en discord y plasmado con la ayuda de la herramienta Miro. A continuación, se explica el proceso:

### 1. Open:
En esta etapa el equipo se concentró en generar la mayor cantidad de eventos de dominio posibles (cosas que suceden en el negocio) escribiendo en los post-its naranjas.

![big-picture-open](./assets/ddd/big-picture/big-picture-open.png)

### 2. Explore:
Después de la anterior etapa, en esta se concentró en ordenar cronológicamente los eventos, eliminar los eventos repetidos, identificar sus actores y posibles sistemas externos, y finalmente algunos puntos de dolor en post-its morados.

![big-picture-explore](./assets/ddd/big-picture/big-picture-explore.png)

### 3. Close: 
En esta última etapa, se documentaron en post-its rosados los problemas más relevantes detectados, junto con aspectos que debíamos investigar más a fondo o descartar según el alcance definido.

![big-picture-close](./assets/ddd/big-picture/big-picture-close.png)

Luego de conversar un poco, el equipo descartó algunos eventos y identificó mejor un sistema externo:

![big-picture-final](./assets/ddd/big-picture/big-picture-final.png)

_Enlace del Miro:_ [Big Picture EventStorming](https://miro.com/app/board/uXjVGgNF4CQ=/?share_link_id=24630775329)


### 2.3.6. Ubiquitous Language 
## 2.4. Requirements specification
### 2.4.1. User Stories
| Story ID | User | Priority | Epic | Title | Description | Acceptance Criteria |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **US01** | Visitante | Alta | EP01 | Landing: Propuesta de Valor | Como visitante, deseo ver cómo SmartCart compara supermercados y tiendas de conveniencia para ahorrar. | **E1:** Dado que el visitante accede al inicio, cuando carga la landing, entonces visualiza la comparativa de ahorro entre cadenas de retail. <br> **E2:** Dado que el visitante baja a "Beneficios", cuando lee el contenido, entonces comprende la diferencia de precios entre conveniencia y supermercado. <br> **E3:** Dado que el visitante busca cobertura, cuando el sistema muestra el mapa, entonces resalta las zonas de Lince y Surquillo. |
| **US02** | Visitante | Media | EP01 | Landing: Marcas Aliadas | Como visitante, deseo ver qué cadenas de supermercados están mapeadas para confiar en la app. | **E1:** Dado que el visitante llega a la sección de aliados, cuando el sistema carga los logos, entonces muestra marcas de supermercados y tiendas de conveniencia. <br> **E2:** Dado que el visitante hace scroll, cuando aparecen las tarjetas, entonces visualiza el número de locales registrados por cada cadena. <br> **E3:** Dado que el visitante consulta la veracidad, cuando lee la sección de datos, entonces el sistema explica que los precios se actualizan mediante la comunidad. |
| **US03** | Visitante | Baja | EP01 | Landing: Registro Interés | Como visitante, deseo dejar mi correo para recibir el aviso de lanzamiento oficial del proyecto. | **E1:** Dado que el visitante llega al formulario final, cuando ingresa un correo válido, entonces el sistema registra la suscripción en la base de datos. <br> **E2:** Dado que el formato del correo es inválido, cuando el sistema valida el campo, entonces muestra una alerta de error en la landing. <br> **E3:** Dado que el correo ya existe, cuando el sistema procesa el envío, entonces notifica que el usuario ya está registrado en la lista de espera. |
| **US04** | Consumidor | Alta | EP05 | Comparativa Retail | Como consumidor, deseo comparar mi lista entre un supermercado y una tienda de conveniencia. | **E1:** Dado que el consumidor tiene productos en su lista, cuando solicita comparar, entonces el sistema muestra la diferencia de costo total entre ambos formatos. <br> **E2:** Dado que un producto es exclusivo de supermercado, cuando se genera el ranking, entonces el sistema indica que no se encuentra en tiendas de conveniencia. <br> **E3:** Dado que el consumidor elige "Menor precio", cuando el sistema ordena, entonces prioriza el local con el ticket total más bajo. |
| **US05** | Consumidor | Alta | EP05 | Filtro por Formato | Como consumidor, deseo filtrar resultados para ver solo tiendas de conveniencia (Tambo/Oxxo). | **E1:** Dado que el consumidor activa filtros, cuando selecciona "Conveniencia", entonces el sistema oculta los grandes supermercados del mapa. <br> **E2:** Dado que el consumidor cambia a "Supermercados", cuando el sistema actualiza, entonces muestra solo locales con gran inventario (Metro/Plaza Vea). <br> **E3:** Dado que no hay filtros activos, cuando el sistema carga la vista, entonces combina ambos formatos de tienda en el radio de búsqueda. |
| **US06** | Consumidor | Alta | EP04 | Escaneo de Productos | Como consumidor, deseo escanear el código de barras en el supermercado para ver si está más barato en la tienda de conveniencia de al lado. | **E1:** Dado que el consumidor activa el escáner, cuando reconoce el código de barras, entonces muestra el precio del producto en todas las tiendas cercanas. <br> **E2:** Dado que el producto es de marca blanca, cuando el sistema busca coincidencias, entonces ofrece el equivalente de la marca blanca de la competencia. <br> **E3:** Dado que el código no se reconoce, cuando termina el proceso, entonces el sistema permite la búsqueda manual por nombre de marca. |
| **US07** | Consumidor | Media | EP04 | Armado de Canasta | Como consumidor, deseo agregar productos de marcas reconocidas para armar mi canasta básica. | **E1:** Dado que el consumidor busca una marca específica, cuando selecciona el ítem, entonces el sistema lo añade a la lista con la imagen referencial del empaque. <br> **E2:** Dado que el consumidor añade varios lácteos, cuando el sistema totaliza, entonces agrupa los productos por categorías de supermercado. <br> **E3:** Dado que el consumidor desea duplicar un ítem, cuando incrementa la cantidad, entonces actualiza el peso estimado de la canasta. |
| **US08** | Consumidor | Alta | EP06 | Ruta de Compra Eficiente | Como consumidor, deseo una ruta que incluya el supermercado y la tienda de conveniencia más cercanos. | **E1:** Dado que el consumidor selecciona dos paradas de distinto formato, cuando solicita la ruta, entonces el sistema traza el camino más corto entre ambos. <br> **E2:** Dado que el consumidor está en Surquillo, cuando inicia la navegación, entonces el sistema prioriza calles con acceso vehicular para supermercados. <br> **E3:** Dado que un local está cerrado, cuando el sistema verifica el horario de la cadena, entonces sugiere la tienda de conveniencia 24h más cercana. |
| **US09** | Consumidor | Media | EP06 | Cálculo de Tiempo | Como consumidor, deseo ver cuánto tardaré en recorrer el supermercado según la afluencia reportada. | **E1:** Dado que el consumidor selecciona un supermercado grande, cuando el sistema calcula el tiempo, entonces suma un margen estimado de permanencia en tienda. <br> **E2:** Dado que elige una tienda de conveniencia, cuando el sistema estima el tiempo, entonces reduce el margen por ser una compra rápida (express). <br> **E3:** Dado que el tráfico en Lince es alto, cuando el sistema actualiza la ruta, entonces incrementa el tiempo de llegada estimado automáticamente. |
| **US10** | Gerente Tienda | Alta | EP02 | Registro de Sucursal | Como gerente de sucursal, deseo registrar mi tienda de conveniencia para que aparezca en el mapa. | **E1:** Dado que el gerente ingresa el RUC de la cadena, cuando el sistema valida, entonces permite añadir la ubicación específica de la sucursal. <br> **E2:** Dado un local nuevo, cuando se registra la dirección en Surquillo, entonces el sistema lo posiciona geográficamente de forma exacta. <br> **E3:** Dado que la sucursal ya existe, cuando el sistema detecta la duplicidad por coordenadas, entonces deniega el nuevo registro. |
| **US11** | Gerente Tienda | Alta | EP03 | Carga de Catálogo | Como gerente de tienda, deseo subir la lista de precios de la semana para atraer clientes del distrito. | **E1:** Dado que el gerente carga el archivo de precios, cuando el sistema procesa el formato, entonces actualiza los valores de los productos en la app. <br> **E2:** Dado que un precio es una "Oferta del día", cuando se registra el cambio, entonces el sistema le asigna una etiqueta visual de descuento. <br> **E3:** Dado que el archivo tiene errores de formato, cuando el sistema valida, entonces rechaza la carga e indica la línea del error. |
| **US12** | Gerente Tienda | Media | EP03 | Alerta de Quiebre | Como gerente, deseo marcar productos como "Sin Stock" para evitar reclamos de consumidores. | **E1:** Dado que se agota el stock de un producto de alta demanda, cuando el gerente lo marca en el panel, entonces desaparece de las búsquedas inmediatas. <br> **E2:** Dado que llega el camión de reposición, cuando el gerente actualiza el estado, entonces el sistema vuelve a listar el producto. <br> **E3:** Dado que el producto está agotado en toda la cadena, cuando el administrador central lo marca, entonces se actualiza en todas las sucursales vinculadas. |
| **US13** | Gerente Tienda | Media | EP02 | Horarios Especiales | Como gerente, deseo actualizar el horario de mi tienda de conveniencia (ej: 24 horas) para informar al usuario. | **E1:** Dado que el local cambia a atención 24h, cuando el gerente guarda el cambio, entonces el sistema muestra el icono de disponibilidad nocturna. <br> **E2:** Dado un feriado próximo, cuando el gerente programa el cierre temprano, entonces el sistema notifica a los usuarios que tengan ese local en su ruta. <br> **E3:** Dado que el horario es regular, cuando el sistema llega a la hora de cierre, entonces cambia el estado a "Cerrado" automáticamente en el mapa. |
| **US14** | Consumidor | Alta | EP07 | Validación Comunitaria | Como consumidor, deseo confirmar que el precio del supermercado es el mismo que dice la app para ganar puntos. | **E1:** Dado que el consumidor está físicamente en la tienda, cuando marca "Precio Correcto", entonces el sistema le otorga 10 puntos de SmartCart. <br> **E2:** Dado que el precio cambió en góndola, cuando el consumidor ingresa el nuevo valor, entonces el sistema actualiza el precio tras una validación cruzada. <br> **E3:** Dado que el consumidor está lejos de la tienda, cuando intenta validar, entonces el sistema bloquea la acción por falta de cercanía GPS. |
| **US15** | Consumidor | Media | EP07 | Reporte de Oferta Falsa | Como consumidor, deseo denunciar si una tienda de conveniencia no respeta la oferta publicada. | **E1:** Dado que el consumidor detecta publicidad engañosa, cuando envía el reporte, entonces el sistema marca la oferta como "Bajo revisión". <br> **E2:** Dado que el reporte incluye foto del ticket, cuando el sistema lo recibe, entonces otorga un bono de puntos por veracidad de denuncia. <br> **E3:** Dado que la tienda acumula reportes, cuando el sistema procesa los datos, entonces envía una alerta al gerente del local. |
| **US16** | Gerente Tienda | Alta | EP03 | Actualización masiva | Como gerente de supermercado, deseo actualizar miles de precios mediante integración para ahorrar tiempo. | **E1:** Dado que se sube un archivo masivo, cuando el sistema termina el procesamiento, entonces emite un resumen de cambios exitosos y fallidos. <br> **E2:** Dado que hay precios con variaciones extremas, cuando el sistema los detecta, entonces solicita una confirmación manual de seguridad. <br> **E3:** Dado un error de conexión durante la subida, cuando el sistema recupera el enlace, entonces retoma la carga desde el último punto guardado. |
| **US17** | Consumidor | Media | EP10 | Alerta de Canasta Económica | Como consumidor, deseo que la app me avise cuando mi lista de supermercado salga más barata en otra cadena. | **E1:** Dado que el ahorro potencial supera el 10%, cuando el sistema detecta la baja de precios en la competencia, entonces envía una notificación push. <br> **E2:** Dado que el consumidor abre la alerta, cuando el sistema carga la comparativa, entonces muestra exactamente cuánto dinero ahorraría si cambia de tienda. <br> **E3:** Dado que el consumidor desactiva alertas, cuando el sistema encuentra ahorros, entonces los guarda en la sección "Oportunidades" para consulta manual. |
| **US18** | Consumidor | Media | EP01 | Perfil de Consumo | Como consumidor, deseo registrar mis marcas preferidas de supermercado para recibir ofertas personalizadas. | **E1:** Dado que el consumidor selecciona categorías (ej: limpieza), cuando el sistema encuentra ofertas en esos pasillos, entonces las resalta en el home. <br> **E2:** Dado que el consumidor cambia de marca preferida, cuando actualiza su perfil, entonces el sistema ajusta las recomendaciones automáticamente. <br> **E3:** Dado que no hay preferencias marcadas, cuando el sistema sugiere productos, entonces utiliza los artículos más vendidos en Lince y Surquillo. |
| **US19** | Admin | Alta | EP02 | Auditoría de Cadenas | Como admin, deseo verificar que los locales registrados pertenezcan a cadenas reales de retail. | **E1:** Dado una nueva solicitud de registro, cuando el admin cruza el RUC con el padrón oficial, entonces aprueba la visibilidad de la tienda de conveniencia. <br> **E2:** Dado un registro falso de supermercado, cuando el admin lo detecta, entonces elimina el local y bloquea la cuenta del remitente. <br> **E3:** Dado que la cadena cambia de nombre comercial, cuando el admin lo actualiza, entonces el cambio se refleja en todas las sucursales de la red. |
| **US20** | Consumidor | Media | EP08 | Resumen Mensual | Como consumidor, deseo ver cuánto ahorré comprando en tiendas de conveniencia vs supermercados. | **E1:** Dado que el consumidor accede a sus ahorros, cuando el sistema carga el gráfico, entonces diferencia el ahorro por tipo de establecimiento. <br> **E2:** Dado que el ahorro supera la meta mensual, cuando el sistema detecta el logro, entonces otorga una medalla de "Comprador Inteligente". <br> **E3:** Dado que el consumidor quiere exportar su ahorro, cuando selecciona la opción, entonces el sistema genera un resumen visual compartible. |
| **US21** | Consumidor | Media | EP08 | Recompensas Retail | Como consumidor, deseo canjear mis puntos por vales de descuento en los supermercados asociados. | **E1:** Dado que el consumidor alcanza los 500 puntos, cuando selecciona el vale de descuento, entonces el sistema genera un código alfanumérico único. <br> **E2:** Dado que el vale es para una cadena específica, cuando el sistema lo emite, entonces indica claramente en qué sucursales de Lince es válido. <br> **E3:** Dado que el punto ha vencido, cuando el usuario intenta el canje, entonces el sistema informa que el saldo no está disponible. |
| **US22** | Consumidor | Media | EP04 | Lista Compartida | Como consumidor, deseo compartir mi lista de supermercado con mi familia para que me ayuden con las compras. | **E1:** Dado que el consumidor genera un enlace de lista, cuando lo envía por chat, entonces permite que otros vean los precios comparados. <br> **E2:** Dado que otro usuario añade un producto a la lista compartida, cuando el sistema procesa el cambio, entonces actualiza el costo total para todos. <br> **E3:** Dado que se marca un producto como "Comprado", cuando el sistema actualiza la lista, entonces lo tacha en tiempo real en todos los dispositivos. |
| **US23** | Consumidor | Media | EP09 | Guía de Pasillos | Como consumidor, deseo saber en qué pasillo del supermercado están los productos de mi lista. | **E1:** Dado que el supermercado tiene mapeo de pasillos, cuando el consumidor consulta el producto, entonces el sistema indica el número de zona. <br> **E2:** Dado que el local es una tienda de conveniencia pequeña, cuando el sistema muestra la ubicación, entonces indica que es de "Acceso rápido" cerca de caja. <br> **E3:** Dado que la distribución cambió, cuando un usuario reporta la nueva ubicación, entonces el sistema actualiza el pasillo para los demás. |
| **US24** | Consumidor | Alta | EP05 | Comparación por Peso | Como consumidor, deseo comparar precios por unidad de medida (ej: $/kg) para saber qué tamaño conviene más. | **E1:** Dado que el sistema tiene el peso del producto, cuando el consumidor visualiza el precio, entonces muestra el valor calculado por kilo o litro. <br> **E2:** Dado dos productos similares de distinto tamaño, cuando el sistema los compara, entonces resalta cuál ofrece el menor costo por unidad. <br> **E3:** Dado que falta el dato del peso, cuando el sistema procesa el ítem, entonces omite la comparación por unidad para evitar errores de cálculo. |
| **US25** | Gerente Tienda | Media | EP09 | Reporte de Demanda | Como gerente, deseo ver qué productos de mi supermercado son los más buscados en la zona de Surquillo. | **E1:** Dado que el gerente accede a analíticas, cuando el sistema procesa las búsquedas, entonces muestra un ranking de los 10 productos más deseados. <br> **E2:** Dado que un producto tiene mucha demanda pero poco stock, cuando el sistema detecta la brecha, entonces emite una alerta de oportunidad de venta. <br> **E3:** Dado que la demanda cae, cuando el sistema analiza la tendencia semanal, entonces sugiere al gerente realizar una oferta para rotar el inventario. |
| **US26** | Visitante | Baja | EP01 | Landing: Preguntas de Pago | Como visitante, deseo saber si la app permite pagar directamente o solo comparar precios. | **E1:** Dado que el visitante accede a las FAQ de la landing, cuando busca "Pagos", entonces el sistema explica que la app es una herramienta de comparación. <br> **E2:** Dado que el visitante consulta sobre métodos de pago, cuando lee la respuesta, entonces conoce que los pagos se hacen en la caja de cada tienda. <br> **E3:** Dado que el visitante tiene dudas legales, cuando lee los términos, entonces comprende que SmartCart no vende productos directamente. |
| **US27** | Consumidor | Baja | EP01 | Tiendas Favoritas | Como consumidor, deseo marcar mi "Supermercado de confianza" para ver sus precios primero. | **E1:** Dado que el consumidor marca una cadena como favorita, cuando abre la app, entonces el sistema prioriza sus precios en la pantalla de inicio. <br> **E2:** Dado que hay una oferta en la tienda favorita, cuando el sistema la detecta, entonces envía una notificación especial destacada. <br> **E3:** Dado que el usuario desea cambiar de tienda favorita, cuando actualiza su elección, entonces el sistema reajusta el orden de prioridad en el ranking. |
| **US28** | Consumidor | Media | EP02 | Estado de Afluencia | Como consumidor, deseo saber si el supermercado está muy lleno para decidir si ir ahora o después. | **E1:** Dado que el sistema recibe datos de usuarios en tiempo real, cuando el consumidor consulta el local, entonces muestra un nivel de afluencia (Baja/Media/Alta). <br> **E2:** Dado que la tienda está vacía, cuando el sistema procesa el estado, entonces muestra una recomendación de "Buen momento para comprar". <br> **E3:** Dado que no hay datos recientes, cuando el sistema muestra el local, entonces indica "Afluencia habitual según horario". |
| **US29** | Gerente Tienda | Media | EP03 | Gestión de Categorías | Como gerente, deseo organizar mis productos por categorías de retail para facilitar la navegación del usuario. | **E1:** Dado que el gerente añade un ítem, cuando selecciona "Abarrotes", entonces el sistema lo posiciona en la sección correspondiente de la app. <br> **E2:** Dado que un producto pertenece a varias categorías, cuando el gerente lo etiqueta, entonces el sistema permite su búsqueda en ambos filtros. <br> **E3:** Dado que la categoría es nueva, cuando el gerente la propone, entonces el sistema la envía al administrador para su aprobación global. |
| **US30** | Consumidor | Baja | EP01 | Interfaz Adaptativa | Como consumidor, deseo que la interfaz se adapte al modo de luz de mi teléfono para leer mejor los precios. | **E1:** Dado que el teléfono está en modo noche, cuando el sistema detecta la configuración, entonces cambia la app a colores oscuros. <br> **E2:** Dado que el consumidor está bajo luz solar fuerte, cuando el sistema ajusta el contraste, entonces mejora la visibilidad de los números de precio. <br> **E3:** Dado que el usuario prefiere un modo fijo, cuando selecciona "Claro" en ajustes, entonces el sistema bloquea los cambios automáticos. |
| **US31** | Gerente Tienda | Media | EP09 | Comparador de Cadena | Como gerente de tienda de conveniencia, deseo ver el precio de mi competencia directa en el mismo distrito. | **E1:** Dado que el gerente elige un radio de 500m, cuando el sistema procesa los datos, entonces muestra los precios de las otras tiendas del mismo formato. <br> **E2:** Dado que su precio es el más bajo, cuando el sistema lo confirma, entonces le otorga una insignia de "Líder de ahorro en la zona". <br> **E3:** Dado que no hay datos de la competencia, cuando el sistema entrega el informe, entonces indica la fecha de la última actualización registrada. |
| **US32** | Consumidor | Alta | EP07 | Verificación con Ticket | Como consumidor, deseo subir una foto de mi ticket de supermercado para validar todos los precios de una vez. | **E1:** Dado que el consumidor toma foto al ticket, cuando el sistema procesa la imagen, entonces extrae los precios y los compara con la base de datos. <br> **E2:** Dado que los precios del ticket son más recientes, cuando el sistema los valida, entonces actualiza la información pública de ese supermercado. <br> **E3:** Dado que el ticket es ilegible, cuando el sistema falla en el escaneo, entonces solicita al usuario ingresar los datos manualmente para no perder los puntos. |
| **US33** | Consumidor | Media | EP05 | Sugerencia de Marca Blanca | Como consumidor, deseo que la app me sugiera la marca blanca del supermercado si es más barata que la marca líder. | **E1:** Dado que el consumidor añade un producto premium, cuando el sistema detecta un equivalente de marca propia (ej: Bell's, Tottus), entonces muestra el ahorro posible. <br> **E2:** Dado que el consumidor acepta el cambio, cuando confirma la acción, entonces el sistema actualiza la lista con el producto sugerido. <br> **E3:** Dado que no hay stock de marca blanca, cuando el sistema procesa la sugerencia, entonces la omite para no causar confusión. |
| **US34** | Consumidor | Baja | EP08 | Logros de Comprador | Como consumidor, deseo desbloquear logros por visitar diferentes supermercados en Lince y Surquillo. | **E1:** Dado que el consumidor valida precios en 5 tiendas distintas, cuando el sistema confirma la actividad, entonces desbloquea el logro "Explorador de Retail". <br> **E2:** Dado que el logro se activa, cuando el consumidor revisa su perfil, entonces visualiza la nueva insignia y un bono de puntos extra. <br> **E3:** Dado que el usuario es inactivo, cuando el sistema detecta 15 días sin validaciones, entonces envía un recordatorio amistoso para no perder su racha. |
| **US35** | Gerente Tienda | Media | EP10 | QR de Información | Como gerente, deseo generar un QR de mi tienda para que los clientes en el local descarguen la app de SmartCart. | **E1:** Dado que el gerente solicita el kit de tienda, cuando el sistema procesa el ID del local, entonces genera un código QR único con el logo de la sucursal. <br> **E2:** Dado que un cliente escanea el QR en caja, cuando el sistema lo detecta, entonces lo dirige a la landing page informativa del proyecto. <br> **E3:** Dado que el QR es escaneado, cuando el sistema registra el evento, entonces contabiliza la visita para las métricas de alcance del gerente. |
| **US36** | Consumidor | Media | EP02 | Filtro 24 Horas | Como consumidor, deseo filtrar solo tiendas de conveniencia que atiendan de madrugada. | **E1:** Dado que el consumidor activa el filtro "Abierto ahora", cuando el sistema verifica la hora (ej: 3 AM), entonces muestra solo los locales con horario extendido. <br> **E2:** Dado que no hay locales abiertos cerca, cuando el sistema termina la búsqueda, entonces muestra el local 24h más próximo aunque esté fuera del radio. <br> **E3:** Dado que el usuario desactiva el filtro, cuando el sistema refresca el mapa, entonces vuelve a mostrar todos los supermercados con su hora de apertura programada. |
| **US37** | Admin | Alta | EP07 | Moderación de Usuarios | Como admin, deseo suspender a usuarios que suben fotos de tickets falsos para engañar al sistema. | **E1:** Dado que un usuario sube una imagen que no es un ticket, cuando el admin lo rechaza, entonces el sistema envía una advertencia al perfil del usuario. <br> **E2:** Dado un usuario reincidente, cuando el admin bloquea la cuenta, entonces el sistema impide nuevos inicios de sesión desde ese dispositivo. <br> **E3:** Dado que el usuario apela la decisión, cuando el admin revisa las pruebas, entonces el sistema permite reactivar la cuenta si fue un error de procesamiento. |
| **US38** | Consumidor | Media | EP04 | Ubicaciones de Rutina | Como consumidor, deseo guardar la ubicación del supermercado donde siempre compro para comparar rápido. | **E1:** Dado que el consumidor guarda un local como "Mi Super", cuando solicita una comparación, entonces el sistema siempre lo incluye como base de referencia. <br> **E2:** Dado que el consumidor está en otro distrito, cuando abre la app, entonces el sistema le pregunta si quiere comparar contra su local habitual. <br> **E3:** Dado que el local habitual cierra permanentemente, cuando el sistema actualiza la base de datos, entonces sugiere al usuario elegir un nuevo favorito. |
| **US39** | Consumidor | Media | EP10 | Alerta de Oferta Flash | Como consumidor, deseo recibir alertas de ofertas que solo duran unas horas en el supermercado. | **E1:** Dado que la tienda publica una oferta relámpago, cuando el sistema recibe el dato, entonces envía una notificación de alta prioridad al consumidor. <br> **E2:** Dado que el consumidor está cerca del local, cuando el sistema detecta la proximidad, entonces el mensaje incluye la distancia exacta hacia la oferta. <br> **E3:** Dado que la oferta expira, cuando el sistema llega a la hora límite, entonces elimina la notificación de todos los dispositivos para no generar confusión. |
| **US40** | Gerente Tienda | Baja | EP09 | Soporte Empresas | Como gerente, deseo un canal para reportar errores en la ubicación de mi supermercado en el mapa. | **E1:** Dado que la ubicación es incorrecta, cuando el gerente envía la corrección desde su panel, entonces el sistema genera un ticket de revisión técnica. <br> **E2:** Dado que el equipo técnico corrige el pin, cuando el sistema guarda el cambio, entonces notifica al gerente que su local ya está bien posicionado. <br> **E3:** Dado que la solicitud se cierra, cuando el sistema pide feedback, entonces el gerente califica la rapidez de la corrección geográfica. |
| **US41** | Consumidor | Baja | EP06 | Brújula de Tienda | Como consumidor, deseo ver una flecha que me indique hacia dónde caminar para llegar a la tienda de conveniencia. | **E1:** Dado que el consumidor inicia la ruta peatonal, cuando el sistema activa la brújula, entonces muestra la dirección exacta del local en la pantalla. <br> **E2:** Dado que el usuario se equivoca de calle, cuando el sistema detecta el desvío, entonces vibra y recalcula la dirección de la flecha. <br> **E3:** Dado que el consumidor llega al destino, cuando el sistema confirma la posición, entonces oculta la brújula y muestra el mensaje de "Has llegado". |
| **US42** | Consumidor | Baja | EP04 | Exportar Lista de Compras | Como consumidor, deseo descargar mi lista en formato PDF para verla en el supermercado sin usar datos. | **E1:** Dado que la lista está lista, cuando el consumidor selecciona "Descargar PDF", entonces el sistema genera un documento con los nombres de productos y precios. <br> **E2:** Dado que el archivo se abre, cuando el consumidor lo visualiza, entonces los ítems aparecen ordenados por el pasillo del supermercado seleccionado. <br> **E3:** Dado un error de almacenamiento, cuando el sistema falla en la descarga, entonces ofrece enviar la lista por correo electrónico como respaldo. |
| **US43** | Gerente Tienda | Media | EP03 | Promoción de Temporada | Como gerente, deseo destacar la sección de "Cuidado Personal" durante una campaña específica. | **E1:** Dado que inicia la campaña, cuando el gerente activa el destaque en el panel, entonces los productos de esa categoría aparecen primero en las búsquedas. <br> **E2:** Dado que la campaña termina, cuando el sistema detecta la fecha fin, entonces restaura el orden de visualización estándar automáticamente. <br> **E3:** Dado que el destaque tiene costo de puntos, cuando el gerente confirma el gasto, entonces el sistema debita los puntos de la cuenta de la sucursal. |
| **US44** | Consumidor | Media | EP08 | Repetición de Canasta | Como consumidor, deseo repetir la compra de la quincena pasada para no volver a buscar cada producto. | **E1:** Dado que el consumidor accede a su historial, cuando selecciona "Repetir Canasta", entonces el sistema crea una lista nueva con todos los ítems previos. <br> **E2:** Dado que algunos precios de supermercado subieron, cuando el sistema actualiza la lista, entonces resalta en rojo los incrementos de precio. <br> **E3:** Dado que un producto ya no se fabrica, cuando el sistema procesa la copia, entonces lo marca como "Descontinuado" y ofrece buscar un sustituto. |
| **US45** | Consumidor | Media | EP10 | Filtro de Estacionamiento | Como consumidor, deseo ver qué supermercados tienen estacionamiento gratuito para ir con mi auto. | **E1:** Dado que el consumidor activa el filtro "Estacionamiento", cuando el sistema refresca el mapa, entonces muestra solo locales con espacio para vehículos. <br> **E2:** Dado que el estacionamiento tiene costo, cuando el consumidor toca el icono del local, entonces el sistema muestra la tarifa por hora reportada. <br> **E3:** Dado que el local es una tienda de conveniencia sin parking, cuando el filtro está activo, entonces el sistema oculta dicho local de los resultados. |
| **US46** | Gerente Tienda | Baja | EP02 | Notificación de Visibilidad | Como gerente, deseo recibir una alerta cuando mi tienda sea la más barata del distrito de Lince. | **E1:** Dado que los precios del local bajan, cuando el sistema confirma que es el líder del ranking, entonces envía una felicitación al panel del gerente. <br> **E2:** Dado que la competencia baja más sus precios, cuando el local pierde el primer puesto, entonces el sistema informa al gerente para que revise su estrategia. <br> **E3:** Dado que el gerente desactiva alertas de negocio, cuando ocurren cambios de posición, entonces el sistema solo registra los hitos en el historial del local. |
| **US47** | Visitante | Baja | EP09 | Landing: Transparencia | Como visitante, deseo leer cómo se protegen mis datos de consumo en la landing page. | **E1:** Dado que el visitante accede al pie de página, cuando selecciona "Privacidad", entonces el sistema despliega el documento de tratamiento de datos personales. <br> **E2:** Dado que el visitante lee la sección de seguridad, cuando el sistema explica el cifrado de datos, entonces genera confianza sobre el uso de su ubicación GPS. <br> **E3:** Dado que el visitante tiene dudas, cuando selecciona "Más info", entonces el sistema muestra un resumen en lenguaje sencillo de sus derechos ARCO. |
| **US48** | Consumidor | Baja | EP01 | Baja de Servicio | Como consumidor, deseo eliminar mi cuenta y mis listas guardadas para no dejar rastro de mi consumo. | **E1:** Dado que el consumidor solicita el borrado, cuando el sistema recibe la confirmación, entonces programa la eliminación de datos para el final del día. <br> **E2:** Dado que el usuario intenta entrar después de borrar, cuando el sistema valida la cuenta, entonces informa que el perfil ya no existe. <br> **E3:** Dado que la ley lo exige, cuando el sistema borra los datos, entonces mantiene solo los registros de transacciones anonimizados para fines estadísticos. |
| **SK01** | Developer | Alta | EP06 | Spike Optimización Retail | Investigar algoritmos de optimización para rutas que incluyan tiempos de espera en cajas de supermercado. | **E1:** Dado el flujo de compra, cuando el equipo investiga modelos de cola, entonces se entrega un documento de viabilidad técnica. <br> **E2:** Dado un set de datos de prueba, cuando se simula una ruta por 3 tiendas, entonces el cálculo del tiempo total debe tener un margen de error menor al 15%. <br> **E3:** Dado que el spike termina, cuando se documentan los resultados, entonces se define la fórmula de "Tiempo estimado" para el backend. |
| **SK02** | Developer | Alta | EP06 | Spike Mapas de Retail | Investigar la integración de mapas de interiores para grandes supermercados en Lince y Surquillo. | **E1:** Dado que los supermercados son grandes, cuando se prueban capas de interiores, entonces se determina si es posible guiar al usuario por pasillos. <br> **E2:** Dado que el costo de Mapas de Interiores es alto, cuando se analiza el presupuesto, entonces se define si se usará una solución propia o de terceros. <br> **E3:** Dado que se concluye el análisis, cuando se cierra el spike, entonces se documenta el esquema de coordenadas para estanterías de productos. |
| **SK03** | Developer | Media | EP01 | Spike Seguridad OAuth | Investigar la implementación de Single Sign-On para facilitar el registro de consumidores recurrentes. | **E1:** Dado el requerimiento de rapidez, cuando se prueba la integración con Google/Apple, entonces el sistema debe crear un perfil en menos de 5 segundos. <br> **E2:** Dado que se maneja ubicación GPS, cuando se revisan los permisos de privacidad, entonces se documenta la política de tokens necesaria. <br> **E3:** Dado que el spike termina, cuando se entrega el código base, entonces se define el estándar de cabeceras de seguridad para el API. |
| **SK04** | Developer | Media | EP07 | Spike OCR de Tickets | Analizar la precisión del reconocimiento de texto para diferentes formatos de tickets de Plaza Vea y Tambo. | **E1:** Dado un set de 20 tickets reales, cuando el motor OCR extrae la columna de precios, entonces la coincidencia exacta debe ser superior al 95%. <br> **E2:** Dado que los tickets se arrugan, cuando se prueban imágenes con ruido, entonces se determina el nivel de pre-procesamiento de imagen necesario. <br> **E3:** Dado que se selecciona el motor OCR, cuando termina el spike, entonces se documenta el costo por cada 1000 imágenes procesadas. |
| **SK05** | Developer | Alta | EP03 | Spike Base de Datos NoSQL | Investigar el uso de MongoDB para manejar catálogos de productos que cambian diariamente en supermercados. | **E1:** Dado que hay miles de productos, cuando se realizan cargas masivas simultáneas, entonces la base de datos debe mantener la latencia bajo 100ms. <br> **E2:** Dado el esquema flexible, cuando se añaden atributos como "Peso" o "Marca Blanca", entonces se verifica que no afecte a los registros antiguos. <br> **E3:** Dado que se valida el rendimiento, cuando concluye el spike, entonces se entrega el diseño de colecciones optimizado para búsquedas geoespaciales. |
| **SK06** | Developer | Baja | EP10 | Spike Integración Pagos | Investigar la viabilidad de redirección hacia pasarelas de pago de las cadenas de supermercado. | **E1:** Dado que el usuario quiere comprar online, cuando se investigan los Deep Links de las apps de retail, entonces se documenta cuáles permiten la compra directa. <br> **E2:** Dado que algunas cadenas bloquean enlaces externos, cuando se realizan pruebas de salto, entonces se identifican las restricciones técnicas por marca. <br> **E3:** Dado que el spike termina, cuando se entrega el informe, entonces se recomienda si SmartCart debe incluir el botón de "Comprar ahora" o no. |
| **TS01** | Developer | Alta | EP01 | API Login & Auth | Como Developer, deseo un endpoint de autenticación robusto para proteger las listas de los consumidores. | **E1:** Dado un POST con credenciales a `/api/v1/auth`, cuando el sistema las valida, entonces emite un JWT firmado para la sesión. <br> **E2:** Dado un intento de acceso sin token, cuando el backend recibe el request, entonces responde con 401 Unauthorized inmediatamente. <br> **E3:** Dado un token pronto a vencer, cuando el cliente solicita un refresh, entonces el API entrega un nuevo token sin pedir credenciales nuevamente. |
| **TS02** | Developer | Alta | EP05 | API Comparador | Como Developer, deseo un endpoint que calcule el ahorro entre diferentes formatos de tienda (Super vs Conveniencia). | **E1:** Dado una lista de productos y un radio GPS, cuando se invoca al comparador, entonces el sistema devuelve el costo total por cada local disponible. <br> **E2:** Dado que un local no tiene precios actualizados, cuando se procesa la comparación, entonces el API utiliza el último precio promedio de la zona como referencia. <br> **E3:** Dado que el request supera los 50 ítems, cuando el sistema lo recibe, entonces aplica paginación para no saturar la respuesta JSON. |
| **TS03** | Developer | Alta | EP03 | API Carga Catálogo | Como Developer, deseo un servicio que reciba archivos CSV y actualice los precios de supermercado en bloque. | **E1:** Dado un archivo CSV con 1000 filas, cuando se procesa en el servidor, entonces la actualización de la DB debe completarse en menos de 10 segundos. <br> **E2:** Dado que el archivo tiene IDs duplicados, cuando se valida, entonces el sistema ignora el segundo registro y emite un warning en el log. <br> **E3:** Dado que el archivo está vacío, cuando se intenta la subida, entonces el API responde con 400 Bad Request por falta de contenido. |
| **TS04** | Developer | Alta | EP06 | API Motor de Rutas | Como Developer, deseo integrar un servicio que calcule la ruta óptima visitando un supermercado y una tienda de conveniencia. | **E1:** Dado un origen y dos destinos de distinto tipo, cuando se solicita la ruta, entonces el API devuelve las coordenadas ordenadas por eficiencia de tiempo. <br> **E2:** Dado que un punto de la ruta es inaccesible por obras, cuando se consulta al proveedor de mapas, entonces el API devuelve un camino alternativo. <br> **E3:** Dado que no se encuentran rutas posibles (ej: isla), cuando el sistema falla, entonces devuelve un código 422 con un mensaje de error geográfico. |
| **TS05** | Developer | Media | EP10 | API Notificaciones Push | Como Developer, deseo un servicio para enviar alertas de ofertas flash basadas en la ubicación del consumidor. | **E1:** Dado un evento de oferta nueva, cuando el trigger se activa, entonces el API filtra a los usuarios en un radio de 5km para enviar la push. <br> **E2:** Dado que el usuario tiene la app cerrada, cuando llega la notificación, entonces el payload debe incluir el título y el resumen del ahorro. <br> **E3:** Dado un error en el proveedor de push, cuando el sistema detecta el fallo, entonces encola la notificación para un reintento posterior. |
| **TS06** | Developer | Alta | EP02 | API Validador RUC | Como Developer, deseo un microservicio que verifique la vigencia de los supermercados registrados contra SUNAT. | **E1:** Dado un RUC de 11 dígitos enviado al microservicio, cuando se recibe la respuesta externa, entonces el sistema actualiza el estado de "Verificado" en la DB. <br> **E2:** Dado que el RUC no existe, cuando se termina la consulta, entonces el API marca la cuenta del gerente como "Pendiente de revisión". <br> **E3:** Dado que el servicio externo tarda más de 5s, cuando el sistema llega al timeout, entonces responde con un código 504 Gateway Timeout controlado. |
| **TS07** | Developer | Media | EP07 | API Wallet & Puntos | Como Developer, deseo un endpoint para gestionar el balance de puntos ganado por validar tickets de compra. | **E1:** Dado un éxito en el OCR de ticket, cuando se llama al endpoint de puntos, entonces suma el monto correspondiente al saldo del consumidor. <br> **E2:** Dado un intento de canje de vale, cuando se procesa el descuento, entonces genera un código único y lo marca como "Usado" en la tabla de recompensas. <br> **E3:** Dado un GET a `/api/v1/user/points`, cuando se consulta el balance, entonces devuelve el desglose de puntos por tienda validada. |
| **TS08** | Developer | Media | EP03 | API Media Manager | Como Developer, deseo un servicio para almacenar y servir las imágenes de los productos de supermercado de forma eficiente. | **E1:** Dado que se sube una foto de producto, cuando se guarda en el servidor de archivos, entonces el sistema genera versiones en miniatura para ahorrar datos móviles. <br> **E2:** Dado una solicitud de imagen inexistente, cuando el servidor la recibe, entonces devuelve una imagen por defecto de "Producto sin foto". <br> **E3:** Dado un volumen alto de peticiones, cuando el sistema utiliza una CDN, entonces el tiempo de entrega de la imagen debe ser inferior a 300ms. |
| **TS09** | Developer | Baja | EP09 | API Analytics Retail | Como Developer, deseo un endpoint que genere estadísticas de los productos más comparados en Lince y Surquillo. | **E1:** Dado un rango de fechas y un distrito, cuando se invoca al reporte, entonces el API devuelve un JSON con el conteo de búsquedas por categoría. <br> **E2:** Dado que el distrito no tiene actividad, cuando se procesa la estadística, entonces el sistema devuelve valores en cero sin romper el formato. <br> **E3:** Dado que se solicita un reporte de marca específica, cuando se filtra por ID de cadena, entonces muestra el alcance de dicha marca frente a la competencia. |
| **TS10** | Developer | Media | EP07 | API Moderador | Como Developer, deseo un endpoint para que los administradores gestionen las denuncias de precios falsos en supermercados. | **E1:** Dado un ID de denuncia, cuando el admin envía un PUT con el veredicto, entonces el sistema actualiza el registro y notifica al usuario denunciante. <br> **E2:** Dado que la denuncia requiere más pruebas, cuando el admin cambia el estado a "En espera", entonces el sistema bloquea el cierre automático del ticket. <br> **E3:** Dado que se resuelve a favor del usuario, cuando el sistema cierra la denuncia, entonces otorga un bono de puntos de gratitud al consumidor. |
### 2.4.2. Impact Mapping

## Segmento #1: Consumidor - Jorge Retuerto
![Impact Mapping Jorge Retuerto](./assets/imagenes/Impact%20Mapping%20Jorge%20Retuerto.png)

## Segmento #2: Establecimiento Masivo - Carlos Valdivia
![Impact Mapping Carlos Valdivia](./assets/imagenes/Impact%20Mapping%20Carlos%20Valdivia.png)


### 2.4.3. Product Backlog
| Orden | ID | Título | Story Points | Epic | Prioridad |
| :--- | :--- | :--- | :---: | :--- | :--- |
| 1 | **US01** | Propuesta de Valor (Landing Page) | 3 | EP01 | Muy Alta |
| 2 | **US02** | Acceso a Tiendas (Landing Page) | 2 | EP01 | Muy Alta |
| 3 | **US23** | Comparativa de Canasta Completa | 8 | EP05 | Muy Alta |
| 4 | **US21** | Ranking de Tienda más Barata | 5 | EP05 | Muy Alta |
| 5 | **US16** | Creación de Lista de Compras | 3 | EP04 | Alta |
| 6 | **US06** | Registro de Local Comercial | 5 | EP02 | Alta |
| 7 | **US11** | Alta de Producto Individual | 3 | EP03 | Alta |
| 8 | **US13** | Actualización de Precios Real-time | 5 | EP03 | Alta |
| 9 | **US27** | Generación de Ruta Óptima (TSP) | 8 | EP06 | Alta |
| 10 | **US31** | Confirmación de Precio (Crowdsourcing) | 5 | EP07 | Alta |
| 11 | **US05** | Creación de Cuenta de Usuario | 3 | EP01 | Media |
| 12 | **US12** | Carga Masiva de Inventario (CSV) | 8 | EP03 | Media |
| 13 | **US29** | Cálculo de Gasto en Transporte | 5 | EP06 | Media |
| 14 | **US32** | Reporte de Precios Falsos | 3 | EP07 | Alta |
| 15 | **US37** | Canje de Puntos por Cupones | 5 | EP08 | Media |
| 16 | **US45** | Reporte de Visitas para Comerciantes | 5 | EP09 | Baja |
## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
Identificación de las Relaciones Iniciales y Patrones
##### 1. IAM -> Verification
   - Patrón: Open Host Service (OHS)
   - Relación IAM (U) -> Verification (D)
   - Justificación: IAM centraliza la creación de usuarios y el inicio de sesión.
     Verification depende de que exista una identidad validada para proceder con sus procesos (como la verificación de identidad contra SUNAT o la validación de la tienda). IAM se expone como un servicio abierto (OHS) para que Verification consuma el estado de la sesión y el ID del usuario sin acoplarse a la forma en que IAM encripta o almacena credenciales.
##### 2. Verification -> Store Management
   - Patrón: Customer/Supplier + Anticorruption Layer (ACL) 
   - Relación: Verification (U) → Store Management (D)
   - Justificación: Store Management requiere que una tienda esté  previamente validada para permitirle cargar inventario, registrar productos  y generar reportes. Verification actúa como proveedor del estado "Tienda Verificada". Se utiliza un ACL en Store Management para traducir este evento de verificación en la habilitación operativa de la tienda, manteniendo separados los dominios legales/tributarios de los operativos. 
##### 3. Store Management -> Notification
   - Patrón: Publisher/Subscriber + Open Host Service (OHS)
   - Relación: Store Management (U) → Notification (D) 
   - Justificación: Cuando ocurren eventos en Store Management (como falta de stock, reportes o nuevas ofertas), Notification necesita enterarse para enviar alertas push a los usuarios o administradores. Store Management publica estos eventos (Publisher) y Notification (Subscriber) los consume mediante una interfaz estándar (OHS) para transformar la data de inventario en mensajes legibles sin conocer la estructura interna del almacén.
##### 4.  Shopping Planning → Shopping journey 
   - Patrón: Customer/Supplier + Anticorruption Layer (ACL) 
   - Relación: Shopping Planning (U) → Shopping journey (D)  
   - Justificación: Shopping journey necesita la información de la lista de compras, la tienda seleccionada y los precios proyectados (definidos en Shopping Planning) para calcular la ruta óptima y la navegación. Shopping Planning provee esta data. Se usa un ACL en Shopping journey para traducir la "lista de deseos/carrito" a "coordenadas y puntos de recolección" (lógica de mapas y ubicación), aislando el dominio de decisión de compra del dominio de geolocalización.
##### 5. Shopping journey → Experience 
   - Patrón: Customer/Supplier + Anticorruption Layer (ACL) 
   - Relación: Shopping Planning (U) → Experience (D)  
   - Justificación: El contexto de Experience (que incluye calificar la tienda y calcular el ahorro final) solo puede iniciar una vez que la ruta de compra finaliza (ruta completada en Shopping journey). Shopping journey envía el evento de finalización, y Experience lo consume. El ACL traduce los datos del viaje a métricas de satisfacción y financieras, evitando que el módulo de experiencia se contamine con datos GPS o de navegación.

#### Análisis de alternativas y preguntas clave:

### 1. ¿Qué pasaría si Verification y Store Management compartieran la misma 
base de datos (Shared Kernel)? 
#### Alternativa A: Customer/Supplier + ACL (Modelo Actual)
- Ventajas: Autonomía de dominios. Las reglas de validación de 
SUNAT o identidad (Verification) pueden cambiar sin romper el 
módulo de inventario.
- Desventajas: Requiere sincronización de eventos y mantener una 
capa de traducción (ACL).
#### Alternativa B: Shared Kernel 
- Ventajas: Consistencia inmediata; si una tienda es bloqueada por 
SUNAT, el inventario se bloquea instantáneamente. 
- Desventajas: Acoplamiento fuerte. Si la lógica de verificación 
cambia, los desarrolladores de Store Management tendrían que 
coordinar obligatoriamente, enlenteciendo el desarrollo. 
#### Decisión Sustentada: Mantener Customer/Supplier + ACL. 
- Razón crítica: Las validaciones legales/tributarias tienen un ciclo 
de vida y riesgo muy distinto al manejo de stock de productos.
- Mitigación: Asegurar que los eventos de cambio de estado (ej. 
"Tienda suspendida") se transmitan con alta prioridad al módulo de 
inventario. 
### 2. ¿Qué pasaría si Store Management llamara directamente a los servicios de 
Notification sin usar eventos (Acoplamiento directo)?
#### Alternativa A: Publisher/Subscriber + OHS (Modelo Actual) 
- Ventajas: Store Management no necesita saber cómo se envían los 
correos o push notifications. Solo emite el evento "Falta de stock". 
- Desventajas: Complejidad inicial al configurar el bus de eventos o 
colas de mensajería.
#### Alternativa B: Integración directa (Llamada síncrona) 
- Ventajas: Desarrollo inicial muy rápido. 
- Desventajas: Si el servidor de notificaciones cae, Store 
Management podría fallar al intentar registrar un producto. Alto 
acoplamiento. 
#### Decisión Sustentada: Mantener Publisher/Subscriber.
- Razón crítica: Las notificaciones son procesos asíncronos por 
naturaleza. El inventario no debe depender de la disponibilidad del 
sistema de envío de mensajes. 
- Mitigación: Monitorear la cola de eventos para evitar retrasos en las 
alertas a los usuarios.
### 3. ¿Qué pasaría si Shopping Planning y Shopping journey fueran un solo 
Bounded Context? 
#### Alternativa A: Contextos separados (Modelo Actual) 
- Ventajas: Claridad de responsabilidades. Planificar y comparar 
precios es un problema de comercio electrónico; trazar rutas en 
GPS es un problema de logística.
- Desventajas: Mayor sobrecarga arquitectónica por tener dos 
dominios separados para un proceso que el usuario percibe como 
continuo. 
#### Alternativa B: Unificar en un solo Bounded Context ("Shopping")
- Ventajas: Menos integraciones y despliegue más sencillo. 
- Desventajas: Se crearía un "Big Ball of Mud". Las entidades de 
producto, precio y mapa interactuarían caóticamente, dificultando 
el mantenimiento a medida que la app crezca. 
#### Decisión Sustentada: Mantener contextos separados.
- Razón crítica: Las reglas de negocio de armar un carrito 
(presupuestos, sugerencias) son radicalmente distintas a las de 
navegar físicamente en un mapa. Requieren lógicas y quizás 
tecnologías distintas. 
- Mitigación: Diseñar una UI fluida en el Frontend para que el usuario 
no note el salto entre el planificador y el navegador de rutas.
#### Decisión Final
Luego de analizar las alternativas y sus implicancias en SmartCart, el equipo decidió mantener una arquitectura desacoplada y basada en patrones de integración definidos por Domain-Driven Design (DDD). Se priorizó la independencia de cada Bounded Context para facilitar la escalabilidad, el mantenimiento y la evolución de un sistema que integra validaciones externas, e-commerce físico y geolocalización.
- IAM (Identidad): Funciona como Open Host Service (OHS), sirviendo como un núcleo de autenticación centralizado y estándar para el resto de los contextos.
- Validaciones y Operaciones (Verification / Store Management): Se utiliza una relación Customer/Supplier con ACL (Anticorruption Layer). Esto protege la lógica del inventario de la rigidez de las normativas externas (como SUNAT).
- Experiencia de Compra (Shopping Planning / Journey): Implementa también ACL, permitiendo que la planificación de compras evolucione sin depender directamente de la complejidad de los motores de mapas y rutas.
- Comunicación Eficiente: La relación entre la gestión de tienda y las notificaciones es asíncrona (basada en eventos), lo que evita cuellos de botella y asegura que el sistema siga operativo incluso si hay retrasos en los envíos.
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
<div style="text-align: center;">
  <img src="./assets/softwarearchitecture/2.5.3.1.png" alt="Context Level Diagram style="width: 180px; height: auto;">
</div>
El objetivo del este diagrama es establecer los límites del ecosistema, identificando a los actores principales y los sistemas externos necesarios para cumplir con los objetivos del negocio.
#### Descripción de los elementos:

- SmartCart System: El sistema central que orquesta la planificación de compras, la gestión de inventarios y la navegación dentro de las tiendas.
  
- Buyer: El usuario final (comprador) que utiliza la plataforma para optimizar sus rutas de compras y gestionar sus listas personales.
  
- Merchant: El administrador de la tienda (vendedor) responsable de las actualizaciones de stock y la verificación de los datos del establecimiento.

- Sistemas externos: 
  SUNAT: Sistema externo para la validación legal y tributaria de las tiendas.
  Google Maps API: Proveedor de los datos de geolocalización y trazado de rutas necesarios.
  Push Notification Service: Infraestructura de terceros utilizada para el envío de alertas en tiempo real y correos electrónicos a los usuarios.
  
#### 2.5.3.2. Software Architecture Container Level Diagrams
<div style="text-align: center;">
  <img src="./assets/softwarearchitecture/2.5.3.2.png" alt="Container Level Diagram" style="width: 180 px; height: auto;">
</div>

El objetivo de este diagrama es descomponer el sistema SmartCart en contenedores de software independientes. Esta vista detalla las responsabilidades internas, las tecnologías elegidas y los patrones de comunicación estratégicos definidos en el análisis de Context Mapping.

- Gestión de Identidad (OHS): El IAM Service funciona como un Open Host Service, proporcionando un punto de autenticación unificado tanto para la Mobile App como para la Web App.
- Desacoplamiento Asíncrono (Pub/Sub): Para asegurar la alta disponibilidad, el Store Management Service publica eventos en el RabbitMQ. El Notification Service opera como un Subscriber, procesando alertas sin bloquear las operaciones de inventario.
- Protección del Dominio (ACL): Tanto el Shopping Journey Service como el Experience Service implementan capas de anticorrupción (Anticorruption Layers - ACL) para traducir los modelos de datos externos (de Google Maps o métricas de feedback) a la lógica interna del dominio.
- Autonomía de Servicios: Cada servicio gestiona su propia lógica e interactúa con la infraestructura de Database manteniendo los límites lógicos entre los contextos delimitados (Bounded Contexts).

#### 2.5.3.3. Software Architecture Deployment Diagrams
<div style="text-align: center;">
  <img src="./assets/softwarearchitecture/2.5.3.3.png" alt="Deployment Diagram" style="width: 180 px; height: auto;">
</div>

Este Diagrama de Despliegue muestra los contenedores de software en una infraestructura basada en la nube. Destaca cómo el sistema garantiza la escalabilidad y seguridad mediante la distribución de componentes en diversos nodos de hardware.

Detalles de la Infraestructura:

- Nodos de Cliente: Representan el hardware del usuario final (Smartphone y Laptop/PC) donde residen las aplicaciones frontend, comunicándose con la nube a través de protocolos seguros HTTPS.
- Cloud Server (AWS/Azure): Un entorno distribuido donde se alojan los microservicios. El diagrama muestra la separación física de los servicios centrales para facilitar el escalado independiente.
- Capa de Persistencia: Se despliegan múltiples instancias de Database para asegurar que los datos del dominio permanezcan aislados, apoyando la decisión de evitar un Shared Kernel y manteniendo la integridad de los datos de cada servicio.
- Interoperabilidad: La integración con entidades externas como SUNAT y Google Maps API se realiza mediante protocolos estándar HTTPS/REST, mientras que la comunicación interna entre servicios utiliza REST y AMQP para la mensajería asíncrona.

## 2.6. Tactical-Level Domain-Driven Design

### 2.6.1. Bounded Context: IAM
#### 2.6.1.1. Domain Layer
#### 2.6.1.2. Interface Layer
#### 2.6.1.3. Application Layer
#### 2.6.1.4. Infrastructure Layer
#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.1.6.2. Bounded Context Database Design Diagram

### 2.6.2. Bounded Context: Verification
#### 2.6.2.1. Domain Layer
#### 2.6.2.2. Interface Layer
#### 2.6.2.3. Application Layer
#### 2.6.2.4. Infrastructure Layer
#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.2.6.2. Bounded Context Database Design Diagram

### 2.6.3. Bounded Context: Store Management
El Bounded Context Store Management constituye la infraestructura operativa y el pilar de veracidad de datos dentro del ecosistema de SmartCart. Su misión estratégica es la gobernanza integral de los establecimientos comerciales y la sincronización precisa de sus inventarios, transformando la gestión manual en una ventaja competitiva digital. Este contexto opera bajo un modelo de negocio de Efficiency & Reliability, clasificándose como un dominio Core debido a que la exactitud de sus datos (precios y stock) es lo que garantiza el éxito del proceso de ahorro del usuario final.

La comunicación con otros contextos, como Shopping Journey o Experience, se realiza mediante un patrón Customer/Supplier, donde Store Management actúa como el proveedor de la "verdad de campo" (precios verificados y disponibilidad). Para proteger la integridad del dominio, se implementa una Anti-Corruption Layer (ACL) que filtra las actualizaciones masivas de inventario, asegurando que los modelos externos no contaminen la lógica de negocio interna.

#### 2.6.3.1. Domain Layer
La capa de dominio de Store Management concentra toda la lógica de negocio relacionada con la administración de locales y la gestión de catálogos. A continuación, se detallan los bloques de construcción tácticos identificados a partir del Impact Mapping y los requerimientos operativos del sistema:

La capa de dominio de **Store Management** concentra toda la lógica de negocio relacionada con la administración de locales y la gestión de catálogos. A continuación, se detallan los bloques de construcción tácticos identificados:

##### Aggregates

Un **Aggregate** es un clúster de objetos de dominio que se trata como una única unidad de consistencia.

| Aggregate Root | Descripción | Responsabilidad principal |
|---|---|---|
| `Store` | Representa la unidad física y legal del comercio en el sistema. | Garantizar la validez legal del comercio (RUC) y la precisión de sus datos operativos como ubicación y horarios de atención. |
| `Inventory` | Representa el conjunto dinámico de productos, precios y disponibilidad por local. | Mantener la consistencia atómica de precios y stock, especialmente durante procesos de actualización masiva mediante archivos externos. |

##### Entities

Las **Entities** son objetos con identidad propia que persisten a lo largo del tiempo y pueden cambiar de estado.

| Entidad | Aggregate al que pertenece | Atributos clave | Comportamientos |
|---|---|---|---|
| `Merchant` | `Store` | `merchantId`, `fullName: String`, `dni: String`, `email: String`, `lastLogin: LocalDateTime` | `updateProfile()`, `verifyIdentity()`, `trackActivity()` |
| `StoreBranch` | `Store` | `branchId`, `address: Address`, `openingHours: List<Hours>`, `isActive: boolean` | `openBranch()`, `closeBranch()`, `updateLocation()` |
| `Product` | `Inventory` | `productId`, `sku: Sku`, `name: String`, `brand: String`, `categoryId: Long` | `updateDetails()`, `assignCategory()`, `deactivate()` |
| `PriceItem` | `Inventory` | `priceId`, `amount: Money`, `isPromotional: boolean`, `expiryDate: LocalDate` | `applyClearance()`, `validateVigency()`, `markAsExpired()` |
| `StockPoint` | `Inventory` | `stockId`, `quantity: int`, `minThreshold: int`, `lastChecked: LocalDateTime` | `updateStock()`, `replenish()`, `checkLowStock()` |

##### Value Objects

Los **Value Objects** son objetos sin identidad propia que se definen únicamente por sus atributos. Son inmutables y encapsulan reglas de validación del dominio.

| Value Object | Atributos | Reglas de validación / invariantes |
|---|---|---|
| `Ruc` | `value: String` | Debe tener exactamente 11 dígitos numéricos. Lanza `InvalidRucException` si el formato legal de SUNAT no es válido. |
| `Money` | `amount: BigDecimal`, `currency: String` | El monto debe ser mayor o igual a cero. Soporta operaciones para el cálculo de ahorro neto. |
| `Address` | `street: String`, `latitude: double`, `longitude: double`, `district: String` | Las coordenadas GPS son obligatorias y deben estar dentro de rangos geográficos válidos. |
| `Sku` | `code: String` | Identificador alfanumérico único para sincronización. No puede ser nulo ni vacío. |
| `OpeningHours` | `openTime: LocalTime`, `closeTime: LocalTime`, `dayOfWeek: Day` | Invariante: La hora de cierre debe ser posterior a la de apertura. |
| `StockStatus` | `status: Enum{AVAILABLE, LOW_STOCK, OUT_OF_STOCK}` | Controla la visibilidad del producto en la vitrina digital según la cantidad actual. |

##### Domain Events

Los **Domain Events** son hechos relevantes que han ocurrido dentro del dominio y son publicados para que otros contextos puedan reaccionar.

| Domain Event | Aggregate origen | Atributos del payload | Significado de negocio |
|---|---|---|---|
| `StoreVerified` | `Store` | `storeId`, `ruc`, `merchantId`, `verifiedAt` | Un comercio ha superado las validaciones legales y puede empezar a publicar ofertas oficiales. |
| `PriceUpdated` | `Inventory` | `productId`, `storeId`, `newAmount`, `oldAmount`, `isPromotional` | Se ha detectado un cambio de precio que debe notificar a los usuarios interesados en el ahorro. |
| `InventoryBulkSyncCompleted` | `Inventory` | `inventoryId`, `storeId`, `totalItemsProcessed`, `timestamp` | Se ha completado con éxito la carga masiva de precios y stock desde un archivo externo. |
| `LowStockDetected` | `Inventory` | `productId`, `storeId`, `currentQuantity`, `sku` | La existencia de un producto ha caído por debajo del umbral mínimo configurado. |
| `ProductClearanceStarted` | `Inventory` | `productId`, `storeId`, `discountRate`, `expiryDate` | Se ha iniciado una liquidación de productos perecibles para evitar mermas en el local. |

##### Domain Services

Los **Domain Services** encapsulan lógica de negocio que no pertenece naturalmente a ningún Aggregate, ya que opera sobre múltiples objetos o requiere información de varias fuentes.

| Domain Service | Método principal | Descripción |
|---|---|---|
| `InventoryBulkProcessorService` | `process(StoreId id, DataStream source): BulkResult` | Orquesta la carga y validación de miles de registros de productos, asegurando la consistencia del `Inventory`. |
| `LegalComplianceService` | `validateRuc(Ruc ruc): VerificationStatus` | Coordina la validación del estado del comercio (Activo/Habido) interactuando con la ACL de servicios gubernamentales. |
| `PerformanceAnalyticsService` | `generateConversionMetrics(StoreId id): Report` | Analiza el impacto de los precios en las visitas reales para justificar ajustes estratégicos de mercado. |
| `StoreGeofencingService` | `isWithinOperationalRange(Address addr): boolean` | Valida si la ubicación de una sucursal se encuentra dentro de las zonas de cobertura logística permitidas. |

#### 2.6.3.2. Interface Layer

La capa de interfaz de **Store Management** expone las capacidades operativas y de gestión de comercios mediante una API REST. Esta es consumida por la **Web App** del Merchant para la administración de inventarios y por la **Mobile App** del Buyer para la consulta de productos y precios verificados. Todos los endpoints están prefijados con `/api/v1/store-management`.

##### StoreManagementController

| Método HTTP | Endpoint | Descripción | Request DTO | Response DTO |
|---|---|---|---|---|
| POST | `/stores` | Registra una nueva tienda y su Merchant administrador. | `RegisterStoreRequest` | `StoreResponse` |
| GET | `/stores/{storeId}` | Obtiene la información administrativa y estado de verificación legal (RUC). | — | `StoreProfileResponse` |
| POST | `/stores/{storeId}/inventory/bulk` | Carga masiva de productos y precios mediante archivos CSV/Excel. | `MultipartFile` | `BulkUploadResponse` |
| POST | `/stores/{storeId}/inventory/clearance` | Registra productos en liquidación por fecha de vencimiento próxima. | `CreateClearanceRequest` | `ClearanceResponse` |
| GET | `/stores/{storeId}/inventory` | Obtiene el catálogo de productos con stock y precios vigentes. | — (query params: `category`, `sku`) | `Page<ProductStockResponse>` |
| GET | `/stores/{storeId}/analytics` | Provee métricas de conversión y carritos abandonados para el Merchant. | — | `StoreAnalyticsResponse` |

##### DTOs de Request y Response

**RegisterStoreRequest**
```json
{
  "merchantId": "uuid",
  "name": "Bodega Don Carlos",
  "ruc": "20123456789",
  "address": {
    "street": "Av. Petit Thouars 123",
    "district": "Lince",
    "latitude": -12.084,
    "longitude": -77.035
  },
  "operatingHours": [
    { "day": "MONDAY", "open": "08:00", "close": "22:00" }
  ]
}
```
**BulkUploadResponse**
```json
{
  "jobId": "uuid",
  "status": "COMPLETED",
  "totalItemsProcessed": 1250,
  "errorsCount": 0,
  "timestamp": "2026-04-23T15:30:00"
}
```
**CreateClearanceRequest**
```json
{
  "productId": "uuid",
  "discountPercentage": 30,
  "expiryDate": "2026-04-30",
  "reason": "FECHA_PROXIMA_VENCIMIENTO"
}
```
**StoreAnalyticsResponse**
```json
{
  "storeId": "uuid",
  "metrics": {
    "totalViews": 1200,
    "abandonedCarts": 150,
    "conversionRate": 0.12,
    "topProducts": ["SKU-9921", "SKU-1022"]
  }
}
```

#### 2.6.3.3. Application Layer

La capa de aplicación orquesta los flujos de negocio coordinando los objetos del dominio, los repositorios y los servicios de infraestructura. Su responsabilidad es dirigir el flujo de trabajo sin contener lógica de decisión de negocio (orquestación pura).

##### Application Services

| Application Service | Responsabilidad |
|---|---|
| `StoreApplicationService` | Orquesta los procesos de registro, actualización de sucursales y validación legal ante entes gubernamentales (SUNAT). |
| `InventoryApplicationService` | Gestiona la lógica de sincronización de inventarios, procesando cargas masivas y gestionando el ciclo de vida de los precios y stock. |

##### Command Handlers

Los **Command Handlers** reciben un Command Object y ejecutan la operación de escritura correspondiente sobre el dominio.

| Command | Command Handler | Flujo de ejecución |
|---|---|---|
| `RegisterStoreCommand` | `RegisterStoreCommandHandler` | 1) Valida RUC único en el repositorio. 2) Invoca `LegalComplianceService`. 3) Crea el Aggregate `Store`. 4) Persiste en base de datos. 5) Publica el evento `StoreVerified`. |
| `ProcessBulkInventoryCommand` | `ProcessBulkInventoryCommandHandler` | 1) Recibe el archivo del Merchant. 2) Invoca `InventoryBulkProcessorService`. 3) Actualiza el Aggregate `Inventory`. 4) Publica `BulkInventoryUpdated`. |
| `ApplyProductClearanceCommand` | `ApplyProductClearanceCommandHandler` | 1) Identifica ítems próximos a vencer. 2) Llama a `priceItem.applyClearance()`. 3) Actualiza el estado promocional. 4) Publica `ClearanceSaleStarted`. |
| `UpdateStockLevelCommand` | `UpdateStockLevelCommandHandler` | 1) Recupera el `StockPoint`. 2) Ejecuta `updateQuantity()`. 3) Si la cantidad es menor al umbral, publica `LowStockDetected`. 4) Persiste los cambios. |

##### Query Handlers

Los **Query Handlers** se encargan exclusivamente de las operaciones de lectura, optimizando la respuesta hacia la interfaz (CQRS).

| Query | Query Handler | Descripción |
|---|---|---|
| `GetStoreProfileQuery` | `GetStoreProfileQueryHandler` | Recupera el perfil administrativo y legal de una tienda específica mediante un Read Model. |
| `GetInventoryByStoreQuery` | `GetInventoryByStoreQueryHandler` | Obtiene el catálogo de productos y precios optimizado para paginación y búsqueda rápida. |
| `GetStoreMetricsQuery` | `GetStoreMetricsQueryHandler` | Consulta las proyecciones de analítica para mostrar conversiones y carritos abandonados al Merchant. |

##### Integración con procesos de Inventario

El flujo de actualización de inventario permite que el Merchant mantenga su oferta competitiva de forma ágil mediante una arquitectura dirigida por eventos:

```text
[Merchant Web App] --sube archivo--> BulkInventory (REST)
        |
        v
[InventoryApplicationService]
        ├──> [InventoryBulkProcessorService] (Domain Service)
        ├──> [Inventory Aggregate] .updatePriceAndStock()
        └──> publica PriceChanged (Event) --capturado por--> [Shopping Journey]

```
**Al finalizar una carga masiva exitosa:**

* El **`InventoryApplicationService`** confirma la persistencia de los nuevos precios en el repositorio de datos.
* Se emite el evento **`PriceChanged`**, el cual es capturado asíncronamente por el contexto de **Shopping Journey** para actualizar el cálculo de ahorro en las rutas activas de los usuarios.
* Se recalcula el **`StockStatus`**, notificando mediante un servicio de mensajería a los usuarios que tengan el producto en su lista de favoritos si este vuelve a estar disponible.

#### 2.6.3.4. Infrastructure Layer
#### 2.6.3.4. Infrastructure Layer

La capa de infraestructura provee las implementaciones concretas de las interfaces definidas por el dominio (repositorios, mensajería, persistencia) y la capa anticorrupción (ACL) que aísla a **Store Management** de los modelos externos y servicios gubernamentales.

##### Repositories (Implementación)

Las interfaces de repositorio se definen en la capa de dominio y se implementan en infraestructura siguiendo el principio de inversión de dependencias.

| Interfaz (Dominio) | Implementación (Infraestructura) | Tecnología |
|---|---|---|
| `StoreRepository` | `StoreJpaRepository` | Spring Data JPA + PostgreSQL |
| `InventoryRepository` | `InventoryJpaRepository` | Spring Data JPA + PostgreSQL |
| `MerchantReadRepository` | `MerchantMongoReadRepository` | Spring Data MongoDB (Read Model optimizado para analítica) |

##### Mapeo a Base de Datos (Persistencia)

La persistencia utiliza una estrategia híbrida: **PostgreSQL** para los aggregates transaccionales (seguridad ACID para stock y precios) y **MongoDB** para los read models de alta frecuencia de lectura y analítica de conversión.

**Tabla `stores` (PostgreSQL)**
| Columna | Tipo | Descripción |
|---|---|---|
| `id` | UUID (PK) | Identificador único del aggregate `Store`. |
| `ruc` | VARCHAR(11) | Registro Único de Contribuyente (Unique). |
| `legal_status` | VARCHAR(20) | Estado: PENDING, VERIFIED, REJECTED. |
| `latitude` | DECIMAL(10, 8) | Coordenada para geolocalización de rutas. |
| `longitude` | DECIMAL(11, 8) | Coordenada para geolocalización de rutas. |
| `created_at` | TIMESTAMP | Fecha de registro en la plataforma. |

**Tabla `inventory_items` (PostgreSQL)**
| Columna | Tipo | Descripción |
|---|---|---|
| `id` | UUID (PK) | Identificador único del ítem de inventario. |
| `store_id` | UUID (FK) | Vínculo con el aggregate `Store`. |
| `sku` | VARCHAR(50) | Código único de producto para el Merchant. |
| `price_amount` | DECIMAL(10, 2) | Precio actual del producto. |
| `is_clearance` | BOOLEAN | Indica si el producto está en liquidación. |
| `expiry_date` | DATE | Fecha de vencimiento para productos perecibles. |

**Colección `store_analytics_model` (MongoDB)**
```json
{
  "_id": "uuid",
  "storeId": "uuid",
  "totalViews": 1540,
  "abandonedCartsCount": 42,
  "conversionRate": 0.12,
  "topProductSkus": ["SKU-001", "SKU-099"],
  "lastSync": "2026-04-23T18:00:00"
}
```
##### Consumer (StoreManagementEventConsumer)

El consumidor de eventos se encarga de escuchar los mensajes provenientes de otros contextos o servicios externos (como la validación de SUNAT) y delegar la ejecución a la capa de aplicación.

```java
@Component
public class StoreManagementEventConsumer {

    private final StoreApplicationService storeApplicationService;
    private final LegalComplianceACL legalComplianceACL;

    @RabbitListener(queues = "store.ruc-validation")
    public void handleRucValidationResponse(SunatResponse message) {
        // La ACL traduce la respuesta externa a un DTO interno
        LegalStatusDTO statusDto = legalComplianceACL.traducirRegistro(message);
        
        // Se despacha la acción a la capa de aplicación
        storeApplicationService.actualizarEstadoLegal(statusDto);
    }
}
```
#### Anti-Corruption Layer (ACL) — Integración con External Legal API & Merchant Systems

La **Anti-Corruption Layer** es el componente más crítico de la infraestructura. Actúa como un traductor bidireccional que convierte los modelos externos (APIs de SUNAT o archivos de Merchants) al lenguaje ubicuo propio de SmartCart, evitando que conceptos ajenos contaminen el modelo interno.

##### Estructura de la ACL

```text
[External API / Merchant File] ────────────────────────┐
        │                                              │
        ▼                                              │
┌─────────────────────────────────────────────────────┐│
│          StoreManagementACL                         ││
│                                                     ││
│  SunatStatusResponse     →  LegalStatus (Enum)      ││
│  ExternalProductRow      →  Product (Entity)        ││
│  RawCoordinate           →  Address (ValueObject)   ││
│  MerchantCatalogItem     →  Sku (ValueObject)       ││
└─────────────────────────────────────────────────────┘│
        │                                              │
        ▼                                              │
[Store Management Domain Model] ◄──────────────────────┘
```
#### Contrato de traducción del ACL

El contrato define las reglas de transformación entre los esquemas externos y el modelo de dominio interno, asegurando que el **Ubiquitous Language** de Store Management se mantenga consistente.

| Concepto Externo (SUNAT / Merchant) | Traducción Interna (Store Management) | Notas |
|:---|:---|:---|
| `ddp_numruc` / `tax_id` | `Ruc` (Value Object) | Valida formato de 11 dígitos antes de crear el objeto. |
| `desc_estado` (ACTIVO/HABIDO) | `legalStatus` (Enum) | Mapea estados externos al lenguaje de verificación interno. |
| `item_sku_code` | `Sku` (Value Object) | Normaliza el código para asegurar unicidad en el inventario. |
| `raw_lat` / `raw_lng` | `Address` (Value Object) | Convierte coordenadas a dobles precisos para el motor de rutas. |

#### Implementación del ACL

La implementación técnica utiliza el patrón **Adapter** para transformar las respuestas de la API de SUNAT en objetos de transferencia de datos (DTOs) que la capa de aplicación pueda procesar.

```java
@Component
public class StoreManagementACL {

    /**
     * Traduce la respuesta técnica de SUNAT al lenguaje del dominio de SmartCart.
     * @param msg Respuesta cruda de la API externa.
     * @return DTO con información normalizada.
     */
    public StoreProfileDTO traducirRegistro(SunatResponse msg) {
        return StoreProfileDTO.builder()
            .ruc(new Ruc(msg.getDdpNumruc()))
            .name(msg.getDdpNombre().trim())
            .status(mapLegalStatus(msg.getDescEstado(), msg.getDescCondicion()))
            .lastVerified(LocalDateTime.now(ZoneId.of("America/Lima")))
            .build();
    }

    /**
     * Lógica de mapeo para proteger el dominio de cambios en la API de SUNAT.
     */
    private LegalStatus mapLegalStatus(String estado, String condicion) {
        return ("ACTIVO".equalsIgnoreCase(estado) && "HABIDO".equalsIgnoreCase(condicion)) 
            ? LegalStatus.VERIFIED 
            : LegalStatus.REJECTED;
    }
}
``` 
> **Decisión de diseño: El ACL se implementa exclusivamente en la capa de infraestructura, garantizando que ninguna dependencia de modelos externos (como el esquema de la SUNAT) cruce la frontera hacia el dominio. Ante cualquier cambio del proveedor, solo el ACL requiere modificación, protegiendo la integridad del sistema ante la inestabilidad de servicios externos. 


### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se presentan los diagramas de nivel componente que ilustran la arquitectura de software del contexto de **Store Management**. Se detalla la interacción entre los controladores de API que atienden al Merchant, los servicios de aplicación encargados de orquestar la carga masiva de inventarios (Bulk Load) y los componentes de infraestructura que gestionan la persistencia transaccional. Asimismo, se muestra la integración con la **Anti-Corruption Layer (ACL)** para la validación de datos externos de la SUNAT y la comunicación asíncrona mediante el broker de mensajería para notificar cambios de precios al sistema de optimización de rutas.

### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los diagramas de nivel código que detallan la estructura interna y la implementación técnica del contexto de **Store Management**. Estos diagramas reflejan la transición del modelo conceptual a la construcción del software, integrando los principios de **Domain-Driven Design (DDD)** para garantizar que la lógica de negocio, centrada en el cumplimiento legal del comercio y la integridad del stock, se mantenga aislada de las preocupaciones tecnológicas y de persistencia.
> ![Diagrama de Componentes - Store Management](assets/diagramas/Diagrama_Component_Store_Management.png)
#### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de clases del **Domain Layer** del contexto de **Store Management** ilustra los agregados, entidades y objetos de valor que constituyen el núcleo del negocio. Se muestran las relaciones de composición dentro de los agregados de `Store` e `Inventory`, definiendo los límites de consistencia para el registro de comercios, la gestión de horarios de atención y la actualización de catálogos. Además, se detallan los métodos de negocio encargados de aplicar reglas críticas, como la normalización de SKUs, la validación de formatos de RUC y la lógica de liquidación para productos perecibles.

> ![Diagrama de Clases - Store Management](assets/diagramas/Diagrama_Clases_Store_Management.png)

#### 2.6.3.6.2. Bounded Context Database Design Diagram

El diagrama de diseño de base de datos del contexto de **Store Management** muestra la estructura de las tablas y sus restricciones de integridad en el motor relacional **PostgreSQL**. Se detallan las tablas principales que soportan el ciclo de vida del Merchant, las relaciones de clave foránea que vinculan los locales con sus respectivos ítems de inventario y la tabla de horarios de operación. Este diseño físico incluye índices espaciales para la ubicación geográfica de las tiendas y garantiza la consistencia ACID necesaria para manejar actualizaciones masivas de precios y disponibilidad de stock en tiempo real.

> ![Diagrama de Base de Datos - Store Management](assets/diagramas/Diagrama_Database_Store_Management.png)

### 2.6.4. Bounded Context: Notification

El bounded context **Notification** constituye el motor de comunicación omnicanal de SmartCart. Su misión estratégica es gestionar el envío de alertas, recordatorios y notificaciones transaccionales a través de diversos canales como Push, Email y SMS. Clasificado como un dominio de **Soporte (Supporting Subdomain)**, su valor reside en mantener el engagement del usuario y proporcionar confirmaciones críticas del sistema.

La comunicación con otros contextos como **Shopping Journey** o **Store Management** se realiza a través de un patrón **Customer/Supplier** acompañado de una **Anti-Corruption Layer (ACL)**, que garantiza que los eventos externos se traduzcan correctamente a plantillas de notificación sin contaminar el modelo de dominio propio.

---

### 2.6.4.1. Domain Layer

La capa de dominio de Notification concentra toda la lógica de negocio relacionada con la personalización y despacho de comunicaciones. A continuación se detallan los principales bloques de construcción tácticos identificados a partir del EventStorming y del Bounded Context Canvas.

#### Aggregates

Un **Aggregate** es un clúster de objetos de dominio que se trata como una única unidad de consistencia. Notification define dos aggregates raíz:

| Aggregate Root | Descripción | Responsabilidad principal |
| :--- | :--- | :--- |
| **Notification** | Representa una instancia de comunicación única enviada a un destinatario. Actúa como raíz de consistencia que agrupa el Contenido, los Intentos de Envío y el Estado. | Garantizar que el mensaje sea procesado, renderizado y entregado, manteniendo la integridad del historial de intentos y estados. |
| **UserPreference** | Representa el perfil de configuración de comunicaciones de un usuario (Buyer o Merchant). | Validar y filtrar qué notificaciones pueden ser enviadas según los canales permitidos y los horarios de silencio definidos. |

#### Entities

Las **Entities** son objetos con identidad propia que persisten a lo largo del tiempo y pueden cambiar de estado.

| Entidad | Aggregate al que pertenece | Atributos clave | Comportamientos |
| :--- | :--- | :--- | :--- |
| **Template** | Notification | `templateId`, `nombre`, `asuntoBase`, `cuerpoBase`, `tipoCanal: ChannelType` | `renderizarContenido()`, `validarVariables()`, `esVigente()` |
| **DeliveryAttempt** | Notification | `attemptId`, `fechaIntento`, `errorLog`, `proveedorUtilizado`, `duracionMs` | `registrarFallo()`, `esReintentable()`, `marcarExito()` |
| **ChannelConfig** | UserPreference | `canalId`, `tipo: ChannelType`, `estaHabilitado: boolean`, `tokenContacto: String` | `activar()`, `desactivar()`, `actualizarToken()`, `esValido()` |

#### Value Objects

Los **Value Objects** son objetos sin identidad propia que se definen únicamente por sus atributos. Son inmutables y encapsulan reglas de validación del dominio.

| Value Object | Atributos | Reglas de validación / invariantes |
| :--- | :--- | :--- |
| **NotificationId** | `valor: UUID` | Identificador inmutable generado al inicio del proceso de notificación. |
| **Recipient** | `email: String`, `phone: String`, `fcmToken: String` | Debe validar el formato de email o estructura de token de Firebase según el canal. Lanza `InvalidRecipientException` si falla. |
| **MessageContent** | `asunto: String`, `cuerpo: String` | No puede ser nulo ni vacío. El cuerpo se genera tras inyectar variables en la Template. |
| **EstadoEnvio** | `estado: Enum {PENDIENTE, ENVIADO, FALLIDO, LEIDO}` | Controla el ciclo de vida del mensaje. Transiciones válidas: `PENDIENTE` → `ENVIADO`, `FALLIDO` → `PENDIENTE` (si reintentos < 3). |
| **ScheduleWindow** | `horaInicio: LocalTime`, `horaFin: LocalTime` | Define el rango horario permitido para comunicaciones. Valida que `horaInicio` < `horaFin`. |

#### Domain Events

Los **Domain Events** son hechos relevantes que han ocurrido dentro del dominio y son publicados al Message Broker para que otros contextos reaccionen.

| Domain Event | Aggregate origen | Atributos del payload | Significado de negocio |
| :--- | :--- | :--- | :--- |
| **NotificacionCreada** | Notification | `id`, `templateId`, `recipientId`, `priority` | El sistema ha registrado una nueva necesidad de comunicación para ser procesada. |
| **NotificacionEnviada** | Notification | `id`, `gatewayReference`, `fechaEnvio` | El mensaje ha sido aceptado con éxito por el proveedor externo (FCM, AWS SES). |
| **EnvioFallido** | Notification | `id`, `ultimoError`, `intentoActual` | Se ha registrado un fallo en el envío. Dispara la lógica de reintento si no se ha alcanzado el máximo. |
| **PreferenciaModificada** | UserPreference | `userId`, `canal`, `nuevoEstado` | El usuario ha actualizado sus permisos de contacto, afectando futuros envíos. |

#### Domain Services

Los **Domain Services** encapsulan lógica de negocio que no pertenece naturalmente a un Aggregate o Entity, operando sobre múltiples objetos o fuentes de información.

| Domain Service | Método principal | Descripción |
| :--- | :--- | :--- |
| **TemplateEngineService** | `procesar(Template t, Map vars): MessageContent` | Realiza el reemplazo técnico de placeholders por datos reales del contexto (ej. nombre del producto, precio). |
| **NotificationDispatcherService** | `despachar(Notification n, UserPreference p)` | Servicio que coordina con la infraestructura para enviar el mensaje, verificando primero las preferencias de privacidad. |
| **RetryPolicyService** | `calcularProximoIntento(DeliveryAttempt last): LocalDateTime` | Implementa una estrategia de **Exponential Backoff** para determinar el tiempo de espera óptimo antes de un reintento. |
### 2.6.4.2. Interface Layer

La capa de interfaz de **Notification** expone sus capacidades hacia el exterior mediante una API REST consumida principalmente por la **Mobile App** (Buyer) y la **Web App** (Merchant). Todos los endpoints están prefijados con `/api/v1/notifications`.

#### NotificationController

| Método HTTP | Endpoint | Descripción | Request DTO | Response DTO |
| :--- | :--- | :--- | :--- | :--- |
| **POST** | `/preferences` | Permite a un usuario configurar sus canales de comunicación y tokens. | `UpdatePreferencesRequest` | `PreferenceResponse` |
| **GET** | `/preferences/{userId}` | Obtiene la configuración de canales y horarios de silencio de un usuario. | — | `PreferenceResponse` |
| **GET** | `/history/{userId}` | Obtiene el listado paginado de notificaciones enviadas a un usuario. | — (query params: `page`, `size`) | `Page<NotificationSummary>` |
| **POST** | `/send-test` | Envía una notificación de prueba para validar la integración de tokens/canales. | `TestNotificationRequest` | `NotificationStatusResponse` |

#### DTOs de Request y Response

**UpdatePreferencesRequest**
```json
{
  "userId": "uuid",
  "channels": [
    {
      "tipo": "PUSH",
      "estaHabilitado": true,
      "tokenContacto": "fcm_token_987654321"
    }
  ],
  "ventanaSilencio": {
    "horaInicio": "22:00:00",
    "horaFin": "07:00:00"
  }
}
``` 
**NotificationStatusResponse**
```json
{
  "notificationId": "uuid",
  "estado": "ENVIADO",
  "canal": "PUSH",
  "fechaEnvio": "2026-04-23T12:00:00",
  "intentos": 1
}

``` 
### 2.6.4.3. Application Layer

La capa de aplicación orquesta los flujos de negocio coordinando los objetos del dominio, los repositorios y los servicios de infraestructura. No contiene lógica de dominio propia; su responsabilidad es dirigir el flujo de trabajo (orchestration).

#### Application Services

| Application Service | Responsabilidad |
| :--- | :--- |
| **NotificationApplicationService** | Punto de entrada principal para las operaciones de comunicación. Recibe comandos desde la Interface Layer o Message Broker, delega en los agregados y publica los domain events. |
| **PreferenceApplicationService** | Orquesta la actualización de `UserPreference` de un usuario en respuesta a cambios en su configuración o renovaciones de tokens de dispositivo. |

#### Command Handlers

Los **Command Handlers** reciben un Command Object y ejecutan la operación de escritura correspondiente sobre el dominio.

| Command | Command Handler | Flujo de ejecución |
| :--- | :--- | :--- |
| **SendNotificationCommand** | **SendNotificationCommandHandler** | 1) Valida el `userId`. 2) Recupera `UserPreference`. 3) Llama a `Notification.renderizarContenido()`. 4) Persiste el aggregate. 5) Publica `NotificacionCreada`. 6) Dispara el envío físico vía infraestructura. |
| **UpdatePreferencesCommand** | **UpdatePreferencesCommandHandler** | 1) Recupera `UserPreference` activa. 2) Actualiza `ChannelConfig` según los nuevos tokens recibidos. 3) Persiste cambios en el repositorio. 4) Publica `PreferenciaModificada`. |
| **RetryNotificationCommand** | **RetryNotificationCommandHandler** | 1) Recupera la `Notification` fallida. 2) Evalúa `RetryPolicyService.calcularProximoIntento()`. 3) Registra nuevo `DeliveryAttempt`. 4) Publica `NotificacionEnviada` si tiene éxito. |

#### Query Handlers

Los **Query Handlers** se encargan exclusivamente de las operaciones de lectura, sin modificar el estado del sistema (principio CQRS).

| Query | Query Handler | Descripción |
| :--- | :--- | :--- |
| **GetUserPreferencesQuery** | **GetUserPreferencesQueryHandler** | Recupera el `UserPreference` público de un usuario dado su `userId`. Utiliza una proyección de lectura optimizada. |
| **GetNotificationHistoryQuery** | **GetNotificationHistoryHandler** | Obtiene la lista paginada de notificaciones para un usuario, ordenada por fecha de creación descendente. |
| **GetStatusQuery** | **GetStatusQueryHandler** | Recupera el `EstadoEnvio` calculado para una notificación específica. |

#### Integración con el evento de finalización de recorrido

El flujo que detona el ciclo de feedback y comunicación se inicia cuando **Shopping Journey** publica el evento de dominio `RecorridoFinalizado`. La Application Layer de **Notification** actúa como consumidor de este evento a través del Message Broker (RabbitMQ/Kafka):

```text
[Shopping Journey] --publica--> RecorridoFinalizado (AMQP)
       |
       v
[NotificationEventConsumer] --traduce via ACL--> SendNotificationCommand
       |
       v
[NotificationApplicationService]
       |-- dispatch(SendNotificationCommand)
       |-- dispatch(SolicitarFeedbackCommand) <-- dispara notificación push al Buyer

``` 
**Al recibir el evento `RecorridoFinalizado`, el `NotificationApplicationService` realiza las siguientes acciones:**

1. **Traducción de Contexto:** Traduce el evento externo (procedente de Shopping Journey) a su modelo interno de datos utilizando el **ShoppingJourneyACL** para evitar el acoplamiento de modelos.
2. **Procesamiento de Resumen:** Despacha el `SendNotificationCommand` para procesar y preparar el resumen de la compra que se enviará al usuario.
3. **Validación de Políticas de Envío:** Verifica la **Ventana de Silencio** (`ScheduleWindow`) definida en el agregado `UserPreference`. Si el usuario se encuentra en su horario de descanso o "No Molestar", la notificación se encola para ser enviada automáticamente al finalizar dicho periodo.
4. **Ejecución de Despacho Omnicanal:** Envía la notificación final que, a través del **NotificationDispatcherService** (utilizando proveedores como FCM para Push o AWS SES para Email), invita al **Buyer** a realizar dos acciones clave:
    * Calificar la experiencia con el **Merchant**.
    * Reportar posibles errores de precio detectados durante la compra.
### 2.6.4.4. Infrastructure Layer

La capa de infraestructura provee las implementaciones concretas de las interfaces definidas por el dominio (repositorios, mensajería, persistencia) y la capa anticorrupción que aísla a **Notification** de los modelos externos.

#### Repositories (Implementación)

Las interfaces de repositorio se definen en la capa de dominio y se implementan en infraestructura siguiendo el principio de inversión de dependencias.

| Interfaz (Dominio) | Implementación (Infraestructura) | Tecnología |
| :--- | :--- | :--- |
| **NotificationRepository** | **NotificationJpaRepository** | Spring Data JPA + PostgreSQL |
| **UserPreferenceRepository** | **UserPreferenceJpaRepository** | Spring Data JPA + PostgreSQL |
| **TemplateReadModelRepository** | **TemplateMongoReadRepository** | Spring Data MongoDB (Read Model optimizado para carga de plantillas) |

#### Mapeo a Base de Datos (Persistencia)

La persistencia utiliza una estrategia híbrida conforme al modelo visto en el diagrama de arquitectura de contenedores: **PostgreSQL** para los aggregates transaccionales y **MongoDB** para los read models de alta frecuencia de lectura.

**Tabla `notifications` (PostgreSQL)**

| Columna | Tipo | Descripción |
| :--- | :--- | :--- |
| **id** | **UUID (PK)** | Identificador único del aggregate `Notification`. |
| **user_id** | **UUID** | Identificador del destinatario (Buyer o Merchant). |
| **tipo_canal** | **VARCHAR(20)** | Canal utilizado: PUSH, EMAIL, SMS. |
| **contenido_renderizado** | **TEXT** | Cuerpo final del mensaje enviado tras procesar la plantilla. |
| **estado_envio** | **VARCHAR(15)** | PENDIENTE, ENVIADO, FALLIDO. |
| **created_at** | **TIMESTAMP** | Fecha de creación del registro. |
| **updated_at** | **TIMESTAMP** | Fecha de última modificación. |

**Tabla `user_preferences` (PostgreSQL)**

| Columna | Tipo | Descripción |
| :--- | :--- | :--- |
| **id** | **UUID (PK)** | Identificador único del aggregate `UserPreference`. |
| **user_id** | **UUID (UNIQUE)** | Identificador del usuario (vínculo único). |
| **ventana_inicio** | **TIME** | Hora de inicio del periodo de silencio. |
| **ventana_fin** | **TIME** | Hora de fin del periodo de silencio. |
| **updated_at** | **TIMESTAMP** | Fecha del último recálculo o cambio. |

**Colección `templates_read_model` (MongoDB)**

```json
{
  "_id": "uuid",
  "codigo": "RECORRIDO_FINALIZADO",
  "buyerId": "uuid",
  "asunto": "Resumen de tu compra",
  "cuerpo": "Hola {{nombre}}, tu ahorro fue de {{monto}}...",
  "estado": "ACTIVO",
  "fechaActualizacion": "2026-04-21T12:31:00"
}
``` 
> ** Esta colección es un Read Model que permite la recuperación instantánea de estructuras de mensaje predefinidas sin realizar joins complejos en la base de datos relacional, optimizando el tiempo de respuesta del dispatcher.

#### Integración con RabbitMQ (Mensajería Asíncrona)

La integración con el Message Broker se realiza mediante Spring AMQP. **Notification** actúa como **consumidor (Subscriber)** del evento `RecorridoFinalizado` y como **productor (Publisher)** de eventos de entrega.

**Configuración de colas y exchanges:**

| Exchange | Queue | Routing Key | Dirección | Descripción |
| :--- | :--- | :--- | :--- | :--- |
| **shopping-journey.events** | **notification.recorrido-finalizado** | **recorrido.finalizado** | **Inbound (Consumer)** | Consume el fin de recorrido para enviar el resumen y feedback. |
| **notification.events** | **analytics.notificacion-enviada** | **notificacion.enviada** | **Outbound (Publisher)** | Informa que un mensaje fue entregado exitosamente. |
| **notification.events** | **experience.feedback-solicitado** | **feedback.solicitado** | **Outbound (Publisher)** | Avisa a Experience que ya se pidió la reseña al usuario. |

**Consumer (`NotificationEventConsumer`):**

```java
@RabbitListener(queues = "notification.recorrido-finalizado")
public void handleRecorridoFinalizado(RecorridoFinalizadoMessage message) {
    RecorridoFinalizadoDTO dto = shoppingJourneyACL.traducir(message);
    notificationApplicationService.procesarNotificacionPostCompra(dto);
}

``` 
#### Anti-Corruption Layer (ACL) — Integración con Shopping Journey

La **Anti-Corruption Layer** es el componente más crítico de la infraestructura de **Notification**. Actúa como un traductor que convierte los modelos de **Shopping Journey** al lenguaje ubicuo de **Notification**, evitando que conceptos ajenos contaminen el modelo de dominio interno.

**Estructura de la ACL:**

```text
[Shopping Journey Event] ─────────────────────────────┐
        │                                              │
        ▼                                              │
┌─────────────────────────────────────────────────────┐│
│          ShoppingJourneyACL                         ││
│                                                     ││
│  RecorridoFinalizadoMessage  →  RecorridoFinalizadoDTO  │
│  UserMessage                 →  RecipientId (ValueObject) │
│  StoreMessage                →  StoreId (ValueObject)   │
└─────────────────────────────────────────────────────┘│
        │                                              │
        ▼                                              │
[Notification Domain Model] ◄──────────────────────────┘
```
**Contrato de traducción del ACL:**

| Concepto externo (Shopping Journey) | Traducción interna (Notification) | Notas |
| :--- | :--- | :--- |
| **RecorridoFinalizado.journeyId** | **RecorridoId (Value Object)** | Se usa para rastrear el origen de la notificación y mantener la correlación entre contextos. |
| **RecorridoFinalizado.userId** | **RecipientId (Value Object)** | Traducido al ID del destinatario dentro del contexto de mensajería omnicanal. |
| **RecorridoFinalizado.timestamp** | **FechaEvento: LocalDateTime** | Ajustado a la zona horaria local (`America/Lima`) para asegurar la precisión en las reglas de envío. |

**Implementación del ACL:**

```java
@Component
public class ShoppingJourneyACL {

    public RecorridoFinalizadoDTO traducir(RecorridoFinalizadoMessage msg) {
        return RecorridoFinalizadoDTO.builder()
            .recorridoId(new RecorridoId(msg.getJourneyId()))
            .recipientId(new RecipientId(msg.getUserId()))
            .tiendaNombre(msg.getTiendaNombre())
            .fechaFinalizacion(
                msg.getTimestamp().atZone(ZoneId.of("America/Lima")).toLocalDateTime()
            )
            .build();
    }
}

```
> **  Decisión de diseño: El ACL garantiza que si el formato de los eventos de Shopping Journey cambia, solo se deba modificar este componente de infraestructura. Esto protege la lógica de despacho, las políticas de reintento y las plantillas del dominio de Notification, manteniendo la integridad del sistema ante cambios externos.

#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

En esta sección se presentan los **diagramas de nivel componente** que ilustran la arquitectura de software del contexto de **Notification**. Se muestra la interacción entre los diferentes componentes, servicios y capas que conforman este bounded context, destacando el flujo desde la recepción de eventos externos hasta el despacho omnicanal. Se integra con la base de datos relacional y documental definida en el diagrama de contenedores.

#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se presentan los **diagramas de nivel código** que detallan la estructura interna del contexto de **Notification**. Se incluyen diagramas de clases y diseño de base de datos que reflejan cómo se implementan los elementos del dominio y cómo se gestionan las relaciones entre ellos para garantizar un sistema de comunicación escalable y resiliente.
> ![Diagrama de Componentes - Notification](assets/diagramas/Diagrama_Component_Notification.png)
##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de clases del **Domain Layer** del contexto de **Notification** ilustra las entidades, objetos de valor y servicios que componen este bounded context. Se muestran las relaciones entre los agregados de `Notification` y `UserPreference`, detallando sus atributos y métodos principales, como la validación de ventanas de silencio y el manejo de intentos de envío.
> ![Diagrama de Clases - Notification](assets/diagramas/Diagrama_Clases_Notification.png)
##### 2.6.4.6.2. Bounded Context Database Design Diagram

El diagrama de **diseño de base de datos** del contexto de **Notification** muestra la estructura de las tablas y sus relaciones en la base de datos relacional (PostgreSQL) y documental (MongoDB). Se detallan las tablas principales para el historial de notificaciones y preferencias de usuario, asegurando la integridad de los datos necesarios para el seguimiento de comunicaciones.
> ![Diagrama de Base de Datos - Notification](assets/diagramas/Diagrama_Database_Notification.png)
### 2.6.5. Bounded Context: Shopping Planning
#### 2.6.5.1. Domain Layer
#### 2.6.5.2. Interface Layer
#### 2.6.5.3. Application Layer
#### 2.6.5.4. Infrastructure Layer
#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.5.6.2. Bounded Context Database Design Diagram

### 2.6.6. Bounded Context: Shopping Journey
#### 2.6.6.1. Domain Layer
#### 2.6.6.2. Interface Layer
#### 2.6.6.3. Application Layer
#### 2.6.6.4. Infrastructure Layer
#### 2.6.6.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.6.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.6.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.6.6.2. Bounded Context Database Design Diagram

### 2.6.7. Bounded Context: Experience
#### 2.6.7.1. Domain Layer
#### 2.6.7.2. Interface Layer
#### 2.6.7.3. Application Layer
#### 2.6.7.4. Infrastructure Layer
#### 2.6.7.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.7.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.7.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.7.6.2. Bounded Context Database Design Diagram

<hr class="page-break">

## Conclusiones
### Conclusiones y recomendaciones

<hr class="page-break">

## Bibliografía       

Banco Central de Reserva del Perú. (2025). Reporte de Inflación: Panorama actual y proyecciones macroeconómicas. https://www.bcrp.gob.pe/publicaciones/reporte-de-inflacion.html

Infobae. (2025, 3 de agosto). ¿Alcanza el sueldo mínimo para vivir en el Perú? Así se reparten S/1.025 al mes en Lima y regiones. https://www.infobae.com/peru/2025/08/03/alcanza-el-sueldo-minimo-para-vivir-en-el-peru-asi-se-reparten-s1025-al-mes-en-lima-y-regiones/

Instituto Nacional de Estadística e Informática. (2026). Variación de los Indicadores de Precios de la Economía: Marzo 2026 (Informe Técnico N° 04). https://www.inei.gob.pe/media/MenuRecursivo/boletines/informe_de_precios_mar26.pdf

Kantar Worldpanel. (2025). Consumer Insights Perú: Comportamiento y Perfiles de Compra del 'Power Adult'. https://www.kantarworldpanel.com/pe/news/Consumer-Insights-Peru-Power-Adult-2025

ResearchGate. (2024). Optimization of the Traveling Salesman Problem (TSP) in Urban Retail Environments: A study on consumer behavior in emerging markets. https://www.researchgate.net/publication/380000_Optimization_TSP_Urban_Retail

Banco Central de Reserva del Perú [BCRP]. (2025, 9 de enero). Inflación: Diciembre 2024 (Nota de Estudios N° 03-2025). https://www.bcrp.gob.pe/docs/Publicaciones/Notas-Estudios/2025/nota-de-estudios-03-2025.pdf

Euromonitor International. (2024, 7 de marzo). Tiendas de conveniencia y discounters en Perú: Impacto en el retail. Forbes Perú. https://forbes.pe/negocios/2024-03-07/tiendas-de-conveniencia-y-discounters-en-peru

Instituto Nacional de Estadística e Informática [INEI]. (2025). Precios al consumidor de Lima Metropolitana subieron 1,51% en el año 2025. Plataforma del Estado Peruano. https://www.gob.pe/institucion/inei/noticias/1325052-inei-precios-al-consumidor-de-lima-metropolitana-subieron-1-51-en-el-ano-2025

Kantar Division Worldpanel. (2024). El rol de las marcas propias en la canasta familiar peruana: Reporte Anual. https://www.kantarworldpanel.com/pe/news/marcas-propias-peru-2024

Kantar Division Worldpanel. (2025, 15 de octubre). Hogares peruanos con varios integrantes recuperan gasto en consumo masivo. https://www.kantar.com/latin-america/inspiracion/consumo-masivo/2025/crecimiento-consumo-masivo-2025-peru

# Anexos
