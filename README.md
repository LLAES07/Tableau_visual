# Visualización Futbolística con Tableau

Este proyecto se centra en el desarrollo de herramientas de **visualización de datos** utilizando **Tableau Public** para analizar información futbolística en el contexto de la **Champions League**. El objetivo fue proporcionar insights claros y visualmente atractivos que apoyen la toma de decisiones estratégicas relacionadas con equipos rivales y potenciales contrataciones.

---

## Descripción del Proyecto

El proyecto nace de la necesidad de un **análisis integral del panorama futbolístico** para un equipo profesional de una ciudad española. Para lograrlo, diseñé y desarrollé dashboards interactivos que permiten explorar datos clave sobre equipos, jugadores y competiciones.

Los datos utilizados provienen de diversas fuentes, procesadas y modeladas para garantizar una visualización coherente. Entre ellos:
- **players.csv**: Información detallada de jugadores (datos personales, clubes, posiciones).
- **clubs.csv**: Listado maestro de equipos.
- **competitions.csv**: Información de ligas y competiciones.
- **goal_games.csv**: Registro de goles por partido/equipo.
- **game_events.csv**: Datos de goles por jugador.
- **games.csv**: Listado de partidos.
- **player_valuations.csv**: Valoraciones económicas de los jugadores.

---

## Funcionalidades Implementadas

### Modelo de Datos
Diseñé un modelo relacional que conecta las diferentes tablas de datos para una integración eficiente y confiable, considerando relaciones clave como:
- Relación entre jugadores y clubes mediante `Current Club Id`.
- Conexión de clubes con ligas mediante `Competition Id`.

### Análisis Exploratorio
Para entender mejor los datos, creé visualizaciones exploratorias que responden a preguntas como:
- **Países y ligas:** ¿De qué países provienen los equipos? ¿Cuántos equipos hay por liga?
- **Equipos goleadores:** ¿Cuáles fueron los 10 equipos más goleadores en 2021?
- **Diferencia de goles:** ¿Cómo se distribuyen las diferencias de goles en los partidos?

### Dashboard Interactivo de Rendimiento
Diseñé un tablero que permite analizar:
- **Rendimiento ofensivo y defensivo** de los equipos.
- **Cantidad de victorias**.
- **Valoración económica** de los equipos.

### Filtro para Contrataciones
Para apoyar decisiones estratégicas, desarrollé un dashboard que permite:
- Filtrar jugadores por posición (delantero o arquero).
- Ajustar criterios de edad (22-30 años) y valoración económica (< €30M).
- Visualizar estadísticas relevantes como goles anotados y competiciones en las que participan.

---

## Desafíos y Soluciones
- **Modelado de Datos:** Se implementaron relaciones complejas para integrar múltiples tablas de manera eficiente.
- **Interactividad:** Incorporé filtros dinámicos que permiten una exploración personalizada de los datos.
- **Visualización:** Se aplicaron buenas prácticas de diseño para garantizar claridad, coherencia y atractivo visual.

---

## Herramientas y Tecnologías
- **Tableau Public**: Creación de dashboards y gráficos interactivos.
- **Data Wrangling**: Limpieza y transformación de datos para asegurar integridad.

---

## Resultados
Ir a carpeta resultados

## Enlace al Proyecto
El proyecto está publicado en **Tableau Public**. Puedes acceder al dashboard interactivo [aquí](#).

---


