---
layout: project
title: "Contrataciones"
order: 1

project_title: "Contrataciones"
image: "/assets/images/proyecto-tres.png"  # Coloca tu imagen en la carpeta assets/images
description: "Este sistema backend se enfoca en centralizar y optimizar el proceso de contratación dentro de una organización. Su propósito es gestionar de manera integral la información de usuarios, contratos y documentación, facilitando la integración con otros sistemas empresariales y garantizando que toda la información relevante esté disponible de forma segura y organizada. En esencia, la plataforma sirve como la columna vertebral tecnológica para apoyar, automatizar y agilizar los procesos administrativos relacionados con la contratación y gestión de personal."
tags: ["Python","Django", "Django REST Framework", "drf_yasg","PostgreSQL","django-cors-headers","WhiteNoise","python-dotenv","XML-RPC",]
# Datos adicionales para la página de detalle:

gallery:
  - "/assets/images/proyecto_3/proyecto3-3.png"
  - "/assets/images/proyecto_3/proyecto3-2.png"
  - "/assets/images/proyecto_3/proyecto3-1.png"
  - "/assets/images/proyecto_3/proyecto3-4.png" 
  - "/assets/images/proyecto_3/proyecto3-5.png" 
  - "/assets/images/proyecto_3/proyecto3-6.png"
  - "/assets/images/proyecto_3/proyecto3-7.png"
functionalities_intro: |
  Este sistema backend, desarrollado con Django y Django REST Framework, está orientado a la gestión integral de procesos de contratación y administración de contratistas. Incorpora autenticación y autorización mediante tokens, manejo avanzado de usuarios a través de un modelo personalizado, gestión de contratos y contratistas, procesamiento masivo de información vía archivos Excel y administración de documentos (incluyendo conversiones a Base64 para almacenamiento controlado). Además, integra servicios externos como Odoo para consultar datos de compañías y dispone de una documentación interactiva de la API utilizando Swagger, algunas funcionalidades son:
functionalities:
  - "Registro y Creación de Usuarios: Se implementa un modelo de usuario personalizado (CustomUser) que extiende AbstractUser, permitiendo registrar nuevos usuarios con información ampliada. Los serializadores se encargan de validar datos como contraseñas (incluyendo confirmación) y otros atributos esenciales (como cédula, tipo de documento y correo electrónico)."
  - "Autenticación y Generación de Tokens: El sistema utiliza Django REST Framework para gestionar la autenticación mediante tokens, permitiendo que los usuarios inicien sesión y obtengan credenciales que se usan para acceder a endpoints protegidos."
  - "Restablecimiento de Contraseña: Se ofrecen endpoints para solicitar y confirmar el restablecimiento de contraseñas. La solicitud se procesa enviando un correo con un enlace seguro (con token y UID) que, al acceder, permite actualizar la contraseña del usuario."
  - "Creación y Eliminación de Contrataciones: Se exponen endpoints para crear nuevas contrataciones, permitiendo definir detalles como nombre del proyecto, tipo de contratación, fechas de inicio y fin, descripción y número de vacantes. También existe un endpoint para eliminar contrataciones de forma segura"
  - "Gestión de Contratistas: Los contratistas se asocian a las contrataciones mediante relaciones que vinculan un usuario con un contrato específico. La aplicación valida que no se repita la vinculación para un mismo contrato y permite la asociación de roles y estados específicos (como Pendiente, Aprobado, Contratado, etc.)."
  - "Carga Masiva de Contratistas: Para optimizar la incorporación de datos, se ha implementado la carga masiva de contratistas utilizando archivos Excel. La integración con la biblioteca Openpyxl permite leer, validar y procesar los datos de cada fila, generando registros de forma automática y reportando errores en el caso de datos inconsistentes."
  - "Subida y Almacenamiento de Documentos: Los usuarios pueden subir documentos (por ejemplo, certificados, cédulas, constancias, etc.) a través de un endpoint que utiliza campos en Base64 para recibir y convertir archivos, garantizando que se almacenen con nombres y rutas personalizadas que facilitan su identificación."
  - "Consulta y Actualización de Documentos: Se ofrece un endpoint para que los usuarios consulten sus documentos, el cual retorna URLs absolutas para la previsualización de archivos. Adicionalmente, se permite la actualización parcial de los documentos mediante validaciones en el serializador correspondiente."
  - "Conexión con Odoo: La función de integración a través de XML-RPC permite conectar el sistema con Odoo para extraer datos de compañías. Esta funcionalidad facilita la sincronización de información corporativa y la integración de servicios empresariales externos en el proceso de contratación."
  - "Validación de documentos por OCR: El sistema utiliza los servicios de azure vision para realizar un analisis del documento, ayudando al usuario a dar un pre-aprobado de este."
  - "Documentación Interactiva con Swagger: Restricción de sesiones, registros de log y control de fechas."
  - "Gestión de CORS y Archivos Estáticos: Se emplea django-cors-headers para permitir el acceso seguro desde dominios externos (útil para el frontend) y WhiteNoise para servir archivos estáticos de forma eficiente en entornos de producción."
  - "Configuración de Variables de Entorno y Seguridad: La integración de python-dotenv permite la carga de variables sensibles (como credenciales de base de datos y configuración SMTP), mientras que el uso de PostgreSQL garantiza robustez y escalabilidad en la gestión de la información."
  - "Envío de Correos Electrónicos: El sistema utiliza el backend SMTP (configurado con Gmail) para enviar correos electrónicos tanto para la recuperación de contraseñas como para notificaciones de creación de usuario y contratista, mejorando la comunicación y seguridad del proceso."
impact_cards:
  - title: "Productividad"
    content: "El software centraliza y automatiza procesos clave, eliminando tareas manuales y redundantes, lo que incrementa la cantidad de trabajo que se puede gestionar con el mismo equipo."
  - title: "Eficiencia"    
    content: "La integración de datos y la automatización de flujos de trabajo reducen errores humanos y simplifican la administración, optimizando la operación de cada proceso de contratación."
  - title: "Tiempo de Respuesta"
    content: "La automatización y conexión con sistemas externos permiten respuestas más ágiles en la toma de decisiones, mejorando significativamente la rapidez en la atención y gestión de solicitudes."
---



