# Sistema de Gestión para RYC Control de Plagas

**Universidad Técnica Nacional**\
Sede Regional San Carlos

| Información | Detalle                                       |
| ----------- | --------------------------------------------- |
| Curso       | Administración de Proyectos Informáticos      |
| Proyecto    | Sistema de Gestión para RYC Control de Plagas |
| Profesora   | Yesenia Calvo Araya                           |

**Integrantes**

- Brian Rodríguez Pérez
- Jeremy Rodríguez Esquivel

---

## Contenido

- [Sistema de Gestión para RYC Control de Plagas](#sistema-de-gestión-para-ryc-control-de-plagas)
  - [Contenido](#contenido)
  - [Semana 1 · Definición del proyecto](#semana-1--definición-del-proyecto)
    - [Problema](#problema)
    - [Proyecto propuesto](#proyecto-propuesto)
    - [Valor esperado](#valor-esperado)
    - [Objetivo general](#objetivo-general)
    - [Objetivos específicos](#objetivos-específicos)
  - [Semana 2 · Taller: interesados de nuestro proyecto](#semana-2--taller-interesados-de-nuestro-proyecto)
    - [Contexto y restricciones del proyecto](#contexto-y-restricciones-del-proyecto)
    - [Registro de interesados](#registro-de-interesados)
    - [Justificación de valoraciones relevantes](#justificación-de-valoraciones-relevantes)
    - [Mapa Poder–Interés](#mapa-poderinterés)
    - [Tres interesados críticos y su involucramiento](#tres-interesados-críticos-y-su-involucramiento)
    - [Preguntas de análisis de interesados](#preguntas-de-análisis-de-interesados)
      - [¿A quién debemos involucrar primero?](#a-quién-debemos-involucrar-primero)
      - [¿Quién puede bloquear una decisión?](#quién-puede-bloquear-una-decisión)
      - [¿Quién necesita información frecuente?](#quién-necesita-información-frecuente)
      - [¿Qué interesado estamos subestimando?](#qué-interesado-estamos-subestimando)
      - [¿Qué conflicto de expectativas puede aparecer?](#qué-conflicto-de-expectativas-puede-aparecer)
    - [Enfoque de gestión del proyecto](#enfoque-de-gestión-del-proyecto)
  - [Semana 3 Planeamiento del proyecto](#semana-3-planeamiento-del-proyecto)
    - [Alcance y organización de la información](#alcance-y-organización-de-la-información)
      - [Cuenta, cliente y asociación](#cuenta-cliente-y-asociación)
      - [Atención sin cuenta: recorrido principal](#atención-sin-cuenta-recorrido-principal)
      - [Atención con cuenta: recorrido opcional](#atención-con-cuenta-recorrido-opcional)
    - [Landing Page y contacto por WhatsApp](#landing-page-y-contacto-por-whatsapp)
      - [Contenido y recorrido](#contenido-y-recorrido)
      - [Formulario breve para preparar el mensaje](#formulario-breve-para-preparar-el-mensaje)
    - [Necesidades de los usuarios y resultados esperados](#necesidades-de-los-usuarios-y-resultados-esperados)
      - [Necesidades de las personas interesadas y los clientes](#necesidades-de-las-personas-interesadas-y-los-clientes)
      - [Necesidades de César](#necesidades-de-césar)
      - [Necesidades de RYC como empresa](#necesidades-de-ryc-como-empresa)
    - [Registro e inicio de sesión](#registro-e-inicio-de-sesión)
      - [Campos del registro](#campos-del-registro)
      - [Opciones del login](#opciones-del-login)
      - [Validación de formularios y seguridad de las cuentas](#validación-de-formularios-y-seguridad-de-las-cuentas)
        - [Mensajes al completar los formularios](#mensajes-al-completar-los-formularios)
        - [Páginas y funciones de acceso](#páginas-y-funciones-de-acceso)
        - [Medidas para proteger las cuentas](#medidas-para-proteger-las-cuentas)
    - [Diseño y comportamiento en dispositivos](#diseño-y-comportamiento-en-dispositivos)
      - [Dirección visual](#dirección-visual)
      - [Colores](#colores)
      - [Tipografía](#tipografía)
      - [Login](#login)
      - [Presentación de la administración y el portal](#presentación-de-la-administración-y-el-portal)
    - [Experiencia de uso de César](#experiencia-de-uso-de-césar)
      - [Registro por etapas y reutilización](#registro-por-etapas-y-reutilización)
      - [Guardado de formularios](#guardado-de-formularios)
      - [Acciones y estado](#acciones-y-estado)
    - [Empresas, sedes y cuentas](#empresas-sedes-y-cuentas)
      - [Permisos de consulta y solicitud](#permisos-de-consulta-y-solicitud)
      - [Ejemplo de acceso por sede](#ejemplo-de-acceso-por-sede)
      - [Justificación](#justificación)
    - [Asociación mediante ID](#asociación-mediante-id)
    - [Consultoría y aceptación del servicio](#consultoría-y-aceptación-del-servicio)
      - [Formulario de consultoría](#formulario-de-consultoría)
      - [Estados de la consultoría](#estados-de-la-consultoría)
      - [Cómo se registra la aceptación del trabajo](#cómo-se-registra-la-aceptación-del-trabajo)
      - [Orden y situación financiera](#orden-y-situación-financiera)
      - [Datos del reporte de pago](#datos-del-reporte-de-pago)
      - [Comunicación y seguimiento de los pagos](#comunicación-y-seguimiento-de-los-pagos)
      - [Archivos, permisos y alcance comercial](#archivos-permisos-y-alcance-comercial)
    - [Clientes, ubicaciones y servicios](#clientes-ubicaciones-y-servicios)
      - [Cliente particular](#cliente-particular)
      - [Empresa](#empresa)
      - [Servicio realizado](#servicio-realizado)
    - [Plagas, productos y tratamientos](#plagas-productos-y-tratamientos)
      - [Catálogo de plagas](#catálogo-de-plagas)
      - [Catálogo de productos](#catálogo-de-productos)
      - [Registro del tratamiento](#registro-del-tratamiento)
      - [Publicación del historial](#publicación-del-historial)
    - [Visitas y calendario](#visitas-y-calendario)
      - [Datos de una visita](#datos-de-una-visita)
      - [Reglas](#reglas)
      - [Presentación](#presentación)
    - [Información histórica](#información-histórica)
    - [Tecnología, alojamiento y entrega](#tecnología-alojamiento-y-entrega)
      - [Tecnologías](#tecnologías)
      - [Alojamiento de la demostración y del piloto](#alojamiento-de-la-demostración-y-del-piloto)
      - [Respaldo y entrega](#respaldo-y-entrega)
    - [Páginas del sistema y su contenido](#páginas-del-sistema-y-su-contenido)
      - [Convenciones de presentación](#convenciones-de-presentación)
      - [Mensajes de validación de campos](#mensajes-de-validación-de-campos)
      - [Navegación](#navegación)
      - [Cómo se organiza cada página](#cómo-se-organiza-cada-página)
      - [Landing Page y acceso a la aplicación web](#landing-page-y-acceso-a-la-aplicación-web)
        - [Landing Page de RYC](#landing-page-de-ryc)
          - [Formulario de contacto por WhatsApp](#formulario-de-contacto-por-whatsapp)
        - [Inicio de sesión](#inicio-de-sesión)
        - [Crear cuenta](#crear-cuenta)
        - [Recuperar acceso](#recuperar-acceso)
        - [Cambiar contraseña por recuperación](#cambiar-contraseña-por-recuperación)
      - [Portal del cliente](#portal-del-cliente)
        - [Panel del cliente](#panel-del-cliente)
          - [Verificación del correo en el portal](#verificación-del-correo-en-el-portal)
          - [Solicitudes y seguimiento del cliente](#solicitudes-y-seguimiento-del-cliente)
          - [Formulario de consultoría del portal](#formulario-de-consultoría-del-portal)
          - [Formulario de nueva visita](#formulario-de-nueva-visita)
          - [Propuesta del trabajo y decisión del cliente](#propuesta-del-trabajo-y-decisión-del-cliente)
          - [Próximas visitas y solicitud de cambios](#próximas-visitas-y-solicitud-de-cambios)
          - [Historial de servicios del cliente](#historial-de-servicios-del-cliente)
        - [Pagos y documentos](#pagos-y-documentos)
          - [Pagos y reportes del cliente](#pagos-y-reportes-del-cliente)
          - [Datos de facturación de la orden](#datos-de-facturación-de-la-orden)
          - [Documentos y descargas del cliente](#documentos-y-descargas-del-cliente)
      - [Administración de César](#administración-de-césar)
        - [Panel de administración de César](#panel-de-administración-de-césar)
          - [Registro rápido de un contacto](#registro-rápido-de-un-contacto)
          - [Consultorías y propuesta del trabajo](#consultorías-y-propuesta-del-trabajo)
          - [Nuevas visitas y cambios por revisar](#nuevas-visitas-y-cambios-por-revisar)
          - [Programación y estado de una visita](#programación-y-estado-de-una-visita)
          - [Servicio y tratamiento realizado](#servicio-y-tratamiento-realizado)
          - [Pagos y documentos dentro de la ficha de atención](#pagos-y-documentos-dentro-de-la-ficha-de-atención)
        - [Clientes](#clientes)
          - [Formulario de cliente particular o empresa](#formulario-de-cliente-particular-o-empresa)
          - [Ficha del cliente y cuentas autorizadas](#ficha-del-cliente-y-cuentas-autorizadas)
          - [Ubicaciones del cliente](#ubicaciones-del-cliente)
          - [Registro de servicios anteriores](#registro-de-servicios-anteriores)
        - [Calendario](#calendario)
        - [Catálogos](#catálogos)
        - [Cobros y documentos](#cobros-y-documentos)
          - [Revisión de pagos recibidos](#revisión-de-pagos-recibidos)
          - [Recibos no fiscales](#recibos-no-fiscales)
          - [Documentos fiscales de la atención](#documentos-fiscales-de-la-atención)
          - [Entrega de documentos de la atención](#entrega-de-documentos-de-la-atención)
      - [Cuenta compartida por portal y administración](#cuenta-compartida-por-portal-y-administración)
        - [Mi cuenta](#mi-cuenta)
    - [Comprobaciones del sistema](#comprobaciones-del-sistema)
  - [Semana 4 · Interacción e integración entre procesos](#semana-4--interacción-e-integración-entre-procesos)
  - [Semana 5 · Integración, DoD y Sprint Backlogs](#semana-5--integración-dod-y-sprint-backlogs)
    - [Product Backlog priorizado](#product-backlog-priorizado)
    - [Criterios utilizados para priorizar](#criterios-utilizados-para-priorizar)
    - [Criterios de terminación y aceptación](#criterios-de-terminación-y-aceptación)
    - [Sprints y Sprint Backlogs](#sprints-y-sprint-backlogs)
      - [Sprint 1: base técnica, acceso y datos iniciales](#sprint-1-base-técnica-acceso-y-datos-iniciales)
      - [Sprint 2: solicitudes, asociaciones y condiciones](#sprint-2-solicitudes-asociaciones-y-condiciones)
      - [Sprint 3: agenda, cobros y recibos](#sprint-3-agenda-cobros-y-recibos)
      - [Sprint 4: tratamientos, documentos e integración](#sprint-4-tratamientos-documentos-e-integración)
      - [Sprint 5: validación, respaldo y cierre](#sprint-5-validación-respaldo-y-cierre)
    - [Backlog técnico de implementación](#backlog-técnico-de-implementación)
      - [Simbología de las historias y las tareas](#simbología-de-las-historias-y-las-tareas)
      - [Dependencias de construcción y reglas de uso](#dependencias-de-construcción-y-reglas-de-uso)
      - [H01: Conocer RYC y contactar desde la Landing Page](#h01-conocer-ryc-y-contactar-desde-la-landing-page)
      - [H02: Iniciar sesión en la aplicación web](#h02-iniciar-sesión-en-la-aplicación-web)
      - [H03: Crear una cuenta de cliente](#h03-crear-una-cuenta-de-cliente)
      - [H04: Recuperar el acceso desde Olvidé mi contraseña](#h04-recuperar-el-acceso-desde-olvidé-mi-contraseña)
      - [H05: Consultar mi resumen y gestionar mis atenciones](#h05-consultar-mi-resumen-y-gestionar-mis-atenciones)
      - [H06: Consultar mis pagos y documentos](#h06-consultar-mis-pagos-y-documentos)
      - [H07: Consultar pendientes y gestionar las atenciones](#h07-consultar-pendientes-y-gestionar-las-atenciones)
      - [H08: Consultar y administrar Mi cuenta](#h08-consultar-y-administrar-mi-cuenta)
      - [H09: Gestionar clientes, ubicaciones y cuentas autorizadas](#h09-gestionar-clientes-ubicaciones-y-cuentas-autorizadas)
      - [H10: Programar visitas y administrar la disponibilidad](#h10-programar-visitas-y-administrar-la-disponibilidad)
      - [H11: Administrar los catálogos de plagas y productos](#h11-administrar-los-catálogos-de-plagas-y-productos)
      - [H12: Verificar cobros y gestionar documentos y entregas](#h12-verificar-cobros-y-gestionar-documentos-y-entregas)
      - [Componentes y tareas comunes](#componentes-y-tareas-comunes)
        - [Preparación inicial de la aplicación web](#preparación-inicial-de-la-aplicación-web)
        - [Componentes utilizados en las páginas](#componentes-utilizados-en-las-páginas)
        - [Pruebas de la aplicación web](#pruebas-de-la-aplicación-web)
        - [Entorno de entrega y respaldos](#entorno-de-entrega-y-respaldos)
        - [Guía, aceptación y cierre](#guía-aceptación-y-cierre)
      - [Etapas de las tareas comunes](#etapas-de-las-tareas-comunes)
    - [Historias de usuario desarrolladas — Especificación formal según plantilla](#historias-de-usuario-desarrolladas--especificación-formal-según-plantilla)
      - [Introducción y metodología de desarrollo](#introducción-y-metodología-de-desarrollo)
      - [Historia H01: Conocer RYC y contactar desde la Landing Page](#historia-h01-conocer-ryc-y-contactar-desde-la-landing-page)
      - [Historia H02: Iniciar sesión en la aplicación web](#historia-h02-iniciar-sesión-en-la-aplicación-web)
      - [Historia H03: Crear una cuenta de cliente](#historia-h03-crear-una-cuenta-de-cliente)
      - [Historia H04: Recuperar el acceso desde Olvidé mi contraseña](#historia-h04-recuperar-el-acceso-desde-olvidé-mi-contraseña)
      - [Historia H05: Consultar mi resumen y gestionar mis atenciones](#historia-h05-consultar-mi-resumen-y-gestionar-mis-atenciones)
        - [H05.1 — Solicitar consultorías con correo verificado](#h051--solicitar-consultorías-con-correo-verificado)
        - [H05.2 — Solicitar nuevas visitas y cambios de agenda](#h052--solicitar-nuevas-visitas-y-cambios-de-agenda)
        - [H05.3 — Consultar solicitudes y decidir propuestas](#h053--consultar-solicitudes-y-decidir-propuestas)
        - [H05.4 — Consultar resumen e historial de atenciones](#h054--consultar-resumen-e-historial-de-atenciones)
      - [Historia H06: Consultar mis pagos y documentos](#historia-h06-consultar-mis-pagos-y-documentos)
      - [Historia H07: Consultar pendientes y gestionar las atenciones](#historia-h07-consultar-pendientes-y-gestionar-las-atenciones)
        - [H07.1 — Registrar contactos y valorar consultorías](#h071--registrar-contactos-y-valorar-consultorías)
        - [H07.2 — Gestionar consultorías y comprobar el anticipo](#h072--gestionar-consultorías-y-comprobar-el-anticipo)
        - [H07.3 — Registrar el tratamiento y las recomendaciones reales](#h073--registrar-el-tratamiento-y-las-recomendaciones-reales)
        - [H07.4 — Publicar y corregir atenciones desde el panel operativo](#h074--publicar-y-corregir-atenciones-desde-el-panel-operativo)
      - [Historia H08: Consultar y administrar Mi cuenta](#historia-h08-consultar-y-administrar-mi-cuenta)
      - [Historia H09: Gestionar clientes, ubicaciones y cuentas autorizadas](#historia-h09-gestionar-clientes-ubicaciones-y-cuentas-autorizadas)
        - [H09.1 — Registrar y mantener clientes particulares y empresas](#h091--registrar-y-mantener-clientes-particulares-y-empresas)
        - [H09.2 — Administrar ubicaciones y frecuencias de visita](#h092--administrar-ubicaciones-y-frecuencias-de-visita)
        - [H09.3 — Asociar y revocar cuentas con permisos por sede](#h093--asociar-y-revocar-cuentas-con-permisos-por-sede)
        - [H09.4 — Incorporar antecedentes y clasificarlos por sede](#h094--incorporar-antecedentes-y-clasificarlos-por-sede)
      - [Historia H10: Programar visitas y administrar la disponibilidad](#historia-h10-programar-visitas-y-administrar-la-disponibilidad)
      - [Historia H11: Administrar los catálogos de plagas y productos](#historia-h11-administrar-los-catálogos-de-plagas-y-productos)
      - [Historia H12: Verificar cobros y gestionar documentos y entregas](#historia-h12-verificar-cobros-y-gestionar-documentos-y-entregas)
        - [H12.1 — Confirmar, rechazar y corregir cobros](#h121--confirmar-rechazar-y-corregir-cobros)
        - [H12.2 — Guardar y versionar recibos de pagos confirmados](#h122--guardar-y-versionar-recibos-de-pagos-confirmados)
        - [H12.3 — Custodiar facturas electrónicas externas y correcciones](#h123--custodiar-facturas-electrónicas-externas-y-correcciones)
        - [H12.4 — Registrar la entrega de documentos y recomendaciones](#h124--registrar-la-entrega-de-documentos-y-recomendaciones)
      - [Resumen de estimaciones y prioridades del Product Backlog](#resumen-de-estimaciones-y-prioridades-del-product-backlog)
      - [Consideraciones sobre la Definition of Done y entrega progresiva](#consideraciones-sobre-la-definition-of-done-y-entrega-progresiva)
      - [Conclusión](#conclusión)
  - [Semana 6 · Estimación y planificación de entregas](#semana-6--estimación-y-planificación-de-entregas)
    - [Matriz de estimación en puntos de historia](#matriz-de-estimación-en-puntos-de-historia)
      - [Formalización de los puntos de historia](#formalización-de-los-puntos-de-historia)
    - [Desglose de puntos de las historias subdivididas](#desglose-de-puntos-de-las-historias-subdivididas)
    - [Estimación y asignación de las tareas](#estimación-y-asignación-de-las-tareas)
    - [Equipo profesional y capacidad](#equipo-profesional-y-capacidad)
      - [Puestos, experiencia y dedicación](#puestos-experiencia-y-dedicación)
      - [Disponibilidad y carga por sprint](#disponibilidad-y-carga-por-sprint)
      - [Secuencia, capacidad y sensibilidad del plazo](#secuencia-capacidad-y-sensibilidad-del-plazo)
    - [Presupuesto del proyecto simulado](#presupuesto-del-proyecto-simulado)
      - [Tarifas profesionales y costo del equipo](#tarifas-profesionales-y-costo-del-equipo)
      - [Infraestructura y operación prevista](#infraestructura-y-operación-prevista)
      - [Presupuesto total y distribución](#presupuesto-total-y-distribución)
    - [Supuestos, dependencias y riesgos de la estimación](#supuestos-dependencias-y-riesgos-de-la-estimación)
    - [Capacidad y cierre en cinco sprints](#capacidad-y-cierre-en-cinco-sprints)
    - [Cronograma de entregas (Release Plan)](#cronograma-de-entregas-release-plan)

---

## Semana 1 · Definición del proyecto

> **Fecha lectiva de referencia:** miércoles 16 de septiembre de 2026, correspondiente a la Semana 1.
>
> **Resumen:** Identificación del problema, propuesta del sistema web, valor esperado y definición de objetivos generales y específicos.

### Problema

RYC conserva clientes, visitas, plagas, productos y próximas fumigaciones en medios dispersos. Cuesta consultar tratamientos, frecuencias y fechas de regreso. Los clientes dependen de llamadas o mensajes para conocer sus servicios y solicitar atención.

### Proyecto propuesto

Planificar y simular la construcción de una aplicación web con una página pública de presentación (Landing Page), Administración de César y un Portal del cliente
opcional. Las funciones siguientes describen el producto que construiría el equipo profesional del escenario.

La página pública presentará información real de RYC y facilitará el contacto por WhatsApp sin cuenta. César gestionará clientes, empresas, ubicaciones,
solicitudes, agenda, servicios, tratamientos, pagos y documentos desde celular y computadora.

RYC atiende en toda Costa Rica. La consultoría inicial será gratuita en el cantón de San Carlos; fuera se cotizará y cobrará completamente antes de la visita. El trabajo requiere 50% antes de iniciar
y 50% al finalizar, verificados por César.

Facturas y documentos se emitirán externamente y se entregarán sin exigir cuenta. Quien se registre podrá consultar el historial autorizado, solicitar atención o
informar pagos; César asociará registros existentes mediante el ID, con acceso por empresa o sede.

### Valor esperado

Centralizar el seguimiento de clientes, tratamientos y próximas visitas, y facilitar la consulta y solicitud de atención desde el portal opcional.

### Objetivo general

Planificar y simular el desarrollo del sistema web de RYC para gestionar clientes, visitas y tratamientos, con portal opcional, definiendo tareas, equipo, presupuesto y aceptación para completarlo en diez semanas y cinco sprints.

### Objetivos específicos

Capacidades previstas del producto:

- Presentar servicios, operador, zonas y condiciones reales; facilitar WhatsApp directo o con mensaje preparado, sin registro.
- Gestionar particulares, empresas y ubicaciones con o sin cuenta; reunir contactos de César y solicitudes del portal.
- Aplicar consultoría gratuita en San Carlos y cotización con pago previo fuera; trabajo con 50% de anticipo y saldo al finalizar.
- Verificar SINPE, efectivo y transferencias sin duplicar dinero; consultar confirmados por periodo y moneda.
- Conservar servicios, plagas, productos, cantidades, tratamientos y recomendaciones reales, con historial por cliente/lugar, agenda y seguimiento según frecuencia acordada.
- Facilitar las tareas de César en celular y computadora, reutilizando datos.
- Adjuntar documentos fiscales externos y registrar su entrega y la de recomendaciones sin exigir cuenta.
- Ofrecer portal opcional para solicitudes, reportes de pago y consulta de historial, pagos, documentos y próximas visitas.
- Asociar historial por ID sin duplicarlo; autorizar toda una empresa o solo la sede asignada.

## Semana 2 · Taller: interesados de nuestro proyecto

> **Fecha lectiva de referencia:** miércoles 23 de septiembre de 2026, correspondiente a la Semana 2.
>
> **Resumen:** Identificación y clasificación de interesados, matriz Poder–Interés, estrategias de involucramiento y restricciones del proyecto.

### Contexto y restricciones del proyecto

César concentra la operación y el conocimiento de RYC; su disponibilidad condiciona consultas y validación. La información histórica está dispersa: él decide qué incorporar.

Brian y Jeremy preparan el expediente; el equipo profesional hipotético representa la ejecución en diez semanas y cinco sprints. La aplicación necesita Internet, dispositivos compatibles y alojamiento. Priorizar ordena la construcción manteniendo el alcance.

### Registro de interesados

| Interesado                                                            | Necesidad                                                  | Poder | Interés | Actitud inicial     | Estrategia                                              | Responsable documental |
| --------------------------------------------------------------------- | ---------------------------------------------------------- | ----- | ------- | ------------------- | ------------------------------------------------------- | ---------------------- |
| César Rodríguez Corrales, propietario y operador                      | Centralizar clientes, visitas, tratamientos y seguimiento. | 5     | 5       | Favorable           | Consultar necesidades y validar avances de cerca.       | Brian y Jeremy         |
| Brian Rodríguez Pérez y Jeremy Rodríguez Esquivel, autores académicos | Requisitos y retroalimentación para el plan.               | 4     | 5       | Favorable           | Coordinar expediente, dudas y decisiones.               | Brian y Jeremy         |
| Diez profesionales hipotéticos                                        | Requisitos, dependencias y disponibilidad suficientes.     | 4     | 5       | Favorable, supuesto | Representar asignaciones, capacidad, costos y revisión. | Brian y Jeremy         |
| Clientes particulares                                                 | Historial, próximas visitas y solicitudes.                 | 2     | 4       | Favorable           | Informar y recoger comentarios del portal.              | Jeremy                 |
| Empresas clientes                                                     | Seguimiento de servicios y tratamientos.                   | 3     | 5       | Favorable           | Informar, consultar y validar necesidades del portal.   | Brian                  |
| Encargados de empresas                                                | Coordinar visitas e información para recibirlas.           | 3     | 5       | Favorable           | Informar y consultar la coordinación.                   | Jeremy                 |
| Proveedores de productos                                              | Identificación correcta de productos.                      | 2     | 2       | Neutral             | Monitorear y consultar datos puntuales.                 | Brian                  |
| Proveedor de alojamiento                                              | Requisitos técnicos claros.                                | 2     | 2       | Neutral             | Monitorear condiciones y disponibilidad.                | Brian                  |
| Entidades reguladoras aplicables                                      | Atender disposiciones pertinentes.                         | 5     | 2       | Neutral             | Identificar requisitos y mantener satisfechas.          | Brian y Jeremy         |

### Justificación de valoraciones relevantes

- **Autores y profesionales: poder 4, interés 5.** Planifican y ejecutarían, respectivamente; César valida el negocio.
- **Empresas y encargados: poder 3, interés 5.** Aportan requisitos y coordinación, sin autoridad identificada para aprobar cambios ni representar siempre a la empresa.
- **Proveedores: poder 2, interés 2.** Información puntual, sin autoridad sobre el sistema.
- **Reguladores: poder 5, interés 2.** Pueden condicionar decisiones sin participar diariamente. Falta identificar entidades y disposiciones concretas.

### Mapa Poder–Interés

![Mapa Poder–Interés del Sistema de Gestión para RYC Control de Plagas](img/mapa-poder-interes.png)

### Tres interesados críticos y su involucramiento

| Interesado         | Participación y momento                                                                                                                     | Responsable documental |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| César              | Consultas de necesidades y revisión de requisitos, recorridos y aceptación al inicio y cierre de ciclos, según disponibilidad.              | Brian y Jeremy         |
| Empresas           | Consultas y revisión de servicios, visitas y solicitudes durante la definición del portal. Las pruebas de software pertenecen al escenario. | Brian                  |
| Autores académicos | Reuniones y mensajes para repartir documentación, revisar avances y decidir; coordinación semanal y ante dudas o bloqueos.                  | Brian y Jeremy         |

### Preguntas de análisis de interesados

#### ¿A quién debemos involucrar primero?

A César, propietario y principal conocedor de la operación.

#### ¿Quién puede bloquear una decisión?

César puede modificar o detener decisiones del negocio; los requisitos regulatorios aplicables también pueden exigir cambios.

#### ¿Quién necesita información frecuente?

César, Brian y Jeremy para definir y validar el plan. La comunicación profesional se representa en los cinco sprints.

#### ¿Qué interesado estamos subestimando?

Los encargados de empresas: conocen cómo coordinan visitas y reciben servicios.

#### ¿Qué conflicto de expectativas puede aparecer?

La cantidad de funciones frente al plazo disponible, o diferencias entre la gestión interna de RYC y lo que esperan los clientes del portal.

### Enfoque de gestión del proyecto

Enfoque adaptativo: precisar requisitos con César y usuarios, según disponibilidad, y simular cinco ciclos con backlog y revisión de decisiones. Brian y Jeremy documentan cómo la retroalimentación afecta la ejecución profesional prevista, conservando los objetivos.

## Semana 3 Planeamiento del proyecto

> **Fecha lectiva de referencia:** miércoles 30 de septiembre de 2026, correspondiente a la Semana 3.
>
> **Resumen:** Definición del alcance, requisitos funcionales, procesos del negocio, seguridad, diseño de interfaces, tecnologías y estructura del sistema.

### Alcance y organización de la información

**César Rodríguez Corrales**, dueño y operador de RYC, organiza y realiza servicios para particulares y empresas. **Cliente** es quien solicita o recibe atención.

La aplicación se utiliza desde el navegador en celular o computadora:

| Área                    | Quién entra                                | Función                                                               |
| ----------------------- | ------------------------------------------ | --------------------------------------------------------------------- |
| Landing Page            | Cualquier persona, sin cuenta.             | Conocer RYC y contactar por WhatsApp.                                 |
| Acceso y Mi cuenta      | Cliente y César, con credenciales propias. | Ingresar, recuperar acceso y editar perfil.                           |
| Portal del cliente      | Cliente autenticado.                       | Consultar registros autorizados, solicitar atención e informar pagos. |
| Administración de César | César, con permiso administrativo.         | Gestionar todos los registros del negocio.                            |

Un login compartido dirige a cada área según permisos. César y el cliente autorizado consultan el mismo servicio publicado. **WhatsApp es el canal comercial principal; la cuenta es opcional**, incluso para pagos y documentos. El formulario público prepara un mensaje; solo el envío del portal o el registro del contacto recibido por César guarda una solicitud.

#### Cuenta, cliente y asociación

| Elemento   | Significado                                                                                                   |
| ---------- | ------------------------------------------------------------------------------------------------------------- |
| Cuenta     | Correo, contraseña, perfil e ID personal.                                                                     |
| Cliente    | Ficha de particular o empresa, contactos, ubicaciones e historial; existe sin cuenta.                         |
| Asociación | Autorización comprobada por César para consultar un cliente y sus lugares permitidos, sin duplicar historial. |

Registrarse no asocia historial. Aplicar [permisos](#permisos-de-consulta-y-solicitud) y [comprobación por ID](#asociación-mediante-id).

#### Atención sin cuenta: recorrido principal

1. La persona conoce RYC y envía el contacto por WhatsApp.
2. César busca coincidencias, registra el contacto y comprueba cliente/lugar.
3. César comprueba el lugar: consultoría gratuita en San Carlos o [cotización aceptada y 100% confirmado fuera](#consultoría-y-aceptación-del-servicio). Después de atender presenta el trabajo; aceptar su propuesta crea la orden.
4. Comparte instrucciones de pago, verifica dinero y aplica el [requisito para iniciar](#visitas-y-calendario).
5. Registra tratamiento y recomendaciones reales, cobra saldo y adjunta documentos externos.
6. Entrega documentos/recomendaciones y registra la entrega.
7. Si después se crea cuenta, comprueba su ID y asocia el mismo historial.

#### Atención con cuenta: recorrido opcional

El portal guarda una solicitud y ofrece **Consultar por WhatsApp** con su referencia. Cambiar de canal conserva la solicitud y reutiliza la orden del cobro correspondiente, sin duplicar decisiones ni pagos.

El cliente acepta propuestas e informa pagos; César registra respuestas externas y confirma dinero una vez. Rigen las mismas condiciones comerciales. Consultar servicios publicados o documentos autorizados en el portal no sustituye su entrega.

### Landing Page y contacto por WhatsApp

#### Contenido y recorrido

**Público.** Acción principal: **Contactar por WhatsApp**; secundaria: **Ver mi historial**.

| Sección, en orden   | Contenido                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------- |
| Encabezado          | RYC; Servicios, Cómo trabajamos, Zonas, Contacto; WhatsApp y portal.                           |
| Presentación        | Servicio, zona y foto real autorizada del operador si existe; WhatsApp y Preparar mi consulta. |
| Quién atiende       | Nombre, función y datos autorizados de César.                                                  |
| Servicios           | Servicios/plagas confirmados; consulta sin confirmar precio ni disponibilidad.                 |
| Cómo trabajamos     | Contacto, consultoría, propuesta, anticipo, tratamiento, saldo y documentos.                   |
| Zonas y condiciones | Atención en toda Costa Rica; consultoría gratuita en San Carlos y cotizada con pago previo fuera; condiciones y total antes de aceptar.                        |
| Historial opcional  | Servicios, tratamientos, recomendaciones, pagos y documentos; Crear cuenta/Ver mi historial.   |
| Contacto y cierre   | WhatsApp autorizado y formulario breve.                                                        |

#### Formulario breve para preparar el mensaje

En las tablas de campos, **\*** significa obligatorio; los demás son opcionales salvo condición indicada. Los límites de texto se expresan en **caracteres**. Teléfono, correo y territorio utilizan las [reglas comunes](#campos-del-registro).

| Campo, en orden         | Regla                                                          |
| ----------------------- | -------------------------------------------------------------- |
| Nombre de contacto \*   | 2–100; nombre completo, sin separar apellidos.                 |
| Teléfono de contacto \* | Teléfono común; puede responder desde el número con que envíe. |
| Cantón o lugar \*       | 2–150; César comprueba dirección y cantón después.             |
| Descripción \*          | 10–2000.                                                       |
| Fecha preferida         | Hoy o futura; no reserva.                                      |

Una columna. **Continuar en WhatsApp** prepara saludo y campos codificados al número real de RYC, conservando tildes/saltos; **Contactar sin formulario**, solo saludo. El usuario envía en WhatsApp o su versión web. Texto: **Prepararemos tu mensaje en WhatsApp. Revísalo y pulsa Enviar allí. Esto no reserva una visita.**

Abrir, copiar o regresar no registra solicitud, recepción ni reserva. Datos solo en la página abierta, sin guardarlos en base de datos, direcciones de la aplicación, analítica o diagnóstico. Ante fallo de WhatsApp/portapapeles, ofrecer número y texto para copia manual.

Sin correo, contraseña, identificación fiscal, pagos o archivos; César completa el contacto recibido. Sin chat web ni lectura automática de WhatsApp.

### Necesidades de los usuarios y resultados esperados

#### Necesidades de las personas interesadas y los clientes

Consultar [H01 — Landing Page](#h01-conocer-ryc-y-contactar-desde-la-landing-page), [H02 — Login](#h02-iniciar-sesión-en-la-aplicación-web), [H03 — Registro](#h03-crear-una-cuenta-de-cliente), [H04 — Recuperación](#h04-recuperar-el-acceso-desde-olvidé-mi-contraseña), [H05 — Panel del cliente](#h05-consultar-mi-resumen-y-gestionar-mis-atenciones), [H06 — Pagos/documentos](#h06-consultar-mis-pagos-y-documentos) y [H08 — Mi cuenta](#h08-consultar-y-administrar-mi-cuenta), compartida con César.

#### Necesidades de César

Consultar [H07 — Panel administrativo](#h07-consultar-pendientes-y-gestionar-las-atenciones), [H09 — Clientes](#h09-gestionar-clientes-ubicaciones-y-cuentas-autorizadas), [H10 — Calendario](#h10-programar-visitas-y-administrar-la-disponibilidad), [H11 — Catálogos](#h11-administrar-los-catálogos-de-plagas-y-productos) y [H12 — Cobros/documentos](#h12-verificar-cobros-y-gestionar-documentos-y-entregas).

#### Necesidades de RYC como empresa

En Sprint 5 se aceptaría aplicación validada, guía, archivos privados persistentes y recuperación comprobada, mediante las [tareas comunes](#componentes-y-tareas-comunes).

### Registro e inicio de sesión

Registro público de clientes; acceso administrativo de César asignado inicialmente. La cuenta sin verificar puede ingresar y editar perfil; solicitar atención exige correo verificado y teléfono. Correo automático para acceso; WhatsApp para comunicación comercial.

#### Campos del registro

Reglas comunes aplicables a todos los formularios; la tabla local determina obligatoriedad y valor inicial:

| Dato            | Regla común                                                                                                                                                                      |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Correo          | Formato válido, máximo 254. En cuentas: único, recortando espacios exteriores y normalizando para detectar duplicados.                                                           |
| Teléfono        | Ocho dígitos nacionales costarricenses; acepta +506 y separadores, máximo 20 caracteres introducidos. Retirar prefijo/separadores para validar; guardar con +506 para contactos. |
| Territorio      | Selectores de provincia, cantón y distrito dependientes del mismo catálogo. Cambiar provincia limpia cantón/distrito; cambiar cantón limpia distrito.                            |
| Fecha preferida | Selector de fecha: hoy o futura; expresa preferencia, sin reservar agenda.                                                                                                       |
| Monto           | Positivo, hasta dos decimales y moneda de la orden, salvo excepción explícita.                                                                                                   |

Registro, en este orden:

| Campo                 | Regla                                                            |
| --------------------- | ---------------------------------------------------------------- |
| Nombre completo \*    | 2–100; espacios, tildes, apóstrofos y guiones permitidos.        |
| Correo electrónico \* | Correo común; único.                                             |
| Teléfono              | Teléfono común; opcional al registrarse.                         |
| Contraseña \*         | 8–128; espacios y Unicode permitidos; admite pegar desde gestor. |
| Confirmación \*       | Coincidencia exacta con contraseña.                              |

#### Opciones del login

[Inicio de sesión](#inicio-de-sesión) permite entrar o recuperar acceso. **60 minutos** de inactividad finalizan la sesión; **Cerrar sesión** la invalida. Recuperación: enlace de un uso, **30 minutos**, con los dos pasos de [H04 — Recuperar acceso](#h04-recuperar-el-acceso-desde-olvidé-mi-contraseña).

#### Validación de formularios y seguridad de las cuentas

Aplicar las reglas y mensajes siguientes.

##### Mensajes al completar los formularios

Usar los [mensajes comunes](#mensajes-de-validación-de-campos) con los límites de cada campo.

##### Páginas y funciones de acceso

Login, registro y las dos páginas de recuperación están en [Acceso](#landing-page-y-acceso-a-la-aplicación-web); la [verificación](#verificación-del-correo-en-el-portal), dentro del Panel del cliente.

##### Medidas para proteger las cuentas

- Máximo **cinco fallos/minuto por correo y dirección IP** (dirección de red del intento); error definido en login.
- **Argon2id en Laravel 13:** guardar una huella de la contraseña (hash) y comprobar contra ella los intentos de acceso. No guardar contraseñas legibles ni incluirlas en registros de error/diagnóstico.
- El registro público no otorga administración. Para consultar historial y próximas visitas, exigir correo verificado y asociación activa según [permisos](#empresas-sedes-y-cuentas).

### Diseño y comportamiento en dispositivos

#### Dirección visual

Priorizar las tareas de César en ambos dispositivos. Historial en línea de tiempo. Usar logo real de RYC; mientras falte, **RYC Control de Plagas**.

#### Colores

| Uso                                           | Color          |
| --------------------------------------------- | -------------- |
| Acciones principales y encabezados destacados | Verde #166534  |
| Fondo de página                               | #F4F7F5        |
| Superficies de formularios y paneles          | Blanco #FFFFFF |
| Texto principal                               | #1F2937        |
| Bordes                                        | #CBD5E1        |
| Errores                                       | #B91C1C        |

#### Tipografía

Manrope 600 para encabezados; Source Sans 3, 400 para texto/formularios/tablas y 600 para etiquetas. Fuentes locales, alternativa sans-serif del sistema. Base 16 px/altura 1.5; etiquetas 14 px; título 28 px, 24 px en celular.

#### Login

Contenedor de ancho disponible, máximo **420 px**, centrado horizontal/vertical si cabe; alto según contenido y desplazamiento si excede la pantalla. Exterior 16 px en celular, 24 px mayor; interior 24 px, 32 px desde 640 px; radio 12 px; separación encabezado/formulario 24 px. Campos, botones, etiquetas y errores siguen las [convenciones](#convenciones-de-presentación).

#### Presentación de la administración y el portal

Contenido máximo **1280 px**. Navegación: lateral **240 px**, encabezado **64 px**, comportamiento en [Navegación](#navegación). Registro: una columna, máximo **520 px**, estilo login. Formularios, listados y accesibilidad: [convenciones comunes](#convenciones-de-presentación). Agrupar tareas por contacto, lugar, condiciones, programación, trabajo y documentos, con datos precargados y siguiente acción visible.

### Experiencia de uso de César

Celular y computadora ofrecen las mismas funciones y conservan cliente, ubicación y atención.

#### Registro por etapas y reutilización

La [ficha](#panel-de-administración-de-césar) reúne contacto, lugar, condiciones, pago, servicio, entrega y seguimiento, con datos disponibles precargados. Coincidencias de nombre/teléfono no fusionan clientes. El catálogo evita reescribir productos; cantidades, tratamiento y recomendaciones se comprueban por atención.

#### Guardado de formularios

Confirmar la acción guarda tras validar. Fallos o sesión vencida conservan el texto mientras la página siga abierta. Cancelar/salir con cambios exige confirmación. Guardar requiere conexión y sesión válida; aplicar [contexto común](#cómo-se-organiza-cada-página).

#### Acciones y estado

La ficha muestra registrado, pendiente y siguiente acción. Programar enlaza solicitud/visita; confirmar dinero recalcula saldo; publicar finaliza servicio/visita. César confirma decisiones, dinero, horario y tratamiento. Celular prioriza dato/acción siguiente; computadora admite dos columnas y tablas.

### Empresas, sedes y cuentas

**Empresa**: ficha administrativa. **Sede**: ubicación empresarial con historial propio. Existen sin cuenta; la asociación determina qué puede consultar cada cuenta.

#### Permisos de consulta y solicitud

El historial incluye visitas, plagas, productos, tratamientos, recomendaciones, pagos, recibos, facturas y próximas visitas.

| Cuenta               | Alcance                                                                                                                     |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Principal de empresa | Historial y atención de todas sus sedes.                                                                                    |
| De sede              | Historial y atención solo de la sede asignada.                                                                              |
| Particular           | Sus ubicaciones y atenciones.                                                                                               |
| Sin asociación       | Perfil, ID, solicitudes propias; consultoría con correo verificado. Pagos/documentos de órdenes nacidas de sus solicitudes. |
| César                | Todos los clientes, sedes y atenciones desde Administración.                                                                |

- Una cuenta se asocia a un solo particular/empresa; una empresa admite varias cuentas personales, cada cuenta de sede a una sede.
- Historia empresarial sin sede: solo César y cuentas principales hasta clasificarla.
- La solicitud conserva su cuenta autora. Con asociación activa, el cliente y sedes autorizados limitan incluso las órdenes propias anteriores.
- El servidor verifica permisos al listar, abrir, actuar, reportar pagos y descargar; cambiar ID en la dirección web no amplía acceso.
- El historial pertenece al cliente/lugar, no a la cuenta. Administración permanece separada del portal.

#### Ejemplo de acceso por sede

Una empresa tiene Sede A y Sede B:

| Cuenta           | Historial de A | Historial de B |
| ---------------- | -------------- | -------------- |
| Principal        | Sí             | Sí             |
| Cuenta de Sede A | Sí             | No             |
| Cuenta de Sede B | No             | Sí             |
| César            | Sí             | Sí             |

#### Justificación

Separar sedes protege el historial por lugar; las credenciales individuales identifican quién solicita o informa pagos.

### Asociación mediante ID

**ID** identifica la cuenta mediante **UUID v4** (identificador único universal, versión 4), visible con **Copiar ID** en Mi cuenta.

César busca el ID, comprueba nombre/correo verificado y autorización por WhatsApp/llamada a número conocido u otra vía verificable. El ID desde un contacto desconocido no basta. Para empresa selecciona Todas las sedes o Una sede propia.

Controles, registro de autorización, cambios y retirada: [Ficha del cliente y cuentas autorizadas](#ficha-del-cliente-y-cuentas-autorizadas). Reutilizar historial sin duplicar; mantener separados los clientes homónimos.

### Consultoría y aceptación del servicio

RYC atiende en **toda Costa Rica**. Solicitar no cuesta. La consultoría inicial es gratuita en todo el **cantón de San Carlos, Alajuela**; fuera del cantón se cotiza y exige el 100% confirmado antes de la visita, incluidos otros cantones de Alajuela. Tratamiento con propuesta independiente. Una nueva visita para necesidad conocida también exige condiciones y aceptación confirmadas por César.

#### Formulario de consultoría

El portal guarda y precarga cuenta/lugar; el formulario público solo prepara WhatsApp. Campos, en orden:

| Campo                       | Regla                                             |
| --------------------------- | ------------------------------------------------- |
| Tipo de solicitante \*      | Particular/Empresa.                               |
| Nombre de contacto \*       | 2–100; precargado desde cuenta.                   |
| Nombre de empresa           | Obligatorio para Empresa; 2–150.                  |
| Teléfono \*                 | Teléfono común.                                   |
| Correo de contacto \*       | Verificado de la cuenta, solo lectura.            |
| Provincia \*                | Selector territorial, inicialmente sin selección. |
| Cantón \*                   | Dependiente de provincia.                         |
| Distrito \*                 | Dependiente de cantón.                            |
| Dirección \*                | 10–500.                                           |
| Descripción del problema \* | 10–2000.                                          |
| Fecha preferida             | Regla común.                                      |

Con asociación, cliente fijo y ubicación activa autorizada; territorio/dirección de solo lectura. Cuenta de sede: su sede; principal: cualquier sede activa propia. Sin asociación, territorio/dirección editables según [reglas comunes](#campos-del-registro).

#### Estados de la consultoría

César gestiona los estados administrativos. La decisión del trabajo la registra el cliente desde el portal o César por el canal acordado; leer no cambia estados.

| Estado                            | Acción y siguiente estado                                                               |
| --------------------------------- | --------------------------------------------------------------------------------------- |
| Recibida                          | Revisar → En revisión; cancelar → Cancelada.                                            |
| En revisión                       | Confirmar visita → Consultoría programada; cancelar → Cancelada.                        |
| Consultoría programada            | Registrar atención → Consultoría realizada; cancelar antes de atender → Cancelada.      |
| Consultoría realizada             | Preparar propuesta con lugar, descripción y precio → Pendiente de decisión del trabajo. |
| Pendiente de decisión del trabajo | Registrar decisión y canal → Aceptada o No aceptada.                                    |

Se permite programar con pago pendiente. Cancelar conserva motivo, pagos y documentos para revisión. Aceptada, No aceptada y Cancelada cierran seguimiento; corregir conserva fecha/motivo y solicitud.

#### Cómo se registra la aceptación del trabajo

Propuesta: cliente, ubicación, descripción de 10–2000, total positivo de hasta dos decimales y moneda CRC/USD. Anticipo **50%**, redondeado a dos decimales; saldo = total − anticipo.

Cliente confirma sobre solicitud autorizada; César registra respuesta externa con fecha/canal. Aceptar crea una orden anterior al servicio con origen si existe, concepto, descripción, monto, moneda y condiciones. No confirma dinero ni asocia cuentas. Rechazar conserva decisión sin orden.

#### Orden y situación financiera

La consultoría cobrada y el trabajo aceptado generan órdenes distintas; cada una conserva servicio, ubicación, precio y condiciones. Estados con fecha/responsable: **Aceptada** al aceptar; **En atención** al iniciar; **Finalizada** al terminar; **Cancelada** con motivo.

Cada orden utiliza una sola moneda: CRC o USD. Sus pagos y saldos se registran en esa moneda. Los resúmenes de varias órdenes mantienen CRC y USD separados, sin convertirlos.

Pago separado: **Sin pagos confirmados**, **Pago parcial**, **Pago completo** o **Saldo a favor pendiente de revisión**. Solo dinero confirmado reduce deuda; pendientes, rechazados y facturas no descuentan.

#### Datos del reporte de pago

| Campo                  | Regla                                                                       |
| ---------------------- | --------------------------------------------------------------------------- |
| Orden \*               | Autorizada y fija; cliente, lugar, total y moneda de solo lectura.          |
| Concepto \*            | Consultoría, anticipo o saldo, según orden.                                 |
| Monto \*               | Monto común.                                                                |
| Medio \*               | SINPE, efectivo o transferencia.                                            |
| Fecha/hora del pago \* | Real, no futura; America/Costa_Rica.                                        |
| Referencia bancaria    | Obligatoria para SINPE/transferencia; 2–100.                                |
| Comprobante            | Obligatorio para SINPE/transferencia; PDF/JPG/PNG, tipo real, máximo 5 MiB. |
| Comentario             | Hasta 1000; visible para cliente autorizado y César.                        |

#### Comunicación y seguimiento de los pagos

Reunir reportes de todos los canales en la misma orden. César comunica resultado por el canal acordado y registra cuándo/cómo. Estado junto al pago: Pendiente de revisión, Confirmado o Rechazado con motivo; sin mensajes automáticos a WhatsApp.

#### Archivos, permisos y alcance comercial

Archivos privados y autorizados: César adjunta recibos/documentos fiscales; cliente reporta pagos y datos de facturación. Se excluyen emisión fiscal automática, pasarelas, conciliación bancaria automática, contratos e integración de conversaciones.

### Clientes, ubicaciones y servicios

#### Cliente particular

| Campo                 | Regla                                       |
| --------------------- | ------------------------------------------- |
| Nombre completo \*    | 2–100.                                      |
| Teléfono principal \* | Teléfono común.                             |
| Correo de contacto    | Correo común; cliente permitido sin correo. |
| Identificación        | Hasta 30; conservar formato real.           |
| Nota interna          | Hasta 2000, privada.                        |
| Estado \*             | Activo inicialmente; Activo/Inactivo.       |

#### Empresa

| Campo                   | Regla                                 |
| ----------------------- | ------------------------------------- |
| Razón social \*         | 2–150.                                |
| Nombre comercial        | Hasta 150.                            |
| Identificación          | Hasta 30; formato del documento real. |
| Contacto principal \*   | 2–100.                                |
| Teléfono de contacto \* | Teléfono común.                       |
| Correo de contacto      | Correo común.                         |
| Nota interna            | Hasta 2000, privada.                  |
| Estado \*               | Activo inicialmente; Activo/Inactivo. |

Identificación no asocia automáticamente; aplicar [comprobación por ID](#asociación-mediante-id).

#### Servicio realizado

Conservar cliente/lugar, visita de origen si existe, fecha real, tipo (consultoría/tratamiento/seguimiento), plagas, productos/cantidades, tratamiento, recomendaciones, notas internas y próxima atención programada. Relacionar orden, confirmados y documentos cuando corresponda. Campos y publicación en [Servicio y tratamiento realizado](#servicio-y-tratamiento-realizado).

Desactivar clientes, empresas, ubicaciones y catálogos conserva historial y bloquea uso nuevo. Las correcciones de servicios finalizados conservan fecha/motivo.

### Plagas, productos y tratamientos

César mantiene los catálogos y registra los elementos realmente utilizados.

#### Catálogo de plagas

Nombre obligatorio de 2–100; descripción opcional hasta 1000; estado Activo/Inactivo.

#### Catálogo de productos

Nombre comercial obligatorio de 2–150; ingrediente activo opcional hasta 150, referencia interna/proveedor hasta 100 y nota hasta 1000; estado Activo/Inactivo.

#### Registro del tratamiento

- Plagas: una o varias; sin ellas, marcar Preventivo y justificar con 10–2000 caracteres.
- Descripción: 10–2000, obligatoria en Tratamiento; zona opcional hasta 500.
- Por producto utilizado: producto, cantidad decimal positiva y unidad **mL, L, g, kg o unidad**. No exigir químico no utilizado.
- Método real opcional hasta 500; recomendaciones y observaciones internas opcionales hasta 2000 cada una.

Registrar lo informado por César; no prescribir químicos/dosis ni copiar cantidades/tratamientos de otra atención. Notas internas privadas.

#### Publicación del historial

Distinguir propuesta, programación y servicio publicado. Solo el último muestra tratamiento real, sin notas internas; admite históricos incompletos según [Información histórica](#información-histórica).

### Visitas y calendario

César crea/confirma visitas; el cliente solicita atención o cambios y consulta lo confirmado.

#### Datos de una visita

Cliente, ubicación, tipo (consultoría/tratamiento/seguimiento), inicio, duración **15–480 minutos**, descripción hasta 500, estado Programada/En curso/Realizada/Cancelada y motivo de cambio/cancelación. Formulario en [Programación](#programación-y-estado-de-una-visita).

#### Reglas

- Zona **America/Costa_Rica**; programación nueva presente/futura; impedir superposición entre visitas activas y bloqueos de César. Reservar traslados manualmente y prever duración suficiente.
- Reprogramar conserva fecha anterior/motivo; cancelar, visita/motivo. El cliente solicita y César confirma.
- Frecuencia en días sugiere próxima fecha; César confirma creación. Finalizar registra servicio real.
- Atención nueva cobrada exige orden aceptada: **100% confirmado** para consultoría fuera de San Carlos; **50%** para trabajo. Comprobar al iniciar y al finalizar/publicar directamente sin inicio, incluso sin visita de origen. Saldo restante no bloquea publicar.
- Históricos no se bloquean por orden/pagos antiguos desconocidos.

#### Presentación

FullCalendar Standard: Mes, Semana y Lista en Administración; próximas visitas en portal con fecha/hora/lugar/estado. Fechas día/mes/año y horas de 24 h.

### Información histórica

Carga manual de clientes activos, lugares y servicios relevantes para César. Conservar origen histórico y fecha de incorporación separados de fecha real disponible. Adjuntar originales disponibles; sin inventar archivos/respuestas de Hacienda.

Dato desconocido: **No registrado**; fecha desconocida: **Fecha no registrada**, al final. Empresa sin sede: solo César/principal hasta clasificar. No exige cuenta; asociación posterior consulta los mismos registros. [Registro anterior](#registro-de-servicios-anteriores) permite ubicación/fecha desconocidas.

### Tecnología, alojamiento y entrega

#### Tecnologías

| Parte                                       | Tecnología                                                                                  |
| ------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Aplicación                                  | Laravel 13 y PHP 8.4.                                                                       |
| Interfaz                                    | Livewire, Blade y Tailwind CSS, con starter kit oficial.                                    |
| Base de datos                               | MySQL.                                                                                      |
| Autenticación                               | Herramientas del starter kit, configuradas según las reglas de registro e inicio de sesión. |
| Calendario                                  | FullCalendar Standard.                                                                      |
| Comprobantes, recibos y documentos fiscales | Archivos en almacenamiento privado y persistente.                                           |
| Correos                                     | Servicio SMTP para verificación y recuperación.                                             |
| Repositorio                                 | GitHub                                                                                      |

**Términos:** PHP ejecuta lógica del servidor; CSS, estilos; SQL consulta datos; SMTP envía correo; HTTPS cifra acceso web. XML estructura datos; PDF documentos; JPG/PNG imágenes.

Starter kit oficial para acceso, interfaz/negocio en un proyecto; fijar versiones al prepararlo. Referencias: [Laravel](https://laravel.com/docs/13.x/releases), [Argon2id](https://laravel.com/docs/13.x/hashing).

César aprueba número internacional público, cobros, instrucciones de efectivo, textos y fotos. Incorporarlos inicialmente y probar contacto en ambos dispositivos.

#### Alojamiento de la demostración y del piloto

**T078 — Preparación** organiza versiones, instrucciones, datos aprobados y entorno local (MySQL, correo de prueba, archivos privados); **T079 — Modelo de datos** carga esos datos.

**T101 — Publicación en Railway**, a cargo del profesional DevOps: Laravel, MySQL, variables, HTTPS y volúmenes persistentes para datos y archivos privados. El escenario con SMTP requiere **Railway Pro o superior**, según su [política de correo saliente](https://docs.railway.com/networking/outbound-networking). Comprobar envío, descargas autorizadas y permanencia tras reinicios/actualizaciones. Brian y Jeremy documentan dependencias/aceptación.

Los [costos de infraestructura](#infraestructura-y-operación-prevista) son provisiones, sin contratación ni precio garantizado.

#### Respaldo y entrega

Condiciones del escenario:

- Respaldo diario de datos/documentos: **siete copias diarias y cuatro semanales**, gestionadas por el procedimiento de T102 — Respaldos. Comprobar esa retención; los [respaldos nativos de Railway](https://docs.railway.com/volumes/backups) tienen plazos propios y no sustituyen la copia externa cifrada.
- Originales fiscales: **al menos cinco años**; rotar copias no los elimina. [Decreto 44739-H, considerando III](https://www.pgrweb.go.cr/DOCS/NORMAS/1/VIGENTE/D/2020-2029/2020-2024/2024/19326/16FAC2.HTML). Revisar obligaciones y conservación adicional con RYC antes de ejecutar.
- Copia semanal cifrada fuera del alojamiento, bajo control de RYC.
- Restaurar copia válida en entorno de prueba y comprobar consulta de datos/archivos antes de entregar.
- Versión HTTPS, datos de demostración y guía. Datos reales solo tras validar permisos, archivos, respaldo y aceptación.

En el curso se documentan procedimientos/casos; resultados ficticios rotulados simulados.

### Páginas del sistema y su contenido

#### Convenciones de presentación

Aplicar el [diseño común](#diseño-y-comportamiento-en-dispositivos):

| Elemento              | Regla                                                                                                                                                                                             |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Idioma y tamaños      | Español. Pequeña <640 px; intermedia 640–1023; amplia ≥1024. Exterior 16/24/32 px respectivamente.                                                                                                |
| Formulario de gestión | Ancho disponible, máximo 960 px; blanco, interior 24 px, radio 12 px.                                                                                                                             |
| Título/acciones       | Título arriba, acciones al final; celular: botones de ancho completo, apilados, separación 12 px.                                                                                                 |
| Campos                | Etiqueta visible a 8 px; grupos a 16 px; \* y leyenda para obligatorios.                                                                                                                          |
| Controles             | Alto mínimo 48 px; correo, texto con teclado telefónico, contraseña oculta y números según campo.                                                                                                 |
| Texto/columnas        | Texto extenso en área de ancho completo, inicialmente 96 px de alto, ampliable. Una columna bajo 640 px; dos iguales desde 640, separación 16 px. Dirección, descripción y notas a todo el ancho. |
| Listados              | Filtros arriba; 20 registros/página, Anterior/Siguiente abajo. Tarjetas bajo 1024 px; tablas desde 1024, mismos datos/acciones; comparación horizontal adicional.                                 |
| Confirmaciones        | Centradas, máximo 420 px, interior 24 px; descripción, Cancelar/confirmar y desplazamiento vertical.                                                                                              |
| Contraseña            | Mostrar contraseña/Ocultar contraseña al final del campo, sin cambiar valor.                                                                                                                      |
| Accesibilidad         | Teclado, etiquetas, áreas táctiles 44 × 44 px; foco verde de 2 px separado 2 px.                                                                                                                  |
| Guardado              | **Guardando…**, botón inhabilitado; repetir no duplica registros.                                                                                                                                 |
| Validación            | Texto/color de error debajo; conservar valores y enfocar primer campo inválido.                                                                                                                   |
| Inicio/carga          | Datos disponibles, opcionales sin valor vacíos; **Cargando…**, habilitar dependientes al terminar.                                                                                                |
| Sin resultados        | **No hay registros para mostrar.** Ofrecer Limpiar filtros si existen.                                                                                                                            |
| Error                 | **No se pudo completar la operación. Inténtalo de nuevo.** Conservar contenido cuando corresponda.                                                                                                |
| Éxito                 | **Contacto guardado**, **Pago confirmado**, **Visita programada** o **Servicio publicado**; registro actualizado.                                                                                 |
| Autorización          | **No tienes permiso para consultar esta información.** Ocultar contenido.                                                                                                                         |
| Sesión finalizada     | **Tu sesión terminó. Inicia sesión para continuar**; conservar texto mientras la página siga abierta.                                                                                             |

Acceso: una columna, medidas de [Login](#login); recuperación usa ese contenedor y registro máximo 520 px.

#### Mensajes de validación de campos

Los límites indicados entre llaves se sustituyen por los valores de la tabla del campo correspondiente.

| Condición                                       | Mensaje                                                              |
| ----------------------------------------------- | -------------------------------------------------------------------- |
| Campo obligatorio vacío                         | Completa este campo.                                                 |
| Correo incorrecto                               | Escribe un correo válido.                                            |
| Texto fuera de un intervalo                     | Escribe entre {mínimo} y {máximo} caracteres.                        |
| Texto que supera un máximo                      | No superes {máximo} caracteres.                                      |
| Teléfono inválido                               | Escribe un teléfono de 8 dígitos; puedes incluir +506 y separadores. |
| Opción inválida o ajena al cliente autorizado   | Selecciona una opción válida.                                        |
| Cantidad o monto no positivo                    | Escribe un número mayor que cero.                                    |
| Duración fuera de límites                       | Escribe una duración de entre 15 y 480 minutos.                      |
| Frecuencia inválida                             | Escribe un número entero de días entre 1 y 365.                      |
| Fecha preferida en el pasado                    | Selecciona hoy o una fecha futura.                                   |
| Fecha y hora de programación nueva en el pasado | Selecciona una fecha y hora actuales o futuras.                      |
| Fecha de atención o documento en el futuro      | La fecha no puede ser futura.                                        |
| Formato de fecha o de hora inválido             | Escribe una fecha y hora válidas.                                    |
| Comprobante o recibo no permitido               | Adjunta un archivo PDF, JPG o PNG.                                   |
| Documento fiscal no permitido                   | Adjunta un XML original o un PDF de representación, según el campo.  |
| Archivo demasiado grande                        | El archivo no puede superar 5 MiB.                                   |
| Final de bloqueo anterior o igual al inicio     | El final debe ser posterior al inicio.                               |

Los opcionales vacíos no generan error. Los valores introducidos cumplen formato y límites; al registrar en el sistema se comprueban también en servidor. El [Formulario de contacto por WhatsApp](#formulario-de-contacto-por-whatsapp) solo prepara el mensaje y no registra datos.

#### Navegación

| Área                    | Menú, en orden                                                                            |
| ----------------------- | ----------------------------------------------------------------------------------------- |
| Landing Page            | Servicios; Cómo trabajamos; Zonas; Contacto; Contactar por WhatsApp; Ver mi historial.    |
| Portal del cliente      | Inicio; Pagos y documentos; Mi cuenta; Contactar por WhatsApp.                            |
| Administración de César | Inicio (Panel de César); Clientes; Calendario; Catálogos; Cobros y documentos; Mi cuenta. |
| Cuenta                  | Cerrar sesión.                                                                            |

RYC al inicio del encabezado. Lateral visible desde 1024 px; debajo, **Menú** abre/cierra, seleccionar y Escape cierran. La Landing utiliza su [encabezado público](#landing-page-de-ryc).

Historial/próximas visitas requieren correo verificado y asociación activa; demás funciones según [permisos](#empresas-sedes-y-cuentas). Sin asociación: **Aún no tienes un historial asociado. Comunica tu ID a César si ya has recibido servicios.**

#### Cómo se organiza cada página

Una fila por página; H04 reúne los dos pasos de recuperación.

| Área                    | Página y contenido                                                                                | Historia                                                         |
| ----------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Pública                 | [Landing Page](#landing-page-de-ryc): presentación, servicios, zonas y WhatsApp.                  | [H01](#h01-conocer-ryc-y-contactar-desde-la-landing-page)        |
| Acceso                  | [Inicio de sesión](#inicio-de-sesión): ingreso, registro y recuperación.                          | [H02](#h02-iniciar-sesión-en-la-aplicación-web)                  |
| Acceso                  | [Crear cuenta](#crear-cuenta): registro opcional.                                                 | [H03](#h03-crear-una-cuenta-de-cliente)                          |
| Acceso                  | [Recuperar acceso](#recuperar-acceso): solicitar enlace.                                          | [H04](#h04-recuperar-el-acceso-desde-olvidé-mi-contraseña)       |
| Acceso                  | [Cambiar contraseña](#cambiar-contraseña-por-recuperación): guardar contraseña.                   | [H04](#h04-recuperar-el-acceso-desde-olvidé-mi-contraseña)       |
| Portal del cliente      | [Panel del cliente](#panel-del-cliente): resumen, solicitudes, visitas, historial y verificación. | [H05](#h05-consultar-mi-resumen-y-gestionar-mis-atenciones)      |
| Portal del cliente      | [Pagos y documentos](#pagos-y-documentos): pagos, filtros, reportes, facturación y descargas.     | [H06](#h06-consultar-mis-pagos-y-documentos)                     |
| Administración de César | [Panel de César](#panel-de-administración-de-césar): pendientes, listado y atención.              | [H07](#h07-consultar-pendientes-y-gestionar-las-atenciones)      |
| Compartida              | [Mi cuenta](#mi-cuenta): perfil e ID.                                                             | [H08](#h08-consultar-y-administrar-mi-cuenta)                    |
| Administración de César | [Clientes](#clientes): ficha, ubicaciones, cuentas e históricos.                                  | [H09](#h09-gestionar-clientes-ubicaciones-y-cuentas-autorizadas) |
| Administración de César | [Calendario](#calendario): visitas y bloqueos.                                                    | [H10](#h10-programar-visitas-y-administrar-la-disponibilidad)    |
| Administración de César | [Catálogos](#catálogos): plagas/productos.                                                        | [H11](#h11-administrar-los-catálogos-de-plagas-y-productos)      |
| Administración de César | [Cobros y documentos](#cobros-y-documentos): pagos, archivos y entregas.                          | [H12](#h12-verificar-cobros-y-gestionar-documentos-y-entregas)   |

**Contexto común:** formularios largos dentro de su sección; confirmaciones breves en diálogo. Guardar actualiza; Cancelar descarta cambios pendientes tras confirmar. Conservar registro, datos guardados, pestaña y filtros. Celular apila secciones. Listados y accesos rápidos utilizan los mismos registros/permisos.

#### Landing Page y acceso a la aplicación web

##### Landing Page de RYC

**Pública**, con [secciones y orden](#contenido-y-recorrido) aprobados por César. Una columna; desde 1024 px, texto/foto en dos si existe imagen autorizada. Sin datos de clientes ni sustitución de condiciones.

Encabezado con RYC, navegación, WhatsApp y **Ver mi historial**. Celular: **Menú** despliega sin tapar controles; contacto accesible. Enlaces internos, foco y teclado siguen el contenido.

**Contactar por WhatsApp** prepara saludo; **Preparar mi consulta** abre el [formulario](#formulario-de-contacto-por-whatsapp); **Ver mi historial**, login; **Crear cuenta**, registro. Sin número autorizado y probado en ambos dispositivos se bloquea publicar contacto.

###### Formulario de contacto por WhatsApp

Una columna, máximo 640 px; [campos y comportamiento](#formulario-breve-para-preparar-el-mensaje). **Continuar en WhatsApp** y **Copiar mensaje** validan en navegador. **Contactar sin formulario** prepara saludo; fallo de apertura/copia ofrece número/texto manuales. Pedir revisar y enviar en WhatsApp; abrir, copiar o regresar nunca muestra **Solicitud recibida** ni **Visita confirmada**.

##### Inicio de sesión

**Público. Orden:** RYC, **Iniciar sesión**, correo, contraseña, **Entrar**, recuperación, registro. Campos obligatorios/vacíos; correo común y contraseña oculta con **Mostrar contraseña**.

**Entrar** o Enter envían. César entra a Administración; cliente a su Panel con aviso de verificación si falta. **Olvidé mi contraseña** abre [Recuperar acceso](#recuperar-acceso); **Crear cuenta**, [registro](#crear-cuenta); **Volver a RYC**, Landing. WhatsApp sin sesión.

Errores: **El correo o la contraseña no coinciden.** / **Demasiados intentos. Espera un minuto y vuelve a intentarlo.** Aplicar [seguridad/sesión](#registro-e-inicio-de-sesión).

##### Crear cuenta

**Público**, una columna, [campos del registro](#campos-del-registro) en orden; nombre/correo/teléfono de una línea y contraseñas ocultas con mostrar/ocultar.

**Crear cuenta** valida, genera cuenta/ID y abre Panel con aviso de verificación; no crea empresa ni autoriza historial. **Ya tengo cuenta** abre login.

Mensajes: **Escribe entre 8 y 128 caracteres.**, **Las contraseñas no coinciden.**, **Este correo ya está registrado. Inicia sesión o recupera tu acceso.**

##### Recuperar acceso

**Público**, desde Olvidé mi contraseña. Correo obligatorio, vacío, con regla común.

**Enviar enlace** responde para cualquier correo: **Si el correo corresponde a una cuenta, recibirás un enlace para recuperar el acceso.** Enlace de [30 minutos y un uso](#opciones-del-login). **Volver a iniciar sesión** abre login.

##### Cambiar contraseña por recuperación

Segundo paso con enlace válido. Nueva contraseña y Confirmar contraseña obligatorias/vacías, con [reglas del registro](#campos-del-registro).

**Guardar contraseña** invalida enlace/sesiones anteriores, muestra **Contraseña actualizada** y abre login; **Volver a iniciar sesión** también lleva allí. Enlace vencido/usado: **El enlace de recuperación no es válido. Solicita uno nuevo.**

#### Portal del cliente

##### Panel del cliente

**Cliente autenticado. Orden:**

1. Nombre y aviso de correo sin verificar.
2. Tarjetas: servicios recientes, próxima visita, pagado/pendiente. Una columna en celular, dos desde 640 px, separación 16 px.
3. **Solicitar consultoría**, **Solicitar nueva visita** si se permite, **Contactar por WhatsApp**. Texto: **Visita inicial gratuita en San Carlos; fuera del cantón se cotiza.**
4. Pestañas Solicitudes (inicial), Próximas visitas e Historial.

**Ver solicitudes**, **Ver próxima visita** y **Ver historial** eligen pestaña y llevan al inicio de su contenido. Un listado visible; pestañas accesibles con teclado también en celular. Detalles/formularios permanecen dentro del panel según [contexto común](#cómo-se-organiza-cada-página).

**Ver mis pagos** abre [Pagos y documentos](#pagos-y-documentos); atención consulta los mismos pagos/archivos. Aplicar [permisos](#empresas-sedes-y-cuentas); sin asociación, mostrar vínculo, acceso a Mi cuenta para copiar ID y solicitudes propias.

###### Verificación del correo en el portal

Cuenta autenticada sin verificar: correo, instrucción de revisar mensaje, **Reenviar correo de verificación**, Mi cuenta y **Cerrar sesión**; perfil disponible.

Enlace de **60 minutos** para esa cuenta; reenvío bloqueado **60 segundos** con espera visible. Verificar actualiza Panel/habilita funciones. Error: **El enlace de verificación no es válido. Solicita uno nuevo.**

###### Solicitudes y seguimiento del cliente

Solo propias; no cambiar estados administrativos. Listado: fecha, tipo, lugar, estado, **Ver detalle**. Filtros Consultoría/Nueva visita y estado; **Limpiar filtros**. Detalle: datos enviados, costo, decisiones y programación.

Costo pendiente: **Aceptar costo de consultoría** / **No aceptar costo**, confirmando total/lugar según [decisión](#consultoría-y-aceptación-del-servicio). **Ir a pagos** despliega orden en el detalle. WhatsApp conserva referencia y decisiones en la misma solicitud.

###### Formulario de consultoría del portal

Correo verificado; [campos, orden y ubicación](#formulario-de-consultoría). **Enviar solicitud** guarda Recibida y abre detalle. **Consultar por WhatsApp** usa referencia, tipo y lugar guardados, sin duplicar ni incluir pagos/documentos.

Texto: **Enviar la solicitud no tiene costo. La visita inicial es gratuita en el cantón de San Carlos; fuera de ese cantón se cotiza y se paga antes de realizarla. La fecha indicada es una preferencia.**

###### Formulario de nueva visita

Cuenta verificada/asociada; cliente/contacto de solo lectura.

| Campo, en orden | Regla                                                                           |
| --------------- | ------------------------------------------------------------------------------- |
| Ubicación \*    | Selector de activas autorizadas; una se precarga, varias inician sin selección. |
| Teléfono \*     | Común, precargado desde cuenta si existe.                                       |
| Descripción \*  | Vacía; 10–2000.                                                                 |
| Fecha preferida | Vacía; regla común.                                                             |

**Enviar solicitud** guarda Recibida y abre detalle; **Cancelar** cierra conservando Solicitudes. WhatsApp reutiliza referencia.

Sin ubicaciones: **Contacta a César para registrar o activar el lugar de atención.** Texto: **Enviar la solicitud es gratuito. César confirmará la programación y las condiciones del servicio.**

###### Propuesta del trabajo y decisión del cliente

Cuenta solicitante autorizada: propuesta, lugar, total/moneda, anticipo, saldo y decisión. Documentos disponibles desde que se adjuntan, antes o después del trabajo.

Solo pendiente: **Aceptar servicio** / **No aceptar**. Confirmaciones: **¿Confirmas que aceptas este servicio por el monto indicado?** / **¿Confirmas que no deseas contratar este servicio?** **Cancelar** conserva decisión.

Aplicar [aceptación](#cómo-se-registra-la-aceptación-del-trabajo); mostrar referencia/anticipo/saldo y **Ir a pagos** dentro del detalle. **Completar datos de facturación** envía a revisión; WhatsApp lleva referencia y respuesta externa cierra la misma decisión pendiente.

###### Próximas visitas y solicitud de cambios

Mostrar fecha/hora, ubicación, tipo, duración y estado; identificar canceladas. Solo Programada ofrece **Solicitar cambio**: Reprogramación/Cancelación, motivo 2–1000 y fecha preferida opcional solo al reprogramar.

**Enviar solicitud** muestra **Cambio solicitado**; visita original continúa hasta revisión de César. En curso/Realizada no permiten estos cambios desde portal.

###### Historial de servicios del cliente

Línea de tiempo descendente; filtros ubicación/fechas, **Aplicar filtros**, **Limpiar filtros**. Mostrar fecha, lugar, tipo y **Ver detalle** con plagas, tratamiento, productos/cantidades/unidades, recomendaciones y recibos.

Solo publicados/autorizados, sin notas internas; deuda no oculta servicio. Datos desconocidos y empresa sin sede: [Información histórica](#información-histórica).

##### Pagos y documentos

**Cliente con correo verificado y [permisos](#empresas-sedes-y-cuentas)**. Pagos, reportes, facturación y archivos; detalle de orden con total, pagado y pendiente. Panel del cliente utiliza los mismos registros.

###### Pagos y reportes del cliente

Listado: fecha, referencia del servicio, lugar, monto/moneda, medio, estado y **Ver detalle**. Filtros Fecha desde/hasta, Estado, Medio y Ubicación si hay varias; **Aplicar filtros**, **Limpiar filtros**. Mes actual inicialmente.

Detalle: total, pagado, pendiente, instrucciones, comprobantes, documentos y WhatsApp. **Informar pago** usa [datos del reporte](#datos-del-reporte-de-pago), orden fija. Cambiar medio confirma retirar adjunto no enviado. **Enviar reporte** guarda Pendiente de revisión y muestra **Pago reportado. César debe confirmar que recibió el dinero.** **Cancelar** conserva detalle.

Estado junto al pago: **Pendiente de revisión**, César debe comprobar; **Confirmado**, dinero comprobado; **Rechazado**, motivo y **Reportar corrección**, conservando reporte anterior. César revisa en Administración.

Sumar debajo solo confirmados que cumplen filtros, por recepción real en America/Costa_Rica, **CRC/USD separados**. No sumar pendientes, rechazados ni facturas. Correcciones usan monto/fecha vigentes con seguimiento; cambios de asociación actualizan permisos. Saldo a favor queda en revisión.

Sin datos: **No hay pagos confirmados en este periodo**.

###### Datos de facturación de la orden

**Completar datos de facturación** precarga orden; **Enviar datos** deja a revisión de César para emisión externa. No exigir al registrarse ni al crear cliente sin facturación; validar obligatoriedad fiscal concreta.

| Campo, en orden           | Regla                                                                       |
| ------------------------- | --------------------------------------------------------------------------- |
| Nombre/razón social \*    | 2–150.                                                                      |
| Tipo de identificación    | Selector: física, jurídica, DIMEX, NITE u otra admitida por emisor externo. |
| Identificación            | Hasta 30; requerida según tipo, conservar ceros iniciales.                  |
| Correo para documentos    | Correo común, según entrega externa.                                        |
| Provincia/cantón/distrito | Territorio común para dirección nacional.                                   |
| Dirección detallada       | 10–500.                                                                     |
| Información adicional     | Opcional, hasta 1000.                                                       |

No cambiar automáticamente razón social/identificación maestra. **DIMEX**: Documento de Identidad Migratorio para Extranjeros; **NITE**: Número de Identificación Tributaria Especial.

###### Documentos y descargas del cliente

Listado: tipo, referencia, fecha, orden/servicio, lugar, monto/moneda y estado fiscal. Filtros tipo, lugar y fechas; **Aplicar filtros**, **Limpiar filtros**.

**Descargar recibo**, **Ver PDF**, **Descargar XML** y **Descargar respuesta** si existe. Conservar originales/correcciones; aplicar [permisos](#empresas-sedes-y-cuentas), [históricos](#información-histórica) y [estado fiscal](#documentos-fiscales-de-la-atención). Mostrar entregas autorizadas; disponibilidad en portal no prueba entrega por WhatsApp.

#### Administración de César

##### Panel de administración de César

**César.** Resumen arriba, listado debajo. La ficha reúne **Contacto y lugar, Propuesta, Programación, Pagos, Servicio y Documentos**, con referencia, cliente, ubicación y siguiente acción visibles.

| Resumen, en orden                    | Datos/acción                                                               |
| ------------------------------------ | -------------------------------------------------------------------------- |
| Visitas de hoy                       | Hora, cliente, lugar, estado; Abrir atención/Iniciar visita si se permite. |
| Solicitudes pendientes               | Portal y contactos recibidos guardados por César.                          |
| Pagos por verificar/saldos al cierre | Orden, cliente, monto/moneda; Revisar pago.                                |
| Documentos pendientes                | Referencia, respuesta/entrega pendiente; Abrir documentos.                 |

Encabezado: **Registrar contacto**, **Buscar cliente**, **Programar visita**. Tarjeta Solicitudes selecciona listado; otras abren atención/orden en su sección.

Listado de contactos, consultorías, nuevas visitas y servicios; búsqueda contacto/empresa y filtros tipo/estado. Aplicar [contexto común](#cómo-se-organiza-cada-página); Calendario/Cobros reutilizan registros.

Resumen: una columna celular, dos desde 1024 px. En celular precede al listado; elegir atención abre formularios. Conservar foco al abrir/cerrar ficha; teclado disponible. Solo datos del servidor: enlace público de WhatsApp no crea filas.

###### Registro rápido de un contacto

Desde Panel o ficha del cliente; **Buscar cliente** por nombre/teléfono/identificación, precargado desde ficha. Cliente activo y ubicación completa se exigen antes de cotizar/programar.

| Campo, en orden        | Regla                                                                                   |
| ---------------------- | --------------------------------------------------------------------------------------- |
| Cliente existente      | Selector con búsqueda; vacío salvo desde ficha. Solo activos para atención nueva.       |
| Nombre del contacto \* | 2–100; precargado al elegir cliente, editable si llama otra persona.                    |
| Teléfono \*            | Común; precargado si existe.                                                            |
| Lugar indicado         | Vacío/dato conocido, hasta 500; sin considerar ubicación verificada.                    |
| Motivo \*              | 10–2000; consulta recibida por César.                                                   |
| Fecha preferida        | Regla común.                                                                            |
| Origen \*              | WhatsApp inicialmente; Llamada/Presencial/Otro medio acordado. Otro: descripción 2–100. |

**Guardar contacto** valida y abre ficha Recibida con referencia/origen/fecha; no crea automáticamente cliente, empresa, cuenta, lugar definitivo, orden, pago o visita. **Cancelar** aplica cambios pendientes.

Elegir/crear cliente y ubicación reutiliza contacto. Coincidencias: **Abrir registro existente** / **Continuar como contacto distinto**, sin fusionar/asociar. WhatsApp no envía documentos ni cambia seguimiento. Celular una columna/acciones apiladas; computadora hasta dos, motivo a todo el ancho.

###### Consultorías y propuesta del trabajo

Listado: fecha, contacto, tipo, empresa, lugar, origen Portal/WhatsApp/registro de César, estado y **Ver detalle**. Filtros estado/tipo/contacto-empresa. **Registrar contacto** abre su formulario; detalle reúne solicitud, lugar, cotización, orden, pagos, visita y decisiones.

Acciones: **Revisar solicitud**, **Revisar costo**, **Programar consultoría**, **Registrar consultoría realizada**, **Preparar propuesta**, **Registrar decisión**, **Cancelar consultoría**, según [costo](#consultoría-y-aceptación-del-servicio), [estados](#estados-de-la-consultoría) y [aceptación](#cómo-se-registra-la-aceptación-del-trabajo). Exigir cliente/lugar completos para cotizar/programar. Leer/elegir cliente no cambia estados ni asocia. Cancelación previa: motivo 2–1000; corrección: fecha/motivo.

Compartir propuesta al contacto autorizado por WhatsApp y registrar envío; también visible a cuenta solicitante autorizada. Decisión: resultado, fecha real, canal Portal/WhatsApp/Llamada/Presencial/Otro medio acordado y nota opcional hasta 1000; sin duplicar orden.

**Preparar mensaje** copia referencia/lugar/condiciones, sin enviar ni confirmar recepción. Registrar realización aplica [pago previo](#visitas-y-calendario).

###### Nuevas visitas y cambios por revisar

Listado: fecha, cliente, lugar, tipo Nueva visita/Cambio de visita, preferencia, estado y **Ver detalle**.

Estados de nueva visita: **Recibida, En revisión, Programada, Cancelada**; de cambio: **Recibida, En revisión, Aplicada, No aplicada**.

**Revisar solicitud**, **Programar visita**, **Aplicar cambio**, **No aplicar**; cancelar/no aplicar exige motivo 2–1000. Revisar conserva agenda; aplicar registra cambio/cancelación y resultado en portal. Programar enlaza una visita; trabajo nuevo con cobro exige propuesta y orden aceptadas. Puede programarse con pago pendiente; iniciar exige el anticipo confirmado.

###### Programación y estado de una visita

| Campo, en orden | Regla                                                                                                                   |
| --------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Cliente \*      | Selector, sin selección; activos.                                                                                       |
| Ubicación \*    | Dependiente, inhabilitada hasta cliente; solo sus activas.                                                              |
| Tipo \*         | Selector Consultoría/Tratamiento/Seguimiento; sin selección.                                                            |
| Orden de cobro  | Selector dependiente, obligatorio para atención nueva cobrada; aceptada del mismo cliente/lugar, sin selección inicial. |
| Inicio \*       | Fecha/hora vacía; presente/futura.                                                                                      |
| Duración \*     | Entero vacío; 15–480 minutos.                                                                                           |
| Descripción     | Vacía, hasta 500.                                                                                                       |
| Estado \*       | Solo lectura, Programada inicialmente; acciones autorizadas.                                                            |

Filas: cliente/ubicación; tipo/duración; orden; fecha/hora; descripción. Mostrar pago requerido/confirmado; desde solicitud, cliente/lugar precargados y fijos.

**Guardar visita/Cancelar**. Programada: **Iniciar visita/Reprogramar/Cancelar visita**. En curso: **Finalizar atención** con servicio real. Realizada/Cancelada conserva seguimiento. Reprogramar pide inicio, duración y motivo 2–1000; cancelar, confirmación/motivo; corregir finalizados, motivo.

Aplicar [agenda y pago previo](#visitas-y-calendario), incluida publicación directa. Mensajes: **Ese horario se superpone con otra visita o bloqueo de agenda.** / **Falta confirmar el pago requerido para iniciar esta atención.**

###### Servicio y tratamiento realizado

Listado: fecha, cliente, lugar, tipo, estado, **Ver detalle**; filtros cliente/lugar/tipo/fechas. Grupos: Datos de atención, Plagas y productos, Tratamiento, Recomendaciones, Observaciones internas.

Para nuevos: cliente, ubicación, fecha real no futura y tipo obligatorios; visita precarga cliente/lugar/orden. Aplicar [campos del servicio](#servicio-realizado) y [tratamiento](#registro-del-tratamiento). Plagas múltiples; **Añadir producto/Quitar fila**, producto vertical en celular y tabla en computadora.

**Finalizar y publicar** confirma/valida datos y [pago previo](#visitas-y-calendario); publica servicio, marca visita Realizada y muestra saldo, sin exigir deuda restante pagada. Excepción histórica y notas privadas vigentes. **Corregir servicio** conserva motivo 2–1000, fecha y seguimiento.

###### Pagos y documentos dentro de la ficha de atención

Pagos: orden, comprobantes, confirmados, saldo y [revisión](#revisión-de-pagos-recibidos). Documentos: [recibos](#recibos-no-fiscales), [fiscales](#documentos-fiscales-de-la-atención) y [entregas](#entrega-de-documentos-de-la-atención). Reutilizar formularios con cliente/orden precargados, sin salir de atención.

##### Clientes

**César.** Listado, registro/edición y ficha. Mostrar nombre/razón social, tipo, contacto, teléfono, estado; buscar nombre/razón social/teléfono/identificación, filtrar Particular/Empresa y Activo/Inactivo.

**Ver/Editar/Desactivar/Reactivar/Nuevo cliente**. Celular: **Abrir ficha** principal; resto en menú identificado. Desactivar con confirmación conserva ficha, lugares, asociaciones e historial, permite consulta autorizada y bloquea atención nueva hasta reactivar. Coincidencias no fusionan/asocian.

###### Formulario de cliente particular o empresa

Elegir tipo y [campos](#clientes-ubicaciones-y-servicios). Primera fila: nombre/teléfono o razón social/nombre comercial; correo/identificación juntos, notas a todo el ancho; demás en orden y una columna celular.

**Guardar cliente/Cancelar**. Editar precarga y fija tipo. No exige cuenta ni correo; Activo inicial, notas privadas.

###### Ficha del cliente y cuentas autorizadas

Encabezado: nombre/razón social, tipo, estado. Secciones: Datos, Atenciones, Ubicaciones, Cuentas, Historial, Pagos y Documentos. Atenciones enlaza solicitud, propuesta, orden, visita, servicio/documentos por referencia, con datos precargados; **Registrar contacto** precarga cliente.

Cuentas: nombre, correo, ID, alcance, sede, fecha. **Asociar cuenta** pide ID; **Buscar cuenta** muestra nombre/correo verificado. Errores: **Introduce un ID de cuenta válido.** / **No se encontró una cuenta con ese ID.**

Comprobar [autorización por ID](#asociación-mediante-id): canal WhatsApp/Llamada/Otro medio acordado (Otro: descripción 2–100) y **He confirmado que esta persona está autorizada para consultar este historial**. Empresa: Todas las sedes/Una sede propia; particular: sus ubicaciones, sin selector empresarial.

**Guardar asociación** exige correo verificado/autorización; registra responsable, fecha, cuenta, cliente, alcance, sede y canal. **Cambiar alcance**: nueva comprobación, motivo 2–1000, antes/después y fecha. **Retirar asociación** confirma y revoca el acceso concedido por esa asociación. Las solicitudes y órdenes propias siguen sujetas a los [permisos generales](#permisos-de-consulta-y-solicitud). No duplicar; retirar anterior antes de otro cliente.

###### Ubicaciones del cliente

Listado: nombre, dirección, provincia/cantón/distrito, estado; **Editar/Desactivar/Reactivar**. Formulario: cliente fijo, nombre, territorio, dirección, acceso, frecuencia, estado según [Ubicación](#ubicaciones-del-cliente). Activo inicial; frecuencia opcional de 1–365 días enteros, acordada con César, sin recomendar tratamiento.

**Guardar ubicación/Cancelar** cierra en página de origen; desde atención, guardar selecciona lugar y conserva otros datos. Inactiva conserva historial y bloquea atención nueva.

###### Registro de servicios anteriores

**Registrar servicio anterior** abre Registro histórico desde ficha; cliente obligatorio, lugar/fecha pueden desconocerse. Aplicar [históricos](#información-histórica) y límites de datos introducidos. Revisar/publicar habilita consulta autorizada.

**Clasificar sede** exige sede de la misma empresa y fecha/responsable/motivo. Sin ubicación no generar próxima visita.

##### Calendario

**César.** Mes/Semana/Lista, periodo visible, **Hoy/Anterior/Siguiente**. Visita con hora/cliente/lugar; seleccionar abre detalle/acciones.

**Programar visita** reutiliza [formulario](#programación-y-estado-de-una-visita); guardar/cancelar conserva periodo. Zona/formatos según [Visitas](#visitas-y-calendario).

**Bloquear horario**: descripción 2–500 e inicio/final obligatorios, final posterior; traslado/indisponibilidad sin cliente. Impedir solapamientos; modificar/retirar conserva seguimiento.

**Sugerir próxima visita** = fecha del servicio finalizado + frecuencia del lugar. César revisa horario/duración/conflictos y confirma; sugerir no reserva.

##### Catálogos

**César.** Plagas/Productos con búsqueda por nombre, filtro de estado y [campos](#plagas-productos-y-tratamientos). Listar nombre/descripción/estado de plagas; nombre comercial/ingrediente/referencia/estado de productos. Nombre/ingrediente de una línea, descripción/nota de varias.

**Guardar/Cancelar/Editar/Desactivar/Reactivar**; Activo inicial. Desactivar confirma, conserva referencias históricas y excluye uso nuevo.

##### Cobros y documentos

**César.** Pagos, Recibos y Documentos fiscales. Abrir orden muestra movimientos/archivos para confirmar, rechazar, adjuntar o registrar entregas. Reutilizar formularios desde atención con cliente/lugar/orden precargados.

###### Revisión de pagos recibidos

Listado: fecha, cliente, sede, orden, concepto, medio, monto, referencia, estado, **Revisar**. Filtros estado (inicial Pendiente de revisión), cliente/sede/medio/fechas. Detalle: reporte, instrucciones, comprobante, verificaciones y saldo; origen Portal/WhatsApp/Registro de César, cliente/orden precargados desde atención.

Para SINPE o transferencia, César comprueba el ingreso en la cuenta bancaria de RYC. Para efectivo, comprueba que recibió físicamente el dinero; no se exige referencia ni comprobante bancario. En todos los medios, solo la confirmación de César reduce el saldo.

- **Confirmar pago**: monto/fecha reales precargados; diferencias exigen motivo 2–1000 y **He comprobado que RYC recibió este dinero**, una vez.
- **Rechazar reporte**: motivo 2–1000 junto al pago; comunicar resultado por canal acordado.
- **Registrar pago recibido**: cliente/orden/concepto/medio/monto/fecha y [referencia/archivo según medio](#datos-del-reporte-de-pago), también sin cuenta.
- **Corregir registro de pago**: motivo, antes/después y responsable, sin alterar facturas.
- **Adjuntar recibo/Adjuntar documento fiscal/Revisar datos de facturación**.

Duplicado abre existente: **Esta referencia ya tiene un pago confirmado. Revisa el registro.** Exceso: **Saldo a favor pendiente de revisión**, sin devolver ni aplicar a otra orden automáticamente.

###### Recibos no fiscales

Constancias de dinero confirmado. Listado: referencia, cliente/lugar, orden/pago, fecha, monto/moneda; **Ver/Descargar/Sustituir archivo**. Filtros cliente/lugar/referencia/fechas. Desde pago confirmado precargar cliente/orden/pago/monto/moneda.

| Campo        | Regla                                                                  |
| ------------ | ---------------------------------------------------------------------- |
| Cliente \*   | Con o sin cuenta.                                                      |
| Orden        | Obligatoria en cobro nuevo; aceptada, sin exigir servicio finalizado.  |
| Pago         | Obligatorio en recibo nuevo; confirmado.                               |
| Servicio     | Opcional cuando exista; no exigir para anticipo.                       |
| Referencia   | Obligatoria en nuevo, hasta 100; histórico desconocido: No registrado. |
| Fecha        | Obligatoria en nuevo; real, no futura.                                 |
| Monto/moneda | Obligatorios en nuevo; positivo, dos decimales, CRC/USD del pago.      |
| Archivo \*   | PDF/JPG/PNG, tipo real, máximo 5 MiB.                                  |
| Nota interna | Hasta 1000, privada.                                                   |

Mostrar nombre/tamaño y **Quitar archivo** antes de enviar. **Guardar recibo/Cancelar**; nombre generado/archivo privado. Sustituir conserva versión/motivo 2–1000, sin aplicar a facturas. Históricos conservan relaciones conocidas; Clasificar sede usa lugar del mismo cliente con seguimiento.

###### Documentos fiscales de la atención

Facturas/notas externas. Listado: tipo, consecutivo, cliente/sede, orden, emisión, total/moneda, estado, **Ver detalle**. Filtros cliente/sede/tipo/estado/fechas. **Adjuntar documento** abre:

| Campo                 | Regla                                                                                                                                    |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Cliente/orden         | Obligatorios en nuevos; cliente y sede de orden, sin mezclar sedes.                                                                      |
| Tipo \*               | Factura electrónica, nota de crédito/débito.                                                                                             |
| Consecutivo/clave \*  | Copiados del XML, no generados: consecutivo de 20 dígitos y clave de 50 caracteres, respetando el formato del emisor; únicos por emisor. |
| Emisión \*            | Fecha/hora real, no futura.                                                                                                              |
| Total/moneda \*       | Total positivo del XML, hasta cinco decimales, sin recortar su precisión; moneda igual a la orden. No modifica el saldo.                 |
| Relación con cobro \* | Consultoría/anticipo/saldo/total.                                                                                                        |
| Pago relacionado      | Uno o varios de la misma orden.                                                                                                          |
| Documento corregido   | Obligatorio en notas/reemplazo rechazado; original de la misma orden.                                                                    |
| XML original          | Obligatorio en nuevo; válido, máximo 5 MiB, sin resolver entidades externas.                                                             |
| PDF                   | Obligatorio en nuevo; válido, máximo 5 MiB.                                                                                              |
| Respuesta de Hacienda | Cuando exista; XML, máximo 5 MiB, misma clave.                                                                                           |
| Estado \*             | Solo lectura: Pendiente de respuesta; Aceptado/Rechazado solo según XML de respuesta válido.                                             |

Archivos: nombre/tamaño, **Quitar archivo** antes de guardar. **Guardar documento** valida formato/pertenencia y coteja metadatos/XML; no valida en línea con Hacienda. Sin respuesta, Pendiente. **Adjuntar respuesta** conserva archivo/actualiza estado sin sustituir original. Formatos de referencia: [Hacienda, anexos 4.4, encabezado y total](https://www.hacienda.go.cr/docs/ANEXOS_Y_ESTRUCTURAS_V4.4.pdf). Los históricos conservan originales y datos disponibles según [Información histórica](#información-histórica).

**Ver PDF/Descargar XML/Descargar respuesta/Adjuntar nota relacionada**, esta a original de misma orden. **Adjuntar comprobante corregido** enlaza nuevo/rechazado, conservando ambos; no eliminar/reemplazar facturas ni fabricar históricos. Revisar [receptor](#datos-de-facturación-de-la-orden) sin alterar ficha maestra.

###### Entrega de documentos de la atención

**Preparar entrega** descarga archivos/copia recomendaciones, sin enlaces públicos permanentes. **Registrar entrega**, dentro de orden:

| Campo           | Regla                                                                                       |
| --------------- | ------------------------------------------------------------------------------------------- |
| Destinatario \* | Precargado, 2–150.                                                                          |
| Canal \*        | Inicialmente vacío: WhatsApp/correo/presencial/otro acordado; Otro exige descripción 2–100. |
| Fecha/hora \*   | Actual editable, no futura.                                                                 |
| Elementos \*    | Uno o más documentos/recomendaciones de atención.                                           |

**He realizado esta entrega** conserva datos, responsable y fecha de declaración. Descargar, adjuntar o abrir WhatsApp no registra entrega ni acredita lectura.

#### Cuenta compartida por portal y administración

##### Mi cuenta

**Cliente y César, perfil propio.** Nombre, correo, teléfono e ID; correo/ID de solo lectura. **Copiar ID** muestra **ID copiado**. **Editar datos** habilita nombre/teléfono con [reglas del registro](#campos-del-registro); **Guardar cambios/Cancelar**. **Recuperar contraseña** abre recuperación; **Cerrar sesión** invalida sesión y abre login.

### Comprobaciones del sistema

Documentar entradas, pasos y resultados esperados de estos casos; rotular **simulado** cualquier resultado ficticio. Cada enlace remite a las reglas y mensajes aplicables.

| Grupo y reglas                                                                               | Casos y resultado esperado                                                                                                                                                                                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Registro y acceso](#registro-e-inicio-de-sesión)                                            | Rechazar datos inválidos conservando lo válido; crear solo cliente. Sin verificar, editar perfil pero no solicitar. Rechazar enlaces inválidos, vencidos o usados; recuperación una sola vez.                                                                                                                                                                                   |
| [Asociaciones y permisos](#empresas-sedes-y-cuentas)                                         | Copiar/asociar ID correcto y revocar el acceso concedido al retirar la asociación. Comprobar aparte los permisos sobre solicitudes y órdenes propias. Probar dos clientes y dos sedes sin consultas ni descargas ajenas. Restringir historia sin sede y órdenes anteriores al alcance activo.                                                                                   |
| [Solicitudes y aceptación](#solicitudes-y-seguimiento-del-cliente)                           | Rechazar empresa sin nombre, fecha pasada, lugar inactivo/ajeno o aceptación sin propuesta pendiente. Cancelar conserva decisión; aceptar crea una orden.                                                                                                                                                                                                                       |
| [Agenda y cambios](#visitas-y-calendario)                                                    | Cambio solicitado conserva visita hasta decisión de César. Rechazar superposición con visita/bloqueo sin reservar horario.                                                                                                                                                                                                                                                      |
| [Clientes](#clientes) y [catálogos](#catálogos)                                              | Registrar sin cuenta/correo. Desactivar conserva historial y bloquea uso nuevo; producto previo sigue visible.                                                                                                                                                                                                                                                                  |
| [Cobro previo](#consultoría-y-aceptación-del-servicio)                                                  | San Carlos ₡0; fuera 100% confirmado y trabajo 50%, incluso al publicar directamente. Aceptación congela tarifa, cálculo, total e instrucciones.                                                                                                                                                                                                                                |
| [Pagos](#revisión-de-pagos-recibidos)                                                        | Repetir reporte/referencia no duplica dinero. Pendientes/rechazados no reducen saldo; efectivo confirmado sin cuenta sí. Deuda restante permite publicación.                                                                                                                                                                                                                    |
| [Servicios](#servicio-y-tratamiento-realizado)                                               | Rechazar tratamiento sin plaga/justificación preventiva y cantidades no positivas. Publicar tratamiento y recomendaciones reales, sin notas internas.                                                                                                                                                                                                                           |
| [Historia anterior](#registro-de-servicios-anteriores)                                       | Lugar desconocido: **No registrado**; fecha desconocida: **Fecha no registrada**. No generar visita ni inventar datos.                                                                                                                                                                                                                                                          |
| [Recibos](#recibos-no-fiscales) y [documentos fiscales](#documentos-fiscales-de-la-atención) | Rechazar tipo/tamaño inválido, extensión falsa, identificadores fiscales incompletos, respuesta XML de otra clave y entidades externas. Conservar el total original del XML hasta cinco decimales. Versionar recibo; conservar originales, notas y corregido enlazado al rechazado. Facturas/estado fiscal no alteran saldo. Admitir anticipos y documentos antes de finalizar. |
| [Contacto público](#formulario-de-contacto-por-whatsapp)                                     | Sin cuenta en celular/computadora; preservar tildes, saltos y opcionales. Abrir/copiar no registra ni reserva; fallos ofrecen número/texto.                                                                                                                                                                                                                                     |
| [Contacto administrativo](#registro-rápido-de-un-contacto)                                   | Guardar sin ficha/lugar completos; reutilizar referencia sin duplicar. Cotizar/programar exige cliente y ubicación comprobados.                                                                                                                                                                                                                                                 |
| [Canales y entrega](#entrega-de-documentos-de-la-atención)                                   | Portal/WhatsApp conservan solicitud, orden y dinero únicos. Entregar sin cuenta; asociación posterior conserva archivos. Adjuntar/descargar no entrega ni acredita lectura.                                                                                                                                                                                                     |
| [Consulta de pagos](#pagos-y-reportes-del-cliente)                                           | Combinar/limpiar filtros de fecha, estado, medio y ubicación; mostrar motivo de rechazo. Sumar solo confirmados del periodo por moneda; descargar recibos/facturas desde el mismo detalle.                                                                                                                                                                                      |
| [Panel del cliente](#panel-del-cliente)                                                      | Tarjetas abren su pestaña y un listado a la vez; guardar/cancelar conserva contexto. Ver mis pagos abre Pagos y documentos; correo/asociación limitan acceso.                                                                                                                                                                                                                   |
| Uso general                                                                                  | Reenvíos sin duplicados; completar con teclado y pantalla pequeña. César recorre celular/computadora; registrar dificultades y correcciones.                                                                                                                                                                                                                                    |

---

## Semana 4 · Interacción e integración entre procesos

> **Fecha lectiva de referencia:** miércoles 7 de octubre de 2026, correspondiente a la Semana 4.
>
> **Resumen:** Product Backlog inicial y continuidad entre planificación, ejecución y seguimiento.

El material de Semana 4 introduce el Product Backlog inicial, la selección de trabajo para un sprint y su seguimiento. El desarrollo consolidado del backlog, la DoD y los Sprint Backlogs se presenta en [Semana 5](#semana-5--integración-dod-y-sprint-backlogs).

El backlog alimenta la planificación del sprint; sus tareas describen la ejecución prevista y las comprobaciones permiten revisar el resultado y ajustar el plan. La [DoD](#criterios-de-terminación-y-aceptación) define la calidad exigida. La estimación vigente y la proyección de entregas se documentan en [Semana 6](#semana-6--estimación-y-planificación-de-entregas).

---

## Semana 5 · Integración, DoD y Sprint Backlogs

> **Fecha lectiva de referencia:** miércoles 14 de octubre de 2026, correspondiente a la Semana 5.
>
> **Resumen:** Consolidación del Product Backlog, criterios de calidad, Sprint Backlog 1 y planificación del escenario de cinco sprints.

El material de esta semana pide la DoD y el Sprint Backlog 1 a partir del backlog iniciado en Semana 4. Este apartado reúne el backlog detallado, las tareas y las historias con sus subdivisiones. Los cinco Sprint Backlogs describen la ejecución hipotética; sus fechas se mantienen como referencias del escenario. Las [estimaciones, capacidad y costos](#estimación-y-asignación-de-las-tareas) se desarrollan en Semana 6.

### Product Backlog priorizado

El Product Backlog reúne **12 historias principales**. H05, H07, H09 y H12 contienen cuatro subdivisiones cada una: **16 subdivisiones en total**. La estimación vigente es de **124 puntos de historia**, adoptada como línea base de planificación de la simulación según la [formalización documentada](#formalización-de-los-puntos-de-historia).

La tabla se presenta por identificador para localizar cada historia. La columna **Orden de prioridad** conserva la prioridad de implementación registrada; la ejecución también respeta las dependencias.

| Historia principal | Subdivisiones | Orden de prioridad | Prioridad | Puntos vigentes |
| --- | --- | ---: | --- | ---: |
| [H01: Conocer RYC y contactar desde la Landing Page](#h01-conocer-ryc-y-contactar-desde-la-landing-page) | — | 4 | Alta | 5 |
| [H02: Iniciar sesión en la aplicación web](#h02-iniciar-sesión-en-la-aplicación-web) | — | 2 | Alta | 5 |
| [H03: Crear una cuenta de cliente](#h03-crear-una-cuenta-de-cliente) | — | 3 | Alta | 5 |
| [H04: Recuperar el acceso desde Olvidé mi contraseña](#h04-recuperar-el-acceso-desde-olvidé-mi-contraseña) | — | 5 | Media | 5 |
| [H05: Consultar mi resumen y gestionar mis atenciones](#h05-consultar-mi-resumen-y-gestionar-mis-atenciones) | H05.1–H05.4 | 11 | Media | 18 (subtotal) |
| [H06: Consultar mis pagos y documentos](#h06-consultar-mis-pagos-y-documentos) | — | 12 | Media | 8 |
| [H07: Consultar pendientes y gestionar las atenciones](#h07-consultar-pendientes-y-gestionar-las-atenciones) | H07.1–H07.4 | 9 | Alta | 20 (subtotal) |
| [H08: Consultar y administrar Mi cuenta](#h08-consultar-y-administrar-mi-cuenta) | — | 6 | Media | 3 |
| [H09: Gestionar clientes, ubicaciones y cuentas autorizadas](#h09-gestionar-clientes-ubicaciones-y-cuentas-autorizadas) | H09.1–H09.4 | 1 | Alta | 21 (subtotal) |
| [H10: Programar visitas y administrar la disponibilidad](#h10-programar-visitas-y-administrar-la-disponibilidad) | — | 7 | Alta | 8 |
| [H11: Administrar los catálogos de plagas y productos](#h11-administrar-los-catálogos-de-plagas-y-productos) | — | 8 | Alta | 5 |
| [H12: Verificar cobros y gestionar documentos y entregas](#h12-verificar-cobros-y-gestionar-documentos-y-entregas) | H12.1–H12.4 | 10 | Alta | 21 (subtotal) |
| **Total** | **16 subdivisiones en 4 historias principales** | — | **8 principales Alta / 4 principales Media** | **124** |

Los subtotales de las cuatro historias desglosadas incluyen sus subdivisiones. Los puntos se suman una sola vez: **44 puntos de las ocho historias sin subdividir + 80 de las dieciséis subdivisiones = 124**. Los puntos expresan esfuerzo relativo, complejidad e incertidumbre. Las horas-persona se conservan en la tabla de estimaciones técnicas.

Terminar una historia principal desglosada exige comprobar todas sus subdivisiones y los componentes comunes que correspondan. Propuestas, órdenes, saldos, permisos y facturación utilizan los mismos registros y se construyen y estiman una vez.

### Criterios utilizados para priorizar

1. Clientes/lugares independientes de cuentas y contacto público sin registro.
2. Cuentas, verificación, asociación y permisos antes de consultas/descargas restringidas.
3. Propuesta/orden y cobro antes de atención nueva con costo; documentos admitidos antes del tratamiento finalizado.
4. Dependencias terminadas antes de cada tarea, también dentro del sprint.
5. Incrementos integrados comprobables, con evidencia documental del ejercicio.
6. Capacidad profesional, revisión cruzada y retroalimentación del negocio.

### Criterios de terminación y aceptación

**Calidad del producto representado — Definición de Terminado (DoD):**

Cada historia debe cumplir sus criterios de aceptación y los siguientes criterios de calidad:

1. **Pruebas:** definir los casos unitarios, de integración y manuales aplicables, con entradas, pasos y resultados esperados; resolver los fallos que impidan aceptar la historia.
2. **Seguridad:** comprobar validaciones y permisos en el servidor para proteger los registros y archivos de cada cliente y sede.
3. **Uso en dispositivos:** comprobar celular, computadora y teclado, con etiquetas, foco visible y conservación del registro abierto y sus datos al guardar o cancelar.
4. **Revisión técnica:** otro integrante del equipo profesional del escenario revisa el trabajo y se resuelven sus observaciones.
5. **Integración:** incorporar los cambios a la rama principal y comprobarlos en el entorno de pruebas previsto, conservando las funciones anteriores; los formularios compartidos utilizan los mismos registros.
6. **Documentación:** actualizar la documentación mínima de la función y su evidencia de comprobación, diferenciando resultados ejecutados y supuestos simulados.

**Control del expediente, estimaciones y presupuesto:** cada una de las 105 tareas registra su resultado, dependencias, sprint, profesional y estimaciones. La planificación conserva los 105 identificadores y los totales de esfuerzo; las revisiones de secuencia y recursos quedan justificadas. Las sumas y los bloques deben ser consistentes y el presupuesto, recalculable. Los cambios justificados de estimación o presupuesto conservan el motivo y los valores anteriores y actualizan los cálculos y apartados afectados. Brian y Jeremy realizan la revisión cruzada del expediente.

**Aceptación final del escenario:** S5 exige HTTPS, correo, persistencia, restauración, guía y aceptación, con riesgos, cambios y resultados documentados.

En el curso se documentan los casos y la evidencia esperada de esa ejecución; los resultados supuestos se rotulan **simulados**. El cierre académico exige coherencia y revisión documental, sin entregar una aplicación funcional real.

### Sprints y Sprint Backlogs

El escenario termina en **10 semanas y 5 sprints de 2 semanas**, incluido el cierre. Cada unidad de entrega —una historia sin subdividir o una subdivisión— concentra sus tareas propias en un sprint. Las cuatro historias principales desglosadas pueden abarcar varios sprints. Se mantienen **12 principales, 16 subdivisiones, 24 unidades de entrega y 105 tareas técnicas únicas**.

La secuencia reserva bloques para las **1.482 horas-persona desfavorables**. Las estimaciones **466 / 926 / 1.482 h** favorable/base/desfavorable no se reducen. Los 124 puntos se cuentan una vez al aceptar cada unidad con sus criterios y DoD; no se convierten en horas ni se reparten entre tareas.

**T094 — Comprobaciones de cobros y documentos, T098 — Continuidad y T103 — Guía** tienen dos etapas internas cada una. Siguen siendo tres tareas de las 105; las tablas de sprint contienen **108 actividades o partes**, no 108 identificadores nuevos. Los componentes comunes preparados antes se reutilizan sin duplicar esfuerzo. [Detalle de etapas](#etapas-de-las-tareas-comunes).

Los incrementos se integran y prueban en su sprint con datos ficticios, según la DoD. S5 añade regresión completa, restauración y aceptación conjunta. Todo resultado representado se identifica como **simulado**; el curso entrega el expediente.

#### Sprint 1: base técnica, acceso y datos iniciales

**Semanas simuladas 1–2; revisión de referencia 23/09/2026.**

**Objetivo:** Preparar la aplicación, el acceso, la Landing Page, clientes y catálogos básicos.

**Incremento previsto:** Ingreso de César, clientes y catálogos; Landing pública y registro opcional. Las ubicaciones y las asociaciones se incorporan en S2.

**Sprint Backlog:** 22 tareas o partes; **188 h base y 296 h reservadas** para cubrir el caso desfavorable.

| Historia o trabajo común | Tareas o parte incluida | Base (h) | Desfavorable (h) |
| --- | --- | ---: | ---: |
| H01 — Conocer RYC y contactar desde la Landing Page | T001, T002 | 20 | 30 |
| H02 — Iniciar sesión en la aplicación web | T003, T004 | 14 | 22 |
| H03 — Crear una cuenta de cliente | T005, T006 | 16 | 24 |
| H09.1 — Registrar y mantener clientes particulares y empresas | T043, T044, T045, T046 | 36 | 54 |
| H11 — Administrar los catálogos de plagas y productos | T064, T065, T066, T067 | 24 | 40 |
| Componentes y tareas comunes | T078, T079, T080, T081, T082, T083, T088, T092 | 78 | 126 |

**Comprobación del expediente:** revisar tareas, precedencia, carga por profesional y evidencia esperada del incremento; corregir inconsistencias antes de avanzar.

#### Sprint 2: solicitudes, asociaciones y condiciones

**Semanas simuladas 3–4; revisión de referencia 07/10/2026.**

**Objetivo:** Completar consultorías, propuestas, cuentas autorizadas y condiciones de cobro, con el entorno Railway disponible.

**Incremento previsto:** El cliente solicita consultoría y decide propuestas; César registra contactos y cotiza. Se habilitan sedes, asociaciones, recuperación y Mi cuenta. Aceptar no confirma dinero.

**Sprint Backlog:** 26 tareas o partes; **216 h base y 352 h reservadas** para cubrir el caso desfavorable.

| Historia o trabajo común | Tareas o parte incluida | Base (h) | Desfavorable (h) |
| --- | --- | ---: | ---: |
| H04 — Recuperar el acceso desde Olvidé mi contraseña | T007, T008 | 8 | 12 |
| H05.1 — Solicitar consultorías con correo verificado | T009, T011, T012, T014 | 28 | 44 |
| H05.3 — Consultar solicitudes y decidir propuestas | T013, T015, T016 | 18 | 28 |
| H07.1 — Registrar contactos y valorar consultorías | T028, T029, T031 | 28 | 44 |
| H08 — Consultar y administrar Mi cuenta | T041, T042 | 10 | 16 |
| H09.2 — Administrar ubicaciones y frecuencias de visita | T047, T048, T049 | 20 | 30 |
| H09.3 — Asociar y revocar cuentas con permisos por sede | T050, T051, T052 | 22 | 38 |
| Componentes y tareas comunes | T084, T086, T087, T089, T100, T101 | 82 | 140 |

**Comprobación del expediente:** revisar tareas, precedencia, carga por profesional y evidencia esperada del incremento; corregir inconsistencias antes de avanzar.

#### Sprint 3: agenda, cobros y recibos

**Semanas simuladas 5–6; revisión de referencia 21/10/2026.**

**Objetivo:** Completar agenda, solicitudes de cambio, historial de consulta, comprobación de pagos y recibos.

**Incremento previsto:** César programa y cobra con verificación; el cliente consulta agenda, solicita cambios y consulta el historial publicado disponible. Las consultas se prueban con datos ficticios; los registros nuevos aparecen al publicarse en S4.

**Sprint Backlog:** 28 tareas o partes; **226 h base y 366 h reservadas** para cubrir el caso desfavorable.

| Historia o trabajo común | Tareas o parte incluida | Base (h) | Desfavorable (h) |
| --- | --- | ---: | ---: |
| H05.2 — Solicitar nuevas visitas y cambios de agenda | T017, T018, T019 | 20 | 32 |
| H05.4 — Consultar resumen e historial de atenciones | T010, T020, T021 | 20 | 32 |
| H07.2 — Gestionar consultorías y comprobar el anticipo | T030, T033, T040 | 34 | 58 |
| H10 — Programar visitas y administrar la disponibilidad | T056, T057, T058, T059, T060, T061, T062, T063 | 66 | 102 |
| H12.1 — Confirmar, rechazar y corregir cobros | T068, T069, T070 | 26 | 44 |
| H12.2 — Guardar y versionar recibos de pagos confirmados | T071, T072, T073, T074 | 30 | 50 |
| Componentes y tareas comunes | T085, T090, T093, T094 (Casos de pagos, anticipo y efectivo) | 30 | 48 |

**Comprobación del expediente:** revisar tareas, precedencia, carga por profesional y evidencia esperada del incremento; corregir inconsistencias antes de avanzar.

#### Sprint 4: tratamientos, documentos e integración

**Semanas simuladas 7–8; revisión de referencia 04/11/2026.**

**Objetivo:** Integrar tratamientos, publicación, pagos del cliente, documentos fiscales y entrega.

**Incremento previsto:** César registra y publica lo realmente realizado; el cliente utiliza pagos y descargas. Se incorporan antecedentes, facturas externas y entregas sin exigir cuenta.

**Sprint Backlog:** 24 tareas o partes; **206 h base y 332 h reservadas** para cubrir el caso desfavorable.

| Historia o trabajo común | Tareas o parte incluida | Base (h) | Desfavorable (h) |
| --- | --- | ---: | ---: |
| H06 — Consultar mis pagos y documentos | T022, T023, T024, T025, T026 | 46 | 72 |
| H07.3 — Registrar el tratamiento y las recomendaciones reales | T034, T035, T036, T037 | 32 | 50 |
| H07.4 — Publicar y corregir atenciones desde el panel operativo | T027, T032, T038, T039 | 30 | 50 |
| H09.4 — Incorporar antecedentes y clasificarlos por sede | T053, T054, T055 | 20 | 32 |
| H12.3 — Custodiar facturas electrónicas externas y correcciones | T075, T076 | 28 | 48 |
| H12.4 — Registrar la entrega de documentos y recomendaciones | T077 | 8 | 12 |
| Componentes y tareas comunes | T091, T094 (Casos de documentos y correcciones), T098 (Continuidad sin cuenta y entrega), T099, T103 (Redacción y preparación de guía) | 42 | 68 |

**Comprobación del expediente:** revisar tareas, precedencia, carga por profesional y evidencia esperada del incremento; corregir inconsistencias antes de avanzar.

#### Sprint 5: validación, respaldo y cierre

**Semanas simuladas 9–10; revisión de referencia 18/11/2026.**

**Objetivo:** Comprobar aislamiento y recorridos completos, restaurar respaldos, revisar la guía y cerrar la aceptación simulada.

**Incremento previsto:** Se representa la aceptación conjunta de las 12 historias principales y sus 16 subdivisiones, con archivos privados, recuperación y guía comprobadas.

**Sprint Backlog:** 8 tareas o partes; **90 h base y 136 h reservadas** para cubrir el caso desfavorable.

| Historia o trabajo común | Tareas o parte incluida | Base (h) | Desfavorable (h) |
| --- | --- | ---: | ---: |
| Componentes y tareas comunes | T095, T096, T097, T098 (Asociación posterior y acceso al mismo historial), T102, T103 (Ajuste y revisión final de guía), T104, T105 | 90 | 136 |

**Comprobación del expediente:** revisar tareas, precedencia, carga por profesional y evidencia esperada del incremento; corregir inconsistencias antes de avanzar.

### Backlog técnico de implementación

**77 tareas propias por página y 28 comunes**, definidas y estimadas una vez. Cada historia indica persona, página/reglas y autor documental; las tablas conservan resultado y dependencias. Cliente y César utilizan los mismos registros compartidos.

Las 12 historias principales organizan las funciones por objetivo y página. H05, H07, H09 y H12 se detallan en 16 subdivisiones, cada una con sus tareas y criterios. Los sprints seleccionan tareas de esas entregas; las subdivisiones conservan las páginas previstas. [Agile Alliance: historias de usuario](https://agilealliance.org/glossary/user-stories/).

#### Simbología de las historias y las tareas

| Símbolo      | Significado                                                                                        |
| ------------ | -------------------------------------------------------------------------------------------------- |
| H01–H12      | Historia principal por objetivo/página; H01 Landing y H08 Mi cuenta. H04 reúne dos páginas. |
| H05.1–H05.4, H07.1–H07.4, H09.1–H09.4, H12.1–H12.4 | Las 16 subdivisiones de las cuatro historias principales desglosadas. |
| T001–T105    | Tarea de construcción, preparación o comprobación; rangos incluyen extremos, comas separan tareas. |
| Común        | Compartida y contabilizada una vez.                                                                |
| Dependencias | Tareas que deben terminar antes; — sin prerrequisitos registrados.                                 |
| h            | Horas-persona: 8 h = ocho horas individuales.                                                      |
| S1–S5        | Sprints 1 a 5.                                                                                     |
| O/Base/P     | Esfuerzo favorable/central/desfavorable.                                                           |
| Bloque reservado | Posición dentro de 64 h efectivas/sprint, con duración desfavorable; no son horas del reloj. Un esfuerzo menor libera parte del bloque.                     |

Los ID ordenan el catálogo; prioridad/dependencias ordenan ejecución. T078–T081 preparan la aplicación en Sprint 1 aunque tengan número mayor. Total: **12 historias principales, 16 subdivisiones en 4 de ellas, 13 páginas y 105 tareas**.

**Responsable documental:** Brian, Jeremy o Brian y Jeremy. **Cliente/César:** usuarios. **Ejecutor:** profesional hipotético, identificado en [puestos](#puestos-experiencia-y-dedicación).

#### Dependencias de construcción y reglas de uso

Las dependencias indican qué componentes deben estar disponibles para **construir** una tarea. Las condiciones que el sistema exige al **utilizarla** siguen en Semana 3: cuenta autorizada, correo verificado, cliente y sede correctos, propuesta aceptada, pago previo, tratamiento real y documentos privados.

Formularios y consultas pueden construirse con el modelo y probarse con datos ficticios mientras otro profesional termina la pantalla que guarda esos datos. Esto no permite operar con datos inválidos, publicar sin validaciones ni aceptar una unidad sin integración y DoD. El registro rápido sigue admitiendo contacto sin ficha o lugar completos; las órdenes y los pagos no dependen de que exista una cuenta de portal.

| Trabajo reorganizado | Motivo y control conservado |
| --- | --- |
| Diseño, formularios y catálogos | Usan campos y estilos aprobados. Guardar requiere el modelo; el acceso administrativo se comprueba al operar. |
| Acceso y búsqueda por ID | Utilizan cuentas y UUID ya guardados; no necesitan terminar antes la pantalla de registro o de copiar ID. |
| Órdenes, cobros y recibos | Se construyen contra el modelo común. En ejecución se exige aceptación y dinero confirmado según cada operación; el reporte del cliente es opcional. |
| Formularios de solicitud y permisos | La persistencia y la asociación exigen correo verificado y autorizaciones. Construir el formulario no equivale a habilitar su envío. |
| Agenda, tratamiento, publicación e historial | Comparten modelos y validaciones. Publicar comprueba el trabajo real y el anticipo; las consultas solo muestran servicios publicados autorizados. |
| Railway y comprobaciones | El entorno se prepara en S2; las pruebas acompañan los incrementos y la aceptación final espera todos los casos y la restauración. |

#### H01: Conocer RYC y contactar desde la Landing Page

**Historia:** Persona interesada: conocer RYC y contactar por WhatsApp sin registrarme.

**Página y reglas:** [Landing Page de RYC](#landing-page-de-ryc). **Responsable documental:** Jeremy.

| ID   | Tarea                           | Resultado comprobable                                                          | Dependencias |
| ---- | ------------------------------- | ------------------------------------------------------------------------------ | ------------ |
| T001 | Construir la Landing adaptable. | Contenido aprobado, público y adaptable; WhatsApp principal y portal opcional. | T080 |
| T002 | Preparar mensaje y copia. | Formulario valida sin guardar solicitud; contacto directo y copia manual. | T083 |

**Componentes comunes:** T083 — WhatsApp. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H02: Iniciar sesión en la aplicación web

**Historia:** Cliente y César: ingresar con su cuenta y acceder a sus funciones.

**Página y reglas:** [Inicio de sesión](#inicio-de-sesión). **Responsable documental:** Jeremy.

| ID   | Tarea                    | Resultado comprobable                                                                                          | Dependencias |
| ---- | ------------------------ | -------------------------------------------------------------------------------------------------------------- | ------------ |
| T003 | Construir login. | Correo, contraseña, mostrar/ocultar y enlaces de registro/recuperación. | T082 |
| T004 | Validar acceso y sesión. | Credenciales, errores, límite de fallos, cierre e inactividad según [seguridad](#registro-e-inicio-de-sesión). | T003, T079, T081 |

**Componentes comunes:** T082 — Diseño de acceso. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H03: Crear una cuenta de cliente

**Historia:** Persona interesada: crear cuenta para utilizar el portal opcional.

**Página y reglas:** [Crear cuenta](#crear-cuenta). **Responsable documental:** Jeremy.

| ID   | Tarea                      | Resultado comprobable                                                  | Dependencias |
| ---- | -------------------------- | ---------------------------------------------------------------------- | ------------ |
| T005 | Construir registro. | Cinco campos, etiquetas y reglas del [registro](#campos-del-registro). | T082 |
| T006 | Guardar cuenta de cliente. | Validación, UUID v4 y contraseña protegida con Argon2id. | T005, T079 |

**Componentes comunes:** T082 — Diseño de acceso. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H04: Recuperar el acceso desde Olvidé mi contraseña

**Historia:** Cliente y César: recuperar acceso desde Olvidé mi contraseña.

**Página y reglas:** [Recuperar acceso y Cambiar contraseña](#recuperar-acceso). **Responsable documental:** Jeremy. Dos páginas: solicitar enlace y [guardar contraseña](#cambiar-contraseña-por-recuperación).

| ID   | Tarea                             | Resultado comprobable                                                 | Dependencias |
| ---- | --------------------------------- | --------------------------------------------------------------------- | ------------ |
| T007 | Solicitar enlace de recuperación. | Correo válido, respuesta genérica y envío cuando corresponde. | T006 |
| T008 | Guardar nueva contraseña. | Enlace válido; invalidar enlace/sesiones, confirmar y volver a login. | T007 |

**Componentes comunes:** T082 — Diseño de acceso. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H05: Consultar mi resumen y gestionar mis atenciones

**Historia:** Cliente: consultar resumen y gestionar solicitudes, visitas e historial en un panel.

**Página y reglas:** [Panel del cliente](#panel-del-cliente). **Responsable documental:** Jeremy.

**Subdivisiones:** [H05.1 — Solicitar consultorías con correo verificado](#h051--solicitar-consultorías-con-correo-verificado); [H05.2 — Solicitar nuevas visitas y cambios de agenda](#h052--solicitar-nuevas-visitas-y-cambios-de-agenda); [H05.3 — Consultar solicitudes y decidir propuestas](#h053--consultar-solicitudes-y-decidir-propuestas); [H05.4 — Consultar resumen e historial de atenciones](#h054--consultar-resumen-e-historial-de-atenciones).

| ID   | Tarea                               | Resultado comprobable                                                                      | Dependencias           |
| ---- | ----------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------- |
| T009 | Verificar correo. | Aviso, reenvío y habilitación según [verificación](#verificación-del-correo-en-el-portal). | T006 |
| T010 | Mostrar resumen y pestañas. | Una página con filtros conservados y acceso a pagos. | T009, T041, T089 |
| T011 | Construir solicitud de consultoría. | Formulario territorial integrado; distinguir solicitud de visita. | T088, T092 |
| T012 | Guardar solicitud de consultoría. | Solicitante/lugar autorizados; fecha preferida no reserva. | T009, T011, T089 |
| T013 | Consultar solicitudes propias. | Listado, detalle y propuesta dentro del panel, conservando contexto. | T012, T089 |
| T014 | Incluir referencia en WhatsApp. | Solicitud, consultoría o propuesta existente; abrir no duplica, cliente envía allí. | T012, T083 |
| T015 | Aceptar propuesta. | Decisión única crea orden, sin confirmar dinero; pagos dentro del detalle. | T009, T012, T084, T086 |
| T016 | Rechazar propuesta. | Confirmación cambia pendiente a No aceptada una vez. | T012, T084 |
| T017 | Solicitar nueva visita. | Ubicación activa autorizada; guardar/cancelar conserva contexto. | T048, T051 |
| T018 | Consultar próximas visitas. | Cuenta asociada: fecha/hora/lugar/estado autorizados. | T051, T059 |
| T019 | Solicitar cambio de visita. | Formulario junto a visita; conservar agenda hasta confirmación de César. | T018, T060 |
| T020 | Consultar historial. | Línea de tiempo con publicados del cliente/sedes autorizados. | T079, T089 |
| T021 | Consultar servicio. | Detalle con plagas/productos/tratamiento/recomendaciones dentro del panel. | T020, T079 |

**Componentes comunes:** T083 — WhatsApp; T084 — Propuesta; T085 — Decisión de consultoría; T086 — Orden; T087 — Pagado/pendiente; T088 — Territorio; T089 — Permisos; T090 — Facturación; T091 — Actualización; T092 — Menús. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H06: Consultar mis pagos y documentos

**Historia:** Cliente: buscar pagos, informar dinero entregado y descargar recibos/facturas.

**Página y reglas:** [Pagos y documentos](#pagos-y-documentos). **Responsable documental:** Jeremy.

| ID   | Tarea                                   | Resultado comprobable                                                            | Dependencias           |
| ---- | --------------------------------------- | -------------------------------------------------------------------------------- | ---------------------- |
| T022 | Mostrar y filtrar pagos. | Filtros, detalle y suma por moneda según [Pagos](#pagos-y-reportes-del-cliente). | T024, T068, T070, T087 |
| T023 | Mostrar estado y rechazo. | Estado actualizado, motivo y opción de corregir reporte. | T068 |
| T024 | Informar pago realizado. | [Reporte](#datos-del-reporte-de-pago) con orden fija; Pendiente de revisión. | T087, T089 |
| T025 | Guardar comprobante. | Archivo privado, tipo/tamaño según medio; efectivo sin archivo. | T024 |
| T026 | Consultar y descargar recibos/facturas. | Recibo, PDF, XML y respuesta autorizados; admite orden propia sin asociación. | T079, T089 |

**Componentes comunes:** T086 — Orden; T087 — Pagado/pendiente; T089 — Permisos; T090 — Facturación; T091 — Actualización. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H07: Consultar pendientes y gestionar las atenciones

**Historia:** César: consultar pendientes y gestionar contacto, programación, cobros y servicio desde un panel.

**Página y reglas:** [Panel de administración de César](#panel-de-administración-de-césar). **Responsable documental:** Brian.

**Subdivisiones:** [H07.1 — Registrar contactos y valorar consultorías](#h071--registrar-contactos-y-valorar-consultorías); [H07.2 — Gestionar consultorías y comprobar el anticipo](#h072--gestionar-consultorías-y-comprobar-el-anticipo); [H07.3 — Registrar el tratamiento y las recomendaciones reales](#h073--registrar-el-tratamiento-y-las-recomendaciones-reales); [H07.4 — Publicar y corregir atenciones desde el panel operativo](#h074--publicar-y-corregir-atenciones-desde-el-panel-operativo).

| ID   | Tarea                            | Resultado comprobable                                                                                       | Dependencias                 |
| ---- | -------------------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------- |
| T027 | Mostrar pendientes de César. | Tarjetas, ficha y filtros; listado mediante T029 — Solicitudes. | T029, T059, T068, T075, T077 |
| T028 | Registrar contacto recibido. | Guardar y abrir ficha; cliente/lugar pueden completarse después. | T079, T092 |
| T029 | Listar solicitudes. | Contactos/solicitudes guardados y su ficha; enlace público no genera filas. | T012, T028 |
| T030 | Gestionar consultoría. | Estados, decisiones y cancelación conservan seguimiento y pago previo. | T029, T031, T033, T085 |
| T031 | Calcular consultoría. | [Costo territorial](#consultoría-y-aceptación-del-servicio) revisado; aceptación conserva cálculo/total/instrucciones. | T012, T028 |
| T032 | Registrar decisión externa. | Aceptación/rechazo con fecha y canal. | T084, T086 |
| T033 | Verificar pago previo. | Bloquear inicio/publicación directa sin [pago requerido](#visitas-y-calendario). | T068, T087 |
| T034 | Registrar servicio. | Enlazar cliente/lugar/orden/visita; conservar excepción histórica. | T033, T045, T048, T086 |
| T035 | Registrar plagas/productos. | Cantidad positiva, unidad y prevención según [tratamiento](#registro-del-tratamiento). | T034, T065, T067 |
| T036 | Registrar tratamiento. | Conservar descripción, método real y zona atendida. | T035 |
| T037 | Registrar recomendaciones/notas. | Recomendaciones para cliente; notas internas privadas. | T034 |
| T038 | Publicar atención. | Publicar lo realizado y habilitar cobro del saldo; deuda restante no bloquea. | T033, T034, T079 |
| T039 | Corregir servicio. | Conservar motivo, fecha y seguimiento. | T038 |
| T040 | Reutilizar ficha de atención. | Precargar cliente/lugar/orden y acciones; crear ubicación conserva contexto. | T028, T086 |

**Componentes comunes:** T084 — Propuesta; T085 — Decisión de consultoría; T086 — Orden; T087 — Pagado/pendiente; T088 — Territorio; T089 — Permisos; T090 — Facturación; T091 — Actualización; T092 — Menús; T093 — Tarjetas/tablas. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H08: Consultar y administrar Mi cuenta

**Historia:** Cliente y César: consultar su perfil y actualizar los datos permitidos.

**Página y reglas:** [Mi cuenta](#mi-cuenta). **Responsable documental:** Jeremy.

| ID   | Tarea              | Resultado comprobable                                 | Dependencias |
| ---- | ------------------ | ----------------------------------------------------- | ------------ |
| T041 | Mostrar/copiar ID. | Identificador visible y copia con ID copiado. | T004 |
| T042 | Editar perfil. | Nombre/teléfono validados; correo/ID de solo lectura. | T041 |

**Componentes comunes:** T092 — Menús. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H09: Gestionar clientes, ubicaciones y cuentas autorizadas

**Historia:** César: conservar clientes/lugares y controlar las cuentas autorizadas para su historial.

**Página y reglas:** [Clientes](#clientes). **Responsable documental:** Brian. T050 — Buscar cuenta, T051 — Asociar, T052 — Retirar y T054 — Relacionar históricos: Brian y Jeremy.

**Subdivisiones:** [H09.1 — Registrar y mantener clientes particulares y empresas](#h091--registrar-y-mantener-clientes-particulares-y-empresas); [H09.2 — Administrar ubicaciones y frecuencias de visita](#h092--administrar-ubicaciones-y-frecuencias-de-visita); [H09.3 — Asociar y revocar cuentas con permisos por sede](#h093--asociar-y-revocar-cuentas-con-permisos-por-sede); [H09.4 — Incorporar antecedentes y clasificarlos por sede](#h094--incorporar-antecedentes-y-clasificarlos-por-sede).

| ID   | Tarea                                    | Resultado comprobable                                                          | Dependencias           |
| ---- | ---------------------------------------- | ------------------------------------------------------------------------------ | ---------------------- |
| T043 | Construir formulario particular. | Campos, obligatoriedad y límites de [Cliente particular](#cliente-particular). | T080 |
| T044 | Construir formulario empresa. | Razón social, contacto y demás [campos empresariales](#empresa). | T080 |
| T045 | Guardar/editar cliente. | Particulares/empresas sin exigir cuenta. | T079, T043, T044 |
| T046 | Listar/desactivar clientes. | Conservar datos e historial. | T079, T081, T092 |
| T047 | Construir formulario ubicación. | Datos del lugar y cliente propietario. | T079, T092 |
| T048 | Gestionar ubicaciones. | Identificar lugar por visita y permitir desactivarlo. | T045, T047 |
| T049 | Registrar frecuencia. | Opcional, entero de 1–365 días. | T048 |
| T050 | Buscar cuenta por ID. | Mostrar nombre y correo verificado. | T006, T045, T079 |
| T051 | Asociar cuenta autorizada. | Comprobación registrada y cambios de alcance con seguimiento. | T009, T048, T050, T089 |
| T052 | Retirar asociación. | Conservar cambio y revocar el acceso concedido por la asociación. | T051 |
| T053 | Registrar servicio anterior. | Conservar datos conocidos, origen histórico y desconocidos. | T034 |
| T054 | Relacionar historial/recibos anteriores. | Asociación posterior sin duplicados; sin sede, solo acceso principal/César. | T051, T053, T055, T073 |
| T055 | Clasificar historia por sede. | Solo César/principal hasta asignar sede con seguimiento. | T073, T075, T089 |

**Componentes comunes:** T088 — Territorio; T089 — Permisos; T092 — Menús; T093 — Tarjetas/tablas. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H10: Programar visitas y administrar la disponibilidad

**Historia:** César: organizar visitas y disponibilidad, resolviendo cambios sin conflictos.

**Página y reglas:** [Calendario](#calendario). **Responsable documental:** Brian.

| ID   | Tarea                           | Resultado comprobable                                                                                  | Dependencias           |
| ---- | ------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------- |
| T056 | Revisar/programar nueva visita. | Trabajo nuevo con cobro: propuesta y orden aceptadas para programar; anticipo confirmado para iniciar. | T017, T059, T086 |
| T057 | Resolver cambio solicitado. | Aplicada/No aplicada; agenda cambia solo al confirmar. | T019, T060 |
| T058 | Construir programación. | [Formulario](#programación-y-estado-de-una-visita) reutilizado en atención/Calendario. | T048, T092 |
| T059 | Guardar visita. | Validar fecha/duración y ausencia de solapamiento. | T058 |
| T060 | Reprogramar/cancelar visita. | Conservar programación anterior y motivo. | T059 |
| T061 | Mostrar Calendario. | Mes/Semana/Lista, zona prevista, detalle/acciones y formulario compartido. | T059, T092 |
| T062 | Sugerir próxima visita. | Frecuencia en días; César confirma, sugerencia no reserva. | T049, T079 |
| T063 | Bloquear horario. | Motivo conservado; rechazar solapamiento de visitas nuevas. | T059, T061 |

**Componentes comunes:** T086 — Orden; T087 — Pagado/pendiente; T091 — Actualización; T092 — Menús; T093 — Tarjetas/tablas. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H11: Administrar los catálogos de plagas y productos

**Historia:** César: mantener plagas/productos para seleccionarlos en cada atención.

**Página y reglas:** [Catálogos](#catálogos). **Responsable documental:** Brian.

| ID   | Tarea                           | Resultado comprobable                             | Dependencias |
| ---- | ------------------------------- | ------------------------------------------------- | ------------ |
| T064 | Construir formulario plagas. | Nombre, descripción y estado. | T080 |
| T065 | Guardar/desactivar plaga. | Conservar referencias históricas. | T064, T079 |
| T066 | Construir formulario productos. | Nombre, ingrediente, referencia, nota y estado. | T080 |
| T067 | Guardar/desactivar producto. | Conservar referencias en tratamientos anteriores. | T066, T079 |

**Componentes comunes:** T092 — Menús; T093 — Tarjetas/tablas. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### H12: Verificar cobros y gestionar documentos y entregas

**Historia:** César: comprobar cobros y conservar documentos y entregas.

**Página y reglas:** [Cobros y documentos](#cobros-y-documentos). **Responsable documental:** Brian.

**Subdivisiones:** [H12.1 — Confirmar, rechazar y corregir cobros](#h121--confirmar-rechazar-y-corregir-cobros); [H12.2 — Guardar y versionar recibos de pagos confirmados](#h122--guardar-y-versionar-recibos-de-pagos-confirmados); [H12.3 — Custodiar facturas electrónicas externas y correcciones](#h123--custodiar-facturas-electrónicas-externas-y-correcciones); [H12.4 — Registrar la entrega de documentos y recomendaciones](#h124--registrar-la-entrega-de-documentos-y-recomendaciones).

| ID   | Tarea                                 | Resultado comprobable                                                            | Dependencias     |
| ---- | ------------------------------------- | -------------------------------------------------------------------------------- | ---------------- |
| T068 | Confirmar/rechazar reporte. | Solo dinero verificado reduce saldo; rechazo motivado, sin duplicar referencias. | T086, T087 |
| T069 | Registrar pago externo/efectivo. | Misma orden y comprobantes, sin duplicar reporte del portal. | T068 |
| T070 | Corregir pago/registrar exceso. | Motivo, importes y responsable; exceso sin reembolso automático. | T068 |
| T071 | Construir carga de recibo. | Pago confirmado, cliente/orden precargados, servicio opcional; admite anticipo. | T079, T081, T086 |
| T072 | Guardar archivo del recibo. | Validar tipo/tamaño, nombre generado, archivo privado. | T071 |
| T073 | Relacionar recibo. | Orden/pago/cliente en nuevos; relaciones conocidas en históricos. | T072 |
| T074 | Sustituir recibo conservando versión. | Motivo y archivo anterior; no aplica a factura emitida. | T073 |
| T075 | Adjuntar documento fiscal externo. | XML/PDF/respuesta/metadatos privados; formulario reutilizado en atención. | T072, T086, T090 |
| T076 | Conservar originales/correcciones. | Notas relacionadas y corregido enlazado a rechazado. | T075 |
| T077 | Preparar/registrar entrega. | [Entrega](#entrega-de-documentos-de-la-atención) en orden sin exigir cuenta. | T073, T075 |

**Componentes comunes:** T086 — Orden; T087 — Pagado/pendiente; T089 — Permisos; T090 — Facturación; T091 — Actualización; T092 — Menús; T093 — Tarjetas/tablas. [Uso por persona](#componentes-utilizados-en-las-páginas).

#### Componentes y tareas comunes

T078–T105 cubren preparación, componentes reutilizados, pruebas, alojamiento y cierre. Cada tarea se construye, asigna y estima una vez.

##### Preparación inicial de la aplicación web

**Autores documentales:** Brian y Jeremy; T081 — Cuenta administrativa, Brian. Preparar proyecto/datos/diseño/permisos; César aprueba los [datos iniciales](#tecnologías).

| ID   | Tarea                             | Resultado comprobable                                                                                                                                      | Dependencias |
| ---- | --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| T078 | Preparar proyecto y dependencias. | Versiones/instrucciones, entorno local y datos aprobados según [Alojamiento](#alojamiento-de-la-demostración-y-del-piloto); Railway en T101 — Publicación. | — |
| T079 | Definir modelo y cargar datos. | Cuentas, clientes/sedes, solicitudes, órdenes, servicios, pagos, archivos y entregas relacionados. | T078 |
| T080 | Definir estilos comunes. | Colores, tipografía, controles y espacios según [Diseño](#diseño-y-comportamiento-en-dispositivos). | — |
| T081 | Configurar cuenta de César. | Permiso administrativo fuera del registro público. | T079 |

##### Componentes utilizados en las páginas

**Autores documentales:** Brian y Jeremy. Jeremy: T082 — Acceso, T083 — WhatsApp, T085 — Decisión, T090 — Facturación. Brian: T084 — Propuesta, T087 — Pagado/pendiente, T093 — Listados administrativos.

| Componente                      | Cliente/visitante                            | César                                 |
| ------------------------------- | -------------------------------------------- | ------------------------------------- |
| T082 — Acceso                   | Login, registro, recuperación.               | Login y recuperación.                 |
| T083 — WhatsApp                 | Contacto público o solicitud.                | Recibe; registra con T028 — Contacto. |
| T084 — Propuesta                | Consulta.                                    | Prepara.                              |
| T085 — Consultoría              | Acepta/rechaza costo.                        | Registra decisión externa.            |
| T086 — Orden                    | Consulta condiciones.                        | Administra.                           |
| T087 — Pagado/pendiente         | Consulta importes.                           | Registra/revisa/corrige.              |
| T088 — Territorio               | Indica/selecciona lugar autorizado.          | Comprueba.                            |
| T089 — Permisos                 | Sus registros/archivos.                      | Autoriza/administra.                  |
| T090 — Facturación              | Envía datos.                                 | Completa/revisa.                      |
| T091 — Actualización            | Consulta cambios autorizados.                | Confirma acciones.                    |
| T092 — Menús                    | Portal.                                      | Administración.                       |
| T093 — Listados administrativos | Listados propios en H05 — Panel/H06 — Pagos. | Tarjetas/tablas.                      |

| ID   | Tarea                                      | Resultado comprobable                                                                                                        | Dependencias           |
| ---- | ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| T082 | Construir diseño de acceso. | Login/registro/recuperación con anchos, espacios y desplazamiento previstos. | T080 |
| T083 | Preparar contacto WhatsApp. | Número aprobado/mensaje codificado abren en ambos dispositivos; usuario envía allí. | T001 |
| T084 | Guardar/mostrar propuesta. | César prepara; WhatsApp comparte y portal consulta, sin exigir cuenta. | T045, T079, T086 |
| T085 | Registrar decisión de consultoría. | Portal o César, fecha/canal; aceptar crea orden con T086 — Condiciones aceptadas. | T031, T086 |
| T086 | Conservar orden aceptada. | Cliente/sede, solicitante si existe, total/moneda/condiciones; cuenta opcional. | T079 |
| T087 | Calcular pagado/pendiente. | Consultoría, anticipo y saldo según [condiciones](#consultoría-y-aceptación-del-servicio); solo dinero confirmado descuenta. | T086 |
| T088 | Construir selectores territoriales. | Catálogo y niveles dependientes compartidos entre solicitudes/ubicaciones. | T079, T092 |
| T089 | Aplicar permisos a datos/archivos. | Comprobar correo y alcance en consultas/acciones/descargas según [permisos](#empresas-sedes-y-cuentas). | T006, T079 |
| T090 | Recibir/revisar datos de factura. | Dentro de orden; César revisa sin alterar ficha maestra. | T086, T089 |
| T091 | Actualizar seguimiento relacionado. | Confirmar visita/pago/publicación actualiza una vez todas las vistas y siguiente acción. | T038, T040, T068 |
| T092 | Construir menús adaptables. | Estructura y comportamiento según [Navegación](#navegación) y [Diseño](#diseño-y-comportamiento-en-dispositivos). | T080 |
| T093 | Construir tarjetas/tablas administrativas. | Iguales datos, acciones y permisos en celular/computadora. | T046, T092 |

##### Pruebas de la aplicación web

**Autores documentales:** Brian y Jeremy. Documentar entradas, pasos y resultado esperado de los [casos](#comprobaciones-del-sistema); resultados ficticios rotulados simulados.

| ID   | Tarea                                    | Resultado comprobable                                                                                                                                               | Dependencias                                                   |
| ---- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| T094 | Comprobar cobros/documentos. | Casos de pagos en S3 y de documentos en S4, con resultados esperados y seguimiento; no se duplica esfuerzo. | Casos de pagos, anticipo y efectivo: T033, T069, T070; Casos de documentos y correcciones: T075, T076, T026 |
| T095 | Comprobar aislamiento. | Servicios/visitas/pagos/XML/PDF de dos clientes y sedes; orden propia no abre historial ajeno. | T018, T021, T026, T055 |
| T096 | Comprobar atención completa. | Contacto sin cuenta, consulta gratis/cobrada, decisiones, anticipo, servicio, saldo, entrega e historial opcional. | T015, T026, T032, T038, T056, T094, T098 |
| T097 | Validar uso con César. | César en Administración y equipo en Portal: paneles completos en celular/computadora, pestañas, filtros, guardar/cancelar; dificultades/correcciones registradas. | T010, T014, T022–T023, T027, T042, T077, T091, T093–T094, T099 |
| T098 | Comprobar continuidad sin cuenta/portal. | Recorrido sin cuenta en S4 y asociación posterior en S5; conservar historial único y documentos sin registro. | Continuidad sin cuenta y entrega: T002, T028, T032, T069, T077; Asociación posterior y acceso al mismo historial: T014, T021, T026, T051, T054 |
| T099 | Comprobar interfaz inicialmente. | Sprint 4: acceso, menús, paneles y calendario en celular/computadora, teclado, foco, etiquetas y áreas táctiles. T097 completa la revisión final. | T008, T010, T018, T029, T061, T082, T092 |

##### Entorno de entrega y respaldos

**Autores documentales:** Brian y Jeremy; T101 — Publicación, Brian. Entorno común para toda la aplicación.

| ID   | Tarea                           | Resultado comprobable                                                                                                                                                 | Dependencias                            |
| ---- | ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| T100 | Preparar datos ficticios. | Datos ficticios coherentes con el modelo; completar los recorridos al integrar los módulos, sin datos reales de clientes. | T079 |
| T101 | Publicar/configurar Railway. | Entorno Railway con HTTPS, SMTP y archivos privados desde S2; desplegar y comprobar los incrementos al integrarlos. Persistencia y descargas se validan con datos ficticios. | T078, T079, T100 |
| T102 | Configurar/comprobar respaldos. | Copias, conservación fiscal y restauración consultable según [Respaldo](#respaldo-y-entrega). | T101 |

##### Guía, aceptación y cierre

**Autores documentales:** Brian y Jeremy.

| ID   | Tarea                      | Resultado comprobable                                                                                                           | Dependencias          |
| ---- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| T103 | Preparar guía para César. | Redacción en S4 y revisión final tras recorridos y restauración en S5; guía coherente con el sistema representado. | Redacción y preparación de guía: T061, T101; Ajuste y revisión final de guía: redacción previa de la guía, T096, T097, T102 |
| T104 | Validar entrega con César. | Aceptación simulada de las 12 historias principales, incluidas las 16 subdivisiones de H05, H07, H09 y H12, y las tareas comunes tras T001–T103, según [criterios](#criterios-de-terminación-y-aceptación). | T001–T103 |
| T105 | Documentar cierre. | Aceptación, resultados y lecciones conservados. | T104 |

#### Etapas de las tareas comunes

Estas seis filas detallan T094, T098 y T103. No crean identificadores adicionales ni aumentan sus estimaciones: cada etapa usa sus propias dependencias. Una tarea que necesita T094, T098 o T103 completas espera a sus dos etapas. La revisión final queda antes de T104.

| Tarea y etapa | Profesional | Sprint | O (h) | Base (h) | P (h) | Bloque reservado | Depende de |
| --- | --- | --- | ---: | ---: | ---: | --- | --- |
| T094 — Casos de pagos, anticipo y efectivo | QSM | S3 | 4 | 6 | 10 | 54–64 | T033, T069, T070 |
| T094 — Casos de documentos y correcciones | QSM | S4 | 4 | 8 | 12 | 48–60 | T075, T076, T026 |
| T098 — Continuidad sin cuenta y entrega | QA2 | S4 | 4 | 6 | 10 | 48–58 | T002, T028, T032, T069, T077 |
| T098 — Asociación posterior y acceso al mismo historial | QA2 | S5 | 2 | 6 | 8 | 0–8 | T014, T021, T026, T051, T054 |
| T103 — Redacción y preparación de guía | PO | S4 | 4 | 6 | 10 | 0–10 | T061, T101 |
| T103 — Ajuste y revisión final de guía | PO | S5 | 2 | 4 | 6 | 38–44 | T103 — Redacción, T096, T097, T102 |

### Historias de usuario desarrolladas — Especificación formal según plantilla

#### Introducción y metodología de desarrollo

**Proyecto:** Sistema de Gestión para RYC Control de Plagas
**Curso:** Administración de Proyectos Informáticos (ISW-912)
**Integrantes:** Brian Rodríguez Pérez y Jeremy Rodríguez Esquivel
**Universidad Técnica Nacional — Sede Regional San Carlos**
**Profesora:** Yesenia Calvo Araya

Las historias de usuario describen las funcionalidades y el comportamiento esperado del sistema desde la perspectiva de las personas que interactúan con él: César Rodríguez Corrales como administrador y operador técnico, y los clientes particulares o empresariales que contratan los servicios de control de plagas.

El **Product Backlog** contiene **12 historias principales, H01–H12**, y **16 subdivisiones dentro de H05, H07, H09 y H12**. Las historias sin subdividir y las subdivisiones suman **124 puntos de historia**; las cuatro principales desglosadas muestran únicamente el subtotal de sus partes. Se adopta la estructura establecida en la plantilla oficial de la asignatura (**UserStoryTemplate.docx**), asegurando que cada historia defina con precisión su alcance, valor y condiciones de aceptación:

- **Título e identificador:** H01–H12 para historias principales; H05.1–H05.4, H07.1–H07.4, H09.1–H09.4 y H12.1–H12.4 para sus subdivisiones, vinculadas con el backlog técnico y los Sprint Backlogs.
- **Tareas técnicas relacionadas:** Vínculo con las tareas de implementación (T001–T105) del backlog técnico.
- **Estructura canónica:** Formulación mediante la tríada **Como [rol en el sistema], quiero [capacidad funcional concreta], para [beneficio o valor obtenido]**.
- **Criterios de aceptación verificables:** Definición estructurada mediante **Dado que [contexto o precondición], cuando [evento o acción realizada], entonces [resultado observable]**, cubriendo casos de éxito, validaciones y restricciones operativas.
- **Prioridad:** Clasificación de valor de negocio (Alta o Media).
- **Estimación en puntos:** escala de Fibonacci de 1, 2, 3, 5 y 8 para historias sin subdividir y subdivisiones. Cada principal desglosada muestra la suma de sus cuatro partes, sin añadir una estimación independiente.
- **Justificación de la estimación:** Explicación concisa de los factores determinantes del esfuerzo relativo.
- **Notas adicionales:** Delimitaciones de alcance, reglas de negocio y restricciones operativas.

El catálogo se presenta por familias: H01, H02, H03, H04, H05 con H05.1–H05.4, H06, H07 con H07.1–H07.4, H08, H09 con H09.1–H09.4, H10, H11 y H12 con H12.1–H12.4. Cada subdivisión aplica los criterios de su principal que correspondan a su alcance, además de sus criterios específicos.

#### Historia H01: Conocer RYC y contactar desde la Landing Page

**Tareas técnicas relacionadas:** T001, T002, T083

**Historia de usuario**

Como persona interesada en contratar un servicio de control de plagas,
quiero consultar en la página web pública información sobre la empresa, los servicios que ofrece, las zonas de atención y las condiciones generales, así como preparar un mensaje de contacto directo por WhatsApp,
para conocer si RYC resuelve mi problema de plagas y comunicarme de forma inmediata sin necesidad de registrarme ni crear una cuenta en el sistema.

**Criterios de aceptación**

1. Dado que una persona ingresa a la Landing Page pública, cuando el contenido carga, entonces visualiza la presentación de RYC, el perfil técnico del operador, los servicios disponibles y la cobertura en toda Costa Rica y las condiciones de consultoría: gratuita en el cantón de San Carlos y cotizada con pago previo fuera de él.
2. Dado que la persona desea comunicarse directamente, cuando selecciona la opción rápida de WhatsApp, entonces se abre una conversación dirigida al número telefónico autorizado de RYC.
3. Dado que la persona utiliza el formulario de contacto, cuando completa nombre, teléfono, lugar y descripción del problema, entonces el sistema valida los datos y prepara un mensaje codificado con esa información estructurada.
4. Dado que falta un dato obligatorio en el formulario, cuando la persona intenta continuar, entonces el sistema indica de forma visual cuál campo debe completar.
5. Dado que la persona abre WhatsApp o copia el mensaje, cuando regresa a la página, entonces el sistema no registra automáticamente una solicitud en la base de datos ni reserva citas de atención.
6. Dado que WhatsApp no puede abrirse en el dispositivo, cuando ocurre el fallo de protocolo, entonces la interfaz ofrece el número autorizado y el contenido del texto para copiarlos manualmente al portapapeles.

**Prioridad:** Alta.
**Estimación:** 5 puntos de historia.
**Justificación de la estimación:** Integra diseño web adaptable de acceso público, validación de formularios en el cliente, codificación URI multiplataforma y contingencias de copiado al portapapeles sin persistencia en base de datos.
**Notas adicionales:** La publicación de información comercial requiere aprobación de César; el formulario público no guarda registros huérfanos; los precios y la disponibilidad están sujetos a evaluación técnica; el acceso al portal es opcional.

#### Historia H02: Iniciar sesión en la aplicación web

**Tareas técnicas relacionadas:** T003, T004, T082

**Historia de usuario**

Como usuario registrado del sistema (cliente o César),
quiero iniciar sesión mediante mi correo electrónico y contraseña,
para acceder de forma segura a las funciones y datos que me corresponden según mi rol y permisos autorizados.

**Criterios de aceptación**

1. Dado que el usuario ingresa sus credenciales válidas, cuando el sistema las comprueba, entonces inicia su sesión y lo redirige automáticamente según su rol (César al área administrativa y clientes al portal).
2. Dado que las credenciales son incorrectas, cuando el usuario intenta ingresar, entonces el sistema rechaza el acceso con un mensaje neutro sin revelar cuál dato falló.
3. Dado que se registran múltiples intentos fallidos consecutivos, cuando se alcanza el umbral de seguridad establecido, entonces el sistema restringe temporalmente nuevos intentos.
4. Dado que el usuario permanece inactivo durante sesenta minutos, cuando vence la sesión, entonces el sistema exige autenticarse nuevamente para continuar.
5. Dado que el usuario presiona cerrar sesión, cuando ejecuta la acción, entonces el sistema invalida la sesión activa y redirige a la pantalla de acceso.

**Prioridad:** Alta.
**Estimación:** 5 puntos de historia.
**Justificación de la estimación:** Manejo de sesiones seguras, autenticación mediante huellas de contraseña (hashes) generadas con Argon2id, redirección por roles, mitigación de fuerza bruta y políticas de expiración por inactividad.
**Notas adicionales:** El registro público nunca otorga permisos administrativos; las restricciones deben comprobarse en el servidor y no limitarse a ocultar elementos visuales en el navegador.

#### Historia H03: Crear una cuenta de cliente

**Tareas técnicas relacionadas:** T005, T006, T082

**Historia de usuario**

Como cliente interesado en utilizar las funciones del portal web,
quiero registrar una cuenta personal mediante mis datos básicos de contacto y credenciales,
para ingresar a la plataforma y dar seguimiento digital a mis solicitudes, visitas y documentos autorizados.

**Criterios de aceptación**

1. Dado que una persona ingresa a la opción de crear cuenta, cuando completa nombre, correo electrónico, teléfono opcional, contraseña y confirmación, entonces el sistema registra la cuenta con rol de cliente.
2. Dado que el correo electrónico ya pertenece a una cuenta registrada, cuando se intenta registrarlo nuevamente, entonces el sistema impide el duplicado y muestra una advertencia adecuada.
3. Dado que la contraseña no cumple las condiciones de seguridad o no coincide con su confirmación, cuando se intenta guardar, entonces el sistema solicita corregirla detallando los requisitos pendientes.
4. Dado que el registro se completa exitosamente, cuando se almacena la cuenta, entonces el sistema le asigna un identificador único (ID de cuenta) y muestra el aviso para verificar el correo.

**Prioridad:** Alta.
**Estimación:** 5 puntos de historia.
**Justificación de la estimación:** Validación de datos personales, control de unicidad de correos, hashing de contraseñas con Argon2id y asignación de identificadores únicos para procesos de vinculación.
**Notas adicionales:** Crear una cuenta no genera automáticamente una ficha comercial de cliente ni da acceso a servicios anteriores; la asociación con el historial requiere verificación y autorización de César.

#### Historia H04: Recuperar el acceso desde Olvidé mi contraseña

**Tareas técnicas relacionadas:** T007, T008, T082

**Historia de usuario**

Como usuario registrado del sistema que olvidó su contraseña,
quiero solicitar un enlace seguro de recuperación a mi correo electrónico,
para establecer una nueva contraseña y restablecer el acceso a mi cuenta.

**Criterios de aceptación**

1. Dado que el usuario solicita recuperación de contraseña, cuando ingresa su correo, entonces el sistema muestra una confirmación general sin revelar si la cuenta existe en la base de datos.
2. Dado que el correo corresponde a una cuenta activa, cuando se procesa la solicitud, entonces se envía un enlace de recuperación con un token de un solo uso vigente por treinta minutos.
3. Dado que el usuario accede mediante un enlace válido y vigente, cuando introduce y confirma su nueva contraseña, entonces el sistema actualiza la clave y anula el token utilizado.
4. Dado que el enlace expiró o ya fue utilizado previamente, cuando se intenta usar, entonces el sistema rechaza la operación e invita a solicitar uno nuevo.

**Prioridad:** Media.
**Estimación:** 5 puntos de historia.
**Justificación de la estimación:** Generación y validación de tokens criptográficos de un solo uso con expiración temporal, plantillas de correo transaccional y prevención de enumeración de usuarios.
**Notas adicionales:** Los enlaces tienen vigencia estricta de 30 minutos y quedan inutilizados tras su primer uso exitoso; el cambio de contraseña invalida sesiones anteriores.

#### Historia H05: Consultar mi resumen y gestionar mis atenciones

**Tareas técnicas relacionadas:** T009, T010, T011, T012, T013, T014, T015, T016, T017, T018, T019, T020, T021, T084, T085, T086

**Historia de usuario**

Como cliente registrado,
quiero verificar mi correo, solicitar consultorías y nuevas visitas, evaluar propuestas de trabajo, consultar citas programadas con opción de solicitar cambios y revisar el historial de tratamientos de mis ubicaciones autorizadas,
para coordinar de forma integral la atención de plagas en mis inmuebles y contar con trazabilidad técnica de los servicios recibidos.

**Criterios de aceptación**

1. Dado que el cliente accede mediante el enlace recibido en su correo electrónico, cuando el sistema valida el token de confirmación, entonces marca el correo como verificado y habilita las acciones protegidas del portal.
2. Dado que el cliente tiene su correo verificado, cuando completa el formulario de consultoría (ubicación territorial, problema y teléfono), entonces la solicitud se registra con estado Recibida y genera una referencia única.
3. Dado que la consultoría solicitada corresponde a una ubicación fuera de San Carlos, cuando se revisan las condiciones, entonces el sistema notifica que el servicio queda sujeto a cotización previa y pago confirmado antes de realizar la visita.
4. Dado que el cliente solicita una nueva visita técnica, cuando selecciona una de sus ubicaciones activas autorizadas e ingresa el motivo, entonces el sistema registra la solicitud con estado Recibida conservando la fecha preferida sin bloquear la agenda.
5. Dado que existe una propuesta de trabajo pendiente, cuando el cliente abre su detalle, entonces visualiza descripción, total, moneda, anticipo del 50 % y saldo del 50 %, pudiendo aceptar o rechazar el trabajo de forma definitiva.
6. Dado que el cliente acepta formalmente la propuesta, cuando se procesa la decisión, entonces se genera la orden de trabajo correspondiente sin acreditar dinero automáticamente.
7. Dado que el cliente tiene visitas en estado Programada, cuando solicita reprogramación o cancelación indicando su motivo, entonces se genera una solicitud de cambio para revisión de César sin alterar la cita activa en la agenda.
8. Dado que una cuenta verificada aún no tiene historial asociado, cuando el cliente completa el formulario de consultoría cumpliendo las condiciones del territorio, entonces puede solicitar una consultoría inicial sin necesidad de que César haya asociado previamente registros a esa cuenta.
9. Dado que el cliente consulta su historial, cuando revisa los servicios finalizados y publicados que está autorizado a consultar, entonces puede visualizar fecha, plagas identificadas, tratamiento aplicado, químicos y recomendaciones de sus sedes autorizadas, sin tener acceso a las notas internas privadas de César.

**Prioridad:** Media.
**Estimación total:** 18 puntos, subtotal de H05.1–H05.4. Las subdivisiones se estiman individualmente y se suman una vez.
**Justificación de la estimación:** Agrupación de gran amplitud funcional que integra verificación de correos, lógica territorial de consultorías, validación de permisos por sede (control IDOR), decisiones contractuales con esquemas 50/50, gestión de agenda y consulta de historiales técnicos.
**Notas adicionales:** Las unidades de entrega se completan en S2, S3; solicitar atención no reserva automáticamente citas en el calendario; aceptar una propuesta genera la orden pero el anticipo del 50 % debe confirmarse antes de iniciar el tratamiento; César decide si aprueba las reprogramaciones.

##### H05.1 — Solicitar consultorías con correo verificado

**Puntos:** 5. **Prioridad:** Media. **Entrega prevista:** S2.

**Historia:** Como cliente, quiero verificar mi correo y enviar una consultoría con una referencia única, para solicitar atención sin tener que registrar directamente una cita.

**Tareas asociadas:** T009, T011, T012, T014. **Dependencias clave:** T006, T083, T088, T089, T092.

**Criterios de aceptación:**

1. Dado que el cliente verifica su correo y completa los datos obligatorios, cuando envía una consultoría, entonces esta se guarda como Recibida, con referencia única, sin reservar horario.

2. Dado que la consultoría es fuera de San Carlos, cuando se consulta su detalle o se prepara el mensaje para WhatsApp, entonces se advierte la cotización y el pago previo, sin crear solicitudes duplicadas.

**Justificación de los puntos:** Combina verificación, formulario territorial y continuidad del mismo contacto sin automatizar WhatsApp.

##### H05.2 — Solicitar nuevas visitas y cambios de agenda

**Puntos:** 5. **Prioridad:** Media. **Entrega prevista:** S3.

**Historia:** Como cliente autorizado, quiero solicitar nuevas visitas y pedir cambios sobre las programadas, para coordinar la atención sin modificar la agenda de César por mi cuenta.

**Tareas asociadas:** T017, T018, T019. **Dependencias clave:** T048, T051, T059, T060.

**Criterios de aceptación:**

1. Dado que una cuenta tiene acceso a una ubicación activa, cuando solicita una nueva visita, entonces se registra la petición sin reservar una fecha automáticamente.

2. Dado que existe una visita Programada, cuando el cliente pide cancelarla o reprogramarla, entonces se envía la solicitud de cambio y la visita original continúa hasta que César resuelva.

**Justificación de los puntos:** La autorización por ubicación y la diferencia entre solicitar y modificar la agenda añaden reglas de negocio.

##### H05.3 — Consultar solicitudes y decidir propuestas

**Puntos:** 5. **Prioridad:** Media. **Entrega prevista:** S2.

**Historia:** Como cliente, quiero revisar mis solicitudes y aceptar o rechazar propuestas de trabajo, para conocer y decidir las condiciones antes de contratar.

**Tareas asociadas:** T013, T015, T016. **Dependencias clave:** T009, T012, T084, T086, T089.

**Criterios de aceptación:**

1. Dado que una solicitud pertenece a la cuenta autorizada, cuando el cliente la consulta, entonces ve su estado y la propuesta disponible sin acceder a datos de otros clientes.

2. Dado que existe una propuesta pendiente, cuando la acepta, entonces se crea una única orden con anticipo y saldo, sin confirmar dinero; cuando la rechaza, no se crea orden.

**Justificación de los puntos:** Requiere control del estado de la propuesta y una decisión única enlazada a órdenes y permisos.

##### H05.4 — Consultar resumen e historial de atenciones

**Puntos:** 3. **Prioridad:** Media. **Entrega prevista:** S3.

**Historia:** Como cliente autorizado, quiero ver mi resumen y los servicios publicados de mis ubicaciones, para consultar tratamientos y recomendaciones sin solicitar otra vez la información.

**Tareas asociadas:** T010, T020, T021. **Dependencias clave:** T009, T041, T079, T089.

**Criterios de aceptación:**

1. Dado que el cliente tiene acceso a una sede, cuando abre el historial o un servicio publicado, entonces solo aparecen atenciones autorizadas y no se muestran notas internas.

2. Dado que consulta el panel, cuando cambia entre sus secciones, entonces conserva los filtros y puede acceder al detalle del servicio publicado.

**Justificación de los puntos:** Reutiliza los registros y permisos desarrollados previamente para presentar un resumen y consulta.

#### Historia H06: Consultar mis pagos y documentos

**Tareas técnicas relacionadas:** T022, T023, T024, T025, T026

**Historia de usuario**

Como cliente que contrató servicios de RYC,
quiero consultar el estado financiero de mis órdenes, reportar pagos realizados adjuntando comprobantes y descargar recibos o facturas disponibles,
para conocer mis saldos pendientes, acreditar transferencias y conservar el respaldo documental de mis atenciones.

**Criterios de aceptación**

1. Dado que el cliente consulta la sección de pagos de una orden autorizada, cuando carga la vista, entonces visualiza el monto pactado, el dinero efectivamente confirmado y el saldo pendiente en la única moneda de esa orden, CRC o USD.
2. Dado que el cliente reporta un pago por SINPE Móvil o transferencia bancaria, cuando ingresa el monto, número de referencia y adjunta comprobante (PDF, JPG, PNG hasta 5 MiB), entonces el reporte queda almacenado como Pendiente de revisión.
3. Dado que el cliente envía un reporte de pago, cuando se guarda el registro, entonces el saldo de la orden no se reduce hasta que César confirme que recibió el dinero: ingreso bancario para SINPE o transferencia y recepción física para efectivo.
4. Dado que existen recibos o facturas electrónicas autorizadas para su atención, cuando el cliente selecciona descargar, entonces obtiene los archivos disponibles (PDF, XML de factura y respuesta de Hacienda, cuando exista) mediante descarga autenticada y segura.
5. Dado que un reporte de pago fue rechazado por César, cuando el cliente consulta el detalle, entonces visualiza el motivo justificado y dispone de la opción para ingresar un nuevo reporte corregido.

**Prioridad:** Media.
**Estimación:** 8 puntos de historia.
**Justificación de la estimación:** Manejo de información financiera con monedas segregadas (CRC y USD), carga segura de archivos con validación de tipo MIME y cuotas de tamaño, y descargas controladas mediante endpoints autenticados.
**Notas adicionales:** Reportar un pago no extingue la deuda; solo los pagos confirmados por César descuentan saldo; los documentos fiscales se generan externamente y se consultan a modo de repositorio.

#### Historia H07: Consultar pendientes y gestionar las atenciones

**Tareas técnicas relacionadas:** T027, T028, T029, T030, T031, T032, T033, T034, T035, T036, T037, T038, T039, T040, T084, T085, T086

**Historia de usuario**

Como César, administrador y responsable operativo de RYC,
quiero registrar contactos recibidos, gestionar solicitudes de consultoría según su zona geográfica, preparar propuestas y registrar decisiones, registrar en campo los datos reales de los tratamientos aplicados y publicar los servicios finalizados,
para organizar integralmente el ciclo de atención comercial y técnico de la empresa, asegurando un historial fidedigno y trazable.

**Criterios de aceptación**

1. Dado que César recibe una consulta por llamada o WhatsApp, cuando la registra con datos básicos, entonces crea una ficha de seguimiento con estado Recibida sin exigir ubicación definitiva.
2. Dado que César evalúa una consultoría en San Carlos, cuando la revisa, entonces se determina gratuita sin requerir cobro; si es fuera del cantón, registra la cotización requerida y permite programar la visita con pago pendiente, pero impide iniciar la atención cobrada o publicarla sin el pago previo requerido confirmado.
3. Dado que César prepara una propuesta de tratamiento, cuando ingresa el monto total, entonces el sistema calcula automáticamente el anticipo del 50 % y el saldo del 50 %.
4. Dado que el cliente aprueba la propuesta por canal externo (WhatsApp o llamada), cuando César registra la decisión, fecha y canal, entonces se genera la orden de trabajo correspondiente sin duplicar registros.
5. Dado que César finaliza un servicio en campo, cuando documenta la atención, entonces asocia cliente, ubicación, fecha real, plagas identificadas desde el catálogo (o justifica servicio preventivo), productos químicos con cantidades exactas y unidad de medida.
6. Dado que César ingresa notas de la atención, cuando las guarda, entonces el sistema separa de forma estricta las recomendaciones públicas para el cliente de las observaciones internas privadas de administración.
7. Dado que César intenta publicar un servicio de tratamiento que requería anticipo del 50 % sin que este figure como pago confirmado en la orden, cuando presiona publicar, entonces el sistema bloquea la acción hasta que se verifique el pago previo.
8. Dado que la atención se publica exitosamente, cuando existe una visita en agenda asociada, entonces su estado pasa a Realizada y se habilita la consulta en el portal del cliente.

**Prioridad:** Alta.
**Estimación total:** 20 puntos, subtotal de H07.1–H07.4. Las subdivisiones se estiman individualmente y se suman una vez.
**Justificación de la estimación:** Historia central de la administración operativa que abarca captura comercial de prospectos, validación geográfica de consultorías, cálculo de anticipos 50/50, persistencia de tratamientos químicos en campo, verificación de pagos previos y auditoría de publicaciones.
**Notas adicionales:** Las unidades de entrega se completan en S2, S3, S4; el software no prescribe dosis químicas automáticas, sino que registra lo efectivamente aplicado por César; las notas privadas nunca se exponen al cliente.

##### H07.1 — Registrar contactos y valorar consultorías

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S2.

**Historia:** Como César, quiero registrar contactos recibidos y calcular las condiciones iniciales de una consultoría, para dar seguimiento a personas con o sin cuenta web.

**Tareas asociadas:** T028, T029, T031. **Dependencias clave:** T012, T079, T092.

**Criterios de aceptación:**

1. Dado que César recibe un mensaje o llamada, cuando registra el contacto, entonces crea una ficha Recibida sin exigir aún una ubicación definitiva.

2. Dado que revisa la zona de consultoría, cuando determina el costo, entonces identifica gratuidad dentro de San Carlos o cotización requerida fuera de él.

**Justificación de los puntos:** Abarca contacto multicanal y reglas territoriales sin duplicar el registro inicial.

##### H07.2 — Gestionar consultorías y comprobar el anticipo

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S3.

**Historia:** Como César, quiero actualizar consultorías y verificar el pago requerido antes de iniciar una atención, para cumplir las condiciones aceptadas por el cliente.

**Tareas asociadas:** T030, T033, T040. **Dependencias clave:** T028, T029, T031, T068, T085, T086, T087.

**Criterios de aceptación:**

1. Dado que existe una consultoría, cuando César actualiza su estado o recupera la ficha, entonces se conservan solicitud, cliente y ubicación sin duplicarlos.

2. Dado que el servicio exige pago previo, cuando se intenta iniciar o publicar sin el importe confirmado, entonces el sistema bloquea la operación y muestra lo pendiente.

**Justificación de los puntos:** Integra estados, reglas de anticipo y acceso a la misma ficha de atención.

##### H07.3 — Registrar el tratamiento y las recomendaciones reales

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S4.

**Historia:** Como César, quiero documentar el servicio realizado con plagas, productos, cantidades y recomendaciones, para conservar evidencia técnica fiel de cada tratamiento.

**Tareas asociadas:** T034, T035, T036, T037. **Dependencias clave:** T033, T045, T048, T065, T067, T086.

**Criterios de aceptación:**

1. Dado que registra una atención, cuando selecciona las plagas y productos realmente utilizados, entonces guarda cantidades positivas con unidades válidas o justifica el servicio preventivo.

2. Dado que añade recomendaciones y observaciones, cuando guarda el registro, entonces las notas internas quedan separadas de la información visible al cliente.

**Justificación de los puntos:** Manejo de datos técnicos, validaciones y separación entre recomendaciones y notas privadas.

##### H07.4 — Publicar y corregir atenciones desde el panel operativo

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S4.

**Historia:** Como César, quiero gestionar decisiones externas y publicar o corregir servicios desde mi panel, para mantener visible el estado real de las atenciones.

**Tareas asociadas:** T027, T032, T038, T039. **Dependencias clave:** T029, T033, T034, T059, T068, T075, T077, T079, T084, T086.

**Criterios de aceptación:**

1. Dado que el cliente decide por un canal externo, cuando César registra la decisión, entonces se conserva fecha y canal y no se duplica la orden.

2. Dado que la atención cumple los controles previos y contiene datos del servicio, cuando César la publica, entonces queda disponible para el cliente autorizado; si la corrige, conserva el motivo y el seguimiento.

**Justificación de los puntos:** Integra panel, decisiones, publicación y correcciones con varias dependencias administrativas.

#### Historia H08: Consultar y administrar Mi cuenta

**Tareas técnicas relacionadas:** T041, T042

**Historia de usuario**

Como usuario autenticado del sistema (César o cliente),
quiero consultar mis datos personales, actualizar teléfono o nombre permitido y copiar mi ID de cuenta al portapapeles,
para mantener mis datos de contacto correctos y disponer de mi identificador para los procesos de vinculación autorizada.

**Criterios de aceptación**

1. Dado que el usuario ingresa a Mi cuenta, cuando carga la página, entonces visualiza su nombre completo, correo electrónico, teléfono y su identificador alfanumérico único (ID de cuenta).
2. Dado que el usuario modifica su nombre o número de teléfono con valores válidos, cuando guarda los cambios, entonces el perfil se actualiza en el sistema.
3. Dado que el usuario visualiza su correo electrónico y su ID de cuenta, cuando interactúa con el formulario, entonces ambos campos permanecen bloqueados en modo de solo lectura.
4. Dado que presiona el botón copiar ID, cuando ejecuta la acción, entonces el identificador se copia al portapapeles y se muestra una confirmación visual inmediata.

**Prioridad:** Media.
**Estimación:** 3 puntos de historia.
**Justificación de la estimación:** Operaciones atómicas de consulta y actualización sobre el registro del usuario en sesión, protección de campos inmutables y funcionalidad de portapapeles.
**Notas adicionales:** La interfaz es compartida entre clientes y administración; el ID de cuenta es una clave pública de búsqueda pero no concede acceso por sí solo al historial si César no autoriza la asociación.

#### Historia H09: Gestionar clientes, ubicaciones y cuentas autorizadas

**Tareas técnicas relacionadas:** T043, T044, T045, T046, T047, T048, T049, T050, T051, T052, T053, T054, T055

**Historia de usuario**

Como César, propietario y administrador de RYC Control de Plagas,
quiero registrar y actualizar clientes particulares y empresas con sus diferentes sedes físicas y frecuencias de atención, asociar cuentas del portal con permisos por empresa o sede específica, e incorporar antecedentes de servicios históricos,
para estructurar la base maestra de clientes, controlar quién accede digitalmente a cada inmueble y preservar el historial técnico acumulado de la empresa.

**Criterios de aceptación**

1. Dado que César registra un cliente particular, cuando completa nombre y teléfono obligatorios, entonces se guarda con estado Activo sin exigir correo electrónico ni cuenta web.
2. Dado que registra una empresa, cuando ingresa razón social, nombre de contacto y teléfono, entonces se crea la ficha comercial pudiendo registrar el nombre comercial por separado.
3. Dado que un cliente particular o empresa posee inmuebles, cuando César agrega ubicaciones indicando provincia, cantón, distrito y señas obligatorias, pudiendo registrar una frecuencia sugerida de atención en días como dato opcional, entonces quedan vinculadas unívocamente a su ficha.
4. Dado que César desactiva un cliente o ubicación, cuando confirma la acción, entonces se bloquea su selección para nuevas atenciones pero se conserva íntegro su historial técnico anterior.
5. Dado que un cliente particular o representante de empresa comunica su ID de cuenta, cuando César verifica su identidad por medio confiable, entonces puede asociarlo al cliente particular o a una empresa con acceso a todas las sedes o restringido a una sede física específica.
6. Dado que un usuario con permiso de sede específica inicia sesión en el portal, cuando consulta atenciones o solicita visitas, entonces el sistema restringe su acceso estrictamente a dicha sede autorizada.
7. Dado que César incorpora datos de servicios anteriores al sistema, cuando los registra con la información real disponible, entonces el sistema los rotula como Registro histórico sin inventar datos desconocidos ni facturas ficticias.
8. Dado que César retira una asociación previamente otorgada a un cliente particular o empresa, cuando confirma la desvinculación, entonces el sistema conserva el registro del cambio y revoca de inmediato el acceso que dicha cuenta tenía sobre el cliente o sus sedes.

**Prioridad:** Alta.
**Estimación total:** 21 puntos, subtotal de H09.1–H09.4. Las subdivisiones se estiman individualmente y se suman una vez.
**Justificación de la estimación:** Modela la estructura relacional central del negocio (particulares, empresas, sedes múltiples), control de acceso granular por sede (RBAC/ABAC), auditoría de asociaciones y reglas de flexibilización controlada para migración de datos legacy.
**Notas adicionales:** Las unidades de entrega se completan en S1, S2, S4; una empresa puede tener múltiples sedes independientes; el historial pertenece a la sede y al cliente, no a la cuenta de usuario empleada para consultarlo.

##### H09.1 — Registrar y mantener clientes particulares y empresas

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S1.

**Historia:** Como César, quiero crear, editar y desactivar fichas de clientes particulares y empresas, para mantener sus datos comerciales sin exigirles una cuenta.

**Tareas asociadas:** T043, T044, T045, T046. **Dependencias clave:** T079, T080, T081, T092.

**Criterios de aceptación:**

1. Dado que completa los datos obligatorios del tipo de cliente, cuando guarda la ficha, entonces se registra como Activa aunque no exista correo o usuario web.

2. Dado que desactiva un cliente, cuando confirma la acción, entonces no se utiliza para nuevas atenciones y se preserva su historial.

**Justificación de los puntos:** Diferentes tipos de cliente, validaciones y conservación de registros históricos.

##### H09.2 — Administrar ubicaciones y frecuencias de visita

**Puntos:** 3. **Prioridad:** Alta. **Entrega prevista:** S2.

**Historia:** Como César, quiero registrar las ubicaciones y frecuencias de visita de cada cliente, para programar trabajos en el inmueble correcto.

**Tareas asociadas:** T047, T048, T049. **Dependencias clave:** T045, T079, T092.

**Criterios de aceptación:**

1. Dado que existe un cliente, cuando César crea una ubicación con su territorio y dirección, entonces queda vinculada a esa ficha y no a otra.

2. Dado que registra una frecuencia o desactiva la ubicación, cuando guarda el cambio, entonces la frecuencia solo sugiere una visita y la sede inactiva conserva su historial.

**Justificación de los puntos:** Formulario y mantenimiento acotados que reutilizan cliente y selector territorial.

##### H09.3 — Asociar y revocar cuentas con permisos por sede

**Puntos:** 8. **Prioridad:** Alta. **Entrega prevista:** S2.

**Historia:** Como César, quiero asociar o retirar cuentas del portal verificando identidad y alcance por sede, para proteger el historial privado de cada cliente.

**Tareas asociadas:** T050, T051, T052. **Dependencias clave:** T006, T009, T045, T048, T079, T089.

**Criterios de aceptación:**

1. Dado que recibe un ID de cuenta, cuando comprueba la autorización y asocia una empresa o sede, entonces el usuario solo puede consultar los registros del alcance aprobado.

2. Dado que César retira una asociación, cuando confirma la operación, entonces se revoca ese permiso, se guarda el cambio y no se otorga acceso por conocer únicamente el ID.

**Justificación de los puntos:** Alta incertidumbre y riesgo de seguridad en la autorización por cliente, empresa y sede.

##### H09.4 — Incorporar antecedentes y clasificarlos por sede

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S4.

**Historia:** Como César, quiero ingresar servicios anteriores y relacionarlos con sus ubicaciones cuando se conozcan, para conservar un historial real sin inventar datos.

**Tareas asociadas:** T053, T054, T055. **Dependencias clave:** T034, T051, T073, T075, T089.

**Criterios de aceptación:**

1. Dado que importa una atención anterior, cuando falta su fecha o ubicación, entonces el sistema conserva el dato como desconocido sin fabricar fechas ni documentos.

2. Dado que un servicio o documento antiguo identifica a la empresa pero no la sede atendida, cuando se consulta, entonces solo César y la cuenta principal de esa empresa pueden verlo. Las cuentas de sede no lo ven hasta que César lo clasifique; después, solo lo consulta la cuenta de la sede correspondiente, además de César y la cuenta principal.

**Justificación de los puntos:** Información incompleta, vínculos con recibos y control de exposición por sede.

#### Historia H10: Programar visitas y administrar la disponibilidad

**Tareas técnicas relacionadas:** T056, T057, T058, T059, T060, T061, T062, T063

**Historia de usuario**

Como César, encargado de realizar las visitas en campo,
quiero agendar citas para mis clientes, reprogramar y cancelar visitas justificadas, reservar bloqueos de tiempo no laboral y consultar mi calendario en vistas de mes, semana y lista,
para organizar eficientemente mis jornadas de trabajo, evitar colisiones de horario y planificar traslados entre cantones.

**Criterios de aceptación**

1. Dado que César programa una visita para un cliente y ubicación activos, cuando define tipo, fecha, hora y duración (de 15 a 480 minutos), entonces se registra con estado Programada siempre que no colisione con otra cita o bloqueo de agenda activo.
2. Dado que una visita o bloqueo coincide total o parcialmente con el intervalo propuesto, cuando se intenta agendar o reprogramar, entonces el sistema detecta la superposición temporal y rechaza la inserción.
3. Dado que César necesita apartar tiempo para traslados intercantonales o asuntos personales, cuando registra un bloqueo de disponibilidad con su motivo, entonces ese periodo queda reservado como no disponible.
4. Dado que una visita requiere cambio de fecha u hora (por decisión de César o atendiendo una solicitud del cliente), cuando César confirma la reprogramación válida con su motivo, entonces el sistema actualiza la agenda y conserva el registro del horario previo.
5. Dado que una visita debe anularse definitivamente, cuando César ingresa el motivo de cancelación, entonces el estado pasa a Cancelada y se libera el espacio en el calendario.
6. Dado que un servicio finalizado en una ubicación tiene configurada una frecuencia preventiva en días, cuando se publica, entonces el sistema genera una sugerencia de próxima visita que requiere confirmación explícita de César antes de agendarse.
7. Dado que César accede a la interfaz del calendario de trabajo, cuando alterna entre las vistas de Mes, Semana y Lista, entonces el sistema presenta las visitas programadas y bloqueos temporales correspondientes al intervalo seleccionado sin perder el contexto operativo.

**Prioridad:** Alta.
**Estimación:** 8 puntos de historia.
**Justificación de la estimación:** Algoritmo de detección de solapamientos temporales en huso horario de Costa Rica (America/Costa_Rica), control de colisiones con bloqueos personales, vistas interactivas de agenda y sugerencias automáticas de seguimiento.
**Notas adicionales:** Las unidades de entrega se completan en S3; los únicos estados válidos son Programada, En curso, Realizada y Cancelada; reprogramar es una acción de modificación sobre una visita programada y no un estado nuevo.

#### Historia H11: Administrar los catálogos de plagas y productos

**Tareas técnicas relacionadas:** T064, T065, T066, T067

**Historia de usuario**

Como César, responsable técnico de los tratamientos,
quiero gestionar los catálogos de plagas atendidas y productos plaguicidas utilizados en los tratamientos,
para estandarizar la captura técnica de datos y seleccionar con exactitud las plagas detectadas y químicos aplicados en cada servicio.

**Criterios de aceptación**

1. Dado que César registra una plaga, cuando ingresa su nombre común o científico obligatorio y notas complementarias, entonces se añade al catálogo activo.
2. Dado que César registra un producto, cuando ingresa su nombre comercial obligatorio, pudiendo registrar el ingrediente activo, referencia y notas de manipulación como campos opcionales, entonces queda registrado en el catálogo de productos sin incorporar control de inventarios ni prescripción de dosis.
3. Dado que una plaga o químico deja de utilizarse, cuando César lo desactiva en el catálogo, entonces desaparece de las opciones seleccionables en nuevos servicios.
4. Dado que un elemento desactivado fue utilizado en atenciones anteriores, cuando se consultan servicios históricos, entonces el registro técnico conserva intactos el nombre y los datos originales del tratamiento.

**Prioridad:** Alta.
**Estimación:** 5 puntos de historia.
**Justificación de la estimación:** Mantenimiento de catálogos maestros con validación de nombres, bajas lógicas y aseguramiento de integridad referencial sobre tratamientos pasados.
**Notas adicionales:** Las unidades de entrega se completan en S1; el catálogo es estrictamente descriptivo e identificatorio; no prescribe dosis automáticas; todo químico utilizado históricamente permanece visible en los expedientes archivados.

#### Historia H12: Verificar cobros y gestionar documentos y entregas

**Tareas técnicas relacionadas:** T068, T069, T070, T071, T072, T073, T074, T075, T076, T077

**Historia de usuario**

Como César, responsable de la administración de cobros de RYC,
quiero verificar los reportes de pago informados para confirmarlos o rechazarlos, asentar cobros directos en efectivo, adjuntar recibos, custodiar facturas electrónicas externas (XML y PDF) y registrar formalmente la entrega de documentos al cliente,
para asegurar que solo el dinero comprobado reduzca la deuda de las órdenes, mantener organizados los expedientes tributarios y conservar evidencia de las entregas realizadas.

**Criterios de aceptación**

1. Dado que existe un reporte de SINPE o transferencia con comprobante adjunto, cuando César comprueba el ingreso real en la cuenta bancaria de RYC y confirma el movimiento, entonces el estado pasa a Confirmado y se descuenta el importe del saldo de la orden.
2. Dado que un reporte de SINPE o transferencia no coincide con los movimientos bancarios o su comprobante es ilegible, cuando César lo rechaza con un motivo, entonces el saldo permanece intacto y se conserva el registro del rechazo.
3. Dado que César recibe un cobro en efectivo en campo, cuando comprueba que recibió físicamente el dinero y lo registra en la orden, entonces el pago queda Confirmado y reduce el saldo, sin exigir referencia ni comprobante bancario o cuenta en el portal.
4. Dado que se intenta confirmar un reporte cuya referencia bancaria ya fue utilizada previamente en otro pago, cuando el sistema evalúa la duplicidad, entonces bloquea la operación para evitar doble contabilización.
5. Dado que un pago está confirmado, cuando César adjunta un recibo digital (PDF, JPG, PNG hasta 5 MiB), entonces se almacena en directorio privado y queda disponible para descarga del cliente.
6. Dado que César emitió una factura en su sistema externo, cuando la adjunta a la orden correspondiente, entonces sube obligatoriamente el XML de factura y la representación gráfica en PDF; la respuesta de Hacienda se adjunta cuando esté disponible.
7. Dado que se registra una factura electrónica en una orden, cuando se actualiza la vista financiera, entonces el documento fiscal no altera por sí mismo el saldo pendiente de cobro.
8. Dado que César entrega recibos, facturas o recomendaciones al cliente por WhatsApp, correo o presencialmente, cuando registra la fecha, destinatario y canal, entonces queda asentada la evidencia formal de entrega.

**Prioridad:** Alta.
**Estimación total:** 21 puntos, subtotal de H12.1–H12.4. Las subdivisiones se estiman individualmente y se suman una vez.
**Justificación de la estimación:** Agrupación compleja de cierre administrativo que integra control transaccional de cobros bancarios, prevención de duplicados, gestión de almacenamiento binario para recibos, validación de formatos tributarios XML/PDF y auditoría de entregas.
**Notas adicionales:** Las unidades de entrega se completan en S3, S4; solo los pagos confirmados modifican saldos; el sistema no realiza conciliación bancaria automática; las facturas se emiten externamente y se custodian en el sistema; descargar un archivo no acredita entrega sin confirmación explícita de César.

##### H12.1 — Confirmar, rechazar y corregir cobros

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S3.

**Historia:** Como César, quiero revisar reportes de pago y registrar cobros recibidos directamente, para actualizar los saldos solo con dinero comprobado.

**Tareas asociadas:** T068, T069, T070. **Dependencias clave:** T086, T087.

**Criterios de aceptación:**

1. Dado que se reporta un pago, cuando César lo confirma tras verificarlo, entonces reduce la deuda una sola vez y bloquea referencias duplicadas.

2. Dado que registra efectivo, rechaza un reporte o corrige un movimiento, cuando guarda la operación, entonces conserva responsable y motivo sin acreditar pagos pendientes.

**Justificación de los puntos:** Control transaccional, prevención de duplicaciones y trazabilidad del dinero confirmado.

##### H12.2 — Guardar y versionar recibos de pagos confirmados

**Puntos:** 5. **Prioridad:** Alta. **Entrega prevista:** S3.

**Historia:** Como César, quiero adjuntar recibos y conservar sus versiones vinculadas al pago, para entregar constancias verificables de los cobros.

**Tareas asociadas:** T071, T072, T073, T074. **Dependencias clave:** T079, T081, T086.

**Criterios de aceptación:**

1. Dado que un pago está confirmado, cuando César carga un recibo válido, entonces se guarda en privado y queda relacionado con la orden y el cliente.

2. Dado que sustituye el archivo de un recibo, cuando registra el motivo, entonces el archivo anterior se conserva como versión y no se modifica una factura fiscal.

**Justificación de los puntos:** Archivos privados, integridad de asociaciones y conservación de versiones.

##### H12.3 — Custodiar facturas electrónicas externas y correcciones

**Puntos:** 8. **Prioridad:** Alta. **Entrega prevista:** S4.

**Historia:** Como César, quiero adjuntar facturas externas, respuestas y documentos correctivos a cada orden, para conservar los originales tributarios de forma segura.

**Tareas asociadas:** T075, T076. **Dependencias clave:** T072, T086, T090.

**Criterios de aceptación:**

1. Dado que se incorpora una factura externa, cuando César adjunta XML y PDF válidos, entonces el documento queda vinculado a la orden correcta y no altera por sí mismo el saldo.

2. Dado que existe una respuesta o nota correctiva, cuando se adjunta, entonces conserva el original, relaciona la corrección y evita mezclar órdenes de distintos clientes.

**Justificación de los puntos:** Validación documental XML/PDF, protección de archivos y correcciones tributarias.

##### H12.4 — Registrar la entrega de documentos y recomendaciones

**Puntos:** 3. **Prioridad:** Alta. **Entrega prevista:** S4.

**Historia:** Como César, quiero registrar a quién, cuándo y por qué canal entregué documentos o recomendaciones, para conservar seguimiento de la atención al cliente.

**Tareas asociadas:** T077. **Dependencias clave:** T073, T075.

**Criterios de aceptación:**

1. Dado que una orden tiene documentos o recomendaciones disponibles, cuando César confirma una entrega real, entonces guarda destinatario, fecha, canal y elementos entregados.

2. Dado que solo abre o descarga un documento, cuando no confirma la entrega, entonces no se registra una entrega ficticia.

**Justificación de los puntos:** Acción de registro acotada que reutiliza los archivos y el seguimiento de órdenes.

#### Resumen de estimaciones y prioridades del Product Backlog

El catálogo reúne 12 historias principales y 16 subdivisiones dentro de cuatro de ellas. Los subtotales siguientes incluyen sus partes; el total de 124 puntos de historia se contabiliza una sola vez. Las tareas técnicas mantienen sus asignaciones en los cinco sprints:

| Código | Título de la historia de usuario | Prioridad | Estimación (pts) | Tareas técnicas asociadas | Entregas previstas |
|:---:|:---|:---:|:---:|:---|:---:|
| **H01** | Conocer RYC y contactar desde la Landing Page | Alta | 5 | T001, T002, T083 | S1 |
| **H02** | Iniciar sesión en la aplicación web | Alta | 5 | T003, T004, T082 | S1 |
| **H03** | Crear una cuenta de cliente | Alta | 5 | T005, T006, T082 | S1 |
| **H04** | Recuperar el acceso desde Olvidé mi contraseña | Media | 5 | T007, T008, T082 | S2 |
| **H05** | Consultar mi resumen y gestionar mis atenciones | Media | 18 (subtotal) | T009–T021, T084–T086 | S2, S3 |
| **H06** | Consultar mis pagos y documentos | Media | 8 | T022–T026 | S4 |
| **H07** | Consultar pendientes y gestionar las atenciones | Alta | 20 (subtotal) | T027–T040, T084–T086 | S2, S3, S4 |
| **H08** | Consultar y administrar Mi cuenta | Media | 3 | T041, T042 | S2 |
| **H09** | Gestionar clientes, ubicaciones y cuentas autorizadas | Alta | 21 (subtotal) | T043–T055 | S1, S2, S4 |
| **H10** | Programar visitas y administrar la disponibilidad | Alta | 8 | T056–T063 | S3 |
| **H11** | Administrar los catálogos de plagas y productos | Alta | 5 | T064–T067 | S1 |
| **H12** | Verificar cobros y gestionar documentos y entregas | Alta | 21 (subtotal) | T068–T077 | S3, S4 |
| **Total** | **12 historias principales; 16 subdivisiones en 4 de ellas** | **8 principales Alta / 4 principales Media** | **124 pts** | **105 tareas técnicas (T001–T105)** | **5 Sprints** |

---

#### Consideraciones sobre la Definition of Done y entrega progresiva

Las 12 historias principales y sus 16 subdivisiones describen el comportamiento esperado. Una principal desglosada se acepta al validar todas sus partes; las historias sin subdividir se comprueban completas. Para que una historia se considere terminada dentro del marco del proyecto, debe cumplir sus criterios de aceptación y la [Definición de Terminado (DoD)](#criterios-de-terminación-y-aceptación), que reúne los criterios comunes de calidad y la evidencia requerida para la simulación.

**Reglas de negocio:** la aceptación conserva la gratuidad de consultoría en San Carlos y el cobro previo fuera del cantón; el anticipo del 50 % antes del tratamiento; la comprobación del dinero recibido según el medio de pago; las notas internas privadas de César y una sola moneda por orden, con CRC y USD separados en los resúmenes.

**Estimaciones y presupuesto:** las horas y los costos se controlan en [Estimación y asignación de las tareas](#estimación-y-asignación-de-las-tareas) y [Presupuesto del proyecto simulado](#presupuesto-del-proyecto-simulado). Sus revisiones justificadas se registran y recalculan según el control del expediente. La DoD evalúa la calidad del trabajo y sus comprobaciones.

**Nota metodológica sobre INVEST y entrega progresiva:** las 24 unidades de entrega —ocho historias sin subdividir y dieciséis subdivisiones— concentran sus tareas propias dentro de un sprint y se aceptan con sus criterios y la DoD. H05, H07, H09 y H12 conservan el alcance de sus cuatro partes y pueden abarcar varios sprints. Los componentes comunes previos se reutilizan; T094, T098 y T103 se completan por etapas según su tabla. [Guía de Scrum: elementos preparados para un sprint](https://scrumguides.org/scrum-guide.html#product-backlog).

---

#### Conclusión

Las 12 historias principales y las 16 subdivisiones de H05, H07, H09 y H12 se relacionan con las 105 tareas técnicas, la estimación de 124 puntos de historia y los cinco sprints del escenario.

---

## Semana 6 · Estimación y planificación de entregas

> **Fecha lectiva de referencia:** miércoles 21 de octubre de 2026, correspondiente a la Semana 6.
>
> **Objetivo:** Presentar la estimación vigente de 124 puntos de historia, su relación con las 105 tareas, la capacidad profesional, el presupuesto y las entregas del escenario de cinco sprints.

### Matriz de estimación en puntos de historia

El proyecto contiene **12 historias principales**. **H05, H07, H09 y H12 se desglosan en cuatro subdivisiones cada una: 16 en total**. La estimación vigente es de **124 puntos de historia**, calculados sobre las ocho historias sin subdividir y las dieciséis subdivisiones.

#### Formalización de los puntos de historia

**Línea base vigente del expediente: 124 puntos de historia.** Se adopta esta estimación documentada para planificar la simulación de diez semanas y cinco sprints. Su uso en el expediente no queda condicionado a una validación posterior.

**Método:** estimación relativa según alcance, complejidad e incertidumbre, con **H08 — Mi cuenta (3 puntos)** como referencia y la escala de Fibonacci de **1, 2, 3, 5 y 8**. Las justificaciones de las historias y subdivisiones sustentan los valores de la matriz.

**Cómputo:** las ocho historias sin subdividir suman **44 puntos** y las dieciséis subdivisiones, **80**: **44 + 80 = 124**. H05, H07, H09 y H12 muestran subtotales de sus partes, sin puntos independientes ni doble contabilización.

**Naturaleza y control:** es una estimación académica formalizada, no un resultado de programación ejecutada ni de una sesión real de Planning Poker. Los puntos no se convierten directamente en horas-persona. Cualquier revisión posterior exige una decisión explícita, su justificación y la actualización de la matriz, los subtotales, las historias y las entregas afectadas; las horas, capacidad y costos se revisan si el cambio también afecta el trabajo técnico.

| Historia o subdivisión | Funcionalidad | Puntos | Prioridad | Tareas técnicas | Dependencias de referencia | Entrega prevista |
| --- | --- | ---: | --- | --- | --- | --- |
| H01 | Contacto público y WhatsApp | 5 | Alta | T001, T002 | T080, T083 | S1 |
| H02 | Iniciar sesión | 5 | Alta | T003, T004 | T079, T081, T082 | S1 |
| H03 | Crear cuenta | 5 | Alta | T005, T006 | T079, T082 | S1 |
| H04 | Recuperar acceso | 5 | Media | T007, T008 | T006 | S2 |
| **H05** | **Consultar mi resumen y gestionar mis atenciones — historia principal** | **18 (subtotal)** | Media | Se detalla en H05.1–H05.4 | Ver subdivisiones | Ver subdivisiones |
| H05.1 | Solicitar consultorías con correo verificado | 5 | Media | T009, T011, T012, T014 | T006, T083, T088, T089, T092 | S2 |
| H05.2 | Solicitar nuevas visitas y cambios de agenda | 5 | Media | T017, T018, T019 | T048, T051, T059, T060 | S3 |
| H05.3 | Consultar solicitudes y decidir propuestas | 5 | Media | T013, T015, T016 | T009, T012, T084, T086, T089 | S2 |
| H05.4 | Consultar resumen e historial de atenciones | 3 | Media | T010, T020, T021 | T009, T041, T079, T089 | S3 |
| H06 | Pagos y documentos del cliente | 8 | Media | T022, T023, T024, T025, T026 | T068, T070, T079, T087, T089 | S4 |
| **H07** | **Consultar pendientes y gestionar las atenciones — historia principal** | **20 (subtotal)** | Alta | Se detalla en H07.1–H07.4 | Ver subdivisiones | Ver subdivisiones |
| H07.1 | Registrar contactos y valorar consultorías | 5 | Alta | T028, T029, T031 | T012, T079, T092 | S2 |
| H07.2 | Gestionar consultorías y comprobar el anticipo | 5 | Alta | T030, T033, T040 | T028, T029, T031, T068, T085, T086, T087 | S3 |
| H07.3 | Registrar el tratamiento y las recomendaciones reales | 5 | Alta | T034, T035, T036, T037 | T033, T045, T048, T065, T067, T086 | S4 |
| H07.4 | Publicar y corregir atenciones desde el panel operativo | 5 | Alta | T027, T032, T038, T039 | T029, T033, T034, T059, T068, T075, T077, T079, T084, T086 | S4 |
| H08 | Mi cuenta (referencia) | 3 | Media | T041, T042 | T004 | S2 |
| **H09** | **Gestionar clientes, ubicaciones y cuentas autorizadas — historia principal** | **21 (subtotal)** | Alta | Se detalla en H09.1–H09.4 | Ver subdivisiones | Ver subdivisiones |
| H09.1 | Registrar y mantener clientes particulares y empresas | 5 | Alta | T043, T044, T045, T046 | T079, T080, T081, T092 | S1 |
| H09.2 | Administrar ubicaciones y frecuencias de visita | 3 | Alta | T047, T048, T049 | T045, T079, T092 | S2 |
| H09.3 | Asociar y revocar cuentas con permisos por sede | 8 | Alta | T050, T051, T052 | T006, T009, T045, T048, T079, T089 | S2 |
| H09.4 | Incorporar antecedentes y clasificarlos por sede | 5 | Alta | T053, T054, T055 | T034, T051, T073, T075, T089 | S4 |
| H10 | Programación y calendario | 8 | Alta | T056, T057, T058, T059, T060, T061, T062, T063 | T017, T019, T048, T049, T079, T086, T092 | S3 |
| H11 | Catálogos de plagas y productos | 5 | Alta | T064, T065, T066, T067 | T079, T080 | S1 |
| **H12** | **Verificar cobros y gestionar documentos y entregas — historia principal** | **21 (subtotal)** | Alta | Se detalla en H12.1–H12.4 | Ver subdivisiones | Ver subdivisiones |
| H12.1 | Confirmar, rechazar y corregir cobros | 5 | Alta | T068, T069, T070 | T086, T087 | S3 |
| H12.2 | Guardar y versionar recibos de pagos confirmados | 5 | Alta | T071, T072, T073, T074 | T079, T081, T086 | S3 |
| H12.3 | Custodiar facturas electrónicas externas y correcciones | 8 | Alta | T075, T076 | T072, T086, T090 | S4 |
| H12.4 | Registrar la entrega de documentos y recomendaciones | 3 | Alta | T077 | T073, T075 | S4 |
| **Total** | **12 historias principales; 16 subdivisiones dentro de 4 de ellas** | **124** | — | **105 tareas propias y comunes** | — | **5 sprints** |

**Lectura de la matriz:** las filas principales H05, H07, H09 y H12 muestran subtotales de sus partes. Para obtener 124 se suman las ocho historias sin subdividir y las dieciséis subdivisiones; los subtotales no se añaden otra vez. Cada unidad concentra sus tareas propias en el sprint indicado y exige criterios de aceptación y DoD. Las principales desglosadas se completan al aceptar sus cuatro partes. Las tareas comunes se utilizan como dependencias y se construyen y estiman una vez. Las dependencias completas figuran en el [backlog técnico de Semana 5](#backlog-técnico-de-implementación); horas y ejecutores, en [Estimación y asignación de las tareas](#estimación-y-asignación-de-las-tareas).

### Desglose de puntos de las historias subdivididas

| Historia principal | Subdivisiones | Puntos de sus partes |
| --- | --- | ---: |
| H05 — Consultar mi resumen y gestionar mis atenciones | H05.1, H05.2, H05.3, H05.4 | 18 |
| H07 — Consultar pendientes y gestionar las atenciones | H07.1, H07.2, H07.3, H07.4 | 20 |
| H09 — Gestionar clientes, ubicaciones y cuentas autorizadas | H09.1, H09.2, H09.3, H09.4 | 21 |
| H12 — Verificar cobros y gestionar documentos y entregas | H12.1, H12.2, H12.3, H12.4 | 21 |
| **Total de las cuatro principales desglosadas** | **16 subdivisiones** | **80** |

Las ocho historias sin subdividir suman **44 puntos** y las dieciséis subdivisiones suman **80 puntos**: **124 puntos de historia en total**. Estos valores integran la línea base académica vigente; no se asignan puntos independientes a las cuatro principales que agrupan las subdivisiones.

### Estimación y asignación de las tareas

**Horas-persona:** O = favorable, Base = esfuerzo previsto y P = desfavorable. Las cifras conservan implementación, validaciones, pruebas, revisión y documentación. Coordinación y ceremonias usan la reserva de disponibilidad; los autores académicos no son los profesionales contratados del escenario.

- **O:** Base × 0,65, redondeada hacia abajo a pares, mínimo 2 h.
- **P:** Base × 1,5; × 1,8 en las tareas de mayor riesgo, redondeada hacia arriba a pares. T101, T102 y las etapas de T094/T098/T103 conservan la suma de sus actividades.
- **Bloque reservado:** posición dentro de 64 h efectivas por sprint, dimensionada con P. Se conserva el inicio y se usa la duración O/Base/P correspondiente; un esfuerzo menor libera parte del bloque. No son horas del reloj.
- **Asignación:** los códigos identifican personas. D4 combina desarrollo y DevOps con una sola bolsa y sin tareas simultáneas. Las etapas comunes indican profesional y bloque en su tabla; se contabilizan una vez.

| ID | Historia o común | Sprint | Profesional | O (h) | Base (h) | P (h) | Bloque reservado |
| --- | --- | --- | --- | ---: | ---: | ---: | --- |
| T001 | H01 | S1 | D5 | 6 | 12 | 18 | S1: 18–36 |
| T002 | H01 | S1 | D4 | 4 | 8 | 12 | S1: 52–64 |
| T003 | H02 | S1 | D2 | 2 | 6 | 10 | S1: 40–50 |
| T004 | H02 | S1 | D3 | 4 | 8 | 12 | S1: 52–64 |
| T005 | H03 | S1 | D3 | 4 | 8 | 12 | S1: 30–42 |
| T006 | H03 | S1 | D2 | 4 | 8 | 12 | S1: 52–64 |
| T007 | H04 | S2 | D1 | 2 | 4 | 6 | S2: 30–36 |
| T008 | H04 | S2 | D2 | 2 | 4 | 6 | S2: 52–58 |
| T009 | H05.1 | S2 | D5 | 2 | 6 | 10 | S2: 16–26 |
| T010 | H05.4 | S3 | D1 | 2 | 6 | 10 | S3: 54–64 |
| T011 | H05.1 | S2 | D2 | 6 | 10 | 16 | S2: 10–26 |
| T012 | H05.1 | S2 | D5 | 4 | 8 | 12 | S2: 30–42 |
| T013 | H05.3 | S2 | D3 | 2 | 6 | 10 | S2: 42–52 |
| T014 | H05.1 | S2 | D1 | 2 | 4 | 6 | S2: 58–64 |
| T015 | H05.3 | S2 | D5 | 4 | 8 | 12 | S2: 42–54 |
| T016 | H05.3 | S2 | D5 | 2 | 4 | 6 | S2: 54–60 |
| T017 | H05.2 | S3 | D4 | 4 | 8 | 12 | S3: 6–18 |
| T018 | H05.2 | S3 | D3 | 2 | 6 | 10 | S3: 32–42 |
| T019 | H05.2 | S3 | D3 | 2 | 6 | 10 | S3: 42–52 |
| T020 | H05.4 | S3 | D3 | 4 | 8 | 12 | S3: 0–12 |
| T021 | H05.4 | S3 | D4 | 2 | 6 | 10 | S3: 42–52 |
| T022 | H06 | S4 | D2 | 6 | 10 | 16 | S4: 48–64 |
| T023 | H06 | S4 | D1 | 2 | 6 | 10 | S4: 54–64 |
| T024 | H06 | S4 | D3 | 6 | 10 | 16 | S4: 0–16 |
| T025 | H06 | S4 | D3 | 4 | 8 | 12 | S4: 16–28 |
| T026 | H06 | S4 | D1 | 6 | 12 | 18 | S4: 10–28 |
| T027 | H07.4 | S4 | D5 | 4 | 8 | 12 | S4: 48–60 |
| T028 | H07.1 | S2 | LT | 6 | 10 | 16 | S2: 26–42 |
| T029 | H07.1 | S2 | D3 | 4 | 8 | 12 | S2: 52–64 |
| T030 | H07.2 | S3 | LT | 6 | 12 | 22 | S3: 42–64 |
| T031 | H07.1 | S2 | D1 | 6 | 10 | 16 | S2: 42–58 |
| T032 | H07.4 | S4 | D1 | 2 | 6 | 10 | S4: 0–10 |
| T033 | H07.2 | S3 | D1 | 6 | 10 | 18 | S3: 22–40 |
| T034 | H07.3 | S4 | D5 | 6 | 10 | 16 | S4: 0–16 |
| T035 | H07.3 | S4 | D4 | 6 | 12 | 18 | S4: 16–34 |
| T036 | H07.3 | S4 | D2 | 2 | 6 | 10 | S4: 34–44 |
| T037 | H07.3 | S4 | D2 | 2 | 4 | 6 | S4: 16–22 |
| T038 | H07.4 | S4 | D3 | 6 | 10 | 18 | S4: 28–46 |
| T039 | H07.4 | S4 | D3 | 2 | 6 | 10 | S4: 54–64 |
| T040 | H07.2 | S3 | LT | 6 | 12 | 18 | S3: 22–40 |
| T041 | H08 | S2 | D2 | 2 | 6 | 10 | S2: 0–10 |
| T042 | H08 | S2 | D5 | 2 | 4 | 6 | S2: 10–16 |
| T043 | H09.1 | S1 | D2 | 4 | 8 | 12 | S1: 28–40 |
| T044 | H09.1 | S1 | D1 | 4 | 8 | 12 | S1: 28–40 |
| T045 | H09.1 | S1 | D1 | 6 | 12 | 18 | S1: 46–64 |
| T046 | H09.1 | S1 | LT | 4 | 8 | 12 | S1: 52–64 |
| T047 | H09.2 | S2 | D1 | 4 | 8 | 12 | S2: 0–12 |
| T048 | H09.2 | S2 | D3 | 4 | 8 | 12 | S2: 12–24 |
| T049 | H09.2 | S2 | D1 | 2 | 4 | 6 | S2: 24–30 |
| T050 | H09.3 | S2 | D1 | 2 | 6 | 10 | S2: 12–22 |
| T051 | H09.3 | S2 | D2 | 6 | 12 | 22 | S2: 30–52 |
| T052 | H09.3 | S2 | D2 | 2 | 4 | 6 | S2: 58–64 |
| T053 | H09.4 | S4 | D5 | 4 | 8 | 12 | S4: 16–28 |
| T054 | H09.4 | S4 | D4 | 2 | 6 | 10 | S4: 54–64 |
| T055 | H09.4 | S4 | D4 | 2 | 6 | 10 | S4: 36–46 |
| T056 | H10 | S3 | D2 | 2 | 6 | 10 | S3: 52–62 |
| T057 | H10 | S3 | D5 | 2 | 6 | 10 | S3: 54–64 |
| T058 | H10 | S3 | D5 | 4 | 8 | 12 | S3: 0–12 |
| T059 | H10 | S3 | D2 | 6 | 12 | 18 | S3: 12–30 |
| T060 | H10 | S3 | D4 | 4 | 8 | 12 | S3: 30–42 |
| T061 | H10 | S3 | D2 | 8 | 14 | 22 | S3: 30–52 |
| T062 | H10 | S3 | D4 | 2 | 4 | 6 | S3: 0–6 |
| T063 | H10 | S3 | D4 | 4 | 8 | 12 | S3: 52–64 |
| T064 | H11 | S1 | D1 | 2 | 6 | 10 | S1: 18–28 |
| T065 | H11 | S1 | LT | 2 | 6 | 10 | S1: 42–52 |
| T066 | H11 | S1 | D2 | 2 | 6 | 10 | S1: 18–28 |
| T067 | H11 | S1 | D4 | 2 | 6 | 10 | S1: 42–52 |
| T068 | H12.1 | S3 | LT | 6 | 12 | 22 | S3: 0–22 |
| T069 | H12.1 | S3 | D3 | 2 | 6 | 10 | S3: 22–32 |
| T070 | H12.1 | S3 | D1 | 4 | 8 | 12 | S3: 40–52 |
| T071 | H12.2 | S3 | D5 | 4 | 8 | 12 | S3: 12–24 |
| T072 | H12.2 | S3 | D5 | 6 | 10 | 18 | S3: 24–42 |
| T073 | H12.2 | S3 | D5 | 2 | 6 | 10 | S3: 42–52 |
| T074 | H12.2 | S3 | D3 | 2 | 6 | 10 | S3: 52–62 |
| T075 | H12.3 | S4 | LT | 12 | 20 | 36 | S4: 0–36 |
| T076 | H12.3 | S4 | D5 | 4 | 8 | 12 | S4: 36–48 |
| T077 | H12.4 | S4 | D1 | 4 | 8 | 12 | S4: 36–48 |
| T078 | Común | S1 | D4 | 4 | 8 | 12 | S1: 0–12 |
| T079 | Común | S1 | D4 | 10 | 16 | 30 | S1: 12–42 |
| T080 | Común | S1 | UX | 6 | 12 | 18 | S1: 0–18 |
| T081 | Común | S1 | D3 | 2 | 4 | 8 | S1: 44–52 |
| T082 | Común | S1 | D3 | 4 | 8 | 12 | S1: 18–30 |
| T083 | Común | S1 | D5 | 2 | 4 | 6 | S1: 36–42 |
| T084 | Común | S2 | D3 | 6 | 10 | 16 | S2: 26–42 |
| T085 | Común | S3 | D3 | 2 | 6 | 10 | S3: 12–22 |
| T086 | Común | S2 | LT | 8 | 14 | 26 | S2: 0–26 |
| T087 | Común | S2 | LT | 6 | 12 | 22 | S2: 42–64 |
| T088 | Común | S1 | D5 | 6 | 10 | 16 | S1: 48–64 |
| T089 | Común | S2 | D4 | 10 | 16 | 30 | S2: 0–30 |
| T090 | Común | S3 | D2 | 4 | 8 | 12 | S3: 0–12 |
| T091 | Común | S4 | LT | 6 | 10 | 18 | S4: 46–64 |
| T092 | Común | S1 | LT | 10 | 16 | 24 | S1: 18–42 |
| T093 | Común | S3 | D1 | 6 | 10 | 16 | S3: 0–16 |
| T094 | Común | S3, S4 | QSM | 8 | 14 | 22 | S3: 54–64 (Casos de pagos, anticipo y efectivo); S4: 48–60 (Casos de documentos y correcciones) |
| T095 | Común | S5 | QSM | 10 | 16 | 24 | S5: 18–42 |
| T096 | Común | S5 | QA2 | 10 | 16 | 24 | S5: 8–32 |
| T097 | Común | S5 | QSM | 6 | 12 | 18 | S5: 0–18 |
| T098 | Común | S4, S5 | QA2 | 6 | 12 | 18 | S4: 48–58 (Continuidad sin cuenta y entrega); S5: 0–8 (Asociación posterior y acceso al mismo historial) |
| T099 | Común | S4 | QSM | 6 | 12 | 18 | S4: 0–18 |
| T100 | Común | S2 | D3 | 4 | 8 | 12 | S2: 0–12 |
| T101 | Común | S2 | D4 | 10 | 22 | 34 | S2: 30–64 |
| T102 | Común | S5 | D4 | 12 | 24 | 38 | S5: 0–38 |
| T103 | Común | S4, S5 | PO | 6 | 10 | 16 | S4: 0–10 (Redacción y preparación de guía); S5: 38–44 (Ajuste y revisión final de guía) |
| T104 | Común | S5 | PO | 4 | 8 | 12 | S5: 44–56 |
| T105 | Común | S5 | QSM | 2 | 4 | 6 | S5: 56–62 |

**Totales O/Base/P: 466 / 926 / 1.482 h.** Las 105 tareas se estiman una vez. Sus etapas internas se incluyen en esos totales.

T101 — Railway: publicación 4/8/12, correo 2/6/10 y archivos privados 4/8/12; total **10/22/34 h**, en S2, con actualización de los incrementos posteriores.

T102 — Respaldos: diario 4/8/12, externo cifrado 2/6/10 y restauración 6/10/16; total **12/24/38 h**, en S5. T101 y T102 conservan **46 h base**.

### Equipo profesional y capacidad

#### Puestos, experiencia y dedicación

**Diez profesionales hipotéticos con dedicaciones parciales:** seis desarrolladores, incluidos el líder técnico y D4 con DevOps; dos profesionales de calidad/facilitación; UX y Product Owner. **2.152 h brutas ≈ 5,38 personas a tiempo completo durante diez semanas**. Brian y Jeremy elaboran el expediente; César aporta decisiones del negocio.

| Código | Puesto y experiencia supuesta | Horas brutas reservadas |
| --- | --- | ---: |
| LT | Líder técnico/full stack senior, ≥5 años: arquitectura, seguridad, revisión e integración. | 304 |
| D1 | Full stack intermedio, 2–4 años: Laravel, Livewire, SQL y pruebas. | 276 |
| D2 | Full stack intermedio, 2–4 años: formularios, portal y archivos privados. | 268 |
| D3 | Full stack intermedio, 2–4 años: componentes, integración y validaciones. | 304 |
| D4 | Full stack senior y DevOps, ≥5 años en desarrollo y ≥4 en despliegue, correo, persistencia y restauración; una sola persona. | 324 |
| D5 | Full stack intermedio, 2–4 años: administración, agenda y pruebas. | 276 |
| QSM | QA y facilitación Scrum, ≥3 años en pruebas y experiencia facilitando equipos; una sola bolsa. | 196 |
| QA2 | QA intermedio, ≥3 años: aislamiento, archivos y recorridos integrales. | 56 |
| UX | Diseño UX/UI intermedio, ≥2 años: formularios, accesibilidad y revisión de uso. | 44 |
| PO | Product Owner/analista, ≥3 años: negocio, prioridades, guía y aceptación. | 104 |

La selección incluye perfiles intermedios capaces de usar los componentes del framework; LT y D4 atienden las tareas de arquitectura, autorización, órdenes, dinero y XML de mayor riesgo. Revisión por pares y pruebas están incluidas en las estimaciones.

#### Disponibilidad y carga por sprint

Máximo **80 h brutas por persona y sprint**: 80% planificable y 20% reservado para coordinación, ceremonias e interrupciones. Las bolsas se redondean hacia arriba a bloques de 4 h a partir de la carga desfavorable. Además se reserva continuidad: LT/D4 al menos 16 h por sprint; desarrolladores al menos 8 h y 16 h en S5; QSM 32 h; PO 20 h; UX 24 h iniciales, 4 h en S2–S4 y 8 h en S5. Son supuestos de contratación del ejercicio, incluidos en el costo.

Los profesionales deben estar disponibles en los bloques indicados, aunque su bolsa sea parcial. D4 atiende infraestructura y desarrollo en momentos diferentes; QSM no duplica horas por sus dos funciones.

| Persona | S1 (h) | S2 (h) | S3 (h) | S4 (h) | S5 (h) | Total (h) |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| LT | 60 | 80 | 80 | 68 | 16 | 304 |
| D1 | 52 | 72 | 72 | 64 | 16 | 276 |
| D2 | 56 | 76 | 80 | 40 | 16 | 268 |
| D3 | 56 | 80 | 80 | 72 | 16 | 304 |
| D4 | 80 | 80 | 68 | 48 | 48 | 324 |
| D5 | 52 | 60 | 80 | 68 | 16 | 276 |
| QSM | 32 | 32 | 32 | 40 | 60 | 196 |
| QA2 | 0 | 0 | 0 | 16 | 40 | 56 |
| UX | 24 | 4 | 4 | 4 | 8 | 44 |
| PO | 20 | 20 | 20 | 20 | 24 | 104 |

| Sprint | Actividades o partes | Base (h) | P reservado (h) | Disponibilidad bruta (h) | Capacidad al 80% (h) | Libre tras P (h) |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| S1 | 22 | 188 | 296 | 432 | 345,6 | 49,6 |
| S2 | 26 | 216 | 352 | 504 | 403,2 | 51,2 |
| S3 | 28 | 226 | 366 | 516 | 412,8 | 46,8 |
| S4 | 24 | 206 | 332 | 440 | 352,0 | 20,0 |
| S5 | 8 | 90 | 136 | 260 | 208,0 | 72,0 |

**2.152 h brutas** proporcionan **1.721,6 h planificables** para **1.482 h desfavorables**: quedan **239,6 h planificables de apoyo/ajustes**, además de **430,4 h reservadas para coordinación e interrupciones**. Se paga la disponibilidad completa; estas bolsas no se descuentan otra vez del presupuesto.

#### Secuencia, capacidad y sensibilidad del plazo

La secuencia comprueba todas las dependencias por etapa, una tarea por persona a la vez y los límites de cada sprint. Las 24 unidades de entrega concentran sus tareas propias en un solo sprint. El plazo permanece en **10 semanas y 5 sprints**, con jornada ordinaria de 40 h semanales y 32 h planificables.

La cadena técnica sin esperas suma **134 h base y 224 h desfavorables**. Con los bloques, recursos y revisiones del plan, **T105 termina en la hora efectiva 318 de 320** en el desfavorable; el margen de cierre es de **2 h efectivas**. Es una secuencia factible bajo los supuestos, no una prueba de que diez personas sean el mínimo ni una ejecución real.

| Riesgo | Respuesta dentro de cinco sprints | Responsable |
| --- | --- | --- |
| Esfuerzo superior al desfavorable o espera no prevista | Usar apoyo disponible y revisar secuencia, alcance o recursos mediante decisión explícita; no declarar trabajo pendiente como terminado. | LT/PO |
| Especialista ausente o bloque parcial no disponible | Confirmar disponibilidades y sustitución con la misma competencia; recalcular secuencia y costo. | QSM/LT |
| Decisión pendiente de César | Resolver consultas concretas y registrar el supuesto; no inventar una aprobación. | PO |
| Tarifas o infraestructura mayores | Contrastar cotizaciones y consumo; utilizar contingencia solo contra el riesgo correspondiente. | D4/PO |
| Permisos, archivos o restauración fallan | Corregir y repetir los casos antes de T104; conservar los resultados simulados identificados. | LT/QSM/QA2/D4 |

### Presupuesto del proyecto simulado

#### Tarifas profesionales y costo del equipo

**CRC, antes de impuestos.** Son bloques de servicios profesionales y tarifas académicas, no salarios de Brian/Jeremy ni cotizaciones oficiales. Una relación laboral exigiría sus cargas y provisiones. Las bolsas recomendadas cubren el escenario desfavorable y se reservan desde el inicio; no dependen de contratar a una persona desconocida cuando aparezca el problema.

| Persona | Horas base comparativas | Horas reservadas para P | Rango supuesto/h | Tarifa de referencia/h | Costo reservado |
| --- | ---: | ---: | --- | ---: | ---: |
| LT | 192 | 304 | ₡10.000–₡16.000 | ₡12.000 | ₡3.648.000 |
| D1 | 184 | 276 | ₡6.000–₡10.000 | ₡8.000 | ₡2.208.000 |
| D2 | 180 | 268 | ₡6.000–₡10.000 | ₡8.000 | ₡2.144.000 |
| D3 | 196 | 304 | ₡6.000–₡10.000 | ₡8.000 | ₡2.432.000 |
| D4 | 204 | 324 | ₡10.000–₡16.000 | ₡12.000 | ₡3.888.000 |
| D5 | 184 | 276 | ₡6.000–₡10.000 | ₡8.000 | ₡2.208.000 |
| QSM | 168 | 196 | ₡6.000–₡10.000 | ₡8.000 | ₡1.568.000 |
| QA2 | 36 | 56 | ₡6.000–₡10.000 | ₡8.000 | ₡448.000 |
| UX | 44 | 44 | ₡6.000–₡10.000 | ₡8.000 | ₡352.000 |
| PO | 100 | 104 | ₡8.000–₡14.000 | ₡10.000 | ₡1.040.000 |

**Capacidad para el esfuerzo base: ₡13.688.000. Refuerzo de disponibilidad para cubrir P: ₡6.248.000. Equipo reservado recomendado: ₡19.936.000.** D4 incluye DevOps; no se agrega otra factura de OPS para las mismas horas.

#### Infraestructura y operación prevista

Provisión de tres meses para diez semanas/cierre, sujeta a consumo/cotizaciones. Equipos/conexión incluidos en tarifa profesional; sin licencias pagadas en caso base.

| Concepto                           | Unidad prevista | Cantidad | Costo del escenario |
| ---------------------------------- | --------------- | -------- | ------------------- |
| Alojamiento de desarrollo y piloto | ₡15.000/mes     | 3        | ₡45.000             |
| Correo transaccional               | ₡5.000/mes      | 3        | ₡15.000             |
| Copia externa de respaldos         | ₡5.000/mes      | 3        | ₡15.000             |
| Dominio por un año                 | ₡10.000/año     | 1        | ₡10.000             |

**₡85.000** total. Los ₡15.000/mes de alojamiento son una provisión académica, no una cotización. Validarla contra [Railway Pro, consumo y almacenamiento](https://railway.com/pricing), con tipo de cambio e impuestos al contratar; el mínimo del plan no garantiza el costo total.

Después: **₡25.000/mes + ₡10.000/año = ₡310.000 por doce meses**, antes de impuestos, sin soporte/mantenimiento evolutivo. No duplicar los tres meses iniciales.

#### Presupuesto total y distribución

Se propone **un presupuesto a autorizar**, con el refuerzo de capacidad identificado. La columna base permite comparar el costo de contratar solo la dedicación esperada; la recomendada financia la disponibilidad necesaria para mantener cinco sprints también con las horas desfavorables. No son dos proyectos ni dos cobros acumulables.

| Componente | Referencia base | Refuerzo para cubrir P | Recomendado |
| --- | ---: | ---: | ---: |
| Equipo profesional | ₡13.688.000 | ₡6.248.000 | **₡19.936.000** |
| Infraestructura | ₡85.000 | ₡0 | **₡85.000** |
| Subtotal | ₡13.773.000 | ₡6.248.000 | **₡20.021.000** |
| Contingencia financiera del 15% | ₡2.065.950 | ₡937.200 | **₡3.003.150** |
| Total antes de impuestos | ₡15.838.950 | ₡7.185.200 | **₡23.024.150** |

El 20% de disponibilidad ya está incluido en las bolsas. El refuerzo cubre la diferencia de capacidad entre Base y P. La contingencia financiera del 15% atiende variaciones de tarifas, servicios u otros costos no incluidos; no vuelve a cobrar las mismas horas desfavorables ni el mismo 20%. No representa un nivel estadístico de confianza. [Criterio general de presupuesto base, incertidumbre y contingencia](https://www.gov.uk/government/publications/cost-estimating-guidance/cost-estimating-guidance).

El favorable reduce esfuerzo, pero no es la base recomendada para comprometer un plazo fijo. Con las bolsas reservadas se paga la disponibilidad acordada aunque se utilicen menos horas; reducirla o liberar dinero exige revisar el acuerdo y el riesgo del plazo. La inversión real de RYC queda por confirmar; el ejercicio no afirma que el negocio haya autorizado el desembolso.

**Sensibilidad a tarifas, con las mismas personas y bolsas reservadas:**

| Tarifa | Equipo | Infraestructura | Contingencia 15% | Total antes de impuestos |
| --- | ---: | ---: | ---: | ---: |
| Inferior | ₡15.632.000 | ₡85.000 | ₡2.357.550 | ₡18.074.550 |
| Referencia | ₡19.936.000 | ₡85.000 | ₡3.003.150 | ₡23.024.150 |
| Superior | ₡25.704.000 | ₡85.000 | ₡3.868.350 | ₡29.657.350 |

| Sprint | Equipo reservado | Infraestructura | Contingencia | Presupuesto recomendado |
| --- | ---: | ---: | ---: | ---: |
| S1 | ₡4.056.000 | ₡25.000 | ₡612.150 | ₡4.693.150 |
| S2 | ₡4.712.000 | ₡25.000 | ₡710.550 | ₡5.447.550 |
| S3 | ₡4.760.000 | ₡25.000 | ₡717.750 | ₡5.502.750 |
| S4 | ₡4.024.000 | ₡0 | ₡603.600 | ₡4.627.600 |
| S5 | ₡2.384.000 | ₡10.000 | ₡359.100 | ₡2.753.100 |

La distribución suma **₡23.024.150** antes de impuestos, incluidos los mismos ₡85.000 de infraestructura y la contingencia; no se agregan renovaciones o compras duplicadas.

### Supuestos, dependencias y riesgos de la estimación

Las **12 historias principales** organizan la documentación; H05, H07, H09 y H12 contienen las **16 subdivisiones**. Se conservan las páginas, formularios y reglas del sistema. Las **105 tareas** conservan **926 horas base** y se asignan según la secuencia reservada para P; T094, T098 y T103 se detallan por etapas sin aumentar esfuerzo. Cada subdivisión aplica los criterios de su principal que correspondan a su alcance y sus criterios específicos. La validación de una principal desglosada comprende todas sus partes y las tareas comunes aplicables.

Los principales riesgos son la dependencia de permisos por sede (H09.3), la verificación de dinero (H12.1 y H07.2), la custodia de XML/PDF (H12.3), las aprobaciones de César y la integración necesaria para publicar servicios. Algunas historias pequeñas dependen de tareas que se completan antes, dentro de otras historias o como componentes comunes; eso no implica duplicar esfuerzo. Las dependencias del backlog técnico de Semana 5 y las asignaciones de esta semana conservan la secuencia técnica de referencia.

El ejercicio de clase **N08/N10: 16 puntos, 2 Sprints y ₡240.000** corresponde solo a dos funcionalidades y a supuestos de dos integrantes. **N08 no equivale a toda H09**, porque H09 incluye cuentas autorizadas e historiales; los importes y la velocidad del ejercicio parcial no sustituyen el plan completo de diez profesionales hipotéticos.

### Capacidad y cierre en cinco sprints

**Plazo fijo: 10 semanas y cinco sprints de dos semanas**, incluida la aceptación y el cierre. Los tres escenarios usan la misma secuencia reservada; cambian las horas de ejecución dentro de cada bloque, no los requisitos ni la fecha comprometida.

Los 124 puntos expresan tamaño relativo; 124 ÷ 5 = **24,8 puntos por sprint como promedio del proyecto**, no un límite de capacidad. Las entregas previstas suman **25 / 34 / 31 / 34 / 0 puntos**. S5 contiene trabajo común de comprobación y cierre, sin contar otra vez las historias. No existe velocidad observada de un equipo real: todo el caso es teórico.

| Escenario | Horas-persona | Cierre manteniendo los inicios reservados | Resultado |
| --- | ---: | --- | --- |
| Favorable: menos dificultad/correcciones | 466 | Hora efectiva 314 de 320, en S5 | Cabe en cinco sprints con las bolsas reservadas. |
| Base: esfuerzo previsto | 926 | Hora efectiva 316 de 320, en S5 | Cabe en cinco sprints con las bolsas reservadas. |
| Desfavorable: mayor dificultad/integración | 1.482 | Hora efectiva 318 de 320, en S5 | Cabe en cinco sprints con las bolsas reservadas. |

**Plan recomendado:** diez profesionales parciales, **2.152 h brutas y 1.721,6 h planificables**, con presupuesto de **₡23.024.150 antes de impuestos**. La comparación base de **₡15.838.950** ayuda a identificar el refuerzo; no es otra suma que se añada al recomendado.

La reorganización permite construir componentes en paralelo contra modelos comunes, preparar Railway antes y repartir comprobaciones y guía en etapas. Los permisos, aceptación comercial, pago previo, tratamiento real y entrega siguen siendo obligatorios al utilizar el sistema. La factibilidad comprobada depende de las horas y disponibilidades declaradas; una desviación fuera de ese rango exige una decisión de respuesta dentro del plazo, no una ampliación automática ni una aceptación ficticia.

### Cronograma de entregas (Release Plan)

Los cinco sprints mantienen las fechas de referencia. Cada una de las ocho historias sin subdividir y las dieciséis subdivisiones se construye y acepta en un sprint con sus criterios y DoD. Las cuatro principales desglosadas se completan al aceptar sus partes; sus subtotales no se añaden otra vez. La comprobación integral y aceptación conjunta de S5 no duplican puntos.

| Sprint | Fechas previstas | Incremento principal | Unidades de entrega previstas | Puntos | Presupuesto recomendado |
| --- | --- | --- | --- | ---: | ---: |
| **S1** | 10–23 sep. 2026 | Base técnica, acceso y datos iniciales | H01, H02, H03, H09.1, H11 | **25** | ₡4.693.150 |
| **S2** | 24 sep.–7 oct. 2026 | Solicitudes, asociaciones y condiciones | H04, H05.1, H05.3, H07.1, H08, H09.2, H09.3 | **34** | ₡5.447.550 |
| **S3** | 8–21 oct. 2026 | Agenda, cobros y recibos | H05.2, H05.4, H07.2, H10, H12.1, H12.2 | **31** | ₡5.502.750 |
| **S4** | 22 oct.–4 nov. 2026 | Tratamientos, documentos e integración | H06, H07.3, H07.4, H09.4, H12.3, H12.4 | **34** | ₡4.627.600 |
| **S5** | 5–18 nov. 2026 | Validación, respaldo y cierre | Comprobaciones comunes, restauración, guía, aceptación y cierre | **0** | ₡2.753.100 |
| **Total** | **10 semanas** | **105 tareas únicas; 108 actividades al detallar tres tareas comunes** | **12 historias principales, 16 subdivisiones y 24 unidades de entrega** | **124** | **₡23.024.150** |

**Seguimiento:** revisar por sprint tareas y etapas terminadas, carga, criterios, presupuesto y riesgos. Un burndown comienza con 124 puntos y descuenta únicamente unidades aceptadas, una vez cada una. Se registran los cambios y la evidencia del expediente en Git; los resultados hipotéticos se rotulan simulados. Las modificaciones nuevas de alcance, dependencias, personas o costos se consultan antes de aplicarlas y se propagan a todos los apartados afectados.
