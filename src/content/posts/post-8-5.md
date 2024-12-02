---
title: "8.5. Desarrollar el cronograma"
description: "meta description"
date: 2024-12-02T05:00:00+00:00
image: "/images/posts/08-5.png"
draft: false
authors: ["Brian Inca"]
tags: ["desarrollo","cronograma"]
categories: ["Linea base del cronograma"]
---

El desarrollo del cronograma es el proceso de analizar la secuencia de actividades, sus duraciones, los recursos necesarios y las restricciones del cronograma para crear el cronograma del proyecto.

&nbsp;
## Entradas
&nbsp;

### Plan para la Dirección del Proyecto

<iframe src="https://docs.google.com/document/d/e/2PACX-1vQEghe1rYfdFqjdE9cCYOE8yCF06AUDsaQ63Iqd8BJTYkuyeAHJZtWGpYfT-cbCYS4pLFUBHmyl3JB-/pub?embedded=true" width="100%" height="500px"></iframe>

&nbsp;
### Diagrama de Red del Cronograma

<!-- draw.io diagram -->
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#E6E6E6&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers tags lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;url&quot;:&quot;https://drive.google.com/uc?id=1SlpW2b6MsuBCfPR1xm9n0S-wvSXmJU3L&amp;export=download&quot;}"></div>
<script type="text/javascript" src="https://viewer.diagrams.net/embed2.js?&fetch=https%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1SlpW2b6MsuBCfPR1xm9n0S-wvSXmJU3L%26export%3Ddownload"></script>

&nbsp;
### Lista de actividades

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT4DuKdF75e1XSKWDn5OiCoctyr-Fk0Pymbfy0pIIvYja3Y8bSCmFyCoIkHHWFk6N_NKGtH0rmkDcrn/pubhtml?gid=0&amp;single=true" width="100%" height="500px"></iframe>

&nbsp;
### Duración de las actividades

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRUk7NyzDLjmRU8YBKUhHBEQlaATrRqwdRKAFW_aRfVrAMuFJZOueE63ARm78gClx9jaBOHSK3_0J2p/pubhtml?gid=0&amp;single=true" width="100%" height="500px"></iframe>

&nbsp;
## Herramientas y Técnicas
&nbsp;

### Método de la ruta crítica

El CPM permite identificar la secuencia de actividades críticas que determinan la duración total del proyecto. Las actividades críticas no tienen margen de flotación, por lo que cualquier retraso en estas afectará la fecha de finalización del proyecto.
Pasos a seguir:
- Identificar las actividades críticas: Basándonos en las duraciones y dependencias, identificamos la ruta más larga en el proyecto.
- Calcular fechas de inicio y fin: Usamos las fechas de inicio más tempranas y más tardías para determinar la flexibilidad (flotación).
- Incorporar los feriados y días no laborables: Ajustamos las fechas calculadas para considerar fines de semana y feriados.

Actividad A: Selección del sitio

- Inicio temprano (ES): 01/03/2025 (Fecha de inicio del proyecto)
- Fin temprano (EF): 01/03/2025 + 3 días = 04/03/2025
Actividad B: Preparación del sitio

ES: 05/03/2025 (debido a la dependencia de A)
EF: 05/03/2025 + 4 días = 09/03/2025

&nbsp;
## Salidas
&nbsp;

### Cronograma del proyecto

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT2LM21ZL-pf6CzLL0BLlMd9tTQQDcvpXBmjYqiCHMrayHb8s_g0DLB3Bql5DYFdhMmy0AUnsqFur7u/pubhtml?gid=0&amp;single=true" width="100%" height="500px"></iframe>