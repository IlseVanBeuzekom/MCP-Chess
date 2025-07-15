Install this MCP server by adding the following JSON code to your JSON configuration file:

```json
{
  "mcpServers": {
	"chess":{
		"command": "uvx",
		"args": [
            "--from",
            "git+https://github.com/IlseVanBeuzekom/MCP-Chess.git",
			"chess"
		]
	}
  }
}
```