# Laravel Project Setup

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