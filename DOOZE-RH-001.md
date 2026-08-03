Especificación Funcional -- Gestión de Personal

Código: DOOZE-RH-001Versión: 1.0Estado: Aprobado

1. Objetivo

Administrar el ciclo de vida completo del colaborador dentro de DOOZEHair Club, manteniendo historial, trazabilidad y flexibilidad.

2. Alcance

Incluye:

Personas

Colaboradores

Períodos laborales

Cargos

Jornadas

Plantillas

Salarios

Vacaciones

Licencias

Suspensiones

Seguimiento

Documentos laborales

Usuarios

Permisos

No incluye:

Control de Asistencia

Agenda

Inventario

Caja

3. Actores

Administrador

Colaborador

4. Conceptos

Persona

Colaborador

Período laboral

Cargo

Jornada

Plantilla

Salario

Área

Usuario

5. Requerimientos Funcionales (RF)

RF-RH-001 al RF-RH-030

Registrar personas.

Convertir una persona en colaborador.

Permitir múltiples roles (cliente, colaborador, proveedor).

Registrar múltiples medios de pago.

Crear períodos laborales.

Finalizar períodos laborales.

Reingresar colaboradores mediante un nuevo período laboral.

Asignar y cambiar cargos conservando historial.

Asignar y cambiar jornadas conservando historial.

Asignar y cambiar plantillas laborales.

Asignar y cambiar salarios con vigencia.

Registrar vacaciones.

Registrar licencias.

Registrar suspensiones.

Registrar seguimientos.

Gestionar documentos laborales.

Crear y desactivar usuarios.

Asignar permisos y permisos excepcionales.

Administrar áreas.

Asignar múltiples áreas.

Administrar catálogo de cargos.

Clasificar cargos.

Programar cambios futuros.

Ejecutar asistentes para incorporación, cambios, cese y reingreso.

6. Reglas de Negocio (RN)

RN-RH-001

Una persona puede existir sin ser colaboradora.

RN-RH-002

Una persona puede desempeñar múltiples roles simultáneamente.

RN-RH-003

Solo puede existir un período laboral activo por colaborador.

RN-RH-004

El reingreso genera un nuevo período laboral.

RN-RH-005

Cambiar la jornada no crea un nuevo período laboral.

RN-RH-006

Todo cambio de cargo conserva historial.

RN-RH-007

El cambio de cargo no modifica automáticamente el salario.

RN-RH-008

El salario vigente permanece hasta una nueva asignación.

RN-RH-009

Solo existe una jornada vigente por colaborador.

RN-RH-010

Solo existe una plantilla vigente por colaborador.

RN-RH-011

Solo existe un cargo vigente por colaborador.

RN-RH-012

Los permisos se asignan inicialmente por cargo.

RN-RH-013

El administrador puede asignar permisos excepcionales.

RN-RH-014

Las excepciones frecuentes deben revisarse para ajustar roles.

RN-RH-015

Los cargos existen aunque no tengan colaboradores asignados.

RN-RH-016

El salario referencial del cargo no modifica el salario del colaborador.

RN-RH-017

Los cambios pueden programarse con vigencia futura.

RN-RH-018

Ningún cambio elimina el historial.

RN-RH-019

Un colaborador puede pertenecer a varias áreas.

RN-RH-020

Los seguimientos no modifican automáticamente la situación laboral.

RN-RH-021

Puede existir más de un medio de pago, con uno principal.

RN-RH-022

No todo colaborador requiere usuario del ERP.

RN-RH-023

El usuario se deshabilita al finalizar el período laboral.

RN-RH-024

El cese conserva el historial.

RN-RH-025

Los datos personales pueden modificarse directamente.

RN-RH-026

Los documentos laborales conservan trazabilidad.

RN-RH-027

El sistema informa vacaciones disponibles.

RN-RH-028

Licencias y suspensiones afectan la disponibilidad laboral.

RN-RH-029

Las decisiones críticas pertenecen al administrador.

RN-RH-030

Los procesos laborales se ejecutan mediante asistentes cuando aportenvalor.

7. Reglas de Auditoría (RA)

Registrar creación de colaboradores.

Registrar cambios de cargo.

Registrar cambios de jornada.

Registrar cambios salariales.

Registrar cambios de plantilla.

Registrar vacaciones.

Registrar licencias y suspensiones.

Registrar carga de documentos.

Registrar activación/desactivación de usuarios.

8. Casos Especiales (CE)

Colaborador y cliente simultáneamente.

Múltiples medios de pago.

Varias áreas asignadas.

Cambio de cargo sin cambio salarial.

Cambio salarial sin cambio de cargo.

Cambio PT ↔ FT.

Reingreso.

Practicante → Trabajadora.

Cambios futuros programados.

9. UX

Informar antes que bloquear.

Confirmar acciones exitosas.

Utilizar asistentes para procesos complejos.

Formularios simples.

10. Dashboard

Mostrar:

Cumpleaños.

Vacaciones pendientes.

Seguimientos pendientes.

Licencias.

Suspensiones.

Incorporaciones recientes.

Ceses recientes.

11. Configuración

Administrar:

Cargos.

Áreas.

Jornadas.

Plantillas.

Medios de pago.

Tipos de seguimiento.

Tipos de documentos.

Roles.

Permisos.

12. Principios del módulo

Historial antes que sobrescribir.

El administrador tiene la decisión final.

Uso de vigencias.

Configuración antes que programación.

Simplicidad sobre complejidad.

13. Historial

Versión: 1.0Estado: Aprobado funcionalmente.
