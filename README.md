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
  "workbench.colorTheme": "Tokyo Night Storm",
  "git.autofetch": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnPaste": true, // required
  "editor.formatOnType": true, // required
  "editor.formatOnSave": true, // optional
  "editor.formatOnSaveMode": "file",
  "files.autoSave": "afterDelay",
  "typescript.format.insertSpaceAfterTypeAssertion": true,
  "eslint.format.enable": true,
  "prettier.printWidth": 150,
  "prettier.singleQuote": true,
  "prettier.useTabs": true // required to format on save
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

Prettier - Code formatter
v9.5.0

Sass
v1.8.22

ES7+ React/Redux/React-Native snippets
v4.4.3    (rafcp - tworzenie funkcyjne komponentu)

Tokyo Night
v0.8.9
enkia

ESLint
v2.2.6

Prettier ESLint
v5.0.4




```
## Lista Konfiguracji w Terminalu:  
```
npx create-react-app nazwa // instaluje tez Node_modules
npm install husky --save-dev
npm install --save-dev lint-staged
npm i styled-components


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








```

