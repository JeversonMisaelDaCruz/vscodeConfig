Aqui está uma versão aprimorada e mais estilizada do Markdown, com a imagem aparecendo corretamente e sem a conclusão:

```md
# VSCode Configurações

Essa configuração torna seu VSCode mais clean e focado para o trabalho. Pessoalmente, prefiro visualizar apenas o código, e essas configurações refletem esse estilo minimalista.

---

## Interface do VSCode

### Novo Arquivo ao Iniciar

Abre automaticamente um arquivo em branco ao iniciar o VSCode, permitindo começar a trabalhar imediatamente.

```json
"workbench.startupEditor": "newUntitledFile"
```

### Fonte e Espaçamento

Melhora a legibilidade com um tamanho de fonte confortável e espaçamento adequado entre as linhas.

```json
"editor.fontSize": 15,
"editor.lineHeight": 1.8
```

### Barra de Status e Atividades

Remove a barra de status e a barra de atividades para uma interface mais limpa e sem distrações.

```json
"workbench.statusBar.visible": false,
"workbench.activityBar.visible": false
```

### Desativar Minimap

Foca na área de código ao desativar o minimap.

```json
"editor.minimap.enabled": false
```

---

## Importação e Validação

### Importações Automáticas

Facilita a importação automática de dependências ao mover ou modificar arquivos JavaScript e TypeScript.

```json
"javascript.suggest.autoImports": true,
"typescript.suggest.autoImports": true,
"typescript.updateImportsOnFileMove.enabled": "always"
```

### Validação de Código com ESLint

Configura ESLint para validar uma variedade de tipos de arquivos, garantindo consistência no estilo de código.

```json
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
```

---

## Visual Limpo e Minimalista

### Ocultar Scrollbar Vertical

Elimina a barra de rolagem vertical para uma aparência mais minimalista.

```json
"editor.scrollbar.vertical": "hidden"
```

### Exibir Pastas sem Compactação

Mantém as pastas no explorador de arquivos em seu formato completo, evitando a compactação automática.

```json
"explorer.compactFolders": false
```

### Ícones Personalizados

Utiliza um tema de ícones personalizado para facilitar a identificação visual dos arquivos.

```json
"workbench.iconTheme": "vscode-icons"
```

---

## Terminal Integrado

### Aparência do Terminal

Define uma fonte legível e um tamanho confortável para o terminal integrado.

```json
"terminal.integrated.fontSize": 14,
"terminal.integrated.fontFamily": "JetBrainsMono mono"
```

### Aceleração de GPU no Terminal

Melhora o desempenho gráfico do terminal integrado ao ativar a aceleração por GPU.

```json
"terminal.integrated.gpuAcceleration": "on"
```

### Perfis de Terminal

Configura perfis de terminal personalizados, como Fish no macOS e Ubuntu no Windows (WSL).

```json
"terminal.integrated.defaultProfile.osx": "fish",
"terminal.integrated.defaultProfile.windows": "Ubuntu (WSL)"
```

---

## Plugins e Extensões

### Codeium para Sugestões de Código

Habilita o **Codeium** para sugestões de código assistidas por IA, com foco em projetos **Prisma**.

```json
"codeium.enableConfig": {
  "*": true,
  "prisma": true
}
```

---

## Melhoria de Performance

### Ocultar Arquivos e Pastas Desnecessários

Esconde arquivos e pastas que não são essenciais, como `node_modules` e `.git`, mantendo o explorador de arquivos limpo.

```json
"files.exclude": {
  "**/CVS": true,
  "**/.DS_Store": true,
  "**/.hg": true,
  "**/.svn": true,
  "**/.git": true,
  ".vscode": true,
  "node_modules": true
}
```

### Salvamento Automático e Formatação

Ativa o salvamento automático e formatação do código ao salvar o arquivo, mantendo o código sempre organizado.

```json
"files.autoSave": "afterDelay",
"editor.formatOnSave": true
```

---
 
```

