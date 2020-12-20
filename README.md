# sass-masterclass-rocketseat
<a href="https://www.youtube.com/watch?v=BaI8dHUthLA">Vídeo</a>

## Desabilitando Compactação do arquivo

Pressione as teclas `CTRL+SHIFT+P`  

Procure por **Settings(json)**, e edite conforme abaixo:  

Vá em Live Sass Compiler > Settings: Formats
```json
{
    "breadcrumbs.enabled": true,
    "editor.renderWhitespace": "all",
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorTheme": "Dracula",
    "liveSassCompile.settings.autoprefix": [
        " "
    ],
    "liveSassCompile.settings.formats": [
    
        {
            "format": "expanded", // Outras opções também como, "compressed(comprimido)", expanded(expandido)
            "extensionName": ".css",
            "savePath": null
        }
    ]
}
```