# template-vuejs

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Configuration VS code Lint
Extentions :
- vetur
- vue 3 snippets
- eslint (edit in settings.json) :
```
{
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
    "eslint.run": "onSave",
    "eslint.autoFixOnSave": true,
    "eslint.validate": [
        {
          "language": "vue",
          "autoFix": true
        },
        {
          "language": "html",
          "autoFix": true
        },
        {
          "language": "javascript",
          "autoFix": true
        }
      ],
      "editor.accessibilitySupport": "off"
}
```

