# Visual Studio Code


## Lista ustawień: 
```js 


{
	"liveServer.settings.donotShowInfoMsg": true,
	"explorer.confirmDragAndDrop": false,
	"editor.wordWrap": "on",
	"editor.linkedEditing": true,
	"editor.cursorBlinking": "expand",
	"editor.tabCompletion": "on",
	"workbench.iconTheme": "material-icon-theme",
	"security.workspace.trust.enabled": false,
	"breadcrumbs.enabled": false,
	"editor.bracketPairColorization.enabled": true,
	"workbench.colorCustomizations": {
		"editorBracketHighlight.foreground1": "#ffd700",
		"editorBracketHighlight.foreground2": "#ff00ff",
		"editorBracketHighlight.foreground3": "#00bfff",
		"editorBracketHighlight.foreground4": "#7cfc00",
		"editorBracketHighlight.unexpectedBracket.foreground": "#ff0000"
	},

	"emmet.syntaxProfiles": {
		"html": {
			"inline_break": 2
		}
	},
	"emmet.variables": {
		"lang": "pl",
		"charset": "UTF-8"
	},
	"emmet.includeLanguages": {
		"orb": "html",
		"javascript": "javascriptreact"
	},
	"emmet.excludeLanguages": [],
	"emmet.triggerExpansionOnTab": true,
	"workbench.colorTheme": "Community Material Theme",
	"git.autofetch": true,
	"typescript.format.insertSpaceAfterTypeAssertion": true,
	"files.autoSave": "afterDelay",
	"prettier.printWidth": 150,
	"prettier.jsxSingleQuote": true,
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.formatOnType": true,
	"editor.formatOnSave": true,
	"editor.formatOnPaste": true,
	"prettier.useTabs": true,
	"eslint.alwaysShowStatus": true,
	"eslint.format.enable": true,
	"javascript.updateImportsOnFileMove.enabled": "always",
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[json]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},

	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"prettier.singleQuote": true,
	"prettier.withNodeModules": true,
	"html.format.indentInnerHtml": true,
	"html.format.templating": true
}







```

## Lista wtyczek:  
```

JavaScript (ES6) code snippets
v1.8.0
charalampos karypidis

Live Sass Compiler
v5.4.0
Glenn Marks

Live Server
v5.7.5

Material Icon Theme
v4.19.0

Sass
v1.8.22

Reactjs code snippets
v2.4.0

Tokyo Night
v0.8.9
enkia

ESLint
v2.2.6

Prettier - Code formatter
v9.5.0

vscode-styled-components
v1.7.4

Node.js Modules Intellisense
v1.5.0

```
## Lista Konfiguracji 
```

"devDependencies"
"@babel/core": "^7.18.9",
    "@babel/parser": "^7.18.9",
    "@babel/preset-env": "^7.18.9",
    "babel-loader": "^8.2.5",
    "eslint": "^8.21.0",
    "eslint-config-airbnb": "^19.0.4",
    "eslint-config-prettier": "^8.5.0",
    "eslint-plugin-import": "^2.26.0",
    "eslint-plugin-jsx-a11y": "^6.6.1",
    "eslint-plugin-prettier": "^4.2.1",
    "eslint-plugin-react": "^7.30.1",
    "eslint-plugin-react-hooks": "^4.6.0",
    "prettier": "^2.7.1",
    "webpack": "^5.74.0"
    
    "dependencies": {
    "@babel/eslint-parser": "^7.18.9",
    "@testing-library/jest-dom": "^5.16.4",
    "@testing-library/react": "^13.3.0",
    "@testing-library/user-event": "^13.5.0",
    "lodash": "^4.17.21",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "styled-components": "^5.3.5",
    "web-vitals": "^2.1.4"
    
    ```
    
```
## .prettierrc

```


{
  "singleQuote": true,
  "printWidth": 150,
  "endOfLine": "auto"
}


```
 ## .eslintrc

```
{
  "extends": ["react-app", "react-app/jest", "plugin:prettier/recommended", "prettier"],
  "plugins": ["prettier"],
  "rules": {
    "prettier/prettier": [
      "warn",
      {
        "singleQuote": true,
        "printWidth": 150
      }
    ],
    "import/first": 0
  },
  "env": {
    "browser": true,
    "node": true,
    "es6": true
  },
  "parser": "@babel/eslint-parser"
}










```
## Snippets:  
```



Configure user snipets : javascript 
https://snippet-generator.app/
 react components skrót :
{
  "": {
    "prefix": "rc",
    "body": [
      "import React from 'react'",
      "import PropTypes from 'prop-types'",
      "",
      "",
      "const $1 = () => (",
      "  ",
      "    <div>$0</div>",
      "  )",

      "$1.propTypes = {}",
      "",
      "export default $1"
    ],
    "description": "React Component"
  }
}




