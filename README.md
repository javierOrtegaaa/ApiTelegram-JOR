# ApiTelegram-JOR
🌐 Proyecto de Automatización Web – Javier Ortega Reina

Autor: Javier Ortega Reina
Correo: ortegareinajavier@gmail.com

Teléfono: +34 747 483 279

🧩 Descripción del Proyecto

Este proyecto forma parte del Trabajo de Fin de Grado del ciclo de Desarrollo de Aplicaciones Web.
El objetivo ha sido construir un sistema completo que integra:

🌍 Una página web moderna desarrollada en Framer

🔄 Flujos de automatización creados en n8n

🧠 Una API propia alojada en Render

🗄️ Una base de datos SQLite, gestionada con DBeaver

El sistema permite recibir datos desde la web, procesarlos con automatizaciones y almacenarlos, además de enviar correos automáticos cuando es necesario.

🎨 1. Página Web en Framer

La web funciona como interfaz principal del proyecto.

✨ Características principales:

Diseño responsive

Interfaz moderna y visual

Secciones:

Cabecera con navegación

Hero principal

Contacto

Funcionalidades conectadas con la API

Publicación sencilla e integración con servicios externos

Framer permitió desarrollar una web fluida y enfocada en la experiencia de usuario sin necesidad de escribir demasiado código.

🤖 2. Automatizaciones en n8n

Se desarrollaron dos flujos principales que conectan la web, la API y los correos automáticos.

💬 2.1 Chatbot

Este flujo:

Recibe datos enviados desde la web

Procesa los campos en formato JSON

Genera respuestas o activa otros bloques

Puede interactuar con la API cuando se necesita

📧 2.2 Gmail Bot

Automatiza el envío de correos:

Detecta eventos específicos (por ejemplo, formularios enviados)

Obtiene datos del usuario

Construye el email

Lo envía automáticamente mediante Gmail

n8n fue esencial como pieza central de la automatización del proyecto.

🛠️ 3. API REST alojada en Render

La API funciona como punto de conexión entre la web, n8n y la base de datos.

📌 Funciones principales:

Recibir datos enviados desde formularios o flujos

Procesar información

Operaciones CRUD

Responder en formato JSON

Enviar eventos a n8n

🌐 ¿Por qué Render?

Fácil despliegue

Logs en tiempo real

Variables de entorno

Plan gratuito funcional

🗃️ 4. Base de Datos SQLite con DBeaver

SQLite se utilizó por su simplicidad, ligereza y compatibilidad.

📋 Funciones:

Almacenar registros enviados desde la API

Comprobar datos en tiempo real con DBeaver

Administrar tablas, tipos y estructura general

Realizar pruebas de inserción y consulta

La base de datos demuestra el flujo completo:
Web → API → SQLite → (opcional) n8n → Gmail

🧠 5. Dificultades y Aprendizajes

Durante el desarrollo, surgieron diversos retos:

Conectar correctamente Framer → API → n8n

Manejar errores de servidor y dependencias en Render

Estructurar y validar datos en SQLite

Trabajar con JSON en automatizaciones complejas

Estos desafíos fortalecieron habilidades en backend, automatización, despliegue y diseño web.

✅ 6. Conclusión

El proyecto integra tecnologías modernas utilizadas actualmente en el sector:

Parte	Tecnología
Frontend	Framer
Automatización	n8n
Backend	API REST en Render
Base de datos	SQLite + DBeaver

El resultado es un sistema funcional, automatizado y totalmente conectado.
Una experiencia muy enriquecedora que combina frontend, backend, automatización y diseño de sistemas.

👤 Autor

Javier Ortega Reina
📧 ortegareinajavier@gmail.com

📱 +34 747 483 279
