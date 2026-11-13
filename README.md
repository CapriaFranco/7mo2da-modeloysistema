# Sistema de Gestión de Préstamos de Pañol Escolar

Proyecto de documentación técnica y de diseño realizado para la materia **Modelos y Sistemas** (7mo Año, Escuela Técnica).

## Qué se hizo

Se diseñó y documentó un sistema web simple para administrar el pañol escolar, cubriendo las dos vistas principales de funcionamiento:

* **Vista de Usuario (Alumnos y Profesores):** Permite solicitar herramientas o materiales indicando la cantidad y la fecha de devolución, además de consultar el estado de los préstamos activos y cuándo vencen.
* **Vista de Administrador (Encargado de Pañol):** Permite controlar el stock disponible, aprobar o rechazar solicitudes pendientes, detectar devoluciones atrasadas y generar pedidos de compra para reponer insumos.

## Por qué se hizo

En el pañol de la escuela el registro de herramientas prestadas, fechas de entrega y faltantes de stock suele llevarse de forma manual. El objetivo de este proyecto es plantear una solución ordenada y fácil de usar que centralice los pedidos, evite pérdidas de materiales y alerte cuando hace falta reponer insumos.

## Stack tecnológico

* **Frontend:** HTML5, CSS3, React.js
* **Backend:** Node.js, Express (API REST)
* **Base de Datos:** PostgreSQL
* **Autenticación y Despliegue:** JWT, BCrypt, Docker, Nginx

## Índice del repositorio

* `documentacion.md`: Documento principal con las 7 fases de documentación, preguntas conceptuales, caso de uso formal, paso a paso, y diagramas.
* `pert-y-gantt.md`: Desarrollo del caso práctico de planificación mediante diagramas PERT y Gantt, camino crítico, holguras y cuadro comparativo.
* `img/`: Carpeta con los bocetos visuales de interfaz (`01_login.jpg`, `02_panel_usuario.jpg`, `03_panel_admin.jpg`), el diagrama de flujo (`06_diagrama_flujo.png`) y los diagramas de planificación (`04_diagrama_pert.png`, `05_diagrama_gantt.png`).

## Autor

* **Franco Capria** (7mo Año)
