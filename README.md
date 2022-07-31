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



```
## Lista Konfiguracji w Terminalu:  
```
npx create-react-app nazwa --use-npm
npm install husky --save-dev
npx husky install
npx husky add .husky/pre-commit "npm run pre-commit"
w package.json do "scripts" dodajemy: "pre-commit": "lint-staged"

jsconfig.json
```
{
  "compilerOptions": {
    "baseUrl": "src"
  },
  "include": ["src"]
}
```

npm install eslint --global


.prettierrc 
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
  "parser": "babel-eslint"
}
```
.eslintrc

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
      },
      "error",
      {
        "endOfLine": "auto"
      }

    ]
 
    ,
    "import/first": 0
  },
  "env": {
    "browser": true,
    "node": true,
    "es6": true
  },
  "parser": "babel-eslint"
}




````



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

