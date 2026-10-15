# HU-A2: Gestionar el estado de la pila

| Campo | Valor |
|---|---|
| **ID** | HU-A2 |
| **Actividad** | A. Configuración de polígonos y pilas en el SIG |
| **Release** | R1 – MVP de trazabilidad de leyes |
| **WSJF de la actividad** | 5.75 |
| **Dependencias** | HU-A1 |
| **Estado** | Por refinar |

## Historia

**Como** jefe de geología, **quiero** cambiar el estado de la pila (Abierta, Cerrada, En consumo, Agotada), **para** controlar qué pilas aceptan volquetes y cuáles están disponibles para blending.

## Criterios de aceptación

- **CA1:** Una pila "Cerrada" no acepta nuevos volquetes.
- **CA2:** Solo las pilas "Cerradas" o "En consumo" aparecen disponibles para blending.
- **CA3:** Cada cambio de estado queda registrado con usuario y fecha.
