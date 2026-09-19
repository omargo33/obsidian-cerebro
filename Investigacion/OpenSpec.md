
OpenSpec es un framework de desarrollo driven por specs para asistentes de AI. Tiene sus propios skills diseñados para su CLI (@fission-ai/openspec), no para MiMoCode directamente.
Lo que OpenSpec ofrece:
- /opsx:propose - Crear una propuesta de cambio con specs
- /opsx:explore - Explorar opciones antes de comprometerse
- /opsx:apply - Implementar las tareas de una propuesta
- /opsx:archive - Archivar cambios completados
- Y otros comandos más
Para usarlo en tu proyecto, necesitarías:
# 1. Instalar el CLI globalmente
```bash
npm install -g @fission-ai/openspec@latest
# 2. Inicializar en tu proyecto
cd tu-proyecto
```
openspec init
Esto instalará los skills en tu proyecto y registraría los comandos slash.
Perfecto, voy a instalar OpenSpec globalmente para que puedas usarlo desde cualquier terminal.
Instalado. Verifico que funciona:
OpenSpec v1.13.1 instalado globalmente. Ya puedes usarlo desde cualquier terminal.
Uso básico:
# En tu proyecto:
cd tu-proyecto
openspec init          # Inicializa OpenSpec en el proyecto
# Comandos principales:
openspec change        # Gestionar propuestas de cambio
openspec list          # Listar cambios y specs
openspec view          # Dashboard interactivo
openspec spec          # Gestionar especificaciones
openspec archive       # Archivar cambios completados
openspec doctor        # Diagnosticar problemas
openspec config        # Configuración
Los slash commands (/opsx:propose, /opsx:explore, /opsx:apply) funcionan dentro de asistentes de AI compatibles (Cursor, Copilot, Claude, etc.) después de hacer openspec init.