---
{"dg-publish":true,"permalink":"/morfo-i/unidad-ii-metabolismo-intermedio-y-bioenergetica/tema-16-glucogenolisis-y-glucogenogenesis/","dg-note-properties":{}}
---

# Tema 16: Metabolismo de los Carbohidratos: Glucogenólisis y Glucogenogénesis

El [[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 5 - Carbohidratos\|Glucógeno]] es la principal forma de almacenamiento de glucosa en el cuerpo humano, acumulado primordialmente en el **hígado** ($\approx 100\ g$, 10% del peso hepático) y en el **músculo esquelético** ($\approx 400\ g$, 1-2% del peso muscular, [[Morfo I/Unidad IV - Embriología y Tejidos Básicos/Tema 35 - Tejido muscular - Liso y estriado\|Tejido muscular]]):
- **Glucógeno Hepático:** Actúa como reserva de glucosa para mantener la glucemia en sangre durante el ayuno y entre comidas.
- **Glucógeno Muscular:** Reserva energética de movilización inmediata para la contracción muscular propia; no puede exportar glucosa al torrente sanguíneo.

---

## 1. Glucogenogénesis (Síntesis de Glucógeno)
Vía anabólica citosólica que sintetiza glucógeno a partir de glucosa-6-fosfato:
1. **Fosfoglucomutasa:** Isomeriza reversiblemente la Glucosa-6-fosfato (G6P) en Glucosa-1-fosfato (G1P).
2. **Activación de la Glucosa (Síntesis de UDP-Glucosa):**
   $$\text{G1P} + UTP \xrightarrow{\text{UDP-glucosa pirofosforilasa}} \text{UDP-glucosa} + PP_i$$
   - La hidrólisis subsiguiente del pirofosfato inorgánico ($PP_i \rightarrow 2\ P_i$) por la pirofosfatasa inorgánica impulsa irreversiblemente la reacción ([[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 7 - Bioenergética\|Acoplamiento energético]]).
3. **Iniciación de la Cadena y Cebador:** La enzima glucógeno sintasa solo puede alargar cadenas preexistentes; la proteína **Glucogenina** actúa como cebador autoglucosilante, fijando covalentemente hasta 8 residuos de glucosa a un residuo de tirosina.
4. **Elongación:** La enzima **Glucógeno Sintasa** cataliza la adición sucesiva de unidades de glucosa desde la UDP-glucosa a los extremos no reductores de la cadena, formando **enlaces $\alpha(1\rightarrow 4)$ glucosídicos**. Es la enzima marcapasos reguladora de la vía.
5. **Ramificación:** Cuando la cadena alcanza al menos 11 residuos, la **enzima ramificante** (amilo $\alpha(1\rightarrow 4)\rightarrow \alpha(1\rightarrow 6)$ transglicosilasa) corta un bloque de 6-7 residuos y lo transfiere a un carbono 6 de la misma u otra cadena, creando un **enlace $\alpha(1\rightarrow 6)$**. Las ramificaciones aumentan exponencialmente la solubilidad del polímero y multiplican los extremos no reductores para una síntesis y degradación aceleradas.

---

## 2. Glucogenólisis (Degradación de Glucógeno)
Ruta catabólica citosólica que moviliza unidades de glucosa desde las reservas de glucógeno:
1. **Fosforólisis:** La enzima **Glucógeno Fosforilasa** cataliza la rotura fosforolítica de los enlaces $\alpha(1\rightarrow 4)$ en los extremos no reductores, incorporando un fosfato inorgánico ($P_i$) sin consumir ATP:
   $$\text{Glucógeno}_{(n\ \text{residuos})} + P_i \xrightarrow{\text{Glucógeno fosforilasa}} \text{Glucógeno}_{(n-1)} + \text{Glucosa-1-fosfato (G1P)}$$
   - Emplea como cofactor indispensable el **Piridoxal Fosfato (PLP)** derivado de la vitamina B6 ([[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 9 - Enzimas, cofactores y vitaminas\|Vitaminas]]).
   - Se detiene cuando quedan 4 residuos antes de un punto de ramificación $\alpha(1\rightarrow 6)$ (dextrina límite).
2. **Desramificación:** La **enzima desramificante** bifuncional resuelve la ramificación:
   - *Actividad 4-$\alpha$-glucanotransferasa:* Transfiere un bloque de 3 residuos de glucosa al extremo de una cadena contigua lineal.
   - *Actividad amilo-$\alpha(1\rightarrow 6)$-glucosidasa:* Hidroliza el enlace $\alpha(1\rightarrow 6)$ del residuo restante, liberando una molécula de **glucosa libre** sin fosforilar ($\approx 10\%$ de la glucosa liberada en la glucogenólisis).
3. **Conversión a Glucosa-6-Fosfato:** La *fosfoglucomutasa* interconvierte la G1P en Glucosa-6-fosfato (G6P).

### Destinos Tisulares Divergentes de la Glucosa-6-Fosfato:
- **En el Hígado:** La membrana del retículo endoplásmico posee la enzima **Glucosa-6-fosfatasa**, que hidroliza la G6P en **glucosa libre**:
  $$\text{G6P} + H_2O \xrightarrow{\text{Glucosa-6-fosfatasa}} \text{Glucosa} + P_i$$
  La glucosa libre sale a la sangre a través del transportador GLUT2 para restablecer la glucemia.
- **En el Músculo:** El tejido muscular **carece de glucosa-6-fosfatasa**. La G6P queda atrapada intracelularmente e ingresa directamente en la [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 12 - Metabolismo de carbohidratos - Glicólisis\|Glicólisis]], generando ATP para sostener la contracción mecánica.

---

## 3. Regulación Hormonal y Covalente Coordinada
Para evitar ciclos fútiles, la glucogenogénesis y la glucogenólisis se regulan de forma recíproca mediante fosforilación/desfosforilación ([[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 10 - Regulación de la actividad enzimática\|Modificación covalente]]):

| Estado Fisiológico | Hormona Dominante | Efecto sobre Enzimas Reguladoras | Vía Metabólica Favorecida |
| :--- | :--- | :--- | :--- |
| **Ayuno / Hipoglucemia / Estrés** | **Glucagón** (hígado) / **Adrenalina** (hígado y músculo) | Activan la vía adenilato ciclasa $\rightarrow$ AMPc $\rightarrow$ **Proteína Quinasa A (PKA)**. La PKA fosforila enzimas clave:<br>• **Glucógeno Fosforilasa:** Se fosforila a su forma activa (*Fosforilasa a*).<br>• **Glucógeno Sintasa:** Se fosforila a su forma inactiva (*Sintasa b*). | **Glucogenólisis** (degradación) |
| **Postprandial / Abundancia** | **Insulina** | Activa fosfodiesterasas y la **Proteína Fosfatasa-1 (PP1)**, que desfosforila las enzimas:<br>• **Glucógeno Sintasa:** Se desfosforila a su forma activa (*Sintasa a*).<br>• **Glucógeno Fosforilasa:** Se desfosforila a su forma inactiva (*Fosforilasa b*). | **Glucogenogénesis** (síntesis) |

- **Regulación Alostérica en Músculo:** El aumento de **AMP** activa alostéricamente a la fosforilasa muscular sin fosforilación; el influjo de **$Ca^{2+}$** tras la despolarización neuromuscular activa a la fosforilasa quinasa, sincronizando la movilización de glucógeno con la contracción.
r
