---
layout: project
title: "Reporte de Novedades"
project_title: "Reporte de Novedades"
order: 2

image: "/assets/images/proyecto-uno.png"  # Coloca tu imagen en la carpeta assets/images
description: "Este proyecto es un sistema web de registro y gestión de novedades laborales que facilita a los empleados reportar ausencias, ingresos, retiros, cambios de zona y más, mediante formularios inteligentes y dinámicos. Incluye validaciones automáticas y conexión en tiempo real con sistemas externos, ofreciendo una interfaz amigable para una experiencia de usuario moderna y eficiente."
tags: ["Python","Django","Django REST Framework","Odoo API","Azure Blob Storage","Azure AD","OAuth 2.0","HTML","CSS","JavaScript"]
# Datos adicionales para la página de detalle:
project_summary: "Resumen del proyecto. Aquí se explica detalladamente el objetivo y el contexto de la aplicación..."
technologies: ["Python", "Django", "REST"]
gallery:
  - "/assets/images/proyecto_1/proyecto1-1.png"
  - "/assets/images/proyecto_1/proyecto1-2.png"
functionalities_intro: |
  El sistema web de gestión de novedades laborales está diseñado para optimizar la administración de reportes laborales, permitiendo a los empleados registrar novedades operativas de la organización. La plataforma ofrece una interfaz intuitiva y dinámica, asegurando una experiencia de usuario fluida y eficiente. Además, integra múltiples validaciones automáticas y conexiones en tiempo real con sistemas externos para garantizar la precisión y actualidad de los datos. Las funcionalidades del sistema están diseñadas para facilitar la gestión y el seguimiento de las novedades laborales, mejorando la eficiencia operativa y la comunicación dentro de la organización:
functionalities:
  - "Autenticación de Usuarios: Inicio y cierre de sesión, incluyendo integración con Microsoft 365."
  - "Pantalla de Bienvenida: Listado detallado de empleados (nombre, identificación, zona, departamento y correo)."
  - "Selección de Zona: Confirmación o corrección de información antes de reportar novedades."
  - "Formulario Dinámico: Adaptación según el tipo de reporte (ausencias, ingresos, retiros, etc.)."
  - "Validación de Fechas: Registro de justificaciones fuera del horario establecido."
  - "Cálculo Automático: Cantidad de horas o días basado en fechas y horarios ingresados, incluyendo cálculos específicos para novedades especiales."
  - "Carga y Selección Dinámica: Rutas, zonas y colaboradores mediante llamadas asíncronas."
  - "Reporte de Reemplazos: Reportes de reemplazos de otros usuarios basándose en el correo electrónico."
  - "Envío de Datos: Almacenamiento en listas de SharePoint."
  - "Conexión con Odoo ERP: Validación de empleados, zonas y datos básicos del ERP."
  - "Validaciones Internas: Restricción de sesiones, registros de log y control de fechas."
  - "Odoo ERP: Obtención de zonas y empleados con sus rutas asociadas."
  - "API Externa: Validación de fecha límite de reporte diario y necesidad de justificación."
  - "Azure Blob Storage: Carga de archivos estáticos como CSS personalizados y logotipos."
impact_cards:
  - title: "Productividad"
    content: "El sistema elimina procesos manuales que antes requerían llamadas, correos y aprobaciones físicas, permitiendo a los empleados registrar novedades de manera rápida, directa y organizada a través de formularios inteligentes."
  - title: "Eficiencia"
    content: "Al digitalizar la captura de información como cédulas, zonas y rutas, se eliminan los errores comunes de transcripción que antes ocurrían en procesos manuales en papel, mejorando la precisión de los reportes y asegurando datos confiables que impactan positivamente en la productividad operativa."
  - title: "Tiempo de Respuesta"
    content: "Gracias a la integración con el sistema Odoo ERP y validaciones automáticas en el frontend, las novedades se verifican y registran de forma instantánea, reduciendo significativamente los tiempos de respuesta ante ausencias, cambios de turno o ingresos."
---

