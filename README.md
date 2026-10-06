# Sistema de Gestión para RYC Control de Plagas

**Universidad Técnica Nacional**  
Sede Regional San Carlos

| Información | Detalle |
| --- | --- |
| Curso | Administración de Proyectos Informáticos |
| Proyecto | Sistema de Gestión para RYC Control de Plagas |
| Profesor | Deiver Cubero Molina |

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
    - [Página pública y contacto por WhatsApp](#página-pública-y-contacto-por-whatsapp)
    - [Necesidades de los usuarios y resultados esperados](#necesidades-de-los-usuarios-y-resultados-esperados)
      - [Necesidades de las personas interesadas y los clientes](#necesidades-de-las-personas-interesadas-y-los-clientes)
      - [Necesidades de César](#necesidades-de-césar)
      - [Necesidades de RYC como empresa](#necesidades-de-ryc-como-empresa)
    - [Registro e inicio de sesión](#registro-e-inicio-de-sesión)
    - [Diseño y comportamiento en dispositivos](#diseño-y-comportamiento-en-dispositivos)
    - [Experiencia de uso de César](#experiencia-de-uso-de-césar)
    - [Empresas, sedes y cuentas](#empresas-sedes-y-cuentas)
    - [Asociación mediante ID](#asociación-mediante-id)
    - [Consultoría y aceptación del servicio](#consultoría-y-aceptación-del-servicio)
    - [Clientes, ubicaciones y servicios](#clientes-ubicaciones-y-servicios)
    - [Plagas, productos y tratamientos](#plagas-productos-y-tratamientos)
    - [Visitas y calendario](#visitas-y-calendario)
    - [Información histórica](#información-histórica)
    - [Tecnología, alojamiento y entrega](#tecnología-alojamiento-y-entrega)
    - [Páginas del sistema y su contenido](#páginas-del-sistema-y-su-contenido)
      - [Convenciones de presentación](#convenciones-de-presentación)
      - [Mensajes de validación de campos](#mensajes-de-validación-de-campos)
      - [Navegación](#navegación)
      - [Cómo se organiza cada página](#cómo-se-organiza-cada-página)
      - [Página pública y acceso](#página-pública-y-acceso)
        - [Página pública de RYC](#página-pública-de-ryc)
        - [Inicio de sesión](#inicio-de-sesión)
        - [Crear cuenta](#crear-cuenta)
        - [Recuperar acceso](#recuperar-acceso)
        - [Cambiar contraseña por recuperación](#cambiar-contraseña-por-recuperación)
      - [Portal del cliente](#portal-del-cliente)
        - [Inicio del portal](#inicio-del-portal)
        - [Mis atenciones](#mis-atenciones)
        - [Pagos y documentos](#pagos-y-documentos)
      - [Administración de César](#administración-de-césar)
        - [Inicio administrativo](#inicio-administrativo)
        - [Atenciones](#atenciones)
        - [Clientes](#clientes)
        - [Calendario](#calendario)
        - [Catálogos](#catálogos)
        - [Cobros y documentos](#cobros-y-documentos)
        - [Configuración](#configuración)
      - [Cuenta compartida por portal y administración](#cuenta-compartida-por-portal-y-administración)
        - [Mi cuenta](#mi-cuenta)
    - [Comprobaciones del sistema](#comprobaciones-del-sistema)
  - [Cronograma general del proyecto](#cronograma-general-del-proyecto)
    - [Ciclo de vida y organización del equipo](#ciclo-de-vida-y-organización-del-equipo)
      - [Fases del ciclo de vida](#fases-del-ciclo-de-vida)
      - [Organización del equipo y roles](#organización-del-equipo-y-roles)
    - [Base del cronograma y calendario del curso](#base-del-cronograma-y-calendario-del-curso)
    - [Objetivos e incrementos por Sprint (Gestión del proyecto)](#objetivos-e-incrementos-por-sprint-gestión-del-proyecto)
    - [Plan técnico de trabajo e implementación del sistema](#plan-técnico-de-trabajo-e-implementación-del-sistema)
      - [Cálculo de capacidad técnica](#cálculo-de-capacidad-técnica)
      - [Páginas que agrupan las tareas técnicas](#páginas-que-agrupan-las-tareas-técnicas)
      - [Tareas, responsables y dependencias](#tareas-responsables-y-dependencias)
      - [Distribución del backlog en fases técnicas de desarrollo (Releases técnicos)](#distribución-del-backlog-en-fases-técnicas-de-desarrollo-releases-técnicos)
      - [Criterios de terminación de tareas (Definition of Done - DoD)](#criterios-de-terminación-de-tareas-definition-of-done---dod)
      - [Dinámica de trabajo y ceremonias Scrum](#dinámica-de-trabajo-y-ceremonias-scrum)
      - [Seguimiento, control y gestión de cambios](#seguimiento-control-y-gestión-de-cambios)

---

## Semana 1 · Definición del proyecto

### Problema

RYC Control de Plagas lleva el seguimiento de sus clientes, visitas, tipos de plagas, productos químicos utilizados y próximas fumigaciones de forma poco centralizada. Esto puede dificultar saber cuándo corresponde volver a visitar a un cliente, qué tratamiento se utilizó anteriormente, qué tipo de plaga presenta cada lugar y cuál es la frecuencia de atención necesaria.

Además, los clientes no cuentan con un medio digital propio donde puedan consultar la información de los servicios recibidos, conocer sus próximas visitas o solicitar una nueva visita, lo que genera una mayor dependencia de la comunicación directa con la empresa.

### Proyecto propuesto

Desarrollar una aplicación web con una página pública de presentación (landing page), administración para César y un portal opcional.

La página pública presentará información real de RYC y facilitará el contacto por WhatsApp sin cuenta. César gestionará clientes, empresas, ubicaciones, solicitudes, agenda, servicios, tratamientos, pagos y documentos desde celular y computadora.

La consultoría inicial será gratuita en el cantón de San Carlos; fuera se cotizará y cobrará completamente antes de la visita. El trabajo requiere 50% antes de iniciar y 50% al finalizar, verificados por César.

Facturas y documentos se emitirán externamente y se entregarán sin exigir cuenta. Quien se registre podrá consultar el historial autorizado, solicitar atención o informar pagos; César asociará registros existentes mediante el ID, con acceso por empresa o sede.

### Valor esperado

Mejorar la organización y el control de los servicios realizados por RYC Control de Plagas, facilitando el seguimiento de clientes, tratamientos y próximas visitas.

Además, se busca mejorar la experiencia del cliente mediante un espacio donde pueda consultar de manera sencilla la información relacionada con sus servicios y solicitar nuevas visitas sin depender únicamente de llamadas o mensajes.

### Objetivo general

Desarrollar un sistema web que permita a RYC Control de Plagas gestionar y dar seguimiento a sus clientes, visitas y tratamientos, incorporando un portal de autoservicio para mejorar la comunicación y el acceso de los clientes a la información de sus servicios.

### Objetivos específicos

- Presentar servicios, operador, zonas y condiciones reales de RYC.
- Facilitar contacto por WhatsApp sin registro, directo o mediante un mensaje preparado.
- Administrar particulares, empresas y ubicaciones con o sin cuenta.
- Registrar contactos recibidos por César y solicitudes del portal en un seguimiento común.
- Aplicar gratuidad de consultoría en San Carlos y cotización con pago previo fuera del cantón.
- Registrar propuestas, órdenes y pagos con anticipo del 50% y saldo al finalizar.
- Verificar SINPE, efectivo y transferencias sin duplicar pagos.
- Registrar servicios y próximas atenciones según necesidades y frecuencia acordada.
- Conservar plagas, productos, cantidades, tratamientos y recomendaciones reales.
- Mantener historial por cliente/lugar y calendario de visitas.
- Facilitar tareas de César en ambos dispositivos, reutilizando datos y borradores.
- Adjuntar documentos fiscales externos y registrar entrega de documentos y recomendaciones sin cuenta.
- Ofrecer cuenta opcional para consultar historial, pagos, documentos y próximas visitas.
- Permitir solicitudes y reportes de pago desde el portal como alternativa.
- Asociar mediante ID un historial autorizado sin duplicarlo.
- Aplicar acceso de empresa a todas sus sedes y acceso de sede solo a la asignada.
- Consultar pagos confirmados por periodo y moneda.

---

## Semana 2 · Taller: interesados de nuestro proyecto

### Contexto y restricciones del proyecto

RYC Control de Plagas es una empresa pequeña administrada principalmente por César Rodríguez Corrales, quien además realiza la mayor parte de los servicios y concentra gran parte del conocimiento operativo del negocio. Debido a esto, su disponibilidad será importante para obtener información, aclarar procesos y validar las funcionalidades desarrolladas.

El proyecto será desarrollado por Brian Rodríguez Pérez y Jeremy Rodríguez Esquivel dentro del periodo establecido para el curso, por lo que el tiempo disponible representa una restricción importante. Además, el proyecto cuenta con recursos económicos limitados, por lo que se buscará utilizar herramientas y tecnologías de bajo costo o gratuitas cuando sea posible.

A nivel tecnológico, el sistema será desarrollado como una aplicación web y dependerá de acceso a Internet, dispositivos compatibles y un servicio de alojamiento. También será necesario considerar que parte de la información histórica de clientes y servicios puede encontrarse distribuida en distintos medios, por lo que deberá determinarse qué información podrá incorporarse al sistema.

Debido al tamaño del equipo, al tiempo disponible y a la dependencia de la información proporcionada por César Rodríguez Corrales, será necesario priorizar las funcionalidades que aporten mayor valor al proyecto.

### Registro de interesados

| Interesado | Necesidad | Poder | Interés | Actitud inicial | Estrategia | Responsable |
| --- | --- | :---: | :---: | --- | --- | --- |
| César Rodríguez Corrales, propietario y operador de RYC | Centralizar la información de clientes, visitas, tratamientos y próximas fumigaciones. | 5 | 5 | Favorable | Gestionar de cerca: consultar necesidades y validar avances. | Ambos |
| Brian Rodríguez Pérez y Jeremy Rodríguez Esquivel, equipo del proyecto | Contar con requisitos claros y retroalimentación para organizar y desarrollar el sistema. | 4 | 5 | Favorable | Gestionar de cerca: coordinar tareas, resolver dudas y revisar avances. | Ambos |
| Clientes particulares | Consultar su historial, próximas visitas y solicitar nuevas visitas desde su cuenta. | 2 | 4 | Favorable | Mantener informados y recoger comentarios sobre el portal. | Jeremy |
| Empresas clientes, como organizaciones que contratan los servicios | Consultar el historial de servicios y dar seguimiento a los tratamientos recibidos. | 3 | 5 | Favorable | Mantener informadas y consultar sus necesidades durante las validaciones del portal. | Brian |
| Encargados o contactos de empresas clientes | Coordinar las visitas y consultar la información necesaria para recibir los servicios. | 3 | 5 | Favorable | Mantener informados y consultar el proceso de coordinación de visitas. | Jeremy |
| Proveedores de productos utilizados por RYC | Que los productos suministrados se identifiquen correctamente en los registros de tratamientos. | 2 | 2 | Neutral | Monitorear y consultar información de los productos cuando sea necesario para su registro. | Brian |
| Proveedor de alojamiento o infraestructura web | Contar con requisitos técnicos claros para prestar el servicio de alojamiento. | 2 | 2 | Neutral | Monitorear las condiciones y disponibilidad del servicio. | Brian |
| Entidades reguladoras aplicables | Que el proyecto considere las disposiciones que le correspondan. | 5 | 2 | Neutral | Mantener satisfechas mediante la identificación y atención de los requisitos aplicables. | Ambos |

### Justificación de valoraciones relevantes

- **Equipo del proyecto — poder 4 e interés 5:** toma decisiones técnicas y organiza el desarrollo, aunque las decisiones sobre las necesidades del negocio deben validarse con César.

- **Empresas clientes — poder 3 e interés 5:** sus necesidades influyen en el portal y el resultado les afecta directamente, pero no se ha identificado autoridad para aprobar cambios en el proyecto.

- **Encargados de empresas clientes — poder 3 e interés 5:** pueden facilitar o dificultar la coordinación y aportar información relevante, aunque no necesariamente deciden por la empresa que representan.

- **Proveedores de productos utilizados por RYC — poder 2 e interés 2:** pueden aportar información para identificar correctamente los productos registrados en los tratamientos, pero no tienen autoridad sobre las decisiones del sistema. Su participación sería puntual, por lo que inicialmente se les asigna poder e interés bajos.

- **Entidades reguladoras — poder 5 e interés 2:** se propone un poder alto porque los requisitos que resulten aplicables podrían condicionar decisiones del proyecto. Su interés se considera bajo por no participar en el trabajo cotidiano. Las entidades y disposiciones concretas deberán identificarse.

### Mapa Poder–Interés

![Mapa Poder–Interés del Sistema de Gestión para RYC Control de Plagas](img/mapa-poder-interes.png)

### Tres interesados críticos y su involucramiento

| Interesado crítico | Cómo se involucrará | Momento o frecuencia propuesta | Responsable |
| --- | --- | --- | --- |
| César Rodríguez Corrales | Mediante consultas directas para identificar necesidades y demostraciones para validar funcionalidades y resolver dudas. | Al inicio y al finalizar cada ciclo de trabajo, según su disponibilidad. | Ambos |
| Empresas clientes | Mediante consultas y pruebas del portal con representantes, para revisar la información de servicios, próximas visitas y solicitudes. | Durante la definición del portal y cuando exista una versión que puedan probar. | Brian |
| Equipo del proyecto | Mediante reuniones breves y mensajes para distribuir tareas, revisar avances y tomar decisiones entre ambos integrantes. | Coordinación semanal y comunicación cuando surjan dudas o bloqueos. | Ambos |

### Preguntas de análisis de interesados

#### ¿A quién debemos involucrar primero?

A César Rodríguez Corrales, debido a que es el propietario y la persona que posee mayor conocimiento sobre el funcionamiento de RYC Control de Plagas.

#### ¿Quién puede bloquear una decisión?

César Rodríguez Corrales puede modificar o detener decisiones relacionadas con las necesidades reales del negocio. También podrían existir requisitos regulatorios que obliguen a modificar alguna decisión del proyecto.

#### ¿Quién necesita información frecuente?

César Rodríguez Corrales y los integrantes del equipo del proyecto, ya que participan directamente en la definición, desarrollo y validación de las funcionalidades.

#### ¿Qué interesado estamos subestimando?

Los encargados o contactos de empresas clientes, debido a que pueden aportar información importante sobre la forma en que coordinan las visitas y reciben los servicios de RYC.

#### ¿Qué conflicto de expectativas puede aparecer?

Puede existir un conflicto entre la cantidad de funcionalidades que se desean desarrollar y el tiempo disponible para completar el proyecto. También pueden existir diferencias entre las necesidades internas de RYC y las funcionalidades que los clientes esperan encontrar en el portal.

### Enfoque de gestión del proyecto

Se propone un enfoque adaptativo, porque los detalles de los procesos y las funcionalidades deberán precisarse mediante consultas con César y retroalimentación de los usuarios.

La empresa concentra gran parte de sus decisiones y conocimiento operativo en su propietario, por lo que será necesario coordinar las validaciones según su disponibilidad. Además, el equipo está formado por dos estudiantes, dispone de recursos limitados y debe trabajar dentro del periodo del curso.

Por estas condiciones, se desarrollará el sistema en ciclos cortos, revisando los avances y ajustando los detalles de las funcionalidades con la retroalimentación recibida. Se priorizará el orden de implementación de los objetivos aprobados en la clase 1.

---

## Semana 3 Planeamiento del proyecto
### Alcance y organización de la información

Una sola aplicación web reunirá clientes, empresas, ubicaciones, solicitudes, consultorías, agenda, servicios, plagas, productos, tratamientos, recomendaciones, órdenes, pagos y documentos.

| Área | Quién la usa | Función |
| --- | --- | --- |
| Página pública de presentación (landing) | Cualquier persona, sin cuenta. | Conocer RYC, sus servicios, operador, zonas y condiciones; contactar por WhatsApp. |
| Administración | César Rodríguez Corrales. | Gestionar la atención y sus registros desde celular o computadora. |
| Portal opcional | Personas que decidan registrarse. | Consultar información autorizada, enviar solicitudes e informar pagos. |

WhatsApp será el canal comercial principal. La cuenta es opcional antes, durante y después de la atención. Los pagos, facturas y recomendaciones se gestionan también sin cuenta.

#### Cuenta, cliente y asociación

| Elemento | Qué representa |
| --- | --- |
| Cuenta de acceso | Credenciales personales de correo y contraseña, datos de perfil e ID único. |
| Registro de datos del cliente | Ficha de un particular o empresa, con contactos, ubicaciones e historial; existe aunque nadie cree una cuenta. |
| Asociación | Autorización que César comprueba y registra para que una cuenta consulte un cliente y las ubicaciones permitidas. |

Asociar una cuenta permite consultar el historial existente; no duplica servicios ni documentos. Las cuentas de particulares, principales de empresa y de sede usan el mismo portal con distintos permisos. Solo César utiliza administración.

| Persona | Qué puede hacer |
| --- | --- |
| Sin cuenta | Consultar la landing; contactar, coordinar, aceptar condiciones, informar pagos y recibir documentos por el medio acordado. |
| Con cuenta sin asociación | Gestionar su perfil, copiar su ID y solicitar consultoría con correo verificado. Puede haber historial previo pendiente de asociar. Pagos y documentos se limitan a órdenes de sus propias solicitudes. |
| Con cuenta asociada | Consultar servicios, plagas, productos, tratamientos, recomendaciones, pagos, documentos y próximas visitas autorizados; solicitar atención para esas ubicaciones. |
| César | Gestionar todos los registros, verificar pagos, registrar entregas y administrar asociaciones. |

#### Atención sin cuenta: recorrido principal

1. La persona conoce RYC en la landing y contacta por WhatsApp directamente o con el mensaje del formulario público.
2. César busca coincidencias y registra el contacto recibido; reutiliza el cliente y los datos existentes.
3. Comprueba la ubicación y aplica el costo de consultoría: gratuita en San Carlos; fuera, cotización aceptada y 100% confirmado antes de la visita.
4. Después de la consultoría presenta el trabajo, ubicación, total y moneda, con 50% de anticipo y 50% al finalizar. Registra la decisión; aceptar crea la orden, no un pago.
5. Comparte datos de cobro por SINPE, transferencia o efectivo; registra y verifica el dinero informado. Puede programar antes, pero iniciar exige el anticipo confirmado.
6. Al finalizar registra productos, cantidades, tratamiento y recomendaciones reales, y cobra el saldo.
7. Adjunta los documentos de su herramienta externa (Factura electronica de Hacienda); entrega documentos y recomendaciones y registra la entrega.
8. Si el cliente se registra después, el cliente comunica su ID. César comprueba su autorización y asocia el historial con el cliente correspondiente.

#### Atención con cuenta: recorrido opcional

La persona puede elegir WhatsApp o el portal. Una solicitud del portal queda guardada una vez y ofrece Consultar por WhatsApp con su referencia. La coordinación, decisión y pagos siguen la misma orden aunque cambie el canal.

El portal permite aceptar propuestas e informar pagos con comprobante; César registra las respuestas recibidas por WhatsApp y confirma el dinero una sola vez. Se aplican las mismas condiciones del recorrido principal.

La cuenta consulta los servicios publicados y documentos autorizados. Tenerlos en el portal no sustituye su entrega. La asociación habilita el historial y las sedes permitidas, sin duplicar registros ni otorgar administración.

### Página pública y contacto por WhatsApp

#### Contenido y recorrido

La landing se consulta sin cuenta. Acción principal: Contactar por WhatsApp; Secundaria: Ver mi historial.

| Sección, en orden | Contenido y acciones |
| --- | --- |
| Encabezado | Identificación de RYC; Servicios, Cómo trabajamos, Zonas y Contacto; WhatsApp y acceso al portal. |
| Presentación | Servicio y zona de atención; foto real autorizada del operador si existe; WhatsApp y Preparar mi consulta. |
| Quién atiende | Nombre y función de César; datos reales autorizados por RYC. |
| Servicios | Servicios y plagas confirmados; consulta por WhatsApp sin confirmar precio ni disponibilidad. |
| Cómo trabajamos | Contacto, consultoría, propuesta, anticipo, tratamiento, saldo y entrega de documentos. |
| Zonas y condiciones | Gratuidad en San Carlos y cobro fuera; condiciones del trabajo y total confirmado antes de aceptar. |
| Historial opcional | Servicios, tratamientos, recomendaciones, pagos y documentos; Crear cuenta o Ver mi historial. |
| Contacto y cierre | Número autorizado de WhatsApp y formulario breve. |

#### Formulario breve para preparar el mensaje

| Campo, en orden | Obligatorio | Regla |
| --- | --- | --- |
| Nombre de contacto | Sí | Entre 2 y 100 caracteres; no exige campos separados para apellidos. |
| Teléfono de contacto |  Sí| Debe contener 8 dígitos con prefijo +506 y separadores permitidos. El contacto puede responder desde el número con que envíe el mensaje. |
| Cantón o lugar de atención | Sí | Entre 2 y 150 caracteres; César comprueba después la dirección y el cantón real. |
| Descripción de la consulta | Sí | Entre 10 y 2000 caracteres. |
| Fecha preferida | No | Hoy o una fecha futura; no reserva una visita. |

Una columna y controles comunes. Acciones: Continuar en WhatsApp y Contactar sin formulario.

Texto de apoyo: Prepararemos tu mensaje en WhatsApp. Revísalo y pulsa Enviar allí. Esto no reserva una visita.

El enlace usa el número real de RYC y el saludo con los campos completados, codificados para conservar tildes y saltos de línea. Abre WhatsApp o su versión web; el usuario debe enviar el mensaje allí. Abrir, copiar o regresar al formulario no confirma recepción, guarda una solicitud ni reserva una visita.

Los datos permanecen mientras la página siga abierta; no se guardan en la base de datos, direcciones de la propia aplicación, analítica ni registros de diagnóstico. Si falla WhatsApp o el portapapeles, se muestra el número y el texto para copiar manualmente.

No se piden correo, contraseña, identificación fiscal, pagos ni archivos. César registra el contacto que recibió y completa después los datos necesarios. No habrá chat web ni lectura automática de WhatsApp.

### Necesidades de los usuarios y resultados esperados

Cada fila indica quién necesita una función, qué quiere hacer y qué resultado debe ofrecer el sistema. En los ID, **N** significa **necesidad** y el número identifica cada una.

#### Necesidades de las personas interesadas y los clientes

| ID  | Necesidad del usuario                                                                                                                               | Resultado esperado                                                                                                                                    |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| N01 | Como persona interesada, quiero conocer RYC y contactar por WhatsApp sin crear una cuenta; si lo deseo, quiero registrarme para utilizar el portal. | Página pública con contacto accesible y registro opcional con acceso propio y correo verificado.                                                      |
| N02 | Como solicitante, quiero conocer el costo de la consultoría según el lugar y la propuesta del trabajo antes de decidir.                             | Consulta gratuita en San Carlos o cotización aceptada y pagada fuera; decisión del trabajo registrada.                                                |
| N03 | Como cliente asociado, quiero solicitar una nueva visita y consultar su programación.                                                               | Solicitud revisada por César y atención confirmada.                                                                                                   |
| N04 | Como cliente autorizado, quiero consultar el historial y descargar mis recibos.                                                                     | Información publicada y documentos del cliente correspondiente.                                                                                       |
| N05 | Como cliente, quiero informar un pago por el canal que elegí y consultar su confirmación en el portal si tengo cuenta.                              | Una sola recepción registrada por anticipo, saldo o consultoría; César verifica lo recibido, comunica el resultado y el portal muestra lo autorizado. |
| N06 | Como cliente, quiero recibir mis documentos sin que me obliguen a crear una cuenta.                                                                 | Documentos entregados por el medio acordado y entrega registrada; consulta adicional en el portal si me registro.                                     |
| N07 | Como cliente autorizado, quiero consultar cuánto pagué en un mes o periodo.                                                                         | Resumen de pagos confirmados de mis ubicaciones autorizadas, separado por moneda y enlazado a sus órdenes.                                            |

#### Necesidades de César

| ID  | Necesidad del usuario                                                                                                                               | Resultado esperado                                                                                                                                    |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| N08 | Como César, quiero registrar particulares, empresas y ubicaciones aunque no tengan cuenta.                                                          | Información del negocio centralizada e independiente del registro en el portal.                                                                       |
| N09 | Como César, quiero asociar una cuenta autorizada mediante su ID.                                                                                    | Consulta del historial existente sin duplicar los registros.                                                                                          |
| N10 | Como César, quiero organizar las visitas en una agenda.                                                                                             | Programación con seguimiento y prevención de conflictos.                                                                                              |
| N11 | Como César, quiero registrar el servicio y tratamiento realmente realizados.                                                                        | Plagas, productos, cantidades y recomendaciones conservados por atención.                                                                             |
| N12 | Como César, quiero incorporar información anterior aunque esté incompleta.                                                                          | Historial identificable y sin datos inventados.                                                                                                       |
| N13 | Como César, quiero adjuntar los documentos fiscales emitidos externamente y conservar sus originales.                                               | Facturas, respuestas y representaciones disponibles para las cuentas autorizadas, con seguimiento de correcciones.                                    |
| N14 | Como César, quiero registrar una atención desde celular o computadora reutilizando los datos y retomando lo guardado.                               | Ficha de atención con acciones por tarea, datos precargados, borradores privados y seguimiento sin duplicados.                                        |

#### Necesidades de RYC como empresa

| ID  | Necesidad del usuario                                                                                                                               | Resultado esperado                                                                                                                                    |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| N15 | Como RYC, quiero recibir el sistema y su guía con respaldo comprobado.                                                                              | Entrega validada y posibilidad de restaurar datos y documentos.                                                                                       |

### Registro e inicio de sesión

El portal usa correo y contraseña. El registro público crea cuentas de cliente; César recibe su acceso administrativo durante la configuración.

Una cuenta puede iniciar sesión y editar su perfil sin verificar correo. La verificación se exige para enviar solicitudes y consultar información asociada; el teléfono se exige al solicitar atención. Los correos automáticos son para acceso, y WhatsApp para comunicación comercial.

#### Campos del registro

| Campo | Obligatorio | Regla |
| --- | --- | --- |
| Nombre completo | Sí | Entre 2 y 100 caracteres; permite espacios, tildes, apóstrofos y guiones. |
| Correo electrónico | Sí | Formato de correo, hasta 254 caracteres; único entre las cuentas. Se recortan espacios exteriores y se normaliza para comparar duplicados. |
| Teléfono | No en registro | Permite 8 caracteres; prefijo nacional +506 y separadores habituales.  |
| Contraseña | Sí | Entre 8 y 128 caracteres; permite espacios y caracteres Unicode; admite pegar desde un gestor de contraseñas. |
| Confirmación de contraseña | Sí | Debe coincidir exactamente con la contraseña. |

#### Opciones del login

- Dos campos: correo electrónico y contraseña.
- Botón principal: **Entrar**.
- Control para mostrar u ocultar la contraseña.
- Enlace **Olvidé mi contraseña**.
- Enlace **Crear cuenta**.
- Recuperación mediante enlace de un solo uso enviado al correo, con vencimiento de 30 minutos.
- Cierre de sesión disponible desde el menú de cuenta.
- Inactividad máxima de 60 minutos por sesión.

#### Validación de formularios y seguridad de las cuentas

Esta sección define los mensajes que aparecen al completar formularios y las reglas que protegen el registro, el inicio de sesión y la recuperación del acceso a las cuentas.

##### Mensajes al completar los formularios

La tabla [Mensajes de validación de campos](#mensajes-de-validación-de-campos) está en [Páginas del sistema y su contenido](#páginas-del-sistema-y-su-contenido). Indica qué mensaje aparece cuando falta un dato obligatorio o cuando el correo, el teléfono, una fecha, una cantidad o un archivo no cumple sus reglas.

##### Páginas y funciones de acceso

Las páginas de acceso y los controles dentro del portal se describen por su nombre en [Páginas del sistema y su contenido](#páginas-del-sistema-y-su-contenido):

| Página o función | Dónde se utiliza |
| --- | --- |
| [Inicio de sesión](#inicio-de-sesión) | Página de ingreso; incluye el segundo factor de César. |
| [Crear cuenta](#crear-cuenta) | Página de registro opcional. |
| [Recuperar acceso](#recuperar-acceso) | Página para solicitar el enlace por correo. |
| [Cambiar contraseña por recuperación](#cambiar-contraseña-por-recuperación) | Página que abre el enlace recibido. |
| [Verificación del correo](#verificación-del-correo-en-el-portal) | Aviso y acciones dentro de Inicio del portal. |
| [Seguridad de la cuenta administrativa](#seguridad-de-la-cuenta-administrativa) | Configuración dentro de Mi cuenta de César. |

##### Medidas para proteger las cuentas

- **Limitar los intentos de inicio de sesión:** se permiten hasta cinco intentos fallidos por minuto para una misma combinación de correo y dirección IP. La IP es la dirección de red desde la que llega el intento. Al alcanzar el límite, aparece Demasiados intentos. Espera un minuto y vuelve a intentarlo.
- **Guardar las contraseñas de forma protegida:** se configurará **Laravel 13** para utilizar **Argon2id** al guardar y comprobar las contraseñas, sin almacenarlas como texto legible. Las contraseñas tampoco se incluirán en los registros de errores o diagnóstico.
- **Verificación adicional para César:** además de su correo y contraseña, César ingresa un código temporal de una aplicación autenticadora en su celular. La configuración y los códigos de recuperación se describen en [Seguridad de la cuenta administrativa](#seguridad-de-la-cuenta-administrativa).
- **Separar el acceso del cliente y el administrativo:** el registro público crea cuentas del portal para clientes. El acceso administrativo de César se asigna durante la configuración y nunca se obtiene mediante el registro público.
- **Confirmar el correo antes de usar funciones restringidas:** una cuenta puede iniciar sesión y editar su perfil sin verificarlo. Para solicitar consultoría debe verificar su correo; para consultar el historial de un cliente también necesita una asociación activa y los permisos correspondientes.

### Diseño y comportamiento en dispositivos
#### Dirección visual

Una interfaz clara que presente RYC, facilite el contacto y permita administrar atenciones y consultar servicios. La prioridad de uso será César, que introduce la mayoría de los datos desde celular y computadora por igual. En el portal, una línea de tiempo del historial mostrará fecha, lugar, plagas, tratamiento y recomendaciones de cada atención.

Se utilizará el logo real que facilite RYC. Mientras esté pendiente, el encabezado mostrará el texto **RYC Control de Plagas**.
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
- Encabezados: Manrope, peso 600.
- Texto, formularios y tablas: Source Sans 3, peso 400; etiquetas en peso 600.
- Fuentes servidas desde el proyecto, con alternativa sans-serif del sistema.
- Texto base: 16 px y altura de línea 1.5.
- Etiquetas: 14 px.
- Título principal de una página: 28 px; en celular, 24 px.

#### Login
| Elemento | Definición |
| --- | --- |
| Ubicación | Centrado horizontal y verticalmente cuando el espacio disponible lo permite. |
| Ancho | 100% del espacio disponible, con máximo de 420 px. |
| Alto | Determinado por el contenido. Permite desplazamiento si el formulario supera el alto disponible. |
| Espacio exterior | 16 px en celular; 24 px en pantallas mayores. |
| Espacio interior | 24 px en celular; 32 px desde 640 px de ancho. |
| Radio del contenedor | 12 px. |
| Campos y botón principal | 48 px de alto mínimo. |
| Separación entre etiqueta y campo | 8 px. |
| Separación entre grupos de campos | 16 px. |
| Separación entre encabezado y formulario | 24 px. |
| Error de campo | Debajo del campo, con texto además del color. |
#### Presentación de la administración y el portal
| Elemento | Regla |
| --- | --- |
| Navegación | Desde 1024 px, menú lateral de 240 px y encabezado de 64 px; debajo, menú desplegable. |
| Formularios | Una columna bajo 640 px; hasta dos desde 640 px para campos relacionados. |
| Contenido | Máximo 1280 px; espacios de 16 a 32 px según tamaño. |
| Listados | 20 registros por página; tarjetas en celular y tablas en computadora. Comparación horizontal como vista adicional. |
| Accesibilidad | Áreas táctiles de 44 × 44 px, teclado, etiquetas y foco visible. |
| Registro | Una columna, máximo 520 px; estilo del login. |
| Tareas | Grupos de contacto, lugar, condiciones, programación, trabajo y documentos; datos precargados y siguiente acción clara. |

### Experiencia de uso de César

César utilizará celular y computadora por igual. La administración tendrá las mismas funciones en ambos; las vistas se adaptarán al espacio disponible y conservarán la referencia del cliente, la ubicación y la atención que se está gestionando.

#### Registro por etapas y reutilización

1. **Contacto:** buscar cliente por nombre, teléfono o identificación; elegirlo o guardar el contacto sin exigir una ficha completa.
2. **Lugar:** elegir o crear la ubicación sin salir de la atención; comprobar cliente, provincia, cantón, distrito y dirección antes de cotizar o programar.
3. **Condiciones:** registrar la propuesta y decisión recibida por WhatsApp o portal.
4. **Pago:** revisar el comprobante y movimiento real; confirmar o rechazar en la misma orden.
5. **Atención:** precargar cliente, ubicación y orden; registrar lo realmente utilizado.
6. **Cierre:** publicar el servicio, cobrar saldo, adjuntar documentos y registrar entrega.
7. **Seguimiento:** consultar historial y próxima visita; asociar una cuenta solo si el cliente la desea y está autorizado.

Una coincidencia de nombre o teléfono no fusiona clientes. Se reutilizan solicitudes y productos de catálogo; las cantidades, el tratamiento y las recomendaciones se comprueban para cada atención.

#### Borradores y continuidad

Permiten a César guardar una atención incompleta y terminarla después.

- **Guardado:** primero **Guardar borrador**; después, automático tras **dos segundos sin escribir**, con conexión y sesión válida.
- **Contenido:** privados; referencia, contacto o cliente, tipo y última modificación. Se validan tamaño y tipo al guardar; todos los requisitos al registrar la solicitud o publicar el servicio. Al completarse conservan su referencia.
- **Acciones:** guardar no programa visitas, acepta propuestas, confirma pagos, publica servicios ni entrega documentos.
- **Continuidad:** otro dispositivo recupera la última versión del servidor. Una versión antigua conserva el texto local, impide sobrescribir y muestra **Esta atención cambió en otro dispositivo. Revisa la versión guardada antes de continuar**.
- **Cambios pendientes:** salir exige confirmación. Ante fallos de guardado o sesión vencida, el texto permanece en la pantalla abierta para iniciar sesión y reintentar. No hay modo sin conexión.

**Mensajes:** **Guardando borrador…**, **Borrador guardado** con hora o **No se pudo guardar el borrador. Reintenta antes de salir**.
#### Acciones y estado

Cada atención muestra lo registrado, lo pendiente y la siguiente acción. Programar enlaza visita y solicitud; confirmar dinero recalcula saldo; publicar finaliza el servicio y la visita relacionada. Las acciones se completan en la ficha de atención y sus secciones muestran el resultado actualizado.

César confirma decisiones comerciales, dinero, horarios y tratamiento real. En celular se priorizan el dato principal y la siguiente acción; los grupos extensos se despliegan por tarea. En computadora se usan hasta dos columnas y tablas, manteniendo visible la referencia.

### Empresas, sedes y cuentas

Una **empresa** es la ficha administrativa; una **sede** es una ubicación suya con historial propio. Ambas existen sin cuentas. La asociación vincula una cuenta a la empresa y define las sedes autorizadas.

#### Permisos de consulta y solicitud

El historial incluye visitas, plagas, productos, tratamientos, recomendaciones, pagos, recibos, facturas y próximas visitas.

| Cuenta | Información y solicitudes permitidas |
| --- | --- |
| Principal de empresa | Historial y atención de todas las sedes de esa empresa. |
| De sede | Historial y atención de una sola sede asignada. |
| De cliente particular | Información y atención de las ubicaciones de ese cliente. |
| Sin asociación | Perfil, ID y solicitudes propias; consultoría con correo verificado. Pagos y documentos solo de órdenes originadas en sus solicitudes. |
| Administrativa de César | Gestionar todos los clientes, sedes y atenciones de RYC. |

- Una cuenta se asocia como máximo a un particular o empresa. Una empresa puede tener varias cuentas personales; cada cuenta de sede corresponde a una sola sede.
- La historia empresarial sin sede conocida solo es visible para César y cuentas principales, hasta que César la clasifique.
- Las solicitudes conservan la cuenta que las envió. Tener una solicitud propia no amplía un alcance activo: si la cuenta ya está asociada, se aplican su cliente y sedes incluso sobre órdenes anteriores.
- El servidor comprueba permisos al listar, abrir, informar pagos y descargar; cambiar un ID en la dirección web no amplía acceso.
- El historial pertenece al cliente y ubicación, no a cada cuenta. La cuenta administrativa permanece separada del portal.

#### Ejemplo de acceso por sede
Una empresa tiene Sede A y Sede B:

| Cuenta           | Historial de A | Historial de B |
| ---------------- | -------------- | -------------- |
| Principal        | Sí             | Sí             |
| Cuenta de Sede A | Sí             | No             |
| Cuenta de Sede B | No             | Sí             |
| César            | Sí             | Sí             |
#### Justificación

Las sedes separan tratamientos y documentos por lugar; las credenciales individuales identifican quién solicita o informa pagos. La cuenta principal consulta la empresa y la de sede limita el acceso a su ubicación. 

### Asociación mediante ID

1. La cuenta recibe un UUID v4, visible en **Mi cuenta** con **Copiar ID**.
2. César pega el ID en la ficha; el sistema muestra nombre y correo verificado.
3. Comprueba autorización por WhatsApp o llamada a un número ya conocido del cliente, o registra otra vía verificable acordada. Un ID enviado desde un contacto desconocido no basta.
4. Para empresas elige **Todas las sedes** o **Una sede**, perteneciente a esa empresa; confirma la comprobación y guarda.
5. Se registran responsable, fecha, cuenta, cliente, alcance, sede y canal.

La asociación habilita el historial existente dentro de esos permisos. Cambiar alcance o retirar una asociación conserva el seguimiento; no duplica registros. Clientes con el mismo nombre siguen separados. Los controles y mensajes están en [Ficha del cliente y cuentas autorizadas](#ficha-del-cliente-y-cuentas-autorizadas), dentro de Clientes.

### Consultoría y aceptación del servicio

Enviar una solicitud es gratuito. La **visita inicial de consultoría** es gratuita en todo el **cantón de San Carlos, Alajuela**; fuera se cobra, incluidos otros cantones de Alajuela. El tratamiento posterior tiene su propia propuesta.

**Solicitar nueva visita** permite pedir atención para una ubicación autorizada cuando ya se conoce la necesidad; César confirma condiciones y aceptación antes del trabajo.

#### Formulario de consultoría

Formulario del portal: guarda la solicitud y precarga cuenta y ubicación. El formulario público solo prepara el mensaje descrito en su apartado.

| Campo | Obligatorio | Regla |
| --- | --- | --- |
| Tipo de solicitante | Sí | Particular o empresa. |
| Nombre de contacto | Sí | Inicialmente toma el nombre de la cuenta; entre 2 y 100 caracteres. |
| Nombre de empresa | Para empresas | Entre 2 y 150 caracteres. |
| Teléfono | Sí | 8 digitos, con prefijo y separadores permitidos. |
| Correo de contacto | Sí | Correo verificado de la cuenta, mostrado como solo lectura. |
| Provincia | Sí | Selector del catálogo territorial; inicialmente sin selección. |
| Cantón | Sí | Selector de cantones de la provincia elegida. |
| Distrito | Sí | Selector de distritos del cantón elegido. |
| Dirección del lugar | Sí | Entre 10 y 500 caracteres. |
| Descripción del problema | Sí | Entre 10 y 2000 caracteres. |
| Fecha preferida | No | Fecha presente o futura; expresa una preferencia y César confirma la atención. |

Si la cuenta ya tiene un cliente asociado, se selecciona una ubicación activa dentro de sus permisos y se muestran sus datos territoriales. Una cuenta de sede solo puede elegir la sede asignada; una cuenta principal puede elegir cualquier sede activa de su empresa. Las solicitudes deben corresponder al registro de cliente asociado.

#### Costo de la visita inicial

- César verifica cantón y dirección. San Carlos: **₡0**, sin reporte de pago.
- Fuera: cotización inicial en CRC de **₡15.000 + ₡150 × kilómetros de ida y vuelta + peajes**. César introduce recorrido real desde su salida; no se calcula ruta automáticamente.
- Base y costo por km son configurables. César revisa costos e impuestos antes de enviar cálculo, total final, moneda, lugar y descripción; no agrega cargos ocultos.
- Ajustar exige motivo de 2 a 1000 caracteres. Una cotización aceptada conserva valores e instrucciones; modificarla exige nueva aceptación y revisar pagos.
- Aceptar por WhatsApp o portal conserva decisión, fecha y canal, y crea una sola orden de consultoría. El **100% del pago de la consultoria debe estar confirmado antes de la visita**.
- El costo de consultoría se registra aparte del trabajo y no se descuenta automáticamente del tratamiento.

#### Estados de la consultoría

Los estados cambian por acciones confirmadas de César, con o sin cuenta del cliente. Leer un detalle no cambia el estado.

| Estado | Acción y siguiente estado |
| --- | --- |
| Recibida | Revisar → En revisión; cancelar → Cancelada. |
| En revisión | Confirmar visita → Consultoría programada; cancelar → Cancelada. |
| Consultoría programada | Registrar atención → Consultoría realizada; cancelar antes de atender → Cancelada. |
| Consultoría realizada | Preparar propuesta con lugar, descripción y precio → Pendiente de decisión del trabajo. |
| Pendiente de decisión del trabajo | Registrar decisión y canal → Aceptada o No aceptada. |

La programación puede quedar prevista con pago pendiente, pero iniciar consulta cobrada exige el 100% confirmado. Cancelar registra motivo y conserva pagos y documentos para revisión. Aceptada, No aceptada y Cancelada cierran el seguimiento; corregir exige fecha y motivo y no elimina la solicitud.

#### Cómo se registra la aceptación del trabajo

La propuesta requiere cliente, ubicación, descripción de 10 a 2000 caracteres,  moneda CRC o USD. El total incluye ambas mitades: anticipo del 50% y saldo igual a total menos anticipo.

Aceptar servicio en el portal exige confirmación y autorización sobre la solicitud propia. César puede registrar la respuesta recibida por WhatsApp u otro medio acordado, con fecha y canal.

Aceptar crea una única orden anterior al servicio, con solicitud de origen cuando exista, concepto, descripción, monto, moneda y condiciones. No confirma dinero ni asocia cuentas. Rechazar conserva la decisión y no crea orden del trabajo.

#### Orden y situación financiera

La orden reúne lo acordado con el cliente: servicio, ubicación, precio y condiciones. Su estado —aceptada, en atención, finalizada o cancelada— se controla por separado de los pagos recibidos.

| Estado operativo | Cuándo se registra |
| --- | --- |
| Aceptada | Al aceptar la propuesta. |
| En atención | Al iniciar la visita. |
| Finalizada | Al finalizar el servicio. |
| Cancelada | Al cancelar con motivo. |

Cada transición conserva fecha y responsable. El pago se muestra aparte: **Sin pagos confirmados**, **Pago parcial**, **Pago completo** o **Saldo a favor pendiente de revisión**.

#### Medios e instrucciones de pago

El cliente paga por SINPE, transferencia o efectivo, siguiendo los datos que César comparte por WhatsApp o portal. El sistema registra los pagos; César comprueba que recibió el dinero.

#### Datos del reporte de pago

| Campo | Obligatorio | Regla |
| --- | --- | --- |
| Orden | Sí | Orden autorizada; cliente, ubicación, total y moneda se muestran de solo lectura. |
| Concepto | Sí | Consultoría, anticipo o saldo, según la orden. |
| Monto reportado | Sí | Mayor que cero, hasta dos decimales; moneda igual a la orden. |
| Medio | Sí | SINPE, efectivo o transferencia. |
| Fecha y hora del pago | Sí | Fecha real, no futura; America/Costa_Rica. |
| Referencia bancaria | Para SINPE o transferencia | De 2 a 100 caracteres. |
| Comprobante | Para SINPE o transferencia | PDF, JPG o PNG; máximo de 5 MiB, con tipo real comprobado. |
| Comentario | No | Hasta 1000 caracteres; visible para el cliente autorizado y César. |

El reporte indica la orden, concepto, monto, medio y fecha del pago. SINPE y transferencia requieren referencia y comprobante. Queda pendiente de revisión y se evitan reportes duplicados.

#### Comunicación y seguimiento de los pagos

Los reportes recibidos por WhatsApp o portal se reúnen en la misma orden. César comunica el resultado y registra cuándo y por cuál canal. El portal muestra el estado; sus avisos internos no envían WhatsApp automáticamente.

#### Archivos, permisos y alcance comercial

Los archivos son privados y cada cuenta consulta únicamente lo autorizado. César adjunta recibos y documentos fiscales; el cliente reporta pagos y aporta datos de facturación. Se excluyen la emisión fiscal automática, las pasarelas de pago, la conciliación bancaria automática, los contratos y la integración de conversaciones.

### Clientes, ubicaciones y servicios
#### Cliente particular

| Campo | Obligatorio | Regla |
| --- | --- | --- |
| Nombre completo | Sí | Entre 2 y 100 caracteres. |
| Teléfono principal | Sí | 8 digitos; prefijo y separadores permitidos. |
| Correo de contacto | No | Formato válido; hasta 254 caracteres. Puede registrarse un cliente sin correo. |
| Identificación | No | Hasta 30 caracteres; conserva el formato real facilitado a César. |
| Nota interna | No | Hasta 2000 caracteres. |
| Estado | Sí | Activo o inactivo; inicialmente activo. |

#### Empresa

| Campo                        | Obligatorio | Regla                                                     |
| ---------------------------- | ----------- | --------------------------------------------------------- |
| Razón social                 | Sí          | Entre 2 y 150 caracteres.                                 |
| Nombre comercial             | No          | Hasta 150 caracteres.                                     |
| Identificación de la empresa | No          | Hasta 30 caracteres; se conserva según el documento real. |
| Nombre de contacto principal | Sí          | Entre 2 y 100 caracteres.                                 |
| Teléfono de contacto         | Sí          | 8 digitos; prefijo y separadores permitidos.                                     |
| Correo de contacto           | No          | Formato válido; hasta 254 caracteres.                     |
| Nota interna                 | No          | Hasta 2000 caracteres.                                    |
| Estado                       | Sí          | Activo o inactivo; inicialmente activo.                   |

La identificación no se utiliza para asociar automáticamente una cuenta. La asociación requiere la comprobación indicada en la asociación mediante ID.

#### Ubicación del servicio

- Cliente al que pertenece.
- Nombre de ubicación: entre 2 y 100 caracteres.
- Dirección: entre 10 y 500 caracteres.
- Provincia, cantón y distrito: selectores dependientes del catálogo territorial; se conserva la selección correspondiente al lugar real.
- Indicaciones de acceso: opcionales, hasta 1000 caracteres.
- Estado activo o inactivo.
- Cada visita pertenece a una ubicación; clientes particulares también pueden tener más de una.

#### Servicio realizado

- Cliente y ubicación.
- Visita programada de origen, cuando exista.
- Fecha real de atención.
- Tipo: consultoría, tratamiento o seguimiento.
- Plagas observadas.
- Productos y cantidades realmente utilizados.
- Tratamiento aplicado.
- Recomendaciones para el cliente.
- Observaciones internas de César.
- Próxima atención, cuando César la programe.
- Orden del cobro, pagos confirmados, recibos y documentos fiscales asociados cuando correspondan.

Para tratamientos se requiere al menos una plaga o la justificación de un tratamiento preventivo. Las notas internas permanecen en administración; el portal consulta las recomendaciones y el contenido del servicio destinado al cliente.

Los clientes, empresas, ubicaciones y elementos de catálogo se pueden desactivar conservando el historial. Las correcciones de un servicio ya finalizado registran la fecha y el motivo del cambio.

### Plagas, productos y tratamientos

César mantiene catálogos sencillos de plagas y productos. Cada atención selecciona los elementos utilizados y permite registrar sus detalles reales.

#### Catálogo de plagas

- Nombre: entre 2 y 100 caracteres.
- Descripción: opcional, hasta 1000 caracteres.
- Estado activo o inactivo.

#### Catálogo de productos

- Nombre comercial: entre 2 y 150 caracteres.
- Ingrediente activo: opcional, hasta 150 caracteres.
- Referencia interna o del proveedor: opcional, hasta 100 caracteres.
- Nota descriptiva: opcional, hasta 1000 caracteres.
- Estado activo o inactivo.

#### Registro del tratamiento

- Una o varias plagas seleccionadas.
- Descripción de lo realizado: entre 10 y 2000 caracteres.
- Zona atendida dentro de la ubicación: opcional, hasta 500 caracteres.
- Para cada producto utilizado: producto, cantidad mayor que cero y unidad.
- Unidades: mL, L, g, kg y unidad.
- Método de aplicación: opcional, hasta 500 caracteres; describe la atención real.
- Recomendaciones para el cliente: opcionales, hasta 2000 caracteres.
- Observaciones internas: opcionales, hasta 2000 caracteres.

Las cantidades, productos y métodos se registran a partir de lo que informe César. Este planeamiento no prescribe qué químico ni qué dosis debe aplicarse.

#### Publicación del historial

El portal distingue propuesta, programación y servicio publicado. Solo este último muestra el tratamiento realmente realizado; conserva datos históricos incompletos y excluye notas internas. Publicación y correcciones se especifican en [Servicio y tratamiento realizado](#servicio-y-tratamiento-realizado), dentro de Atenciones.

### Visitas y calendario

César crea y confirma las visitas. El portal permite solicitar atención y consultar la programación confirmada.

#### Datos de una visita

- Cliente.
- Ubicación.
- Tipo: consultoría, tratamiento o seguimiento.
- Fecha y hora de inicio.
- Duración prevista, de 15 a 480 minutos.
- Descripción breve, hasta 500 caracteres.
- Estado: programada, en curso, realizada o cancelada.
- Motivo de cancelación o reprogramación, cuando corresponda.
#### Reglas

- La agenda se muestra en la zona horaria America/Costa_Rica.
- Las visitas nuevas se programan para el presente o el futuro.
- El sistema impide que dos visitas activas de César ocupen el mismo intervalo.
- La duración debe contemplar el tiempo que César necesita para esa atención. Los espacios de traslado se reservan manualmente en la agenda.
- Reprogramar conserva la fecha anterior y el motivo.
- Cancelar conserva la visita y su motivo.
- Los clientes solicitan los cambios y César los confirma en la agenda.
- Una frecuencia definida en días permite sugerir la siguiente fecha; César confirma la creación de la visita siguiente.
- Al finalizar una visita, César registra el servicio realmente realizado.
- Cada atención con cobro se relaciona con su orden aceptada. Iniciar visita comprueba 100% confirmado para consultoría fuera de San Carlos o al menos 50% para el trabajo.
- Las atenciones históricas no se bloquean por no disponer de una orden o de pagos antiguos registrados.

#### Presentación

- Administración: vistas de mes, semana y lista.
- Portal: listado de próximas visitas con fecha, hora, lugar y estado.
- Fechas visibles en formato día/mes/año y horas en formato de 24 horas.
- Calendario construido con FullCalendar Standard.

### Información histórica

La carga inicial será manual y se centrará en los clientes activos, sus ubicaciones y los servicios que César considere relevantes para su seguimiento.

- César crea los registros de clientes y empresas.
- Registra sus servicios anteriores con la fecha real disponible.
- Puede adjuntar los recibos y documentos fiscales originales disponibles, sin inventar archivos ni respuestas de Hacienda.
- Si un documento antiguo de empresa no identifica sede, lo consultan César y la cuenta principal hasta que César lo clasifique.
- Los campos desconocidos se marcan como no registrados.
- El registro histórico indica que fue incorporado a partir de información anterior.
- La carga no exige una cuenta de portal.
- Las cuentas creadas posteriormente consultan esa misma información al asociarse.

### Tecnología, alojamiento y entrega
#### Tecnologías

| Parte | Tecnología |
| --- | --- |
| Aplicación | Laravel 13 y PHP 8.4. |
| Interfaz | Livewire, Blade y Tailwind CSS, con starter kit oficial. |
| Base de datos | MySQL. |
| Autenticación | Herramientas del starter kit, configuradas según las reglas de registro e inicio de sesión. |
| Calendario | FullCalendar Standard. |
| Comprobantes, recibos y documentos fiscales | Archivos en almacenamiento privado y persistente. |
| Correos | Servicio SMTP para verificación y recuperación. |
| Repositorio | GitHub |

Una sola aplicación permite desarrollar las páginas, secciones y formularios junto con la lógica del negocio dentro del mismo proyecto. El starter kit cubre funciones de acceso que serían necesarias en cualquier caso. Las versiones finales de paquetes se fijarán al iniciar la implementación.

#### Alojamiento de la demostración y del piloto

Railway, con un servicio para Laravel, otro para MySQL y almacenamiento persistente para los documentos.

El alojamiento previsto para la demostración y el piloto es Railway. Brian gestionará el despliegue y ambos colaborarán en el repositorio.

El presupuesto objetivo del piloto es de US$20 mensuales para alojamiento. El consumo se comprobará antes de contratar. Dominio y correo requieren cotización.

#### Respaldo y entrega

- Respaldo diario de la base de datos y los documentos.
- Retención de siete copias diarias y cuatro semanales mediante el procedimiento de respaldo que se implemente.
- El archivo de documentos fiscales mantiene su conservación mínima de cinco años; la rotación de respaldos no borra esos originales.
- Copia semanal cifrada fuera del alojamiento, bajo control de RYC.
- Prueba de restauración antes de entregar el sistema.
- Entrega inicial mediante una versión accesible por HTTPS, datos de demostración y una guía breve para César.
- Uso real con datos de clientes después de comprobar permisos, archivos, respaldo y aceptación del negocio.

### Páginas del sistema y su contenido

#### Convenciones de presentación

Las páginas y los formularios aplican las medidas, mensajes y permisos comunes. Cada página agrupa sus funciones y enlaza los campos que utiliza.

| Elemento | Especificación |
| --- | --- |
| Idioma | Español en etiquetas, acciones, mensajes y fechas. |
| Pantalla pequeña | Ancho inferior a 640 px. |
| Pantalla intermedia | Desde 640 px hasta menos de 1024 px. |
| Pantalla amplia | Desde 1024 px. |
| Espacio del contenido | 16 px en pantallas pequeñas; 24 px en intermedias; 32 px en amplias. |
| Caja de los formularios de gestión | Ancho disponible, máximo de 960 px; superficie blanca, espacio interior de 24 px y radio de 12 px. |
| Títulos y acciones | Título al inicio del contenido; acciones al final del formulario. En celular los botones ocupan el ancho disponible y se apilan con 12 px de separación. |
| Campos | Etiqueta visible sobre el control; 8 px entre ambos; 16 px entre grupos. El carácter * identifica los obligatorios y una leyenda explica su significado. |
| Controles de una línea | Altura mínima de 48 px. Correo: campo de correo; teléfono: campo de texto con teclado telefónico; contraseña: campo oculto; cantidades y duración: controles numéricos. |
| Texto extenso | Área de texto con alto inicial de 96 px y ancho del contenedor; permite ampliar el alto. |
| Formularios de dos columnas | Dos columnas de igual ancho desde 640 px, con 16 px de separación; una columna por debajo de ese ancho. Dirección, descripciones y notas ocupan ambas columnas. |
| Listados | Filtros sobre el listado; 20 registros por página; navegación Anterior y Siguiente debajo. Tablas en computadora y tarjetas con los mismos datos y acciones en celular; desplazamiento horizontal como vista adicional de comparación. |
| Confirmaciones | Contenedor centrado, ancho máximo de 420 px, espacio interior de 24 px; descripción de la operación y botones Cancelar y confirmar la acción. Permite desplazamiento vertical. |
| Mostrar u ocultar contraseña | Control al final del campo; cambia entre Mostrar contraseña y Ocultar contraseña sin alterar el valor. |
| Guardado | El botón muestra Guardando… y queda inhabilitado mientras se procesa el envío. Un envío repetido no crea otra solicitud, visita, asociación o recibo. |
| Validación | Error debajo del campo, en el color de error y con texto; se conservan los valores y el foco pasa al primer campo inválido. |
| Foco | Contorno visible de 2 px en el verde principal, separado 2 px del control. |
| Estado inicial | Se muestran los datos disponibles; los campos opcionales sin valor permanecen vacíos. |
| Carga de información | Se muestra Cargando… en el área que recibe datos; los controles dependientes se habilitan cuando termina la carga. |
| Sin resultados | No hay registros para mostrar. Si hay filtros, se ofrece Limpiar filtros. |
| Error general | No se pudo completar la operación. Inténtalo de nuevo. Se conserva el contenido cuando corresponde. |
| Operación completada | Confirmación acorde a la acción: Contacto guardado, Pago confirmado, Visita programada o Servicio publicado. La vista muestra el registro actualizado. |
| Falta de autorización | No tienes permiso para consultar esta información. No se muestra el contenido solicitado. |
| Sesión finalizada | Tu sesión terminó. Inicia sesión para continuar; los cambios aún no guardados permanecen en la pantalla mientras siga abierta. |

Acceso en una columna: medidas de [Login](#login); registro de 520 px. Recuperación, cambio de contraseña y segundo factor usan el contenedor del login.

#### Mensajes de validación de campos

Los límites indicados entre llaves se sustituyen por los valores de la tabla del campo correspondiente.

| Condición                                         | Mensaje                                                             |
| ------------------------------------------------- | ------------------------------------------------------------------- |
| Campo obligatorio vacío                           | Completa este campo.                                                |
| Correo incorrecto                                 | Escribe un correo válido.                                           |
| Texto fuera de un intervalo                       | Escribe entre {mínimo} y {máximo} caracteres.                       |
| Texto que supera un máximo                        | No superes {máximo} caracteres.                                     |
| Teléfono inválido                                 | Escribe un teléfono de entre 8 y 15 dígitos.                        |
| Opción inválida o ajena al cliente autorizado     | Selecciona una opción válida.                                       |
| Cantidad o monto no positivo                      | Escribe un número mayor que cero.                                   |
| Duración fuera de límites                         | Escribe una duración de entre 15 y 480 minutos.                     |
| Frecuencia inválida                               | Escribe un número entero de días entre 1 y 365.                     |
| Fecha preferida o programación nueva en el pasado | Selecciona hoy o una fecha futura.                                  |
| Fecha de atención o documento en el futuro        | La fecha no puede ser futura.                                       |
| Formato de fecha o de hora inválido               | Escribe una fecha y hora válidas.                                   |
| Comprobante o recibo no permitido                 | Adjunta un archivo PDF, JPG o PNG.                                  |
| Documento fiscal no permitido                     | Adjunta un XML original o un PDF de representación, según el campo. |
| Archivo demasiado grande                          | El archivo no puede superar 5 MiB.                                  |
| Final de bloqueo anterior o igual al inicio       | El final debe ser posterior al inicio.                              |

Los opcionales vacíos no generan error. Los valores introducidos cumplen formato y límites; al registrar en el sistema se comprueban también en servidor. El borrador admite datos incompletos según sus reglas. El [Formulario de contacto por WhatsApp](#formulario-de-contacto-por-whatsapp) solo prepara el mensaje y no registra datos.

#### Navegación

| Área | Opciones del menú, en orden |
| --- | --- |
| Pública | Servicios; Cómo trabajamos; Zonas; Contacto; Contactar por WhatsApp; Ver mi historial. |
| Portal | Inicio; Mis atenciones; Pagos y documentos; Mi cuenta; Contactar por WhatsApp. |
| Administración | Inicio; Atenciones; Clientes; Calendario; Catálogos; Cobros y documentos; Configuración; Mi cuenta. |
| Cuenta | Cerrar sesión. |

RYC al inicio del encabezado. En administración y portal, el menú lateral permanece visible desde 1024 px; debajo, **Menú** lo abre/cierra, una selección lo cierra y Escape también. La página pública utiliza el encabezado descrito en [Página pública de RYC](#página-pública-de-ryc).

Historial y próximas visitas requieren verificación y asociación activa; solicitudes, pagos y documentos usan los permisos generales. Sin asociación: **Aún no tienes un historial asociado. Comunica tu ID a César si ya has recibido servicios.**

#### Cómo se organiza cada página

Los encabezados de página indican áreas a las que se puede entrar. Debajo se describen las secciones, listados y formularios que contiene cada una. Una acción como aceptar, programar, confirmar un pago o adjuntar un archivo se completa en la página y el registro donde se abrió.

El portal utiliza **Inicio, Mis atenciones, Pagos y documentos y Mi cuenta**. César utiliza **Inicio, Atenciones, Clientes, Calendario, Catálogos, Cobros y documentos, Configuración y Mi cuenta**. Mi cuenta se comparte entre ambas áreas con los permisos correspondientes.

| Área | Página | Contenido |
| --- | --- | --- |
| Pública | [Página pública de RYC](#página-pública-de-ryc) | Presentación, servicios, zonas y formulario para preparar WhatsApp. |
| Acceso | [Inicio de sesión](#inicio-de-sesión) | Correo, contraseña y segundo factor de César dentro del ingreso. |
| Acceso | [Crear cuenta](#crear-cuenta) | Registro opcional. |
| Acceso | [Recuperar acceso](#recuperar-acceso) | Solicitud del enlace por correo. |
| Acceso | [Cambiar contraseña por recuperación](#cambiar-contraseña-por-recuperación) | Nueva contraseña desde el enlace recibido. |
| Portal | [Inicio del portal](#inicio-del-portal) | Resumen, accesos rápidos y aviso de verificación de correo. |
| Portal | [Mis atenciones](#mis-atenciones) | Solicitudes, propuestas, próximas visitas e historial. |
| Portal | [Pagos y documentos](#pagos-y-documentos) | Órdenes, reportes, resumen de pagos, datos fiscales y descargas. |
| Administración | [Inicio administrativo](#inicio-administrativo) | Visitas del día, pendientes y borradores. |
| Administración | [Atenciones](#atenciones) | Contactos, solicitudes y ficha completa de cada atención. |
| Administración | [Clientes](#clientes) | Listado, ficha, ubicaciones, asociaciones e historial anterior. |
| Administración | [Calendario](#calendario) | Visitas, programación y bloqueos de agenda. |
| Administración | [Catálogos](#catálogos) | Plagas y productos. |
| Administración | [Cobros y documentos](#cobros-y-documentos) | Verificación de pagos, recibos, documentos fiscales y entregas. |
| Administración | [Configuración](#configuración) | Tarifas, medios de cobro y contacto público. |
| Compartida | [Mi cuenta](#mi-cuenta) | Perfil e ID; seguridad adicional de César. |

**Uso dentro de una página:** los formularios largos se despliegan en su sección y las confirmaciones breves usan un diálogo. Guardar o cancelar conserva el registro abierto y los filtros. En celular las secciones se apilan; en computadora aprovechan el espacio disponible. Abrir un listado general o un acceso rápido utiliza los mismos registros y permisos.

#### Página pública y acceso

##### Página pública de RYC

**Contiene:** presentación de RYC, servicios, zonas, forma de trabajo y contacto. El formulario para preparar el mensaje de WhatsApp pertenece a esta misma página.

**Acceso, contenido y presentación**

- Público; contenido y orden de [Página pública y contacto por WhatsApp](#página-pública-y-contacto-por-whatsapp), con estilos comunes.
- Presentación de una columna; desde 1024 px, texto/foto en dos si hay imagen autorizada. No expone datos de clientes ni sustituye condiciones.
- Encabezado público: identificación, navegación, WhatsApp y **Ver mi historial**. En celular, **Menú** despliega enlaces sin tapar controles; contacto accesible.

**Acciones y navegación**

- Enlaces internos llevan a sus secciones; foco y teclado siguen el orden del contenido.
- **Contactar por WhatsApp** usa número revisado y saludo; **Preparar mi consulta** despliega el [Formulario de contacto por WhatsApp](#formulario-de-contacto-por-whatsapp) en la misma página, **Ver mi historial** → [Inicio de sesión](#inicio-de-sesión), **Crear cuenta** → [Crear cuenta](#crear-cuenta).

**Requisitos para publicar**

- Solo contenido aprobado por César. Sin número autorizado y comprobado en ambos dispositivos se bloquea publicar el contacto.

###### Formulario de contacto por WhatsApp

**Acceso, campos y distribución**

- Público. Campos, reglas y acciones de [Formulario breve para preparar el mensaje](#formulario-breve-para-preparar-el-mensaje).
- Una columna, máximo 640 px; controles comunes.

**Acciones y alternativas de contacto**

- **Continuar en WhatsApp** valida en navegador y abre el mensaje codificado al número autorizado; no guarda una solicitud.
- **Contactar sin formulario** prepara saludo sin exigir campos; **Copiar mensaje** valida y copia. Si falla, muestra texto para copia manual y número.

**Instrucciones y mensajes**

- Indicar que debe revisar y enviar en WhatsApp; nunca mostrar **Solicitud recibida** o **Visita confirmada** por abrir, copiar o regresar.

##### Inicio de sesión

**Contiene:** correo, contraseña y enlaces para crear cuenta o recuperar acceso. César completa el segundo factor dentro de este mismo ingreso.

**Acceso y presentación**

- Público.
- Orden: RYC, **Iniciar sesión**, correo, contraseña, **Entrar**, recuperación y registro.

**Campos**

- Correo obligatorio y vacío: formato válido, máximo 254 caracteres.
- Contraseña obligatoria, vacía y oculta, con **Mostrar contraseña**.

**Acciones y navegación**

- **Entrar** o Enter envían.
- César introduce su código de segundo factor dentro del mismo inicio de sesión y después entra al Inicio administrativo. El cliente entra al Inicio del portal; si falta verificar su correo, allí se muestra el aviso correspondiente.
- **Volver a RYC** abre la landing; **Contactar por WhatsApp** no exige sesión.

**Mensajes de error**

- Error: **El correo o la contraseña no coinciden.**
- Exceso de fallos: **Demasiados intentos. Espera un minuto y vuelve a intentarlo.**

###### Código de segundo factor al ingresar

**Acceso después del inicio de sesión**

- Después del login: código y **Verificar**, o **Usar código de recuperación** con su campo.

- Error: **El código no es válido.**

##### Crear cuenta

**Contiene:** el formulario para crear una cuenta opcional y los mensajes de sus campos.

**Acceso, campos y distribución**

- Público, una columna; campos en el orden de [Campos del registro](#campos-del-registro), con sus reglas.
- Nombre, correo y teléfono de una línea; contraseñas ocultas con opción de mostrarlas.

**Acciones y resultado**

- **Crear cuenta** registra los datos; **Ya tengo cuenta** abre [Inicio de sesión](#inicio-de-sesión).
- Guardar crea la cuenta de portal e ID y abre Inicio del portal con el aviso para verificar el correo; no crea empresa ni autoriza historial previo.

**Mensajes de validación**

- Mensajes: **Usa entre 8 y 128 caracteres.**, **Las contraseñas no coinciden.** o **Este correo ya está registrado. Inicia sesión o recupera tu acceso.**

##### Recuperar acceso

**Contiene:** el correo para solicitar el enlace de recuperación y la respuesta del envío.

**Acceso**

- Público.

**Campo del formulario**

- Campo **Correo electrónico** obligatorio, vacío, válido y de hasta 254 caracteres.

**Acciones y navegación**

- **Enviar enlace**; **Volver a iniciar sesión** → [Inicio de sesión](#inicio-de-sesión).

**Mensaje de respuesta**

- Respuesta para cualquier correo: **Si el correo corresponde a una cuenta, recibirás un enlace para recuperar el acceso.**

##### Cambiar contraseña por recuperación

**Contiene:** nueva contraseña y confirmación; se abre desde el enlace de recuperación.

**Acceso**

- Enlace de recuperación válido.

**Campos**

- **Nueva contraseña** y **Confirmar contraseña**, obligatorias y vacías; reglas de registro.

**Acciones y resultado**

- **Guardar contraseña**; **Volver a iniciar sesión** → [Inicio de sesión](#inicio-de-sesión).
- Guardar invalida enlace y sesiones anteriores, muestra **Contraseña actualizada** y abre [Inicio de sesión](#inicio-de-sesión).

**Mensaje de error**

- Vencido o usado: **El enlace de recuperación no es válido. Solicita uno nuevo.**

#### Portal del cliente

##### Inicio del portal

**Contiene:** resumen de la cuenta, servicios, próxima visita, pagos y accesos rápidos. El aviso de correo sin verificar aparece dentro de Inicio.

**Opciones según la cuenta**

- Cuenta asociada: **Solicitar nueva visita** y accesos a Solicitudes, Próximas visitas e Historial dentro de **Mis atenciones**, y a **Pagos y documentos**.
- Sin asociación: estado del vínculo y Mi cuenta para copiar ID; órdenes propias según los permisos generales.
- Sin verificar: aviso de verificación en Inicio; enviar solicitudes o consultar información asociada exige verificar el correo.

**Contenido y presentación**

- Nombre, **Solicitar consultoría**, **Contactar por WhatsApp** y texto **Visita inicial gratuita en San Carlos; fuera del cantón se cotiza.**
- Resumen con últimos servicios, próxima visita y pagos del periodo autorizado; sin datos, explicación de asociación.
- Tarjetas: una columna en celular, dos desde 640 px, separación de 16 px.

###### Verificación del correo en el portal

**Acceso y permisos**

- Cuenta autenticada sin correo verificado.
- El perfil sigue disponible; solicitudes e información asociada requieren verificación.

**Datos que se muestran**

- Muestra correo e instrucción para revisar el mensaje.

**Acciones y resultado**

- **Reenviar correo de verificación**, **Mi cuenta** → [Mi cuenta](#mi-cuenta) y **Cerrar sesión**.
- Verificar habilita las funciones correspondientes y actualiza Inicio del portal.

**Plazos y mensaje de error**

- Reenvío inhabilitado por 60 segundos con espera visible. Enlace de 60 minutos para esa cuenta.
- Error: **El enlace de verificación no es válido. Solicita uno nuevo.**

##### Mis atenciones

**Contiene:** Solicitudes, Próximas visitas e Historial, como secciones de esta misma página. Abrir una atención despliega su detalle; desde él se consultan propuesta, pagos y documentos autorizados. Los formularios de nueva solicitud y de cambios se abren en la sección correspondiente.

###### Solicitudes y seguimiento del cliente

**Acceso y permisos**

- Solo solicitudes propias.
- El cliente no cambia estados administrativos.

**Datos, filtros y detalle**

- Datos: fecha, tipo, lugar, estado y **Ver detalle**.
- Filtros: Consultoría/Nueva visita y estado; **Limpiar filtros**.
- Detalle: datos enviados, costo, decisiones y programación.

**Acciones y resultado**

- Costo pendiente: **Aceptar costo de consultoría** o **No aceptar costo**, confirmando total y lugar. Aceptar crea una orden; **Ir a pagos** despliega sus pagos dentro del detalle. Rechazar conserva resultado sin orden ni atención realizada.
- **Consultar por WhatsApp** incluye referencia; las decisiones externas se registran en la misma solicitud.

###### Formulario de consultoría del portal

**Acceso**

- Cuenta con correo verificado.

**Campos y reglas de ubicación**

- Campos y orden de [Formulario de consultoría](#formulario-de-consultoría).
- [Empresa](#empresa) muestra su nombre obligatorio. Cuenta asociada: cliente fijo y ubicación activa autorizada; territorio y dirección de solo lectura.
- Sin asociación: provincia, cantón, distrito y dirección editables. Cambiar provincia limpia cantón/distrito; cambiar cantón limpia distrito.

**Acciones y resultado**

- **Enviar solicitud** guarda Recibida y muestra su detalle dentro de Mis atenciones.
- **Consultar por WhatsApp** usa referencia, tipo y lugar guardados; no repite la solicitud ni incluye datos de pago o documentos.

**Texto informativo**

- Texto: **Enviar la solicitud no tiene costo. La visita inicial es gratuita en el cantón de San Carlos; fuera de ese cantón se cotiza y se paga antes de realizarla. La fecha indicada es una preferencia.**

###### Formulario de nueva visita

**Acceso y datos fijos**

- Cuenta verificada y asociada; cliente y contacto de solo lectura.

**Campos del formulario**

| Campo | Control | Obligatorio | Valor inicial y regla |
| --- | --- | --- | --- |
| Ubicación | Selector | Sí | Solo ubicaciones activas autorizadas. Si existe una sola, se precarga; si hay varias, inicia sin selección. |
| Teléfono de contacto | Texto con teclado telefónico | Sí | Teléfono de la cuenta si existe; hasta 20 caracteres y de 8 a 15 dígitos. |
| Descripción de la atención requerida | Área de texto | Sí | Vacía; entre 10 y 2000 caracteres. |
| Fecha preferida | Fecha | No | Vacía; presente o futura; no reserva el calendario. |

**Acciones y resultado**

- **Enviar solicitud** guarda Recibida y muestra su detalle en Mis atenciones; **Cancelar** cierra el formulario y conserva la sección Solicitudes sin guardar.
- **Consultar por WhatsApp** usa la referencia guardada; no registra otra solicitud.

**Mensajes**

- Sin ubicaciones activas: **Contacta a César para registrar o activar el lugar de atención.**
- Texto: **Enviar la solicitud es gratuito. César confirmará la programación y las condiciones del servicio.**

###### Propuesta del trabajo y decisión del cliente

**Acceso**

- Cuenta solicitante autorizada.

**Datos que se muestran**

- Muestra propuesta, lugar, total, moneda, anticipo, saldo y decisión.
- Documentos disponibles desde que César los adjunta, incluso antes del trabajo.

**Acciones y resultado**

- Solo pendientes: **Aceptar servicio** o **No aceptar**.
- Confirmar registra decisión y fecha una vez. Aceptar crea orden y muestra referencia, anticipo y saldo; **Ir a pagos** despliega los pagos de esa orden en el mismo detalle.
- **Completar datos de facturación** envía datos a revisión.
- **Consultar por WhatsApp** incluye referencia. Registrar una respuesta externa cierra la misma decisión pendiente.

**Confirmaciones**

- Confirmaciones: **¿Confirmas que aceptas este servicio por el monto indicado?** / **¿Confirmas que no deseas contratar este servicio?**; **Cancelar** no cambia nada.

###### Próximas visitas y solicitud de cambios

**Datos que se muestran**

- Visitas autorizadas: fecha, hora, ubicación, tipo, duración y estado; canceladas identificadas.

**Solicitud de cambios**

- Programada ofrece **Solicitar cambio**: tipo Reprogramación/Cancelación, motivo de 2 a 1000 caracteres y fecha preferida opcional, presente o futura, solo al reprogramar.
- **Enviar solicitud** muestra **Cambio solicitado** y conserva la visita hasta revisión de César.

**Restricciones**

- En curso o Realizada no permite cambios de programación desde portal.

###### Historial de servicios del cliente

**Presentación, filtros y detalle**

- Línea de tiempo de más reciente a antigua; filtros ubicación y fechas, **Aplicar filtros** y **Limpiar filtros**.
- Cada atención: fecha, ubicación, tipo y **Ver detalle**; detalle con plagas, tratamiento, productos/cantidades/unidades, recomendaciones y recibos.

**Mensajes para datos faltantes**

- Sin dato: **No registrado**; sin fecha: **Fecha no registrada**, al final de la lista.

**Permisos y publicación**

- Solo servicios publicados y autorizados; sin notas internas. La deuda no oculta un tratamiento publicado.
- Historia empresarial sin sede: permisos de [Empresas, sedes y cuentas](#empresas-sedes-y-cuentas).

##### Pagos y documentos

**Contiene:** secciones Pagos y Documentos. El cliente consulta su resumen, abre una orden y despliega sus reportes, comprobantes y datos de facturación en ese detalle. Los mismos registros pueden consultarse desde Mis atenciones, según sus permisos.

###### Pagos y reportes del cliente

**Acceso, datos y consulta**

- Cuenta verificada con permisos generales. Datos: orden, lugar, concepto, total, confirmado, pendiente, saldo y **Ver detalle**; filtros lugar, concepto y situación.
- Detalle: condiciones, instrucciones, reportes y documentos. **Consultar por WhatsApp** ofrece la alternativa de contacto.

**Reportar y corregir pagos**

- **Informar pago**: campos y reglas de [Datos del reporte de pago](#datos-del-reporte-de-pago); orden fijo, concepto/medio, monto/fecha-hora, referencia, comprobante y comentario.
- Efectivo no exige referencia/archivo; al cambiar medio se confirma retirar el adjunto no enviado.
- **Enviar reporte** o **Cancelar**; mensaje **Pago reportado. César debe confirmar que recibió el dinero.**
- Pendiente/Confirmado de solo lectura; Rechazado ofrece **Reportar corrección**, mostrando motivo y reporte anterior.

**Avisos**

- Avisos: fecha, asunto, Leído/No leído, **Ver detalle** y **Marcar como leído**. No hay pago automático.

**Consulta por periodo**

**Resumen de pagos:** mes/año actual o rango de fechas, ubicación autorizada, **Aplicar**, **Limpiar filtros**. Sumar confirmados por fecha real de recepción en America/Costa_Rica, separados en CRC y USD, con detalle de orden. Pendientes, rechazados y facturas no se suman.

Correcciones usan monto y fecha vigentes con seguimiento; cambio de alcance recalcula lo autorizado. Saldo a favor no presume devolución. Sin datos: **No hay pagos confirmados en este periodo**. No convierte monedas ni es reporte tributario.

###### Datos de facturación de la orden

- **Completar datos de facturación** precarga orden; **Enviar datos** los deja a revisión de César.

**Completar datos de facturación** abre los siguientes campos, en este orden. César los revisa antes de emitir con la herramienta externa; no se exigen para crear una cuenta o registrar un cliente sin facturación. Su obligatoriedad fiscal concreta debe validarse.

| Campo | Control y regla |
| --- | --- |
| Nombre o razón social | Texto obligatorio, entre 2 y 150 caracteres. |
| Tipo de identificación | Selector: física, jurídica, DIMEX, NITE u otra identificación admitida por la herramienta externa. |
| Número de identificación | Texto, hasta 30 caracteres; requerido cuando el tipo lo exija; conserva ceros iniciales. |
| Correo para documentos | Correo válido, hasta 254 caracteres; se recoge según el procedimiento externo de entrega. |
| Provincia, cantón y distrito | Selectores dependientes, para dirección nacional. |
| Dirección detallada | Texto de 10 a 500 caracteres. |
| Información adicional para el emisor | Texto opcional, hasta 1000 caracteres. |

Enviar estos datos no cambia automáticamente la razón social ni la identificación maestra del cliente.

###### Documentos y descargas del cliente

**Datos y filtros**

- Datos: tipo, referencia, fecha, orden/servicio, ubicación, monto, moneda, estado fiscal y acciones.
- Filtros: tipo, ubicación y fechas; **Aplicar filtros**, **Limpiar filtros**.

**Descargas**

- Recibo: **Descargar recibo**. Factura: **Ver PDF**, **Descargar XML** y **Descargar respuesta** si existe; correcciones relacionadas conservan originales.

**Permisos y entrega**

- Estado fiscal según los documentos adjuntos y datos faltantes según [Información histórica](#información-histórica); cada descarga aplica permisos de cliente, sede u orden propia.
- Detalle con entregas autorizadas; disponibilidad en portal no demuestra entrega por WhatsApp.

#### Administración de César

##### Inicio administrativo

**Contiene:** visitas de hoy, solicitudes, pagos, documentos pendientes y borradores. Las acciones rápidas abren los formularios de la tarea elegida.

**Datos y orden de los bloques**

- César; bloques en este orden:

| Bloque | Datos y acceso |
| --- | --- |
| Visitas de hoy | Hora, cliente, lugar y estado; **Abrir atención** o **Iniciar visita** permitido. |
| Solicitudes pendientes | Solicitudes del portal y contactos recibidos por WhatsApp que César guardó. |
| Pagos por verificar y saldos al cierre | Orden, cliente, monto y moneda; **Revisar pago** abre la [Revisión de pagos recibidos](#revisión-de-pagos-recibidos) dentro del detalle de la orden. |
| Documentos pendientes | Referencia y pendiente de respuesta/entrega; **Abrir documentos**. |
| Continuar borradores | Referencia, contacto/cliente y última modificación; **Continuar**. |

**Acciones del encabezado**

- Encabezado: **Registrar contacto**, **Buscar cliente** y **Programar visita**.

**Presentación y origen de los registros**

- Una columna en celular y dos desde 1024 px, con las mismas funciones. Solo datos guardados en servidor; abrir WhatsApp desde el formulario público no crea filas.

##### Atenciones

**Contiene:** contactos y solicitudes, consultorías, nuevas visitas y servicios realizados. El listado se organiza por tipo y estado. Al abrir un registro, César trabaja en una ficha con Contacto y lugar, Propuesta, Programación, Pagos, Servicio y Documentos; la referencia, cliente, ubicación y siguiente acción permanecen visibles.

Los formularios se despliegan dentro de la ficha. Guardar, confirmar o cancelar conserva la atención y los datos; no exige volver al listado para continuar. Los listados generales de calendario, cobros y documentos acceden a esos mismos registros.

###### Registro rápido de un contacto

**Acceso y búsqueda del cliente**

- César; desde Inicio administrativo, Atenciones o la ficha del cliente. **Buscar cliente** por nombre, teléfono o identificación; desde ficha se precarga cliente. Coincidencia no asocia cuentas.

**Campos y requisitos**

- Nombre, teléfono y motivo obligatorios para registrar; lugar completo antes de cotizar/programar.

| Campo, en orden | Obligatorio | Regla y valor inicial |
| --- | --- | --- |
| Cliente existente | No al primer contacto | Selector con búsqueda; vacío salvo al abrir desde su ficha. Solo clientes activos para atención nueva. |
| Nombre del contacto | Sí | De 2 a 100 caracteres; se precarga al elegir cliente, editable si llama otro contacto. |
| Teléfono de contacto | Sí | Hasta 20 caracteres y de 8 a 15 dígitos; se precarga si existe. |
| Lugar indicado | No al primer contacto | Vacío o dato conocido; hasta 500 caracteres. No se trata como ubicación verificada. |
| Motivo de la consulta | Sí | De 10 a 2000 caracteres; texto recibido por César. |
| Fecha preferida | No | Hoy o una fecha futura; no reserva una visita. |
| Origen | Sí | **WhatsApp**, **Llamada**, **Presencial** u **Otro medio acordado**; inicia en WhatsApp. Otro exige descripción de 2 a 100 caracteres. |

**Guardado y borradores**

- **Guardar contacto** valida esos datos, guarda Recibida con referencia, origen y fecha y muestra la ficha de esa atención en Atenciones, conservando lo ingresado. No crea automáticamente cliente, empresa, cuenta, lugar definitivo, orden, pago o visita.
- **Guardar borrador** según sus reglas; al completarlo mantiene referencia. **Cancelar** pregunta si hay cambios pendientes.

**Reutilización y seguimiento**

- Cliente activo y ubicación completa se eligen o crean desde atención reutilizando contacto antes de cotizar/programar.
- Coincidencias: **Abrir registro existente** / **Continuar como contacto distinto**, sin fusión automática.
- Abrir WhatsApp del contacto no envía documentos ni cambia seguimiento.

**Presentación por dispositivo**

- Celular: una columna y acciones apiladas. Computadora: hasta dos columnas; motivo a todo el ancho.

###### Consultorías y propuesta del trabajo

**Listado, filtros y detalle**

- Datos: fecha, contacto, tipo, empresa, lugar, origen Portal/WhatsApp/registro de César, estado y **Ver detalle**. Filtros: estado, tipo y contacto/empresa. **Registrar contacto** despliega el [Registro rápido de un contacto](#registro-rápido-de-un-contacto) en Atenciones.
- Detalle con solicitud, lugar, cotización, orden, pagos, visita y decisiones.

**Acciones disponibles**

- **Revisar solicitud**, **Revisar costo**, **Programar consultoría**, **Registrar consultoría realizada**, **Preparar propuesta**, **Registrar decisión**, **Cancelar consultoría**.

**Requisitos y correcciones**

- Usar campos y reglas de [Costo de la visita inicial](#costo-de-la-visita-inicial), [Estados de la consultoría](#estados-de-la-consultoría) y [Cómo se registra la aceptación del trabajo](#cómo-se-registra-la-aceptación-del-trabajo). Completar cliente y ubicación antes de cotizar/programar; lectura y selección de cliente no cambian estados ni asocian cuentas.
- Cancelar antes de atender exige motivo de 2 a 1000 caracteres. Correcciones conservan fecha y motivo.

**Propuestas, decisiones y comunicación**

- Compartir propuesta por WhatsApp con contacto autorizado y registrar envío; también visible a la cuenta solicitante autorizada si existe.
- Decisión: resultado, fecha real, canal Portal/WhatsApp/Llamada/Presencial/Otro medio acordado y nota opcional de hasta 1000 caracteres. Repetir no crea otra orden.
- **Preparar mensaje** copia referencia, lugar y condiciones elegidas; no envía ni confirma recepción. Iniciar o registrar consulta realizada aplica el pago requerido de [Programación y estado de una visita](#programación-y-estado-de-una-visita).

###### Nuevas visitas y cambios por revisar

**Datos del listado**

- Datos: fecha, cliente, ubicación, tipo Nueva visita/Cambio de visita, preferencia, estado y **Ver detalle**.

**Estados**

- Estados de nueva visita: Recibida, En revisión, Programada o Cancelada. Estados de cambio: Recibida, En revisión, Aplicada o No aplicada.

**Acciones y resultado**

- **Revisar solicitud**, **Programar visita**, **Aplicar cambio**, **No aplicar**; cancelar o no aplicar exige motivo de 2 a 1000 caracteres.
- Programar enlaza una sola visita. Trabajo nuevo requiere propuesta aceptada, orden y condiciones de cobro.
- Revisar no modifica agenda; aplicar registra cambio/cancelación y resultado en portal.

###### Programación y estado de una visita

**Campos y distribución**

| Campo | Control | Obligatorio | Valor inicial y regla |
| --- | --- | --- | --- |
| Cliente | Selector | Sí | Sin selección; solo clientes activos. |
| Ubicación | Selector dependiente | Sí | Inhabilitado hasta elegir cliente; solo ubicaciones activas de ese cliente. |
| Tipo | Selector | Sí | Consultoría, Tratamiento o Seguimiento; sin selección al crear. |
| Orden de cobro | Selector dependiente | Para atención nueva con cobro | Orden aceptada del mismo cliente y ubicación; sin selección al crear. |
| Fecha y hora de inicio | Fecha y hora | Sí | Vacía al crear; presente o futura para programación nueva. |
| Duración prevista | Número entero | Sí | Vacía; entre 15 y 480 minutos. |
| Descripción | Área de texto | No | Vacía; máximo de 500 caracteres. |
| Estado | Texto de solo lectura | Sí | Programada al crear; cambia mediante las acciones autorizadas. |

- Filas: cliente/ubicación; tipo/duración; orden; fecha/hora; descripción. Mostrar pago requerido y confirmado.
- Desde solicitud, cliente y ubicación precargados y fijos.

**Acciones según el estado**

- **Guardar visita** o **Cancelar**.
- Programada: **Iniciar visita**, **Reprogramar**, **Cancelar visita**.
- En curso: **Finalizar atención**, registrando el servicio real. Realizada/Cancelada conserva seguimiento.
- Reprogramar: inicio, duración y motivo de 2 a 1000 caracteres. Cancelar exige confirmación y ese motivo; corregir finalizados exige motivo.

**Validaciones de agenda y cobro**

- Conflictos y estados según [Visitas y calendario](#visitas-y-calendario). Mensaje: **Ese horario se superpone con otra visita o bloqueo de agenda.**
- Iniciar aplica las reglas de cobro de [Visitas y calendario](#visitas-y-calendario); si falta: **Falta confirmar el pago requerido para iniciar esta atención.**
- La misma comprobación se aplica al finalizar/publicar una atención nueva con cobro sin inicio registrado; no puede evitarse pasando directamente a publicación.

###### Servicio y tratamiento realizado

**Listado y filtros**

- Datos: fecha, cliente, ubicación, tipo, estado y **Ver detalle**; filtros cliente, ubicación, tipo y fechas.

**Campos, grupos y distribución**

- Grupos: Datos de atención, Plagas y productos, Tratamiento, Recomendaciones, Observaciones internas.
- Datos de [Servicio realizado](#servicio-realizado): para nuevos registros son obligatorios cliente, ubicación, fecha real no futura y tipo. Desde visita se precargan cliente, ubicación y orden.
- Plagas: selección múltiple; sin plagas, Tratamiento exige **Preventivo** y justificación de 10 a 2000 caracteres.
- Productos: **Añadir producto** y **Quitar fila**, con producto, cantidad decimal positiva y unidad. Límites, unidades y textos de [Registro del tratamiento](#registro-del-tratamiento); descripción obligatoria para Tratamiento. No se exige químico si no se utilizó.
- Celular: producto en grupo vertical; computadora: tabla. Catálogo evita reescribir nombres, pero no copia cantidades ni tratamientos de otras atenciones.

**Borradores, publicación y correcciones**

- **Guardar borrador** / **Continuar borrador** según [Borradores y continuidad](#borradores-y-continuidad).
- **Finalizar y publicar** confirma y valida datos y condición de inicio; publica servicio, marca visita Realizada y muestra saldo para cobro.
- **Corregir servicio** exige motivo de 2 a 1000 caracteres y conserva fecha y seguimiento.

**Reglas de cobro y privacidad**

- Atención nueva con cobro aplica orden y regla de inicio [Programación y estado de una visita](#programación-y-estado-de-una-visita), también sin visita de origen. Históricos mantienen su excepción.
- Deuda no bloquea publicación; notas internas no aparecen en portal.

###### Pagos y documentos dentro de la ficha de atención

La sección Pagos muestra la orden, comprobantes, confirmados y saldo, y permite [revisar los pagos](#revisión-de-pagos-recibidos) sin salir de la atención. Documentos permite [adjuntar recibos](#recibos-no-fiscales), [documentos fiscales](#documentos-fiscales-de-la-atención) y [registrar entregas](#entrega-de-documentos-de-la-atención), con cliente y orden precargados. Los campos y controles se definen en Cobros y documentos y se reutilizan aquí.

##### Clientes

**Contiene:** listado y búsqueda de clientes, formulario de registro o edición y ficha del cliente. En la ficha se despliegan ubicaciones, cuentas autorizadas, historial, pagos y documentos.

**Datos, búsqueda y filtros**

- Datos: nombre/razón social, tipo, contacto, teléfono, estado y acciones.
- Búsqueda por nombre, razón social, teléfono o identificación; filtros Particular/Empresa y Activo/Inactivo.

**Acciones y navegación**

- **Ver**, **Editar**, **Desactivar** o **Reactivar**; **Nuevo cliente** despliega el [Formulario de cliente particular o empresa](#formulario-de-cliente-particular-o-empresa) dentro de Clientes.

**Reglas de conservación y coincidencias**

- Desactivar exige confirmación y conserva ficha, ubicaciones, asociaciones e historial. Inactivo mantiene consulta autorizada, pero no atención nueva hasta reactivarse.
- Buscar ofrece coincidencias sin fusionar ni asociar cuentas.

**Presentación en celular**

- Celular: **Abrir ficha** principal y demás acciones en menú identificado.

###### Formulario de cliente particular o empresa

**Campos y distribución**

- Elegir Particular/Empresa; campos, orden y reglas de [Clientes, ubicaciones y servicios](#clientes-ubicaciones-y-servicios).
- Primera fila: nombre/teléfono en particular; razón social/nombre comercial en empresa. Correo e identificación comparten fila; notas internas a todo el ancho. Demás campos en orden y una columna en celular.

**Acciones y resultado**

- **Guardar cliente** o **Cancelar**. Editar precarga datos y fija el tipo.

**Estado, privacidad y requisitos**

- Estado inicial Activo; notas internas fuera del portal.
- Guardar no exige cuenta ni correo.

###### Ficha del cliente y cuentas autorizadas

**Datos y secciones de la ficha**

- Encabezado: nombre/razón social, tipo y estado. Secciones: Datos, Atenciones, Ubicaciones, Cuentas, Historial, Pagos y Documentos.
- Atenciones une solicitud, propuesta, orden, visita, servicio y documentos por referencia; acciones precargan cliente, lugar y orden. **Registrar contacto** precarga cliente y **Continuar borrador** recupera lo guardado.
- Cuentas: nombre, correo, ID, alcance, sede y fecha; **Cambiar alcance**, **Retirar asociación**.

**Asociar una cuenta**

- **Asociar cuenta**: ID y **Buscar cuenta**. Mensajes: **Introduce un ID de cuenta válido.** / **No se encontró una cuenta con ese ID.**; resultado muestra nombre y correo verificado.
- Comprobación según [Asociación mediante ID](#asociación-mediante-id): canal WhatsApp/Llamada/Otro medio acordado; Otro exige descripción de 2 a 100 caracteres. Marcar **He confirmado que esta persona está autorizada para consultar este historial**.
- Empresa: **Todas las sedes** o **Una sede** de esa empresa; particular: sus ubicaciones, sin selector de empresa.
- **Guardar asociación** registra responsable, fecha, cuenta, cliente, alcance, sede y canal; exige correo verificado y autorización.

**Cambiar o retirar una asociación**

- **Cambiar alcance** exige nueva comprobación y motivo de 2 a 1000 caracteres; conserva anterior/nuevo y fecha.
- Asociación repetida no se duplica; para otro cliente se retira primero la anterior. Retirar exige confirmación y corta consultas futuras.

###### Ubicaciones del cliente

**Datos y acciones del listado**

- Datos: nombre, dirección, provincia, cantón, distrito y estado; **Editar**, **Desactivar**, **Reactivar**.

**Campos y validaciones**

- Formulario: cliente fijo; nombre; provincia/cantón/distrito; dirección; acceso; frecuencia; estado. Reglas de [Ubicación del servicio](#ubicación-del-servicio).
- Territorio obligatorio y dependiente; cambiar nivel limpia los inferiores.
- Frecuencia opcional de 1 a 365 días, acordada por César; no recomienda tratamiento. Estado inicial Activo.

**Guardado y navegación**

- **Guardar ubicación** o **Cancelar** cierra el formulario en su página de origen. Si se abrió desde una atención, al guardar selecciona el lugar y conserva los demás datos.

**Conservación del historial**

- Inactiva conserva historial, pero no admite atención nueva.

###### Registro de servicios anteriores

**Registro y campos históricos**

- **Registrar servicio anterior** desde ficha abre atención marcada **Registro histórico**.
- Campos y carga según [Información histórica](#información-histórica). Cliente obligatorio; ubicación y fecha pueden quedar desconocidas. Datos introducidos mantienen sus límites.

**Revisión y publicación**

- Revisar y publicar habilita consulta por permiso; conservar fecha de incorporación aparte de fecha real.

**Clasificación de sede**

- **Clasificar sede** exige una sede de esa empresa y registra fecha, responsable y motivo. Sin ubicación no se genera próxima visita.

##### Calendario

**Contiene:** agenda de visitas, bloqueos y acceso al formulario de programación. Elegir una visita muestra sus datos y acciones dentro del Calendario.

**Presentación y navegación**

- **Hoy**, **Anterior**, **Siguiente**; vistas Mes, Semana y Lista; encabezado con periodo. Visita con hora, cliente y lugar; seleccionar abre detalle.

**Programar visitas**

- **Programar visita** despliega [Programación y estado de una visita](#programación-y-estado-de-una-visita) dentro del Calendario. Zona y formatos de [Visitas y calendario](#visitas-y-calendario).

**Bloqueos de agenda**

- **Bloquear horario**: descripción de 2 a 500 caracteres, inicio y final obligatorios; final posterior al inicio. Reserva traslado u otra indisponibilidad, sin cliente.
- Visitas nuevas no se superponen con bloqueos; modificar/retirar conserva seguimiento.

**Sugerencia de próxima visita**

- **Sugerir próxima visita** suma fecha del servicio finalizado y frecuencia de su ubicación. César revisa horario, duración y conflictos antes de confirmar; la sugerencia no reserva agenda.

El formulario de [Programación y estado de una visita](#programación-y-estado-de-una-visita) se despliega dentro del Calendario con los mismos campos y controles de la ficha de atención. Guardar o cancelar conserva el periodo mostrado.

##### Catálogos

**Contiene:** secciones Plagas y Productos, cada una con búsqueda, filtros y formulario de registro o edición.

**Datos, campos y distribución**

- Plagas: nombre, descripción, estado. Productos: nombre comercial, ingrediente activo, referencia, estado.
- Formularios en orden de [Catálogo de plagas](#catálogo-de-plagas) y [Catálogo de productos](#catálogo-de-productos), con sus límites; estado inicial Activo. Nombre/ingrediente de una línea y descripción/nota de varias.

**Acciones y conservación del historial**

- Buscar por nombre y filtrar estado; **Editar**, **Desactivar**, **Reactivar**.
- **Guardar** o **Cancelar**. Desactivar exige confirmación, conserva referencias históricas y excluye el elemento de tratamientos nuevos.

##### Cobros y documentos

**Contiene:** secciones Pagos, Recibos y Documentos fiscales. Revisar una orden despliega sus movimientos y archivos. Confirmar, rechazar, adjuntar o registrar una entrega se realiza dentro de ese detalle. Los mismos formularios pueden abrirse desde la ficha de atención, conservando cliente, ubicación y orden.

###### Revisión de pagos recibidos

**Datos, filtros y revisión**

- César. Datos: fecha, cliente, sede, orden, concepto, medio, monto, referencia, estado y **Revisar**. Filtros: estado —inicial Pendiente de verificación—, cliente, sede, medio y fechas.
- Revisar muestra reporte, instrucciones usadas, comprobante, verificaciones y saldo. Desde atención precarga cliente/orden; origen Portal/WhatsApp/Registro de César.

**Acciones y resultado**

- **Confirmar pago** precarga monto/fecha real; diferencias exigen motivo de 2 a 1000 caracteres. Marcar **He comprobado que RYC recibió este dinero** y confirmar una vez.
- **Rechazar reporte** confirma motivo de 2 a 1000 caracteres y avisa a la cuenta.
- **Registrar pago recibido** usa cliente, orden, concepto, medio, monto y fecha; banco exige referencia/archivo, efectivo no. Mismo registro para clientes sin cuenta.
- **Corregir registro de pago** conserva motivo, antes/después y responsable, sin alterar facturas.
- **Adjuntar recibo**, **Adjuntar documento fiscal**, **Revisar datos de facturación**.

**Duplicados y montos en exceso**

- Duplicado abre movimiento existente. Mensaje: **Esta referencia ya tiene un pago confirmado. Revisa el registro.**
- Exceso: **Saldo a favor pendiente de revisión**, sin devolución ni aplicación automática a otra orden.

###### Recibos no fiscales

**Listado, filtros y datos iniciales**

- Listado: referencia, cliente, lugar, orden, pago, fecha, monto y moneda; **Ver**, **Descargar**, **Sustituir archivo**. Filtros cliente, lugar, referencia y fechas.
- Desde pago confirmado se precargan cliente, orden, pago, monto y moneda. El archivo muestra nombre, tamaño y **Quitar archivo** antes de enviar.

**Campos del recibo**

| Campo | Obligatorio | Regla |
| --- | --- | --- |
| Cliente | Sí | Registro al que pertenece; puede no tener cuenta de portal. |
| Orden | Para nuevos cobros | Orden aceptada; no exige servicio finalizado. |
| Pago | Para nuevos recibos de cobro | Pago confirmado al que corresponde la constancia. |
| Servicio realizado | No | Se enlaza cuando exista; no se exige para el anticipo. |
| Referencia | Para nuevos recibos | Hasta 100 caracteres; en históricos desconocidos: **No registrado**. |
| Fecha del documento | Para nuevos recibos | Fecha real, no futura. |
| Monto y moneda | Para nuevos recibos | Mayor que cero, hasta dos decimales; CRC o USD, igual al pago relacionado. |
| Archivo | Sí | PDF, JPG o PNG; máximo de 5 MiB. |
| Nota interna | No | Hasta 1000 caracteres; visible solo para César. |

**Guardado, sustitución e historial**

- **Guardar recibo** o **Cancelar**. Sustituir conserva versión y motivo de 2 a 1000 caracteres; no aplica a factura.
- Históricos conservan relaciones conocidas; **Clasificar sede** usa una ubicación del mismo cliente y registra seguimiento.

###### Documentos fiscales de la atención

**Listado y filtros**

- César. Listado: tipo, consecutivo, cliente, sede, orden, emisión, total, moneda, estado y **Ver detalle**; filtros cliente, sede, tipo, estado y fechas.

**Adjuntar y revisar documentos**

- **Adjuntar documento** abre los campos siguientes. Archivos muestran nombre, tamaño y **Quitar archivo** antes de guardar.

**Campos del documento fiscal**

| Campo | Obligatorio | Regla |
| --- | --- | --- |
| Cliente y orden | Para documentos nuevos | Cliente y sede de la orden; no se mezclan sedes. |
| Tipo | Sí | Factura electrónica, nota de crédito o nota de débito. |
| Consecutivo y clave | Sí | Copiados del documento, no generados aquí; consecutivo de 1 a 20 caracteres y clave de 1 a 50, únicos por emisor. |
| Fecha de emisión | Sí | Fecha y hora reales, no futuras. |
| Total y moneda | Sí | Mayor que cero, hasta dos decimales; moneda igual a la orden. |
| Relación con el cobro | Sí | Consultoría, anticipo, saldo o total de la operación. |
| Pago relacionado | No | Uno o varios pagos de la misma orden. |
| Documento corregido | Para notas o reemplazo de uno rechazado | Original de la misma orden al que hace referencia el documento externo. |
| XML original | Para documentos nuevos | XML válido, máximo de 5 MiB; sin resolver entidades externas al procesarlo. |
| Representación PDF | Para documentos nuevos | PDF válido, máximo de 5 MiB. |
| Respuesta de Hacienda | Cuando se disponga | XML, máximo de 5 MiB; estado conforme a la respuesta adjunta. |
| Estado | Sí | Pendiente de respuesta, Aceptado o Rechazado. |

Se comprueban formato, pertenencia y consistencia básica de los metadatos. Adjuntar XML no equivale a validarlo en línea con Hacienda.

**Guardar y adjuntar respuesta**

- **Guardar documento** comprueba metadatos contra XML. Inicia Pendiente de respuesta; **Adjuntar respuesta** conserva XML y estado, con la misma clave.

**Descargas y correcciones**

- **Ver PDF**, **Descargar XML**, **Descargar respuesta**, **Adjuntar nota relacionada**. Nota requiere original de la misma orden.
- **Adjuntar comprobante corregido** enlaza el nuevo al rechazado. Conservar originales; sin reemplazar/eliminar facturas ni fabricar documentos históricos.

**Datos del receptor**

- Datos del receptor: mismos campos de [Datos de facturación de la orden](#datos-de-facturación-de-la-orden). César los completa o revisa dentro de la orden en administración, sin cambiar la ficha maestra.

###### Entrega de documentos de la atención

- **Preparar entrega** descarga archivos o copia recomendaciones, sin enlaces públicos permanentes.
- **Registrar entrega** abre dentro de la orden el formulario con destinatario precargado, canal sin seleccionar, fecha/hora actual editable no futura y elementos.
- Marcar **He realizado esta entrega** registra quién la declaró y cuándo. Descargar, adjuntar o abrir WhatsApp no la registra ni demuestra lectura.

##### Configuración

**Contiene:** tarifa de consultoría, medios de pago y contacto público, con sus datos configurables.

**Secciones y campos de configuración**

- César; secciones Tarifa de consultoría, Medios de pago y Contacto público.

| Configuración | Campos y controles |
| --- | --- |
| WhatsApp público | Código de país y 8–15 dígitos; acepta + y separadores, enlace solo con dígitos. **Probar contacto** para revisar destino. Obligatorio antes de publicar; independiente de SINPE. |
| Tarifa | Base y costo/km en CRC, no negativos y hasta dos decimales; iniciales ₡15.000 y ₡150. San Carlos ₡0 de solo lectura. |
| SINPE y transferencia | Beneficiario 2–150 caracteres; número SINPE/cuenta 2–100; banco opcional hasta 100; moneda CRC/USD; instrucciones hasta 1000. |
| Efectivo | Instrucciones hasta 1000 caracteres; sin datos de banco. |

**Guardado y seguimiento**

- **Guardar contacto público** y **Guardar configuración** registran responsable, cambios y fecha. Medios incompletos o de otra moneda no se ofrecen; no se convierte dinero automáticamente.

**Reglas de publicación y cotización**

- Textos y fotos se incorporan al proyecto tras revisión de César; sin editor general de páginas. Un formato válido no prueba propiedad del número.
- Cotización: recorrido total y peajes no negativos, hasta dos decimales. Fuera de San Carlos, **Enviar cotización** exige km mayores que cero y total revisado; ajustar requiere motivo de 2 a 1000 caracteres.
- Guardar aceptación conserva tarifa, cálculo, total e instrucciones; cambios de configuración no la alteran.

#### Cuenta compartida por portal y administración

##### Mi cuenta

**Contiene:** perfil, ID y acciones de acceso. César también configura aquí el segundo factor; el portal del cliente conserva sus permisos propios.

**Datos y permisos de edición**

- Nombre, correo, teléfono e ID; César también ve su segundo factor.
- Correo e ID de solo lectura.

**Acciones y navegación**

- **Copiar ID** muestra **ID copiado**.
- **Editar datos** habilita nombre y teléfono con las reglas del registro; **Guardar cambios** o **Cancelar**.
- **Recuperar contraseña** abre [Recuperar acceso](#recuperar-acceso); **Cerrar sesión** invalida sesión y abre [Inicio de sesión](#inicio-de-sesión).

###### Seguridad de la cuenta administrativa

Solo César utiliza esta sección dentro de Mi cuenta.

**Configuración y recuperación**

- Configuración en Mi cuenta de César: QR, clave manual y **Código de verificación** de seis dígitos; **Confirmar** activa el factor al comprobarlo.
- Mostrar códigos de recuperación y **Copiar códigos**; César los conserva fuera del sistema.

**Protección**

- Desactivar o reconfigurar exige contraseña y factor actual o código de recuperación.

### Comprobaciones del sistema

Cada grupo reúne situaciones relacionadas. Se comprueba el resultado junto con las reglas y los mensajes de las páginas o secciones indicadas.

| Grupo | Páginas o secciones que se revisan | Resultado esperado |
| --- | --- | --- |
| Registro y acceso | [Inicio de sesión](#inicio-de-sesión); [Crear cuenta](#crear-cuenta); [Recuperar acceso](#recuperar-acceso); [Cambiar contraseña por recuperación](#cambiar-contraseña-por-recuperación); [Mi cuenta](#mi-cuenta) | Datos inválidos muestran sus errores y conservan lo válido. Una cuenta nueva es del portal; sin verificar puede editar su perfil, pero no enviar solicitudes. Recuperación y códigos de recuperación funcionan una sola vez; los códigos incorrectos se rechazan. |
| Asociaciones y permisos | [Clientes](#clientes); [Mis atenciones](#mis-atenciones); [Pagos y documentos](#pagos-y-documentos) | Copiar y asociar el ID identifica la cuenta correcta; retirar la asociación revoca el acceso. Se prueban dos clientes y dos sedes: no se consulta ni descarga información ajena. Historia empresarial sin sede se restringe hasta clasificarla; una asociación activa de sede limita también las solicitudes anteriores de la cuenta. |
| Solicitudes y aceptación | [Mis atenciones](#mis-atenciones); [Atenciones](#atenciones) | Se rechazan empresa sin nombre, fecha pasada, lugar inactivo o sin permiso y aceptación sin propuesta pendiente. Cancelar la confirmación conserva la decisión; aceptar registra una única orden. |
| Agenda y cambios | [Próximas visitas y solicitud de cambios](#próximas-visitas-y-solicitud-de-cambios); [Atenciones](#atenciones); [Calendario](#calendario) | Pedir un cambio conserva la visita original hasta revisión de César. Superposiciones con visitas o bloqueos se rechazan sin reservar horario. |
| Clientes y catálogos | [Clientes](#clientes); [Catálogos](#catálogos); [Servicio y tratamiento realizado](#servicio-y-tratamiento-realizado) | Se registra cliente sin cuenta ni correo. Desactivar conserva historial y bloquea su uso en atenciones nuevas; un producto desactivado sigue visible en servicios anteriores. |
| Cobros previos | [Mis atenciones](#mis-atenciones); [Atenciones](#atenciones); [Cobros y documentos](#cobros-y-documentos); [Configuración](#configuración) | San Carlos cuesta ₡0; fuera se exige el 100% confirmado. Un trabajo exige el 50% confirmado, también al publicar directamente. Cambiar tarifas conserva cotizaciones aceptadas. |
| Pagos | [Pagos y documentos](#pagos-y-documentos); [Cobros y documentos](#cobros-y-documentos) | Repetir reporte o referencia no duplica dinero. Rechazados y pendientes no descuentan saldo; efectivo confirmado de cliente sin cuenta sí. El saldo pendiente permite publicar el servicio realizado. |
| Servicios | [Servicio y tratamiento realizado](#servicio-y-tratamiento-realizado) | Se rechaza tratamiento sin plaga o justificación preventiva y cantidades no positivas. Se publican tratamiento y recomendaciones reales; las notas internas permanecen privadas. |
| Historia anterior | [Registro de servicios anteriores](#registro-de-servicios-anteriores) | Fecha o ubicación desconocidas muestran **No registrado** y no generan otra visita ni datos inventados. |
| Recibos y documentos | [Documentos y descargas del cliente](#documentos-y-descargas-del-cliente); [Recibos no fiscales](#recibos-no-fiscales); [Documentos fiscales de la atención](#documentos-fiscales-de-la-atención) | Se rechazan tamaño o tipo inválidos, extensiones falsas, respuesta XML de otra clave y entidades externas. Sustituir recibo conserva versión; documentos fiscales conservan originales y correcciones. El comprobante corregido enlaza al rechazado; estado fiscal y cantidad de facturas no alteran el saldo. Anticipo y documentos se registran antes del servicio finalizado. |
| Contacto público | [Página pública de RYC](#página-pública-de-ryc); [Formulario de contacto por WhatsApp](#formulario-de-contacto-por-whatsapp) | Contactar funciona sin cuenta en ambos dispositivos. Tildes, saltos y campos opcionales conservan el mensaje; abrir o copiar no registra solicitud ni reserva. Si falla WhatsApp o el portapapeles, se ofrecen número y texto. |
| Contacto administrativo | [Registro rápido de un contacto](#registro-rápido-de-un-contacto); [Atenciones](#atenciones) | Un contacto puede guardarse sin ficha o lugar completo; elegir registros existentes mantiene su referencia sin duplicar historial. Cotizar o programar exige cliente y ubicación comprobados. |
| Borradores | [Atenciones](#atenciones); [Ficha del cliente y cuentas autorizadas](#ficha-del-cliente-y-cuentas-autorizadas) | Otro dispositivo recupera lo guardado. Una versión anterior no sobrescribe; fallos o sesión vencida conservan el texto en pantalla para reintentar. |
| Continuidad de canales y entrega | [Mis atenciones](#mis-atenciones); [Atenciones](#atenciones); [Cobros y documentos](#cobros-y-documentos) | Portal y WhatsApp conservan una solicitud u orden y un registro del dinero. Entregar documentos no exige cuenta; asociarla después conserva los mismos archivos. Adjuntar o descargar no registra entrega ni lectura. |
| Resumen de pagos | [Pagos y reportes del cliente](#pagos-y-reportes-del-cliente) | Se suman solo confirmados del periodo y lugares autorizados, con CRC y USD separados; pendientes y facturas quedan fuera. |
| Uso general | Todas las páginas. | Repetir envíos no duplica registros. Teclado y pantalla pequeña permiten completar las tareas. César prueba los recorridos en ambos dispositivos y se anotan dificultades para corregirlas. |

---

## Cronograma general del proyecto

> **Nota metodológica:** Este cronograma general se formula durante la Semana 3 como parte fundamental del proceso de planeamiento del proyecto. Sin embargo, debido a su naturaleza integradora y transversal, organiza, articula y da seguimiento a todo el horizonte temporal del curso (Semanas 1 a 14) y a los cuatro Sprints principales de gestión.

---

### Ciclo de vida y organización del equipo

#### Fases del ciclo de vida

El proyecto adopta un ciclo de vida híbrido (predictivo-adaptativo). La estructura académica y los hitos de entrega se rigen por el calendario de 14 semanas del curso, mientras que la definición de requisitos, el alcance funcional, el diseño de la solución y la simulación de la gestión se articulan bajo el marco ágil Scrum en ciclos de dos semanas (Sprints).

| Etapa | Descripción y resultado | Semanas del curso |
| --- | --- | --- |
| **Definición e inicio** | Identificación del problema de negocio de RYC, propuesta de valor, objetivos general y específicos, análisis de contexto, restricciones y matriz de interesados documentados. | Semanas 1 y 2 |
| **Planeamiento e integración** | Definición detallada del alcance, catálogo de necesidades (N01–N15), especificación de las 16 páginas, reglas de negocio, ciclo de vida, cronograma del proyecto y backlog técnico (T001–T115). | Semanas 3 y 4 |
| **Tiempo, costos, calidad y riesgos** | Estimación de esfuerzo, presupuesto y costos del proyecto, línea base de tiempo, plan de aseguramiento de calidad y matriz de gestión de riesgos. | Semanas 5 y 6 |
| **Recursos, comunicaciones y adquisiciones** | Plan de asignación de recursos, matriz RACI, plan de comunicaciones con César y usuarios, adquisiciones tecnológicas y liderazgo de equipos. | Semanas 7 y 8 |
| **Simulación y control integrado** | Negociación de cambios, resolución de conflictos, integración, seguimiento y simulación de la gestión del proyecto. | Semanas 9 a 11 |
| **Evaluación, entrega y cierre del proyecto** | Evaluación teórica de la materia (Semana 12). Entrega final del proyecto integrado, validación de resultados con César, informe ejecutivo, lecciones aprendidas y cierre del proyecto (Semana 13). | Semanas 12 y 13 |
| **Cierre del curso** | Entrega de actas y notas por parte de la cátedra. | Semana 14 |

---

#### Organización del equipo y roles

El equipo de proyecto está conformado por dos estudiantes de la carrera de Ingeniería del Software de la Universidad Técnica Nacional, en coordinación directa con el propietario de la empresa como cliente e interesado principal.

| Integrante o interesado | Rol en el proyecto | Responsabilidades principales |
| --- | --- | --- |
| **Brian Rodríguez Pérez** | Product Owner y Desarrollador | Gestiona y prioriza los requerimientos del producto; canaliza las decisiones de negocio con César; responsable de redactar, estructurar y dar seguimiento al cronograma del proyecto y la gestión del tiempo. |
| **Jeremy Rodríguez Esquivel** | Scrum Master y Desarrollador | Facilita la aplicación del marco Scrum, remueve impedimentos y asegura la disciplina metodológica; responsable de redactar y estructurar el planeamiento del proyecto, la arquitectura funcional y los criterios de aceptación. |
| **Ambos integrantes** | Equipo de Desarrollo y Gestión | Analizan requerimientos, diseñan las soluciones técnicas, definen dependencias y criterios de comprobación, revisan mutuamente el trabajo (peer review) y coordinan la integración final. |
| **César Rodríguez Corrales** | Interesado clave / Dueño del negocio (Sponsor) | Propietario de RYC Control de Plagas. Aporta el conocimiento operativo del negocio, valida requerimientos y flujos de trabajo, y evalúa la pertinencia de las soluciones propuestas. |

##### Dinámica de comunicación y coordinación

- **Seguimiento en cada día de trabajo del equipo (Daily Standup):** Reunión breve de sincronización (10–15 minutos) entre Brian y Jeremy en cada jornada coordinada de trabajo para revisar avances, plan del día y bloqueos.
- **Consulta semanal con César:** Sesión de aproximadamente 20 minutos para resolver dudas operativas, verificar tarifas, flujos de atención y documentos comerciales.
- **Demostración y revisión de Sprint (Sprint Review):** Sesión de aproximadamente 30 minutos al cierre de cada ciclo para validar los incrementos documentales y prototipos con César, según su disponibilidad.

---

### Base del cronograma y calendario del curso

El cronograma del proyecto está alineado con la duración oficial de **14 semanas** del curso de Administración de Proyectos Informáticos (UTN - Sede Regional San Carlos).

De acuerdo con las indicaciones de la cátedra, el trabajo se estructura en **cuatro Sprints principales de dos semanas** para la fase medular de formulación, planeamiento y gestión, seguidos por las fases de simulación integral, evaluación, entrega final y cierre:

| Parámetro | Detalle |
| --- | --- |
| **Duración total del curso** | 14 semanas. |
| **Marco de trabajo** | Scrum adaptado al entorno académico y de proyectos de TI. |
| **Periodo de Sprints principales** | Semanas 1 a 8 del curso (4 Sprints de 2 semanas cada uno). |
| **Sprint 1 (Completado)** | Semanas 1 y 2: Definición del proyecto, contexto y gestión de interesados. |
| **Sprint 2 (En cierre / Actual)** | Semanas 3 y 4: Planeamiento del proyecto, alcance, arquitectura funcional, cronograma e integración. |
| **Sprint 3 (Próximo)** | Semanas 5 y 6: Gestión del tiempo, estimación de esfuerzo, costos, calidad y riesgos. |
| **Sprint 4 (Posterior)** | Semanas 7 y 8: Recursos, comunicaciones, adquisiciones y liderazgo de equipos. |
| **Fase de simulación y negociación** | Semanas 9 a 11: Simulación de la gestión del proyecto, negociación de cambios y resolución de conflictos. |
| **Evaluación teórica** | Semana 12: Comprobación de conocimientos de la materia. |
| **Entrega final y cierre del proyecto** | Semana 13: Presentación integral de la documentación, prototipos, validación con César, informe de lecciones aprendidas y cierre formal del proyecto. |
| **Cierre del curso** | Semana 14: Entrega de actas y notas por parte de la cátedra. |
| **Responsable del cronograma** | Brian Rodríguez Pérez. |
| **Pendientes de estimación** | Horas semanales disponibles y esfuerzo estimado por tarea técnica (a definirse formalmente en el Sprint 3, Semana 5: Tiempo y Costos, según la técnica indicada por la cátedra). |

---

### Objetivos e incrementos por Sprint (Gestión del proyecto)

| Sprint y semanas | Estado | Objetivo del Sprint | Áreas del proyecto y entregables | Incremento / Hito al cierre |
| --- | --- | --- | --- | --- |
| **Sprint 1**<br>(Semanas 1–2) | **Completado** | Establecer las bases estratégicas del proyecto, delimitando el problema de negocio, los objetivos de la intervención y el mapa de partes interesadas. | - Problema de negocio de RYC.<br>- Proyecto propuesto y valor esperado.<br>- Objetivo general y específicos.<br>- Contexto y restricciones.<br>- Registro y justificación de interesados.<br>- Matriz Poder-Interés y análisis de interesados críticos.<br>- Enfoque de gestión del proyecto. | **Hito M1:** *Acta y Marco de Inicio del Proyecto* documentados y consolidados en el expediente del proyecto (README). |
| **Sprint 2**<br>(Semanas 3–4) | **En cierre / Actual** | Desarrollar el planeamiento integral del proyecto: alcance, necesidades de usuario, especificación de la solución, ciclo de vida, cronograma y backlog técnico. | - Alcance y organización de la información.<br>- Catálogo de necesidades (N01–N15).<br>- Flujos de atención con cuenta y sin cuenta.<br>- Especificación funcional de las 16 páginas del sistema.<br>- Reglas de negocio y casos de comprobación.<br>- Ciclo de vida y organización del equipo.<br>- Cronograma del proyecto y backlog técnico (T001–T115). | **Hito M2:** *Plan Integral del Proyecto y Especificación del Sistema* integrado en el README, con estructura de trabajo y cronograma de referencia. |
| **Sprint 3**<br>(Semanas 5–6) | **Próximo** | Formular la línea base de tiempo, costos, calidad y riesgos aplicados al proyecto y a la solución técnica de RYC. | - Estimación de esfuerzo del backlog técnico según técnica de clase.<br>- Capacidad real y horas asignadas.<br>- Presupuesto del proyecto y costos de tecnología/operación.<br>- Métricas de calidad y criterios de aceptación.<br>- Matriz de riesgos, impacto, probabilidad y planes de respuesta. | **Hito M3:** *Línea Base de Tiempo, Costos, Calidad y Gestión de Riesgos* documentada y articulada con el backlog técnico. |
| **Sprint 4**<br>(Semanas 7–8) | **Posterior** | Planificar la gestión de personas, comunicaciones internas y externas, adquisiciones de servicios y estrategias de liderazgo de equipo. | - Matriz de asignación de responsabilidades (RACI).<br>- Plan de comunicaciones (César, clientes, equipo, profesor).<br>- Plan de adquisiciones (hosting, dominio web, correo, almacenamiento u otros servicios necesarios; sin pasarelas de pago).<br>- Estrategias de liderazgo y acuerdos de equipo de alto desempeño. | **Hito M4:** *Plan de Recursos, Comunicaciones, Adquisiciones y Liderazgo* consolidado en el expediente. |

#### Fases posteriores al ciclo de Sprints principales

- **Semanas 9 a 11 (Simulación, conflictos y negociación):** Práctica integrada de control del proyecto, atención de solicitudes de cambio de alcance, resolución de desvíos en la simulación y dinámicas de negociación en la gestión del proyecto.
- **Semana 12 (Evaluación teórica):** Comprobación individual o grupal de conocimientos del curso.
- **Semana 13 (Entrega final y cierre del proyecto):** Presentación del expediente completo del proyecto, validación de resultados con César, informe de lecciones aprendidas y cierre formal del proyecto.
- **Semana 14 (Cierre del curso):** Entrega de actas y notas finales por parte del docente.

---

### Plan técnico de trabajo e implementación del sistema

> **Nota sobre el alcance y la naturaleza del plan técnico:**  
> Las tareas descritas a continuación (**T001–T115**) representan el desglose analítico de trabajo (Work Breakdown Structure / Product Backlog) que requeriría la construcción técnica integral del software en un escenario de ejecución real.  
> Para efectos del curso académico de *Administración de Proyectos Informáticos*, este catálogo constituye la **base técnica simulada** para planificar, estimar esfuerzo, calcular capacidades, analizar rutas críticas de dependencias, asignar roles y aplicar con rigor profesional las ceremonias de Scrum. Su inclusión en el expediente demuestra la viabilidad técnica y el nivel de detalle de la solución, sin que implique que los estudiantes deban programar la totalidad de los 115 componentes durante las semanas lectivas.

---

#### Cálculo de capacidad técnica

Para la estimación de capacidad en la simulación de desarrollo técnico se establece el siguiente modelo de cálculo por Sprint:

| Parámetro | Fórmula / Definición | Propósito |
| --- | --- | --- |
| **Horas disponibles por Sprint** | 2 × (Horas semanales de Jeremy + Horas semanales de Brian) | Total de horas brutas que el equipo dispone en un ciclo de 2 semanas. |
| **Reserva para ajustes e imprevistos** | 20% de las horas disponibles | Amortiguador (buffer) para contingencias, consultas imprevistas y bloqueos técnicos. |
| **Capacidad efectiva para tareas** | 80% de las horas disponibles | Esfuerzo neto asignable a tareas de análisis, diseño, código, pruebas y documentación. |
| **Capacidad total del horizonte técnico** | 8 × (Horas semanales de Jeremy + Horas semanales de Brian) | Capacidad agregada para el conjunto de 4 iteraciones técnicas de referencia. |

*Nota metodológica:* El esfuerzo de cada tarea comprende desarrollo, pruebas unitarias, revisión cruzada, integración y documentación. La asignación numérica del esfuerzo se completará durante la Semana 5 (Gestión del tiempo y estimación), aplicando la técnica y escala que establezca la cátedra.

---

#### Páginas que agrupan las tareas técnicas

El backlog técnico se articula alrededor de las **16 páginas** definidas en la arquitectura del sistema:

| Área funcional | Páginas del sistema |
| --- | --- |
| **Pública y acceso** | 1. Página pública de RYC (Landing page)<br>2. Inicio de sesión<br>3. Crear cuenta<br>4. Recuperar acceso<br>5. Cambiar contraseña por recuperación |
| **Portal del cliente** | 6. Inicio del portal<br>7. Mis atenciones<br>8. Pagos y documentos |
| **Administración (César)** | 9. Inicio administrativo<br>10. Atenciones<br>11. Clientes<br>12. Calendario<br>13. Catálogos<br>14. Cobros y documentos<br>15. Configuración |
| **Transversal / Compartida** | 16. Mi cuenta (con vistas adaptadas para clientes y para César) |

---

#### Tareas, responsables y dependencias

**T** identifica cada tarea de implementación, diseño o comprobación técnica. Cada registro especifica responsable, resultado tangible y dependencias de precedencia.

| ID | Tarea | Responsable | Resultado comprobable | Depende de |
| --- | --- | --- | --- | --- |
| T001 | Preparar el proyecto y fijar las versiones de sus dependencias. | Ambos | Se registran las versiones utilizadas de Laravel, PHP y componentes de la interfaz. | — |
| T002 | Definir las relaciones de cuentas, clientes, ubicaciones, solicitudes, órdenes, servicios, pagos, documentos y borradores. | Ambos | Se distinguen cuenta, cliente, sede, alcance, origen del contacto, atención, versión de borrador y entrega de documentos. | T001 |
| T003 | Definir los estilos comunes de colores, tipografía, controles y espacios. | Ambos | Los valores coinciden con la sección de diseño. | T001 |
| T004 | Construir la distribución adaptable de las páginas de acceso. | Jeremy | Inicio de sesión, Crear cuenta y recuperación respetan sus anchos, espacios y desplazamiento. | T003 |
| T005 | Construir el menú y la estructura adaptable de administración y portal. | Ambos | Portal: Inicio, Mis atenciones, Pagos y documentos, Mi cuenta y WhatsApp. Administración: Inicio, Atenciones, Clientes, Calendario, Catálogos, Cobros y documentos, Configuración y Mi cuenta. Se aplican los comportamientos definidos para los anchos de 640 y 1024 px. | T003 |
| T006 | Configurar la cuenta administrativa de César. | Brian | El registro público no puede otorgar este permiso. | T002 |
| T007 | Construir el formulario de registro. | Jeremy | Presenta los cinco campos descritos y sus etiquetas. | T002, T004 |
| T008 | Validar y guardar una cuenta pública. | Jeremy | Se comprueban nombre, correo único, teléfono opcional, contraseña y confirmación. | T007 |
| T009 | Implementar la verificación del correo de la cuenta. | Jeremy | El aviso y el reenvío se muestran dentro de Inicio del portal; las solicitudes y la información asociada requieren correo verificado. | T008 |
| T010 | Construir el formulario de inicio de sesión. | Jeremy | Incluye correo, contraseña, mostrar u ocultar, recuperación y registro. | T004 |
| T011 | Comprobar las credenciales y limitar los intentos de acceso. | Jeremy | Se aplican el mensaje definido y cinco fallos por minuto por correo e IP. | T008, T010 |
| T012 | Implementar la recuperación de contraseña. | Jeremy | El enlace es de un solo uso y vence a los 30 minutos. | T008 |
| T013 | Configurar el segundo factor del acceso administrativo. | Jeremy | César introduce el código de su aplicación autenticadora dentro de Inicio de sesión y configura el segundo factor y los códigos de recuperación en Mi cuenta. | T006, T011 |
| T014 | Mostrar el ID de cuenta y gestionar su sesión. | Jeremy | Mi cuenta muestra Copiar ID; existe cierre de sesión e inactividad de 60 minutos. | T011 |
| T015 | Construir el formulario de cliente particular. | Brian | Presenta los campos, obligatoriedad y longitudes definidos. | T002, T005, T006 |
| T016 | Construir el formulario de empresa. | Brian | Presenta razón social, contacto y los demás campos definidos. | T002, T005, T006 |
| T017 | Guardar y modificar los registros de cliente. | Brian | César puede registrar particulares y empresas sin una cuenta de portal. | T015, T016 |
| T018 | Listar y desactivar registros de cliente. | Brian | La desactivación conserva sus datos e historial. | T017 |
| T019 | Construir el formulario de ubicación. | Brian | Presenta los datos definidos y el cliente al que pertenece. | T017 |
| T020 | Guardar y gestionar las ubicaciones de un cliente. | Brian | Cada visita puede distinguir el lugar atendido y las ubicaciones se pueden desactivar. | T019 |
| T021 | Buscar una cuenta por su ID desde la ficha de cliente. | Ambos | Se muestran nombre y correo verificado de la cuenta encontrada. | T014, T017 |
| T022 | Guardar una asociación autorizada entre cuenta y cliente. | Ambos | Se registra autorización, responsable, fecha, cuenta, cliente, alcance y sede; cambios de alcance conservan seguimiento. | T021, T020, T081 |
| T023 | Retirar una asociación incorrecta. | Ambos | Se conserva el registro del cambio y se retira el acceso al historial. | T022 |
| T024 | Construir el formulario de consultoría con identificación territorial. | Jeremy | El formulario se despliega en Mis atenciones e incluye campos y selectores dependientes para determinar el lugar; el texto distingue solicitud y visita. | T005, T009, T080 |
| T025 | Validar y registrar una solicitud de consultoría. | Jeremy | Se conserva solicitante y ubicación autorizada; la fecha preferida no confirma una visita. | T024 |
| T026 | Mostrar las solicitudes en administración. | Brian | El listado de Atenciones reúne solicitudes del portal y contactos registrados desde WhatsApp; abrir una fila despliega su ficha, sin filas originadas por un enlace público no enviado. | T025, T105 |
| T027 | Gestionar los estados y la cancelación de una consultoría. | Brian | Se conserva el seguimiento y las decisiones de costo y trabajo; la visita cobrada requiere confirmar el 100% antes de realizarse. | T026, T029, T082, T083, T091 |
| T028 | Construir el formulario administrativo de una visita. | Brian | El formulario se despliega en la ficha de Atenciones y se prepara para reutilizarlo en Calendario; incluye cliente, ubicación, tipo, orden para atención con cobro, inicio, duración y descripción. | T020, T005 |
| T029 | Guardar la programación de una visita. | Brian | Se comprueban fecha, duración y ausencia de solapamiento en la agenda de César. | T028 |
| T030 | Registrar cambios de fecha y cancelaciones de visitas. | Brian | Se conserva la programación anterior y el motivo del cambio. | T029 |
| T031 | Registrar y mostrar la propuesta básica del servicio. | Brian | La propuesta se prepara dentro de Atenciones y presenta condiciones del trabajo para compartir por WhatsApp y consultar en Mis atenciones; no exige cuenta al cliente. | T027, T017 |
| T032 | Registrar la aceptación del servicio desde el portal. | Jeremy | Confirmar desde el detalle de Mis atenciones guarda la decisión y crea la orden una sola vez; no confirma pago. Los pagos de la orden se despliegan en ese mismo detalle. | T031, T025, T009, T084 |
| T033 | Registrar una decisión recibida fuera del portal. | Brian | César conserva aceptación, fecha y forma de recepción; también el resultado no aceptado. | T031, T084 |
| T034 | Enviar una solicitud de nueva visita desde una cuenta asociada. | Jeremy | El formulario se despliega en Mis atenciones y solo admite ubicaciones activas dentro del alcance de cliente y sede; al guardar muestra el detalle y al cancelar conserva la sección. | T022, T020 |
| T035 | Revisar y programar una nueva visita solicitada. | Brian | César confirma fecha y condiciones; para nuevo trabajo con cobro registra propuesta, aceptación y orden antes de iniciarlo. | T034, T029, T031, T084 |
| T036 | Construir el formulario del catálogo de plagas. | Brian | Incluye nombre, descripción y estado. | T005, T006 |
| T037 | Guardar y desactivar elementos del catálogo de plagas. | Brian | Los elementos desactivados conservan su referencia en el historial. | T036 |
| T038 | Construir el formulario del catálogo de productos. | Brian | Incluye nombre comercial, ingrediente, referencia, nota y estado. | T005, T006 |
| T039 | Guardar y desactivar elementos del catálogo de productos. | Brian | Los elementos desactivados conservan su referencia en los tratamientos. | T038 |
| T040 | Registrar los datos generales de un servicio realizado. | Brian | Relaciona cliente, ubicación, orden y visita para atención nueva con cobro; conserva excepción para historia anterior. | T017, T020, T029, T084, T091 |
| T041 | Registrar las plagas y los productos utilizados. | Brian | Cada producto conserva cantidad positiva y unidad; se contempla el tratamiento preventivo. | T037, T039, T040 |
| T042 | Registrar la descripción y el método del tratamiento. | Brian | Se conserva lo realmente aplicado y la zona atendida. | T041 |
| T043 | Registrar recomendaciones y observaciones internas. | Brian | El portal consulta las recomendaciones; las observaciones internas quedan en administración. | T040 |
| T044 | Finalizar y publicar una atención. | Brian | Publica lo realizado y habilita cobro del saldo; la publicación no depende de tener el saldo completo. | T042, T043, T091 |
| T045 | Mostrar el historial del cliente asociado en el portal. | Jeremy | La sección Historial de Mis atenciones muestra una línea de tiempo con solo servicios publicados del cliente y sedes autorizadas. | T022, T044 |
| T046 | Consultar el detalle de un servicio en el portal. | Jeremy | El detalle se despliega dentro de Mis atenciones; solo las cuentas autorizadas consultan plagas, productos, tratamiento y recomendaciones. | T045 |
| T047 | Construir la carga administrativa de un recibo no fiscal. | Brian | El formulario se utiliza dentro de Cobros y documentos o la ficha de Atenciones, con cliente, orden, pago confirmado y servicio opcional; admite anticipo antes de ejecutar el trabajo. | T084, T089, T006 |
| T048 | Validar y almacenar el archivo de un recibo. | Brian | Se comprueban PDF/JPG/PNG y 5 MiB; el archivo tiene nombre generado y almacenamiento privado. | T047 |
| T049 | Relacionar el recibo con la orden, el pago y el cliente. | Brian | Los documentos nuevos se enlazan al cobro; los históricos permiten conservar solo los datos disponibles. | T048 |
| T050 | Consultar y descargar recibos desde una cuenta autorizada. | Jeremy | Los recibos se consultan en Pagos y documentos o desde el detalle autorizado de Mis atenciones; cada consulta y descarga comprueba cliente, sede o pertenencia exclusiva a una orden de solicitud propia. | T022, T049 |
| T051 | Conservar versiones al sustituir un recibo no fiscal. | Brian | Se guarda motivo y versión anterior; no se sustituye así una factura emitida. | T049 |
| T052 | Construir las vistas administrativas del calendario. | Brian | Calendario muestra mes, semana y lista en America/Costa_Rica; datos y acciones de la visita se despliegan en la página y reutilizan el formulario de programación. | T029, T030 |
| T053 | Mostrar las próximas visitas en el portal. | Jeremy | La sección Próximas visitas de Mis atenciones permite a la cuenta asociada consultar fecha, hora, lugar y estado. | T022, T029 |
| T054 | Sugerir una próxima visita según la frecuencia en días. | Brian | César confirma la creación; la sugerencia no reserva la agenda. | T029, T044, T076 |
| T055 | Recibir solicitudes de cambio de una visita desde el portal. | Jeremy | El formulario de cambio se despliega junto a la visita en Mis atenciones; la programación se conserva hasta que César confirme la modificación de la agenda. | T053, T030 |
| T056 | Registrar servicios anteriores con datos incompletos. | Brian | Se conserva la información conocida, su origen histórico y los datos no registrados. | T040 |
| T057 | Relacionar recibos e historial anteriores con el registro de cliente. | Ambos | Una asociación posterior permite consultar registros por alcance sin duplicar; documentos empresariales sin sede se reservan al acceso principal. | T056, T049, T022, T096 |
| T058 | Preparar los datos ficticios de la demostración. | Ambos | Se pueden recorrer los flujos con cuenta, sin cuenta y asociación posterior. | T057 |
| T059 | Comprobar el aislamiento entre clientes y entre sedes de una empresa. | Ambos | Se verifica aislamiento de servicios, visitas, pagos y XML/PDF; órdenes propias no abren otro historial. | T046, T050, T053, T095, T096 |
| T060 | Comprobar los flujos completos de atención. | Ambos | Se recorre contacto público sin cuenta, consulta gratis o cobrada, decisiones, anticipo, atención, saldo, entrega e historial opcional. | T032, T033, T035, T044, T050, T098, T115 |
| T061 | Comprobar la interfaz en los tamaños y medios de navegación definidos. | Ambos | Se revisan adaptación, teclado, foco, etiquetas y áreas táctiles; abrir, guardar o cancelar formularios de atención conserva el registro, los datos y los filtros de la página. | T004, T005, T052, T053 |
| T062 | Publicar la aplicación de demostración mediante HTTPS. | Brian | La versión entregada es accesible y ejecuta los flujos acordados. | T001, T058 |
| T063 | Configurar el correo del entorno de entrega. | Brian | La verificación y la recuperación funcionan mediante el servicio SMTP. | T062, T009, T012 |
| T064 | Configurar la persistencia privada de los documentos. | Brian | Comprobantes, recibos, XML, respuestas y PDF se conservan privados y persistentes. | T062, T048, T088, T094 |
| T065 | Configurar el respaldo diario de los datos y documentos. | Ambos | Se mantienen siete copias diarias y cuatro semanales; su rotación no elimina archivo fiscal. | T062, T064 |
| T066 | Preparar la copia semanal cifrada fuera del alojamiento. | Ambos | RYC dispone de una copia bajo su control. | T065 |
| T067 | Comprobar la restauración de una copia de seguridad. | Ambos | Se recuperan datos y documentos de una copia válida. | T065, T066 |
| T068 | Preparar la guía breve de uso para César. | Ambos | Explica las páginas de administración y el trabajo dentro de la ficha de Atenciones: contacto por WhatsApp, registro rápido, borradores en ambos dispositivos, asociación por sede, cobros, entrega y respaldo. | T060, T052, T067, T114 |
| T069 | Validar la entrega con César. | Ambos | Se validan tareas reales en ambos dispositivos, funciones, permisos, entrega independiente de cuenta y respaldos. | T059, T060, T061, T063, T064, T067, T068, T114, T115 |
| T070 | Documentar el cierre del proyecto. | Ambos | Se conservan aceptación, resultados y lecciones aprendidas. | T069 |
| T071 | Editar los datos permitidos de Mi cuenta. | Jeremy | Nombre y teléfono se actualizan con sus validaciones; correo e ID permanecen de solo lectura. | T014 |
| T072 | Construir Inicio del portal. | Jeremy | Inicio del portal muestra resumen y accesos según verificación y asociación; el aviso de correo sin verificar y sus acciones permanecen dentro de Inicio. | T009, T014, T022 |
| T073 | Mostrar el listado y detalle de solicitudes propias. | Jeremy | Solicitudes es una sección de Mis atenciones; el listado, detalle y propuesta pertenecen a esa página. La cuenta consulta únicamente las solicitudes que emitió y su seguimiento. | T025, T034 |
| T074 | Registrar el rechazo de una propuesta desde el portal. | Jeremy | La decisión pendiente cambia a No aceptada después de confirmar; no se duplica el resultado. | T031, T025 |
| T075 | Construir Inicio administrativo. | Brian | Inicio administrativo muestra visitas de hoy, contactos pendientes, revisión de pagos, saldos y entrega; sus accesos abren el registro correspondiente con sus datos. Los borradores se conectan al incorporarse T107. | T026, T029, T089, T094, T110 |
| T076 | Registrar la frecuencia de seguimiento de una ubicación. | Brian | El valor es opcional y admite enteros de 1 a 365 días. | T020 |
| T077 | Registrar bloqueos de agenda y comprobar sus conflictos. | Brian | Se conserva la indisponibilidad con su motivo; las visitas nuevas no se superponen con ella. | T029, T052 |
| T078 | Revisar y resolver solicitudes de cambios de visita. | Brian | César registra Aplicada o No aplicada y solo modifica la agenda al confirmar. | T055, T030 |
| T079 | Conservar el seguimiento de correcciones de servicios publicados. | Brian | La corrección exige motivo y conserva cuándo se realizó. | T044 |
| T080 | Preparar selectores de provincia, cantón y distrito. | Ambos | Las solicitudes y ubicaciones comparten un catálogo territorial coherente y niveles dependientes. | T002, T005 |
| T081 | Aplicar el alcance de empresa o sede en las autorizaciones. | Ambos | Una cuenta principal accede a toda su empresa; una de sede solo a esa sede; la regla rige consultas y archivos. | T002, T020, T009 |
| T082 | Calcular y revisar el costo territorial de la consultoría. | Brian | San Carlos produce costo cero; fuera se conserva cálculo y total revisados para una solicitud recibida por cualquier canal. | T025, T105, T086, T099 |
| T083 | Registrar aceptación o rechazo del costo de consultoría. | Jeremy | La decisión de la solicitud propia queda registrada; aceptar permite crear la orden de esa consulta. | T082, T084 |
| T084 | Crear y conservar la orden de una atención aceptada. | Ambos | Se registra cliente, sede, solicitante cuando exista, total, moneda y condiciones; una cuenta es opcional para crear la orden. | T017, T020, T025, T105 |
| T085 | Calcular obligaciones, montos confirmados y saldo. | Brian | Se distingue 100% de consulta, anticipo del 50% y saldo; pendientes y facturas no reducen la deuda. | T084 |
| T086 | Configurar los medios e instrucciones reales de cobro. | Brian | SINPE, efectivo y transferencia tienen datos revisados; no se ofrecen medios incompletos. | T006, T005 |
| T087 | Construir y guardar el reporte de pago del portal. | Jeremy | Informar pago se despliega dentro del detalle de la orden autorizada en Pagos y documentos o Mis atenciones; conserva concepto, medio, monto, fecha, referencia y comentario y queda pendiente. | T085, T081, T086 |
| T088 | Validar y almacenar el comprobante del reporte. | Jeremy | Los medios de banco exigen PDF/JPG/PNG de hasta 5 MiB y almacenamiento privado; efectivo no exige archivo. | T087 |
| T089 | Revisar, confirmar o rechazar los reportes de pago. | Brian | Solo confirmaciones verificadas afectan el saldo; rechazo registra motivo y se evitan referencias duplicadas. | T088, T085 |
| T090 | Registrar pagos recibidos fuera del portal y en efectivo. | Brian | César registra dinero y comprobantes recibidos por WhatsApp o en efectivo en la misma orden; evita duplicar un reporte del portal. | T089 |
| T091 | Comprobar el pago requerido antes de iniciar la atención. | Brian | Se bloquea consulta cobrada sin el 100% y trabajo sin el anticipo; no se omite al finalizar directamente. | T029, T089, T085 |
| T092 | Mostrar avisos internos del flujo financiero. | Jeremy | Reportes, resultados y documentos nuevos aparecen con enlace, fecha y marca de lectura. | T089, T094 |
| T093 | Recoger y revisar datos de facturación de la orden. | Jeremy | El formulario de la orden se utiliza en Pagos y documentos o Mis atenciones para el cliente autorizado y dentro de la orden administrativa para César; se revisa sin alterar automáticamente el registro del cliente. | T084, T081 |
| T094 | Adjuntar y revisar documentos fiscales externos. | Brian | El formulario de Cobros y documentos se reutiliza dentro de Atenciones; conserva clave, consecutivo, total, XML, PDF y respuesta; no se declara aceptación sin respuesta. | T084, T048, T093 |
| T095 | Mostrar el estado financiero y descargar documentos por permiso. | Jeremy | Pagos y documentos muestra órdenes, confirmados, pendientes y saldo; el detalle de Mis atenciones consulta los mismos registros autorizados. Las descargas respetan empresa, sede u orden propia. | T089, T094, T050, T081 |
| T096 | Clasificar registros y documentos anteriores por sede. | Brian | Solo César y el acceso principal ven historia empresarial sin sede hasta asignarla con seguimiento. | T081, T049, T094 |
| T097 | Conservar originales y documentos fiscales de corrección. | Brian | El comprobante válido mantiene notas relacionadas; uno rechazado por Hacienda enlaza al nuevo comprobante corregido, conservando ambos. | T094 |
| T098 | Comprobar anticipos, consulta cobrada y facturación externa. | Ambos | Se prueban pagos parciales, duplicados, rechazo, efectivo, inicio bloqueado, saldo y documentos antes del servicio. | T090, T091, T095, T097, T100 |
| T099 | Guardar tarifas configurables y cotizaciones aceptadas. | Brian | Base y costo por km son configurables; cotizaciones aceptadas conservan valores e instrucciones. | T006, T005 |
| T100 | Conservar las correcciones y excesos de pagos confirmados. | Brian | Una corrección registra motivo, montos y responsable; un exceso se muestra sin reembolso automático. | T089 |
| T101 | Configurar y revisar el contenido público y el WhatsApp de RYC. | Brian | Datos, imágenes y servicios reales aprobados; número internacional revisado; precios no confirmados no se publican. | T006, T005 |
| T102 | Construir la página pública adaptable. | Jeremy | Página pública de RYC presenta la empresa y sus condiciones con contacto principal y portal opcional, sin exigir registro. | T003, T101 |
| T103 | Preparar y comprobar enlaces de contacto por WhatsApp. | Jeremy | El número revisado y texto codificado abren el contacto en ambos dispositivos; no se declara envío ni recepción. | T101, T102 |
| T104 | Construir el formulario público breve y su alternativa de copia. | Jeremy | El formulario integrado en Página pública de RYC valida y prepara el mensaje sin crear solicitudes; ofrece contacto directo y copia manual. | T103 |
| T105 | Registrar rápidamente un contacto recibido fuera del portal. | Brian | El formulario Registro rápido de un contacto se despliega en Atenciones o desde un acceso de Inicio administrativo o Clientes; guarda nombre, teléfono y motivo y continúa en la misma atención, permitiendo completar cliente y lugar después sin crear fichas ficticias. | T017, T020, T005 |
| T106 | Reutilizar datos y acciones desde la ficha de atención. | Brian | La ficha de Atenciones precarga cliente, ubicación, orden y datos disponibles para cotizar, programar, revisar pagos, registrar tratamiento y adjuntar documentos. Desde la ficha de Clientes se abre la misma atención con sus datos; crear una ubicación conserva el contexto y la referencia. | T105, T029, T084 |
| T107 | Guardar y retomar borradores privados de contacto y servicio. | Brian | Guardado inicial explícito, posteriores cambios tras dos segundos y recuperación en otro dispositivo; no se ejecutan acciones comerciales. | T105, T040, T106 |
| T108 | Evitar sobrescritura y pérdida de cambios entre dispositivos. | Ambos | Una versión desactualizada se detecta; errores y sesión vencida conservan el texto visible para reintentar. | T107 |
| T109 | Construir el componente común de tarjetas administrativas en celular. | Brian | Listados comunes presentan sus datos y acciones en tarjetas para celular y tablas de computadora sin perder permisos. | T005, T018 |
| T110 | Preparar y registrar la entrega de documentos sin exigir cuenta. | Brian | La entrega se prepara y registra dentro de la orden en Cobros y documentos o Atenciones: descarga de archivos privados y registro de destinatario, canal, fecha y elementos entregados; adjuntar no implica entregar. | T049, T094 |
| T111 | Mostrar pagos confirmados por mes o periodo autorizado. | Jeremy | El resumen de Pagos y documentos suma confirmados por recepción real, separa monedas y aplica permisos y correcciones sin sumar facturas. | T095, T100 |
| T112 | Mantener la referencia de solicitudes al consultar por WhatsApp. | Jeremy | Las solicitudes, consultorías y propuestas dentro de Mis atenciones ofrecen WhatsApp con su referencia; abrirlo no repite formularios ni guarda otra solicitud. | T025, T034, T103 |
| T113 | Conectar acciones confirmadas con su seguimiento relacionado. | Ambos | Programar, confirmar pago y publicar actualizan su resultado una sola vez dentro de la ficha de atención y muestran la siguiente tarea pendiente; los listados generales reflejan los mismos registros. | T106, T044, T089 |
| T114 | Validar la facilidad de uso con César en ambos dispositivos. | Ambos | Se observan tareas, tiempo, repeticiones, errores y ayuda dentro de las páginas del portal y de administración; se comprueba guardar y cancelar conservando contexto en ambos dispositivos. Se corrigen impedimentos y pérdida de información antes de aceptar. | T108, T109, T110, T111, T112, T113, T061, T098 |
| T115 | Comprobar el recorrido sin cuenta y su continuidad con el portal opcional. | Ambos | Contacto público, atención, dinero, entrega y asociación posterior conservan un solo historial; ningún documento exige registro. | T104, T105, T090, T110, T095, T112 |

---

#### Distribución del backlog en fases técnicas de desarrollo (Releases técnicos)

Para efectos de modelado de desarrollo y análisis de dependencias, las 115 tareas técnicas se agrupan en **cuatro incrementos técnicos o releases de software**, ordenados por su arquitectura de dependencias:

| Incremento técnico | Cantidad | Tareas asignadas | Objetivo del incremento técnico |
| :---: | :---: | :--- | :--- |
| **Fase Técnica 1**<br>*(Base, Identidad y Acceso)* | 31 | T001–T020, T071, T076, T080–T081, T086, T099, T101–T104, T109. | Fundaciones de arquitectura, modelo de datos, diseño responsivo, landing pública, enlace WhatsApp, autenticación, control de perfiles y gestión básica de clientes y sedes. |
| **Fase Técnica 2**<br>*(Atención, Propuestas y Cobros)* | 40 | T021–T035, T047–T051, T072–T075, T082–T085, T087–T091, T093–T095, T105–T106, T110, T112. | Registro rápido de contactos, ficha unificada de atenciones, cotizaciones territoriales, aceptación, generación de órdenes, control de anticipos, registro de recibos y portal del cliente. |
| **Fase Técnica 3**<br>*(Tratamientos, Catálogos y Operación)* | 19 | T036–T046, T079, T092, T097, T100, T107–T108, T111, T113. | Catálogos de plagas y productos, registro de tratamientos aplicados, persistencia de borradores entre dispositivos, publicación de atenciones y visualización del historial. |
| **Fase Técnica 4**<br>*(Agenda, Respaldo y Cierre Técnico)* | 25 | T052–T070, T077–T078, T096, T098, T114–T115. | Vistas de calendario, gestión de bloqueos de agenda, clasificación histórica por sede, pruebas integrales de seguridad y usabilidad con César, copias de seguridad y despliegue. |

##### Secuencia y orden crítico de trabajo técnico

- **Fase Técnica 1:** La definición de relaciones (T002) y estilos (T003) precede a las páginas de acceso y estructura del menú (T004, T005). La configuración de clientes y ubicaciones (T015–T020) precede a las reglas de asociación y permisos de sede (T081). El contenido y número de WhatsApp (T101) preceden a la landing y al formulario de contacto público (T102–T104).
- **Fase Técnica 2:** El registro rápido (T105) precede al listado general de atenciones (T026). La orden de servicio (T084) precede a las decisiones de aceptación (T032, T033, T083). La configuración territorial y tarifas (T080, T082) preceden a la cotización formal. La confirmación de pagos (T089) es prerrequisito para habilitar el inicio de la visita (T091). La integración de formularios en la ficha de atenciones (T106) unifica la operativa de César.
- **Fase Técnica 3:** Los catálogos (T036–T039) son prerrequisito para registrar el tratamiento real (T041, T042). El servicio registrado (T040, T106) precede al motor de borradores (T107) y concurrencia (T108). La publicación del servicio (T044) precede a su consulta en el historial del cliente (T045).
- **Fase Técnica 4:** La historia previa por sede (T096) se clasifica antes de validar el aislamiento total de datos (T059). Las pruebas de facilidad de uso (T114) y recorrido sin cuenta (T115) preceden a la redacción de la guía de usuario (T068) y la aceptación de César (T069). El entorno seguro (T062) precede a las rutinas de respaldo (T065) y pruebas de restauración (T067).

---

#### Criterios de terminación de tareas (Definition of Done - DoD)

Una tarea del plan técnico se considera formalmente terminada (**Done**) cuando:

1. **Cumplimiento funcional:** Satisface el resultado comprobable de su fila y las reglas de negocio descritas en la especificación del sistema.
2. **Robustez y validación:** Supera las validaciones de entrada, control de duplicados, integridad referencial y permisos de acceso por rol y sede.
3. **Diseño responsivo y accesibilidad:** Es completamente operable desde dispositivos móviles (pantallas pequeñas) y computadoras de escritorio, permitiendo navegación fluida y compatibilidad con teclado.
4. **Conservación de contexto:** Las acciones de guardar o cancelar formularios conservan el registro abierto, sus datos ingresados y los filtros de navegación aplicados.
5. **Revisión por pares (Peer Review):** El código, diseño o documento ha sido revisado por el otro integrante del equipo y los comentarios u observaciones han sido resueltos.
6. **Integración documental:** La tarea queda integrada en la versión consolidada del repositorio y su documentación de soporte se encuentra actualizada.

---

#### Dinámica de trabajo y ceremonias Scrum

| Evento Scrum | Periodicidad | Participantes | Objetivo y entregable |
| --- | --- | --- | --- |
| **Sprint Planning** | Inicio de cada Sprint (cada 2 semanas) | Brian y Jeremy | Revisar el objetivo del Sprint académico, seleccionar las tareas del backlog técnico pertinentes, analizar dependencias y confirmar la capacidad disponible. |
| **Daily Scrum** | En cada día de trabajo del equipo (10–15 min) | Brian y Jeremy | Sincronización breve: ¿Qué se completó en la última jornada? ¿Qué se trabajará hoy? ¿Existe algún impedimento o bloqueo? |
| **Sesión de enlace con el negocio** | Semanal (~20 min) | Brian, Jeremy y César | Consultar dudas de negocio, validar tarifas, formatos de comprobantes y flujos operativos según disponibilidad de César. |
| **Sprint Review** | Al finalizar cada Sprint (~30 min) | Brian, Jeremy y César (cuando aplique) | Demostrar los entregables del Sprint (documentos, wireframes o componentes funcionales), recibir retroalimentación y verificar el valor aportado. |
| **Sprint Retrospective** | Inmediatamente tras la Review | Brian y Jeremy | Analizar el desempeño del equipo: qué funcionó bien, qué dificultades surgieron y definir al menos un compromiso concreto de mejora para el siguiente ciclo. |

---

#### Seguimiento, control y gestión de cambios

- **Control de avance:** Al cierre de cada Sprint, el equipo contrasta el trabajo planificado contra el trabajo efectivamente terminado. Las tareas que no alcancen la Definición de Terminado se reevalúan y se replanifican según prioridades y capacidad.
- **Gestión de cambios de alcance:** Cualquier ajuste significativo en las funcionalidades, reglas de negocio o requerimientos de César o del profesor se documenta formalmente evaluando su triple restricción (alcance, tiempo y esfuerzo).
- **Estimación en Semana 5:** Durante el Sprint 3 (Semanas 5–6), se realizará la estimación formal del esfuerzo del backlog técnico aplicando la técnica y nivel de detalle indicados por la cátedra en la Semana 5 (Gestión del tiempo y costos), estableciendo la línea base definitiva de tiempo y presupuesto del proyecto.
