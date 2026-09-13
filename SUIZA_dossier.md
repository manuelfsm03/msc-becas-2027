# SUIZA — Dossier completo (8ª tanda)

> **Armado y verificado el 9-sep-2026** contra fuentes primarias: `studyprogrammes.ch` (API pública del sitio), `swissuniversities.ch`, `bde.es` (bases oficiales en PDF), `unisg.ch`, `mimecon.ch`, `unibas.ch`, `unil.ch`, `unige.ch`, `oec.uzh.ch`, `graduateinstitute.ch`, `bag.admin.ch`, `ideas.repec.org`.
> **Disparador:** consulta de Manuel sobre el listado de `studyprogrammes.ch` filtrado por Economía / Máster / inglés.
> **Qué resuelve:** el mapa suizo nunca se había barrido a fondo. Estaba cubierto sólo por el lado de las becas (ESKAS ❌, ETH ESOP ⚠️, EPFL Excellence ⚠️) y por una línea suelta en `CONTEXTO_MSC_traspaso.md`. Este archivo cubre programas, costos reales, financiación y fit contra la espina.

---

## 0. Las cinco conclusiones

1. **El pasaporte español no sirve para la matrícula en Suiza.** Suiza no está en la UE y no diferencia por ciudadanía: diferencia por **origen del título de secundaria** ("non-Swiss educational qualifications"). Con secundario argentino, Manuel paga tarifa extranjera en todas partes. Es la segunda excepción a la palanca central del proyecto, después de Irlanda — y por un mecanismo distinto.

2. **Pero la matrícula suiza es barata igual.** Entre CHF 870 y 8.000 al año según la universidad, contra £25-30k en UK. El problema suizo no es la matrícula, es **vivir**: CHF 19.000-30.000/año según la ciudad, más seguro de salud obligatorio.

3. **El pasaporte español sí sirve para tres cosas concretas, y una de ellas es una beca.** **HSG Best Talents** (St. Gallen) está restringida a nacionales UE/EFTA o permiso C suizo — cubre matrícula completa más aporte a costo de vida. Es la única beca de máster que encontré en Suiza cuya elegibilidad es exactamente lo que Manuel tiene. Las otras dos: permiso B UE/EFTA sin visado y **sin el tope de 15 h/semana ni la espera de 6 meses** que sí atan a los no-UE, y deadlines más holgados (UNIL: 30-abr para él, 28-feb para quien necesita visado).

4. **La financiación real de Suiza es española, no suiza.** El Banco de España cubre **matrícula completa sin tope** más **€21.500/año** para "España y el resto de los países europeos" — Suiza entra. Bajo el BdE, la matrícula deja de discriminar (HSG y IHEID pasan a costar cero) y lo único que separa a los destinos es el costo de vida de la ciudad.

5. **Suiza se comporta como UK, no como Alemania: necesita beca full sí o sí.** No hay DAAD suizo, no hay Master Mind, y Erasmus+ no la cubre. Pero a diferencia de UK, el hueco a tapar es sólo el costo de vida, y el derecho a trabajar sin tope permite taparlo en parte por cuenta propia.

---

## 1. Qué hay realmente en esa página

El listado que pasaste es la página 2 de 5. El filtro (Máster + área Economía/Negocios + inglés no exclusivo) devuelve **87 programas**, de los cuales la enorme mayoría no aplica:

- **~18 entradas de UZH de 30 ECTS son *minors*, no carreras** (Banking, Behavioral Economics, Development and Economic Policy, Quantitative Finance…). Son la segunda mitad del máster de UZH, no un programa propio.
- Management, marketing, turismo, comunicación, salud, informática: fuera.
- Varias figuran con `lang=de` porque el filtro pedía "incluye inglés", no "sólo inglés". Unifr, ZHAW, BFH y buena parte de UniBE son efectivamente en alemán.

⚠️ **El filtro `areas_of_study=1` deja afuera EPFL Financial Engineering y el MSc Quantitative Finance ETH-UZH**, que están clasificados en ingeniería/ciencias exactas. No es pérdida: confirma lo que el proyecto ya sabía (ETH y EPFL no tienen MSc Economics), pero conviene saber que ese listado no es exhaustivo del universo suizo.

**Lo que queda después del filtro real: nueve programas.**

| Programa | Institución | ECTS / dur. | Idioma | Matrícula/año (extranjero) | Track |
|---|---|---|---|---|---|
| **MEcon** | HSG St. Gallen | 90 / 3 sem | Inglés | CHF 6.634 | T2 (y T1) |
| **MA Economics** | UZH Zúrich | 120 / 4 sem | Inglés | CHF 1.640 | T1 + T2 |
| **MSc Economics** | UNIL Lausanne | 120 / 4 sem | Inglés | ~CHF 1.000-1.160 | T1 + T2 |
| **MIME — Intl & Monetary Economics** | Basel + Bern (joint) | 90 / 3 sem | Inglés | CHF 1.700 (vía Basel) | **T1 puro** |
| **MiQE/F** | HSG St. Gallen | 90 / 3 sem | Inglés | CHF 6.634 | T1 quant |
| **Master in International Economics** | IHEID Ginebra | 120 / 4 sem | Inglés | CHF 8.000 | T2 |
| **MSc Economics** | UNIGE Ginebra | 90 / 3 sem | Inglés | CHF 870 | T2 (econometría) |
| **MSc Applied Economic Analysis** | UniBE Berna | 90 / 3 sem | Inglés | CHF 5.100 | T2 |
| **MSc Applied Economics** | UniNE Neuchâtel | 90 / 3 sem | Inglés | CHF 1.550 | T2 |

USI Lugano (Economics 90 ECTS) y Unilu (Economics and Management) quedan afuera del análisis serio: USI cobra CHF 8.000/año y está #16 de Suiza en RePEc; Unilu es más chico todavía. No justifican el costo ni el riesgo.

---

## 2. Costos verificados

### 2.1 Matrícula — la tabla de swissuniversities (curso 2026-27)

Tarifa por **semestre**. La columna "extranjero" aplica a quien tiene título de secundaria no suizo. Manuel cae ahí siempre.

| Universidad | Suizos | Extranjeros | Año (extranjero) |
|---|---|---|---|
| Genève | 435 | 435 | **870** |
| Lausanne | 500 | 500 | **1.000** |
| Neuchâtel | 500 | 775 | 1.550 |
| Zürich (máster) | 720 | 820 | **1.640** |
| Basel | 850 | 850 | 1.700 |
| Luzern | 725 | 1.025 | 2.050 |
| **Bern** | 850 | **2.550** | **5.100** |
| **St. Gallen (máster)** | 1.284 | **3.317** | **6.634** |
| **USI Lugano** | 2.000 | **4.000** | 8.000 |
| IHEID Ginebra | — | 4.000 | **8.000** |
| ETH / EPFL | 730 | 2.190 | 4.380 |

Fuente: [swissuniversities — Tuition fees at universities](https://www.swissuniversities.ch/en/themen/lehre-studium/information-on-studies/tuition-fees/tuition-fees-at-universities). IHEID de su propia [página de fees](https://www.graduateinstitute.ch/fees-financial-aid) (CHF 5.000 residentes / 8.000 no residentes).

**Dato clave: Ginebra, Lausana, Zúrich y Basilea cobran menos de CHF 1.700 al año.** Eso es más barato que Países Bajos (€2.694) y comparable a Bélgica. Berna y St. Gallen sí penalizan fuerte al extranjero.

### 2.2 Costo de vida — el único número que importa

| Ciudad | CHF/mes | CHF/año |
|---|---|---|
| Zúrich · Ginebra | 2.000-2.500 | 24.000-30.000 |
| Lausana | 1.700-2.100 | 20.000-25.000 |
| **St. Gallen · Berna · Basilea** | 1.500-1.900 | **18.000-23.000** |
| Neuchâtel · Fribourg | ~1.600 | ~19.000 |

A eso se suma el **seguro de salud obligatorio (KVG/LAMal): CHF 280-380/mes**, o sea CHF 3.400-4.600/año, si no se consigue exención.

⚠️ **Vía de exención a verificar, vale ~CHF 4.000/año.** Los estudiantes UE/EFTA pueden pedir la *Befreiung von der Versicherungspflicht* si siguen asegurados en su país de residencia y presentan la Tarjeta Sanitaria Europea — pero **la condición se rompe si trabajan**, y la residencia de Manuel es Argentina, no España ([BAG, seguro para estudiantes extranjeros](https://www.bag.admin.ch/en/health-insurance-foreign-students-in-switzerland)). La vía practicable para él es probablemente la de terceros países: exención con seguro privado de cobertura equivalente al KVG, renovable. **Resolver con el cantón antes de presupuestar.**

---

## 3. La financiación

### 3.1 Banco de España — verificado contra las bases oficiales

Fuente primaria: [Bases 2026-27, Anuncio 28/2025 del 19-dic-2025](https://www.bde.es/f/webbde/PER/convoca/ficheros/descargar/Bases26_27.pdf), leídas completas el 9-sep-2026.

Lo que dicen, textual:

- **Dotación:** *"21.500 euros para los estudios realizados en España y en el resto de los países europeos"* (base 2.b.3). Suiza es un país europeo sin discusión. ✅
- **Matrícula:** *"Derechos de inscripción y matrícula en la correspondiente universidad o centro académico, que se abonarán previa justificación de los mismos"* (base 2.a). **Sin tope.** ✅
- **Dos años:** *"ayudar a financiar un máximo de dos cursos académicos, siempre que los estudios solicitados así lo requieran"*. Los programas suizos de 120 ECTS / 4 semestres (UZH, UNIL, IHEID) califican. ✅
- **Estancia:** 1-2 meses en el Banco entre junio y septiembre posteriores a cada curso, **+€1.550 por mes**.
- **Requisitos:** nacionalidad española + título de grado. **Las bases no exigen homologación del título ni universidad española** — esto acota (no cierra) el pendiente 9 del nodo. También: **no exigen experiencia laboral**, como ya estaba registrado.
- **Cierre 26-27:** 18-feb-2026, 14:00. Los informes de profesorado van **directo del profesor** a `investigacion.becas@bde.es`, misma fecha. Para 27-28, esperar ~18-feb-2027.

**Dos hallazgos nuevos de leer las bases completas:**

**(a) La incompatibilidad SÍ alcanza a las becas propias de universidad — pero con una excepción que vale mucho.** Base 7, textual:

> *"El disfrute de estas ayudas es incompatible con el disfrute simultáneo de cualquier otra ayuda, beca o remuneración, **excepto si se derivan de actividades de investigación en el área de especialización de la persona beneficiaria y sujetas, en todo caso, a autorización por parte del Banco de España**."*

Esto responde la **pregunta abierta #2 de `RECAP_becas_y_pairing.md`**, que estaba marcada como de alto impacto: "cualquier otra ayuda, beca o remuneración" cubre las becas propias de universidad. BdE + HSG Best Talents no se apilan. BdE + Warwick Regional o Bristol Think Big tampoco. **Pero la excepción no es sólo para becas: cubre *remuneración* derivada de investigación.** Un contrato de *Hilfsassistenz* / asistente de investigación en el departamento, en su área, con autorización del BdE, es plausiblemente compatible. Eso importa mucho más allá de Suiza. ⚠️ Confirmar por mail — es interpretación, no cita.

**(b) Riesgo de idioma específicamente suizo.** Base 1:

> *"Las personas participantes en el Programa deberán conocer suficientemente, a juicio del Banco de España, **el idioma del país donde vayan a realizar sus estudios**."*

En Suiza el idioma del país es alemán, francés o italiano — y los programas son en inglés. La lectura razonable es "idioma de instrucción", pero está escrito distinto y no hay precedente documentado en el proyecto. **Es barato de resolver y caro de suponer.** Va en el mismo mail que (a).

### 3.2 Aritmética: ¿alcanza el Banco de España en Suiza?

€21.500 ≈ **CHF 20.000** ⚠️ (asumiendo EUR/CHF ~0,93; el tipo de cambio mueve el resultado y hay que recalcularlo con el número del día). La matrícula va aparte y completa, así que sólo hay que cubrir vida + seguro:

| Ciudad | Vida + seguro | Cubierto por BdE | Hueco |
|---|---|---|---|
| **St. Gallen · Berna · Basilea** | 22.000-27.000 | 20.000 | **CHF 2.000-7.000** |
| Neuchâtel | ~23.000 | 20.000 | ~3.000 |
| Lausana | 24.000-29.000 | 20.000 | 4.000-9.000 |
| Zúrich · Ginebra | 28.000-34.000 | 20.000 | **8.000-14.000** |

Con la estancia paga en el Banco (+€3.100 por dos meses) el hueco baja otros ~CHF 2.900. Y el hueco restante es exactamente lo que cubre un trabajo de asistente — que Manuel puede tomar **sin tope de horas** por ser UE, a tarifas suizas.

**Lectura:** en St. Gallen, Berna o Basilea el Banco de España deja a Suiza esencialmente autofinanciable. En Zúrich y Ginebra, no alcanza solo.

### 3.3 HSG Best Talents — el hallazgo suizo

Fuente: [unisg.ch — HSG Best Talents](https://www.unisg.ch/en/studying/why-hsg/hsg-best-talents/), verificada 9-sep-2026. Textual:

> *"In general, all students from EU/EFTA countries as well as holders of a Swiss C-permit who are admitted to a Master's programme at HSG can apply."*

- **Cubre:** *"Coverage of tuition fees and contributions to living expenses"* + programa de desarrollo personal y acceso a la red HSG. ⚠️ **El monto del aporte de vida no está publicado** — hay que preguntarlo.
- **Cupo:** 39 en la cohorte 2026, escalando a 45 por cohorte.
- **Requisito previo:** hay que estar **ya admitido** a un máster de HSG. La beca no se aplica en paralelo, se aplica después.
- **Calendario:** la cohorte 2026 cerró el 12-jun-2026 con decisiones al 12-jul. **El portal reabre en noviembre de 2026 para la cohorte 2027** — que es exactamente el inicio que busca Manuel. Adjudicación *"on an ongoing basis"*, o sea que aplicar temprano conviene.
- **Criterios:** notas excelentes + compromiso extracurricular demostrado + sentido de responsabilidad social/económica/ambiental + diversidad de perspectivas.

Esto encaja con el perfil: cum laude, docencia en FCE-UBA, IIEP, el paper de biomasa regional. Y es **incompatible con el BdE** (§3.1.a), así que entra en la misma decisión de orden de preferencia que Areces y del Pino.

### 3.4 El resto de las becas suizas — confirmación de lo que ya sabíamos

| Beca | Estado | Detalle verificado 9-sep-2026 |
|---|---|---|
| **ESKAS / Swiss Government Excellence** | ❌ confirmado | El ciclo 2027-28 es Research Fellowship: exige **tener máster al 31-jul-2027** y propuesta de investigación con supervisor suizo. Sigue siendo material para el PhD, no para el máster. |
| **ETH ESOP** | ⚠️ sin cambios | ETH no tiene MSc Economics. Ventana 1-30 nov-2026. Sólo si entra MTEC o Quantitative Finance. |
| **EPFL Excellence** | ⚠️ sin cambios | Ídem. 1ª ronda 15-dic-2026. Fit sería Financial Engineering. |
| **UZH** | ❌ | Prácticamente nada a nivel máster. La universidad se apoya en que la matrícula ya es baja. |
| **IHEID** | ✅ parcial | Beca completa o parcial, **máximo CHF 20.000 por dos años**, mérito + necesidad, se pide junto con la admisión. Contra CHF 8.000 de matrícula y Ginebra a CHF 28.000+/año, no es paquete full. |
| **USI Lugano** | ✅ menor | 60 becas de CHF 4.000 (mérito + necesidad) = descuento de un semestre de matrícula. No toca el costo de vida. |
| **Erasmus Mundus** | ❌ ⚠️ | Suiza no participa de Erasmus+ como país asociado desde 2014; corre su propio SEMP, que es de intercambio, no de título. ⚠️ Verificar si algún consorcio EM la incluye como socio no asociado antes de descartarlo del todo. |

---

## 4. Fit con la espina

La espina vigente (`SOP_MAESTRO_desarrollo_policy.md` §1, `MATCH_grupos_profes_por_uni.md`): **identificación causal aplicada a preguntas macro y de política pública, endgame Ministerio de Economía / Banco Central.**

### 4.1 Ranking de investigación (RePEc, julio-2026)

Posición **dentro de Suiza**: 1º Universität Zürich · 2º BIS · 3º UNIL (HEC) · 4º ETH D-MTEC · 5º IHEID · 6º Universität Bern · 7º Universität St. Gallen · 8º Swiss Finance Institute · 9º SNB · 10º Basel · 11º Genève · 16º USI · 21º Neuchâtel. ([IDEAS/RePEc — Suiza](https://ideas.repec.org/top/top.switzerland.html))

Nótese quiénes están en esa lista: **el BIS (Basilea), el SNB (Berna/Zúrich) y el Swiss Finance Institute**. Para un endgame de banca central, el ecosistema suizo es un argumento en sí mismo, y es un argumento que ninguna carta a Alemania o UK puede hacer con la misma fuerza salvo Goethe/ECB.

### 4.2 Los programas, ordenados por fit

**1 · HSG MEcon (St. Gallen) — ★★★★ el mejor fit suizo, y por un margen amplio**

El **SEW-HSG** (Swiss Institute for Empirical Economic Research), dirigido por **Michael Lechner**, hace literalmente lo que dice la carta: *causal machine learning* aplicado a evaluación de política pública, con datos administrativos suizos sobre programas activos de mercado laboral, financiado por el SNSF dentro del NRP 75. Es la línea de investigación que más se parece a la espina de todo el mapa europeo relevado hasta ahora — comparable a Frölich en Mannheim y a Han en Bristol, con la diferencia de que acá el instituto entero está organizado alrededor de eso. ([SEW-HSG — Economic Policy and Causal Machine Learning](https://sew.unisg.ch/empirical-economics-and-econometrics/team-michael-lechner/research/economic-policy-and-causal-machine-learning/), verificado 9-sep-2026)

Y encima:
- **GRE/GMAT es OPCIONAL.** Vale 25% del score; si no se presenta, *"the grade point average is weighted twice"*. Es la única puerta a una universidad suiza de primera línea que no obliga a rendir GRE — y el cum laude 7,82 es lo que se pondera doble. Para el GRE que sí se presente, en GRE cuenta **Quantitative Reasoning**.
- Ventana de aplicación **1-oct al 31-mar**, CHF 250.
- Requisito de título: bachelor con ≥60 ECTS en materias core de economía (Micro, Macro, Econometría, Teoría de Juegos, Economía Internacional). Administración de empresas no cuenta. La Lic. en Economía de la UBA pasa cómoda.
- **Elegible para HSG Best Talents.**
- **La ciudad más barata de la lista.**

> **Matcheo completo de centros, profesores y objetos citables: `MATCH_grupos_profes_por_uni.md` → BLOQUE SUIZA (10-sep-2026).** Resumen: el SEW-HSG tiene las dos mitades de la tesis del SOP bajo un mismo techo — Lechner por el método y **Winfried Koeniger** (director del instituto) por el escalamiento a macro, con un proyecto SNSF sobre transmisión de política monetaria y fiscal identificada con datos transaccionales de alta frecuencia. Objetos citables por nombre: el paquete de Python **`mcf`** que el instituto desarrolla, el curso **Causal Inference** de **GSERM**, y la especialización **Public Policy** del propio MEcon.

Contras: HSG carga fama de escuela de negocios; el departamento de economía es chico (RePEc #7 en Suiza). Requisitos administrativos particulares: **dos cursos de idioma extranjero obligatorios para graduarse** y **prueba de conocimientos de contabilidad** o examen. Y *"integration week Economics"* obligatoria antes de arrancar para quien viene de una disciplina similar.

**2 · UZH MA Economics (Zúrich) — ★★★★ el mejor departamento, la peor economía**

RePEc #1 de Suiza y top-10 europeo. En el claustro: **Dina Pomeranz** (finanzas públicas y tributación en países en desarrollo, evaluación de impacto), **David Yanagizawa-Drott** (desarrollo y economía política, J-PAL / BREAD / CEPR), Lorenzo Casaburi, David Dorn, Ulf Zölitz, Mathias Hoffmann (macro internacional). Es el departamento suizo donde el T2 tiene más densidad real. Además UZH **ya figura en el proyecto** como una de las plazas europeas de la ruta predoc (`NODO_MAESTRO` §"Ruta predoc"), lo que la vuelve doblemente coherente con el endgame PhD.

Contras: 120 ECTS / 4 semestres, estructurado como **Major 90 + Minor 30** (los "minors" del listado que pasaste son justamente eso). Zúrich es la ciudad más cara de Suiza, el BdE se queda corto ahí, y UZH no tiene beca de máster. ⚠️ **Deadline de aplicación sin verificar** — hueco de esta tanda.

**3 · UNIL MSc Economics (Lausana) — ★★★★ el único programa que cubre los dos tracks explícitamente**

Sus especializaciones son, textual: Data Science · **Development Economics** · Environmental Economics · **Macroeconomic Policy** · Microeconomic Policy · **Public Economics** · **Quantitative Economics**, más la especialización Behaviour, Economics and Evolution. Eso es T1 y T2 en un solo título, con la opción de tomar **dos** menciones. RePEc #3 de Suiza. Inglés, 120 ECTS, matrícula ~CHF 1.000.

Y acá aparece la ventaja del pasaporte: **el deadline general es el 30 de abril; el 28 de febrero es sólo para quien necesita visado.** Como ciudadano UE, Manuel cae en el 30-abr. Es el mismo mecanismo que se encontró en Konstanz (`DAAD_STUDY_SCHOLARSHIP_dossier.md`).

⚠️ **Riesgo abierto y decisivo:** UNIL avisa que *"some applicants, such as those from universities of applied sciences or universities outside Switzerland, must successfully complete a bridging programme"*. Si a un título de la UBA le exigen *mise à niveau*, el programa pasa de 4 a 5-6 semestres y el cálculo de financiación se rompe. **Preguntar a `HECmasterAdmission@unil.ch` antes de invertir en esta vía.** Inglés: TOEFL 100 / IELTS 7 (más alto que el estándar).

**4 · MIME — International and Monetary Economics (Basilea + Berna) — ★★★ el T1 puro**

Joint degree, 90 ECTS / 3 semestres, en inglés. Es el equivalente suizo más cercano a Goethe MMF, y con mejor entorno institucional: **Basilea es la sede del BIS**, **Berna la del SNB** y el **Study Center Gerzensee** (fundación del propio SNB) está a media hora.

Vía Basilea es la barata y la más flexible: **CHF 850/semestre**, deadline **30 de abril** con tolerancia hasta el **31 de julio**, CHF 100 de tasa. Admisión: bachelor reconocido con logros equivalentes en economía y métodos cuantitativos, **nota mínima 5,0/6**; el GRE se acepta **como alternativa a la nota** si Quantitative Reasoning y Analytical Writing están en el 30% superior. ([mimecon.ch — admisión Basilea](https://mimecon.ch/admission/basel/))

⚠️ **Un 7,82/10 de la UBA probablemente no convierta a 5,0/6 suizo** (5,0 es aproximadamente un 8,3). Si es así, **el GRE pasa a ser obligatorio por esta vía**. La vía Berna es más dura todavía: exige 5,0 de universidad suiza o GRE/GMAT en el rango superior, y Berna cobra CHF 5.100/año de matrícula contra los 1.700 de Basilea. **Si se va por MIME, es por Basilea.**

**5 · HSG MiQE/F — ★★★ el T1 cuantitativo, con peaje de GRE**

Mismo ecosistema que MEcon (mismo campus, mismo Best Talents, misma ciudad barata), pero **GMAT o GRE es obligatorio**, más writing sample. Ventana 1-oct al 30-abr. Es más quant y más finanzas que MEcon; el fit con la espina es peor porque el eje es método cuantitativo, no identificación causal. **Dato útil:** si se aplica antes del 31 de enero se puede designar un **programa alternativo** (MEcon o MACFin) que se evalúa automáticamente si MiQE/F rechaza. O sea: una sola aplicación, dos tiros.

**6 · IHEID Ginebra — ★★★ el T2 de política, con la única beca propia decente**

Master in International Economics o International and Development Studies, 120 ECTS. RePEc #5 de Suiza. Ginebra es el nodo de organismos internacionales (OMC, UNCTAD, OIT), lo cual sirve al endgame de política pública aunque no al de banco central. Su ayuda financiera (hasta CHF 20.000 por dos años, mérito + necesidad, con la admisión) es la más real de Suiza después de HSG. Pero: matrícula CHF 8.000, ciudad carísima, y es una escuela de política internacional más que un departamento de economía. **Sin el BdE no cierra.**

**7 · UNIGE MSc Economics — ★★ barata y con econometría, pero flaca**

La matrícula más barata de Suiza (CHF 870/año) y una especialización declarada en econometría. Deadline **28 de febrero**. Pero RePEc #11 de Suiza y Ginebra es la ciudad más cara. La combinación no cierra.

**8 · UniBE Applied Economic Analysis — ★★** Berna tiene un grupo de econometría aplicada respetable y está pegada al SNB, pero cobra CHF 5.100/año de matrícula al extranjero (3× la tarifa suiza) sin nada que lo compense. Si se quiere Berna, MIME vía Basilea da el mismo ecosistema por un tercio.

**9 · UniNE Applied Economics — ★** Barata y en inglés, pero RePEc #21 de Suiza. Sólo tendría sentido como plan de contención.

---

## 5. Dónde queda Suiza contra lo que ya está en el mapa

- **Contra Alemania (Bonn / Mannheim / Goethe MMF + DAAD):** Alemania gana en financiabilidad y no está cerca. Matrícula gratis por pasaporte + DAAD €992/mes = paquete full **sin depender del BdE**. Suiza sin BdE ni Best Talents no cierra. Suiza gana en entorno institucional para T1 (BIS + SNB + Gerzensee) y, en el caso de HSG, en fit de método.
- **Contra UK:** si el BdE cae, **Suiza domina a UK con claridad**. Matrícula CHF 1.000-6.600 contra £25-30k, departamentos en promedio más fuertes, y el derecho a trabajar sin tope que UK no da. Y a diferencia de UK, Suiza tiene una vía alternativa propia (Best Talents) si el BdE no sale.
- **Contra CEMFI/BSE:** CEMFI mantiene la ventaja de coherencia institucional con el BdE (es su propia Fundación) y de costo. Suiza no compite ahí.
- **Ubicación tentativa en el ranking del Excel:** HSG MEcon y UNIL entran en la banda de los top picks continentales **condicionado a BdE o Best Talents**; sin ninguno de los dos, puntúan como UK (financiación incierta). UZH puntúa alto en fit y prestigio y bajo en costo neto por Zúrich. ⚠️ Los scores hay que calcularlos en la planilla, no acá.

---

## 6. Calendario suizo, insertado en el del proyecto

| Cuándo | Qué |
|---|---|
| **1-oct-2026** | Abre la ventana de aplicación de HSG (MEcon y MiQE/F) |
| **nov-2026** | **Reabre el portal de HSG Best Talents para la cohorte 2027.** Adjudicación rolling → aplicar temprano |
| 1-30 nov 2026 | ETH ESOP (sólo si entra MTEC/QF) |
| 15-dic-2026 | EPFL Excellence 1ª ronda (ídem) |
| ~dic-2026 | Salen las bases BdE 2027-28 → **mandar el mail con las tres preguntas de §7** |
| ene-2027 | IELTS. UNIL pide **TOEFL 100 / IELTS 7**, más alto que el estándar del proyecto |
| 31-ene-2027 | Límite para designar programa alternativo en la aplicación de MiQE/F |
| **28-feb-2027** | UNIGE cierra |
| ~18-feb-2027 | **BdE cierra** (+ informes de profesorado, misma fecha, enviados por ellos) |
| **31-mar-2027** | **HSG MEcon cierra** |
| **30-abr-2027** | HSG MiQE/F cierra · **UNIL cierra** (30-abr por ser UE, no 28-feb) · **MIME Basilea** cierra (tardías hasta 31-jul) |
| sep-2027 | Inicio |

---

## 7. Pendientes que abre este dossier

**Alta prioridad — bloquean decisiones:**

1. **Mail al BdE (`per.investigacion.becas@bde.es`), tres preguntas en uno, cuando salgan las bases ~dic-2026:**
   - (a) ¿"Conocer el idioma del país" se satisface con inglés si el programa se dicta íntegramente en inglés en Suiza?
   - (b) ¿Un contrato de asistente de investigación en el departamento, en el área de especialización, entra en la excepción de la base 7 sobre remuneración derivada de actividades de investigación?
   - (c) Confirmar que un grado de la UBA sin homologar cumple el requisito de "título de licenciatura o de grado universitario" (las bases 26-27 no exigen homologación, pero conviene tenerlo por escrito). *Cierra el pendiente 9 del nodo.*
2. **Mail a HSG:** monto exacto del aporte a costo de vida de Best Talents, y si es compatible con una beca externa. Determina si Best Talents es alternativa real al BdE o sólo complemento.
3. **Mail a `HECmasterAdmission@unil.ch`:** ¿un título de la UBA dispara *bridging programme*? Si sí, cuántos semestres. **UNIL no se puede rankear hasta saber esto.**
4. **Conversión de nota UBA → escala suiza /6.** Determina si MIME exige GRE. Preguntar a la oficina de admisiones de Basilea con el analítico.

**Media:**

5. Deadline de aplicación de UZH para el semestre de otoño (⚠️ no verificado en esta tanda).
6. Exención del KVG: consultar al cantón de destino cuál de las dos vías (EHIC vs. seguro privado equivalente) aplica a un ciudadano español residente en Argentina. Vale ~CHF 4.000/año.
7. Tarifas reales de *Hilfsassistenz* en los departamentos objetivo. Es la línea que cierra el hueco del BdE en las ciudades caras.
8. ⚠️ Confirmar que ningún consorcio Erasmus Mundus del área de economía tenga socio suizo.

---

## 8. Nota de método

Los resultados de `studyprogrammes.ch` no se renderizan en el HTML (es una app Next.js que consulta `api.studyprogrammes.ch`). Los 87 programas se obtuvieron llamando directo a `list_studyprogrammes` con los mismos parámetros de la URL, paginando las 5 páginas y deduplicando. **Si hace falta volver a barrer el catálogo suizo, ése es el camino** — el fetch de la página devuelve sólo el cascarón.
