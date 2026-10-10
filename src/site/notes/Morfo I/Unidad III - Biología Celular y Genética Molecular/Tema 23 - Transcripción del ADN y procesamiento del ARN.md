---
{"dg-publish":true,"permalink":"/morfo-i/unidad-iii-biologia-celular-y-genetica-molecular/tema-23-transcripcion-del-adn-y-procesamiento-del-arn/","dg-note-properties":{}}
---

# Tema 23: Transcripción del ADN y Procesamiento Postranscripcional del ARN

La transcripción es el proceso biológico fundamental mediante el cual la información almacenada en una secuencia de [[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 21 - Nucleótidos y ácidos nucleicos\|Ácido desoxirribonucleico (ADN)]] se transfiere a una molécula de [[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 21 - Nucleótidos y ácidos nucleicos\|Ácido ribonucleico (ARN)]] catalizada por la enzima **ARN polimerasa dependiente de ADN**.

---

## 1. Principios Fundamentales de la Transcripción
- **Selectiva:** Solo se transcriben genes específicos o conjuntos de genes en respuesta a señales fisiológicas del desarrollo o del medio.
- **Hebra Molde vs. Hebra Codificante:**
  - *Hebra Molde (antisentido):* Es la hebra de ADN que lee la ARN polimerasa en dirección **$3' \rightarrow 5'$**.
  - *Hebra Codificante (sentido):* Es la hebra complementaria de ADN; su secuencia de bases es idéntica a la del ARN transcrito (con la única diferencia de que el ARN contiene Uracilo en lugar de Timina).
- **Dirección de Síntesis:** La ARN polimerasa sintetiza la nueva cadena de ARN exclusivamente en **dirección $5' \rightarrow 3'$**, incorporando ribonucleósidos trifosfato ($ATP, GTP, CTP, UTP$) y liberando pirofosfato.
- **Sin Necesidad de Cebador:** A diferencia de las ADN polimerasas, las ARN polimerasas pueden iniciar cadenas de novo sin cebador.

---

## 2. Tipos de ARN Polimerasas en Células Eucariotas
En el núcleo de las células eucariotas ([[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 20 - Núcleo, cromatina y nucléolo\|Núcleo]]) existen tres ARN polimerasas nucleares especializadas:

| Enzima | Localización Subnuclear | Transcritos Sintetizados | Sensibilidad a $\alpha$-Amanitina |
| :--- | :--- | :--- | :--- |
| **ARN Polimerasa I** | [[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 20 - Núcleo, cromatina y nucléolo\|Nucléolo]] | Precursor ribosomal $45S$ (que madura en los ARNr $18S, 28S$ y $5.8S$). | Insensible. |
| **ARN Polimerasa II** | Nucleoplasma | **Pre-ARNm** (ARN heterogéneo nuclear, hnARN), la mayoría de los microARN (miRNA) y snRNA. | Altamente sensible (inhibición potente por veneno de *Amanita phalloides*). |
| **ARN Polimerasa III** | Nucleoplasma | **ARNt**, ARNr $5S$ y otros ARN pequeños estables. | Sensibilidad intermedia. |

---

## 3. Etapas de la Transcripción por la ARN Polimerasa II

### A. Iniciación
1. **Promotores Basales:** Secuencias reguladoras en el ADN situadas inmediatamente río arriba del sitio de inicio de la transcripción ($+1$). El elemento canónico más común es la **caja TATA** (situada en $-25$ a $-30$ pb).
2. **Factores Generales de Transcripción (GTF):** Proteínas que se ensamblan en un orden estricto sobre el promotor para posicionar a la ARN Polimerasa II formando el **complejo de iniciación pretranscripcional**:
   - **TFIID:** Contiene la proteína de unión a TATA (**TBP**), que reconoce y flexiona la caja TATA.
   - **TFIIB, TFIIA, TFIIF, TFIIE:** Reclutan y fijan a la ARN Polimerasa II.
   - **TFIIH:** Posee actividad helicasa (que desenrolla el ADN consumiendo ATP para abrir la burbuja de transcripción) y actividad quinasa (que fosforila el dominio C-terminal -CTD- de la ARN Polimerasa II, liberándola del promotor para iniciar la fase de elongación).
3. **Potenciadores (Enhancers) y Silenciadores:** Secuencias distales reguladoras a las que se unen activadores o represores transcripcionales específicos.

### B. Elongación
La ARN Polimerasa II avanza a lo largo de la hebra molde de ADN, manteniendo una burbuja de transcripción abierta de unos 14 pares de bases y desenrollando el ADN por delante mientras lo rebobina por detrás. La tasa promedio de elongación es de unos 20-50 nucleótidos por segundo.

### C. Terminación
Al alcanzar el extremo $3'$ del gen, la ARN polimerasa transcribe una secuencia de señal de poliadenilación de consenso (**$5'-AAUAAA-3'$**). Esta secuencia es reconocida por endonucleasas asociadas al dominio CTD que cortan el ARN naciente entre 10 y 30 nucleótidos río abajo, liberando el transcrito primario.

---

## 4. Modificaciones Postranscripcionales del ARNm Eucariota (Maduración)
El transcrito primario (pre-ARNm) no es funcional para la traducción y debe sufrir tres modificaciones obligadas en el núcleo antes de ser exportado al citoplasma:

### 1. Adición de la Caperuza $5'$ (Capping)
Ocurre co-transcripcionalmente cuando la cadena tiene unos 20-30 nucleótidos:
- Se añade un residuo de **7-metilguanosina ($m^7G$)** al extremo $5'$ mediante un enlace inusual trifosfato $5'-5'$.
- **Funciones:** Protege al ARNm naciente de la degradación por exonucleasas $5'\rightarrow 3'$, facilita la exportación hacia el citoplasma y actúa como sitio de reconocimiento por los factores de iniciación de la traducción ([[Morfo I/Unidad III - Biología Celular y Genética Molecular/Tema 25 - Código genético y síntesis de proteínas\|Traducción]]).

### 2. Poliadenilación del Extremo $3'$ (Cola Poli-A)
- Tras la escisión endonucleolítica en la señal $AAUAAA$, la enzima **Poli-A Polimerasa (PAP)** añade de forma template-independiente una cola de **200 a 250 residuos de adenilato (cola de poli-A)**.
- **Funciones:** Confiere estabilidad metabólica al ARNm en el citosol (determina su vida media) y facilita la salida a través de los poros nucleares.

### 3. Corte y Empalme de Intrones (Splicing)
Los genes eucariotas son discontinuos o "mosaicos":
- **Exones:** Secuencias que codifican para aminoácidos o forman las regiones no traducidas funcionales ($UTR$).
- **Intrones:** Secuencias intercaladas no codificantes que deben eliminarse con precisión absoluta.
- **El Espliceosoma (Spliceosome):** Gran complejo macromolecular ribonucleoproteico formado por cinco complejos de ribonucleoproteínas nucleares pequeñas (**snRNP: U1, U2, U4, U5 y U6**) y más de 100 proteínas:
  - U1 se aparea con el sitio de corte $5'$ del intrón (consenso $GU$).
  - U2 se aparea con la secuencia de ramificación interna contigua a una Adenina invariante.
  - La adenina ataca nucleofílicamente al sitio $5'$, formando un intermediario en lazo (**lariat**).
  - El extremo $3'$ del exón ataca al sitio $3'$ del intrón (consenso $AG$), expulsando el intrón en lazo y ligando covalentemente los exones vecinos mediante enlace fosfodiéster.

---

## 5. Splicing Alternativo y Diversidad Proteica
El splicing alternativo es el mecanismo biológico por el cual diferentes combinaciones de exones del mismo pre-ARNm pueden unirse o excluirse selectivamente:
- Permite que un solo gen genómico codifique múltiples isoformas proteicas diferentes con propiedades cinéticas, afinidades o localizaciones tisulares específicas (ej. tropomiosinas musculares, receptores de membrana).
- Explica por qué el genoma humano con apenas $\approx 20.000$ genes codificantes de proteínas puede producir más de $100.000$ proteínas distintas en el proteoma.
