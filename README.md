# README.MD: Settings VS Code
## Configurações básicas do Visual Studio Code para trabalhar com desenvolvimento web/mobile.

![Image VS Code - Settings](Image-VSCode.png)

## Como utilizar:
- No seu VS Code entre no menu File > Preferences > Settings.
- Altere o arquivo .json das configurações do VS Code conforme abaixo.
- Cada linha está comentada, explicando sua funcionalidade.

## Configurando o arquivo "settings.json":

{<br>
  "window.zoomLevel": 0.2, //Zoom no editor<br>
  "workbench.iconTheme": "material-icon-theme", // ícones para extensões dos arquivos<br>
  "workbench.colorTheme": "Dracula", // tema principal<br>
  "workbench.startupEditor": "newUntitledFile", //abrir novo arquivo com este nome<br>
  "editor.fontFamily": "Fira Code", // fonte do font ligatures<br>
  "editor.fontSize": 14, // tamanho padrão da fonte do editor<br>
  "editor.fontLigatures": true, // font ligatures habilitado<br>
  "editor.rulers": [80, 120], // máximo de caracteres por linha=80, não ultrapassar de 120 de forma alguma<br>
  "editor.renderLineHighlight": "gutter", // borda da linha<br>
  "editor.tabSize": 2, // espaçamento em tab<br>
  "terminal.integrated.fontSize": 14, // tamanho da fonte do terminal<br>
  "emmet.includeLanguages": { // criar html de forma mais rápida<br>
    // Emmet não funciona em arquivos react, adicionar javascript no emmet<br>
      "javascript": "javascriptreact" // Add javascript no emmet<br>
  },<br>
  "emmet.syntaxProfiles": {<br>
    "javascript": "jsx" // add jsx no emmet<br>
  },<br>
  "javascript.updateImportsOnFileMove.enabled": "never", // tenta trocar as importações, alterar para never<br>
  "editor.parameterHints.enabled": false, // desabilita caixa de mensagens ao editar código<br>
  "breadcrumbs.enabled": true, // local onde o arquivo está na estrutura de pasta<br>
  "javascript.suggest.autoImports": false, // VSCode sugere dados para importar na edição do código.<br>
}<br><br>

{
  "window.zoomLevel": 0.2, //Zoom no editor
  "workbench.iconTheme": "material-icon-theme", // ícones para extensões dos arquivos
  "workbench.colorTheme": "Dracula", // tema principal
  "workbench.startupEditor": "newUntitledFile", //abrir novo arquivo com este nome
  "editor.fontFamily": "Fira Code", // fonte do font ligatures
  "editor.fontSize": 14, // tamanho padrão da fonte do editor
  "editor.fontLigatures": true, // font ligatures habilitado
  "editor.rulers": [80, 120], // máximo de caracteres por linha=80, não ultrapassar de 120 de forma alguma
  "editor.renderLineHighlight": "gutter", // borda da linha
  "editor.tabSize": 2, // espaçamento em tab
  "terminal.integrated.fontSize": 14, // tamanho da fonte do terminal
  "emmet.includeLanguages": { // criar html de forma mais rápida
    // Emmet não funciona em arquivos react, adicionar javascript no emmet
      "javascript": "javascriptreact" // Add javascript no emmet
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx" // add jsx no emmet
  },
  "javascript.updateImportsOnFileMove.enabled": "never", // tenta trocar as importações, alterar para never
  "editor.parameterHints.enabled": false, // desabilita caixa de mensagens ao editar código
  "breadcrumbs.enabled": true, // local onde o arquivo está na estrutura de pasta
  "javascript.suggest.autoImports": false // VSCode sugere dados para importar na edição do código.
}
