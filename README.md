# vscode-config
personal vscode config



## List of extensions :

Contains extensions for node, vuejs, PHP, npm

```
bajdzis.vscode-twig-pack
christian-kohler.npm-intellisense
christian-kohler.path-intellisense
dbaeumer.vscode-eslint
donjayamanne.githistory
ecmel.vscode-html-css
eg2.vscode-npm-script
felixfbecker.php-debug
felixfbecker.php-intellisense
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
humao.rest-client
jasonnutter.search-node-modules
joelday.docthis
mubaidr.vuejs-extension-pack
octref.vetur
oysun.vuehelper
robertohuertasm.vscode-icons
shinnn.stylelint
xabikos.JavaScriptSnippets
```

Note that `mubaidr.vuejs-extension-pack` install multiple extensions as dependencies

## Base configuration (in progress) :
```
{
    // ES
    "eslint.enable": true,
    "eslint.autoFixOnSave": true,
    "eslint.options": {
        "extensions": [".js", ".vue"]
    },
    "eslint.validate": [
        { "language": "vue", "autoFix": true },
        { "language": "html", "autoFix": true }
    ],
    //JSDOC
    "docthis.includeDescriptionTag": true,
    "docthis.inferTypesFromNames": true,

    // CSS/LESS
    "scss.lint.important": "error",
    "scss.lint.idSelector": "error",
    "less.lint.important": "error",
    "less.lint.idSelector": "error",
    "css.lint.important": "error",
    "css.lint.idSelector": "error",

    // TO COMPLETE
    "css.remoteStyleSheets": [],

    // other
    "npm-intellisense.scanDevDependencies": true
}
```

## Todo

Add Angular extensions
Add C# extensions
