# vs-code-snippets
Visual Studio Code - Snippets

## React

```json
"Function Component": {
"scope": "",
"prefix": "abc Create Component File",
"body": [
	"import React from 'react'",
	"import { Style } from './${1:name}.style';",
	"",
	"interface Props {",
	"// props go here",
	"}",
	"",
	"const ${1:name} = ({}: Props) => {",
	"	return (",
	"		<Style>",
	"			{/* ${2:start-here}  */}",
	"		</Style>",
	"	);",
	"}",
	" ",
	"export default ${1:name};",
],
"description": "Create Function Component"
},
```
