# Visual Studio Code


## Lista ustawień: 
```js 


{
  "workbench.colorTheme": "Tokyo Night Storm",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#ffd700",
    "editorBracketHighlight.foreground2": "#ff00ff",
    "editorBracketHighlight.foreground3": "#00bfff",
    "editorBracketHighlight.foreground4": "#7cfc00",
    "editorBracketHighlight.unexpectedBracket.foreground": "#ff0000"
  },
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 1000,
  "breadcrumbs.enabled": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "explorer.confirmDragAndDrop": false,
  "editor.formatOnSave": true,
  "editor.insertSpaces": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.linkedEditing": true,
  "editor.cursorBlinking": "expand",
  "editor.wordWrap": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "prettier.arrowParens": "avoid",
  "prettier.jsxSingleQuote": true,
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "prettier.useTabs": false,
  "prettier.printWidth": 180,

  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"],
  "window.zoomLevel": 0,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "emmet.syntaxProfiles": {
    "html": {
      "inline_break": 2
    }
  },
  "emmet.variables": {
    "lang": "pl"
  },
  "codesnap.containerPadding": "10px",
  "codesnap.backgroundColor": "transparent",
  "codesnap.boxShadow": "rgba(0, 0, 0, 0.3) 5px 5px 10px",
  "workbench.startupEditor": "none",
  "css.lint.unknownAtRules": "ignore",
  "css.lint.unknownVendorSpecificProperties": "warning",
  "css.lint.boxModel": "warning",
  "editor.quickSuggestions": {
    "strings": true
  },
  "tailwindCSS.includeLanguages": {
    "plaintext": "html , css , javascript"
  },
  "eslint.alwaysShowStatus": true,
  "eslint.format.enable": true,
  "editor.formatOnType": true,
  "html.format.enable": false,
  "prettier.trailingComma": "all",
  "prettier.tabWidth": 2
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

Community Material Theme
v1.4.4

GitLens — Git supercharged
v12.2.0

Tailwind CSS IntelliSense
v0.8.7

Tailwind Snippets
v1.0.1

TypeScript Hero
v3.0.0

Typescript React code snippets
v1.3.1



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




