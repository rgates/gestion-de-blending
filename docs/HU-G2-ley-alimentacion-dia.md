# HU-G2: Calcular la ley de alimentación del día

| Campo | Valor |
|---|---|
| **ID** | HU-G2 |
| **Actividad** | G. Consolidación de la carga diaria y la ley de alimentación |
| **Release** | R2 – Blending operativo |
| **WSJF de la actividad** | 8.00 |
| **Dependencias** | HU-G1, HU-E1 |
| **Estado** | Por refinar |

## Historia

**Como** superintendente de operaciones, **quiero** ver la ley ponderada de la alimentación diaria, **para** conciliar con los resultados de planta.

## Criterios de aceptación

- **CA1:** Fórmula: Σ(ley de pila × tonelaje cargado) / Σ(tonelaje cargado).
- **CA2:** Permite comparar la ley del día con la ley objetivo.
- **CA3:** Genera un reporte diario exportable.
