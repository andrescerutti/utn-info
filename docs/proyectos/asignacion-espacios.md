# Asignación de Espacios y Aulas

**Estado:** piloto en preparación · **Última actualización:** 08/07/2026

## Contexto

Proyecto para un sistema de **asignación de espacios y aulas**, orientado a la
gestión de reservas, la ocupación en tiempo real y el circuito de incidencias de
los espacios de la facultad.

Se lleva adelante dentro del **ámbito académico**, junto a un grupo de estudiantes de
último año que lo toman como **proyecto final**, ya en coordinación con los docentes.

## Objetivos

### 1. Reserva de espacios e incidencias

- **Reserva de aulas/espacios:** un docente puede reservar el aula o el espacio que va a utilizar.
- **Reporte de incidencias:** desde esa aula, el docente puede reportar un problema (por ejemplo, algo que no funciona).
- **Visibilidad para mantenimiento:** el área de mantenimiento ve la incidencia reportada y la atiende, con trazabilidad del circuito.

### 2. Ocupación en tiempo real

- **Check-in / check-out por NFC:** al iniciar el uso de un aula, el usuario acerca su
  teléfono a la etiqueta del espacio y el sistema lo marca como **ocupado**; al
  finalizar, vuelve a quedar **libre**.
- **Estado de los espacios a la vista:** cualquier persona autorizada puede ver en
  tiempo real qué aulas están libres, reservadas u ocupadas.
- **Reasignación ágil:** si un espacio reservado no registra uso, puede liberarse y
  reasignarse a otra actividad.

## Prueba piloto (NFC)

El equipo avanza hacia una **prueba piloto** basada en etiquetas **NFC** para los
dispositivos que cuenten con esa tecnología.

- Ya se **compraron las etiquetas NFC** (vía Amazon) para las primeras pruebas.
- Los estudiantes tienen escritas las **historias de usuario** y los **requerimientos**.
- Está hecho el **diagrama de arquitectura de la base de datos**.
- Estimación: en aproximadamente **3 semanas** se empezarían las primeras pruebas en espacios específicos de la universidad.

## Problema e impacto

- Falta de trazabilidad en reservas e incidencias.
- Falta de visibilidad en tiempo real sobre qué espacios están libres u ocupados.
- Impacto esperado: mejor aprovechamiento de aulas y espacios, y mejor gestión de mantenimiento.

## Próximos pasos

- [x] Escribir las historias de usuario y los requerimientos.
- [x] Diseñar el diagrama de arquitectura de la base de datos.
- [x] Adquirir las etiquetas NFC para el piloto.
- [ ] Ejecutar las primeras pruebas piloto en espacios específicos (estimado: ~3 semanas).
- [ ] Diseñar el flujo de reporte de incidencias desde el aula y el circuito de atención por mantenimiento.
- [ ] Definir la integración con los sistemas existentes si aplica.

!!! note "Estado"
    El proyecto pasó de la definición funcional a la **preparación del piloto**: con
    requerimientos, historias de usuario y arquitectura de datos listos, el próximo
    hito son las primeras pruebas con NFC.
