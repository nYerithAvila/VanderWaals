# <h1 align="center">El equipo Van der Waals te da la bienvenida 💧⚡</h2>

# Integrantes

| | |
|---|---|
| <img src="https://th.bing.com/th/id/R.3498a697daacd36a022374e953ffa2c8?rik=N40gucyWR2VIPg&riu=http%3a%2f%2fcneer.ier.unam.mx%2fassets%2fimages%2fandy-1-695x1043.jpeg&ehk=yyTue6Up62Phi0rhxtWQRxzRWP4wxflE0a8IMnPGPFE%3d&risl=&pid=ImgRaw&r=0" width="200"/> | **Andrea Amador (@ampea-cloud)**<br> Ingeniera en Energías Renovables enfocada en adquirir habilidades para el diseño de modelos estocásticos que permitan un desarrollo de sistemas energéticos justos, confiables y renovables💫<br><br> |
| <img src="https://media.licdn.com/dms/image/v2/D4E03AQF9NC4v5S30uw/profile-displayphoto-scale_400_400/B4EZs4EMLcGcAg-/0/1766172182283?e=1777507200&v=beta&t=Jif8PZgCvYB_AnJWSJMbX5cFMi3I47xsnrcLvbs0ha8" width="200"/> | **Germán Erreguín (@errage)**<br>Ingeniero en Energías renovables con énfasis en sistemas fotovoltaicos y energía Eólica. Eterno fan de la ciencia abierta y democratización del conocimiento. Trabajo por un mundo mejor a través de los ODS.<br><br>[LinkedIn](https://www.linkedin.com/in/germanerreguin) |
| <img src="https://i.pinimg.com/564x/e6/f9/f1/e6f9f1e6928a17539ea18c05c38144e1.jpg" width="200"/> | **Yerith Avila (@nYerithAvila)**<br>Estudiante de Química Farmacobiología y amante de la tecnología. Interesada en el análisis de datos y su aplicación a problemáticas sociales 💻🧪<br><br>[LinkedIn](https://www.linkedin.com/in/yerith-avila) |

---

# ODS elegido
**ODS 6: Agua Limpia y Saneamiento**

# Descripción breve del proyecto
En el presente proyecto encontrarás tableros interactivos donde resolvemos la pregunta central:

> *"Cuando los datos nos hablan sobre bancarrota hídrica, ¿Cuál es el impacto de nuestras acciones individuales y colectivas?"*

La idea central de nuestro proyecto consiste en crear un tablero interactivo que permita al usuario visualizar, a través de data storytelling, como sus hábitos cotidianos influyen directamente en la situación de bancarrota hídrica que vive actualmente México. 

Para cumplir con nuestro objetivo hicimos uso de herramientas de código abierto como Python, Quarto, Git, Visual Code Studio. Además utilizamos base de datos abiertos, entre ellos: 
[CONAGUA]()
[Agenda 2030]()
[Aqueduct Water Risk Atlas]()

# Coherencia narrativa

| Sección | Nombre | Descripción | Preguntas clave | Fuentes / Enfoque |
|--------|--------|------------|----------------|------------------|
| 1 | **Introducción** | Contextualiza al usuario del tablero sobre sus usos del agua en distintos ámbitos de la vida cotidiana. | _¿Cuál es la huella hídrica aproximada de mi estilo de vida?_ <br> _¿Qué impacto tengo ante este objetivo?_| Datos obtenidos a través de calculadoras hídricas |
| 2 | **Acción ascendente** | Expone las consecuencias del consumo hídrico desmoderado y sobreexplotación persistente de recursos hídricos: daños irreversibles en ecosistemas, aumento de sequías entre otros fenómenos extremos. | _¿Cómo ha afectado este estilo de vida a las reservas de agua y sus ecosistemas?_| Datos del INEGI y CONAGUA sobre ecosistemas, cuerpos de agua, embalses y acuíferos. Enfoque en el ODS 6.6 |
| 3 | **Clímax** | Define y evidencía situación de bancarrota hídrica en México, proyectando escenario hasta el año 2080 con mismos hábitos de consumo hídrico| _¿Qué pasará si persistimos con nuestros hábitos de consumo?_ <br> _¿Qué es la bancarrota hidrica?_ | Datos obtenidos de Aqueduct Risk Atlas, Portal de datos abiertos|
| 4 | **Acción descendente** | Presenta 4 propuestas de acción en las que el usuario puede participar para atender a rubros específicos de la problemática.| _Individualmente ¿Qué acciones específicas reducirían mi huella hídrica habitual?_ <br> _Colectivamente ¿Cómo es que las comunidades se han organizado para atender la problematica hídrica?_ <br> _Institucionalmente ¿Qué información tenemos acceso como ciudadanos? y Gubernamentalmente ¿Qué beneficios puntuales existen de invertir en seguridad hídrica?_ | Datos obtenidos de |
| 5 | **Desenlace** | Analiza el impacto de las acciones propuestas y cómo contribuyen a mejorar la situación hídrica y la relación con el entorno. Genera esperanza. | _¿Cómo impactan estas soluciones al cumplimiento del ODS 6?_ | Evaluación de impacto y sostenibilidad |

## Estructura del proyecto
**Carpeta data**: Se encuentran los datos abiertos utilizados por cada integrante del equipo para la visualizaciòn de gràficas y posteriormente del tablero.

**Carpeta dashboard**: Encontraràs en ella archivo .qmd que planea utilizar el equipo para integrar las diferentes etapas de visualizaciòn del tablero.

**Carpeta notebooks**: Encontraràs archivos .ipynb donde los integrantes del equipo Van der Waals se han dedicado a analizar y limpiar datos abiertos para despuès codificar su visualizaciòn. Su nomenclatura "00X_Introducciòn" es alusiva a la etapa de narrativa que se pretende abordar, leer màs sobre cada tema abordado por etapa en secciòn "Coherencia Narrativa" del READ.ME

**Archivo READ.ME**: Encontraràs integrantes del equipo, descripciòn general de pryecto,estructura, coherencia narrativa, metadatos y potencial de impacto.

**Archivo pyproject.toml**: Encontraràs dependencias necesarias para reproducir el espacio de trabajo ""VanderWalls" en tu servidor local.

**Archivo LICENSE**: La licencia Creative Commons Atribución 4.0 Internacional (CC BY 4.0) permite copiar, redistribuir, adaptar y transformar material, incluso comercialmente, siempre que se dé crédito adecuado al autor, se enlace a la licencia y se indiquen cambios.

**Archivo .gitignore**: Tiene como función principal evitar que los archivos de dependencias y configuración local se suban al repositorio remoto.

**Archivo python-version**: define qué versión específica de Python debe utilizarse en ese directorio.

**Archivo uv.lock**: Un gestor de paquetes rápido escrito en Rust), ya que garantiza la reproducibilidad exacta de las dependencias.

# Metadatos
Los metadatos se encuentran en un archivo txt.

# Potencial de impacto
A lo largo del tiempo, se ha reconocido que México enfrenta una crisis hídrica. No obstante, de acuerdo con el Global Water Bankruptcy Report 2026, este concepto resulta insuficiente para describir la magnitud del problema actual. Hoy hablamos de bancarrota hídrica, un estado en el que los sistemas hídricos han sobreexplotado su capital natural, rebasando puntos críticos de inflexión y comprometiendo su sostenibilidad a largo plazo.

En este contexto, nuestro tablero busca representar de manera clara e informada este nuevo panorama, facilitando la comprensión de una problemática compleja y urgente. Más allá de visibilizar la situación, el proyecto tiene como propósito evidenciar que la magnitud del desafío exige un enfoque colaborativo, en el que tanto las acciones individuales como colectivas desempeñan un papel fundamental en su mitigación.

Asimismo, se pretende destacar que existen múltiples áreas de oportunidad para incidir positivamente, promoviendo una toma de decisiones más consciente, informada y orientada hacia la sostenibilidad del recurso hídrico.

# Este proyecto fue desarrollado para participar en:

![Logo](https://tse4.mm.bing.net/th/id/OIP.DU7u4z4TgUDFvpiQM84ktwHaDt?rs=1&pid=ImgDetMain&o=7&rm=3)

