# HU-D1-1: Cargar leyes desde Excel

| Campo | Valor |
|---|---|
| **ID** | HU-D1-1 |
| **Actividad** | D1. Ingreso de leyes de laboratorio (manual o Excel) |
| **Release** | R1 – MVP de trazabilidad de leyes |
| **WSJF de la actividad** | 8.67 |
| **Dependencias** | HU-C2 |
| **Estado** | Por refinar |

## Historia

**Como** analista de laboratorio, **quiero** cargar un archivo Excel con los resultados de las muestras, **para** registrar las leyes de forma masiva sin digitar una por una.

## Criterios de aceptación

- **CA1:** El sistema valida que cada código de muestra exista.
- **CA2:** Rechaza valores no numéricos o fuera de rango y muestra un reporte de errores.
- **CA3:** Las muestras cargadas cambian a estado "Con resultado".
