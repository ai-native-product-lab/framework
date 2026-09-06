# Clase 4 — Validar la hipótesis crítica

## Propósito de la clase

En la clase anterior, cada equipo completó su Lean Product Canvas, formuló hipótesis y eligió qué necesita aprender primero.

En esta clase vamos a transformar esa decisión en un **Plan de Validación**. El objetivo no es construir el producto ni demostrar que nuestra idea es correcta. El objetivo es decidir qué evidencia necesitamos y cuál es la forma más rápida y barata de obtenerla.

> **El Canvas organiza nuestras hipótesis. La validación nos acerca a la realidad.**

---

## La curva de la verdad

Al comenzar un producto tenemos muchos supuestos y poca evidencia. Por eso, la inversión inicial debe ser pequeña.

A medida que obtenemos evidencia más cercana a comportamientos y situaciones reales, podemos aumentar progresivamente la inversión.

La regla es sencilla:

> **Poca evidencia → poca inversión.**  
> **Más evidencia → mayor inversión.**

Antes de construir cualquier instrumento, el equipo debe responder:

1. ¿Qué sabemos realmente?
2. ¿Qué continúa siendo un supuesto?
3. ¿Qué necesitamos aprender ahora?
4. ¿Cuál es la prueba más barata que puede producir esa evidencia?

---

## El papel de la IA y del equipo

La IA puede:

- leer y organizar el contexto;
- detectar contradicciones;
- proponer métodos de validación;
- ayudar a definir métricas y criterios;
- preparar el encargo para construir el instrumento.

El equipo debe:

- confirmar que la IA interpretó correctamente el Canvas;
- decidir qué evidencia considera válida;
- seleccionar el método apropiado;
- definir el criterio de éxito antes de ejecutar la prueba;
- decidir cuánto conviene invertir.

> **La IA propone y estructura. El criterio y las decisiones pertenecen al equipo.**

---

## Resultado de la clase

Cada equipo entregará un archivo:

`plan-validacion.md`

Este documento dejará preparado el experimento que la IA construirá en la clase siguiente.

En esta clase **no construiremos el MVP ni ejecutaremos todavía el experimento**.

---

## Material necesario

- `lean-product-canvas.md` completo y actualizado.
- Skill `preparar-validacion-hipotesis`.
- Una conversación nueva con una IA que permita adjuntar archivos.
- Repositorio del equipo para guardar el entregable.

---

# Actividad paso a paso

## Paso 0 — Cargar el contexto

1. Abran una conversación nueva con la IA.
2. Activen o carguen la skill `preparar-validacion-hipotesis`.
3. Adjunten el archivo `lean-product-canvas.md`.
4. Envíen este mensaje:

> Usá la skill `preparar-validacion-hipotesis` para guiarnos paso a paso en la creación del Plan de Validación a partir del Lean Product Canvas adjunto. Hacé una sola pregunta por vez. No modifiques el Canvas y no construyas ni ejecutes todavía el experimento.

La IA debe recuperar:

- la hipótesis priorizada;
- lo más importante que necesitan aprender;
- el experimento mínimo previsto;
- la métrica y el criterio de éxito;
- la evidencia, los supuestos y las limitaciones.

No avancen hasta confirmar que la interpretación sea correcta.

---

## Paso 1 — Ubicarse en la curva de la verdad

El equipo debe identificar su situación actual:

### 1. Solo supuestos

El equipo formuló la idea, pero todavía no encontró señales externas.

### 2. Señales preliminares

Existen entrevistas, observaciones, datos secundarios u otros indicios, pero la hipótesis crítica todavía no fue probada.

### 3. Evidencia inicial

Ya existe una prueba o un comportamiento observado que respalda parcialmente la hipótesis.

Registren:

- evidencia disponible;
- supuestos pendientes;
- nivel de incertidumbre;
- nivel de inversión justificado.

La IA puede recomendar una ubicación, pero el equipo debe confirmar que las evidencias mencionadas realmente existen.

---

## Paso 2 — Confirmar qué necesitan aprender

Recuperen la pregunta de aprendizaje de la caja 7 del Canvas.

Comprueben que:

- sea una sola pregunta;
- se relacione con la hipótesis priorizada;
- su respuesta permita tomar una decisión;
- no pregunte simplemente si es posible construir una funcionalidad, salvo que exista un riesgo técnico real.

No reemplacen la pregunta solamente porque otra resulte más fácil de probar.

---

## Paso 3 — Definir qué evidencia necesitan

Antes de elegir una herramienta, definan qué señal permitiría aprender.

La evidencia puede surgir de:

- una acción realizada por una persona;
- una decisión frente a una alternativa;
- un resultado observable;
- datos existentes;
- una prueba técnica;
- una tarea completada con un prototipo.

Eviten utilizar como única evidencia frases como:

- “me gusta”;
- “lo usaría”;
- “parece una buena idea”.

Es preferible observar qué hace, elige o consigue una persona.

---

## Paso 4 — Elegir el método de validación

No todas las hipótesis se validan de la misma manera.

| Hipótesis crítica | Métodos posibles |
| --- | --- |
| Problema o necesidad | Entrevista, observación, análisis de evidencia, diario de experiencia o mapa de empatía |
| Valor | Prototipo de tarea, concierge digital, Wizard of Oz o comparación de alternativas |
| Comportamiento o adopción | Landing page, fake door, reserva, registro o prueba de uso |
| Factibilidad | Prueba técnica, simulación, planilla, script o micro web app con datos de ejemplo |
| Viabilidad | Prueba de precio, costos, capacidad operativa o compromiso de pago |

La IA debe proponer entre dos y tres métodos, explicar qué permitiría aprender cada uno y recomendar el más barato que produzca evidencia suficiente.

El equipo elige el método.

### ¿Cuándo usar un mapa de empatía?

El mapa de empatía es útil cuando la hipótesis requiere comprender el problema, la necesidad o el comportamiento del usuario.

Debe construirse con evidencia obtenida de personas reales y separar:

- **evidencia directa:** lo que la persona dijo o hizo;
- **interpretación:** lo que el equipo cree que significa;
- **supuesto pendiente:** lo que todavía debe comprobarse.

> El mapa de empatía no se utiliza para imaginar al usuario, sino para sintetizar lo aprendido sobre él.

---

## Paso 5 — Definir la métrica y el criterio

La métrica y el criterio deben quedar definidos **antes de construir y ejecutar la prueba**.

Completen:

- **Métrica:** ¿qué vamos a contar, comparar u observar?
- **Criterio de éxito:** ¿qué resultado mínimo justificaría continuar?
- **Criterio de refutación:** ¿qué resultado debilitaría o refutaría la hipótesis?

Ejemplo:

> **Métrica:** cantidad de escenarios que producen recomendaciones coherentes.  
> **Criterio de éxito:** al menos 8 de 10 escenarios coherentes.  
> **Resultado que debilita la hipótesis:** menos de 8 escenarios coherentes.

El criterio no puede modificarse después de conocer los resultados solo para confirmar la idea.

---

## Paso 6 — Definir el instrumento mínimo

Describan qué deberá construir la IA en la clase siguiente.

Puede ser:

- un prototipo navegable;
- una micro web app;
- una landing page;
- un chatbot simulado;
- un formulario;
- una planilla automatizada;
- una simulación;
- una prueba técnica con datos de ejemplo.

Definan expresamente:

- qué debe incluir;
- qué no debe incluir;
- qué podrá demostrar;
- qué todavía no podrá demostrar.

> El instrumento experimental responde una pregunta específica y puede descartarse. No es todavía el MVP.

---

## Paso 7 — Preparar el encargo para la IA

La IA debe redactar un prompt de construcción que incluya:

1. contexto mínimo del proyecto;
2. objetivo de aprendizaje;
3. entradas o tarea del participante;
4. resultado esperado;
5. participantes o fuentes;
6. métrica y criterio de éxito;
7. alcance incluido y excluido;
8. limitaciones de la prueba;
9. instrucción de señalar ambigüedades antes de construir.

El prompt debe explicar **qué evidencia necesita el equipo**, sin imponer lenguajes de programación, frameworks o arquitectura, salvo que exista una restricción real.

---

## Paso 8 — Generar el entregable

Revisen el plan completo. Cuando el equipo lo confirme, pídanle a la IA:

> Generá el archivo `plan-validacion.md` con todas las decisiones confirmadas. No agregues decisiones nuevas y no construyas todavía el instrumento.

Guarden el archivo en el repositorio del equipo.

---

# Estructura del entregable

```markdown
# Plan de Validación — [Nombre del proyecto]

## 1. Hipótesis crítica

## 2. Posición en la curva de la verdad
- Evidencia disponible:
- Supuestos pendientes:
- Nivel de incertidumbre:
- Inversión justificada:

## 3. Pregunta de aprendizaje

## 4. Evidencia necesaria
- Señal o comportamiento:
- Fuente o participantes:

## 5. Método de validación
- Tipo de actividad:
- Tarea:
- Duración:
- Herramienta:
- Papel de la IA:

## 6. Métrica y criterio
- Métrica:
- Criterio de éxito:
- Resultado que debilitaría o refutaría la hipótesis:

## 7. Instrumento que construirá la IA

## 8. Alcance y límites
- Debe incluir:
- Queda fuera:
- Puede demostrar:
- Todavía no puede demostrar:

## 9. Prompt de construcción para la próxima clase
```

---

# Checklist antes de entregar

- [ ] Cargamos y utilizamos nuestro Lean Product Canvas.
- [ ] Conservamos la hipótesis priorizada por el equipo.
- [ ] Diferenciamos evidencia de supuestos.
- [ ] Ubicamos el proyecto en la curva de la verdad.
- [ ] Definimos qué evidencia necesitamos antes de elegir la herramienta.
- [ ] Elegimos un método adecuado al tipo de hipótesis.
- [ ] Definimos métrica, éxito y refutación antes de ejecutar.
- [ ] Limitamos el instrumento a lo necesario para aprender.
- [ ] Explicamos qué podrá y qué no podrá demostrar.
- [ ] Preparamos el prompt que utilizaremos en la próxima clase.
- [ ] El equipo revisó y confirmó todas las decisiones propuestas por la IA.

---

## Cierre

Al terminar esta clase, todavía no sabemos si nuestra hipótesis es verdadera. Sí sabemos:

- qué necesitamos aprender;
- qué evidencia vamos a buscar;
- cómo la obtendremos;
- qué resultado aceptaremos;
- cuánto tiene sentido invertir.

En la próxima clase, la IA construirá el instrumento y el equipo ejecutará la prueba.

> **No avanzamos porque terminamos una actividad. Avanzamos cuando la evidencia justifica la siguiente inversión.**
