# Tablero Scrum/Kanban del Sprint 1

[Volver a Semana 7](../../README.md#semana-7--calidad-recursos-humanos-y-comunicación) · [Sprint Backlog 1](../../README.md#sprint-1-base-técnica-acceso-y-datos-iniciales)

**Herramienta:** Markdown versionado en el repositorio GitHub. **Carga inicial:** 1 de noviembre de 2026. **Periodo representado:** S1, del 10 al 23 de septiembre de 2026; son fechas del caso, no evidencia de programación ejecutada.

Este tablero representa la ejecución técnica simulada. Las cinco unidades están planificadas y comienzan Por hacer. Brian y Jeremy son responsables del expediente. LT identifica al líder técnico y D1–D5, a los desarrolladores hipotéticos; D4 también atiende DevOps, dentro de su misma disponibilidad. Sus dedicaciones figuran en [Equipo profesional](../../README.md#puestos-experiencia-y-dedicación). Cada estado nuevo debe indicar si su evidencia es documental o simulada.

WIP significa trabajo en curso; DoD, Definición de Terminado.

## Vista del tablero

| Por hacer | En progreso — WIP 5 | En revisión — WIP 2 | Hecho — cumple DoD |
| --- | --- | --- | --- |
| [H01 — Landing Page](#h01-landing-page) · Jeremy Rodríguez Esquivel | — | — | — |
| [H02 — Inicio de sesión](#h02-inicio-de-sesión) · Jeremy Rodríguez Esquivel | — | — | — |
| [H03 — Registro de cliente](#h03-registro-de-cliente) · Jeremy Rodríguez Esquivel | — | — | — |
| [H09.1 — Clientes](#h091-clientes) · Brian Rodríguez Pérez | — | — | — |
| [H11 — Catálogos](#h11-catálogos) · Brian Rodríguez Pérez | — | — | — |

**Conteo inicial:** 5 Por hacer; 0 En progreso; 0 En revisión; 0 Hecho. **Puntos:** 25 planificados y 0 terminados. Preparar el expediente no equivale a programar estas funciones.

## Reglas de movimiento y bloqueos

1. **Por hacer → En progreso:** identificar responsable, tareas y dependencias del escenario; comprobar su disponibilidad y el WIP.
2. **En progreso → En revisión:** adjuntar la referencia a los criterios, casos y evidencia prevista o representada, y asignar revisor.
3. **En revisión → Hecho:** revisar criterios y los seis puntos de [DoD](../../README.md#criterios-de-terminación-y-aceptación). Registrar fecha, revisor y evidencia; los resultados supuestos se identifican como simulados y no se atribuyen a ejecución real.
4. Si hay observaciones, devolver a En progreso con el motivo. Una tarjeta bloqueada permanece en su columna y cuenta para su WIP; registrar causa, impacto, responsable y siguiente consulta.
5. Editar la fila de la tarjeta para cambiarla de columna y actualizar los conteos y su ficha. Guardar el cambio mediante commit; conservar la historia del archivo. No duplicar una tarjeta en dos columnas.

El WIP 5 permite coordinar las cinco entregas del S1 con los seis desarrolladores previstos; cada profesional conserva su único bloque activo. El WIP 2 evita acumular revisiones sin responsable. Si se propone cambiar estos límites, registrar el motivo y comprobar su coherencia con capacidad y calidad antes de aplicarlo.

## Tarjetas cargadas

### H01: Landing Page

**Estado:** Por hacer. **Puntos:** 5.

**Responsable documental:** Jeremy Rodríguez Esquivel. **Revisor documental:** Brian Rodríguez Pérez.

Presentar RYC y preparar el contacto por WhatsApp sin cuenta. El formulario público prepara el mensaje; no registra una solicitud.

**Tareas propias:** T001, T002. **Profesionales previstos:** D4, D5. **Esfuerzo propio:** 20 h base / 30 h desfavorables.

**Criterios y reglas:** [Conocer RYC y contactar desde la Landing Page](../../README.md#historia-h01-conocer-ryc-y-contactar-desde-la-landing-page). Aplicar también la DoD y los componentes comunes de su ficha.

**Bloqueos:** ninguno registrado en la carga inicial; comprobar las dependencias antes de iniciar. **Evidencia de ejecución:** no registrada.

### H02: Inicio de sesión

**Estado:** Por hacer. **Puntos:** 5.

**Responsable documental:** Jeremy Rodríguez Esquivel. **Revisor documental:** Brian Rodríguez Pérez.

Ingresar con correo y contraseña, aplicar límites de intentos y gestionar la sesión y el acceso según el rol.

**Tareas propias:** T003, T004. **Profesionales previstos:** D2, D3. **Esfuerzo propio:** 14 h base / 22 h desfavorables.

**Criterios y reglas:** [Iniciar sesión en la aplicación web](../../README.md#historia-h02-iniciar-sesión-en-la-aplicación-web). Aplicar también la DoD y los componentes comunes de su ficha.

**Bloqueos:** ninguno registrado en la carga inicial; comprobar las dependencias antes de iniciar. **Evidencia de ejecución:** no registrada.

### H03: Registro de cliente

**Estado:** Por hacer. **Puntos:** 5.

**Responsable documental:** Jeremy Rodríguez Esquivel. **Revisor documental:** Brian Rodríguez Pérez.

Registrar una cuenta de cliente con correo único, UUID y contraseña protegida con Argon2id. No autoriza historial previo.

**Tareas propias:** T005, T006. **Profesionales previstos:** D2, D3. **Esfuerzo propio:** 16 h base / 24 h desfavorables.

**Criterios y reglas:** [Crear una cuenta de cliente](../../README.md#historia-h03-crear-una-cuenta-de-cliente). Aplicar también la DoD y los componentes comunes de su ficha.

**Bloqueos:** ninguno registrado en la carga inicial; comprobar las dependencias antes de iniciar. **Evidencia de ejecución:** no registrada.

### H09.1: Clientes

**Estado:** Por hacer. **Puntos:** 5.

**Responsable documental:** Brian Rodríguez Pérez. **Revisor documental:** Jeremy Rodríguez Esquivel.

Registrar, editar, listar y desactivar clientes conservando sus datos e historial, sin exigir cuenta en el portal.

**Tareas propias:** T043, T044, T045, T046. **Profesionales previstos:** D1, D2, LT. **Esfuerzo propio:** 36 h base / 54 h desfavorables.

**Criterios y reglas:** [Registrar y mantener clientes particulares y empresas](../../README.md#h091--registrar-y-mantener-clientes-particulares-y-empresas). Aplicar también la DoD y los componentes comunes de su ficha.

**Bloqueos:** ninguno registrado en la carga inicial; comprobar las dependencias antes de iniciar. **Evidencia de ejecución:** no registrada.

### H11: Catálogos

**Estado:** Por hacer. **Puntos:** 5.

**Responsable documental:** Brian Rodríguez Pérez. **Revisor documental:** Jeremy Rodríguez Esquivel.

Mantener plagas y productos con estado activo o inactivo, conservando referencias históricas y sin prescribir dosis.

**Tareas propias:** T064, T065, T066, T067. **Profesionales previstos:** D1, D2, D4, LT. **Esfuerzo propio:** 24 h base / 40 h desfavorables.

**Criterios y reglas:** [Administrar los catálogos de plagas y productos](../../README.md#historia-h11-administrar-los-catálogos-de-plagas-y-productos). Aplicar también la DoD y los componentes comunes de su ficha.

**Bloqueos:** ninguno registrado en la carga inicial; comprobar las dependencias antes de iniciar. **Evidencia de ejecución:** no registrada.

## Componentes comunes y seguimiento

S1 incluye ocho tareas comunes: **T078 — Preparar el proyecto; T079 — Relaciones de datos; T080 — Estilos; T081 — Cuenta administrativa; T082 — Diseño de acceso; T083 — Contacto por WhatsApp; T088 — Selectores territoriales; T092 — Menús**. Se consultan en el Sprint Backlog y la tabla de asignación; no crean otras historias ni puntos adicionales. Las cinco tarjetas reúnen 14 tareas propias y estas 8 comunes: **22 tareas** en total.

Los responsables documentales actualizan el tablero al representar un cambio o resolver una revisión. Cada entrada conserva fecha, tarjeta, columna anterior/nueva, responsable, motivo y referencia a la evidencia. Las decisiones de negocio se consultan con César y las académicas con Yesenia, según el Plan de Comunicaciones.

## Historial del tablero

| Fecha | Cambio | Estado de la evidencia |
| --- | --- | --- |
| 2026-11-01 | Carga inicial de H01, H02, H03, H09.1 y H11, con responsables y reglas. | Planificación documentada; sin programación declarada como realizada. |
