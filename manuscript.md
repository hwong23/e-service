---
title: Propuesta Hoja de Ruta FNA, Período 2023
keywords:
- SOA
- madurez
- gobierno
- FNA
lang: en-US
date-meta: '2023-04-03'
author-meta:
- Harry Wong, ing.
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Propuesta Hoja de Ruta FNA, Período 2023" />
  <meta name="citation_title" content="Propuesta Hoja de Ruta FNA, Período 2023" />
  <meta property="og:title" content="Propuesta Hoja de Ruta FNA, Período 2023" />
  <meta property="twitter:title" content="Propuesta Hoja de Ruta FNA, Período 2023" />
  <meta name="dc.date" content="2023-04-03" />
  <meta name="citation_publication_date" content="2023-04-03" />
  <meta property="article:published_time" content="2023-04-03" />
  <meta name="dc.modified" content="2023-04-03T19:41:59+00:00" />
  <meta property="article:modified_time" content="2023-04-03T19:41:59+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Harry Wong, ing." />
  <meta name="citation_author_institution" content="Arquitecto SOA, Stefanini" />
  <link rel="canonical" href="https://hwong23.github.io/e-service/" />
  <meta property="og:url" content="https://hwong23.github.io/e-service/" />
  <meta property="twitter:url" content="https://hwong23.github.io/e-service/" />
  <meta name="citation_fulltext_html_url" content="https://hwong23.github.io/e-service/" />
  <meta name="citation_pdf_url" content="https://hwong23.github.io/e-service/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://hwong23.github.io/e-service/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/e-service/v/5d6e28331f98e90f547c159b65ec8164de9bd9be/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/e-service/v/5d6e28331f98e90f547c159b65ec8164de9bd9be/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/e-service/v/5d6e28331f98e90f547c159b65ec8164de9bd9be/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
Esta propuesta
([URL](https://hwong23.github.io/e-service/v/5d6e28331f98e90f547c159b65ec8164de9bd9be/))
está basada en el resultado de la consultoría "Arquitectura E-Service"
, [hwong23/e-service@5d6e283](https://github.com/hwong23/e-service/tree/5d6e28331f98e90f547c159b65ec8164de9bd9be)
del April 3, 2023.
</em></small>



## Autores



+ **Harry Wong, ing.**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [e_hwong](https://github.com/e_hwong)
    <br>
  <small>
     Arquitecto SOA, Stefanini
  </small>


::: {#correspondence}
✉ — Enviar mensajes a [GitHub Issues](https://github.com/hwong23/e-service/issues)
o correo electrónico 
Harry Wong, ing. \<e_hwong@stefanini.com\>.


:::


## Resumen y control de cambios {.page_break_before}

|Tema            |Portafolio de iniciativas y brechas: **Hoja de ruta de los proyectos de cierre de brecha E-Service**|
|----------------|---------------------------------------------------|
|Palabras clave  |SOA, E-Service, FNA, Análisis de brecha, GAP, Comparativa          |
|Autor           |                                                   |
|Fuente          |                                                   |
|Versión|5d6e283 del 03 Apr 2023                              |
|Vínculos|[N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md)|

<br>




## Hoja de Ruta E-Service FNA (Arquitectura E-Service)
Los proyectos de la hoja de ruta resultado de la ejecución de la consultoría "Arquitectura E-Service", dentro del proyecto PETI, son los siguientes:

1. Gobierno SOA
1. Oficina de arquitectura
1. Arquitectura de referencia 2.0
1. Portafolio API
1. Microservicios
1. Plataforma híbrida de integración
1. Service mesh
1. Hub de integración digital
1. Gobierno de datos
1. Gestión de datos maestros
1. Arquitectura de datos (data mesh)
1. Devops
1. Infraestructura escalable nube
1. Infraestructura autoservicio de datos

<br>

La secuencia, la dependencia y los plazos estimados de los proyectos de la hoja de ruta E-Service FNA es la indicada en la siguiente imagen.

![](images/hojaruta1.png)

[Imagen 1.]() Proyectos de cierre de brecha FNA. Prioridades, dependencias, secuencia, puntos de control de la evolución de la arquitectura de referencia SOA 2.0 del Fondo.

_Fuente: Consultoría Arquitectura E-Service._

<br>



## Justificación
La ejecución de la hoja de ruta E-Service (diagnóstico SOA) plantea la implementación de los proyectos de cierre de brechas que impacten a los problemas diagnosticados en dicho proyecto. Estos son: a la flexibilidad de negocio, al fortalecimiento de construcción y diseño de servicios, y a la independencia de proveedor, en el ámbito de las vicepresidencias de Crédito y de Operación, en el período de ejecución 2023.

Como resultado del inicio de la ejecución de la hoja de ruta el Fondo Nacional del Ahorro (FNA) procura 1) aumentar las capacidades de desarrollo de soluciones y requerimientos, y 2) modernizar y aumentar la capacidad del uso tecnológico de estas soluciones.

Puntualmente, la implementación (todos los proyectos) de la hoja de ruta, tal como está diagnosticada por E-Service, buscan los objetivos de (ordenados por prioridad):

* Flexibilidad y tiempo de mercado (OBJ3)
* Fortaleza SOA de las aplicaciones (OBJ2)
* Independencia de proveedor (OBJ1)

<br>

Para lo cual, la hoja de ruta E-Service está orientada a impactar los siguientes brechas y oportunidades:

* OP1. Instaurar la figura de gobierno SOA, capacidad, proceso y recursos
* OP2. Mejorar proceso de diseño,  construcción y DevOps de soluciones SOA
* OP3. Mejorar la oferta de servicios analíticos en segmento FNA
* OP4. Aumentar el nivel de utilización de la Tecnología SOA del FNA
* OP5. Desarrollo de Servicios FNA guiada por la arquitectura de referencia 2.0
* OP6. Gestión de la Tecnología (gobierno) orientada por arquitectura 2.0
* OP7. Articulación y fortalecimiento del equipo de arquitectura del FNA junto a proveedores
* OP8. Monitoreo de los índices de eficacia de los servicios FNA

<br>



## Alcance de la primera ejecución de la hoja de ruta E-Service
Para el período 2023, la implementación de la hoja de ruta E-Service impactará los objetivos de Flexibilidad (OBJ3) y Fortalecimiento (OBJ2), mediante el incremento de las capacidades del FNA 
de Gestión de tecnología (CAP1) y de Entrega de productos y funcionalidades (CAP2), en el dominio de aplicaciones y servicios únicamente. Esto implica la planeación, ejecución y seguimiento de los proyectos siguientes:

* PRY01. Gobierno SOA FNA --Incremento 1: dominio de aplicaciones y servicios únicamente
* PRY02. Arquitectura Referencia --Incremento 1: dominio de aplicaciones y servicios únicamente
* PRY03. Estructuración de proyectos posteriores de la hoja de ruta E-Service

<br>

El alcance de la primera ejecución de la hoja de ruta E-Service es el ilustrado a continuación.

![](images/vistaevolucion.png)

[Imagen 1.]() Vista de evolución de capacidades dentro del alcance del proyecto hoja de ruta E-Service, período 2023, dominio de aplicaciones y servicios. Capacidades incrementadas para impactar a los objetivos Flexibilidad (OBJ3) y Fortalecimiento (OBJ2).

<br>



## Proyectos del Alcance
Los proyectos PRY01, PRY02 y PRY03 de la hoja de ruta consignados en este alcance tienen por objeto cerrar las brechas de fortaleza SOA y riesgos técnicos determinados en el diagnóstico de la consultoría "Arquitectura E-Service". Estos proyectos buscan además incrementar las capacidades del FNA, CAP1 y CAP2, mencionadas en el alcance y estructurar el detalle técnico y tecnoleogico de los proyectos futuros planteadas en dicha hoja de ruta.

Las brechas en cuestión, relacionadas abajo en la imagen, son las indicadas en la justificación del presente alcance:

* Flexibilidad y tiempo de mercado (OBJ3)
* Fortaleza SOA de las aplicaciones (OBJ2)
* Independencia de proveedor (OBJ1)

<br>

La evolución de la arquitectura del FNA impactada mediante este alcance está organizada en dos incrementos.

#### Arquitectura de referencia 2.0. Incremento 1
Versión mejorada de arquitectura actual SOA FNA con soporte en implementación parcial del gobierno y definiciones iniciales de la arquitectura de referencia SOA 2.0. Aplicación de arquitectura de referencia inicial a ítems seleccionados en una fase de levantamiento (LVT).

#### Arquitectura de referencia 2.0. Incremento 2
Continuidad de la mejora del incremento 1. La arquitectura SOA FNA cuenta con implementación total del gobierno, una definición candidata de la arquitectura de referencia 2.0, y aplicación de la aplicación de cambios en ítems adicionales de la arquitectura actual.

La siguiente imagen ilustra el alcance propuesto en términos de las capacidades del FNA impactadas, los proyectos de ejecución, las evoluciones de la arquitectura y las brechas involucradas. 

![](images/vistaevolarquitectura.jpg)

[Imagen 2.]() Vista de evolución de arquitectura de referencia FNA a razón de las capacidades incrementadas mediante los proyectos de este alcance.

A continuación presentamos la descripción de los proyectos de este alcance en forma de fichas de proyecto. 

<br>


### PRY01. Gobierno SOA FNA: dominio de aplicaciones y servicios
#### Objetivo
Definir y vigilar las relaciones entre las áreas de negocio, que para este proyecto son la vicepresidencia de operaciones y la vicepresidencia de crédito del FNA; definir y vigilar la implementación y diseño de las soluciones SOA, servicios y herramientas de software, en cumplimiento de la nueva arquitectura de referencia 2.0 del FNA. Este gobierno SOA debe asistir en la aplicación y ejecución de un estándar de implementación, observación y puesta en marcha de dichas soluciones.

#### Actividades
- Fortalecer el comité de gobierno SOA del FNA
- Generar lineamientos y políticas de gobierno SOA
- Medir las decisiones de arquitectura y del proceso de desarrollo de las soluciones SOA

#### Entregables
- PR01. Detalle de los ítems de arquitectura impactados por el proyecto 
- PR02. Detalle de los recursos, herramientas, roles, responsabilidades y participantes
- PR03. Diseño de los procesos y responsabilidades del comité de gobierno
- PR04. Definición de roles y responsabilidades y selección e instalación del comité
- PR05. Procesos de mejoramiento de diseño y vigilancia de riesgos técnicos
- PR06. Modelos actualizados de los ítems de arquitectura impactados por el proyecto
- PR07. Métricas de efectividad del gobierno

#### Plazo de Ejecución
5 meses, iniciado a partir del mes de abril del 2023 (ver Plan de Ejecución PRY01, más adelante).

#### Impacto / Beneficio
- Lineamientos claros, libres de ambigüedad que permitan guiar y medir la evolución de la arquitectura SOA 2.0 en la organización
- Fuente única de planeación y control de las soluciones de software del FNA
- Vigilancia del cumplimiento de los niveles de servicio de las soluciones SOA​

#### Actores
- Comité de gobierno del FNA
- Oficina de arquitectura FNA
- Comité asesor 

#### Consideraciones
- MEGA: depósito centralizado de arquitectura del FNA
- Depósito documental
- Herramientas de gestión de arquitectura
- Herramientas de gestión de proyectos de tecnología

<br>


#### Equipo Base del Proyecto
|                                         | Trabajo              | Dedicación |
|:----------------------------------------|:---------------------|:-----------|
| Director / Gerente proyecto (Stefanini) | Calidad del proyecto | 100% o 50% |
|Nota: este recurso puede ser individual, o común entre ambos proyectos del alcance|
|Especialista SOA 1, o Arquitectura empresarial (Stefanini/MEGA)|Referente para montaje de gobierno SOA, modelamiento procesos, software y servicios|100%|
|Nota: considerar un perfil parcial de apoyo al especialista SOA, experiencia en herr. MEGA|
|Especialista construcción software, servicios y componentes (Stefanini)|Referente para diseño de servicios y software, modelamiento procesos, software y servicios|100%|
|Personal del FNA|Recepción y ejecución de gobierno SOA, modelamiento software y servicios|*|
| - Especialista SOA||
| - Especialista(s) construcción software||

<br>

(*) La dedicación y horas de participación de los recursos internos la dispone el FNA.

<br>



#### Plan de Trabajo
Organización de trabajo. El proyecto 1 (PRY01) está organizado en 4 fases. La fase de Levantamiento (LVT) presentada abajo en la imagen determina en detalle los elementos de gobierno y de la arquitectura que se evolucionarán en los dos incrementos planteados en los proyetos del alcance consignado arriba, y que se corresponden con las fases 2 y 3 de la plan siguiente.

![](images/pry1gobierno.jpg)

[Imagen.]() Plan de Implementación del Proyecto Hoja de Ruta E-Service FNA, 2023. Abril 2023 a Dic 2023. Ver 1.0

#### Fases del proyecto
La fase 1, Definición del Gobierno, diseña y determina los procesos de gestión de mejoramiento de la arquitectura SOA y la vigilancia de riesgo técnico que regirán en adelante en el FNA. Estos mismo procesos de gobierno aplican en las fases sucesivas del proyecto.

Las fases 2 y 3, implantan el gobierno anteriormente definido, e impactan directamente a los modelos y las decisiones de la arquitectura SOA del FNA, esto es, sistemas de información, herramientas de software, servicios, o componentes seleccionados en la fase Levantamiento.

Finalmente, la fase 4 se encarga de ejecutar los indicadores de medición de desempeño, tanto del gobierno como de los incrementos de evolución de la arquitectura de referencia 2.0 (ver resultados del diagnóstico E-Service, 2022).

#### Plazo de Ejecución
El plazo de ejecución, contado desde la firma del contrato y de la autorización de todas las partes, es de 5 meses, o su equivalente en horas

    180 hrs/mes * 5 meses = 910 hrs / hombre proyecto

<br>


### PRY02. Arquitectura de referencia SOA 2.0: dominio de aplicaciones y servicios
#### Objetivo
Definir la línea base de la arquitectura de referencia 2.0 del FNA y dirigir el desarrollo de los servicios SOA del FNA hacia diseños y tecnologías determinadas en la arquitectura de referencia 2.0 (como microservicios, REST, API, infraestructura Nube, etc.) y favorecer la adopción del estilo de arquitectura orientado a eventos para atender las funcionalidades y requerimientos de negocio, que para este proyecto son la vicepresidencia de operaciones y la vicepresidencia de crédito del FNA.

#### Actividades
- Acelerar el desarrollo de las arquitecturas de solución​
- Relacionar las implementaciones con las áreas de negocio y TI​
- Demostrar el cumplimiento de los lineamientos y políticas de gobierno​ SOA/TI del Fondo
- Documentación técnica en el depósito de arquitectura institucional​

#### Entregables
- PR10. Detalle de los ítems de arquitectura impactados por el proyecto 
- PR11. Detalle de los recursos, herramientas, roles, responsabilidades y participantes
- PR12. Diseño detallado y vistas funcional, despliegue, información, integración y tecnología​
- PR13. Modelado en lenguaje y herramienta de diseño del FNA​
- PR14. Administración de las transiciones hacia la arquitectura versión 2.0
- PR15. Inventario de artefactos genéricos y concretos de aceleración de implementación
- PR16. Análisis de impacto y modelos actualizados de los ítems de arquitectura 
- PR17. Ítems de arquitectura incrementados en ejecución

#### Plazo de Ejecución
5 meses, iniciado a partir del mes de abril dl 2023 (ver Plan de Ejecución PRY01 más adelante).

#### Impacto / Beneficio
- Reducción en tiempos y costos asociados a las soluciones SOA​
- Mejora en la alineación entre negocio y TI​
- Mitigación de rotación del equipo de arquitectura​
- Visión global de soluciones de TI vs. requisitos del negocio​
	
#### Actores
- Áreas de negocio críticas​
- Oficina de arquitectura FNA​
- Consultores y equipo de apoyo​

#### Consideraciones
- Depósito de Arquitectura
- Herramientas de modelado


<br>


#### Equipo Base del Proyecto
|                                         | Trabajo              | Dedicación |
|:----------------------------------------|:---------------------|:-----------|
| Director / Gerente proyecto (Stefanini) | Calidad del proyecto | 100% o 50% |
|Nota: este recurso puede ser individual, o común entre ambos proyectos del alcance|
|Especialista SOA o Arquitectura de software (Stefanini)|Referente y vigilancia de implementación y diseños, modelamiento software y servicios|100%|
|Especialista construcción software, servicios y componentes (Stefanini)|Implementación y vigilancia de implementación y diseños, modelamiento software y servicios|100%|
|Personal del FNA|Recepción y ejecución de diseños, requerimientos, e implementación, SOA, modelamiento requerimientos, procesos y servicios|*|
|- Especialistas de aplicaciones pertenecientes al incremento de versión de la arquitectura FNA (ver Figura3. Aplicaciones de software del FNA involucrados en los incrementos de versión de la arquitectura de referencia)||
|- Líder funcional de aplicaciones pertenecientes al incremento de versión de la arquitectura FNA||

<br>

(*) La dedicación y horas de participación de los recursos internos la dispone el FNA.

<br>


#### Plan de Trabajo
Organización de trabajo: el proyecto 2 (PRY02) inicia con la fase de Definición (DEF) en la que amplía en detalle los elementos y tecnologías de la arquitectura de referencia 2.0. Se determina además otros detalles como los elementos de la arquitectura a impactar que terminarán siendo evolucionados en los incrementos siguientes (correspondientes a las fases 2 y 3) de este mismo plan.

![](images/pry2arqref2.0.jpg)

[Imagen.]() Plan de Implementación del Proyecto Hoja de Ruta E-Service FNA, 2023. Abril 2023 a Dic 2023. Ver 1.0

#### Fases del proyecto
La fase 1 y 2, Diseño e Incremento respectivamente, tienen en realidad dos acciones: el planteamiento de la solución de la arquitectura (detalles tecnológicos), y el de la puesta en marcha de cambios mediante una implementación real de este diseño, al que llamamos arquitectura de referencia 2.0 FNA.

Las fases 3, Optimización, busca crear y gestionar el inventario de elementos genéricos de aceleración de desarrollo, como funcionalidades, y artefactos de software que cumplan los estándares de la arquitectura de referencia 2.0 definida anteriormente.

Finalmente, la fase 4 se encarga de ejecutar los indicadores de medición de desempeño de los incrementos de evolución de la arquitectura de referencia 2.0.

#### Plazo de Ejecución
El plazo de ejecución, contado desde la firma del contrato y de la autorización de todas las partes, es de 5 meses, o su equivalente en horas

    180 hrs/mes * 5 meses = 910 hrs / hombre proyecto

<br>



### PRY03. Gobierno SOA FNA: dominio de aplicaciones y servicios
#### Objetivo
Estructurar y detallar los proyectos de cierre de brecha de la hoja de ruta E-Service.

#### Actividades
- Definición de solución de los proyectos de la hoja de ruta E-Service por implementar
- Planificación de las actividades e hitos de los proyectos de la hoja de ruta E-Service
- Alistamiento de ejecución de los proyectos de la hoja de ruta por implementar: recursos y equipo de trabajo
- Aprobación de inicio de de los proyectos de la hoja de ruta

#### Entregables
- PR20. Documentación de estructuración y gestión de proyectos hoja de ruta E-Service por implementar
- PR21. Aprobación de inicio de los proyectos de la hoja de ruta E-Service
- PR22. Plan de trabajo de los proyectos de la hoja de ruta E-Service 
- PR23. Listados de recursos, roles y personas requeridas por los proyectos de la hoja de ruta E-Service
- PR24. Arquitectura de solución de los proyectos de cierre de brecha
- PR25.  Ficha de proyectos hoja de ruta E-Service. Incremento 1
- PR26.  Ficha de proyectos hoja de ruta E-Service. Incremento 2

#### Plazo de Ejecución
4 meses, iniciado a partir del mes de mayo del 2023 (ver Plan de Ejecución PRY03 más adelante).

#### Impacto / Beneficio
- Preparativos que logren la aprobación de la ejecución de los proyectos de cierre de brecha de las debilidades de arquitectura FNA.​

#### Actores
- Comité de gobierno del FNA
- Oficina de arquitectura FNA
- Personal FNA asociado por proyecto (infraestructura, Crédito, Datos, etc.)

#### Consideraciones
- MEGA: depósito centralizado de arquitectura del FNA
- Depósito documental
- Herramientas de gestión de proyectos de tecnología

<br>


#### Equipo Base del Proyecto
|                                         | Trabajo              | Dedicación |
|:----------------------------------------|:---------------------|:-----------|
|Coordinador de proyectos principal Senior (Stefanini)|Estructuración de proyectos de la hoja de ruta E-Service|100%|
|Coordinador de proyectos auxiliar (Stefanini)||100%|
|Personal del FNA|Recepción y ejecución de diseños, requerimientos, e implementación, SOA, modelamiento requerimientos, procesos y servicios|*|
|- Especialistas de aplicaciones pertenecientes al incremento de versión de la arquitectura FNA (ver Figura3. Aplicaciones de software del FNA involucrados en los incrementos de versión de la arquitectura de referencia)||
|- Líder funcional de aplicaciones pertenecientes al incremento de versión de la arquitectura FNA||

<br>

(*) La dedicación y horas de participación de los recursos internos la dispone el FNA.

<br>


#### Plan de Trabajo
Organización de trabajo: el proyecto 3 (PRY03) inicia con la fase de Levantamiento (LVT) de los proyectos por implementar de la hoja de ruta E-Service, en coordinación con las áreas de negocio y tecnología del FNA involucradas en cada proyecto. Se determinan los detalles de los elementos de la arquitectura a impactar.

![](images/pry3estructuracion.jpg)

[Imagen.]() Plan de Implementación del Proyecto Hoja de Ruta E-Service FNA, 2023. Abril 2023 a Dic 2023.

#### Fases del proyecto
Las fases 1 detalla las soluciones de los proyectos de cierre de brechas que confirman la hoja de ruta E-Service por implementar. Trata de los componentes, partes de la arquitectura de referencia 2.0, herramientas, métodos, diseños y tecnologías requeridas para la implementación y ejecución de dichos proyectos de cierre de brecha.

Las fases 2 y 3, de estructuración, agregan la información de la organización, ejecución y seguimiento de los proyectos de solución definidos en la fase anterior.

#### Plazo de Ejecución
El plazo de ejecución, contado desde la firma del contrato y de la autorización de todas las partes, es de 4 meses, o su equivalente en horas

    180 hrs/mes * 4 meses = 720 hrs / hombre proyecto

<br>



## Componentes de la Arquitectura FNA Impactados
Los aumentos de versión de la arquitectura SOA del FNA implica ítems de trabajo, componentes de software, aplicaciones, tecnologías o recursos de capital humano deban ser modificados (aumentado de versión).

Con propósito únicamente ilustrativo de los ítems que pueden ser sujetos de variante (especialización) por concepto de los incrementos de la arquitectura del FNA, dominio de aplicaciones y servicios únicamente, bajo las condiciones de tiempo y recursos del proyecto de implementación de hoja de ruta E-Service, período 2023, presentamos a continuación una lista de aplicaciones de software que pueden llegar a cambiar (otros ítems se no presentes en este ejemplo pueden ser impactados).

![](images/vistaitemsarq.png)

[Imagen 2.]() Aplicaciones de software del FNA involucrados en los incrementos de versión de la arquitectura de referencia.

<br>



## Lista de Entregables de la Propuesta
| PRY01                                                                                   | Documentación |
|-----------------------------------------------------------------------------------------|---------------|
| PR01. Detalle de los ítems de arquitectura impactados por el proyecto                   |               |
| PR02. Detalle de los recursos, herramientas, roles, responsabilidades y participantes   |               |
| PR03. Diseño de los procesos y responsabilidades del comité de gobierno                 |               |
| PR05. Procesos de mejoramiento de diseño y vigilancia de riesgos técnicos               |               |
| PR04. Definición de roles y responsabilidades y selección e instalación del comité      |               |
| PR06. Modelos actualizados de los ítems de arquitectura impactados por el proyecto      |               |
| PR07. Métricas de efectividad del gobierno                                              |               |

<br>

| PRY02                                                                                         | Documentación |
|-----------------------------------------------------------------------------------------------|---------------|
| PR10. Detalle de los ítems de arquitectura impactados por el proyecto                         |               |
| PR11. Detalle de los recursos, herramientas, roles, responsabilidades y participantes         |               |
| PR12. Diseño detallado y vistas funcional, despliegue, información, integración y tecnología​  |               |
| PR13. Modelado en lenguaje y herramienta de diseño del FNA​                                    |               |
| PR14. Administración de las transiciones hacia la arquitectura versión 2.0                    |               |
| PR15. Inventario de artefactos genéricos y concretos de aceleración de implementación         |               |
| PR16. Análisis de impacto y modelos actualizados de los ítems de arquitectura                 |               |
| PR17. Ítems de arquitectura incrementados en ejecución                                        |               |

<br>

| PRY03                                                                                                      | Documentación |
|------------------------------------------------------------------------------------------------------------|---------------|
| PR20. Documentación de estructuración y gestión de proyectos hoja de ruta E-Service por implementar        |               |
| PR21. Aprobación de inicio de los proyectos de la hoja de ruta E-Service                                   |               |
| PR22. Plan de trabajo de los proyectos de la hoja de ruta E-Service                                        |               |
| PR23. Listados de recursos, roles y personas requeridas por los proyectos de la hoja de ruta E-Service |               |
| PR24. Arquitectura de solución de los proyectos de cierre de brecha                                        |               |
| PR25. Ficha de proyectos hoja de ruta E-Service. Incremento 1                                              |               |
| PR26. Ficha de proyectos hoja de ruta E-Service. Incremento 2                                              |               |

<br>


## Costo Beneficio (aproximado)
…

<br>

## Consideraciones
…


## EDT


## Referencias {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
