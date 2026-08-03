DOOZE-AS-001

Especificación Funcional -- Control de Asistencia

Código: DOOZE-AS-001Versión: 1.0Estado: Aprobado

1. Objetivo

Gestionar y controlar la asistencia diaria del personal de DOOZE HairClub, garantizando trazabilidad, flexibilidad y auditoría.

2. Alcance

Incluye:

Jornadas diarias.

Marcaciones.

Refrigerios.

Excepciones diarias.

Correcciones.

Horas extras.

Minutos adeudados.

Incidencias.

No incluye:

Gestión de Personal.

Vacaciones.

Licencias.

Suspensiones.

3. Actores

Administrador.

Colaborador.

4. Conceptos

Jornada diaria.

Marcación.

Refrigerio.

Excepción diaria.

Incidencia.

Hora extra.

Minutos adeudados.

Corrección.

5. Requerimientos Funcionales (RF)

RF-AS-001 al RF-AS-020

Generar automáticamente la jornada diaria.

Registrar ingreso.

Registrar inicio de refrigerio.

Registrar fin de refrigerio.

Registrar salida.

Permitir marcaciones desde dispositivos autorizados.

Permitir correcciones por el administrador.

Recalcular automáticamente la jornada después de una corrección.

Registrar excepciones diarias.

Calcular horas extras y minutos adeudados.

Permitir registrar salida con incidencias.

Aprobar o rechazar horas extras.

Consultar detalle diario de asistencia.

Mostrar el estado actual de la jornada antes de marcar.

Registrar observaciones de la jornada.

Recalcular la jornada tras aprobar una excepción.

Consultar historial de correcciones.

Mostrar resumen mensual de asistencia.

Detectar automáticamente incidencias.

Cerrar la jornada conservando toda la trazabilidad.

6. Reglas de Negocio (RN)

RN-AS-001

La jornada diaria se genera a partir de la plantilla vigente y delcalendario laboral.

RN-AS-002

Las excepciones solo afectan la fecha para la cual fueron registradas.

RN-AS-003

El cálculo de asistencia respeta el siguiente orden: Calendario →Plantilla → Excepción → Marcaciones → Correcciones.

RN-AS-004

Las marcaciones solo pueden realizarse desde dispositivos autorizados.

RN-AS-005

La asistencia utiliza PIN; el usuario y contraseña pertenecen únicamenteal ERP.

RN-AS-006

Solo un administrador puede corregir marcaciones.

RN-AS-007

Toda corrección obliga al recálculo automático.

RN-AS-008

Las horas extras requieren aprobación administrativa.

RN-AS-009

Las incidencias no bloquean la continuidad de la jornada.

RN-AS-010

La ausencia de marcaciones de refrigerio no impide registrar la salida.

RN-AS-011

El administrador puede completar manualmente una salida olvidada.

RN-AS-012

Las excepciones son creadas y aprobadas por un administrador.

RN-AS-013

Las excepciones pueden registrarse posteriormente y recalcular lajornada.

RN-AS-014

Toda excepción requiere un motivo.

RN-AS-015

Cada jornada posee un único estado vigente.

RN-AS-016

Toda marcación correcta muestra una confirmación al colaborador.

RN-AS-017

El sistema advierte antes de generar una incidencia, pero no bloquea unaacción válida.

RN-AS-018

El flujo de marcaciones es flexible y contempla excepciones.

RN-AS-019

Las incidencias son resueltas por el administrador.

RN-AS-020

Las marcaciones, correcciones e incidencias nunca se eliminan.

7. Reglas de Auditoría (RA)

Registrar cada marcación indicando fecha, hora, colaborador ydispositivo.

Registrar toda corrección con valor anterior, nuevo valor, motivo yresponsable.

Registrar aprobación o rechazo de horas extras.

Registrar creación o modificación de excepciones.

Registrar todo recálculo de asistencia.

Registrar modificaciones manuales de jornadas.

Registrar resolución de incidencias.

Las auditorías son inmutables.

8. Casos Especiales (CE)

Olvido de ingreso.

Olvido de salida.

Olvido de refrigerio.

Salida sin refrigerio.

Corrección mediante cámaras.

Cambio excepcional de jornada.

Permanencia sin autorización de horas extras.

Marcación tardía.

Hora registrada incorrectamente.

Colaborador que no tomó refrigerio.

9. UX

Informar antes que bloquear.

Confirmar toda marcación exitosa.

Mostrar advertencias claras.

Guiar al colaborador con una interfaz simple.

Permitir continuar cuando exista una incidencia válida.

10. Dashboard

Mostrar:

Incidencias pendientes.

Horas extras por aprobar.

Jornadas con correcciones.

Tardanzas.

Horas adeudadas.

Excepciones pendientes.

11. Configuración

Administrar:

Dispositivos autorizados.

Motivos de excepción.

Estados de jornada.

Reglas de cálculo.

Parámetros de horas extras.

12. Principios del módulo

Informar antes que bloquear.

El administrador tiene la decisión final.

Toda corrección conserva trazabilidad.

Las incidencias no eliminan información.

El sistema debe reducir errores de marcación.

13. Historial

Versión: 1.0Estado: Aprobado funcionalmente.
