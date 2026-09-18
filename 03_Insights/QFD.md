### Introducción
La Casa de la Calidad (House of Quality) es la herramienta implementada para traducir la necesidad del cliente en requisitos de diseño. En esta fase se establece el ritmo de todo el proceso: se identifican los requerimientos del usuario, se definen las características técnicas que los satisfacen, se asignan valores objetivo y se compara el desempeño frente a la competencia.

Para el presente proyecto, la voz del cliente se obtuvo mediante una entrevista semiestructurada a la usuaria Wanda, quien sufrió un accidente de tránsito con fractura expuesta y conminuta del fémur derecho, diagnosticada además con osteopenia y con secuelas de acortamiento de extremidad (4 cm) y limitación del rango de flexión de rodilla (máximo 60°). Del mismo modo los requerimientos ya se encontraban definidos y trazables a partir de tres pilares: estabilidad y adaptabilidad, movilidad y autonomía y seguridad y protección (este último prioritario con peso 0,4). Estos pilares se desglosaron en un árbol de objetivos con pesos ponderados, del cual se derivaron los requerimientos del proyecto (RQ-01 a RQ-09), todos con criterios de verificación.

### Características Técnicas (Los "CÓMO" de nuestra casa):
| # | Característica técnica | Unidad | Requerimientos que atiende | Descripción |
|---|---|---|---|---|
| CT1 | Masa total del dispositivo | kg | RQ-05 | Debe ser liviana para evitar latigazo medial/lateral al levantar la ortesis y no añadir peso al usuario |
| CT2 | Rango de flexión de rodilla ajustable | grados | RQ-04, RQ-06 | Configurable al ángulo médico establecido; el prototipo debe permitir modificar el grado de flexión |
| CT3 | Altura de compensación ajustable | cm | RQ-01, RQ-03 | Variable según el usuario; el caso actual requiere 4 cm de compensación |
| CT4 | Durabilidad de materiales | años | RQ-05, RQ-07 | Mínimo 2 años de uso diario |
| CT5 | Costo de fabricación | USD | RQ-05 | Materiales adquiribles para una solución accesible |
| CT6 | Distribución de presión | índice (0-1) | RQ-07, RQ-08 | Uniforme, sin usar la rodilla como punto único de presión |
| CT7 | Amortiguación de impacto | J | RQ-08, RQ-09 | Capacidad de absorber y disipar cargas durante la marcha |

### Especificaciones Técnicas (Los "CUÁNTOS" de nuestra casa):
Los CUÁNTOS definen los valores objetivo de cada característica técnica, con valores ideales (deseables) y marginales (mínimos aceptables), fundamentados en estándares de ortesis de rodilla-tobillo-pie (KAFO)y dispositivos de asistencia.

| COMO | Unidad | Valor marginal | Valor ideal |
| :--- | :--- | :--- | :--- |
| CT1 Masa total | kg | ≤ 1,8 | ≤ 1,2 |
| CT2 Rango de flexión ajustable | grados |  ́0–60 |  ́0–90 (configurable fino) |
| CT3 Altura de compensación | cm | 1–6 |  ́0–8 (precisión 0,5) |
| CT4 Durabilidad | años | ≥ 1 | ≥ 2 (uso diario) |
| CT5 Costo de fabricación | USD | ≤ 180 | ≤ 120 |
| CT6 Distribución de presión | índice (0–1) | ≤ 0,6 | ≤ 0,4 (uniforme) |
| CT7 Amortiguación de impacto | J | ≥ 10 | ≥ 20 (absorción controlada) |

### Evaluación competitiva de requerimientos:
La evaluación competitiva compara, en escala de 1 a 5 (1 = pobre, 5 = excelente), el desempeño de la solución frente a las ortesis KAFO comerciales, considerando cada requerimiento del proyecto:
| Requerimiento | Nuestra solución | Ortesis comercial | Brecha |
| :--- | :--- | :--- | :--- |
| RQ-01 Adaptación anatómica | 4 | 3 | +1 |
| RQ-02 Compensar debilidad muscular | 4 | 3 | +1 |
| RQ-03 Equilibrio y alineación | 5 | 3 | +2 |
| RQ-04 Transferencia y descenso | 5 | 2 | +3 |
| RQ-05 Integración a cotidianidad | 4 | 3 | +1 |
| RQ-06 Reducir esfuerzo en marcha | 5 | 2 | +3 |
| RQ-07 Integridad cutánea | 4 | 3 | +1 |
| RQ-08 Amortiguación y manejo de cargas | 4 | 3 | +1 |
| RQ-09 Protección durante la marcha | 5 | 3 | +2 |

### Hallazgos frente a la competencia:
| Característica | Nuestra solución | Ortesis comercial | Grado de innovación |
| :--- | :--- | :--- | :--- |
| Control de flexión de rodilla | Sistema mecánico configurable que limita la flexión al ángulo médico establecido | La mayoría de KAFO ofrecen bloqueo fijo o ajuste básico; pocas permiten configuración fina del ángulo | Media (diferenciador parcial) |
| Compensación de discrepancia de longitud | Plantilla de grosor acorde a los cm de diferencia, integrada a la ortesis | Existen alzas y plantillas independientes, pero pocas integradas a una ortesis de rodilla-tobillo-pie | Alta (integración poco común) |
| Diseño ventilado | Recubrimiento lateral con caras anterior y posterior libres para transpiración | Muchas ortesis usan recubrimiento cerrado; las ventiladas son menos frecuentes | Media-alta (diferenciador) |
| Cobertura (muslo-pantorrilla-pie) | Recubre muslo, pantorrilla y pie con sujeción lateral | Cobertura completa común en KAFO, pero suele ser cerrada | Media (cobertura similar, diseño distinto) |
| Seguridad en marcha y agacharse | Compensa altura y limita flexión para seguridad en desplazamiento | Suelen enfocarse en una sola función | Alta (enfoque integral) |
| Reducción de agotamiento en larga distancia | Nivelación que reduce el esfuerzo físico | Pocas ortesis documentan este beneficio específico | Alta (beneficio poco abordado) |

### Lectura del análisis competitivo
**Ventajas competitivas de nuestra solución:**

- Enfoque integral (diferenciador de alta innovación): combina compensación de discrepancia de longitud, control configurable de flexión y diseño ventilado en una sola ortesis, frente a productos comerciales que atienden una sola función. Esto se refleja en la mayor brecha de desempeño en RQ-04 (transferencia y descenso, +3) y RQ-06 (reducción de esfuerzo en marcha, +3).

- Integración de la compensación de longitud: la plantilla integrada a la ortesis (rodilla-tobillo-pie) es poco común en el mercado, donde suelen usarse alzas independientes. Es el principal diferenciador estructural.

- Configuración fina del ángulo de flexión: a diferencia del bloqueo fijo o ajuste básico de la mayoría de KAFO, nuestro sistema permite adaptar el ángulo al valor médico establecido (60° en el caso de Wanda), lo que se traduce en ventaja en RQ-03 (equilibrio, +2) y RQ-09 (protección en marcha, +2).

### Áreas de paridad relativa (donde la ventaja es menor, +1): 
Adaptación anatómica, compensación muscular, integración a la cotidianidad, integridad cutánea y amortiguación. En estas, la competencia comercial también ofrece prestaciones aceptables, por lo que no son el principal argumento de diferenciación.

### Conclusión: 
La propuesta se posiciona como una solución integral y accesible que supera a las ortesis comerciales especialmente en las necesidades prioritarias de la usuaria —seguridad en marcha, reducción de esfuerzo y facilidad de movimiento—, que son precisamente los requerimientos vinculados a los pilares de mayor peso en el árbol de objetivos (seguridad y protección, 0,4; estabilidad y adaptabilidad, 0,3).
  
