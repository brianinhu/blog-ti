---
title: "VII. Creación de la Estructura de Desglose de Trabajo (EDT)"
description: "meta description"
date: 2024-11-11T06:00:00+00:00
image: "/images/posts/07.jpg"
draft: false
authors: ["Brian Inca"]
tags: ["EDT", "EEFs", "OPAs"]
categories: ["VII"]
---

En este post, se presenta la creación de la EDT para el proyecto de Implementación de Dispensadores de Agua Inteligentes con Gestión de Datos e IoT en la Universidad Nacional Tecnológica de Lima Sur (UNTELS).

&nbsp;
## Entradas
&nbsp;
### 1. Factores Ambientales de la Empresa (EEFs)

Los EEFs impactan en el desarrollo y la operación del proyecto, por lo que es vital analizarlos para anticipar y mitigar riesgos y aprovechar oportunidades.

##### EEFs Internos a la Organización:

- **Cultura, estructura y gobernanza de la organización:** La universidad promueve en su misión la sostenibilidad y la adopción de tecnologías innovadoras, lo que favorece la aceptación del proyecto. La estructura organizativa, orientada a la gestión de proyectos de TI, proporciona un entorno colaborativo entre las áreas de TI, infraestructura y mantenimiento.

- **Distribución geográfica de instalaciones y recursos:** La universidad, al tener un campus mediano en tamaño, cuenta con varios espacios de alto tráfico. La selección de ubicaciones estratégicas para los dispensadores es fundamental para maximizar el impacto en la comunidad universitaria y la accesibilidad al recurso.

- **Infraestructura:** La infraestructura tecnológica existente, como la cobertura de la red Wi-Fi y el acceso a servidores para la plataforma IoT, es crucial para la funcionalidad del proyecto. Evaluar la capacidad de esta infraestructura para soportar los nuevos sistemas es vital.

- **Software informático:** El software actual de gestión de activos debe ser evaluado para determinar la integración con la nueva plataforma de monitoreo IoT. Esto incluye considerar el uso de APIs y sistemas de seguridad en el manejo de datos.

- **Disponibilidad de recursos:** La universidad actualmente tiene un equipo de TI capacitado, pero es necesario identificar si se requieren capacitaciones adicionales para manejar la nueva tecnología.

- **Capacidad de los empleados:** La competencia técnica del personal debe reforzarse mediante entrenamientos específicos en gestión de datos IoT y mantenimiento predictivo.

##### EEFs Externos  a la Organización:

- **Condiciones del mercado:** El acceso a tecnologías de IoT puede depender de factores como la disponibilidad de equipos y el costo fluctuante de componentes. Evaluar la confiabilidad de los proveedores y posibles demoras es esencial.

- **Influencias sociales y culturales:** La comunidad universitaria muestra una inclinación hacia prácticas sostenibles, esto se refuerza aún más con la existencia de la carrera de Ingeniería Ambiental en la universidad. El proyecto debe incluir una campaña de concienciación para incentivar el uso responsable de los dispensadores y destacar sus beneficios en sostenibilidad.

- **Estándares gubernamentales e industriales:** Cumplir con normativas de calidad del agua, regulación de dispositivos IoT y protección de datos es imprescindible para evitar sanciones y garantizar un funcionamiento ético y legal.

- **Restricciones legales:** Las leyes sobre la privacidad de datos y el uso de sensores deben ser revisadas para asegurar el cumplimiento en la recopilación y almacenamiento de datos.

- **Bases de datos comerciales e investigaciones académicas:** Consultar estudios recientes y bases de datos sobre eficiencia en proyectos similares puede ofrecer información valiosa para optimizar el rendimiento.

- **Elementos ambientales físicos:** El clima y las condiciones del campus deben considerarse para proteger los dispensadores de factores externos como humedad y temperaturas extremas. Especialmente el clima de Villa el Salvador, lugar donde queda ubicada la universidad, es húmedo y nublado la mayor parte del tiempo por su cercanía a la playa.

### Activos de los Procesos de la Organización (OPAs)

Los OPAs representan los recursos internos que la UNTELS puede aprovechar para facilitar la implementación y gestión del proyecto.

##### Procesos, políticas y procedimientos organizacionales:

- **Políticas de adquisiciones y contratos:** La UNTELS debe contar con políticas establecidas para la compra de equipos tecnológicos. Estas políticas deben ser revisadas para asegurar la adquisición eficiente de dispensadores y software de IoT.

- **Procedimientos de mantenimiento y operación:** Documentos existentes de mantenimiento preventivo pueden ser adaptados para incluir los nuevos sistemas de dispensadores inteligentes. Estos procedimientos ayudan a asegurar la consistencia en el mantenimiento y operación.

- **Políticas de sostenibilidad:** La universidad tiene iniciativas en sostenibilidad que respaldan el proyecto. Estas políticas deben ser comunicadas para reforzar el compromiso institucional con la gestión responsable del agua.

- **Protocolos de seguridad y protección de datos:** UNTELS posee lineamientos para el manejo seguro de la información. Adaptar estos protocolos para incluir la gestión de datos de los sensores IoT asegurará el cumplimiento de estándares de privacidad.

##### Bases de Conocimiento de la Organización

- **Lecciones aprendidas:** La universidad ha implementado proyectos tecnológicos previos; aprovechar las lecciones aprendidas ayudará a anticipar desafíos y definir mejores prácticas.

- **Documentación técnica:** El acceso a manuales y guías técnicas existentes facilita la capacitación y rápida adaptación del personal a los nuevos sistemas.

- **Registros de mantenimiento y soporte técnico:** Los registros de mantenimiento de otros dispositivos pueden servir como referencia para estructurar un plan de soporte eficiente para los dispensadores inteligentes.

- **Plantillas y formularios:** Utilizar plantillas existentes para informes de progreso y evaluaciones permitirá estandarizar la documentación del proyecto y mejorar la comunicación entre equipos.

&nbsp;
## Herramientas y Técnicas
&nbsp;

### Descomposición

El proceso de descomposición comenzó con la identificación de los entregables principales, dividiendo progresivamente el proyecto en componentes más detallados hasta alcanzar los niveles de paquetes de trabajo.

1. **Identificación de entregables de alto nivel:** Se inició el proceso determinando los entregables principales, como la Instalación del Dispensador Inteligente, la Implementación del Sistema IoT y las Pruebas y Puesta en Marcha.

2. **División en componentes específicos:** Cada entregable se subdividió en partes más detalladas. Por ejemplo, la instalación se descompuso en tareas como la selección del sitio de instalación y el montaje del dispensador, mientras que la implementación del sistema IoT abarcó desde el desarrollo del software hasta la configuración de la red de sensores, ya las pruebas y puestas en marcha se dividió en pruebas del sistemas y puesta en marcha.

3. **Definición de paquetes de trabajo:** El proceso continuó hasta que cada componente alcanzó un nivel que permitiera asignar tareas específicas. Ejemplos incluyen la programación de controladores, la montura de sensores IoT y la documentación del monitoreo inicial.

&nbsp;
## Salidas
&nbsp;

### Línea Base de Alcance

##### Declaración del Alcance del Proyecto

**1. Entregables del Proyecto**

- **Dispensadores de agua inteligentes:** Instalados y operativos en las ubicaciones designadas.

- **Plataforma de monitoreo IoT:** Desarrollada e integrada con la red de la universidad.

- **Manual de usuario y documentación técnica:** Guías completas para la operación y mantenimiento del sistema.

- **Capacitación:** Sesiones de formación para el personal involucrado.

- **Informe de evaluación:** Registro de pruebas, puesta en marcha y recomendaciones para mejoras futuras.

**2. Alcance del Trabajo**

El proyecto incluirá las siguientes actividades:

- **Instalación física:** Identificación y adecuación de sitios de instalación, montaje de los dispensadores y sensores IoT.

- **Desarrollo de software:** Programación de controladores, configuración de la red IoT y pruebas de conectividad.

- **Pruebas y validación:** Ejecución de pruebas de funcionamiento y recopilación de datos de rendimiento.

- **Capacitación y soporte:** Entrenamiento del personal y provisión de soporte técnico durante el período inicial.

**3. Exclusiones del Proyecto**
El proyecto no contempla:

- **Renovaciones de infraestructura no relacionada:** Cualquier actualización o renovación física que no esté directamente vinculada a la instalación de los dispensadores.

- **Mantenimiento a largo plazo:** Soporte técnico más allá del período de garantía inicial.

- **Actualizaciones futuras del software IoT:** Nuevas versiones o características adicionales del sistema desarrolladas después del lanzamiento inicial.

**4. Criterios de Aceptación**
El proyecto se considerará exitoso cuando:

- Los dispensadores estén instalados y operativos en todas las ubicaciones designadas.

- La plataforma IoT funcione correctamente, capturando y mostrando datos en tiempo real.

- El personal esté capacitado y pueda operar y mantener los sistemas sin dificultad.

- Las pruebas y puesta en marcha se hayan completado con resultados satisfactorios, documentados en un informe de evaluación.

**5. Supuestos y Restricciones**

**Supuestos:**

- Se asumirá que la red Wi-Fi existente soporta la conectividad requerida por los dispensadores IoT.

- Los recursos necesarios, tanto humanos como tecnológicos, estarán disponibles según lo planificado.

**Restricciones:**

- El proyecto debe ajustarse al presupuesto establecido y a las regulaciones de protección de datos vigentes.

- Las actividades deben completarse dentro del cronograma definido, sin comprometer la calidad del resultado.

### Estructura de Desglose del Trabajo (EDT)

La estructura, partiendo desde el nivel 1 hasta los niveles más detallados, permite una comprensión clara del alcance completo del proyecto. El desglose abarca desde la instalación y desarrollo de software hasta las pruebas y entrega del sistema.

![chuntels](/images/diagrama-edt.png)