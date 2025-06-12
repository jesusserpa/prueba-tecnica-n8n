# 🧪 Prueba Técnica con n8n – Automatización de Agencia de Desarrollo

Este proyecto demuestra un flujo de automatización creado con n8n, simulando el funcionamiento de una agencia de desarrollo de software que gestiona la captación de clientes, el agendamiento de reuniones y el registro de datos, todo de forma automática y eficiente.


🎯 Objetivo
Automatizar el proceso de atención inicial al cliente, desde que completa un formulario con sus necesidades hasta que agenda una reunión con el equipo de desarrollo, registrando toda la información relevante para su posterior seguimiento.


🔄 Herramientas Utilizadas

n8n
Typeform	         
Gmail	             
Cal.com API	      
Google Sheets	     


🧩 Descripción del Flujo Automatizado

1. ✍️ Captación de Clientes (Typeform)
- El cliente completa un formulario en Typeform especificando sus necesidades.

- n8n detecta automáticamente el envío del formulario y ejecuta:

- Un correo automático de saludo con un mensaje personalizado.

- Se incluye en el correo el enlace a Cal.com para agendar una reunión.


2. 📅 Agendamiento de Reunión (Cal.com)

Cuando el cliente agenda una reunión usando Cal.com, se activa un nuevo evento en n8n:

- Se envía un correo de confirmación al cliente con los detalles de la cita.

- Se guarda automáticamente la información de la reserva en una Google Sheet, permitiendo un registro interno para seguimiento.


🖼️ Vista del Flujo en n8n


![image](https://github.com/user-attachments/assets/f8e87709-36f9-4ba7-95ba-cb30a0d84c8c)



🎥 Video Explicativo
Mira el funcionamiento completo del flujo en este video:

🔗 [https://youtu.be/Nxd1xYBx67s](https://drive.google.com/file/d/1klTvr4yfxF8elqJgDpXRgFWMR9scEFOm/view?usp=sharing)


🌐 JSDevs – Landing Page del Proyecto

Puedes visitar la landing page creada para este flujo en:

🔗 https://js-devs-co.netlify.app/
    

✅ Criterios Técnicos Cubiertos
 Escucha de nuevo formulario (Typeform)

 Extracción y uso dinámico de datos

 Envío de correos personalizados (Gmail)

 Integración con API externa (Cal.com)

 Registro de información en Google Sheets

 

📌 Conclusión
Este flujo demuestra la capacidad de conectar herramientas externas, automatizar procesos de contacto con clientes y mantener un registro ordenado, sin necesidad de escribir código, utilizando n8n como motor principal de automatización.




