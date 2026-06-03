## LCG RH Report — Dashboard de Talent Acquisition

**Dashboard en vivo:** [https://lcgjorgea.github.io/lcg-rh-report/](https://lcgjorgea.github.io/lcg-rh-report/)
**Configuración:** [https://lcgjorgea.github.io/lcg-rh-report/config.html](https://lcgjorgea.github.io/lcg-rh-report/config.html) 

---

### ¿Qué hace?

Herramienta de análisis del pipeline de reclutamiento de LCG México, conectada a Monday.com. Los datos se actualizan automáticamente cada 6 horas vía GitHub Actions, o manualmente desde la página de Configuración.

---

### Pestañas

| Pestaña | Contenido |
|---|---|
| **📊 Pipeline Activo** | KPIs del pipeline actual, funnel por etapa y nivel, ingresos por semana (colapsable), lista de candidatos activos ordenados por actividad reciente |
| **🔄 Movimientos** | Análisis de un período seleccionado: waterfall de headcount (Inicio + Nuevos − Descartados − Inactivos − Oferta Rechazada − Contratados = Final), movimientos entre etapas agrupados por tipo, Sankey de composición por nivel, log de actividad completo |
| **⛔ Descartados** | Análisis de rechazos: por etapa, razón, decisor, nivel, heatmap etapa × razón, histogramas de score Pyxoom y días en pipeline |
| **📅 Timeline** | Evolución semanal de ingresos vs descartes, candidatos acumulados por etapa, distribución de nivel en pipeline activo, gráfica de movimientos semanales (ingresos / actividad / bajas) |
| **🗂 Detalle** | Tabla filtrable de todos los candidatos (estatus, nivel, etapa, fuente, scores, razón), ordenada por actividad más reciente |

---

### Configuración

Desde [config.html](https://lcgjorgea.github.io/lcg-rh-report/config.html) puedes:
- Disparar una actualización manual de datos
- Definir qué estatus de Monday cuentan como Bajas, Descartados, Oferta Rechazada o Contratados
- Ajustar umbrales de alerta de inactividad (días sin actividad, amarillo, rojo)
