
# Iteración 2 - Sistema MSGF (Módulo de Becas-Crédito)

## Resumen del Nuevo Requerimiento
En esta iteración se añade la gestión de Becas-Crédito. La fundación recibirá un aporte anual para otorgar estas becas a estudiantes universitarios. Las becas se otorgan semestralmente y el estudiante debe presentar sus notas al finalizar el periodo. Dependiendo de su rendimiento académico, el sistema evaluará si el estudiante debe devolver el costo de la matrícula del semestre o si, por el contrario, dicho valor le será condonado.

## Diagramas Incluidos en esta Iteración
En esta carpeta se encuentran los archivos `.drawio` actualizados, integrando el nuevo módulo de becas a los diagramas de la iteración anterior:
1.  **Diagrama de Clases Actualizado:** Se añaden las entidades `Estudiante`, `BecaCredito`, `Nota` y `Matricula`.
2.  **Diagrama de Casos de Uso Actualizado:** Se incluye al actor `Estudiante` y los casos de uso para solicitar beca, presentar notas y evaluar/condonar.
3.  **Diagrama de Máquinas de Estado Actualizado:** Se agregan los estados de `Evaluando Notas` y `Procesando Matrícula` dentro del loop del sistema.
4.  **Diagrama de Límite y Control Actualizado:** Se incorporan las nuevas interfaces y entidades del módulo de becas, manteniendo la regla "Límite conoce Control, Control conoce Entidad".
