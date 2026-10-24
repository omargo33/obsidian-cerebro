---
tags:
  - general
---
# Cerebro

*Segundo Cerebro*
## Configuración

- **Navigator**: 
	- https://github.com/johansan/notebook-navigator 
	- https://www.youtube.com/watch?v=m2maDNtho7Y
- **Advanced Tables**: https://github.com/tgrosinger/advanced-tables-obsidian
- **Excalidraw** https://github.com/zsviczian/obsidian-excalidraw-plugin
- **Simple mind map**: https://github.com/wanglin2/obsidian-simplemindmap
- **Git Sync**: https://github.com/livan116/github-valut-sync
- **Plantila**: https://github.com/silentvoid13/Templater
- **Tareas**: 
	- https://github.com/obsidian-tasks-group/obsidian-tasks
	- https://www.youtube.com/watch?v=jTT8P1nFIOM&t=1687s
## 🌐 Links

- **Cloud**: https://www.ovhcloud.com/es/
- **DNS**: https://www.namecheap.com/
- **Repositorio**: https://github.com/omargo33
- **Qapaq**: https://qapaq.site/
- **CheckFind**: https://www.checkfind.lat/
- **Diseno**: [38Sitios](https://www.reddit.com/r/webdev/comments/15x3eph/38_websites_you_can_use_for_cool_backgrounds/?tl=es-419)
- **Coolors.co**: https://coolors.co/
- **AWS**: https://aws.amazon.com/
- **JDK-25**: [Descarga](https://www.oracle.com/java/technologies/javase/jdk25-archive-downloads.html)
- **Texto ASCII para identificación**: https://fsymbols.com/es/generadores/tarty/
## 🤖 Mimo

Para agente de IA de desarrollo se usa *mimo* de [mimoCode](https://mimo.xiaomi.com/mimocode) y tiene la configurado:


> [!warning]
> El agente esta pagado plan básico, y debe ser revisado periódicamente.

### Skill

#### [[Archify]]

- **Url**: https://github.com/tt-a1i/archify
- **promt**: Tengo este sitio https://github.com/tt-a1i/archify puedes usar el skill que aca se describe
- **promt**: Agrégalo como skill a nivel global
- *Uso* una vez instalado reiniciar el chatbot y se puede llamar usando el comando <code>'/archify' </code>


TasteSkill
- **Url**: https://www.tasteskill.dev/
- Install: `npx skills add Leonxlnx/taste-skill`
- Se debe instalar el redesing-existing-project <- revisa en google los tools del sking
- **promt**: `/openspec-propose revisemos el diseno del aplicativo con una skill de redesing-existing-projects`
- **promt**: `/openspec-update-change puedes agregar en la propuesta, que use de manera purista el framework de radix-iu.`

MCP

. **Maven**: el MCP de MAVEN se configura de dos maneras, global o local por proyecto, y en: `.mimocode/mimocode.jsonc` `~/.config/mimocode/mimocode.jsonc`

En donde se agrega:

```bash
{
	"$schema": "https://mimo.xiaomi.com/mimocode/config.json",
	"mcp": {
		"maven-tools": {
		"type": "local",
		"command": ["npx", "-y", "mcp-maven-deps"],
		"enabled": true
		}
	}
}
```

Luego ejecutas `npm install -g mcp-maven-deps` y usas mimo para estas labores. 


[[OpenSpec]]

- **Url**: https://github.com/Fission-AI/OpenSpec/
- **promt**: Tengo este sitio https://github.com/Fission-AI/OpenSpec/ puedes usar el skill que aca se describe
- *Uso* una vez instalado se puede llamar usando el comando <code>'/archify' </code>

#### VS-Code

Para los sistemas se usa configuraciones de extensiones para tres distintos perfiles en la `extensions.json`:

**JAVA**
```bash
{
	"recommendations": [
		"bowlerr.offline-markdown-preview",
		"esbenp.prettier-vscode",
		"github.vscode-github-actions",
		"humao.rest-client",
		"jcruz.openspec-viewer",
		"lennardv.set-window-color-name",
		"ms-azuretools.vscode-containers",
		"redhat.fabric8-analytics",
		"streetsidesoftware.code-spell-checker-spanish",
		"WakaTime.vscode-wakatime",
		"zaaack.markdown-editor",
	]
}
```

**Python**
```bash
{
	"recommendations": [
		"esbenp.prettier-vscode",
		"github.vscode-github-actions",
		"lennardv.set-window-color-name",
		"ms-python.debugpy",
		"ms-python.python",
		"ms-python.vscode-python-envs",
		"ms-toolsai.jupyter",
		"WakaTime.vscode-wakatime",
		"streetsidesoftware.code-spell-checker-spanish"
	]
}
```

**WEB**
```bash
{
	"recommendations": [	
		"bowlerr.offline-markdown-preview",
		"esbenp.prettier-vscode",
		"idered.npm",
		"Jacano.vscode-pnpm",
		"jcruz.openspec-viewer",
		"kisstkondoros.vscode-gutter-preview",
		"lennardv.set-window-color-name",
		"ms-vscode.live-server",
		"rvest.vs-code-prettier-eslint",
		"usernamehw.errorlens",
		"WakaTime.vscode-wakatime",
		"zaaack.markdown-editor",
		"streetsidesoftware.code-spell-checker-spanish"
	]
}
```

---
*2026-09-12*<br/>**<#omargo33>**
