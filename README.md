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
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. Ubiquitous Language
### 2.3.5. Ubiquitous Language

Esta sección establece el **Ubiquitous Language** (Lenguaje Ubicuo) de la plataforma **SmartCart**, unificando el vocabulario entre el equipo técnico y los expertos de negocio para evitar ambigüedades en el desarrollo del sistema. Este glosario se deriva directamente de las responsabilidades y procesos definidos en los contextos estratégicos de la solución, permitiendo que todos los involucrados compartan una visión clara del dominio.

* **Activación**: Proceso de verificación requerido para habilitar formalmente la cuenta de un usuario en el sistema.
* **Alerta de oferta**: Notificación enviada al consumidor cuando se detecta una reducción de precio en un producto de su interés.
* **AnalyticsReport**: Conjunto de métricas de ventas y comportamiento de tráfico generado para cada tienda.
* **Ahorro total**: Diferencia calculada entre el precio de referencia del mercado y el monto real pagado por el consumidor.
* **Calificación**: Puntuación numérica y comentario breve otorgado por el consumidor a un establecimiento visitado.
* **Canal**: Medio técnico (notificación push o correo electrónico) utilizado para la entrega de alertas.
* **Canasta**: Agrupación de productos seleccionados cuyos precios y stock son comparados entre múltiples tiendas.
* **Canasta familiar**: Variante de la lista de compras que puede ser compartida y editada por un grupo familiar específico.
* **Confirmación**: Aviso enviado al usuario tras completar con éxito una acción crítica en la plataforma.
* **Credencial**: Datos de autenticación compuestos por el correo electrónico y la contraseña del usuario.
* **Error de precio**: Discrepancia identificada y reportada entre el precio digital de la app y el precio físico en tienda.
* **Inventario**: Catálogo detallado de productos, existencias y precios pertenecientes a una tienda verificada.
* **Lista de compras**: Conjunto organizado de productos que el consumidor planea adquirir en su recorrido.
* **Llegada**: Registro físico del consumidor en las instalaciones de un local dentro de su ruta.
* **Oferta**: Reducción de carácter temporal aplicada al precio regular de un producto.
* **Presupuesto máximo**: Límite de gasto monetario definido por el usuario para su planificación de compra.
* **Punto de parada**: Cada una de las tiendas específicas que integran el itinerario de compra planificado.
* **Rate limiting**: Restricción técnica sobre la frecuencia de mensajes enviados para evitar la saturación del usuario.
* **Recorrido finalizado**: Estado del sistema que indica la conclusión de las visitas y activa la fase de feedback post-compra.
* **Reseña**: Opinión detallada publicada por el usuario sobre su experiencia de servicio y calidad de productos.
* **Rol**: Clasificación de usuario (Consumer o StoreManager) que determina sus permisos y accesos.
* **RUC**: Número de identificación tributaria utilizado para la validación legal de los establecimientos.
* **Ruta óptima**: Itinerario de compra calculado para minimizar distancias y maximizar la disponibilidad de productos.
* **Sesión**: Periodo de tiempo durante el cual un usuario permanece autenticado de forma activa.
* **ShoppingList**: Evento técnico que consolida los productos y activa el inicio del recorrido de compra.
* **ShoppingRoute**: Entidad de software que almacena el recorrido completo, incluyendo paradas y tiempos estimados.
* **SKU**: Código identificador único asignado a un producto dentro del inventario de una tienda.
* **Solicitud de afiliación**: Pedido formal realizado por una tienda para integrarse a la red de SmartCart.
* **Suscripción**: Preferencia registrada por el usuario para recibir alertas sobre variaciones en productos o tiendas.
* **Tienda**: Local físico que ha sido validado y se encuentra operativo dentro de la plataforma.
* **Tienda verificada**: Estado administrativo que confirma la validez legal y fiscal de un establecimiento.
* **Trust Profile**: Índice de reputación de una tienda construido a partir de las valoraciones de la comunidad.
* **Usuario**: Individuo registrado y autenticado bajo un perfil específico en el sistema.
* **Validación**: Procedimiento de contrastación de datos de la tienda contra fuentes oficiales como Sunat.
## 2.4. Requirements specification
### 2.4.1. User Stories
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
## 2.5.1.1. Candidate Context Discovery

En esta sección se presenta el proceso seguido por el equipo para la descubierta y clasificación de los **Bounded Contexts** candidatos a partir del taller de **EventStorming** realizado previamente. El objetivo es identificar los límites naturales del dominio de SmartCart y determinar las partes core del negocio para priorizar los esfuerzos de diseño.

### Preparación de la sesión
La sesión se desarrolló utilizando como insumos principales:
* La línea de tiempo de eventos y clusters identificados en el mural de **Miro**.
* Los eventos clave (*pivotal events*) que marcan cambios de estado relevantes en el flujo de compra.

### Técnica aplicada: Start-with-Value
Se aplicó la técnica **Start-with-Value**, priorizando las partes del dominio que representan el mayor valor estratégico y diferenciación para la plataforma. Esto permitió categorizar los contextos según su impacto en el negocio y la complejidad de su modelo.

### Candidate Contexts identificados
A partir del análisis del mural de Miro, se identificaron los siguientes bounded contexts candidatos:

| Candidate Context | Eventos Clave Asociados | Clasificación | Descripción | Justificación |
| :--- | :--- | :--- | :--- | :--- |
| **Store Management** | Inventario cargado, Producto registrado, Alcance de precio analizado. | **Core** | Gestión de catálogos, stocks y analítica de precios de las tiendas. | Es el motor de datos del sistema y permite la analítica de precios diferenciadora. |
| **Shopping Journey** | Ruta buscada, Optimización de ruta iniciada, Llegada a local registrada. | **Core** | Ejecución y seguimiento del proceso de compra física en tiempo real. | Constituye la propuesta de valor central: ahorro de tiempo y dinero mediante rutas optimizadas. |
| **Shopping Planning** | Lista de compras creada, Producto añadido a canasta, Presupuesto definido. | **Core** | Fase de planificación y configuración de intenciones de compra del usuario. | Es el punto de entrada crítico donde se capturan las reglas y metas de ahorro del usuario. |
| **Experience** | Error de precio reportado, Calificar tienda, Reseña publicada. | **Supporting** | Sistema de validación comunitaria, reseñas y reputación de establecimientos. | Apoya la veracidad de la información del Core mediante la validación colectiva. |
| **Notification** | Alerta de variación de precio, Alerta de cercanía enviada. | **Supporting** | Gestión de alertas y comunicaciones automáticas con el usuario. | Facilita la interacción y fidelización, pero su complejidad es secundaria frente al motor de rutas. |
| **IAM** | Usuario creado, Sesión iniciada, Usuario activado. | **Generic** | Gestión de identidad, autenticación y roles de usuario (Identity & Access Management). | Es necesario para la operación, pero no es un diferenciador tecnológico del negocio. |
| **Verification** | Solicitud de afiliación enviada, Tienda verificada. | **Generic** | Proceso administrativo de validación legal de los establecimientos afiliados. | Proceso de cumplimiento estándar que no aporta un valor competitivo único al dominio. |

### Clasificación Estratégica
En base al análisis **Start-with-Value**, los contextos se clasifican estratégicamente para concentrar el diseño táctico en las áreas de mayor valor:

* **Core:** Store Management, Shopping Journey, Shopping Planning.
* **Supporting:** Experience, Notification.
* **Generic:** IAM, Verification.
#### 2.5.1.2. Domain Message Flows Modeling
El **Domain Message Flow Modeling** es una técnica colaborativa que busca unificar el conocimiento del negocio y el equipo técnico sobre los flujos de interacción entre **Bounded Contexts**. Su fin es establecer una comprensión compartida de cómo se comunican los diferentes componentes del sistema.

Para la plataforma **SmartCart**, se modelaron las interacciones entre los contextos de IAM, Verification, Store Management, Shopping Planning, Shopping Journey, Experience y Notification. Este proceso permitió clarificar la lógica de negocio y definir con precisión los contratos de comunicación entre cada uno de estos dominios.

#### Escenario 1: Registro y verificación de tienda
**Objetivo:** Una tienda nueva desea registrarse y ser verificada en el sistema SmartCart para comenzar a operar y ser visible para los consumidores.
> ![Diagrama Escenario 1](assets/domain-message-flows/inventory-management.png)

---

#### Escenario 2: Planificación de compra del consumidor
**Objetivo:** Un consumidor desea crear una lista de compras, añadir productos y comparar precios entre distintas tiendas para optimizar su gasto.
> ![Diagrama Escenario 2](assets/domain-message-flows/shopping-planning.png)

---

#### Escenario 3: Ejecución del recorrido de compra
**Objetivo:** El consumidor desea recorrer físicamente las tiendas siguiendo la ruta óptima generada a partir de su lista de compras planificada.
> ![Diagrama Escenario 3](assets/domain-message-flows/shopping-journey.png)

---

#### Escenario 4: Calificación y experiencia post-compra
**Objetivo:** El consumidor desea calificar las tiendas visitadas, verificar la exactitud de precios y publicar una reseña de su experiencia de compra.
> ![Diagrama Escenario 4](assets/domain-message-flows/post-purchase-experience.png)

---

#### Escenario 5: Gestión de inventario y precios de tienda
**Objetivo:** El Store Manager desea actualizar el inventario de productos y los precios de su tienda en tiempo real para que los consumidores siempre accedan a información correcta.
> ![Diagrama Escenario 5](assets/domain-message-flows/inventory-management.png)

---

#### Escenario 6: Cálculo de ahorro y análisis de compra
**Objetivo:** El consumidor desea conocer el ahorro total generado en su recorrido de compra comparado con los precios de referencia, y acceder a un análisis de sus hábitos de consumo.
> ![Diagrama Escenario 6](assets/domain-message-flows/saving-analysis.png)

---

#### Escenario 7: Sistema de alertas y notificaciones de ofertas
**Objetivo:** El consumidor desea suscribirse a alertas de ofertas en productos de su lista de compras para ser notificado cuando haya cambios favorables de precio.
>> ![Diagrama Escenario 7](assets/domain-message-flows/notifications-alerts.png)

El modelado de flujos de mensajes de dominio permitió identificar con claridad las responsabilidades de cada **bounded context** y los puntos de integración críticos dentro de la plataforma **SmartCart**. Los contextos de *Shopping Planning*, *Shopping Journey* y *Experience* conforman el núcleo diferenciador del negocio, mientras que *IAM*, *Verification* y *Notification* actúan como servicios de soporte transversal. *Store Management* cumple un rol estratégico al ser el repositorio central de información de tiendas, productos y precios, siendo consumido por múltiples contextos.

Estos flujos servirán de base para el diseño de los **Bounded Context Canvases** en la sección 2.5.1.3, garantizando coherencia y alineación entre la arquitectura estratégica y la lógica del negocio.
#### 2.5.1.3. Bounded Context Canvases
En esta sección el equipo presenta sus Bounded Context Canvases, empezando por los importantes para el núcleo del negocio.

#### IAM
Encargado de gestionar la identidad, el registro y el inicio de sesión de los usuarios en la plataforma.

> ![Bounded Context Canvas - IAM](assets/canvases/iam.png)

---

#### Verification
Encargado de validar la legitimidad de las tiendas y sus datos fiscales para habilitar su operación.

> ![Bounded Context Canvas - Verification](assets/canvases/verification.png)

---

#### Store Management
Encargado de gestionar los catálogos de productos, inventarios y la actualización de precios de las tiendas.

> ![Bounded Context Canvas - Store Management](assets/canvases/store-management.png)

---

#### Shopping Planning
Encargado de permitir a los consumidores crear listas de compras y comparar precios para optimizar su ahorro.

> ![Bounded Context Canvas - Shopping Planning](assets/canvases/shopping-planning.png)

---

#### Shopping Journey
Encargado de gestionar el recorrido físico del usuario y la optimización de rutas dentro de los locales.

> ![Bounded Context Canvas - Shopping Journey](assets/canvases/shopping-journey.png)

---

#### Experience
Encargado de gestionar el feedback post-compra, el cálculo de ahorros reales y el perfil de confianza de las tiendas.

> ![Bounded Context Canvas - Experience](assets/canvases/experience.png)

---

#### Notification
Encargado del envío de alertas de ofertas, confirmaciones y notificaciones transversales del sistema.

> ![Bounded Context Canvas - Notification](assets/canvases/notification.png)
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

---

# Anexos
