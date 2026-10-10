---
{"dg-publish":true,"permalink":"/morfo-i/unidad-ii-metabolismo-intermedio-y-bioenergetica/tema-15-cadena-respiratoria-y-fosforilacion-oxidativa/","dg-note-properties":{}}
---

# Tema 15: Cadena Respiratoria Mitocondrial y Fosforilación Oxidativa

La fosforilación oxidativa es el proceso metabólico culminante de la respiración celular en los organismos aeróbicos mediante el cual la energía química liberada durante la oxidación de nutrientes se convierte en [[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 7 - Bioenergética\|ATP]] en las [[Morfo I/Unidad II - Metabolismo Intermedio y Bioenergética/Tema 14 - Estructura de la mitocondria y Ciclo de Krebs\|Mitocondrias]]:
- Transcurre acoplada a la membrana mitocondrial interna.
- Utiliza los electrones transportados por las coenzimas reducidas ($NADH$ y $FADH_2$) procedentes de la glicólisis, la $\beta$-oxidación y el ciclo de Krebs.

---

## 1. Componentes Multienzimáticos de la Cadena de Transporte de Electrones
Los electrones fluyen a través de cuatro complejos proteicos transmembrana integrados y dos transportadores móviles, ordenados según su **potencial redox estándar ($E^\circ'$)** creciente (desde $-0.32\ V$ en el par $NAD^+/NADH$ hasta $+0.82\ V$ en el par $O_2/H_2O$):

1. **Complejo I (NADH:Ubiquinona Oxidorreductasa):**
   - Complejo macromolecular en forma de "L" con centros hierro-azufre ($Fe-S$) y mononucleótido de flavina ($FMN$).
   - Oxida el $NADH$ matricial, transfiere $2\ e^-$ a la ubiquinona ($Q$) y **bombea $4\ H^+$** desde la matriz hacia el espacio intermembranoso.
2. **Complejo II (Succinato Deshidrogenasa):**
   - Contiene la enzima del ciclo de Krebs unida a la membrana interna con $FAD$ y centros $Fe-S$.
   - Transfiere electrones del succinato directamente a la ubiquinona ($Q \rightarrow QH_2$).
   - **No bombea protones** a través de la membrana.
3. **Coenzima Q (Ubiquinona / Ubiquinol, $QH_2$):**
   - Molécula lipídica benzoquinona móvil y liposoluble en el núcleo hidrofóbico de la bicapa lipídica ([[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 6 - Lípidos\|Lípidos de membrana]]).
   - Recoge equivalentes reductores del Complejo I, Complejo II y de la $\beta$-oxidación de ácidos grasos, transfiriéndolos al Complejo III.
4. **Complejo III (Citocromo $bc_1$ / Ubiquinona:Citocromo c Oxidorreductasa):**
   - Contiene citocromos $b$, citocromo $c_1$ y la proteína hierro-azufre de Rieske.
   - Opera mediante el **ciclo Q**, transfiriendo electrones desde el $QH_2$ al citocromo c y **bombeando $4\ H^+$** al espacio intermembranoso.
5. **Citocromo c:**
   - Proteína periférica globular soluble asociada electrostáticamente a la cara externa de la membrana interna.
   - Transporta un electrón por molécula desde el Complejo III hasta el Complejo IV.
6. **Complejo IV (Citocromo c Oxidasa):**
   - Contiene grupos hemo ($a$ y $a_3$) y centros de cobre ($Cu_A$ y $Cu_B$).
   - Cataliza la transferencia final de 4 electrones hacia el aceptor terminal de la respiración celular, el oxígeno molecular ($O_2$), reduciéndolo a dos moléculas de agua:
     $$O_2 + 4\ H^+ + 4\ e^- \longrightarrow 2\ H_2O$$
   - **Bombea $2\ H^+$** al espacio intermembranoso por cada par de electrones transferidos.

---

## 2. Hipótesis Quimiosmótica de Mitchell y Fuerza Protón-Motriz
Propuesta por Peter Mitchell (Premio Nobel 1978), postula que la energía libre desprendida por el transporte exergónico de electrones se almacena en forma de un gradiente electroquímico transmembrana de protones:
- Los complejos I, III y IV expulsan protones desde la matriz hacia el espacio intermembranoso ($10\ H^+$ por cada molécula de $NADH$ oxidada; $6\ H^+$ por cada molécula de $FADH_2$).
- Este bombeo crea la **fuerza protón-motriz ($\Delta p$)**, compuesta por:
  - Un gradiente químico de concentración ($\Delta pH \approx 0.75 - 1.0$ unidades de pH).
  - Un potencial eléctrico de membrana ($\Delta\Psi \approx 160 - 180\ mV$, con la matriz cargada negativamente respecto al espacio intermembranoso).

---

## 3. Síntesis de ATP: La ATP Sintasa (Complejo V)
La ATP sintasa es un nanomotor molecular rotacional que sintetiza ATP acoplado al retorno espontáneo de protones hacia la matriz a favor de su gradiente electroquímico:
- **Estructura:**
  - **Sector $F_0$:** Componente hidrofóbico inserto en la membrana interna que contiene el canal por donde fluyen los protones, provocando la rotación del anillo de subunidades $c$.
  - **Sector $F_1$:** Cabeza catalítica globular esférica proyectada hacia la matriz mitocondrial, compuesta por un hexámero $\alpha_3\beta_3$ fijo que contiene los sitios activos para la síntesis de ATP.
- **Mecanismo de Cambio de Unión (Paul Boyer):** La rotación del eje central $\gamma$ altera cíclicamente la conformación de los tres sitios catalíticos $\beta$ entre tres estados:
  1. *Abierto (O):* Muy baja afinidad; libera el ATP sintetizado y une ADP + $P_i$.
  2. *Laxo (L):* Mantiene atrapados al ADP y $P_i$ sin reaccionar.
  3. *Apretado (T):* Alta afinidad catalítica; une fuertemente los sustratos y cataliza la síntesis de ATP.
- **Relación P/O (ATP generado por par de electrones):**
  - $\approx 2.5\ ATP$ por cada $NADH$ oxidado.
  - $\approx 1.5\ ATP$ por cada $FADH_2$ oxidado.

---

## 4. Transporte de ATP y ADP (Translocasa de Nucleótidos de Adenina)
El ATP recién sintetizado en la matriz debe exportarse al citosol para sustentar las actividades celulares dependientes de energía, mientras que el ADP citosólico debe entrar a la matriz:
- La **Translocasa de ATP/ADP (ANT)** es una proteína antiporte electrogénica de la membrana interna que intercambia $ATP^{4-}$ hacia el citosol por $ADP^{3-}$ hacia la matriz.
- El **Simporte Fosfato/$H^+$** introduce fosfato inorgánico ($H_2PO_4^-$) acoplado al influjo de un protón, consumiendo parte de la fuerza protón-motriz.

---

## 5. Farmacología y Toxicología: Inhibidores y Desacopladores

### A. Inhibidores de la Cadena de Transporte de Electrones
Bloquean el flujo de electrones, deteniendo el bombeo de protones y el consumo de oxígeno:
- **Rotenona** (pesticida) y **Amital** (barbitúrico): Bloquean la transferencia de electrones en el **Complejo I**.
- **Antimicina A:** Bloquea el flujo electrónico en el **Complejo III**.
- **Cianuro ($CN^-$), Monóxido de Carbono ($CO$) y Azida:** Inhiben fuertemente el **Complejo IV** fijándose al hierro del hemo $a_3$, deteniendo instantáneamente la respiración celular (asfixia celular química letal).

### B. Inhibidores de la ATP Sintasa
- **Oligomicina:** Se une a la subunidad $F_0$ y bloquea físicamente el canal de protones, deteniendo la síntesis de ATP y, secundariamente por retroacoplamiento, el flujo de electrones.

### C. Desacopladores de la Fosforilación Oxidativa
Disipan el gradiente electroquímico de protones transportando $H^+$ de vuelta a la matriz mitocondrial sin pasar por la ATP sintasa:
- La cadena de electrones funciona a velocidad máxima consumiendo oxígeno, pero **no se sintetiza ATP**; toda la energía libre se libera en forma de **calor**.
- **2,4-Dinitrofenol (DNP):** Ionóforo sintético lipofílico desacoplante.
- **Termogenina (UCP-1 / Proteína Desacoplante 1):** Proteína canal fisiológica presente en las mitocondrias del tejido adiposo pardo, encargada de la **termogénesis sin temblor** en neonatos y mamíferos adaptados al frío.
r
