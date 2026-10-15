# HU-F2: Registrar la carga real ejecutada

| Campo | Valor |
|---|---|
| **ID** | HU-F2 |
| **Actividad** | F. Registro de blending (carga de pila a tolvas) |
| **Release** | R2 – Blending operativo |
| **WSJF de la actividad** | 3.25 |
| **Dependencias** | HU-F1 |
| **Estado** | Por refinar |

## Historia

**Como** operador de planta, **quiero** registrar el tonelaje real cargado de cada pila a cada tolva, **para** comparar lo programado contra lo ejecutado.

## Criterios de aceptación

- **CA1:** El tonelaje real se descuenta del saldo de la pila.
- **CA2:** Muestra la desviación entre programado y real.
- **CA3:** Cuando el saldo de una pila llega a cero, cambia a "Agotada".
