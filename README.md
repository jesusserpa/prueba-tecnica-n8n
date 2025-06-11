# 🧪 Prueba Técnica con n8n – Automatización de Agencia de Desarrollo

Este proyecto demuestra un flujo de automatización creado con n8n, simulando el funcionamiento de una agencia de desarrollo de software que gestiona la captación de clientes y la coordinación de reuniones de forma automatizada.


📌 Descripción del Flujo
El flujo automatiza todo el proceso desde la captación del cliente hasta el registro de su información, pasando por la confirmación de reuniones. Se integran varias herramientas para lograr una experiencia fluida:


🔄 Herramientas Utilizadas

n8n
Typeform	         
Gmail	             
Cal.com API	      
Google Sheets	     


🔧 Detalle del Flujo Automatizado
1. Captación de Clientes
El usuario completa un formulario en Typeform detallando su necesidad.

Al enviarse el formulario, n8n activa un trigger que:

Envía un correo automático de dando un saludo y mostrando la url de Cal para agendar la reunión.


2. Agendamiento de Reunión
Cuando un cliente agenda una reunión mediante Cal.com, se activa un evento:

Se envía un correo de confirmación al cliente.

Se registra automáticamente la información de la reserva en una hoja de Google Sheets para mantener un control interno.


📸 Vista del Flujo en n8n:

![image](https://github.com/user-attachments/assets/5f80ac42-3603-4d3c-99e2-e4d7f288cd7b)



