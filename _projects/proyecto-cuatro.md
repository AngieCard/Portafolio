---
layout: project
title: "Inscripción de porveedores"
order: 4
project_title: "Inscripción de porveedores"

image: "/assets/images/proyecto-cuatro.jpg"  # Coloca tu imagen en la carpeta assets/images
description: "El proyecto de Gestión de Proveedores es una solución diseñada para centralizar y organizar la información de los proveedores de la organización. Su objetivo principal es mejorar la administración de datos, garantizando la integridad y evitando la duplicación de registros que se observaba en el sistema anterior basado en formularios. Este nuevo enfoque permite llevar un historial de cada proveedor, facilitando el seguimiento y la trazabilidad de cualquier modificación o actualización en su información."
tags: ["Python","Django","Django REST Framework","Odoo API","Sharepoint API","HTML","CSS","JavaScript"]
# Datos adicionales para la página de detalle:

gallery:
  - "/assets/images/proyecto_4/proyecto4-2.png"
  - "/assets/images/proyecto_4/proyecto4-1.png" 
  - "/assets/images/proyecto_4/proyecto4-3.png"    
  - "/assets/images/proyecto_4/proyecto4-4.png"      
functionalities_intro: |
  El sistema se estructura en varios módulos que, en conjunto, permiten un manejo integral de la información de proveedores. A continuación se detalla cada uno de los aspectos clave del proyecto:
functionalities:
  - "Sistema de login nativo de Django: Utiliza la vista LoginView de django.contrib.auth para el inicio de sesión seguro."
  - "Registro y Actualización de Proveedores: Permite la creación y modificación de registros de proveedores de forma centralizada, incorporando mecanismos de validación que aseguran que la información ingresada sea única y correcta, evitando la duplicidad de registros y posibles errores en la identificación. Además, los datos se integran automáticamente con el ERP de Odoo, centralizando la información y facilitando la gestión eficiente de proveedores dentro de la organización."
  - "Consulta y Búsqueda: Facilita la búsqueda de proveedores a través de filtros y criterios, permitiendo a los usuarios encontrar rápidamente la información necesaria, ofreciendo una vista consolidada de todos los registros, lo que simplifica el seguimiento y la revisión de la información."
  - "Historial de Cambios: Se mantiene un registro detallado de todas las modificaciones realizadas en cada proveedor, Esta funcionalidad es crucial para rastrear la evolución de la información, detectar inconsistencias y analizar el proceso de actualización de datos a lo largo del tiempo,Esta funcionalidad es crucial para rastrear la evolución de la información, detectar inconsistencias y analizar el proceso de actualización de datos a lo largo del tiempo."
  - "Gestión Documental: Incorpora la capacidad de adjuntar y almacenar documentos relevantes relacionados con cada proveedor, asegurando que toda la documentación necesaria se encuentre centralizada, por medio de la integración con la API de SharePoint, garantizando que se organicen y gestionen en un entorno seguro y accesible. "
impact_cards:
  - title: "Productividad"
    content: "La automatización de la gestión de proveedores permite que la información se distribuya de forma centralizada: los datos generales se envían a Odoo y los documentos a SharePoint. En Odoo se genera automáticamente una URL que direcciona a la biblioteca documental con filtros predefinidos, lo que libera al equipo de tareas manuales. Esto no solo reduce la carga administrativa, sino que también mejora la coordinación entre áreas, permitiendo que los colaboradores se concentren en tareas estratégicas."
  - title: "Eficiencia"    
    content: "La integración entre Odoo y SharePoint agiliza la comunicación y el flujo de información. Al recibir datos estructurados en Odoo y contar con enlaces automáticos para acceder a los documentos filtrados, se optimizan procesos y se eliminan pasos intermedios. Esto asegura que tanto la información general como la documental estén disponibles de forma precisa y ordenada, minimizando errores y redundancias en la operación diaria."
  - title: "Tiempo de Respuesta"
    content: "El sistema optimiza la consulta de información al generar automáticamente enlaces en Odoo que direccionan a una biblioteca documental en SharePoint. Esta funcionalidad, junto con herramientas de búsqueda integradas y filtros predefinidos, permite acceder de forma rápida y sencilla a información estructurada y de alta calidad. Con estos mecanismos, se reduce la necesidad de contactar constantemente a los proveedores para verificar o solicitar datos, garantizando respuestas ágiles y precisas en la toma de decisiones."
---




