# HU-E1: Calcular automáticamente la ley ponderada

| Campo | Valor |
|---|---|
| **ID** | HU-E1 |
| **Actividad** | E. Cálculo de la ley ponderada de la pila |
| **Release** | R1 – MVP de trazabilidad de leyes |
| **WSJF de la actividad** | 13.67 |
| **Dependencias** | HU-B1, HU-D1-1 |
| **Estado** | Por refinar |

## Historia

**Como** geólogo de control de leyes, **quiero** que el sistema calcule la ley de la pila ponderada por el tonelaje de cada volquete, **para** conocer la ley real de cada pila.

## Criterios de aceptación

- **CA1:** Fórmula: Σ(ley × tonelaje) / Σ(tonelaje).
- **CA2:** Solo considera muestras con resultado.
- **CA3:** Muestra el porcentaje de volquetes con ley sobre el total de la pila.
