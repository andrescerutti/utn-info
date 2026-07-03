# Asignación de Espacios y Aulas

**Estado:** piloto en preparación · **Última actualización:** 03/07/2026

## Contexto

Proyecto para un sistema de **asignación de espacios y aulas** con un **doble
propósito**: por un lado la gestión de reservas e incidencias de las aulas, y por
otro el control de asistencia y horas de los docentes.

Se lleva adelante dentro del **ámbito académico**, junto a un grupo de estudiantes de
último año que lo toman como **proyecto final**, ya en coordinación con los docentes.

## Objetivos

### 1. Reserva de espacios e incidencias

- **Reserva de aulas/espacios:** un docente puede reservar el aula o el espacio que va a utilizar.
- **Reporte de incidencias:** desde esa aula, el docente puede reportar un problema (por ejemplo, algo que no funciona).
- **Visibilidad para mantenimiento:** el área de mantenimiento ve la incidencia reportada y la atiende, con trazabilidad del circuito.

### 2. Control de asistencia docente

- Registrar la **asistencia** de cada docente.
- Registrar la **cantidad de horas trabajadas** de cada docente, en el aula y en la facultad en general.

## Prueba piloto (NFC)

El equipo avanza hacia una **prueba piloto** basada en etiquetas **NFC** para los
dispositivos que cuenten con esa tecnología.

- Ya se **compraron las etiquetas NFC** (vía Amazon) para las primeras pruebas.
- Los estudiantes tienen escritas las **historias de usuario** y los **requerimientos**.
- Está hecho el **diagrama de arquitectura de la base de datos**.
- Estimación: en aproximadamente **3 semanas** se empezarían las primeras pruebas en espacios específicos de la universidad.

## Problema e impacto

- Falta de trazabilidad en reservas e incidencias.
- Ausencia de un control centralizado de asistencia y horas.
- Impacto esperado: mejora operativa y mejor gestión de mantenimiento y de RR.HH.

## Próximos pasos

- [x] Escribir las historias de usuario y los requerimientos.
- [x] Diseñar el diagrama de arquitectura de la base de datos.
- [x] Adquirir las etiquetas NFC para el piloto.
- [ ] Ejecutar las primeras pruebas piloto en espacios específicos (estimado: ~3 semanas).
- [ ] Diseñar el flujo de reporte de incidencias desde el aula y el circuito de atención por mantenimiento.
- [ ] Especificar el módulo de control de asistencia y horas docentes (criterios de registro y reportes).
- [ ] Definir la integración con los sistemas existentes si aplica.

!!! note "Estado"
    El proyecto pasó de la definición funcional a la **preparación del piloto**: con
    requerimientos, historias de usuario y arquitectura de datos listos, el próximo
    hito son las primeras pruebas con NFC.
