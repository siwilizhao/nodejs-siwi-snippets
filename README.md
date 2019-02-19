
# vscode user snippets for nodejs

## example

```json
{
  "Print to console": {
    "prefix": "log",
    "body": [
      "console.log('$1');",
      "$2"
    ],
    "description": "Log output to console"
  }
}
```

## Immediately Invoked Async Function Expression

```json
{
  "Immediately Invoked Async Function Expression": {
		"prefix": "iife async",
		"body": [
			"(async () => {",
			"    ",
			"})()"
		],
		"description": "Immediately Invoked Async Function Expression"
	},
}
```

## Immediately Invoked Function Expression

```json
{
  "Immediately Invoked Function Expression": {
		"prefix": "iife",
		"body": [
			"(async () => {",
			"    ",
			"})()"
		],
		"description": "Immediately Invoked Function Expression"
	},
}
```