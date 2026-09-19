
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

openspec init
```

# En tu proyecto:

```bash
cd tu-proyecto
openspec init          # Inicializa OpenSpec en el proyecto
```
# Comandos principales:

![[openspec-workflows.png]]

## Video

![Video](https://www.youtube.com/watch?v=-A7seYcvNZo)
