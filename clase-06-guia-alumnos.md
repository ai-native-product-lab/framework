# Clase 6 — Aprender y decidir

## Guía paso a paso para alumnos

## Propósito de la clase

En las clases anteriores investigaron un problema, formularon hipótesis y construyeron un experimento para producir evidencia. En esta clase van a convertir resultados, observaciones, errores y dudas en una decisión.

> **Un resultado no es todavía un aprendizaje. Aprender es poder explicar qué ocurrió, qué podemos concluir, qué no podemos concluir y qué haremos después.**

No buscamos que todos los equipos hayan obtenido resultados favorables. Buscamos que todos puedan tomar una decisión honesta y trazable.

La inteligencia artificial puede ordenar datos, detectar contradicciones, calcular métricas y proponer explicaciones alternativas. El equipo debe verificar las fuentes, distinguir hechos de interpretaciones y tomar la decisión final.

> **La IA analiza y propone. El equipo valida y decide.**

---

## Objetivos

Al finalizar, cada equipo podrá:

- recuperar la hipótesis, métrica y criterio definidos antes de experimentar;
- ordenar los resultados sin eliminar errores, anomalías ni resultados contrarios;
- diferenciar evidencia, interpretación, supuesto y decisión;
- comparar el resultado real contra el criterio original;
- identificar limitaciones y explicaciones alternativas;
- decidir si corresponde avanzar, corregir, iterar, pivotar o actualizar el Canvas;
- practicar un pivot fundamentado sin borrar el recorrido anterior;
- dejar preparado el punto de partida para diseñar una solución en la Clase 7.

---

## La distinción central

| Concepto | Pregunta que responde | Ejemplo |
|---|---|---|
| **Evidencia** | ¿Qué ocurrió? | 3 de 20 personas hicieron clic. |
| **Interpretación** | ¿Qué podría significar? | El beneficio no fue suficientemente claro. |
| **Supuesto** | ¿Qué todavía no sabemos? | Las personas vieron y comprendieron el mensaje. |
| **Aprendizaje** | ¿Qué cambió en nuestra comprensión? | No podemos concluir interés sin separar exposición, comprensión y confianza. |
| **Decisión** | ¿Qué haremos ahora? | Probar comprensión antes de repetir el mismo mecanismo. |

> **Una explicación plausible no se convierte en evidencia sólo porque la escribió una IA.**

---

## Entradas necesarias

Antes de empezar, tengan disponibles:

- **lean-product-canvas.md** actualizado;
- **diseno-experimento.md**;
- **registro-experimento.md**;
- el enlace, archivo o acceso al instrumento utilizado;
- datos originales, capturas, notas, respuestas, observaciones y errores;
- la hipótesis, la métrica y el criterio de éxito definidos antes de probar.

Si el experimento no reunió suficientes resultados, también pueden trabajar. Deben poder explicar qué faltó, por qué faltó y qué sería necesario para llegar a una conclusión.

---

## Archivo de trabajo

Creen en el repositorio del equipo:

~~~
informe-aprendizaje-decision.md
~~~

No borren ni reemplacen los archivos de las clases anteriores. Este informe agrega una nueva capa de aprendizaje al historial del proyecto.

---

## Agenda de trabajo

| Paso | Actividad | Duración sugerida |
|---:|---|---:|
| 1 | Recuperar el contrato experimental | 10 min |
| 2 | Ordenar la evidencia producida | 15 min |
| 3 | Comparar el resultado con el criterio original | 15 min |
| 4 | Separar evidencia, interpretación y supuesto | 10 min |
| 5 | Buscar limitaciones y explicaciones alternativas | 15 min |
| 6 | Pausa | 10 min |
| 7 | Tomar la decisión basada en evidencia real | 15 min |
| 8 | Sprint de Pivot: diseñar una ruta alternativa | 25 min |
| 9 | Preparar el punto de partida para Clase 7 | 15 min |
| 10 | Completar, revisar y entregar | 5 min |
|  | **Total estimado** | **150 min** |

---

# Paso 1 — Recuperar el contrato experimental

**Duración:** 10 minutos  
**Modalidad:** equipo

Antes de mirar los resultados, recuperen lo que habían acordado antes de construir y probar.

Completen:

~~~markdown
## 1. Contrato experimental original

- Hipótesis:
- Pregunta de aprendizaje:
- Participantes, escenarios o fuente de datos:
- Acción o resultado que íbamos a observar:
- Métrica:
- Criterio de éxito definido antes de probar:
- Duración o cantidad de casos acordada:
- Limitación reconocida antes de ejecutar:
~~~

## Control

- ¿La hipótesis es exactamente la que se probó?
- ¿El criterio fue definido antes de conocer los resultados?
- ¿La métrica representa el comportamiento o resultado que querían observar?
- ¿El equipo cambió alguna condición durante la ejecución? Si ocurrió, regístrenlo.

> **No modifiquen ahora el criterio para que el experimento parezca exitoso.**

---

# Paso 2 — Ordenar la evidencia producida

**Duración:** 15 minutos  
**Modalidad:** equipo con IA

Primero organicen los materiales originales. Incluyan tanto las señales favorables como las contrarias.

Usen esta tabla. No todas las evidencias permiten sostener la misma conclusión.

| Evidencia original | Naturaleza | Fuente | Qué puede demostrar | Qué no puede demostrar | Limitación |
|---|---|---|---|---|---|
|  | Técnica real / técnica simulada / primaria cualitativa / primaria conductual / secundaria / dato simulado |  |  |  |  |

## Orientación para clasificar la evidencia

| Evidencia | Naturaleza posible | Puede demostrar | No puede demostrar por sí sola |
|---|---|---|---|
| Prueba automatizada | Técnica simulada | Funcionamiento del recorrido probado | Comprensión o comportamiento humano |
| Entrevista | Primaria cualitativa | Experiencias y comportamientos relatados | Prevalencia en una población |
| Analítica de uso | Primaria conductual | Acciones registradas | Motivación o causalidad |
| Dataset ficticio | Dato simulado | Lógica inicial del modelo | Desempeño con datos reales |

## Prompt sugerido

~~~text
Actuá como analista de evidencia de producto.

Te voy a proporcionar el contrato experimental y los resultados originales.

Organizalos en cuatro grupos:
1. Datos y observaciones directas.
2. Errores, anomalías o cambios durante la prueba.
3. Resultados que parecen respaldar la hipótesis.
4. Resultados que parecen contradecirla.

Para cada elemento, conservá la fuente y separá el dato original de
cualquier interpretación. Indicá su naturaleza y explicitá qué puede y qué
no puede demostrar. No completes datos faltantes, no elimines resultados
contrarios y no tomes una decisión por nosotros.

Contrato experimental:
[PEGAR]

Resultados originales:
[PEGAR O ADJUNTAR]
~~~

## Decisión humana

Verifiquen que la IA no haya:

- inventado resultados;
- transformado una opinión en un hecho;
- eliminado una anomalía;
- supuesto que una correlación explica una causa;
- mezclado datos simulados con datos de personas reales.

---

# Paso 3 — Comparar el resultado con el criterio original

**Duración:** 15 minutos  
**Modalidad:** equipo

Ahora comparen el resultado observado con el criterio definido en el Paso 1.

| Métrica o señal | Criterio original | Resultado observado | ¿La comparación es válida? | Observaciones |
|---|---|---|---|---|
|  |  |  | Sí / No / Parcial |  |

Después completen:

~~~markdown
## 2. Comparación con el criterio

- Resultado principal:
- ¿Se alcanzó el criterio?:
- ¿Qué evidencia permite afirmarlo?:
- ¿Qué dato o condición impide una comparación completa?:
- ¿Qué no podemos concluir todavía?:
~~~

## Tres estados posibles

| Estado | Significado |
|---|---|
| **Respaldada por esta prueba** | Se alcanzó el criterio definido y la evidencia es suficientemente confiable para esta hipótesis. |
| **No respaldada por esta prueba** | La ejecución produjo evidencia válida, pero no alcanzó el criterio. |
| **Inconclusa** | Los datos, el instrumento, la muestra o la ejecución no permiten comparar de manera válida. |

> Ninguno de estos estados demuestra o descarta definitivamente el problema completo ni toda una solución.

## Si el estado es inconclusa

Elijan un motivo principal. Si existe más de uno, registren los secundarios en observaciones.

~~~markdown
- Estado de la hipótesis: inconclusa
- Motivo principal: ejecución incompleta / falla del instrumento /
  medición inválida / muestra o contexto inadecuados / datos insuficientes /
  otro explicado por el equipo
~~~

| Motivo principal | Acción probable |
|---|---|
| Ejecución incompleta | Completar la ejecución |
| Falla del instrumento | Corregir |
| Muestra, canal o contexto inadecuados | Iterar |
| Medición inválida | Revisar el contrato y documentar la limitación |
| Datos insuficientes tras ejecutar | Diseñar una prueba que produzca evidencia interpretable |
| Evidencia válida que cuestiona la hipótesis | Pivotar o actualizar el Canvas |

La tabla orienta la discusión. No toma la decisión por el equipo.

---

# Paso 4 — Separar evidencia, interpretación y supuesto

**Duración:** 10 minutos  
**Modalidad:** equipo con IA

Completen la siguiente tabla antes de discutir decisiones:

| Evidencia directa | Interpretación posible | Supuesto que continúa abierto | Cómo podríamos comprobarlo |
|---|---|---|---|
|  |  |  |  |

## Prompt sugerido

~~~text
Revisá esta tabla de resultados como una persona escéptica.

Para cada afirmación del equipo, clasificá:
- qué parte es evidencia directa;
- qué parte es interpretación;
- qué supuesto sigue abierto;
- qué evidencia faltaría para sostener o refutar esa interpretación.

No decidas por nosotros y no presentes una explicación plausible como si
fuera un hecho.

[PEGAR TABLA]
~~~

> **La IA es un segundo evaluador, no un árbitro.**

---

# Paso 5 — Buscar limitaciones y explicaciones alternativas

**Duración:** 15 minutos  
**Modalidad:** equipo con IA

Un mismo resultado puede tener varias explicaciones. Antes de decidir, intenten cuestionar su lectura inicial.

Ejemplos de limitaciones:

- muestra demasiado pequeña o poco representativa;
- las personas no recibieron el estímulo;
- el mensaje no era comprensible;
- el instrumento tuvo un error técnico;
- la métrica no representaba el comportamiento buscado;
- el contexto de la prueba no era realista;
- se modificaron condiciones durante la ejecución;
- una parte relevante era simulada.

## Prompt sugerido

~~~text
Actuá como revisor crítico del experimento.

Con el contrato original, los resultados y nuestra interpretación inicial:

1. Identificá explicaciones alternativas posibles.
2. Indicá qué limitaciones podrían afectar la conclusión.
3. Señalá si confundimos exposición, comprensión, confianza e interés.
4. Marcá qué conclusión sería excesiva con esta evidencia.
5. Proponé qué dato adicional diferenciaría las explicaciones.

No inventes fallas ni afirmes que una explicación es verdadera. Presentá
alternativas y la evidencia necesaria para evaluarlas.

[PEGAR INFORMACIÓN]
~~~

Registren:

~~~markdown
## 3. Limitaciones y explicaciones alternativas

| Interpretación inicial | Explicación alternativa | Evidencia necesaria para distinguirlas | Decisión del equipo |
|---|---|---|---|
| | | | |
~~~

---

# Paso 6 — Pausa

**Duración:** 10 minutos

Antes de decidir, revisen que el archivo conserve todo lo observado, incluso aquello que contradice su expectativa.

---

# Paso 7 — Tomar la decisión basada en evidencia real

**Duración:** 15 minutos  
**Modalidad:** equipo

Elijan una decisión respecto del experimento real. No elijan la alternativa más cómoda: elijan la que se justifica con la evidencia disponible.

| Decisión | Cuándo corresponde | Qué se conserva | Qué cambia |
|---|---|---|---|
| **Avanzar** | La evidencia alcanza para pasar a la siguiente incertidumbre. | Aprendizaje y problema. | Pregunta de aprendizaje prioritaria. |
| **Completar la ejecución** | El contrato y el instrumento siguen vigentes, pero todavía no se alcanzó la regla de finalización o la cantidad acordada de casos. | Hipótesis, métrica, criterio e instrumento. | Reclutamiento, agenda o continuidad operativa. |
| **Corregir** | Falló el instrumento, la instrucción o la medición. | Problema, hipótesis y criterio. | Instrumento. |
| **Iterar** | La evidencia es insuficiente por muestra, canal o contexto. | Problema e hipótesis. | Método, muestra, canal o contexto. |
| **Pivotar** | La evidencia válida cuestiona una hipótesis, mecanismo, solución, segmento o actor. | Lo que la evidencia respalda. | La hipótesis cuestionada. |
| **Actualizar el Canvas** | Varias pruebas cuestionan el problema o el equipo no puede abordarlo en el alcance actual. | Historial y evidencia. | Segmento, formulación, oportunidad o alcance. |

> **Completar una prueba que todavía no alcanzó su regla de finalización no es necesariamente iterar. Iterar implica cambiar muestra, canal, contexto o método para producir evidencia diferente.**

Completen:

~~~markdown
## 4. Decisión sobre el experimento real

- Estado de la hipótesis: respaldada, no respaldada o inconclusa:
- Motivo de inconclusa, si corresponde:
- Decisión: avanzar, completar la ejecución, corregir, iterar, pivotar o actualizar el Canvas:
- Evidencia principal que la fundamenta:
- Limitación que debemos conservar visible:
- Qué conservamos:
- Qué modificamos:
- Próxima incertidumbre por reducir:
- Próxima acción mínima:
~~~

> **Una decisión no es una predicción infalible. Es la mejor acción que podemos justificar con la evidencia disponible.**

---

# Paso 8 — Sprint de Pivot: la primera respuesta no alcanza

**Duración:** 25 minutos  
**Modalidad:** equipo con IA

Ahora todos los equipos realizarán un pivot de aprendizaje. No importa si su resultado anterior fue favorable.

El objetivo no es inventar que su proyecto fracasó. El objetivo es practicar cómo abandonar una primera forma de resolver el problema sin perder el conocimiento acumulado.

> **Un pivot es una rama nueva, no el borrado de una rama anterior.**

## Regla de integridad

Este ejercicio es una simulación pedagógica. La restricción que usen a continuación **no es evidencia real** y debe quedar identificada como simulación. No reescriban el registro del experimento real.

## Elegir una carta de realidad

Seleccionen una sola condición:

1. El usuario entiende el problema, pero no realiza la acción esperada.
2. La solución funciona, pero el actor clave no tiene incentivo para usarla.
3. El canal elegido no permite llegar de manera confiable al usuario.
4. La propuesta genera interés, pero no confianza.
5. El problema existe, pero el equipo no puede intervenir sobre su causa principal.

## Qué se puede pivotar

No pivoteen automáticamente el problema. Empiecen por el cambio más pequeño que permita aprender algo diferente.

| Mantener, si la evidencia lo permite | Pivotar |
|---|---|
| Problema y usuario | Mecanismo o solución |
| Problema y solución | Segmento o actor que interviene |
| Problema general | Alcance concreto abordable |
| Aprendizajes acumulados | Hipótesis de valor o comportamiento |

## Prompt sugerido

~~~text
Actuá como Product Coach.

Nuestro problema, usuario y evidencia acumulada son:
[PEGAR]

La carta de realidad elegida para esta simulación es:
[PEGAR UNA OPCIÓN]

Ayudanos a diseñar un pivot sin borrar el aprendizaje anterior.

1. Indicá qué conviene conservar.
2. Proponé dos o tres pivots posibles, de menor a mayor cambio.
3. Para cada uno, explicá qué hipótesis cambia, qué ganamos, qué riesgo nuevo
incorporamos y qué evidencia deberíamos obtener.
4. Recomendá el pivot más pequeño que produzca aprendizaje distinto.
5. No tomes la decisión final ni presentes la carta de realidad como evidencia real.
~~~

## Decisión humana

Elijan una ruta alternativa y completen:

~~~markdown
## 5. Pivot 01 — Simulación pedagógica

- Carta de realidad elegida:
- Problema que conservamos:
- Usuario o actor que conservamos:
- Evidencia real que conservamos:
- Supuesto, mecanismo o solución que dejamos de sostener:
- Tipo de pivot: mecanismo, segmento, actor o alcance:
- Nueva hipótesis de valor:
- Nueva propuesta de solución:
- Qué ventaja buscamos:
- Riesgo nuevo que incorporamos:
- Evidencia que necesitaríamos para sostener esta nueva ruta:
- Decisión del equipo y justificación:
~~~

La rama Pivot 01 no reemplaza automáticamente la ruta principal. Conserven ambas:

- **Ruta principal:** decisión surgida de la evidencia del experimento real.
- **Rama Pivot 01:** alternativa creada como simulación pedagógica.

Antes de la Clase 7 elegirán cuál diseñar y dejarán visible si esa elección se basa en evidencia real o en exploración pedagógica.

---

# Paso 9 — Preparar el punto de partida para Clase 7

**Duración:** 15 minutos  
**Modalidad:** equipo

Todos los equipos avanzan a Clase 7. No todos llegan con el mismo nivel de evidencia, pero todos deben saber desde qué evidencia están diseñando.

Completen:

~~~markdown
## 6. Punto de partida para diseñar

- Ruta principal basada en evidencia:
- Rama Pivot 01 simulada:
- Ruta elegida para Clase 7:
- Naturaleza de la elección: basada en evidencia / exploración pedagógica:
- Justificación:
- Problema que conservamos:
- Usuario o actor sobre el que podemos intervenir:
- Evidencia más fuerte:
- Supuesto crítico aún abierto:
- Qué no podemos afirmar todavía:
- Ruta de solución que diseñaremos en Clase 7:
- Qué deberá aprender o medir nuestro futuro MVP:
~~~

## Regla para la siguiente etapa

| Situación del equipo | Cómo diseña en Clase 7 |
|---|---|
| Evidencia suficiente | Diseña una propuesta de valor, User Journey y MVP con foco en entregar valor y observar uso. |
| Evidencia parcial | Diseña una propuesta de valor condicional y un MVP que permita también resolver el supuesto crítico. |
| Elige explorar Pivot 01 | Diseña la ruta alternativa como hipótesis, con su medición incorporada y la elección identificada como exploración pedagógica. |

> **Ningún equipo queda detenido. Pero ningún equipo puede presentar como validado lo que todavía es un supuesto.**

---

# Paso 10 — Completar, revisar y entregar

**Duración:** 5 minutos  
**Modalidad:** equipo

El archivo **informe-aprendizaje-decision.md** debe contener:

1. Contrato experimental original.
2. Evidencia ordenada, incluyendo errores y resultados contrarios.
3. Comparación contra el criterio definido antes de probar.
4. Separación entre evidencia, interpretación y supuesto.
5. Limitaciones y explicaciones alternativas.
6. Decisión fundamentada sobre el experimento real.
7. Pivot 01 claramente identificado como simulación pedagógica.
8. Ruta principal, rama Pivot 01 y elección explícita para Clase 7.

## Checklist final

- [ ] Conservamos los resultados originales, incluso los incómodos.
- [ ] No modificamos la métrica ni el criterio después de probar.
- [ ] Indicamos la naturaleza, el alcance y las limitaciones de cada evidencia.
- [ ] Distinguimos hechos, interpretaciones, supuestos y decisiones.
- [ ] No presentamos datos simulados como datos reales.
- [ ] Explicamos las limitaciones de nuestra prueba.
- [ ] La decisión sobre el experimento real está fundamentada.
- [ ] El Pivot 01 no borra ni falsifica la evidencia anterior.
- [ ] Identificamos qué cambia y qué se conserva en el pivot.
- [ ] La ruta elegida para Clase 7 está justificada y su naturaleza es explícita.
- [ ] Sabemos desde qué evidencia diseñaremos la solución.
- [ ] Guardamos el informe en el repositorio del equipo.

---

## Cierre

La velocidad en producto no consiste en acertar la primera idea. Consiste en reducir el costo de estar equivocados, conservar lo aprendido y volver a decidir mejor.

> **No construimos para defender una idea. Construimos y aprendemos para tomar mejores decisiones.**

La Clase 7 comenzará con esta pregunta:

> **¿Qué solución vale la pena diseñar ahora, para quién y con qué incertidumbre todavía visible?**
