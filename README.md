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

| Criterio específico                                                                                                                                                                 | Acciones realizadas | Conclusiones |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------ |
| **Actualiza conceptos y**<br> **conocimientos necesarios**<br> **para su desarrollo**<br> **profesional y en especial**<br> **para su proyecto en**<br> **soluciones de software.** |                     |              |
| **Reconoce la necesidad del**<br> **aprendizaje permanente**<br> **para el desempeño**<br> **profesional y el desarrollo de**<br> **proyectos en soluciones de**<br> **software.**  |                     |              |

<hr class="page-break">

# Objetivos SMART

A continuación, cada miembro del equipo expone sus objetivos SMART, orientados a su desarrollo profesional tras finalizar la carrera universitaria.

**Integrante 1: Anjali Amaro**  
**Objetivo 1:**
**Objetivo 2:**

**Integrante 2: Joseph Chavez**  
**Objetivo 1:**
**Objetivo 2:**

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
|      | Joseph Manuel Chavez Viera     |      U202314019      | Ingeniería de Software |                                        |
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
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

---
<hr class="page-break">

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

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
|              Atributo               | Detalle                       |
| :---------------------------------: | :---------------------------- |
|               Nombre                |                               |
|                Edad                 |                               |
|              Distrito               |                               |
|              Ocupación              |                               |
|         Fecha de entrevista         |                               |
|               Timing                |                               |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]() |
| Captura de pantalla de la grabación | ![]()                         |
|               Resumen               |                               |

#### Segmento de Comerciantes: 

#### Entrevista 1:
|              Atributo               | Detalle                       |
| :---------------------------------: | :---------------------------- |
|               Nombre                |                               |
|                Edad                 |                               |
|              Distrito               |                               |
|              Ocupación              |                               |
|         Fecha de entrevista         |                               |
|               Timing                |                               |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]() |
| Captura de pantalla de la grabación | ![]()                         |
|               Resumen               |                               |

#### Entrevista 2:
|              Atributo               | Detalle                       |
| :---------------------------------: | :---------------------------- |
|               Nombre                |                               |
|                Edad                 |                               |
|              Distrito               |                               |
|              Ocupación              |                               |
|         Fecha de entrevista         | 15 de abril del 2026          |
|               Timing                |                               |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]() |
| Captura de pantalla de la grabación | ![]()                         |
|               Resumen               |                               |

#### Entrevista 3:
|              Atributo               | Detalle                       |
| :---------------------------------: | :---------------------------- |
|               Nombre                |                               |
|                Edad                 |                               |
|              Distrito               |                               |
|              Ocupación              |                               |
|         Fecha de entrevista         |                               |
|               Timing                |                               |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]() |
| Captura de pantalla de la grabación | ![]()                         |
|               Resumen               |                               |


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
**Distritos:** San Borja, Surco y Villa El Salvador  

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
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
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
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams

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
#### 2.6.3.1. Domain Layer
#### 2.6.3.2. Interface Layer
#### 2.6.3.3. Application Layer
#### 2.6.3.4. Infrastructure Layer
#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.3.6.2. Bounded Context Database Design Diagram

### 2.6.4. Bounded Context: Notification
#### 2.6.4.1. Domain Layer
#### 2.6.4.2. Interface Layer
#### 2.6.4.3. Application Layer
#### 2.6.4.4. Infrastructure Layer
#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.4.6.2. Bounded Context Database Design Diagram

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

# Anexos
