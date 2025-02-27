---
title: Árbol de decisión
markmap:
  colorFreezeLevel: 3
  embedAssets: true
  maxWidth: 300
  initialExpandLevel: 1
  
---

# Árbol de decisión
## ¿Desea desarrollar una solución basada en IA? ¿En qué fase se encuentra?

### Planificación y diseño 
- ¿Las hipótesis iniciales o las suposiciones del proyecto han sido revisadas críticamente para evitar que influyan de manera sesgada en los datos o las decisiones? 
  - Si  
    - ¿El diseño del sistema considera cómo los usuarios podrían interactuar de manera sesgada hacia ciertos géneros, y se han implementado medidas para mitigar estos patrones? 
      - Si
         - ¿El diseño de la interfaz o sistema contempla las necesidades y experiencias de todos los géneros, asegurando una experiencia inclusiva y equitativa?
           - Si
             - ¿El sistema es igualmente accesible y útil para personas de todos los géneros, incluidas aquellas con identidades no binarias o en contextos diversos?
               - Si
                 - ¿Se han considerado las realidades culturales y de género del contexto en el que se aplica la solución, asegurando que los resultados sean culturalmente sensibles y equitativos?
                   - Si
                     - ¿El modelo aborda adecuadamente las particularidades de género del dominio en el que se aplica, evitando generalizaciones que puedan afectar a ciertos géneros?
                       - Si 
                         - ¿El propósito del modelo se ha evaluado para garantizar que no genere impactos desproporcionados o perjudiciales para ciertos géneros?
                           - Si
                             - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
                           - No
                             - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda involucrar a expertos en género, comunidades locales y otros actores relevantes para identificar necesidades específicas y cómo el sistema puede impactar a diferentes géneros en el contexto. Herramientas: [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
                       - No
                         - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar cómo el modelo aplica sus predicciones en el dominio específico, ajustar parámetros según las necesidades. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                   - No
                     - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar análisis cultural del modelo en el contexto específico, colaborar con expertos locales y ajustar los resultados para reflejar las dinámicas culturales. Herramientas: Análisis cualitativo con expertos, encuestas culturales, [What-If Tool](https://pair-code.github.io/what-if-tool/get-started/)
               - No 
                 - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar auditorías de accesibilidad desde una perspectiva de género, implementar mejoras en el diseño y garantizar estándares de accesibilidad universal. Herramientas: [Aequitas](https://github.com/dssg/aequitas), [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
           - No 
             - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda evaluar el diseño con grupos diversos, realizar pruebas de usabilidad enfocadas en equidad de género y ajustar elementos de diseño para garantizar neutralidad. Herramientas: [UserZoom](https://www-usertesting-com.translate.goog/platform/userzoom?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc), [UserTesting](https://www-usertesting-com.translate.goog/)
      - No 
         - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda monitorear las interacciones de los usuarios en tiempo real, ajustar las recomendaciones y resultados basados en patrones de uso y sensibilizar a los usuarios sobre interacciones responsables. Herramientas: [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
  - No
     - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar críticamente las hipótesis iniciales con un panel diverso, realizar validaciones externas e incluir perspectivas inclusivas en las decisiones.Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/).

### Recopilación y tratamiento de datos
- ¿Los datos utilizados reflejan de manera equitativa y proporcional a todos los géneros, incluidos aquellos históricamente subrepresentados o con identidades diversas?
  - Si
    - ¿El proceso de selección de datos evita privilegiar estereotipos o características específicas asociadas a ciertos géneros, y se basa en criterios inclusivos y objetivos?
      - Si
        - ¿Se han identificado y mitigado patrones o roles de género perpetuados en los datos que podrían trasladar desigualdades pasadas al modelo?
          - Si
            - ¿Se han revisado los datos para garantizar que no excluyan representaciones importantes de géneros diversos o minoritarios?
              - Si
                - ¿Las hipótesis iniciales o las suposiciones del proyecto han sido revisadas críticamente para evitar que influyan de manera sesgada en los datos o las decisiones?
                  - Si
                    - ¿Se están buscando y considerando activamente evidencias que desafíen suposiciones previas relacionadas con género, en lugar de reforzar estereotipos existentes? 
                      - Si
                        - ¿La solución garantiza que todas las personas, independientemente de su género, tengan igual acceso, participación y representación en las interacciones con el sistema?
                          - Si
                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
                          - No
                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar encuestas de satisfacción segmentadas por género, identificar barreras de acceso y mejorar el diseño para garantizar una experiencia inclusiva. Herramientas: [Qualtrics](https://www.qualtrics.com/es/plataforma/), [UserTesting](https://www-usertesting-com.translate.goog/)
                      - No
                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda ampliar el análisis a contextos y escenarios que cuestionen las creencias previas, usar datos contrafactuales y validar los resultados para garantizar la neutralidad. Herramientas: [What-If Tool (Google)](https://pair-code.github.io/what-if-tool/get-started/),  [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                  - No 
                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar críticamente las hipótesis iniciales con un panel diverso, realizar validaciones externas e incluir perspectivas inclusivas en las decisiones. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
              - No
                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda analizar los datos en busca de exclusiones intencionales o accidentales, incluir datos adicionales que reflejen mejor la diversidad de género y realizar auditorías de inclusión. Herramientas:  [Pandas Profiling](https://www.geeksforgeeks.org/pandas-profiling-in-python/), [Google Dataset Search](https://datasetsearch.research.google.com/help)
          - No
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda auditar los datos para identificar tendencias históricas sesgadas, reentrenar el modelo con datos actuales o ajustados y validar que los resultados reflejen equidad actual. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
      - No
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar y ajustar los criterios de selección para garantizar neutralidad, así como auditar los datos seleccionados para identificar patrones sesgados. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
  - No
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar un análisis de distribución de datos para identificar grupos subrepresentados, ampliar la recolección de datos de fuentes diversas y aplicar técnicas de balanceo o re-pesado para corregir desbalances en los datos. Herramientas:  [Fairlearn](https://github.com/markmap/coc-markmap),  [Pandas Profiling](https://www.geeksforgeeks.org/pandas-profiling-in-python/),  [Aequitas](https://github.com/dssg/aequitas)

### Creación de modelo(s) y/o adaptación de modelo(s)
- ¿Los datos utilizados reflejan de manera equitativa y proporcional a todos los géneros, incluidos aquellos históricamente subrepresentados o con identidades diversas? 
  - Si 
    - ¿El proceso de selección de datos evita privilegiar estereotipos o características específicas asociadas a ciertos géneros, y se basa en criterios inclusivos y objetivos?
      - Si
        - ¿Se han identificado y mitigado patrones o roles de género perpetuados en los datos que podrían trasladar desigualdades pasadas al modelo?
          - Si
            - ¿Se han revisado los datos para garantizar que no excluyan representaciones importantes de géneros diversos o minoritarios?
              - Si
                - ¿El modelo ha sido evaluado en contextos específicos relacionados con género para garantizar que cumple con las expectativas sin generar resultados sesgados?
                  - Si 
                    - ¿Se valida que el modelo sea aplicable a contextos con dinámicas de género diferentes al original, y se ajusta para reflejar esas diferencias?
                      - Si
                        - ¿Se han considerado las realidades culturales y de género del contexto en el que se aplica la solución, asegurando que los resultados sean culturalmente sensibles y equitativos?
                          - Si 
                            - ¿El modelo aborda adecuadamente las particularidades de género del dominio en el que se aplica, evitando generalizaciones que puedan afectar a ciertos géneros?
                              - Si
                                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
                              - No 
                                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar cómo el modelo aplica sus predicciones en el dominio específico, ajustar parámetros según las necesidades. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                          - No 
                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar análisis cultural del modelo en el contexto específico, colaborar con expertos locales y ajustar los resultados para reflejar las dinámicas culturales. Herramientas:  [AI Fairness 360](https://aif360.readthedocs.io/en/stable/),  [Fairlearn](https://github.com/markmap/coc-markmap)
                      - No
                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar pruebas de transferencia en el nuevo contexto, ajustar los parámetros del modelo y validar que los resultados reflejen dinámicas de género locales. Herramientas:   [AI Fairness 360](https://aif360.readthedocs.io/en/stable/),  [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
                  - No 
                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda probar el modelo en escenarios específicos de género, ajustar parámetros para mejorar el desempeño en esos contextos y realizar validaciones periódicas. Herramientas: [What-If Tool](https://pair-code.github.io/what-if-tool/get-started/), [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
              - No 
                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda analizar los datos en busca de exclusiones intencionales o accidentales, incluir datos adicionales que reflejen mejor la diversidad de género y realizar auditorías de inclusión. Herramientas:  [Pandas Profiling](https://www.geeksforgeeks.org/pandas-profiling-in-python/), [Google Dataset Search](https://datasetsearch.research.google.com/help)
          - No 
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda auditar los datos para identificar tendencias históricas sesgadas, reentrenar el modelo con datos actuales o ajustados y validar que los resultados reflejen equidad actual. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
      - No
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar y ajustar los criterios de selección para garantizar neutralidad, así como auditar los datos seleccionados para identificar patrones sesgados. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/) 
  - No 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar un análisis de distribución de datos para identificar grupos subrepresentados, ampliar la recolección de datos de fuentes diversas y aplicar técnicas de balanceo o re-pesado para corregir desbalances en los datos. Herramientas:  [Fairlearn](https://github.com/markmap/coc-markmap),  [Pandas Profiling](https://www.geeksforgeeks.org/pandas-profiling-in-python/),  [Aequitas](https://github.com/dssg/aequitas)

### Prueba, evaluación, verificación y validación
- ¿Las hipótesis iniciales o las suposiciones del proyecto han sido revisadas críticamente para evitar que influyan de manera sesgada en los datos o las decisiones?
  - Si
    - ¿Se están buscando y considerando activamente evidencias que desafíen suposiciones previas relacionadas con género, en lugar de reforzar estereotipos existentes?
      - Si 
        - ¿Los resultados del modelo están siendo interpretados de manera que eviten perpetuar estereotipos o ideas preconcebidas sobre roles de género?
          - Si 
            - ¿El diseño del sistema considera cómo los usuarios podrían interactuar de manera sesgada hacia ciertos géneros, y se han implementado medidas para mitigar estos patrones?
              - Si
                - ¿La solución garantiza que todas las personas, independientemente de su género, tengan igual acceso, participación y representación en las interacciones con el sistema?
                  - Si
                    - ¿El diseño de la interfaz o sistema contempla las necesidades y experiencias de todos los géneros, asegurando una experiencia inclusiva y equitativa?
                      - Si
                        - ¿El sistema es igualmente accesible y útil para personas de todos los géneros, incluidas aquellas con identidades no binarias o en contextos diversos?
                          - Si
                            - ¿El modelo ha sido evaluado en contextos específicos relacionados con género para garantizar que cumple con las expectativas sin generar resultados sesgados?
                              - Si
                                - ¿Se monitorean las salidas del sistema para identificar si refuerzan patrones sesgados de género, y se aplican correcciones cuando es necesario?
                                  - Si
                                    - ¿El modelo evita amplificar desigualdades o estereotipos de género existentes en los datos o interacciones del sistema?
                                      - Si
                                        - ¿Las adaptaciones del sistema consideran posibles sesgos de género en los datos y resultados, y se ajustan para evitar perpetuar errores o desigualdades?
                                          - Si 
                                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
                                          - No 
                                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar los procesos de adaptación automática del sistema, establecer reglas para detectar adaptaciones sesgadas y ajustar el modelo según sea necesario. Herramientas: [Google AutoML](https://www-run-ai.translate.goog/guides/automl/google-automl?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc), [herramientas de MLOps](https://www.purestorage.com/knowledge/mlops-tools.html)
                                      - No
                                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda analizar las predicciones para identificar amplificaciones no deseadas, reentrenar el modelo si se detectan patrones sesgados y validar los resultados con datos ajustados. Herramientas: [What-If Tool](https://pair-code.github.io/what-if-tool/get-started/), [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                                  - No 
                                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda monitorear los resultados del sistema periódicamente, identificar patrones sesgados y ajustar el modelo para corregir retroalimentaciones negativas. Herramientas: [MLOps dashboards](https://github.com/SumoLogic-Labs/MLOPs-Dashboards), [Aequitas](https://github.com/dssg/aequitas)
                              - No
                                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda probar el modelo en escenarios específicos de género, ajustar parámetros para mejorar el desempeño en esos contextos y realizar validaciones periódicas. Herramientas: [What-If Tool](https://pair-code.github.io/what-if-tool/get-started/), [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                          - No
                            -  De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar auditorías de accesibilidad desde una perspectiva de género, implementar mejoras en el diseño y garantizar estándares de accesibilidad universal. Herramientas: [Aequitas](https://github.com/dssg/aequitas), [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
                      - No 
                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda evaluar el diseño con grupos diversos, realizar pruebas de usabilidad enfocadas en equidad de género y ajustar elementos de diseño para garantizar neutralidad. Herramientas: [UserZoom](https://www-usertesting-com.translate.goog/platform/userzoom?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc), [UserTesting](https://www-usertesting-com.translate.goog/)
                  - No
                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar encuestas de satisfacción segmentadas por género, identificar barreras de acceso y mejorar el diseño para garantizar una experiencia inclusiva. Herramientas: [Qualtrics](https://www.qualtrics.com/es/plataforma/), [UserTesting](https://www-usertesting-com.translate.goog/)
              - No 
                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda monitorear las interacciones de los usuarios en tiempo real, ajustar las recomendaciones y resultados basados en patrones de uso y sensibilizar a los usuarios sobre interacciones responsables. Herramientas: [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
          - No
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar los resultados con observadores externos, usar explicabilidad para justificar decisiones de IA y detectar posibles sesgos en la interpretación. Herramientas:  [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
      - No 
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda ampliar el análisis a contextos y escenarios que cuestionen las creencias previas, usar datos contrafactuales y validar los resultados para garantizar la neutralidad. Herramientas: [What-If Tool (Google)](https://pair-code.github.io/what-if-tool/get-started/),  [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
  - No
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar críticamente las hipótesis iniciales con un panel diverso, realizar validaciones externas e incluir perspectivas inclusivas en las decisiones.  Herramientas:[Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
### Entrada en servicio/despliegue
- ¿La solución garantiza que todas las personas, independientemente de su género, tengan igual acceso, participación y representación en las interacciones con el sistema?
  - Si 
    - ¿El diseño de la interfaz o sistema contempla las necesidades y experiencias de todos los géneros, asegurando una experiencia inclusiva y equitativa?
      - Si
        - ¿Las decisiones durante la implementación consideran posibles impactos desiguales entre géneros, y se toman medidas para garantizar resultados equitativos?
          - Si
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
          - No
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar las decisiones de implementación con un enfoque inclusivo, realizar auditorías técnicas y éticas y garantizar la participación de expertos en género. Herramientas: [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
      - No
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda evaluar el diseño con grupos diversos, realizar pruebas de usabilidad enfocadas en equidad de género y ajustar elementos de diseño para garantizar neutralidad. Herramientas:[UserZoom](https://www-usertesting-com.translate.goog/platform/userzoom?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc), [UserTesting](https://www-usertesting-com.translate.goog/)
  - No 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar encuestas de satisfacción segmentadas por género, identificar barreras de acceso y mejorar el diseño para garantizar una experiencia inclusiva. Herramientas: [Qualtrics](https://www.qualtrics.com/es/plataforma/), [UserTesting](https://www-usertesting-com.translate.goog/)

### Explotación y supervisión (Monitoreo y ajuste)
- ¿Se monitorean las salidas del sistema para identificar si refuerzan patrones sesgados de género, y se aplican correcciones cuando es necesario?
  - Si 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
  - No
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda monitorear los resultados del sistema periódicamente, identificar patrones sesgados y ajustar el modelo para corregir retroalimentaciones negativas. Herramientas: [MLOps dashboards](https://github.com/SumoLogic-Labs/MLOPs-Dashboards), [Aequitas](https://github.com/dssg/aequitas)

### Retirada/desmantelamiento
- ¿La retirada del sistema afecta el acceso a ciertos géneros o grupos subrepresentados?
  - Si 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
  - No 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Realizar auditorías para identificar qué grupos dependen del sistema y asegurar alternativas de acceso antes de la retirada. Herramientas:  [Aequitas](https://github.com/dssg/aequitas),  [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
    
## ¿Desea adquirir una IA? ¿En qué fase se encuentra?

### Planificación y análisis inicial 
- ¿Los resultados del modelo están siendo interpretados de manera que eviten perpetuar estereotipos o ideas preconcebidas sobre roles de género?
  - Si 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
  - No
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar los resultados con observadores externos, usar explicabilidad para justificar decisiones de IA y detectar posibles sesgos en la interpretación. Herramientas:  [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)

### Evaluación y selección de soluciones
- ¿Los datos utilizados reflejan de manera equitativa y proporcional a todos los géneros, incluidos aquellos históricamente subrepresentados o con identidades diversas?
  - Si
    - ¿El proceso de selección de datos evita privilegiar estereotipos o características específicas asociadas a ciertos géneros, y se basa en criterios inclusivos y objetivos?
      - Si 
        - ¿Se han identificado y mitigado patrones o roles de género perpetuados en los datos que podrían trasladar desigualdades pasadas al modelo?
          - Si 
            - ¿Se han revisado los datos para garantizar que no excluyan representaciones importantes de géneros diversos o minoritarios?
              - Si 
                - ¿Las hipótesis iniciales o las suposiciones del proyecto han sido revisadas críticamente para evitar que influyan de manera sesgada en los datos o las decisiones?
                  - Si 
                    - ¿Se están buscando y considerando activamente evidencias que desafíen suposiciones previas relacionadas con género, en lugar de reforzar estereotipos existentes?
                      - Si 
                        - ¿Se valida que el modelo sea aplicable a contextos con dinámicas de género diferentes al original, y se ajusta para reflejar esas diferencias?
                          - Si 
                            - ¿Se han considerado las realidades culturales y de género del contexto en el que se aplica la solución, asegurando que los resultados sean culturalmente sensibles y equitativos?
                              - Si 
                                - ¿El modelo aborda adecuadamente las particularidades de género del dominio en el que se aplica, evitando generalizaciones que puedan afectar a ciertos géneros?
                                  - Si
                                    - ¿El propósito del modelo se ha evaluado para garantizar que no genere impactos desproporcionados o perjudiciales para ciertos géneros?
                                      - Si
                                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
                                      - No 
                                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Involucrar a expertos en género, comunidades locales y otros actores relevantes para identificar necesidades específicas y cómo el sistema puede impactar a diferentes géneros en el contexto. Herramientas: [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
                                  - No 
                                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar cómo el modelo aplica sus predicciones en el dominio específico, ajustar parámetros según las necesidades. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                              - No 
                                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar análisis cultural del modelo en el contexto específico, colaborar con expertos locales y ajustar los resultados para reflejar las dinámicas culturales. Herramientas:  [AI Fairness 360](https://aif360.readthedocs.io/en/stable/),  [Fairlearn](https://github.com/markmap/coc-markmap)
                          - No
                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar pruebas de transferencia en el nuevo contexto, ajustar los parámetros del modelo y validar que los resultados reflejen dinámicas de género locales. Herramientas:   [AI Fairness 360](https://aif360.readthedocs.io/en/stable/),  [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
                      - No 
                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda ampliar el análisis a contextos y escenarios que cuestionen las creencias previas, usar datos contrafactuales y validar los resultados para garantizar la neutralidad. Herramientas: [What-If Tool (Google)](https://pair-code.github.io/what-if-tool/get-started/),  [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                  - No 
                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar críticamente las hipótesis iniciales con un panel diverso, realizar validaciones externas e incluir perspectivas inclusivas en las decisiones. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)

              - No
                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda analizar los datos en busca de exclusiones intencionales o accidentales, incluir datos adicionales que reflejen mejor la diversidad de género y realizar auditorías de inclusión. Herramientas:  [Pandas Profiling](https://www.geeksforgeeks.org/pandas-profiling-in-python/), [Google Dataset Search](https://datasetsearch.research.google.com/help)
          - No 
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda auditar los datos para identificar tendencias históricas sesgadas, reentrenar el modelo con datos actuales o ajustados y validar que los resultados reflejen equidad actual. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
      - No 
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar y ajustar los criterios de selección para garantizar neutralidad, así como auditar los datos seleccionados para identificar patrones sesgados. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html), [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)
  - No
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar un análisis de distribución de datos para identificar grupos subrepresentados, ampliar la recolección de datos de fuentes diversas y aplicar técnicas de balanceo o re-pesado para corregir desbalances en los datos. Herramientas:  [Fairlearn](https://github.com/markmap/coc-markmap),  [Pandas Profiling](https://www.geeksforgeeks.org/pandas-profiling-in-python/),  [Aequitas](https://github.com/dssg/aequitas)

### Implementación e integración
- ¿El diseño del sistema considera cómo los usuarios podrían interactuar de manera sesgada hacia ciertos géneros, y se han implementado medidas para mitigar estos patrones?
  - Si 
    - ¿Las decisiones durante la implementación consideran posibles impactos desiguales entre géneros, y se toman medidas para garantizar resultados equitativos?
      - Si
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
      - No 
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar las decisiones de implementación con un enfoque inclusivo, realizar auditorías técnicas y éticas y garantizar la participación de expertos en género. Herramientas: [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
  - No 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda monitorear las interacciones de los usuarios en tiempo real, ajustar las recomendaciones y resultados basados en patrones de uso y sensibilizar a los usuarios sobre interacciones responsables. Herramientas: [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)

### Explotación y supervisión
- ¿Se están buscando y considerando activamente evidencias que desafíen suposiciones previas relacionadas con género, en lugar de reforzar estereotipos existentes?
  - Si
    - ¿Los resultados del modelo están siendo interpretados de manera que eviten perpetuar estereotipos o ideas preconcebidas sobre roles de género?
      - Si
        - ¿La solución garantiza que todas las personas, independientemente de su género, tengan igual acceso, participación y representación en las interacciones con el sistema?
          - Si 
            - ¿El diseño de la interfaz o sistema contempla las necesidades y experiencias de todos los géneros, asegurando una experiencia inclusiva y equitativa?
              - Si 
                - ¿El sistema es igualmente accesible y útil para personas de todos los géneros, incluidas aquellas con identidades no binarias o en contextos diversos?
                  - Si
                    - ¿El modelo ha sido evaluado en contextos específicos relacionados con género para garantizar que cumple con las expectativas sin generar resultados sesgados?
                      - Si
                        - ¿Las decisiones durante la implementación consideran posibles impactos desiguales entre géneros, y se toman medidas para garantizar resultados equitativos?
                          - Si 
                            - ¿Se monitorean las salidas del sistema para identificar si refuerzan patrones sesgados de género, y se aplican correcciones cuando es necesario?
                              - Si 
                                - ¿El modelo evita amplificar desigualdades o estereotipos de género existentes en los datos o interacciones del sistema?
                                  - Si 
                                    - ¿Las adaptaciones del sistema consideran posibles sesgos de género en los datos y resultados, y se ajustan para evitar perpetuar errores o desigualdades?
                                      - Si 
                                        - ¿Se valida que el modelo sea aplicable a contextos con dinámicas de género diferentes al original, y se ajusta para reflejar esas diferencias?
                                          - Si
                                            - ¿Se han considerado las realidades culturales y de género del contexto en el que se aplica la solución, asegurando que los resultados sean culturalmente sensibles y equitativos?
                                              - Si
                                                - ¿El modelo aborda adecuadamente las particularidades de género del dominio en el que se aplica, evitando generalizaciones que puedan afectar a ciertos géneros?
                                                  - Si 
                                                    - ¿El propósito del modelo se ha evaluado para garantizar que no genere impactos desproporcionados o perjudiciales para ciertos géneros?
                                                      - Si 
                                                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
                                                      - No 
                                                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Involucrar a expertos en género, comunidades locales y otros actores relevantes para identificar necesidades específicas y cómo el sistema puede impactar a diferentes géneros en el contexto. Herramientas: [AI Fairness 360](https://aif360.readthedocs.io/en/stable/)    
                                                  - No  
                                                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar cómo el modelo aplica sus predicciones en el dominio específico, ajustar parámetros según las necesidades. Herramientas: [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)  
                                              - No
                                                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar análisis cultural del modelo en el contexto específico, colaborar con expertos locales y ajustar los resultados para reflejar las dinámicas culturales. Herramientas:    [AI Fairness 360](https://aif360.readthedocs.io/en/stable/),  [Fairlearn](https://github.com/markmap/coc-markmap)       
                                          - No 
                                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar pruebas de transferencia en el nuevo contexto, ajustar los parámetros del modelo y validar que los resultados reflejen dinámicas de género locales.
                                              Herramientas:   [AI Fairness 360](https://aif360.readthedocs.io/en/stable/),  [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
                                      - No 
                                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar los procesos de adaptación automática del sistema, establecer reglas para detectar adaptaciones sesgadas y ajustar el modelo según sea necesario. Herramientas: [Google AutoML](https://www-run-ai.translate.goog/guides/automl/google-automl?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc), [herramientas de MLOps](https://www.purestorage.com/knowledge/mlops-tools.html) 
                                  - No 
                                    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda analizar las predicciones para identificar amplificaciones no deseadas, reentrenar el modelo si se detectan patrones sesgados y validar los resultados con datos ajustados. Herramientas: [What-If Tool](https://pair-code.github.io/what-if-tool/get-started/), [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                              - No 
                                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda monitorear los resultados del sistema periódicamente, identificar patrones sesgados y ajustar el modelo para corregir retroalimentaciones negativas.
                                Herramientas: [MLOps dashboards](https://github.com/SumoLogic-Labs/MLOPs-Dashboards), [Aequitas](https://github.com/dssg/aequitas)
                          - No
                            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar las decisiones de implementación con un enfoque inclusivo, realizar auditorías técnicas y éticas y garantizar la participación de expertos en género. Herramientas:  [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)
                      - No
                        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda probar el modelo en escenarios específicos de género, ajustar parámetros para mejorar el desempeño en esos contextos y realizar validaciones periódicas. Herramientas:[What-If Tool](https://pair-code.github.io/what-if-tool/get-started/), [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html)
                  - No 
                    -  De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar auditorías de accesibilidad desde una perspectiva de género, implementar mejoras en el diseño y garantizar estándares de accesibilidad universal. Herramientas: [Aequitas](https://github.com/dssg/aequitas), [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
              - No 
                - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda evaluar el diseño con grupos diversos, realizar pruebas de usabilidad enfocadas en equidad de género y ajustar elementos de diseño para garantizar neutralidad. Herramientas: [UserZoom](https://www-usertesting-com.translate.goog/platform/userzoom?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc), [UserTesting](https://www-usertesting-com.translate.goog/)
          - No 
            - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda realizar encuestas de satisfacción segmentadas por género, identificar barreras de acceso y mejorar el diseño para garantizar una experiencia inclusiva. Herramientas: [Qualtrics](https://www.qualtrics.com/es/plataforma/), [UserTesting](https://www-usertesting-com.translate.goog/)
      - No 
        - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda revisar los resultados con observadores externos, usar explicabilidad para justificar decisiones de IA y detectar posibles sesgos en la interpretación. Herramientas:   [Fairlearn](https://github.com/markmap/coc-markmap), [Aequitas](https://github.com/dssg/aequitas)    
  - No
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Se recomienda ampliar el análisis a contextos y escenarios que cuestionen las creencias previas, usar datos contrafactuales y validar los resultados para garantizar la neutralidad. Herramientas: [What-If Tool (Google)](https://pair-code.github.io/what-if-tool/get-started/),  [Fairlearn](https://fairlearn.org/v0.11/api_reference/index.html) 
 

### Retirada o reemplazo de la solución
- ¿La retirada del sistema afecta el acceso a ciertos géneros o grupos subrepresentados?
  - Si
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como bajo o moderado. Se recomienda continuar implementando acciones proactivas para identificar, prevenir y mitigar posibles sesgos de género. Mantenga auditorías regulares, fomente la diversidad en su equipo de trabajo y utilice herramientas de análisis inclusivas para garantizar la equidad en el desarrollo o adquisición de su solución de IA.
  - No 
    - De acuerdo con las opciones seleccionadas, su nivel de riesgo se clasifica como alto. Realizar auditorías para identificar qué grupos dependen del sistema y asegurar alternativas de acceso antes de la retirada. Herramientas:  [Aequitas](https://github.com/dssg/aequitas),  [Fairness Indicators](https://github.com/tensorflow/fairness-indicators)
    
    
