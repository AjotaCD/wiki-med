---
{"dg-publish":true,"permalink":"/morfo-i/unidad-i-biomoleculas-y-membrana-celular/tema-10-regulacion-de-la-actividad-enzimatica/","dg-note-properties":{}}
---

# Tema 10: Regulación de la Actividad Enzimática: Cinética, Inhibición y Enzimas Reguladoras

La regulación de la actividad enzimática es fundamental para que el [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 11 - Introducción al metabolismo\|Metabolismo]] responda dinámicamente a las demandas energéticas celulares, garantizando la velocidad óptima de los procesos bioquímicos, la eficiencia energética y la coordinación estricta entre rutas anabólicas y catabólicas.

---

## 1. Cinética Enzimática: Ecuación de Michaelis-Menten y Lineweaver-Burk
La cinética enzimática analiza cuantitativamente la velocidad de las reacciones catalizadas y los factores que la modifican.

### A. Modelo de Michaelis-Menten
Describe una reacción de un solo sustrato que transcurre a través de un complejo enzima-sustrato intermedio ($ES$):
$$E + S \underset{k_{-1}}{\overset{k_1}{ightleftharpoons}} ES \overset{k_2}{\longrightarrow} E + P$$

La ecuación clásica de velocidad inicial ($V_0$) es:
$$V_0 = rac{V_{max}[S]}{K_m + [S]}$$
- **$V_{max}$ (Velocidad Máxima):** Se alcanza cuando todos los centros activos de la enzima están completamente saturados de sustrato.
- **$K_m$ (Constante de Michaelis):** Concentración de sustrato a la cual la velocidad de la reacción es exactamente la mitad de la velocidad máxima ($V_0 = rac{V_{max}}{2}$). Es inversamente proporcional a la afinidad de la enzima por el sustrato (a menor $K_m$, mayor afinidad).

### B. Representación de Dobles Recíprocos (Lineweaver-Burk)
Transformación lineal de la ecuación de Michaelis-Menten que facilita determinar experimentalmente $K_m$ y $V_{max}$:
$$rac{1}{V_0} = rac{K_m}{V_{max}} \cdot rac{1}{[S]} + rac{1}{V_{max}}$$
- Intersección con el eje $y$: $rac{1}{V_{max}}$.
- Intersección con el eje $x$: $-rac{1}{K_m}$.
- Pendiente de la recta: $rac{K_m}{V_{max}}$.

### C. Factores Físicos que Afectan la Actividad
- **Temperatura:** La actividad aumenta con la temperatura hasta alcanzar una temperatura óptima (típicamente $37^\circ C$ en humanos); por encima de ella, sobreviene la desnaturalización térmica de la proteína.
- **pH Óptimo:** Cada enzima opera en un rango estrecho de pH determinado por el estado de ionización de los residuos de su centro activo:
  - *Pepsina gástrica:* pH óptimo fuertemente ácido ($1.5 - 2.0$).
  - *Tripsina pancreática:* pH óptimo neutro-alcalino ($7.5 - 8.5$).

---

## 2. Inhibición Enzimática
Los inhibidores son agentes químicos que reducen o bloquean la velocidad de una reacción enzimática.

### A. Inhibición Reversible

| Tipo de Inhibición | Mecanismo | Efecto sobre $K_m$ | Efecto sobre $V_{max}$ | Ejemplo Clínico / Farmacológico |
| :--- | :--- | :--- | :--- | :--- |
| **Competitiva** | El inhibidor se une reversiblemente al **sitio activo**, compitiendo con el sustrato. Se supera aumentando $[S]$. | **Aumenta** ($K_m$ aparente mayor, menor afinidad). | **Sin cambio** (se alcanza la misma $V_{max}$). | **Estatinas** (atorvastatina) compiten con el sustrato en la HMG-CoA reductasa, reduciendo la síntesis de colesterol. Metotrexato inhibe dihidrofolato reductasa. |
| **No Competitiva** | El inhibidor se une a un **sitio alostérico** distinto, uniéndose tanto a la enzima libre como al complejo $ES$. No se revierte aumentando $[S]$. | **Sin cambio** ($K_m$ inalterada). | **Disminuye** (reduce el número de centros activos funcionales). | Inhibición de enzimas por metales pesados (plomo, mercurio). |
| **Acompetitiva** | El inhibidor se une exclusivamente al complejo enzima-sustrato ($ES$). | **Disminuye** ($K_m$ aparente). | **Disminuye** ($V_{max}$). | Poco frecuente en sistemas biológicos unicelulares. |

### B. Inhibición Irreversible (Inactivadores Suicidas)
El inhibidor se une covalentemente a un residuo crítico del centro activo o desnaturaliza la enzima de forma permanente:
- *Aspirina (Ácido acetilsalicílico):* Acetila irreversiblemente una serina del centro activo de la ciclooxigenasa (COX-1 y COX-2), bloqueando la síntesis de tromboxanos y prostaglandinas.
- *Gases nerviosos y organofosforados:* Fosforilan irreversiblemente la acetilcolinesterasa en el [[Morfo I/Unidad IV - Embriología y Tejidos Básicos/Tema 34 - Tejido nervioso - Neuronas, neuroglia y sinapsis\|Tejido nervioso]].
- *Venenos de serpientes:* Toxinas que inactivan enzimas hemostáticas o neuroreceptores de forma permanente.

---

## 3. Enzimas Reguladoras y Mecanismos de Control Metabólico

### A. Regulación Alostérica
Las enzimas alostéricas poseen una estructura oligomérica con múltiples subunidades:
- Presentan sitios activos para el sustrato y **sitios alostéricos** reguladores independientes donde se unen moléculas moduladoras o efectores:
  - **Efectores Positivos (Activadores):** Desplazan la curva sigmoidea hacia la izquierda (estado R de alta afinidad), aumentando la actividad.
  - **Efectores Negativos (Inhibidores):** Desplazan la curva hacia la derecha (estado T de baja afinidad), disminuyendo la actividad.
- **Ejemplo Clave:** La **Fosfofructoquinasa-1 (PFK-1)**, enzima marcapasos de la [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 12 - Metabolismo de carbohidratos - Glicólisis\|Glicólisis]]:
  - *Activador alostérico:* AMP y Fructosa 2,6-bifosfato (indican baja carga energética celular).
  - *Inhibidor alostérico:* ATP y citrato (indican abundancia de energía).

### B. Modificación Covalente Reversible
Consiste en la adición o remoción covalente de un grupo químico específico sobre residuos de la enzima:
- **Fosforilación / Desfosforilación:** El mecanismo más extendido.
  - Las **proteínas quinasas** transfieren un grupo fosfato desde el ATP a residuos de Serina, Treonina o Tirosina.
  - Las **proteínas fosfatasas** eliminan el grupo fosfato por hidrólisis.
  - Ejemplo: La glucógeno fosforilasa se activa por fosforilación ([[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 16 - Glucogenólisis y glucogenogénesis\|Glucogenólisis]]), mientras que la glucógeno sintasa se inactiva.
- Otras modificaciones: Acetilación, metilación, adenililación y **ubiquitinación** (marca proteínas para degradación proteasómica).

### C. Retroalimentación Negativa (Retroinhibición o Feedback Inhibition)
En una vía multienzimática, el producto final de la ruta se acumula y se une alostéricamente a la primera enzima de la vía, inhibiendo su actividad y evitando la sobreproducción innecesaria:
- Ejemplo: La isoleucina inhibe a la treonina desaminasa en su propia ruta biosintética.

### D. Disponibilidad de Sustratos y Cofactores
La velocidad de las vías depende de la concentración de sustratos y de la relación entre coenzimas oxidadas/reducidas (ej. la relación $NAD^+/NADH$ regula el flujo del [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 14 - Estructura de la mitocondria y Ciclo de Krebs\|Ciclo de Krebs]]).

### E. Regulación por Expresión Génica (Inducción y Represión)
Control a nivel transcripcional que altera la cantidad absoluta de moléculas enzimáticas presentes en la célula:
- **Inducción Enzimática:** Señales hormonales o de sustratos estimulan la síntesis de nuevas enzimas (ej. la insulina induce la síntesis de enzimas glucolíticas y lipogénicas).
- **Represión Enzimática:** El exceso de metabolitos reprime la transcripción de genes biosintéticos (ej. operón triptófano).

### F. Cascadas de Activación Proteolítica (Zimógenos)
Muchas enzimas se sintetizan como precursores inactivos (**zimógenos**) que requieren una escisión proteolítica irreversible para activarse:
- Permite una respuesta biológica ultrarrápida y amplificada sin esperar la síntesis proteica:
  - *Enzimas digestivas:* Pepsinógeno $ightarrow$ pepsina, tripsinógeno $ightarrow$ tripsina.
  - *Cascada de la Coagulación Sanguínea:* Cascada secuencial de serina proteasas que previene hemorragias sin formar trombos descontrolados.
