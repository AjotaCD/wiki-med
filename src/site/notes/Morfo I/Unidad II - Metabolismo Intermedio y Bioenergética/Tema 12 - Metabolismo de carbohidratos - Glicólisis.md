---
{"dg-publish":true,"permalink":"/morfo-i/unidad-ii-metabolismo-intermedio-y-bioenergetica/tema-12-metabolismo-de-carbohidratos-glicolisis/","dg-note-properties":{}}
---

# Tema 12: Metabolismo de los Carbohidratos: Glicólisis, Rendimiento Energético y Regulación

La glicólisis (o vía de Embden-Meyerhof) es la ruta central del catabolismo de la glucosa en todos los organismos vivos. Ocurre exclusivamente en el **citosol** celular y puede operar tanto en condiciones aeróbicas como anaeróbicas.

---

## 1. Etapas y Reacciones de la Vía Glicolítica
Consta de 10 reacciones enzimáticas sucesivas divididas en dos fases:

### Fase I: Fase Preparatoria o de Inversión Energética (Reacciones 1 a 5)
Se consumen dos moléculas de [[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 7 - Bioenergética\|ATP]] para fosforilar y activar la molécula de glucosa, escindiéndola en dos triosas fosforiladas:
1. **Fosforilación de la Glucosa:**
   $$\text{Glucosa} + ATP \xrightarrow{\text{Hexoquinasa / Glucoquinasa}} \text{Glucosa-6-fosfato (G6P)} + ADP$$
   - Reacción irreversible. Atrapa a la glucosa dentro de la célula.
2. **Isomerización de G6P a Fructosa-6-fosfato (F6P):** Catalizada por la *fosfohexosa isomerasa*.
3. **Fosforilación de F6P a Fructosa-1,6-bisfosfato ($F-1,6-BP$):**
   $$\text{Fructosa-6-P} + ATP \xrightarrow{\text{Fosfofructoquinasa-1 (PFK-1)}} \text{Fructosa-1,6-bisfosfato} + ADP$$
   - Reacción irreversible. Es el principal punto de control alostérico y limitante de la glicólisis ([[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 10 - Regulación de la actividad enzimática\|Regulación enzimática]]).
4. **Escisión de la F-1,6-BP:** La *aldolasa* rompe la hexosa en dos triosas: Gliceraldehído-3-fosfato (GAP) y Dihidroxiacetona fosfato (DHAP).
5. **Interconversión de las Triosas:** La *triosa fosfato isomerasa* convierte reversiblemente la DHAP en una segunda molécula de GAP.

### Fase II: Fase de Beneficio o Generación Energética (Reacciones 6 a 10)
Cada molécula de GAP se oxida y transforma en piruvato, generando ATP mediante fosforilación a nivel de sustrato y coenzimas reducidas ($NADH$):
6. **Oxidación y Fosforilación de GAP:**
   $$\text{GAP} + NAD^+ + P_i \xrightarrow{\text{Gliceraldehído-3-fosfato deshidrogenasa (GAPDH)}} \text{1,3-Bisfosfoglicerato (1,3-BPG)} + NADH + H^+$$
7. **Primera Fosforilación a Nivel de Sustrato:** La *fosfoglicerato quinasa* transfiere un fosfato de alta energía al ADP:
   $$\text{1,3-BPG} + ADP \xrightarrow{\text{Fosfoglicerato quinasa}} \text{3-Fosfoglicerato} + ATP$$
8. **Isomerización:** La *fosfoglicerato mutasa* convierte 3-fosfoglicerato en 2-fosfoglicerato.
9. **Deshidratación:** La *enolasa* elimina una molécula de agua, generando Fosfoenolpiruvato (PEP), un intermediario con alto potencial de transferencia de fosfato.
10. **Segunda Fosforilación a Nivel de Sustrato:**
    $$\text{PEP} + ADP \xrightarrow{\text{Piruvato quinasa}} \text{Piruvato} + ATP$$
    - Reacción irreversible regulada covalentemente por fosforilación hormonal.

---

## 2. Rendimiento Energético Neto
Por cada molécula de glucosa ($6C$) degradada a dos moléculas de piruvato ($3C$):
$$\text{Glucosa} + 2\ NAD^+ + 2\ ADP + 2\ P_i \longrightarrow 2\ \text{Piruvato} + 2\ NADH + 2\ H^+ + 2\ ATP + 2\ H_2O$$

- **ATP Neto:** Se invierten $2\ ATP$ y se generan $4\ ATP$, rindiendo **$2\ ATP$ netos** por fosforilación a nivel de sustrato.
- **Poder Reductor:** Se generan **$2\ NADH$** citosólicos.

---

## 3. Destinos del Piruvato y del NADH

### A. Condiciones Aeróbicas
- El piruvato ingresa a la matriz mitocondrial para ser transformado por el complejo de la piruvato deshidrogenasa en Acetil-CoA, ingresando al [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 14 - Estructura de la mitocondria y Ciclo de Krebs\|Ciclo de Krebs]].
- Los electrones del $NADH$ citosólico se transfieren a la mitocondria mediante lanzaderas (malato-aspartato o glicerol-fosfato) y alimentan la [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 15 - Cadena respiratoria y fosforilación oxidativa\|Fosforilación oxidativa]], produciendo $\approx 30-32\ ATP$ por glucosa completa.

### B. Condiciones Anaeróbicas (Fermentación Láctica)
- En ausencia de oxígeno o en tejidos que carecen de mitocondrias, el $NADH$ no puede oxidarse en la cadena respiratoria.
- La enzima **Lactato Deshidrogenasa (LDH)** reduce el piruvato a **L-lactato**, oxidando simultáneamente el $NADH$ a $NAD^+$:
  $$\text{Piruvato} + NADH + H^+ \rightleftharpoons \text{Lactato} + NAD^+$$
- Esta regeneración de $NAD^+$ es obligatoria para que la enzima GAPDH no se detenga y la glicólisis continúe produciendo ATP anaeróbico.
- El lactato acumulado se exporta a la sangre y se recicla en el hígado a través del [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 19 - Gluconeogénesis, regulación hormonal y Ciclo de Cori\|Ciclo de Cori]].

---

## 4. Tejidos Dependientes de la Glicólisis como Fuente de Energía
- **Eritrocitos ([[Morfo I/Unidad IV - Embriología y Tejidos Básicos/Tema 33 - Tejido conjuntivo especializado - Sangre y matriz extracelular\|Glóbulos Rojos]]):** Carecen completamente de mitocondrias y núcleo; dependen **$100\%$ de la glicólisis anaeróbica** para generar el ATP necesario para mantener la forma bicóncava y las bombas iónicas.
- **Médula Renal, Cristalino y Córnea:** Zonas con baja vascularización y bajo tenor de oxígeno.
- **Músculo Esquelético en Ejercicio Intenso ([[Morfo I/Unidad IV - Embriología y Tejidos Básicos/Tema 35 - Tejido muscular - Liso y estriado\|Tejido muscular]]):** Recurre a la glicólisis anaeróbica rápida ante demandas de esfuerzo que superan el suministro vascular de $O_2$.

---

## 5. Regulación Enzimática de la Glicólisis
La vía está controlada por tres enzimas que catalizan pasos irreversibles:
1. **Hexoquinasa / Glucoquinasa:**
   - *Hexoquinasa (en la mayoría de los tejidos):* Baja $K_m$ (alta afinidad), inhibida por su producto (G6P).
   - *Glucoquinasa (hígado y células $\beta$ pancreáticas):* Alta $K_m$ (opera tras las comidas), no es inhibida por G6P; inducible por insulina.
2. **Fosfofructoquinasa-1 (PFK-1):** Enzima marcapasos clave.
   - *Inhibidores alostéricos:* ATP, citrato y bajo pH.
   - *Activadores alostéricos:* AMP, ADP y **Fructosa-2,6-bisfosfato ($F-2,6-BP$)**.
3. **Piruvato Quinasa:**
   - *Activación:* Activada alostéricamente por F-1,6-BP (mecanismo feed-forward).
   - *Inhibición:* Inhibida por ATP, acetil-CoA y alanina.
   - *Regulación hormonal:* El glucagón promueve su fosforilación e inactivación hepática vía AMPc/PKA para frenar la glicólisis durante el ayuno.
r
