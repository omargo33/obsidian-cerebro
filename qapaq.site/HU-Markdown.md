---
tags:
  - hu
fecha: 2026-09-13
---
# *API distribuye Markdown*
## Descripción

|   Elemento | Descripcion                                                                |
| ---------: | -------------------------------------------------------------------------- |
|   **Como** | Como aplicativo cliente                                                    |
| **Quiero** | Quiero distribuir archivos Markdown para que se visualice en app web REACT |
|   **Para** | Facilitar la presentación de detalle                                       |
## Criterio Aceptación 

1. ==En el api== Se solicita un json GET, con un atributo con el contenido de .md.
2. El contenido esta codificado para ser leido desde una carpeta del sistema operativo
3. El ciente web debe poder llamar a este API con seguridad
---
## 🏁 Tareas

- [ ] Crear API de markdonw  [priority:: medium]  [due:: 2026-09-13]
	- [x] Asegurar el API  [due:: 2026-09-13]  [completion:: 2026-09-20]
	- [x] Implementar API-REST client  [due:: 2026-09-13]  [completion:: 2026-09-20]
	- [ ] Implementar en:  [due:: 2026-09-13]
		- [x] Políticas de seguridad  [due:: 2026-09-13]  [completion:: 2026-09-20]
		- [ ] Ley de datos publicos  [due:: 2026-09-13]
		- [ ] Contenido  [due:: 2026-09-13]
			- [ ] Contenido hero [due:: 2026-09-13]
			- [ ] Contenido Scraping [due:: 2026-09-13]
			- [ ] Contenido Qbic [due:: 2026-09-13]

---
### 💡Ideas

Seria buena idea que al no presentar o no encontrar el elemento, este envié igual un documento "vació" con información del hecho