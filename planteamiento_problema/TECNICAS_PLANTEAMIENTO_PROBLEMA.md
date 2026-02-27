# Técnicas para el planteamiento de problemas

Para resolver problemas, es muy importante antes poder identificar y entender las causas que lo provocan ya que esto permite acotarlo y definirlo claramente. Identificar problemas requiere de estructura, analisis y colaboración para lograr distinguir los sintomas de una causa raíz.

Para resolver problemas existen diferentes técnicas, por ejemplo:

- **Five Whys**: La técnica de los 5 por qué, es una técnica interrogativa usada para explorar las relaciones entre las causas y efector de un problema particular.

  El objetivo de este método es determinar la causa raíz del problema a través de 5 iteraciones con la pregunta ¿por qué?.

  - **Ventajas**: La principal ventaja de la aproximación de los 5 por qué es ser altamente efectiva en escenarios de poca o mediana complejidad. Es una técnica simple y muy rápida, permite identificar las causas principales, es una técnica versatil y al enfocarse en las causas raiz, previene repetir la solución multiples veces.

  - **Limitaciones**: Su principal limitación es que cuando existen problemas complejos o que tienen multiples variables relacionadas, no aporta mucho valor. Es una técnica subjetiva, si la técnica es mal aplicada, puede que no resuelva los problemas de raiz. Depende mucho de realizar las preguntas correctas.

  - **Cuándo usarla**: Se debe usar cuando te enfrentas a un problema simple o de baja complejidad, donde la relación causa-efecto es directa y no se requiere un análisis estadístico profundo. Es ideal para situaciones reactivas en las que necesitas identificar rápidamente la causa raíz, especialmente cuando no se dispone de muchos datos o recursos para un análisis más exhaustivo. No es recomendable para problemas complejos, multifactoriales o sistémicos.

    **Ejemplo**: El sistema de ventas en línea de una tienda dejó de funcionar durante el Black Friday.

    - ¿Por qué? Porque el servidor principal se sobrecargó y dejó de responder.
    - ¿Por qué se sobrecargó el servidor? Porque hubo un tráfico mucho mayor al esperado y la infraestructura no estaba preparada.
    - ¿Por qué la infraestructura no estaba preparada? Porque no se realizó una prueba de carga previa al evento.
    - ¿Por qué no se realizó la prueba de carga? Porque el equipo de TI no tenía conocimiento de la magnitud esperada del tráfico.
    - ¿Por qué el equipo de TI no tenía esa información? Porque no hubo comunicación efectiva entre el área de marketing (que planeó la campaña) y el área técnica.

    **Causa raíz:** Falta de comunicación entre áreas clave para anticipar y preparar la infraestructura ante eventos de alta demanda.

  ![diagrama_five_whys](five_whys_diagram.png)

- **Diagrama de Ishikawa**: Es un diagrama causal que muestra las potenciales causas de un evento especifico y su efecto. Esta es una de las herramientas más usadas para la gestión de calidad.

  Este diagrama permite identificar muchas posibles causas de un problema, ordenandolas dentro de categorias.

  - **Ventajas**: Ayuda a visualizar de forma estructurada las causas principales y secundarias de un problema, evitando quedarse solo en los síntomas. Fomenta el análisis profundo y el trabajo en equipo al categorizar el *brainstorming* (por ejemplo, en personas, procesos, tecnología, etc.).

  - **Limitaciones**: Puede volverse visualmente desordenado y demasiado complejo si el problema tiene demasiadas causas menores. Además, no prioriza las causas ni muestra la magnitud del impacto de cada una, y no siempre distingue entre una simple correlación y una causalidad real.

  - **Cuándo usarla**: Se utiliza cuando el problema es claramente multifactorial y necesitas estructurar una sesión de lluvia de ideas. Es indicada cuando sospechas que la falla proviene de una combinación de áreas distintas y necesitas categorizarlas para no perder ninguna de vista.

    **Ejemplo**: La página web de inscripción de materias de la universidad se cae todos los semestres.

    ![diagram_fish_bone](fish_bone_diagram.png)

- **5W2H**: Es una herramienta de gestión usada para crear un plan de acción que pueda ser ejecutado de forma efectiva.Esta técnica es más especializada que la técnica **Five Whys** ya que agrega más preguntas.

  - **W**hat: ¿Qué necesita ser realizado?
  - **W**here: ¿Dónde necesita ser hecho o ejecutado?
  - **W**hen: ¿Cuándo inicia la actividad?
  - **W**ho: ¿Quién es el encargado de esta?
  - **W**hy: ¿Por qué necesita ser completada?
  - **H**ow: ¿Cómo debe ser llevada a cabo?
  - **H**ow much: ¿Cuánto costará?

    Esta herramienta funciona a través de formatos tipo *checklist* compuestas de las 7 preguntas. El objetivo principal de esto es eliminar las dudas sobre como es el progreso de una actividad, de esta manera se permite una ejecución clara y simple.
  
  - **Ventajas**: Es una herramienta extremadamente estructurada y exhaustiva. Asegura que no se pasen por alto detalles importantes al planificar o analizar una situación. Al ser un formato tipo lista de verificación, es fácil de entender, estandarizar y aplicar por cualquier miembro del equipo.

  - **Limitaciones**: Puede resultar una técnica demasiado rígida o burocrática para problemas muy simples o en entornos ágiles. Además, se enfoca mucho más en la operatividad y ejecución (el "qué" y el "cómo") que en el descubrimiento profundo de causas raíz de problemas muy complejos.

  - **Cuándo usarla**: Se debe utilizar cuando ya has diagnosticado el problema, ya tienes una solución en mente y necesitas pasar a la fase de ejecución. Es la técnica correcta cuando tu objetivo es crear un plan de acción libre de ambigüedades, asegurando que todos los involucrados sepan exactamente qué hacer, cuándo, cómo y con qué presupuesto.

    **Ejemplo**: Organizar un Hackathon en la facultad para practicar.

  ![diagram_5w2h](5W2H_diagram.png)

- **Árbol del problema**: El árbol de problema es una herramienta gráfica que permite establecer relaciones de causa y efecto. Esta técnica ayuda a estructurar en una jerarquía los problemas identificados.

  El árbol del problema, permite segregar el problema en diferentes causas, lo que permite priorización y enfoque de objetivos. Adicionalmente, permite identificar el problema central.

  - **Ventajas**: Su principal ventaja es que permite estructurar un problema complejo en partes manejables. Esta aproximación es colaborativa, requiere que todas las partes interesadas compartan la misma visión del problema. Se enfoca en las causas raiz del problema. Es fácil para ilustrar un problema.

  - **Limitaciones**: La principal limitación de esta técnica es sobre simplificar el problema omitiendo partes importantes y sobre todo esta técnica no permite dimensionar la magnitud de cada causa o efecto del problema lo cual hace dificil la priorización.

  - **Cuándo usarla**: Se utiliza en las fases iniciales de diseño de un proyecto, especialmente cuando necesitas comprender a fondo una situación problemática antes de definir soluciones. Es la opción adecuada cuando es importante definir un objetivo central claro y diferenciar los síntomas de las causas estructurales. Además, resulta útil cuando se requiere la participación de varios actores para construir una visión compartida del problema y priorizar intervenciones de manera informada.

    **Ejemplo**: Analizar el problema de "Alta deserción en el curso de Algoritmos".

  ![diagram_problem_tree](problem_tree_diagram.png)

- **Matriz DOFA**: Es un marco de trabajo estrategico que permite evaluar desde una organización, un producto y hasta un proyecto. En esta técnica se propone la identificación de las siguientes categorías:

  - **Debilidades**: Este hace parte del análisis interno y responde a la pregunta ¿Cuáles son las debilidades y desventajas?.
  - **Oportunidades**: Este hace parte del análisis interno y responde a la pregunta ¿Qué oportunidades se pueden explotar?.
  - **Fortalezas**: Este hace parte del análisis externo y reponde a la pregunta ¿Cuáles son las fortalezas y ventajas?.
  - **Amenazas**: Este hace parte del análisis externo y response a la pregunta ¿Cuáles son las amenazas y obstaculos que pueden afectar negativamente su evolución?

  Luego de identificar cada uno de estos puntos, se generan estrategias agrupando categorías:

  - **Estrategias y acciones FO**: Conducen a la potencialización de las fortalezas internas con el objetivo de aprovechar las oportunidades externas.
  - **Estrategias y acciones DO**: Estas se enfocan en mejorar una debilidad a partir de las oportunidades identificadas.
  - **Estrategias y acciones DA**: Su enfoque es minimizar el peligro potencial donde las debilidades se encuentran con las amenazas.
  - **Estrategias y acciones FA**: Están dirigidas a prevenir el impacto de las amenazas a partir de las fortalezas existentes.

  - **Ventajas**: Proporciona una visión integral al cruzar factores internos de control propio (fortalezas y debilidades) con factores externos del entorno (oportunidades y amenazas). Facilita la toma de decisiones al permitir formular estrategias accionables de forma directa basadas en el cruce de categorías.

  - **Limitaciones**: Tiende a ser un análisis muy subjetivo, fuertemente influenciado por los sesgos de quienes lo elaboran. Frecuentemente produce listas de factores sin una priorización clara ni ponderación matemática de su impacto real. Si no se respalda con datos cuantitativos, puede quedarse en un análisis superficial.

  - **Cuándo usarla**: Se usa en la fase de planeación estratégica. Es indispensable cuando necesitas evaluar el estado actual de un proyecto, producto u organización antes de tomar una decisión importante, obligándote a mirar tanto el panorama interno como el entorno externo.

    **Ejemplo**: Un estudiante está decidiendo si debería invertir sus vacaciones en aprender un lenguaje de programación nuevo y difícil.

  ![diagram_dofa](DOFA_diagram.png)

- **Mapa del problema**: Esta técnica es utilizada para mapear las relaciones causales de un problema complejo. Su objetivo no es representar un problema perfectamente, sino dar una claridad y sintesis sobre el problema inicial a través de sus posibles causas.

  Para realizar un mapa de las causas de un problema es necesario seguir los siguientes pasos:

  - **Tormenta de ideas para causas primarias y conceptos**: Se trata de definir las principales causas que generan el problema identificado.
  - **Tormenta de ideas para causas secundarias**: El objetivo de este paso es identificar aquellas causas que provocan las causas de primer orden.
  - **Agregar interrelaciones entre las causas**: En este paso se interrelacionan las diferentes causas, incluyendo relaciones entre causas de segundo orden.

  - **Ventajas**: La principal ventaja de esta aproximación es poder dar manejo a problemas complejos, identificando las causas raiz y las relaciones entre las causas. Permite visualizar facilmente la complejidad del problema, Es fácil de entender el problema a través de sus relaciones, expone las areas en las cuales debe existir una investigación o mejora.

  - **Limitaciones**: Su principal desventaja es que toma mucho tiempo en construir el mapa con todas las posibles relaciones entre las causas, es un diagrama muy subjetivo. Si se aplica mal, el diagrama puede volverse muy complejo para una visión rápida del problema. Hay un riesgo alto de caer en la generalización del problema o sus causas.

  - **Cuándo usarla**: Se debe usar cuando te enfrentes a problemas sistémicos, caóticos o altamente complejos. Es especialmente útil cuando sabes que las causas no son aisladas, sino que están interconectadas y pueden formar ciclos o bucles de retroalimentación. Esta técnica resulta recomendable cuando el equipo necesita una visión global y estructurada del problema antes de priorizar acciones o intervenciones.

    **Ejemplo**: Analizar el agotamiento extremo en los estudiantes de último semestre.

  ![diagram_problem_mapping](problem_mapping_diagram.png)

## Referencias

- [Five Whys](https://en.wikipedia.org/wiki/Five_whys)
- [Problem Solving](https://asq.org/quality-resources/problem-solving)
- [Ishikawa diagram](https://en.wikipedia.org/wiki/Ishikawa_diagram)
- [10 methods of Problem Exploration](https://pavansoni.medium.com/10-methods-of-problem-exploration-a12b4cd1fbb8)
- [Fish bone](https://asq.org/quality-resources/fishbone?srsltid=AfmBOoopYRo3ETL1wZA21HAynu_2PJ-QcTX89nKfOyoaVoPZ-rTv-SQu)
- [Problem Tree](https://mspguide.org/2022/03/18/problem-tree/)
- [Problem Tree And Objective Tree](https://wikis.ec.europa.eu/spaces/ExactExternalWiki/pages/50109060/Problem+and+objective+tree)
- [Guia DOFA](http://www.odontologia.unal.edu.co/docs/claustros-colegiaturas_2013-2015/Guia_Analisis_DOFA.pdf)
- [Problem mapping](https://bryanlindsley.com/simple-guide-problem-mapping/)
