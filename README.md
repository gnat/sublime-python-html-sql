# Highlight HTML + SQL in Python for Sublime!

## Screenshot

![image](https://user-images.githubusercontent.com/24665/183111942-9d6e8dc7-6b82-47fb-9492-07d25ffc6523.png)

## 🚨 Install Instructions

Direct: `Preferences` ➡️ `Browse Packages ...` ➡️ `cd User` ➡️ [Download and extract the latest.](https://github.com/gnat/sublime-python-html/archive/refs/heads/main.zip)

Package Control: `Primary+P` ➡️ `Package Control: Add Repository` ➡️ `https://github.com/gnat/sublime-python-html` ➡️ `Primary+P` ➡️ `Package Install` ➡️ `sublime-python-html`

Use it: `View` ➡️ `Syntax` ➡️ `User` ➡️ `Python (HTML)`

## Suggested Sublime Color Schemes

* [Invader Zim](https://github.com/gnat/sublime-invader-zim) 🛸
* Mariana (Built-in)
* Monokai (Built-in)

Pairs well with:
* Darkstar: https://github.com/lllama/dark-star
* Raw strings for Jinja.

## Alternative for VS Code / Codium

* https://github.com/ptweir/python-string-sql

## Bonus! Dark background color for embedded blocks.

Use it: `Preferences` ➡️ `Customize Color Scheme`

```json
{
	"rules":
	[
		{
			"name": "sql highlight",
			"scope": "source.sql",
			"background": "hsl(180, 0%, 3%)"
		},
		{
			"name": "py highlight",
			"scope": "string.quoted.double.block.python",
			"background": "hsl(180, 0%, 3%)"
		},
		{
			"name": "py highlight2",
			"scope": "source.js.embedded.html",
			"background": "hsl(180, 0%, 3%)"
		},
		{
			"name": "py highlight3",
			"scope": "text.html.basic",
			"background": "hsl(180, 0%, 3%)"
		},
	]
}

```
