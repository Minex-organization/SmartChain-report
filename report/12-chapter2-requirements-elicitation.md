# CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS

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

## 2.4. Big Picture Event Storming

Con el objetivo de comprender el funcionamiento global del sistema de trazabilidad minera, se aplicó la técnica de Big Picture Event Storming. Esta permitió identificar los eventos clave del dominio, los actores involucrados y la secuencia lógica de la operación desde la extracción del mineral hasta su validación por el consumidor final.

### 2.4.1. Generación de Domain Events

Se identificaron los principales eventos del dominio, expresados en tiempo pasado, que representan hechos relevantes dentro del sistema:

- Mineral extraído  
- Lote creado  
- Registro de extracción generado  
- Dispositivo IoT asignado  
- Ubicación registrada  
- Transporte iniciado  
- Ubicación actualizada  
- Transporte finalizado  
- Mineral recibido en planta  
- Mineral procesado  
- Producto creado  
- Código QR generado  
- Producto registrado en el sistema  
- Certificación generada  
- Anomalía detectada  
- Alerta generada  
- Producto verificado por cliente  

<div style="page-break-after: always"></div>

### 2.4.2. Ordenamiento de Eventos (Flujo del Dominio)

Los eventos fueron organizados cronológicamente para representar el flujo principal del sistema:

1. Mineral extraído  
2. Lote creado  
3. Registro de extracción generado  
4. Dispositivo IoT asignado  
5. Transporte iniciado  
6. Ubicación registrada / actualizada (eventos concurrentes)  
7. Transporte finalizado  
8. Mineral recibido en planta  
9. Mineral procesado  
10. Producto creado  
11. Código QR generado  
12. Producto registrado en el sistema  
13. Certificación generada  
14. Producto verificado por cliente  

Adicionalmente, se identificaron eventos alternos como:

- Anomalía detectada  
- Alerta generada  

### 2.4.3. Identificación de Actores

Se determinaron los actores que interactúan con el sistema y que desencadenan los eventos:

- **Operario Minero:** Responsable de la extracción y registro inicial del mineral  
- **Empresa Minera:** Gestiona la información de los lotes  
- **Sistema IoT:** Registra automáticamente datos de ubicación y estado  
- **Transportista:** Responsable del traslado del mineral  
- **Planta Procesadora:** Encargada de transformar el mineral en producto  
- **Cliente Final:** Verifica la autenticidad del producto mediante QR  

<div style="page-break-after: always"></div>

### 2.4.4. Sistemas Externos

Se identificaron sistemas externos que interactúan con la solución:

- Sistemas de geolocalización (GPS)  
- Servicios de validación o certificación externa  
- APIs de integración con sistemas empresariales (ERP/CRM)  

### 2.4.5. Storytelling del Dominio

El flujo del sistema puede describirse de la siguiente manera:

El proceso inicia cuando el operario minero realiza la extracción del mineral, generando un registro inicial dentro del sistema. Posteriormente, se crea un lote y se le asigna un dispositivo IoT que permite capturar datos en tiempo real durante su transporte.

A lo largo del traslado, el sistema registra continuamente la ubicación del mineral hasta su llegada a la planta procesadora, donde es transformado en un producto final. Una vez procesado, se genera un código QR que permite asociar el producto con su historial de trazabilidad.

Finalmente, el cliente puede escanear el código QR para verificar la autenticidad del producto, su origen y las condiciones en las que fue procesado, asegurando transparencia y confianza en la cadena de suministro.

<div style="page-break-after: always"></div>

### 2.4.6. Reverse Storytelling

Partiendo del evento final **“Producto verificado por cliente”**, se identificaron los eventos previos necesarios:

- Código QR generado  
- Producto creado  
- Mineral procesado  
- Transporte finalizado  
- Ubicación registrada  
- Dispositivo IoT asignado  
- Lote creado  
- Mineral extraído  

Este análisis permitió validar la coherencia del flujo y detectar posibles mejoras en la trazabilidad del sistema.

### 2.4.7. Resultados del Event Storming

Como resultado de la dinámica, se obtuvo:

- Una visión compartida del dominio del sistema  
- Identificación de eventos clave del negocio  
- Claridad en la interacción entre actores  
- Base para la definición del lenguaje ubicuo  
- Insumos para el diseño de la arquitectura del sistema  

<div style="page-break-after: always"></div>

![Event Storming Minex Organization](assets/img/event-storming-minex-organization.png)

<div style="page-break-after: always"></div>

## 2.5. Ubiquitous Language