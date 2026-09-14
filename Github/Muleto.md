
# Muleto

## Configuracion de variables y secretos:

Las variables y secretos de GitHub Actions se deben grabar ==en la **configuración del repositorio u organización** de GitHub==, y nunca directamente en el código fuente.

Aquí te detallo las rutas exactas y las diferencias:

🔐 Secretos (Información sensible)

Se usan para contraseñas, tokens de API, llaves SSH o credenciales que deben permanecer ocultas. Una vez guardados, se cifran y nadie los puede volver a ver en la interfaz.

- **Ruta:** Entra a tu repositorio en GitHub → **Settings** → **Secrets and variables** (en el menú izquierdo) → **Actions**.

- **Pestaña:** Quédate en la pestaña **Secrets**.

- **Creación:** Haz clic en **New repository secret**.

- **Cómo usarlos en el código:** `{{ secrets.NOMBRE_DEL_SECRETO }}`

📝 Variables de entorno (Información no sensible)

Se usan para datos de configuración que no son secretos, como nombres de entornos (`production`, `staging`), puertos, URLs públicas o nombres de usuarios públicos.

- **Ruta:** Entra a tu repositorio en GitHub → **Settings** → **Secrets and variables** → **Actions**.

- **Pestaña:** Haz clic en la pestaña **Variables**.

- **Creación:** Haz clic en **New repository variable**.

- **Cómo usarlas en el código:** `{{ vars.NOMBRE_DE_LA_VARIABLE }}`

---

🗂️ Niveles de almacenamiento

Dependiendo del alcance que necesites, puedes guardarlos en tres niveles distintos:

- **Repository (Repositorio):** Solo están disponibles para los flujos de trabajo de ese proyecto específico.

- **Environment (Entorno):** Ideal para despliegues. Permiten restringir secretos según el entorno (por ejemplo, que las llaves de producción solo se usen en la rama `main`) y añadir reglas de aprobación manual.

- **Organization (Organización):** Si tienes una cuenta de organización, puedes crearlos una sola vez y compartirlos entre múltiples repositorios.

Para ayudarte a configurarlos correctamente en tu flujo de trabajo, cuéntame:

- ¿Qué **tipo de dato** estás intentando guardar (un token, una URL, una contraseña)?

- ¿Necesitas usar estos datos para **múltiples entornos** (como desarrollo y producción)?