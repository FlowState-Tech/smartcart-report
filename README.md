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
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams

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
