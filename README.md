# README.MD: Settings VS Code
## Configurações básicas do Visual Studio Code para trabalhar com desenvolvimento web/mobile.

![Image VS Code - Settings](Image-VSCode.png)

## Como utilizar:
- No seu VS Code entre no menu File > Preferences > Settings.
- Altere o arquivo .json das configurações do VS Code conforme abaixo.
- Cada linha está comentada, explicando sua funcionalidade.

## Configurando o arquivo "settings.json":

```javascript
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
```

## Extensões:
### As extensões abaixo são necessárias para deixar o VS Code ainda mais interessante.

- material-icon-theme: Esta extensão coloca um ícone (icon) ao lado do nome de cada arquivo salvo dentro do seu projeto no VS Code, facilitando a visualização do arquivo.
- Dracula: Ao instalar esta extensão é possível deixar o visual do VS Code com uma aparência mais moderna, proporcionando melhor visualização de suas linhas de códigos.
- color highlight: deixar a formatação do código hexadecimal exatamente com a cor da tag. Ao estilizar seu código em um arquivo .css, você terá a cor da tag que está usando no exato momento.
- Rocketseat ReactJS e Rocketseat React Native: Estes dois plugins foram desenvolvidos pela empresa Rocketseat e ajudam a agilizar a criação de arquivos javascripts (.js, .jsx).

## Font Ligatures:
### Faz a junção de caracteres deixando o seu código ainda melhor de visualizar. Exemplo: Ao usar o sinal de "==" ou "==="  ou "!=" a font ligatures irá ligar os caracteres. Para isso é necessário instalar uma fonte especial chamada Fira Code.

- Fira Code:<br>
'- Procurar e baixar esta fonte da Internet.<br>
'- Descompactar e instalar apenas as fontes que estão na pasta "ttf".<br>
'- Abra um novo arquivo no VS Code e digite os sinais "==", ou "===', ou "!=". Você vai perceber que os caracteres ficarão com um visual diferenciado.<br>
'- OBS: Pode ser necessário reinicar o VS Code para que esta fonte tenha efeito.<br>


Feito com 🧡 by Edenir de Souza 😉