---
{"dg-publish":true,"permalink":"/morfo-i/unidad-iii-biologia-celular-y-genetica-molecular/tema-22-dogma-central-replicacion-y-reparacion-del-adn/","dg-note-properties":{}}
---

# Tema 22: Dogma Central de la Genética Molecular, Replicación y Reparación del ADN

## 1. El Dogma Central de la Genética Molecular
Enunciado por Francis Crick en 1958, describe la dirección unidireccional y universal del flujo de la información biológica en los sistemas vivos:
$$\text{ADN} \xrightarrow{\text{Replicación}} \text{ADN} \xrightarrow{\text{Transcripción}} \text{ARN} \xrightarrow{\text{Traducción}} \text{Proteína}$$

- **Replicación:** Duplicación fiel del ADN genómico para transmitirlo a la descendencia celular.
- **[[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 23 - Transcripción del ADN y procesamiento del ARN\|Transcripción]]:** Transferencia de la información contenida en un gen de ADN hacia una molécula de ARN mensajero.
- **[[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 25 - Código genético y síntesis de proteínas\|Traducción]]:** Decodificación del mensaje del ARNm en una secuencia de aminoácidos para construir una proteína funcional.
- **Excepciones al dogma clásico:** La **retrotranscripción o transcripción inversa** (flujo de $ARN \rightarrow ADN$ catalizado por la transcriptasa inversa en retrovirus como el VIH) y la replicación del genoma de ciertos virus de ARN (ARN dependiente de ARN).

---

## 2. Replicación del ADN: Características Generales
Ocurre durante la **Fase S** del [[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 28 - Cromosomas, ciclo celular, mitosis y meiosis\|Ciclo Celular]] en el núcleo celular. Posee tres propiedades universales:
1. **Semiconservativa (Meselson y Stahl, 1958):** Cada una de las hebras parentales sirve de molde para sintetizar una hebra hija complementaria. Cada molécula de ADN recién replicada consta de una hebra madre original y una hebra hija recién sintetizada.
2. **Bidireccional:** A partir de un sitio de origen de replicación (*ori*), la síntesis avanza simultáneamente en dos direcciones opuestas formando dos **horquillas de replicación**. En células eucariotas existen miles de orígenes de replicación por cromosoma para duplicar el genoma en pocas horas.
3. **Semidiscontinua:** Dado que las ADN polimerasas solo sintetizan en dirección $5' \rightarrow 3'$ y las dos hebras parentales son antiparalelas ($5' \rightarrow 3'$ y $3' \rightarrow 5'$), una de las hebras se sintetiza de forma continua mientras que la otra se sintetiza en fragmentos discontinuos.

---

## 3. Maquinaria y Mecanismo Enzimático en la Horquilla de Replicación
La replicación requiere un complejo coordinado de enzimas y proteínas auxiliares:

1. **Iniciación y Desenrrollamiento:**
   - **Helicasas:** Proteínas motoras dependientes de ATP que rompen los puentes de hidrógeno entre las bases complementarias, abriendo la doble hélice.
   - **Proteínas de Unión a Hebra Simple (SSB en bacterias; RPA en eucariotas):** Se unen al ADN monocatenario expuesto, impidiendo que vuelva a cerrarse la doble hélice o que sufra degradación enzimática.
   - **Topoisomerasas (ADN girasa en procariotas; Topo I y II en eucariotas):** Alivian el superenrollamiento positivo y la tensión torsional generada por delante del avance de la horquilla cortando y resellando transitoriamente una o ambas hebras del ADN.
2. **Síntesis del Cebador (Primer):**
   - Las ADN polimerasas no pueden iniciar la síntesis de una cadena de novo; requieren un extremo $3'-OH$ libre preexistente.
   - La enzima **Primasa** (ARN polimerasa dependiente de ADN) sintetiza un oligonucleótido corto de ARN ($\approx 10$ nucleótidos) denominado **cebador**.
3. **Elongación por las ADN Polimerasas:**
   - Las ADN polimerasas catalizan la adición secuencial de desoxirribonucleótidos complementarios ($dATP, dGTP, dCTP, dTTP$) al extremo $3'-OH$ libre:
     $$(ADN)_n + dNTP \xrightarrow{\text{ADN Polimerasa}} (ADN)_{n+1} + PP_i$$
   - **Hebra Conductora (Líder o Continua):** Su dirección permite una síntesis continua y sin interrupciones que progresa en la misma dirección del avance de la horquilla de replicación (catalizada por la ADN Polimerasa $\epsilon$ en eucariotas).
   - **Hebra Rezagada (Retardada o Discontinua):** Se sintetiza en dirección contraria al avance de la horquilla mediante fragmentos discontinuos de $100-200$ nucleótidos denominados **fragmentos de Okazaki** (catalizados por la ADN Polimerasa $\delta$ acoplada a la pinza proliferante PCNA).
4. **Maduración de los Fragmentos de Okazaki:**
   - Los cebadores de ARN son eliminados por endonucleasas (FEN1 y ARNasa H).
   - El espacio resultante es rellenado con desoxirribonucleótidos por una ADN polimerasa reparadora.
   - La enzima **ADN Ligasa** cataliza la formación del enlace fosfodiéster final dependiente de ATP, sellando las muescas entre fragmentos.
5. **Fidelidad y Corrección de Pruebas:**
   - Las ADN polimerasas poseen actividad **exonucleasa $3' \rightarrow 5'$ correctora de pruebas**. Si se incorpora un nucleótido mal apareado, la polimerasa retrocede, escinde el nucleótido erróneo y reanuda la síntesis correcta, reduciendo la tasa de error a menos de 1 por cada $10^9$ nucleótidos incorporados.
6. **Problema de la Replicación Terminal: Telomerasa:**
   - En los extremos de los cromosomas lineales (telómeros), la remoción del cebador de ARN en el extremo $5'$ de la hebra rezagada deja un hueco no replicable, lo que provocaría el acortamiento progresivo del cromosoma en cada ciclo celular.
   - La enzima **Telomerasa** (una ribonucleoproteína con actividad transcriptasa inversa que lleva su propio molde de ARN) extiende los extremos teloméricos en células germinales y células madre, evitando la pérdida de información genética.

---

## 4. Mecanismos de Reparación del ADN
El ADN está expuesto continuamente a agresiones ambientales (radiación UV, radicales libres, agentes alquilantes) y errores metabólicos:
- **Reparación por Escisión de Bases (BER):** Corrige modificaciones de bases aisladas (ej. desaminación espontánea de citosina en uracilo). La enzima *ADN glicosilasa* reconoce y corta la base alterada generando un sitio AP (apurínico/apirimidínico); una endonucleasa AP corta el esqueleto, la ADN polimerasa añade el nucleótido correcto y la ligasa sella.
- **Reparación por Escisión de Nucleótidos (NER):** Repara lesiones voluminosas que distorsionan la doble hélice, como los **dímeros de timina** inducidos por radiación ultravioleta. Una endonucleasa corta un oligonucleótido que contiene la lesión, y el hueco se sintetiza de nuevo. Su alteración genética produce la enfermedad autosómica recesiva **Xerodermia pigmentosa**.
- **Reparación de Apareamientos Erróneos (Mismatch Repair, MMR):** Complejo enzimático que detecta nucleótidos mal apareados que escaparon a la corrección de pruebas durante la replicación, reconociendo la hebra recién sintetizada. Mutaciones en los genes de MMR (MSH2, MLH1) causan el Síndrome de Lynch (cáncer colorrectal hereditario).
- **Reparación de Roturas de Doble Hebra:** Mediante *Recombinación Homóloga (HR)* (reparación precisa durante fases S y G2 utilizando la cromátida hermana) o *Unión de Extremos No Homólogos (NHEJ)* (reparación directa rápida pero propensa a mutaciones).

---

## 5. Desnaturalización y Renaturalización del ADN
- **Desnaturalización:** Separación de las dos hebras complementarias por ruptura de los puentes de hidrógeno debida al aumento de la temperatura o pH alcalino extremo, sin que se rompan los enlaces covalentes fosfodiéster.
- **Temperatura de Fusión ($T_m$):** Temperatura a la cual el 50% de la doble hélice se encuentra desnaturalizada; es mayor cuanto más alto sea el porcentaje de pares $G\equiv C$.
- **Renaturalización o Hibridación:** Si la temperatura desciende gradualmente por debajo de la $T_m$, las hebras complementarias se reconocen y vuelven a formar la doble hélice nativa.
