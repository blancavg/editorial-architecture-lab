# Validación editorial

## Entrada

# **Del prompt genérico al resultado específico: anatomía de un experimento con moodboards**

El año pasado, durante el desarrollo de una mini-app, me encontré con un problema: necesitaba diseñar la interfaz, pero carecía de los fundamentos para expresar lo que quería. No podía simplemente decirle a la IA "que quede bonito" y esperar algo más que un resultado genérico. Necesitaba estructurar mi entrada, pero no tenía el vocabulario visual para hacerlo.

Este post documenta el experimento que diseñé para resolver ese dilema y lo que aprendí en el proceso. Es una reflexión sobre cómo estructurar el contexto cuando trabajamos con herramientas de IA en áreas donde no somos ni siquiera novatos.

## **El problema: cuando no tienes el lenguaje para describir lo que quieres**

Estaba usando vibe-coding para crear la primera versión de la app y luego seguir con codificación asistida para refinarla. Con los fundamentos de programación, es más fácil seguir el proceso y aprender en el camino. Sin embargo, el diseño sí lo fue, ya que no contaba ni con el conocimiento básico.

Intenté darle a la herramienta instrucciones sobre la paleta de colores y "estilo general", pero los resultados seguían siendo genéricos. Me di cuenta de que el problema era mi entrada. Necesitaba ser más específica, pero ¿cómo podía serlo sobre algo que no sabía expresar más allá de los adjetivos básicos?

Podía buscar sitios web que me gustaran y compartir enlaces, pero eso tampoco garantizaba nada. ¿Cómo podía extraer de ellos los elementos específicos de una descripción de diseño que me permitieran evaluar una salida?  Y evaluar no significa: «sí, me gusta».

Fue ahí cuando pensé en los moodboards.

## **La hipótesis: un moodboard como traductor visual**

Un moodboard no es simplemente una colección de imágenes bonitas. Es una herramienta que estructura información visual de forma específica: paleta de colores con códigos hexadecimales, tipografía definida, texturas, tempo, y lo más importante, un estado emocional claro.

Mi hipótesis era simple: si le daba a una herramienta de vibe-coding un moodboard estructurado como entrada, en lugar de descripciones vagas, obtendría resultados menos genéricos y más alineados con lo que buscaba.

El moodboard funcionaría como un traductor: yo no sabía hablar el "lenguaje de diseño", pero podía crear un documento que sí lo hiciera por mí.

## **El experimento: metodología y resultados**

### **Diseño del moodboard**

Primero tuve que aprender a crear un moodboard. Investigué principios básicos y usé Canva para diseñar uno centrado en el estado emocional de la calma". Incluí:

• Paleta de colores con códigos hexadecimales específicos (azules suaves, verdes sage, beige, gris, rosa y lavanda)

• Tipografía definida (Playfair Display para títulos, Inter para cuerpo)

• Imágenes que transmitieran el tempo deseado: texturas suaves, composiciones minimalistas, elementos naturales

• Descripción explícita del estado emocional: calm, thoughtful, human, credible, unhurried

### **Pruebas comparativas**

Diseñé dos prompts para crear un sitio web personal para un usuario ficticio con secciones de About, Blog y Contact:

Prompt sin moodboard: "Create a personal website for a creator. The site should include an About section, a Blog section, and a Contact section. The tone should be professional, clear, and approachable. Use a clean, modern layout with good readability. Avoid unnecessary complexity. The website should feel credible and well-structured."

Prompt con moodboard: El mismo prompt base, pero añadiendo: "Use the attached CALM emotional moodboard as context. All layout, typography, spacing, color, and tone decisions should align with the emotional space defined by the moodboard: calm, thoughtful, human, credible, and unhurried. Avoid loud visuals, startup aesthetics, sales-driven urgency, or overly dense layouts. The site should feel reflective and intentional rather than promotional."

Probé estos prompts en tres herramientas: Replit, Gemini Flash 3 y Lovable.

### **Resultados**

La diferencia fue notable en las tres herramientas. Los resultados con moodboard mostraron:

• Mayor consistencia en el uso de la paleta de colores especificada

• Mejor distribución de los espacios, sin aglomeración de elementos

• Tipografía alineada con las fuentes del moodboard

• Estética menos "startup genérica" y más personalizada

Con el moodboard, las tres salidas se parecían entre sí, mostrando consistencia. Aunque me gustó más el resultado de Gemini Flash 3, cualquiera de las tres satisfacía mis expectativas.

Los resultados sin moodboard caían en patrones visuales que ves en todos lados: colores y degradados llamativos, tonos azul/blanco o naranja/blanco, layouts densos, estética corporativa estándar.

## **Insights clave: más allá del diseño**

### **1\. Input estructurado \> prompt genérico**

El experimento confirmó algo que ya sabía, pero que no había formalizado: la calidad de la salida está directamente relacionada con la especificidad y la estructura del input.

La información que se proporciona, además de ser detallada, debe estar estructurada. El moodboard no es simplemente "más detalles"; es un sistema organizado de especificaciones que la herramienta puede interpretar de forma consistente.

Este principio aplica más allá del diseño visual. En cualquier tarea en la que trabajamos con IA, la forma en que estructuramos el contexto determina la utilidad del resultado.

### **2\. Los fundamentos importan**

Para crear el moodboard, tuve que investigar los principios básicos del diseño. No me convertí en diseñadora experta, ni siquiera en principiante, pero aprendí lo suficiente para:

• Evaluar si los resultados que generaba la IA tenían cierto nivel de calidad

• Identificar qué elementos específicos necesitaba modificar

• Comunicarme de forma más precisa con las herramientas

Aunque suena contraintuitivo, aprender los fundamentos favorece resultados de mayor calidad en el uso de la IA. Este conocimiento te permite distinguir entre resultados mediocres y buenos y dirigir mejor el proceso iterativo. 

### **3\. La experimentación no debe esperar al conocimiento perfecto**

El insight más importante es el de actitud: no necesitas ser experto para empezar a experimentar.

Podría haber esperado a tomar un curso completo de diseño antes de intentarlo. Antes lo habría hecho, lo confieso. En cambio, para agilizar, identifiqué lo mínimo que necesitaba aprender (qué es un moodboard, cómo se estructura), lo aprendí y experimenté.

Las herramientas actuales permiten este tipo de exploración. El costo de experimentar es bajo y el aprendizaje que obtienes es inmediato y práctico.

## **Conectando con análisis de comportamiento: contexto específico \= mejores resultados**

Este principio de que "el contexto estructurado genera mejores resultados" no se limita al diseño visual. Es fundamental cuando trabajamos con modelos de IA en cualquier dominio, incluyendo el análisis de comportamiento y de datos.

Piénsalo así: cuando le pides a un modelo de IA que analice datos de comportamiento, puedes darle un prompt genérico ("analiza estos datos") o puedes estructurar el contexto:

• ¿Qué métricas específicas son relevantes?

• ¿Qué patrones conocidos buscas confirmar o refutar?

• ¿Qué contexto del negocio o del usuario es necesario para interpretar correctamente los datos?

• ¿Qué nivel de granularidad necesitas en el análisis?

El moodboard en mi experimento funcionó como un "framework de especificaciones" para el diseño. De la misma forma, cuando trabajamos con análisis de comportamiento, necesitamos frameworks que estructuren nuestras preguntas y nuestro contexto.

La diferencia es que en diseño visual, el framework (el moodboard) es más tangible y reconocible. En el análisis de datos, el framework es conceptual: las hipótesis que quieres probar, las métricas que defines, el contexto que proporcionas.

En ambos casos, el principio es el mismo: herramientas poderosas \+ contexto estructurado \= resultados específicos y útiles.

## **Para cerrar: qué me llevo de este experimento**

Este experimento comenzó como una solución práctica a un problema de diseño, pero terminó siendo una lección más amplia sobre cómo trabajar efectivamente con IA:

La estructura del input importa tanto como la herramienta que uses. Un prompt genérico, en la mejor herramienta del mundo, te dará resultados genéricos. Un contexto bien estructurado en una herramienta promedio te acerca mucho más a lo que necesitas.

Necesitamos invertir en aprender lo básico (al menos). Este conocimiento nos ayuda a saber qué pedir y a evaluar los resultados.

Y finalmente: la consistencia importa. Cuando trabajas en cualquier proyecto que requiere múltiples iteraciones (un diseño, un análisis, una estrategia), contar con frameworks estructurados te permite mantener la coherencia a lo largo del proceso.

No me convertí en diseñadora, pero en cada iteración voy adquiriendo vocabulario y habilidades que antes no tenía, y eso es invaluable.


## Router

**Tipo:** D
**Confianza:** Alta
**Evidencia (máx. 2 bullets):**

* Formula una **hipótesis explícita**: usar un moodboard estructurado como “traductor visual” para obtener salidas menos genéricas. 
* Describe **diseño experimental + pruebas comparativas + resultados observables** (dos prompts, tres herramientas, diferencias claras en outputs). 
  **Si hay ambigüedad:** Podría ser D vs A, pero predomina D por hipótesis+método+resultados explícitos.


## Auditor
## Resultado general

Ajustes menores


## Desviaciones detectadas

## Resultado general

Ajustes menores



## Desviaciones detectadas

### Dimensión: Coherencia temática y jerarquía de ideas

* Fragmento: “**Conectando con análisis de comportamiento: contexto específico = mejores resultados** …”
* Severidad: Relevante
* Microajuste sugerido (máx. 2 líneas): Marcar explícitamente que es una **extrapolación** del experimento (no un resultado medido) o acotarlo como “hipótesis derivada”.

### Dimensión: Nivel técnico y profundidad

* Fragmento: “**Probé estos prompts en tres herramientas: Replit, Gemini Flash 3 y Lovable.**”
* Severidad: Leve
* Microajuste sugerido (máx. 2 líneas): Añadir 1–2 detalles mínimos para rigor experimental (p. ej., si fue **misma tarea**, **mismo prompt base**, **número de corridas** o si hubo variación).

### Dimensión: Estilo discursivo

* Fragmento: “**Insights clave:** … (1, 2, 3)”
* Severidad: Leve
* Microajuste sugerido (máx. 2 líneas): Mantenerlo en clave de laboratorio: enunciar como “**observaciones del experimento**” para evitar tono de marco general/prescriptivo.



## Incumplimientos Definition of Done

* Punto: **Las limitaciones son explícitas.**
  Falta una sección o frase directa sobre limitaciones/sesgos (p. ej., tamaño de muestra, subjetividad del criterio, ausencia de métricas, variación entre herramientas/corridas).



## Riesgo estructural

Si no se explicita la limitación y se etiqueta la extrapolación, el texto puede leerse como una conclusión general (“aplica a cualquier dominio”) más fuerte que la evidencia presentada.

