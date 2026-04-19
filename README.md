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
| Competidor | Modelo de Negocio | Diferenciador de SmartCart (Nuestra Ventaja) | Debilidad Crítica del Competidor |
| :--- | :--- | :--- | :--- |
| **Apps de Delivery** (Rappi, PedidosYa, Fazil) | Venta de conveniencia y rapidez con recargo. | **Precio Real vs. Precio App:** Mostramos el precio de góndola. Ahorramos al usuario el 15-20% de sobrecosto por "service fee". | Precios inflados y rutas de entrega ineficientes que no permiten comprar en varios locales a la vez. |
| **Apps de Supermercados** (Agora, Tottus, Metro) | Fidelización y ecosistema cerrado (Tarjetas OH!, Cencosud). | **Neutralidad Multimarca:** Comparamos precios entre competidores. Trazamos rutas que incluyen desde el Tambo de la esquina hasta el Metro del frente. | Jamás sugerirán al usuario que un producto de su lista es más barato en la competencia. |
| **Catálogos Digitales** (Tiendeo, Ofertia) | Agregador de folletos publicitarios (PDFs). | **Canasta Dinámica:** No solo mostramos la oferta; calculamos el total de la lista y optimizamos el camino físico para recogerla. | Información estática. El usuario debe buscar manualmente producto por producto. No hay geolocalización. |
| **Marketplaces / Yape Tienda** | Intermediación de productos masivos. | **Logística de Compra Física:** Nos enfocamos en el ahorro presencial y la verificación comunitaria (Crowdsourcing). | Enfoque en envío a domicilio. No resuelven la necesidad del usuario que sale a hacer su mercado físicamente. |

---
### 2.1.2. Estrategias y tácticas frente a competidores
Nuestra ventaja competitiva se basa en ser el **"Waze del Ahorro"**: no vendemos productos, vendemos la ruta óptima para obtener el menor precio posible.

#### A. Estrategia de "Ruta de Ahorro Multi-Stop"
* **Táctica:** Algoritmo de optimización de paradas (**TSP**) basado en el inventario real.
* **Descripción:** A diferencia de las apps de supermercados que te encierran en su local, SmartCart divide tu lista de compras. Si la leche está en oferta en *Tottus* pero el arroz es más barato en *Mass*, la app traza la ruta para visitar ambos puntos minimizando el tiempo de desplazamiento.

#### B. Estrategia de "Caza-Promociones" Agresiva
* **Táctica:** Sistema de alertas por proximidad y validación de ofertas "Flash".
* **Descripción:** Aprovechamos las promociones de "Cierre de Día" o "Liquidación". Mediante el **Crowdsourcing**, un usuario puede reportar una oferta local (ej. en Surquillo); el sistema notifica inmediatamente a otros usuarios cuya ruta pase por esa zona.

#### C. Estrategia de Transparencia de Costos
* **Táctica:** Comparador de "Costo Total de Canasta".
* **Descripción:** Al finalizar la lista, SmartCart muestra tres escenarios:
    1.  Costo comprando todo en la tienda más cercana.
    2.  Costo por Delivery (incluyendo tasas ocultas).
    3.  **Costo con Smart-Ruta (Ahorro Máximo).**

#### D. Táctica de Captación de Comercios de Proximidad
* **Táctica:** Integración de tiendas de conveniencia (Tambo, Oxxo) y bodegas.
* **Descripción:** Damos visibilidad a tiendas pequeñas cuando tienen promociones que superan a los grandes supermercados (ej. 2x1 en bebidas). Esto genera un tráfico de clientes que el comercio agradece y el usuario valora.

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
| ID | Título | Descripción | Criterios de Aceptación (Escenarios BDD) | Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
| **EP01** | **Gestión de Identidad** | Registro y validación legal de usuarios y comercios. | N/A | N/A |
| **US01** | Registro de Usuario | Como usuario, quiero crear una cuenta para guardar mis preferencias. | **Escenario 1:** Dado que el usuario está en la página de registro, cuando ingresa un correo válido y una contraseña segura, entonces el sistema crea la cuenta y envía un correo de verificación. <br><br> **Escenario 2:** Dado que el usuario intenta registrarse, cuando ingresa un correo ya existente, entonces el sistema muestra un mensaje de error. | EP01 |
| **US02** | Perfil de Comerciante | Como comerciante, quiero registrar mi local con datos fiscales. | **Escenario 1:** Dado que el comerciante ha iniciado sesión, cuando completa el formulario con nombre comercial y RUC, entonces el perfil se guarda como pendiente. <br><br> **Escenario 2:** Dado que el comerciante ingresa su RUC, cuando el formato no tiene 11 dígitos, entonces el sistema bloquea el envío. | EP01 |
| **US03** | Validación API SUNAT | Como sistema, quiero validar el RUC con la API de SUNAT. | **Escenario 1:** Dado que se ha ingresado un RUC, cuando la API responde como "Activo", entonces el estado cambia a "Tienda Registrada". <br><br> **Escenario 2:** Dado que la API detecta un RUC no habido, cuando se intenta finalizar, entonces el sistema rechaza la solicitud. | EP01 |
| **US04** | Verificación de Identidad | Como administrador, quiero validar la identidad del comerciante. | **Escenario 1:** Dado que un comerciante subió documentos, cuando el admin los aprueba, entonces el perfil muestra el check de "Verificado". <br><br> **Escenario 2:** Dado que los datos no coinciden, cuando el admin rechaza, entonces el sistema notifica el motivo. | EP01 |
| **US05** | Solicitud de Afiliación | Como sistema, quiero emitir un comprobante de solicitud recibida. | **Escenario 1:** Dado que el comerciante envió su registro, cuando el sistema procesa, entonces muestra un mensaje de "Solicitud Recibida". <br><br> **Escenario 2:** Dado que se recibió la solicitud, cuando se guarda, entonces se envía un comprobante PDF por correo. | EP01 |
| **US06** | Comercio Vinculado | Como comerciante, quiero vincular múltiples sucursales. | **Escenario 1:** Dado que el comerciante tiene cuenta principal, cuando agrega nueva dirección, entonces aparece como sucursal en el mapa. <br><br> **Escenario 2:** Dado que intenta agregar sede sin GPS, cuando intenta guardar, entonces el sistema solicita marcar ubicación. | EP01 |
| **EP02** | **Gestión de Inventario** | Control de productos, stock y precios por el comerciante. | N/A | N/A |
| **US07** | Registro de Producto | Como comerciante, quiero añadir productos al catálogo. | **Escenario 1:** Dado que el comerciante está en inventario, cuando completa datos y foto, entonces el producto se añade al catálogo. <br><br> **Escenario 2:** Dado que intenta guardar, cuando el campo "Nombre" está vacío, entonces el sistema resalta el error. | EP02 |
| **US08** | Carga de Inventario Inicial | Como comerciante, quiero cargar mi stock masivamente. | **Escenario 1:** Dado que el comerciante sube un Excel/CSV, cuando el sistema valida formato, entonces se marca como "Inventario Cargado". <br><br> **Escenario 2:** Dado que el archivo tiene errores de formato, cuando se procesa, entonces muestra lista de errores por fila. | EP02 |
| **US09** | Actualización de Precios | Como comerciante, quiero cambiar precios de forma inmediata. | **Escenario 1:** Dado que un producto existe, cuando el comerciante edita y guarda, entonces el cambio se refleja instantáneamente. <br><br> **Escenario 2:** Dado que se actualiza el precio, cuando se guarda, entonces el sistema registra fecha y hora para analítica. | EP02 |
| **US10** | Reporte de Falta de Stock | Como comerciante, quiero marcar productos como agotados. | **Escenario 1:** Dado que un producto se terminó, cuando el comerciante marca "Sin stock", entonces la app oculta el producto. <br><br> **Escenario 2:** Dado que un usuario lo tenía en lista, cuando se marca agotado, entonces el usuario recibe una notificación. | EP02 |
| **US11** | Oferta Relámpago | Como comerciante, quiero crear ofertas temporales. | **Escenario 1:** Dado que el comerciante elige producto y descuento, cuando define duración, entonces aparece un cronómetro en la app del cliente. <br><br> **Escenario 2:** Dado que el tiempo expiró, cuando llega a cero, entonces el precio vuelve a su valor original. | EP02 |
| **EP03** | **Planificación y Canasta** | Herramientas para que el consumidor organice su gasto. | N/A | N/A |
| **US12** | Lista de Compras | Como consumidor, quiero agregar ítems a una lista de deseos. | **Escenario 1:** Dado que el usuario busca un ítem, cuando presiona "+", entonces se añade a su lista personal. <br><br> **Escenario 2:** Dado que el usuario tiene un producto en lista, cuando desliza a la izquierda, entonces el sistema lo elimina. | EP03 |
| **US13** | Configuración de Canasta | Como consumidor, quiero marcar ítems como esenciales. | **Escenario 1:** Dado que el usuario tiene su lista, cuando selecciona productos recurrentes, entonces se guarda como "Canasta básica". <br><br> **Escenario 2:** Dado que está configurada, cuando el usuario cierra la app, entonces la configuración persiste. | EP03 |
| **US14** | Presupuesto Máximo | Como consumidor, quiero establecer un tope de gasto. | **Escenario 1:** Dado que el presupuesto es S/ 200, cuando el total llega a S/ 210, entonces la barra de presupuesto se torna roja. <br><br> **Escenario 2:** Dado que agrega productos, cuando consulta lista, entonces el sistema muestra el margen de dinero sobrante. | EP03 |
| **US15** | Ubicación de Hogar | Como consumidor, quiero guardar mi dirección principal. | **Escenario 1:** Dado que el usuario está en ajustes, cuando ingresa calle y distrito, entonces el sistema valida y guarda ubicación. <br><br> **Escenario 2:** Dado que el usuario cambia de casa, cuando edita ubicación, entonces las rutas se recalculan desde el nuevo punto. | EP03 |
| **US16** | Adición a Canasta | Como consumidor, quiero mover ítems de la lista a la canasta. | **Escenario 1:** Dado que el usuario está en tienda, cuando marca ítem como "comprado", entonces se mueve de "Pendiente" a "En Canasta". <br><br> **Escenario 2:** Dado que se añade un producto, cuando cambia estado, entonces el total acumulado se de la compra actual se actualiza. | EP03 |
| **EP04** | **Motor de Comparación** | Algoritmos para encontrar el mejor precio y ahorro. | N/A | N/A |
| **US17** | Filtrado por Precio | Como consumidor, quiero ordenar productos por costo. | **Escenario 1:** Dado que el usuario ve resultados, cuando selecciona "Menor precio", entonces se reordena la lista de más barato a caro. <br><br> **Escenario 2:** Dado que hay muchos resultados, cuando selecciona una marca, entonces el sistema oculta los demás. | EP04 |
| **US18** | Sugerencia de Sustitutos | Como sistema, quiero proponer marcas más baratas. | **Escenario 1:** Dado que agregó una marca premium, cuando existe una opción más económica, entonces aparece un banner de sugerencia. <br><br> **Escenario 2:** Dado que aparece la sugerencia, cuando el usuario hace clic en "Cambiar", entonces se reemplaza el ítem. | EP04 |
| **US19** | Comparación de Canastas | Como consumidor, quiero comparar mi lista en tiendas. | **Escenario 1:** Dado que la lista está completa, cuando pulsa "Comparar", entonces se muestra tabla de costo total en Tienda A, B y C. <br><br> **Escenario 2:** Dado que se comparan precios, cuando una tienda es la más barata, entonces se resalta con medalla. | EP04 |
| **US20** | Sugerencia "En Combo" | Como sistema, quiero sugerir compras conjuntas. | **Escenario 1:** Dado que lleva 2 tarros de leche, cuando hay oferta 3x2, entonces el sistema sugiere agregar uno más para ahorrar. <br><br> **Escenario 2:** Dado que compra café, cuando hay oferta en azúcar, entonces sugiere el combo para maximizar ahorro. | EP04 |
| **US21** | Pronóstico de Ahorro | Como sistema, quiero calcular el ahorro mensual. | **Escenario 1:** Dado que finalizó compras, cuando termina el mes, entonces el sistema genera gráfico de gasto real vs. optimizado. <br><br> **Escenario 2:** Dado que usa la app, cuando alcanza S/ 50 de ahorro, entonces recibe una insignia de "Ahorrador Estrella". | EP04 |
| **US22** | Costo Total Proyectado | Como consumidor, quiero ver el monto final antes de salir. | **Escenario 1:** Dado que tiene su ruta lista, cuando consulta resumen, entonces el sistema muestra total incluyendo movilidad estimada. <br><br> **Escenario 2:** Dado que incluye IGV, cuando se suma total, entonces el sistema muestra el desglose de base e impuesto. | EP04 |
| **EP05** | **Logística y Geocalización** | Integración con mapas y rutas eficientes. | Uso de Google Maps. | N/A |
| **US23** | Búsqueda de Ruta | Como consumidor, quiero solicitar la ruta más rápida. | **Escenario 1:** Dado que seleccionó 3 tiendas, cuando pulsa "Optimizar", entonces el sistema ordena paradas para minimizar tiempo. <br><br> **Escenario 2:** Dado que no hay tiendas abiertas, cuando busca ruta, entonces muestra mensaje de locales no disponibles. | EP05 |
| **US24** | Integración Google Maps | Como sistema, quiero conectar con Google Maps Platform. | **Escenario 1:** Dado que la ruta está trazada, cuando inicia navegación, entonces el mapa muestra tráfico en tiempo real. <br><br> **Escenario 2:** Dado que hay fallo de red, cuando intenta cargar mapa, entonces se muestra un mapa estático de respaldo. | EP05 |
| **US25** | Punto de Compra Óptimo | Como sistema, quiero hallar la tienda ideal según la ruta. | **Escenario 1:** Dado que existen 2 tiendas, cuando una ofrece ahorro > 10%, entonces se marca como "Punto óptimo". <br><br> **Escenario 2:** Dado que prioriza tiempo, cuando busca ruta, entonces el sistema elige la tienda más cercana. | EP05 |
| **US26** | Confirmación de Parada | Como consumidor, quiero marcar que llegué a una tienda. | **Escenario 1:** Dado que el usuario está frente al local, cuando presiona "Llegué", entonces el estado cambia a "Parada confirmada". <br><br> **Escenario 2:** Dado que decide no entrar, cuando presiona "Omitir", entonces el sistema recalcula el tiempo restante. | EP05 |
| **US27** | Verificación por GPS | Como sistema, quiero validar la visita mediante geofencing. | **Escenario 1:** Dado que entra en radio de 20m, cuando permanece 2 min, entonces el evento "Visita Confirmada" se dispara. <br><br> **Escenario 2:** Dado que el GPS está apagado, cuando intenta verificar, entonces solicita activar permisos de ubicación. | EP05 |
| **US28** | Finalización de Ruta | Como consumidor, quiero cerrar el recorrido de compras. | **Escenario 1:** Dado que visitó todas las tiendas, cuando pulsa "Finalizar", entonces muestra resumen de ahorro y tiempo. <br><br> **Escenario 2:** Dado que faltan paradas, cuando intenta finalizar, entonces el sistema pregunta si desea guardar progreso. | EP05 |
| **EP06** | **Crowdsourcing** | Control de veracidad de datos por parte de usuarios. | Validación cruzada. | N/A |
| **US29** | Validación de Precio | Como consumidor, quiero confirmar que el precio es real. | **Escenario 1:** Dado que ve precio correcto, cuando presiona check, entonces aumenta el contador de confianza. <br><br> **Escenario 2:** Dado que valida 5 precios, cuando termina, entonces el sistema otorga puntos de reputación. | EP06 |
| **US30** | Reporte de Error | Como consumidor, quiero denunciar precio incorrecto. | **Escenario 1:** Dado que el precio en app difiere de tienda, cuando reporta, entonces el sistema marca precio como "En disputa". <br><br> **Escenario 2:** Dado que reporta error, cuando adjunta foto de góndola, entonces el reporte adquiere prioridad alta. | EP06 |
| **US31** | Detección de Discrepancia | Como sistema, quiero alertar si un precio varía mucho. | **Escenario 1:** Dado que 3 usuarios reportan precios distintos, cuando se detecta, entonces lanza alerta de discrepancia. <br><br> **Escenario 2:** Dado que hay discrepancia alta, cuando procesa, entonces oculta el precio hasta que el comercio valide. | EP06 |
| **US32** | Veracidad Confirmada | Como sistema, quiero dar prioridad a precios validados. | **Escenario 1:** Dado que tiene > 10 validaciones hoy, cuando un usuario busca, entonces aparece sello de "Veracidad Confirmada". <br><br> **Escenario 2:** Dado que pasaron 24h sin validaciones, cuando actualiza, entonces retira el sello de veracidad. | EP06 |
| **US33** | Alerta de Oferta | Como sistema, quiero avisar si se valida una oferta. | **Escenario 1:** Dado que valida "Oferta Relámpago", cuando confirma stock, entonces envía alerta PUSH a usuarios interesados. <br><br> **Escenario 2:** Dado que se activa, cuando envía alerta, entonces solo la reciben usuarios en un radio de 5km. | EP06 |
| **US34** | Notificación Cercanía | Como consumidor, quiero alertas de ofertas al pasar cerca. | **Escenario 1:** Dado que camina por una zona, cuando está a 100m de oferta en su lista, entonces recibe notificación "Oferta cerca". <br><br> **Escenario 2:** Dado que tiene batería baja, cuando rastrea, entonces disminuye la frecuencia de escaneo GPS. | EP06 |
| **EP07** | **Reputación y Gamificación** | Calificación de establecimientos y confianza. | Feedback social. | N/A |
| **US35** | Reseña de Tienda | Como consumidor, quiero escribir mi experiencia. | **Escenario 1:** Dado que finalizó compra, cuando redacta y envía, entonces se muestra "Reseña de Tienda Publicada". <br><br> **Escenario 2:** Dado que escribe ofensas, cuando intenta publicar, entonces el sistema bloquea y pide corregir. | EP07 |
| **US36** | Reseña de Servicio | Como consumidor, quiero calificar la atención. | **Escenario 1:** Dado que fue atendido, cuando califica amabilidad, entonces se guarda en perfil del comercio. <br><br> **Escenario 2:** Dado que marca "Anónimo", cuando publica, entonces el sistema oculta su nombre. | EP07 |
| **US37** | Calificación (Estrellas) | Como consumidor, quiero asignar estrellas (1-5). | **Escenario 1:** Dado que asigna 4 estrellas, cuando confirma, entonces se recalcula el puntaje general del comercio. <br><br> **Escenario 2:** Dado que finalizó ruta, cuando intenta salir, entonces aparece popup pidiendo calificar. | EP07 |
| **US38** | Insignias a Tiendas | Como sistema, quiero premiar tiendas con precios reales. | **Escenario 1:** Dado que mantuvo precios veraces 30 días, cuando hace el corte, entonces otorga "Insignia de confianza". <br><br> **Escenario 2:** Dado que recibe 3 reportes validados, cuando procesa, entonces retira automáticamente la insignia. | EP07 |
| **US39** | Actualización Reputación | Como sistema, quiero recalcular puntajes. | **Escenario 1:** Dado que valida muchos precios, cuando llega a 1000 pts, entonces el perfil cambia a "Reputación Alta". <br><br> **Escenario 2:** Dado que publica ofertas falsas, cuando se confirma fraude, entonces el puntaje del comercio baja drásticamente. | EP07 |
| **EP08** | **Métricas de Negocio** | Análisis de datos para Startup y Comercio. | Dashboards. | N/A |
| **US40** | Meta de Venta | Como comerciante, quiero recibir alertas si llego a mi meta. | **Escenario 1:** Dado que definió meta S/ 1000, cuando ventas llegan al monto, entonces recibe alerta de éxito. <br><br> **Escenario 2:** Dado que es mediodía, cuando abre panel, entonces muestra barra de porcentaje hacia la meta. | EP08 |
| **US41** | Tráfico Mensual | Como comerciante, quiero ver visitas a mi perfil. | **Escenario 1:** Dado que terminó el mes, cuando accede a analítica, entonces genera reporte con gráficos de visitas. <br><br> **Escenario 2:** Dado que genera reporte, cuando pulsa comparar, entonces muestra si subió o bajó respecto al mes previo. | EP08 |
| **US42** | Métrica Venta Perdida | Como comerciante, quiero saber qué buscan y no tengo. | **Escenario 1:** Dado que muchos buscan un producto sin stock, cuando revisa métricas, entonces registra "Venta Perdida". <br><br> **Escenario 2:** Dado ventas perdidas recurrentes, cuando inicia sesión, entonces sugiere añadir dicho producto al stock. | EP08 |
| **US43** | Pérdida Desactualización | Como sistema, quiero informar si pierde clientes por precios viejos. | **Escenario 1:** Dado que usuario cambió de tienda tras ver precio viejo, cuando detecta patrón, entonces notifica al dueño. <br><br> **Escenario 2:** Dado que detectó pérdida, cuando abre alerta, entonces estima dinero dejado de ganar. | EP08 |
| **US44** | Dashboard Ahorro Total | Como admin, quiero ver el ahorro de la comunidad. | **Escenario 1:** Dado que hay 1000 usuarios, cuando entra a dashboard, entonces visualiza suma total de soles ahorrados. <br><br> **Escenario 2:** Dado datos geolocalizados, cuando filtra por zona, entonces muestra qué distrito ahorra más. | EP08 |
| **TS01** | API Gateway & Auth | Centralizar peticiones mediante Gateway con JWT. | **E1:** Genera Access Token tras login válido. <br> **E2:** Retorna 401 si el token es inválido o expiró. | EP01 |
| **TS02** | Sync Datos Offline | Implementar SQLite/Room para funcionamiento sin red. | **E1:** Persiste canasta localmente si se pierde red. <br> **E2:** Sincroniza con servidor al recuperar internet. | EP03 |
| **TS03** | Integración SUNAT | Conectar registro de comercios con padrón SUNAT. | **E1:** Retorna Razón Social y Estado al enviar RUC. <br> **E2:** Implementa Retry Pattern si el servicio falla. | EP01 |
| **TS04** | Algoritmo TSP | Lógica de optimización de rutas (Traveling Salesman). | **E1:** Retorna secuencia que minimiza tiempo de viaje. <br> **E2:** Prioriza locales que cierran pronto en la ruta. | EP05 |
| **TS05** | SDK Maps & Geofencing | Usar SDK para detectar entrada a locales. | **E1:** Dispara evento al entrar en radio de 30m. <br> **E2:** Reduce frecuencia de tracking si no hay ruta activa. | EP05 |
| **TS06** | Notificaciones FCM | Configurar Firebase para alertas push. | **E1:** Envía mensaje PUSH ante validación de oferta. <br> **E2:** Suscribe usuarios a tópicos por distrito (ej. Surquillo). | EP06 |
| **TS07** | Módulo de Venta Perdida | Logs para capturar demandas no satisfechas. | **E1:** Envía evento de log al buscar producto sin stock. <br> **E2:** Muestra suma de clientes perdidos en dashboard. | EP08 |
| **TS08** | Almacenamiento Imágenes | Servicio S3/Cloudinary para fotos de productos. | **E1:** Comprime y retorna URL pública tras subida. <br> **E2:** Retorna error 415 si el formato no es soportado. | EP02 |
| **TS09** | Motor Cálculo Ahorro | Implementar motor comparativo de canastas. | **E1:** Calcula beneficio neto al cerrar la compra. <br> **E2:** Proyecta ahorro potencial mensual en el perfil. | EP04 |
| **TS10** | Lógica de Gamificación | Sistema de puntajes para validadores. | **E1:** Incrementa puntaje al confirmar validación. <br> **E2:** Baja el score si detecta reportes falsos repetidos. | EP07 |
---
### 2.4.2. Impact Mapping

### 2.4.3. Product Backlog
| Epic/US/TS ID | Título | Descripción | Criterios de Aceptación (Escenarios BDD) | Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
| **US01** | Registro de Usuario | Como usuario, quiero crear una cuenta para guardar mis preferencias. | **E1:** Dado datos válidos, cuando el usuario se registra, entonces accede al feed de ofertas locales. <br> **E2:** Dado un email duplicado, cuando intenta registrarse, entonces el sistema muestra un mensaje de error. | EP01 |
| **US03** | Validación API SUNAT | Como sistema, quiero validar el RUC con la API de SUNAT. | **E1:** Dado un RUC ingresado, cuando la API responde como "Activo", entonces la tienda se marca como registrada. <br> **E2:** Dado un RUC inválido, cuando se consulta, entonces el sistema rechaza la afiliación. | EP01 |
| **TS01** | API Gateway & JWT | Como desarrollador, quiero centralizar las peticiones mediante un Gateway. | **E1:** Dado login correcto, cuando solicita acceso, entonces recibe un token JWT seguro. <br> **E2:** Dado token expirado, cuando llama al API, entonces recibe error 401. | EP01 |
| **US07** | Registro de Producto | Como comerciante, quiero añadir productos al catálogo. | **E1:** Dado el panel de inventario, cuando completa nombre y categoría, entonces el producto se añade al catálogo global. <br> **E2:** Dado falta de datos, cuando intenta guardar, entonces el sistema resalta el error en rojo. | EP02 |
| **US09** | Actualización de Precios | Como comerciante, quiero cambiar precios de forma inmediata. | **E1:** Dado que edita un precio, cuando guarda el cambio, entonces se refleja instantáneamente para los consumidores. <br> **E2:** Dado que se actualiza, cuando guarda, entonces se registra la fecha/hora para analítica. | EP02 |
| **US11** | Oferta Relámpago | Como comerciante, quiero crear ofertas temporales. | **E1:** Dado un descuento definido, cuando activa la oferta por 2 horas, entonces aparece un cronómetro en la app del cliente. <br> **E2:** Dado tiempo agotado, cuando llega a cero, entonces el precio vuelve a la normalidad. | EP02 |
| **US12** | Lista de Compras | Como consumidor, quiero agregar ítems a una lista de deseos. | **E1:** Dado el buscador de productos, cuando presiona el botón "+", entonces el ítem se añade a su lista personal. <br> **E2:** Dado un ítem en lista, cuando desliza a la izquierda, entonces el sistema elimina el ítem. | EP03 |
| **US14** | Presupuesto Máximo | Como consumidor, quiero establecer un tope de gasto. | **E1:** Dado un tope de S/ 200, cuando el total llega a S/ 210, entonces la barra de presupuesto se torna roja. <br> **E2:** Dado que agrega productos, cuando consulta, entonces ve cuánto dinero le sobra del presupuesto. | EP03 |
| **TS02** | Sync Offline (Room) | Como desarrollador, quiero implementar una base de datos local. | **E1:** Dado falta de internet, cuando el usuario agrega productos, entonces se guardan en el almacenamiento local. <br> **E2:** Dado que recupera red, cuando abre la app, entonces sincroniza datos con el servidor. | EP03 |
| **US19** | Comparación de Canastas | Como consumidor, quiero comparar mi lista en tiendas. | **E1:** Dado la lista completa, cuando pulsa "Comparar", entonces se muestra una tabla con el costo total en la Tienda A, B y C. <br> **E2:** Dado que se comparan, cuando una es la más barata, entonces el sistema la resalta con una medalla. | EP04 |
| **US22** | Costo Total Proyectado | Como consumidor, quiero ver el monto final antes de salir. | **E1:** Dado la ruta lista, cuando consulta el resumen, entonces ve el total incluyendo una estimación de movilidad. <br> **E2:** Dado precios con IGV, cuando suma el total, entonces ve el desglose del costo base y el impuesto. | EP04 |
| **TS04** | Algoritmo TSP | Como desarrollador, quiero implementar la lógica de ruta óptima. | **E1:** Dado un conjunto de 4 paradas, cuando solicita ruta, entonces retorna el orden que minimiza el tiempo total. <br> **E2:** Dado local cerrado pronto, cuando optimiza, entonces el sistema lo prioriza para visitar primero. | EP05 |
| **US23** | Búsqueda de Ruta | Como consumidor, quiero la ruta más rápida y económica. | **E1:** Dado 3 tiendas seleccionadas, cuando pulsa "Optimizar", entonces el sistema ordena las paradas por tiempo. <br> **E2:** Dado locales cerrados, cuando busca ruta, entonces el sistema indica que no hay locales disponibles ahora. | EP05 |
| **US25** | Punto de Compra Óptimo | Como sistema, quiero hallar la tienda ideal según la ruta. | **E1:** Dado 2 tiendas cercanas, cuando una ahorra > 10%, entonces el sistema la marca como "Punto óptimo". <br> **E2:** Dado prioridad de tiempo, cuando busca ruta, entonces el sistema elige la más cercana aunque no sea la más barata. | EP05 |
| **TS05** | Integración Google Maps | Como desarrollador, quiero usar el SDK de Maps y Geofencing. | **E1:** Dado entrada a local, cuando el GPS detecta radio de 30m, entonces dispara evento "Visita Confirmada". <br> **E2:** Dado app en background, cuando no hay ruta activa, entonces se reduce la frecuencia de rastreo GPS. | EP05 |
| **US29** | Validación de Precio | Como consumidor, quiero confirmar que el precio en tienda es real. | **E1:** Dado precio correcto en góndola, cuando presiona "Verificado", entonces aumenta su reputación de usuario. <br> **E2:** Dado 5 validaciones, cuando termina ruta, entonces el sistema otorga puntos de reputación extra. | EP06 |
| **US30** | Reporte de Error | Como consumidor, quiero denunciar un precio incorrecto. | **E1:** Dado precio en app S/ 5 y en tienda S/ 7, cuando reporta error, entonces el sistema marca el precio como "En disputa". <br> **E2:** Dado reporte con foto, cuando envía, entonces el reporte adquiere prioridad alta para revisión. | EP06 |
| **TS06** | Pipeline PUSH (FCM) | Como desarrollador, quiero configurar Firebase para alertas. | **E1:** Dado oferta validada, cuando el sistema detecta usuarios cerca, entonces envía mensaje PUSH vía FCM. <br> **E2:** Dado nuevo usuario, cuando inicia sesión, entonces se suscribe automáticamente a su distrito en Firebase. | EP06 |
| **US39** | Actualización de Reputación | Como sistema, quiero recalcular el puntaje de los actores. | **E1:** Dado que valida muchos precios, cuando llega a 1000 puntos, entonces su perfil sube a "Reputación Alta". <br> **E2:** Dado ofertas falsas del comercio, cuando se confirma fraude, entonces su puntaje de reputación baja. | EP07 |
| **US42** | Métrica de Venta Perdida | Como comerciante, quiero saber qué productos buscan y no tengo. | **E1:** Dado búsquedas sin stock cerca del local, cuando revisa métricas, entonces el sistema registra la venta perdida. <br> **E2:** Dado ventas perdidas recurrentes, cuando inicia sesión, entonces sugiere añadir ese producto al stock. | EP08 |

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
