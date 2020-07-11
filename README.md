# denotest

## vscode

install deno extension then use this workspace settings:
```json
{
	"folders": [
		{
      "path": "denotest"
		}
	],
	"settings": {
		"deno.importmap": "./dependencies.json"
	}
}