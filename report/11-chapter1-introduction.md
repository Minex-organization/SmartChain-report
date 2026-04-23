# CAPÍTULO I: INTRODUCCIÓN

## 1.1. Startup Profile

### 1.1.1. Descripción del Startup

Somos **MINEX**, una startup  integrado por estudiantes de la carrera de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas. Nuestra startup se centra en la industria minera, con el objetivo de monitorear, examinar y certificar el camino de los minerales desde su extracción hasta el producto final. Esto se logra mediante el desarrollo de una plataforma que permite la trazabilidad de minerales, utilizando tecnología IoT, soluciones web e inteligencia artificial.

*Misión:* Desarrollar tecnologías de vanguardia que permitan rastrear, examinar y validar el trayecto de los minerales, asegurando la autenticidad de los productos y promoviendo activamente la responsabilidad social en la industria.

*Visión:* Consolidarnos como la empresa líder en trazabilidad minera en América Latina, conectando a toda la cadena de valor: desde la mina hasta el consumidor; con información confiable, inmutable y verificable.

<div style="page-break-after: always"></div>

### 1.1.2. Perfiles de integrantes del equipo

## 1.1. Solution Profile

**OpalTrace** es una plataforma web SaaS que tiene como objetivo ayudar a las empresas mineras a aumentar la eficacia y la logística, minimizando pérdidas al igual que optimizando la gestión de las operaciones mediante el uso de datos en tiempo real. Asimismo, proporciona a las joyerías las herramientas imprescindibles para confirmar el origen de los minerales, lo que les permite ofrecer productos de calidad; y así asegurar al consumidor la autenticidad del producto, al facilitar la transparencia de la información, lo que fomenta una compra consciente y ética.

### 1.2.1. Antecedentes y problemática

#### What?
El problema gira en torno a la falta de trazabilidad de los minerales en el Perú. Lo que dificulta el identificar el origen, la autenticidad y el trayecto de recursos como el oro u otros metales.
Según la directora ejecutiva de la Sociedad Nacional de Mineria, Angela Grossheim, rastrear el origen de minerales, especialmente el oro, es difícil debido al mercado informal mezclándose con el mercado formal (DesdeAdentro, 2025). Esto indica que en el sector existen dudas acerca de los minerales y si estos tienen un origen legal, de la misma manera en que se pueden manipular los datos de los productos lo cual incrementa el riesgo de perdidas y/o fraude.

#### Who?
Alrededor de este tema se pueden identificar varios actores, principalmente a las empresas mineras, ya que estas presentan dificultades para mantener un control optimo de su logística. Lo cual termina en ineficiencia operativa, problemas con los equipos y pérdidas de recursos económicos y materiales.
Por otro lado, también como actores involucrados se incluye a las joyerías y los consumidores finales, puestos que estos buscan adquirir productos auténticos que posean un origen ético. Sin embargo, al no contar con datos confiables se crea una desconfianza en el mercado sobre el verdadero valor de algunos productos.

#### Where?
Este problema se presenta alrededor de la industria minera, como en las zonas de extracción, las etapas de transporte, el almacenamiento, procesamiento y comercialización de los minerales.

#### When?
La problemática sucede en momentos como el desplazamiento, procesamiento y transferencia de los minerales.

#### Why?
Este problema aparece debido al bajo uso de tecnologías para supervisar y gestionar los minerales, ya que muchas empresas siguen utilizando registros manuales cuyos datos pueden ser fácilmente alterables.

#### How?
El problema surge debido a la falta de seguimiento de los minerales, lo que lleva a que nuestros usuarios utilicen la solución cuando requieran asegurar el control y la verificación de los minerales.

#### How much?
Esta problemática afecta a varios sectores, pero en especial al económico. Según el fiscal coordinado de las Fiscalias Especializadas en Materia Ambiental, Frank Almanza, afirmo que las pérdidas económicas por minería ilegal equivalen al 2,5% del PBI (Canchari, 2025). Gracias a esto, podemos deducir que la ausencia de un sistema de seguimiento impacta no solo a los ingresos de las empresas, sino que también tiene consecuencias en la economía nacional, resaltando lo importante que es buscar una solución a este problema.

<div style="page-break-after: always"></div>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Nuestra solucion busca mejorar la trazabilidad de los minerales mediante el uso de una plataforma que use tecnología IoT, Web e IA.
Hemos observado que las empresas, sobre todo relacionadas a la mineria, sufren ineficiencias operativas al tener dificultades para monitorear en tiempo real el traslado de los minerales.
*¿Como puede nuestro producto apoyar en el rastreo de minerales para reducir perdidas?*

Nuestra solucion busca verificar la autenticidad de los minerales que son usados en productos.
Hemos observado que las tiendas no cuentan con mecanismos para validar el origen de los minerales lo cual afecta la credibilidad de los distribuidores.
*¿Como puede nuestro producto garantizar la autenticidad de los minerales para reforzar la confianza entre los clientes?*

Nuestra solucion busca ofrecer acceso transparente a la información relacionada al origen de los productos minerales que terminan en objetos que se compran en el dia a dia.
Hemos observado que el consumidor no tiene una forma de verificar si el producto proviene de fuentes responsables.
*¿Como puede nuestro producto fomentar la venta de productos hechos en base a minerales con origen etico?*

<div style="page-break-after: always"></div>

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**
- Creemos que nuestros usuarios necesitan tener una herramienta con la que puedan validar el recorrido de los minerales.
- Estas necesidades se pueden satisfacer con una solucion web que brinde informacion detallada sobre los minerales tratados.
- Nuestros clientes iniciales seran las empresas, joyerias y los usuarios finales.
- El valor mas importante que un cliente quiere de nuestros servicios es la trazabilidad de los minerales, incluyendo informacion desde su origen.
- El cliente tambien va a obtener reduccion de perdidas y apoyo en las decisiones logísticas.
- Vamos a obtener la mayoria de los clientes mediante alianzas con empresas relacionadas al sector minero al igual que marketing B2B y demostraciones del sistema en eventos del sector.
- Vamos a obtener ingresos mediante suscripciones mensuales las cuales dependan de un numero de productos analizados preestablecido.
- Nuestra competencia en el mercado seran soluciones que monitoreen los minerales de manera incompleta con software caro y poco flexible.
- Vamos a tener ventaja frente a nuestra competencia debido a la integración de tecnologías IoT, IA y WEB en el enfoque de la trazabilidad del mineral.
- El mayor riesgo del servicio es la adaptación del sistema en productos ya existentes y errores manuales al momento de registrar datos.
- Lo resolveremos realizando interfaces simple y sesiones de entrenamiento simulando casos reales.

**User Assumptions:**
- **¿Quien es el usuario?**
Los usuarios son empresas mineras que necesiten gestionar los bienes obtenidos. Tambien estan, las joyerías que requieran validar dichos insumos. Finalmente son los usuarios finales que esten interesados en conocer el origen de los productos y evitar ser estafados en el proceso.
- **¿Que problemas tiene nuestro producto que resolver?**
Nuestro producto tiene que resolver las dificultades en el monitoreo de los minerales, al igual que necesita verificar tanto la autenticidad como el origen etico de estos.
- **¿Que caracteristicas son importantes?**
Se incluye el registro y monitoreo en tiempo real del traslado de los minerales, en estos registros estará información como el peso del mineral, la cantidad de este, las condiciones del envió y la verificación de la carga y de la descarga. Del mismo modo es necesaria la generacion de reportes especificando quien superviso, quien manipulo, cuando y donde.
- **¿Donde encaja nuestro producto en su trabajo o vida?**
El producto encaja en la gestión operativa y en la logística de las empresas mineras para que estas puedan tener un mejor control sobre los minerales obtenidos. También encaja tanto en tiendas como en consumidores pues estos pueden validar y verificar información sobre los productos.
- **¿Cuando y como es nuestro producto usado?**
Se utiliza durante todo el proceso del ámbito minero, llendo desde la extracción, incluyendo el traslado, el deposito o el procesamiento hasta la venta final. El producto puede ser usado mediante una plataforma web en cualquier momento siendo limitado por el rol del usuario.
- **¿Como debe verse nuestro producto y como debe comportarse?**
Debe ser intuitiva mediante el uso de dashboards, de esta manera brindara una navegación sencilla a los usuarios mientras brinda información confiable y lo suficientemente rápida como para estar a tiempo real.

<div style="page-break-after: always"></div>

#### 1.2.2.3. Lean UX Hypothesis Statements

**Creemos** que una plataforma que permita monitorear en tiempo real los minerales ayudara a reducir las perdidas de minerales.
**Sabremos que** hemos tenido éxito
**Cuando** en los reportes de las empresas mineras disminuya la cantidad de perdidas.

**Creemos** que una plataforma que pueda certificar la autenticidad de los minerales ayudara a mejorar la confianza entre tiendas y consumidores.
**Sabremos que** hemos tenido éxito
**Cuando** los productos con certificación sean más vendidos respecto a los productos regulares.

**Creemos que** una plataforma que permita al usuario observar información de los productos en venta logrará fomentar decisiones de compra responsables.
**Sabremos que** hemos tenido éxito
**Cuando** calculemos el tiempo de visualización de información como una estadística.

<div style="page-break-after: always"></div>

#### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas SmartChain](../assets/img/chapter-i/LeanUXCanvas.png)

<div style="page-break-after: always"></div>

## 1.3. Segmentos Objetivo

### Segmento 1: Empresas mineras

#### Descripción general:
Se refiere a las empresas que se dedican a la extracción de los minerales que terminan siendo procesados en productos pero que tienen problemas en la trazabilidad de sus operaciones.

#### Perfil Operativo:
Incluye a ingenieros y supervisores de entre 30 a 60 años que trabajan en las zonas mineras del Perú.

#### Datos del sector:
Según Canchari (2025), los problemas de trazabilidad y control en el sector minero genera mas de 22 mil millones de soles como perdidas al año.

#### Necesidad:
Este segmento necesita herramientas tecnológicas que permita el monitoreo en tiempo real para optimizar la logística en el ámbito minero.

### Segmento 2: Joyerías 

#### Descripción general:
Se refiere a empresas que venden productos cuyo material principal son los minerales pero que tienen dificultades al momento de garantizar el origen de dichos productos.

#### Perfil Operativo:
Incluye a dueños y gerentes de dichas tiendas cuya edad varia entre 26 a 60 años ubicados en zonas comerciales del Perú

#### Datos del sector:
Según el presidente de la Sociedad Nacional de Mineria, Petroleo y Energia, Victor Gobitz, la minería ilegal implementa más del millón de onzas de oro al mercado (Cruz, 2024). Esta alarmante cantidad significa que existe una alta probabilidad de que las joyerías vendan productos con una trazabilidad inexistente.

#### Necesidad:
Este segmento necesita herramientas tecnológicas que permitan validar el origen del mineral para ofrecer una certificación confiable a los clientes.

### Segmento 3: Consumidores finales

#### Descripción general:
Se refiere a personas que compran productos como joyas.

#### Perfil Operativo:
Incluye adultos jóvenes de entre 18 a 25 años con un interés en el consumo responsable.

#### Datos del sector:
Según el Anuario Minero 2024 del Minem, el Perú produjo 100 mil toneladas de oro, pero exporto 200 mil (Nuñez, 2025). Esto indica que alrededor de 100 mil toneladas de oro ilegales pueden ser exportadas mediante canales formales los cuales terminan siendo compradas por los consumidores.

#### Necesidad:
Este segmento necesita herramientas que les permita acceder a la información del producto de manera sencilla para poder reconocer su origen y autenticidad.

<div style="page-break-after: always"></div>