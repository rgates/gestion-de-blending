# HU-A1: Crear polígono/pila desde la labor de origen

| Campo | Valor |
|---|---|
| **ID** | HU-A1 |
| **Actividad** | A. Configuración de polígonos y pilas en el SIG |
| **Release** | R1 – MVP de trazabilidad de leyes |
| **WSJF de la actividad** | 5.75 |
| **Dependencias** | Ninguna (habilitador) |
| **Estado** | Por refinar |

## Historia

**Como** geólogo de control de leyes, **quiero** crear un polígono en el SIG asociado a la labor de origen, **para** identificar a qué pila corresponde cada carga.

## Criterios de aceptación

- **CA1:** El polígono registra código único, labor de origen, nivel/tajo, fecha de creación y responsable.
- **CA2:** Cada polígono genera automáticamente una pila con estado "Abierta".
- **CA3:** No se puede crear un polígono sin labor de origen.
