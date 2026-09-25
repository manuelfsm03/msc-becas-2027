# Contexto del proyecto

**Qué es:** búsqueda de un MSc en Economía financiado para arrancar en septiembre de 2027. Manuel es argentino con ciudadanía española; la doble nacionalidad es la palanca central de todo el proyecto.
**Estado:** mapa de becas maduro tras ocho tandas de barrida. Chevening cayó por elegibilidad el 2-ago-2026 y el **Banco de España** pasó a ser la beca principal. McCall MacBain/McGill se desistió el 16-ago-2026 (no salió el endorsement UBA a tiempo). El 9-sep-2026 se barrió Suiza a fondo y se leyeron completas las bases oficiales del BdE: su incompatibilidad alcanza también a las becas propias de universidad. Foco actual: **Banco de España + Inova/UK + HSG St. Gallen** (HSG sumado el 13-sep-2026).
**Última actualización:** 2026-09-13

## Para arrancar

Leer este archivo + `NODO_MAESTRO_MSC_2027.md`. Con eso alcanza para la mayoría de las consultas. Los demás archivos se abren solo si el tema lo pide.

## Mapa de archivos

| Archivo | Cubre | Últ. toque |
|---|---|---|
| `NODO_MAESTRO_MSC_2027.md` | **Hub del proyecto.** Perfil, decisiones estratégicas vigentes, filtros transversales de elegibilidad, mapa de becas por categoría, shortlist UK, timeline y pendientes. Supersede a los dos archivos marcados abajo. | 2026-09-13 |
| `SEGUIMIENTO_DIARIO.md` | **Lista viva de tareas y próximos cierres.** La reescribe un recordatorio automático a las 8:30 y a las 19:00: dos rutinas en la nube de Claude que trabajan sobre el repo privado `github.com/manuelfsm03/msc-becas-2027`, siguen `RECORDATORIO_INSTRUCCIONES.md` y avisan con un evento de Google Calendar. La carpeta local se sincroniza con el repo cada 30 minutos (tarea "MSc Sync GitHub" de Windows). Para registrar avances, una línea en su sección Novedades. | 2026-09-14 |
| `RECORDATORIO_INSTRUCCIONES.md` | Instrucciones que sigue el recordatorio en la nube: qué lee, cómo reordena la lista, cómo commitea y cómo arma el evento de Calendar. Editarlo cambia el comportamiento desde la corrida siguiente. | 2026-09-14 |
| `MAILS_pendientes_sep2026.md` | **Borradores de los mails y mensajes pendientes**, en orden de urgencia: Fabiola/Inova, DAAD Buenos Aires, HSG, traductor público, HEC Lausanne y la confirmación a los tres referentes. Los `[corchetes]` son huecos a llenar. | 2026-09-15 |
| `EXPAND_hallazgos_ago2026.md` | 7ª tanda: barrida por hueco de cobertura. Banco de España, EUI Florencia, Kiel ASP, ruta predoc, catálogo Erasmus Mundus sin barrer. Diff de clases de fuente. | 2026-08-02 |
| `HUNGRIA_stipendium_dossier.md` | Dossier Hungría / Stipendium Hungaricum y el hallazgo de CEU Viena. Producido por otra sesión del 2-ago-2026. | 2026-08-02 |
| `SUIZA_dossier.md` | **Dossier Suiza (8ª tanda).** Los 9 programas que sobreviven al filtro del catálogo oficial, matrículas y costo de vida por ciudad, el mapa de becas suizo (HSG Best Talents es el hallazgo) y el fit contra la espina. Contiene además la **lectura completa de las bases oficiales del Banco de España**, que resuelve la pregunta de incompatibilidad y acota el pendiente de homologación. | 2026-09-10 |
| `RECAP_becas_y_pairing.md` | **Vista de becas vivas y qué destino financia cada una.** Rutas excluyentes A (BdE sola) y B (el stack), foco inmediato, segundo anillo, pairing por país (incluye Suiza) y las decisiones abiertas. | 2026-09-13 |
| `MATCH_grupos_profes_por_uni.md` | **Centros y profesores por universidad para el bloque 5 de cada SOP**, filtrados contra la espina (identificación causal aplicada a macro y política pública). Bloques UK, continental y Suiza/HSG (10-sep), lecturas transversales y reglas de verificación antes de enviar. | 2026-09-13 |
| `SOP_MAESTRO_desarrollo_policy.md` | **SOP maestro, track desarrollo/política.** Espina, borrador en inglés de los bloques 1-4 y 6, riesgos y referencias verificadas. El bloque 5 es modular por universidad y sale de `MATCH_grupos_profes_por_uni.md`. | 2026-09-08 |
| Artefacto web **Dossier Suiza 2027** | Vista navegable de `SUIZA_dossier.md` (programas, costos, financiación, fit): https://claude.ai/code/artifact/f3b188d7-28ad-48f7-a49d-c64ff2cd6389 ⚠️ Su ficha de HSG no tiene el matcheo de profesores del 10-sep. | 2026-09-09 |
| `HSG_MECON_plan_aplicacion.md` | **Foco activo desde el 25-sep-2026.** Requisitos oficiales de admisión a HSG MEcon (ponderación del comité, checklist de documentos, reglas de traducción y apostilla), cronograma hacia la 1ª ronda (cierra el 30-nov, decisión antes del 31-dic) y el enganche con Best Talents. | 2026-09-25 |
| `DAAD_STUDY_SCHOLARSHIP_dossier.md` | ⛔ **Conclusión central equivocada (corregida el 25-sep-2026): Argentina no es elegible.** Dossier DAAD Study Scholarship: confirma que el pasaporte español NO excluye (a diferencia de la Caixa/GREAT/Ireland/Hungría) + mapa de MSc Economics en Alemania más allá de Bonn/Mannheim/Goethe MMF (HU Berlin, Heidelberg, Kiel, Cologne, Konstanz/Tübingen). | 2026-08-25 |
| `BECAS_veredictos_lista_24.md` · `BECAS_nordicos_y_reevaluaciones.md` · `BECAS_top4_UK_barrida.md` | Informes de barridas anteriores (tandas 3ª a 6ª). Snapshots fechados: se consultan, no se reescriben. | 2026-08-02 |
| `MCCALL_MCGILL_plan_ataque.md` | ❌ **Desistido el 16-ago-2026** (no salió el endorsement UBA). Registro histórico de la aplicación a McCall MacBain + McGill MA: checklist, cronograma, supervisores, template de mail. No usar para planificar. | 2026-08-02 |
| `INOVA_todo_documentos.md` | Proceso con la consultora Inova para las 5 aplicaciones UK: documentos, formulario, cronograma. | 2026-08-02 |
| `INFORME_SOP_top4_UK.md` | Statements of purpose para las universidades UK del tier 1. | 2026-07 |
| `masters_consolidado_GRE_2027.xlsx` | **Fuente de datos viva.** 9 hojas: Ranking, Todos los programas (109), Becas, Filtro GRE-GMAT, Timeline, Pendientes. ⚠️ No tiene la 7ª tanda. | 2026-07-24 |
| `ACTUALIZACION_excels_7a_tanda.xml` | Filas listas para pegar en los dos `.xlsx` (no se pudieron editar por script). Ver "Pendiente manual" abajo. | 2026-08-02 |
| `masters_dashboard.html` | Vista navegable del Excel: programas, ranking, becas, timeline, pendientes. | 2026-08-02 |
| `GANTT_becas_MSc_2027.xml` / `.xlsx` | Calendario operativo semanal ago-2026 → sep-2027 con las ~45 becas y sus requisitos. | 2026-08-02 |
| `tabla_becas_uk.xlsx` · `masters_europa_continental.xlsx` | Tablas de apoyo. ⚠️ La de UK no tiene la 7ª tanda. | 2026-07 |
| `recon.json` | Estado del skill `recon` (etapas, inventario, sistemas). Lo escribe el skill, no editar a mano. | 2026-08-02 |
| `_BITACORA.md` | Histórico cronológico de sesiones. | 2026-09-13 |

### ⛔ Supersedidos — no usar para planificar

| Archivo | Por qué |
|---|---|
| `CONTEXTO_MSC_traspaso.md` | Reemplazado por `NODO_MAESTRO_MSC_2027.md`. Sus fechas de Chevening eran erróneas y sus pendientes ya se resolvieron. |
| `briefing_manu_masters_v2.md` | Ídem. Se conservan como registro histórico. |

## Pendiente manual abierto

Los dos `.xlsx` (`masters_consolidado_GRE_2027.xlsx` y `tabla_becas_uk.xlsx`) no recibieron la 7ª tanda: el entorno de scripting que hace falta para editar Excel no arrancó el 2-ago-2026. Las filas están armadas y formateadas en `ACTUALIZACION_excels_7a_tanda.xml`, listas para copiar y pegar. Antes de pegar hay que borrar a mano la fila vieja de Chevening en la hoja Timeline.

## Convenciones

- Fechas en el cuerpo de los documentos: formato `2-ago-2026`. En esta tabla y en la bitácora: ISO (`AAAA-MM-DD`).
- Toda regla de elegibilidad, deadline o monto lleva enlace a la **fuente primaria** y fecha de verificación. Los agregadores y las listas de becas sirven para descubrir, nunca para citar.
- Los huecos se dejan marcados con ⚠️ en vez de rellenarse con una suposición plausible.
- Estados de una beca: ✅ aplica · ⚠️ verificar · ❌ no aplica · 🔍 sin evaluar.
