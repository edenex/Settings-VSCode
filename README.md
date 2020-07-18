# Settings VS Code
## Configurações básicas do Visual Studio Code para trabalhar com desenvolvimento web/mobile.

![Image VS Code - Settings](Image-VSCode.png)

## :black_nib: Como utilizar:
- No seu VS Code entre no menu ***File > Preferences > Settings***.
- Altere o arquivo ***"settings.json"*** das configurações do VS Code conforme abaixo.
- Cada linha está comentada, explicando sua funcionalidade.

## :dart: Configurando o arquivo "settings.json":

```javascript
{
  "window.zoomLevel": 0.2, //Zoom no editor
  "workbench.iconTheme": "material-icon-theme", // ícones para extensões dos arquivos
  "workbench.colorTheme": "Dracula", // tema principal
  "workbench.startupEditor": "newUntitledFile", //abrir novo arquivo com este nome
  "editor.fontFamily": "Fira Code", // fonte do font ligatures
  "editor.fontSize": 14, // tamanho padrão da fonte do editor
  "editor.fontLigatures": true, // font ligatures habilitado
  "editor.rulers": [80, 120], // cria barras verticais no seu editor, nas colunas 80 e 120, auxiliando o desenvolvedor a saber que está na hora de pular de linha
  "editor.renderLineHighlight": "gutter", // borda da linha
  "editor.tabSize": 2, // espaçamento em tab
  "terminal.integrated.fontSize": 14, // tamanho da fonte do terminal
  "emmet.includeLanguages": { // criar html de forma mais rápida
    // Emmet não funciona em arquivos react, adicionar javascript no emmet
      "javascript": "javascriptreact" // adiciona javascript no emmet
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx" // adiciona jsx no emmet
  },
  "javascript.updateImportsOnFileMove.enabled": "never", // tenta trocar as importações, alterar para "never"
  "editor.parameterHints.enabled": false, // desabilita caixa de mensagens ao editar código
  "breadcrumbs.enabled": true, // o local exato em que você está trabalhando no seu código é exibido na parte superior do seu editor
  "javascript.suggest.autoImports": false // VS Code sugere dados para importar na edição do código.
}
```

## :gear: Extensões:
### As extensões abaixo são necessárias para deixar o VS Code ainda mais interessante.

- **material-icon-theme**: Esta extensão coloca um ícone (icon) ao lado do nome de cada arquivo salvo dentro do seu projeto no VS Code, facilitando a visualização do arquivo.
- **Dracula**: Ao instalar esta extensão é possível deixar o visual do VS Code com uma aparência mais moderna, proporcionando melhor visualização de suas linhas de códigos.
- **color highlight**: deixar a formatação do código hexadecimal exatamente com a cor da tag. Ao estilizar seu código em um arquivo .css, por exemplo, você terá a cor da tag que está usando no exato momento.
- **Rocketseat ReactJS** e **Rocketseat React Native**: Estes dois plugins foram desenvolvidos pela empresa Rocketseat e ajudam a agilizar a criação de arquivos javascripts.
- OBS: Pode ser necessário reinicar o VS Code para que estas extensões tenham efeito.

## :pencil2: Font Ligatures:
### Faz a junção de caracteres deixando o seu código ainda melhor de visualizar. Exemplo: Ao usar o sinal de "==" ou "==="  ou "!=" a font ligatures irá ligar os caracteres. Para isso é necessário instalar uma fonte especial chamada Fira Code.

- **Fira Code**:
  - Procurar e baixar esta fonte da Internet.
  - Descompactar e instalar apenas as fontes que estão na pasta "ttf".
  - Abra um novo arquivo no VS Code e digite os sinais "==", ou "===', ou "!=". Você vai perceber que os caracteres ficarão com um visual diferenciado.
  - OBS: Pode ser necessário reinicar o VS Code para que esta fonte tenha efeito.

---
Feito com 🧡 by [Edenir de Souza](https://github.com/edenex) 😉
