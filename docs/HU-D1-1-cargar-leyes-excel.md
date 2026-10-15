# HU-D1-1: Cargar leyes desde Excel

| Campo | Valor |
|---|---|
| **ID** | HU-D1-1 |
| **Actividad** | D1. Ingreso de leyes de laboratorio (manual o Excel) |
| **Release** | R1 – MVP de trazabilidad de leyes |
| **WSJF de la actividad** | 8.67 |
| **Dependencias** | HU-C2 |
| **Estado** | Refinada |
| **Story points** | 5 |

## Historia

**Como** analista de laboratorio, **quiero** cargar un archivo Excel con los resultados de las muestras, **para** registrar las leyes de forma masiva sin digitar una por una.

## Criterios de aceptación

- **CA1:** El sistema valida que cada código de muestra exista.
- **CA2:** Rechaza valores no numéricos o fuera de rango y muestra un reporte de errores.
- **CA3:** Las muestras cargadas cambian a estado "Con resultado".
- **CA4:** El archivo debe usar la plantilla estándar (columnas: código de muestra, elemento, ley, unidad, fecha de ensayo); el sistema permite descargar la plantilla.
- **CA5:** Si un código de muestra ya tiene resultado, el sistema lo marca como duplicado y no lo sobrescribe sin confirmación.

## Notas de refinamiento

- 2026-10-15: Se agregan CA4 y CA5 tras la revisión con Laboratorio. Se estima en 5 story points.
