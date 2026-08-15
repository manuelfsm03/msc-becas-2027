# Contexto del proyecto

**Qué es:** búsqueda de un MSc en Economía financiado para arrancar en septiembre de 2027. Manuel es argentino con ciudadanía española; la doble nacionalidad es la palanca central de todo el proyecto.
**Estado:** mapa de becas maduro tras siete tandas de barrida. Chevening cayó por elegibilidad el 2-ago-2026 y el **Banco de España** pasó a ser la beca principal. Lo más urgente en el calendario es McCall MacBain (19-ago-2026).
**Última actualización:** 2026-08-02

## Para arrancar

Leer este archivo + `NODO_MAESTRO_MSC_2027.md`. Con eso alcanza para la mayoría de las consultas. Los demás archivos se abren solo si el tema lo pide.

## Mapa de archivos

| Archivo | Cubre | Últ. toque |
|---|---|---|
| `NODO_MAESTRO_MSC_2027.md` | **Hub del proyecto.** Perfil, decisiones estratégicas vigentes, filtros transversales de elegibilidad, mapa de becas por categoría, shortlist UK, timeline y pendientes. Supersede a los dos archivos marcados abajo. | 2026-08-02 |
| `EXPAND_hallazgos_ago2026.md` | 7ª tanda: barrida por hueco de cobertura. Banco de España, EUI Florencia, Kiel ASP, ruta predoc, catálogo Erasmus Mundus sin barrer. Diff de clases de fuente. | 2026-08-02 |
| `HUNGRIA_stipendium_dossier.md` | Dossier Hungría / Stipendium Hungaricum y el hallazgo de CEU Viena. Producido por otra sesión del 2-ago-2026. | 2026-08-02 |
| `BECAS_veredictos_lista_24.md` · `BECAS_nordicos_y_reevaluaciones.md` · `BECAS_top4_UK_barrida.md` | Informes de barridas anteriores (tandas 3ª a 6ª). Snapshots fechados: se consultan, no se reescriben. | 2026-08-02 |
| `MCCALL_MCGILL_plan_ataque.md` | Aplicación a McCall MacBain + McGill MA: checklist, cronograma, supervisores, template de mail. **Lo más urgente del calendario.** | 2026-08-02 |
| `INOVA_todo_documentos.md` | Proceso con la consultora Inova para las 5 aplicaciones UK: documentos, formulario, cronograma. | 2026-08-02 |
| `INFORME_SOP_top4_UK.md` | Statements of purpose para las universidades UK del tier 1. | 2026-07 |
| `masters_consolidado_GRE_2027.xlsx` | **Fuente de datos viva.** 9 hojas: Ranking, Todos los programas (109), Becas, Filtro GRE-GMAT, Timeline, Pendientes. ⚠️ No tiene la 7ª tanda. | 2026-07-24 |
| `ACTUALIZACION_excels_7a_tanda.xml` | Filas listas para pegar en los dos `.xlsx` (no se pudieron editar por script). Ver "Pendiente manual" abajo. | 2026-08-02 |
| `masters_dashboard.html` | Vista navegable del Excel: programas, ranking, becas, timeline, pendientes. | 2026-08-02 |
| `GANTT_becas_MSc_2027.xml` / `.xlsx` | Calendario operativo semanal ago-2026 → sep-2027 con las ~45 becas y sus requisitos. | 2026-08-02 |
| `tabla_becas_uk.xlsx` · `masters_europa_continental.xlsx` | Tablas de apoyo. ⚠️ La de UK no tiene la 7ª tanda. | 2026-07 |
| `recon.json` | Estado del skill `recon` (etapas, inventario, sistemas). Lo escribe el skill, no editar a mano. | 2026-08-02 |
| `_BITACORA.md` | Histórico cronológico de sesiones. | 2026-08-02 |

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
