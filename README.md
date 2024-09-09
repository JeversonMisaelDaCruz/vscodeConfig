##VSCODE CONFIGS
- Esta configuração torna seu vscode mais clean para se trabalhar, da minha parte eu prefiro somente vizualizar o codigo e esta configuração e um inicio disso.

![Screenshot from 2024-09-09 16-19-18](https://github.com/user-attachments/assets/c9832cbc-5f36-4aa3-9df4-660cbec40602)

## 1. Editor e Interface Geral

```json
"workbench.startupEditor": "newUntitledFile"
Abre um novo arquivo em branco ao iniciar o VSCode.

## FONTE

"editor.fontSize": 15,
"editor.lineHeight": 1.8
Define o tamanho da fonte para 15px e ajusta o espaçamento vertical entre as linhas para melhorar a legibilidade.

##BARRA STATUS

"workbench.statusBar.visible": false,
"workbench.activityBar.visible": false

Oculta a barra de status e a barra de atividades para uma interface mais limpa.


##DESATIVA MINIMAP

"editor.minimap.enabled": false

## IMPORTAÇÕES AUTOMÁTICAS

"javascript.suggest.autoImports": true,
"typescript.suggest.autoImports": true,
"typescript.updateImportsOnFileMove.enabled": "always"

##FORMATADORES E VALIDAÇÕES

"eslint.validate": [
  "javascript",
  "javascriptreact",
  "graphql",
  "typescript",
  "typescriptreact",
  "json",
  "jsonc",
  "java"
]

## OCULTAR ELEMENTOS VISUAIS

"editor.scrollbar.vertical": "hidden"
"explorer.compactFolders": false
"workbench.iconTheme": "symbols"

## TERMINAL

"terminal.integrated.fontSize": 14,
"terminal.integrated.fontFamily": "JetBrainsMono mono",
"terminal.integrated.gpuAcceleration": "on"

## ATIVA ACELERAÇÃO GPU

"terminal.integrated.defaultProfile.osx": "fish",
"terminal.integrated.defaultProfile.windows": "Ubuntu (WSL)"

##PLUGINS

"codeium.enableConfig": {
  "*": true,
  "prisma": true
}










