---
tags:
  - hu
fecha: 2026-09-13
---
# *API Envió Correo*
## Descripción

|   Elemento | Descripcion                                                       |
| ---------: | ----------------------------------------------------------------- |
|   **Como** | Como usuario del sitio de landingpage                             |
| **Quiero** | Quiero Solicitar información de la empresa vía correo(telefónico) |
|   **Para** | Facilitar la puesta en contacto con los usuarios                  |
## Criterio Aceptación 

1. Un usuario llena el formulario para solicitar información.
2. El correo debe enviarse a el mismo usuario
3. El usuario no puede enviar mas de un correo al día. revisar por IP de solicitud en 24 horas 
4. ==En el api== debe enviar un correo a las personas del team ventas de Qapaq dentro de la parametria del sistema.
---
## 🏁 Tareas

- [ ] Crear API para envió de correo [priority:: medium]  [due:: 2026-09-13]
	- [ ] Enviar correo con formato al solicitante
	- [ ] Enviar correos al team de la empresa
	- [x] Validar un envió cada (8 horas parametrizadas)  [completion:: 2026-09-14]

---
### 💡Ideas

Seria buena idea tener un solo `tool` de envio de correo por AWS