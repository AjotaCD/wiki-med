---
{"dg-publish":true,"permalink":"/morfo-i/unidad-iii-biologia-celular-y-genetica-molecular/tema-25-codigo-genetico-y-sintesis-de-proteinas/","dg-note-properties":{}}
---

# Tema 25: Código Genético y Síntesis de Proteínas (Traducción)

El código genético es el conjunto universal de reglas biológicas que define cómo las secuencias de nucleótidos del ADN y el ARN mensajero ([[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 21 - Nucleótidos y ácidos nucleicos\|Ácidos nucleicos]]) se traducen en secuencias lineales de aminoácidos ([[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 3 - Aminoácidos y péptidos\|Aminoácidos]]) para construir [[Morfo I/Unidad I - Biomoléculas y Membrana Celular/Tema 4 - Proteínas, mioglobina y hemoglobina\|Proteínas]].

---

## 1. Organización del Código Genético y Codones
- Los nucleótidos del ARNm ($A, G, C, U$) se organizan en tripletes consecutivos denominados **codones**.
- Dado que existen 4 bases distintas combinadas de 3 en 3, existen $4^3 = \mathbf{64\ codones\ posibles}$:
  - **61 codones** codifican para los 20 aminoácidos estándar.
  - **1 codón de inicio dual:** **AUG**, que codifica para la **Metionina** y marca simultáneamente el inicio del marco de lectura abierto.
  - **3 codones de terminación (Stop):** **UAA** (ocre), **UAG** (ámbar) y **UGA** (ópalo); no especifican ningún aminoácido y señalan la finalización de la traducción.
- **Marco de Lectura Abierto (ORF, Open Reading Frame):** Secuencia ininterrumpida de codones que comienza en un codón AUG y se extiende de forma continua hasta un codón de parada.

---

## 2. Características Fundamentales del Código Genético

1. **Degenerado (Redundante):** Múltiples codones diferentes especifican el mismo aminoácido (ej. la leucina y la arginina poseen 6 codones cada una).
   - **Hipótesis del Balanceo (Wobble de Crick):** El apareamiento entre las dos primeras bases del codón del ARNm y el anticodón del ARNt es estricto y canónico (Watson-Crick), pero la tercera base del codón ($3'$) y la primera base del anticodón ($5'$) presentan flexibilidad espacial ("balanceo"), permitiendo que una sola especie de ARNt reconozca varios codones sinónimos (ej. la inosina $I$ en el anticodón puede aparearse con $U, C$ o $A$).
   - Excepciones: El triptófano (UGG) y la metionina (AUG) tienen un único codón codificante cada uno.
2. **No Ambiguo:** Cada codón específico codifica para un único aminoácido sin excepción alguna.
3. **No Superpuesto:** La lectura no implica superposición; los codones se leen de tres en tres sin que ningún nucleótido sea compartido por codones adyacentes.
4. **Sin Puntuación (Continuo):** No existen señales espaciadoras ni bases intercaladas entre codones contiguos.
5. **Casi Universal:** El mismo diccionario genético es compartido por la práctica totalidad de organismos vivos, desde bacterias hasta seres humanos (con mínimas variaciones en el ADN mitocondrial, donde ej. UGA codifica triptófano en lugar de stop).

---

## 3. Maquinaria de la Traducción
- **ARN Mensajero (ARNm):** Molécula portadora del mensaje genético estructurado en codones.
- **ARN de Transferencia (ARNt):** Moléculas adaptadoras que portan un aminoácido esterificado en su extremo $3'-CCA$ y un triplete **anticodón** complementario al codón del ARNm.
- **Aminoacil-ARNt Sintetasas:** Familia de enzimas de alta fidelidad que catalizan la activación del aminoácido con ATP y su fijación específica al ARNt cognado:
  $$\text{Aminoácido} + ARNt + ATP \longrightarrow \text{Aminoacil-ARNt} + AMP + PP_i$$
- **[[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 24 - Ribosomas, retículo endoplásmico y aparato de Golgi\|Ribosomas]]:** Contienen tres sitios funcionales clave:
  - **Sitio A (Aminoacilo):** Recibe al nuevo aminoacil-ARNt entrante.
  - **Sitio P (Peptidilo):** Aloja al peptidil-ARNt que sostiene la cadena polipeptídica naciente.
  - **Sitio E (Exit / Salida):** Aloja transitoriamente al ARNt descargado antes de liberarse.

---

## 4. Etapas de la Síntesis de Proteínas

### A. Iniciación
1. La subunidad menor $40S$ se asocia con factores de iniciación eucariotas (eIFs) y el **Met-ARNt iniciador**, formando el complejo $43S$.
2. El complejo reconoce la caperuza $5'$ ($m^7G$) del ARNm y realiza el **escaneo** unidireccional $5' \rightarrow 3'$ a lo largo de la región $5'-UTR$ hasta identificar el codón de inicio **AUG** en el contexto de la secuencia Kozak.
3. Se ensambla la subunidad mayor $60S$ con hidrólisis de GTP, posicionando el Met-ARNt directamente en el **sitio P** del ribosoma $80S$ completo.

### B. Elongación
Ciclo repetitivo en 3 pasos:
1. **Entrada y Apareamiento:** Un nuevo aminoacil-ARNt específico entra al sitio A acoplado al factor de elongación eEF-1A y GTP.
2. **Formación del Enlace Peptídico:** La enzima **peptidil transferasa** (actividad ribozima del ARNr $28S$) transfiere la cadena peptídica del ARNt en el sitio P al grupo amino del aminoácido situado en el sitio A, formando un nuevo enlace peptídico sin consumir energía externa.
3. **Translocación:** El factor eEF-2 dependiente de GTP promueve el desplazamiento relativo del ribosoma exactamente tres nucleótidos a lo largo del ARNm: el ARNt descargado pasa al sitio E y se expulsa, el peptidil-ARNt pasa del sitio A al sitio P, y el sitio A queda vacante para recibir el siguiente codón.

### C. Terminación
1. Cuando un codón de parada (**UAA, UAG o UGA**) entra al sitio A, ningún ARNt lo reconoce.
2. Factores de liberación proteicos (**eRF1 y eRF3-GTP**) se unen al sitio A, induciendo a la peptidil transferasa a transferir la cadena polipeptídica a una molécula de agua.
3. Se libera la proteína recién sintetizada y el complejo ribosomal se disocia en sus subunidades libres.
