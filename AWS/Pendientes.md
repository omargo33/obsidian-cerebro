---
tags:
  - requisitos
fecha: 2026-09-13
---
# AWS

Servicios comprados en AWS y sus configuraciones [Link](https://aws.amazon.com/es/)
## Servicio de Correo `SES`

El servicio SES requiere de dos  configuraciones la primera para interactuar con API y la segunda con SMTP

> [!NOTE]
> - Esta anclado a mi usuario  <omargo33@gmail.com> y al tarjeta de **Bankard**
> - Ambas configuraciones se hacen con el archivo .csv para la configuración.

### SMTP

Para smtp, se debe configurar desde "SMTP de Mail Manager" en "Configuración de SMTP" se debe descargar el *.csv con la información del servidor* y luego se configura en el server de keycloak con estos datos.
### API

Para API,  se debe configurar desde "Credenciales SMTP de IAM" en "Configuración de SMTP" se debe descargar el *.csv con la información del servidor* y luego se configura en el server de keycloak con estos datos.

## 🏁 Tareas

- [ ] Crear una libreria comun para el envió de correos, configurable.  [priority:: highest]  [due:: 2026-09-13]

---
### 💡Ideas
