# Laravel Project Setup

`settings.json`
```json
{
    // Laravel Blade Optimization
    "blade.format.enable": true,
    "[blade]": {
        "editor.autoClosingBrackets": "always",
        "editor.defaultFormatter": "onecentlin.laravel-blade"
    },

    // PHP Intelephense Configuration
    "php.validate.enable": true,
    "php.suggest.basic": true,
    "intelephense.stubs": [
        "vendor/laravel/framework/src/Illuminate"
    ], 

    // Workspace-Specific Path Configuration
    "intelephense.environment.includePaths": [
        "app",
        "config",
        "database" 
    ],

    // Formatting and Validation
    "editor.formatOnSave": true,  
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },

    // Optional: Laravel-Specific Snippets (Install the extension)
    "emmet.includeLanguages": {
        "blade": "html" 
    }
}
```

`.prettierrc`
```json
{
  "printWidth": 100,
  "tabWidth": 2,
  "useTabs": false,
  "semi": true,
  "singleQuote": true,
  "trailingComma": "es5",
  "bracketSpacing": true,
  "arrowParens": "avoid",
  "overrides": [
    {
      "files": "*.blade.php",
      "options": {
        "parser": "blade"
      }
    }
  ]
}
```