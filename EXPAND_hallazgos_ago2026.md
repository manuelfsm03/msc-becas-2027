# EXPAND — Lo que no estabas teniendo en cuenta (2-ago-2026)

> Barrida de tipo *coverage-gap*: en vez de buscar "más becas" (eso ya estaba saturado), diffeé **de dónde** salió todo lo guardado contra las clases de fuente posibles, y busqué en las que nunca se tocaron. Cada hallazgo lleva fuente primaria y fecha de verificación.

---

## 1. El diff: por qué la barrida parecía saturada y no lo estaba

De las nueve clases de fuente posibles, el archivo (nodo maestro + `BECAS_veredictos_lista_24.md` + `BECAS_nordicos...` + `BECAS_top4_UK...`) viene de **tres**:

| Clase de fuente | Estado en el archivo |
|---|---|
| `primary_funder` (DAAD, Chevening, McCall, la Caixa…) | ✅ exhaustivo |
| `applicant_side_national` — lado **argentino** (Campus Argentina Global, BEC.AR) | ✅ barrido |
| `catalogue` / listas sociales (lista de 24, post de Instagram) | ✅ barrido |
| `applicant_side_national` — lado **español** | ❌ **nunca** (solo fundaciones privadas) |
| `institute_direct` (bancos centrales, institutos de investigación) | ❌ nunca |
| `vacancy_board` (EURAXESS, econjobmarket, predoc.org) | ❌ nunca |
| `capacity_database` (CORDIS, GEPRIS, ERC) | ❌ nunca |
| `structured_programme` (escuelas de posgrado, ASP, IMPRS) | ❌ nunca |
| `bibliographic` / `peer_and_lived` | ⚠️ solo para McGill |

Por tipo de financiador, `opportunities` está 100 % en **universidad / fundación / gobierno**. Cero entradas de tipo **empleador**, **industria** o **institución pública no-ministerial**.

**Conclusión:** la conclusión de la 6ª tanda ("no hay agujeros relevantes") era cierta *dentro de las clases buscadas*. El agujero grande no era una beca más: era que nunca se miró el lado español del Estado ni la ruta de empleo remunerado.

---

## 2. ⭐⭐ Banco de España — Programa de ayudas para estudios en economía y finanzas

**Es, con diferencia, el hallazgo principal.** Fuente primaria: [bases oficiales, Anuncio 28/2025 de 19-dic-2025](https://www.bde.es/f/webbde/PER/convoca/ficheros/descargar/Bases26_27.pdf) (curso 2026-2027) · verificado 2-ago-2026.

| Campo | Dato |
|---|---|
| Qué cubre | **Matrícula completa** (aparte, previa justificación) **+ €21.500/año** para España y resto de Europa · £18.500 UK · US$29.000 EEUU |
| Duración | Hasta **2 cursos académicos** si los estudios lo requieren |
| Extra | Estancia de 1-2 meses en el Banco de España por año de ayuda, **+€1.550/mes** |
| Plazas | 10 |
| Elegibilidad | **Nacionalidad española** + título de licenciatura o **grado universitario, o de otro análogo** |
| Destino | Libre elección del centro y de la titulación (posgrado oficial en economía/finanzas) |
| Deadline | 18-feb-2026 para el ciclo 2026-27 → **el ciclo 2027-28 debería abrir ~dic-2026 y cerrar ~feb-2027** |
| Requisito oculto | **2 o más informes de profesorado universitario**, enviados **directamente por los profesores** a `investigacion.becas@bde.es`, redactados *ex profeso* para esta convocatoria |
| ⚠️ Bloqueo | **Incompatible con el disfrute simultáneo de cualquier otra beca o remuneración** (salvo investigación autorizada por el BdE) |

**Por qué importa tanto:**

- Las bases **no exigen que el grado sea de universidad española** — dicen "título de licenciatura o de grado universitario, o de otro análogo". Ese es exactamente el filtro que mató a la Caixa. Acá no aparece.
- Cubre **UK igual que el continente**: £18.500 + matrícula pagada convierte a Bristol/Warwick/Glasgow en viables **sin Chevening**.
- El fit temático con el Track 1 es casi absurdo: la evaluación pondera "la correspondencia entre los estudios y las **prioridades analíticas y de investigación**" del BdE, y la estancia te mete en el departamento de investigación de un banco central. Es el mismo argumento que Goethe MMF/ECB, pero con el dinero adentro.

**Por verificar (no lo dan las bases):** si exigen homologación del título de la UBA. Preguntar a `per.investigacion.becas@bde.es`. Es la única duda seria.

**Tensión estratégica:** al ser incompatible con otra beca simultánea, el BdE **reemplaza** a Chevening / Areces / del Pino, no se suma. Como Areces y del Pino son también vía [ESP] y de calendario parecido (feb), hay que decidir un orden de preferencia antes de febrero-2027, no en el momento.

---

## 3. ⭐ EUI Florencia — hay un cupo nacional español que nadie mira

Fuente primaria: [EUI · Spain/España funding](https://www.eui.eu/en/services/academic-service/doctoral-programme/funding-information/spainespana) · página actualizada 4-nov-2025 · verificado 2-ago-2026.

- **12 becas** para el proceso 2026-2027, financiadas por el **Ministerio de Ciencia, Innovación y Universidades**.
- €1.650/mes + ayuda de viaje + seguro de salud. **No hay solicitud separada**: postularse al doctorado del EUI *es* postularse a la beca nacional.
- Contacto: `becas.iue@universidades.gob.es`.

**Ojo con qué es y qué no es:** esto es el **doctorado**, exige máster oficial terminado (o en curso terminando antes del 31-ago). O sea, no sustituye al MSc 2027 — es el paso siguiente. Pero cambia la estrategia de elección de máster: si el objetivo real es el PhD, España te tiene reservado un carril de 12 plazas en un instituto europeo serio, y conviene elegir un MSc que el EUI mire bien (research master cuantitativo).

⚠️ **Trampa a verificar antes de contar con esto:** la elegibilidad dice *"Citizenship or Legal Residence in Spain for at least two years prior to the application"*. Es ambiguo si el "two years" aplica también a los ciudadanos. Es **exactamente** el mismo patrón que ya te tumbó en la Caixa, GREAT España e Irlanda. Escribir a `becas.iue@universidades.gob.es` antes de darlo por bueno.

---

## 4. La ruta que directamente no está en el archivo: predoc / RA remunerado

Ninguna entrada del archivo es de tipo **empleo**. Y para tu perfil exacto (Python, econometría aplicada, inferencia causal, ya con research fellowship en IIEP) esta es la ruta estándar de preparación para doctorado en economía.

Lo clave: **es un sueldo, no una matrícula**. Por lo tanto **no viola tu política de "Norteamérica solo con full funding"** — no hay nada que financiar.

- Tablero principal verificado: [predoc.org/opportunities](https://www.predoc.org/opportunities) y [EconJobMarket](https://econjobmarket.org/market) (secciones RA / Pre-Doc).
- **En Europa** (los que aparecen listados): Oxford — Global Priorities Institute, CSAE y EIT Oxford; Sciences Po Paris (Suzanna Khalifa); Universidad de Zúrich (admisión rolling); LSE Centre for Economic Performance; Manchester (Arthur Lewis Lab).
- **En EEUU** los volúmenes grandes: Federal Reserve Board y Feds regionales (Atlanta, Boston, Chicago, Cleveland, Kansas City, NY, Richmond, St. Louis), Yale Tobin Center, Princeton IRS y SPIA, Chicago BFI, MIT, Stanford SIEPR, Opportunity Insights.
- **Ciclo:** las convocatorias se concentran **oct-ene** con arranque en verano. O sea: si esto te interesara para 2027, se decide en **octubre-2026**, en paralelo con Chevening.

No te lo estoy recomendando por encima del máster — te lo señalo porque es una rama del árbol que nunca se abrió, y resuelve el problema de fondo (financiar la preparación para PhD) por una vía distinta a la beca.

---

## 5. Kiel Institute — Advanced Studies Program (ASP)

[Kiel Institute · ASP](https://www.ifw-kiel.de/institute/advanced-studies-program/) · verificado 2-ago-2026.

10 meses, macroeconomía internacional / finanzas internacionales / comercio / economía política internacional. **Sin matrícula**, y a los admitidos se les ofrece **beca de €1.750/mes por 16 meses**. Exige máster en economía ya terminado al momento de entrar. Explícitamente orientado a colocar en el job market internacional o en instituciones de policy.

Igual que el EUI: es la pieza **posterior** al MSc, no un sustituto. Vale la pena tenerlo en el mapa porque cambia el cálculo de "1 año vs. research master de 2 años" — si existe un puente financiado post-máster, el máster de 1 año pierde su principal desventaja.

---

## 6. Erasmus Mundus: el catálogo nunca se barrió de verdad

El [catálogo oficial EACEA](https://www.eacea.ec.europa.eu/scholarships/erasmus-mundus-catalogue_en) tiene **220 proyectos** y un filtro por campo **"Economic Sciences (ECO)"**. En el archivo solo figuran QEM y EPOG+ — que llegaron por conocimiento previo, no por barrer el catálogo.

Dos datos del propio catálogo: **Argentina** está en la lista de países participantes, y la **Universidad de Buenos Aires** figura como institución del catálogo. Vale revisar si aparece en algún consorcio ECO — sería una ventaja de contexto real.

Acción concreta: filtrar por ECO + años de selección 2023/2024/2025 y cotejar contra la hoja "Todos los programas". Las ventanas con beca cierran entre **noviembre y enero**.

---

## 7. Contactos — qué encontré y qué no

**Lo honesto primero:** no logré verificar personas nombradas nuevas para los destinos continentales con fuentes baratas, y no las voy a inventar. Pero encontré algo más útil que una lista de profesores:

**Para los MSc taught del continente (Goethe, Bonn, Mannheim, PSE, Aarhus, Tilburg), mailear profesores tiene ROI bajo.** La admisión es por comité y no se exige supervisor — al revés de McGill MA, donde el supervisor confirmado es requisito *al momento de aplicar*. El esfuerzo de outreach está bien puesto donde está (McGill), y no hay que replicarlo en Europa.

**Contactos que sí son accionables ahora, verificados:**

| Contacto | Para qué | Fuente |
|---|---|---|
| `investigacion.becas@bde.es` | Destino de los **informes de profesorado** del BdE (los envían ellos, no vos) | bases BdE, base 4 |
| `per.investigacion.becas@bde.es` | Consultas de elegibilidad BdE — acá va la pregunta de la homologación del título UBA | bases BdE, base 9 |
| `becas.iue@universidades.gob.es` | Consultas del cupo español del EUI — acá va la pregunta de los 2 años de residencia | página EUI Spain |

**Sinergia que vale plata:** los **2+ informes de profesores** del Banco de España y las **2 referencias** de McCall MacBain son, casi con certeza, **los mismos profesores de la FCE-UBA**. Estás pidiendo referencias esta semana para McCall (deadline 19-ago). Pedíles las dos cosas de una vez y avisales que en febrero-2027 viene una segunda ronda para el BdE — es mucho más barato que volver a golpear la puerta en enero.

---

## 7 bis. Chevening: primero la fecha estaba mal, después resultó que no era elegible

**Desenlace (2-ago-2026): Chevening quedó ❌ DESCARTADA por elegibilidad.** Exige *"at least two years' work experience, **acquired after completing your undergraduate degree**"* ([criterios oficiales](https://www.chevening.org/resource-hub/guidance/eligibility/)), más una segunda cláusula que pide haber terminado el grado al menos 2 años antes del deadline. Manuel no llega. El perfil del proyecto decía ">2 años de experiencia profesional" contando experiencia **total**, y ese era el error de fondo — ver §2 bis del nodo maestro, porque la misma regla pone en riesgo a DAAD EPOS y al World Bank JJ/WBGSP.

Lo que sigue se conserva como registro de la corrección de calendario que se había hecho antes de descubrir la inelegibilidad:

Todos los archivos del proyecto decían **"7-oct-2026: abre Chevening"**. La [línea de tiempo oficial](https://www.chevening.org/scholarships/application-timeline/) (verificada 2-ago-2026) dice otra cosa:

| Hito Chevening 2027-28 | Fecha real |
|---|---|
| **Abre** | **4-ago-2026, 11:00 UTC** — pasado mañana |
| **Cierra** | **6-oct-2026, 11:00 UTC** |
| Sift de elegibilidad | desde oct-2026 |
| Comités de lectura | mediados de oct-2026 a ene-2027 |
| Shortlist para entrevista | mediados de feb-2027 |
| Entrevistas | mar-abr 2027 |
| Resultados | desde mediados de jun-2027 |
| **Oferta INCONDICIONAL de una uni UK** | **8-jul-2027, 17:00 BST** |

**Octubre no era el arranque: era el cierre.** La ventana real son ~9 semanas, y adentro entran los 4 essays, el CV y la coordinación de referencias — solapándose con el tramo final de McCall MacBain (19-ago). Las dos piden material de liderazgo y servicio comunitario, así que hay reciclaje posible.

Corregido en: `NODO_MAESTRO_MSC_2027.md`, `masters_dashboard.html`, `GANTT_becas_MSc_2027.xml` (4 celdas), `INOVA_todo_documentos.md`, `BECAS_top4_UK_barrida.md`, `MCCALL_MCGILL_plan_ataque.md`, y marcado en los dos documentos supersedidos.

---

## 8. Qué hacer con esto

**Inmediato (esta semana, aprovechando que ya estás pidiendo referencias para McCall):**

1. Avisar a los profesores de la FCE-UBA que además de McCall va a haber informes para el Banco de España en ~febrero-2027.
2. Mail a `per.investigacion.becas@bde.es`: ¿el título de grado de una universidad extranjera requiere homologación para esta convocatoria?

**Septiembre-octubre 2026:**

3. Mail a `becas.iue@universidades.gob.es` sobre el requisito de residencia del cupo EUI.
4. Decidir si la ruta predoc entra en juego (las ventanas son oct-ene).
5. Filtrar el catálogo Erasmus Mundus por ECO y cotejar contra el Excel.

**Diciembre 2026 – febrero 2027:**

6. Vigilar la publicación de las bases BdE 2027-2028 (patrón: anuncio a mediados de diciembre, cierre ~18 de febrero).
7. **Decidir el orden de preferencia entre BdE / Areces / del Pino / Chevening antes de febrero** — el BdE es incompatible con cualquier otra beca simultánea y todas caen en la misma ventana.

**Pendiente de una segunda pasada:** contactos nombrados para el continente vía OpenAlex + páginas de departamento, si te interesa; y una barrida de `capacity_database` (CORDIS/GEPRIS) que solo tiene sentido si la ruta PhD/predoc entra en juego.

### ⛔ Lo que quedó sin actualizar

Estos dos archivos **no** recibieron nada de esta tanda, por dos motivos combinados: estaban abiertos en LibreOffice (había archivos de bloqueo `.~lock`) y el entorno de scripting que hace falta para editar `.xlsx` no arrancó en esta sesión.

- `masters_consolidado_GRE_2027.xlsx` — falta agregar a la hoja **Becas**: Banco de España (cat. C o una nueva "instituciones públicas"), EUI cupo español, Kiel ASP y la ruta predoc; corregir Chevening en la hoja **Timeline**; y sumar los pendientes nuevos a la hoja **Pendientes**.
- `tabla_becas_uk.xlsx` — falta reflejar que el Banco de España cubre UK (£18.500 + matrícula) y que es incompatible con Chevening y con el resto.

Todo lo demás (nodo maestro, dashboard, GANTT, INOVA, plan McCall, informes) sí quedó actualizado.

**Solución provisoria:** las filas ya están armadas, formateadas y listas para pegar en **`ACTUALIZACION_excels_7a_tanda.xml`** (abre nativo en Excel y LibreOffice, mismo formato que el GANTT). Cuatro hojas: LEEME · 1-Becas nuevas · 2-Timeline correcciones · 3-Pendientes nuevos · 4-UK. Lo único que hay que hacer a mano antes de pegar es **borrar la fila vieja de Chevening** en la hoja Timeline del Excel maestro.

---

*Verificado 2-ago-2026. Toda cifra o regla de elegibilidad de este documento sale de la fuente primaria enlazada al lado. Las dos marcas ⚠️ (homologación del título en el BdE, residencia en el EUI) son huecos abiertos a propósito: no encontré la respuesta en la fuente oficial y no la inventé.*
