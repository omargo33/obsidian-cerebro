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
|   **Para** | Facilitar la presentación de detalle                              |
## Criterio Aceptación 

1. ==En el api== Se solicita un json GET, con un atributo con el contenido de .md.
2. El contenido esta codificado para ser leido desde una carpeta del sistema operativo
3. El ciente web debe poder llamar a este API con seguridad
---
## 🏁 Tareas

- [ ] Crear API de markdonw  [priority:: medium]  [due:: 2026-09-13]
	- [ ] Asegurar el API  [due:: 2026-09-13]
	- [ ] Implementar API-REST client  [due:: 2026-09-13]
	- [ ] Implementar en:  [due:: 2026-09-13]
		- [ ] Políticas de seguridad  [due:: 2026-09-13]
		- [ ] Ley de datos publicos  [due:: 2026-09-13]
		- [ ] Contenido  [due:: 2026-09-13]
			- [ ] Contenido hero [due:: 2026-09-13]
			- [ ] Contenido Scraping [due:: 2026-09-13]
			- [ ] Contenido Qbic [due:: 2026-09-13]

---
### 💡Ideas

Seria buena idea que al no presentar o no encontrar el elemento, este envié igual un documento "vació" con información del hecho