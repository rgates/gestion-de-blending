# HU-F1: Registrar el programa de blending del día

| Campo | Valor |
|---|---|
| **ID** | HU-F1 |
| **Actividad** | F. Registro de blending (carga de pila a tolvas) |
| **Release** | R2 – Blending operativo |
| **WSJF de la actividad** | 3.25 |
| **Dependencias** | HU-A2, HU-E1 |
| **Estado** | Por refinar |

## Historia

**Como** planificador de planta, **quiero** registrar cuánto tonelaje enviar de cada pila a cada tolva, **para** ejecutar la mezcla programada.

## Criterios de aceptación

- **CA1:** Solo se pueden elegir pilas disponibles (Cerrada o En consumo).
- **CA2:** No permite programar más tonelaje del saldo disponible en la pila.
- **CA3:** Muestra la ley estimada de la mezcla mientras se arma el programa.
