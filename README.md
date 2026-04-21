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

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
|1.0      |09/04/26| Anjali Amaro | Organización inicial del informe |


<hr class="page-break">

# Project Report Collaboration Insights

Enlace para acceder al repositorio del reporte del proyecto: [*Ver en GitHub*](https://github.com/FlowState-Tech/smartcart-report)

**GitHub Collaboration Insights**

En GitHub se presenta un timeline de las principales ramas creadas por cada integrante del equipo, así como los procesos de _merge_ realizados.
Todas las ramas fueron gestionadas siguiendo el flujo de trabajo GitFlow, adaptado para una organización que utiliza un sistema de control de versiones.

Los integrantes son: 

| Integrante                      | Usuario GitHub       |
|---------------------------------|----------------------|
| Amaro Villar, Anjali	          | njlmrvllr            | 
| Chavez Viera, Joseph Manuel     | u202314019-MrOsoPanda|
| Mejia Aliaga, Katherine Maryory | KathMJ               |
| Pardo Chumpitazi, Kevin Patrick	| Kevinyin11           |
| Valdivia Quispe, Stephano Renan	| steph-ano            |

Las principales ramas del repositorio son las siguientes:




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
        - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
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
    - [Conclusiones](#conclusiones)
        - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Bibliografía](#bibliografía)
    - [Anexos](#anexos)

<hr class="page-break">

# Student Outcome

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7


<hr class="page-break">

# Objetivos SMART


<hr class="page-break">

# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup


La startup FlowState Tech es un equipo conformado por estudiantes de la carrera de Ingeniería de Software. Se tiene como objetivo principal desarrollar herramientas tecnológicas prácticas que ayuden a las familias de Lima a gestionar mejor sus gastos diarios frente al alza de precios. Mediante la aplicación **SmartCart** se busca facilitar la comparación de precios en tiempo real y la creación de rutas de compra eficientes, permitiendo que los usuarios ahorren dinero y tiempo en su compras cotidianas.

**Misión:** Ayudar a las familias limeñas a optimizar su presupuesto mensual mediante una aplicación móvil que simplifique la búsqueda de los mejores precios y las rutas de compra más rápidas.

**Visión:** Ser la plataforma de referencia para el ahorro inteligente en el Perú, destacando por nuestra facilidad de uso y por el impacto directo y positivo en la economía de nuestros usuarios.

### 1.1.2. Perfiles de los integrantes del equipo

| Foto | Nombres y Apellidos | Código deEstudiante | Carrera | Resumen de Conocimientos y Habilidades |
| --- | --- | --- | --- | --- |
|     |     |     |     |     | 
|     |     |     |     |     | 
|     |     |     |     |     | 
|     |     |     |     |     | 
|     |     |     |     |     | 

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

#### What? (¿Qué?)

#### ¿Cuál es el problema?

El problema central es la ineficiencia económica y la pérdida de tiempo que enfrentan las familias en Lima al realizar sus compras de primera necesidad. Esta problemática surge debido a la alta dispersión de precios entre supermercados y mercados tradicionales, sumada a la falta de herramientas que permitan calcular una ruta de compra optimizada que combine múltiples establecimientos para obtener el menor costo total por una canasta completa.

Esta ineficiencia se ve respaldada por investigaciones que identifican la dispersión de precios como una falla de mercado crítica en el sector minorista peruano, donde productos idénticos presentan variaciones de costo significativas dependiendo del canal de venta y la ubicación geográfica del establecimiento (Banco Central de Reserva del Perú [BCRP], 2025). A esta situación se suma la ineficiencia en la movilidad del consumidor, quien al no contar con una secuencia organizada de visitas a los establecimientos, incurre en gastos innecesarios de transporte y una pérdida de tiempo considerable (ResearchGate, 2024). Esta desinformación logística impide que las familias logren un beneficio neto real, ya que el ahorro obtenido en los productos suele verse anulado por los costos de traslado dentro de la compleja red vial de la capital. De esta manera, la falta de transparencia informativa agrava el impacto de la inflación acumulada en el rubro de alimentos básicos, perjudicando la estabilidad económica de los hogares limeños (Instituto Nacional de Estadística e Informática [INEI], 2026).

#### When? (¿Cuándo?)

#### ¿Cuándo ocurre el problema?

El problema se manifiesta de forma recurrente durante la planificación y ejecución de las compras semanales o quincenales del hogar. Se intensifica en periodos de volatilidad económica, donde los precios de productos básicos fluctúan rápidamente, invalidando la información de días anteriores.

#### Where? (¿Dónde?)

#### ¿Dónde surge el problema?
 
Surge en los hogares de Lima Metropolitana, donde la oferta de canales de venta (bodegas, mercados de abastos y grandes cadenas) es sumamente fragmentada.

#### ¿A dónde se dirige?

Esta propuesta está enfocada en las familias de Lima y los comercios minoristas que buscan modernizar la planificación de sus compras y ventas mediante una herramienta tecnológica sencilla, accesible y adaptada a la realidad económica actual, permitiendo optimizar tanto el ahorro como el tiempo de desplazamiento por la ciudad.

#### Who? (¿Quién?)

#### ¿Quiénes están involucrados? 

**Consumidores:** Jefes de hogar y familias que buscan maximizar su presupuesto.

**Comerciantes:** Dueños de puestos en mercados y administradores de tiendas que necesitan visibilizar sus precios para atraer clientes.

#### ¿Quién lo utilizará?

El producto será utilizado principalmente por personas responsables de las compras del hogar que poseen un smartphone y buscan una solución tecnológica para ahorrar. Asimismo, será usado por comerciantes que deseen gestionar su stock y precios de manera digital.

#### Why? (¿Por qué?)

#### ¿Cuál es la causa del problema?

La causa principal es la asimetría de información. Los consumidores no tienen una forma centralizada de comparar precios en tiempo real de distintos formatos de tienda. A esto se suma el "costo de búsqueda", que es el tiempo y esfuerzo físico necesario para visitar varios locales para comparar precios, lo que usualmente desincentiva el ahorro.

#### How? (¿Cómo?)

#### ¿En qué condiciones los usuarios usarán nuestro producto?

Los consumidores utilizarán el producto inicialmente desde sus hogares para planificar sus presupuestos y consultar las predicciones de ahorro antes de salir de casa, y posteriormente en exteriores para navegar por las rutas de compra optimizadas mediante el sistema de geolocalización en tiempo real de sus dispositivos móviles. Por su parte, los comerciantes emplearán la aplicación directamente en sus puestos de mercado o establecimientos para gestionar de manera ágil el stock y realizar actualizaciones dinámicas de precios, asegurando que la información del ecosistema se mantenga veraz y competitiva mientras gestionan sus ventas diarias y responden a las variaciones del mercado local.

#### ¿Cómo nos conocieron nuestros compradores?

A través de campañas en redes sociales enfocadas en ahorro doméstico, recomendaciones en comunidades universitarias y mediante la visibilidad en las tiendas y mercados locales que ya utilizan la plataforma administrativa.

#### ¿Cómo prefieren nuestros consumidores acceder a nuestro producto?

Prefieren el acceso mediante una aplicación móvil, ya que permite la portabilidad necesaria durante el recorrido de compras y la recepción de alertas de precios en tiempo real.

#### How much? (¿Cuánto?)

#### Estadísticas que sustentan la problemática.

La problemática económica en Lima Metropolitana se ve agravada por una inflación que, según el Instituto Nacional de Estadística e Informática (INEI, 2026), registró un incremento del 2.38% en el Índice de Precios al Consumidor durante marzo de 2026. Esta situación impacta severamente la economía doméstica, considerando que el sueldo mínimo actual resulta insuficiente para cubrir el costo de vida real, donde gran parte del ingreso se diluye rápidamente entre el pago de vivienda y la adquisición de alimentos básicos (Infobae, 2025). Asimismo, la actual Remuneración Mínima Vital de S/ 1,130 enfrenta un escenario donde el gasto promedio mensual para cubrir una canasta básica familiar ya supera significativamente los ingresos percibidos por los trabajadores (Banco Central de Reserva del Perú [BCRP], 2025). Ante este panorama, el 41% de los responsables de las compras en el hogar prioriza la búsqueda de ofertas y el ahorro como su principal estrategia de consumo (Kantar Worldpanel, 2025). Finalmente, la falta de una planificación logística adecuada en los recorridos de compra genera ineficiencias que provocan sobrecostos innecesarios de hasta un 20% en transporte y tiempo de desplazamiento (ResearchGate, 2024).

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

#### Segmento 2: Comerciantes Minoristas 

#### A. Perfil y Ocupación

¿Cuántos años tiene y desde hace cuánto tiempo gestiona su negocio?

¿Cómo describiría su nivel de habilidad con herramientas digitales y aplicaciones móviles?

¿Qué lo motiva a mantener su negocio competitivo frente a las grandes cadenas de supermercados?

#### B. Operación y Frustraciones

¿Cuál es el mayor desafío que enfrenta al momento de fijar los precios de sus productos diariamente?

¿Siente que la falta de visibilidad de sus precios en internet le hace perder clientes frente a los supermercados?

¿Qué marcas o proveedores son sus principales aliados y cuáles influyen más en su inventario?

#### C. Entorno Tecnológico

¿Cuenta con un dispositivo móvil propio en su puesto? ¿Qué modelo y navegador (browser) suele utilizar para buscar información?

¿Utiliza actualmente alguna plataforma digital para atraer clientes o prefiere los métodos tradicionales?

#### D. Objetivos y Antecedentes

¿Cuál es su meta principal para su negocio en los próximos 2 años?

¿En qué condiciones estaría dispuesto a dedicar 5 minutos al día para actualizar sus precios en una plataforma digital?

### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. Ubiquitous Language

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
