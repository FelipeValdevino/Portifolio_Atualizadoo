# Portfolio Pessoal - José Felipe

Este é um portfolio pessoal moderno e responsivo, desenvolvido com HTML, CSS e JavaScript.

## Características

- Design moderno e responsivo
- Animações suaves
- Otimizado para impressão
- Compatível com todos os navegadores modernos
- Fácil de personalizar

## Estrutura do Projeto

```
portfolio/
├── index.html          # Arquivo HTML principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interatividade
└── README.md          # Este arquivo
```

## Como Executar o Portfolio

### Método 1: Abrir diretamente no navegador (mais simples)
1. Navegue até a pasta onde os arquivos do portfolio estão salvos
2. Dê um duplo clique no arquivo `index.html`
3. O portfolio será aberto automaticamente no seu navegador padrão

### Método 2: Usando um servidor local (recomendado)
#### Com Python:
1. Abra um terminal ou prompt de comando
2. Navegue até a pasta do projeto usando o comando `cd caminho/para/pasta`
3. Execute um dos seguintes comandos:
   - Para Python 3: `python -m http.server`
   - Para Python 2: `python -m SimpleHTTPServer`
4. Abra seu navegador e acesse: `http://localhost:8000`

#### Com Node.js:
1. Instale o pacote `http-server` globalmente: `npm install -g http-server`
2. Navegue até a pasta do projeto: `cd caminho/para/pasta`
3. Execute: `http-server`
4. Abra seu navegador e acesse: `http://localhost:8080`

### Método 3: Usando o VS Code com Live Server
1. Instale a extensão "Live Server" no VS Code
2. Abra a pasta do projeto no VS Code
3. Clique com o botão direito no arquivo `index.html`
4. Selecione "Open with Live Server"
5. O portfolio será aberto automaticamente no seu navegador padrão

### Verificação de funcionamento
- Confirme se todos os arquivos (`index.html`, `styles.css` e `script.js`) estão na mesma pasta
- Verifique se os ícones do Font Awesome estão sendo exibidos corretamente
- Teste a responsividade redimensionando a janela do navegador
- Verifique se as animações estão funcionando ao rolar a página

## Como Personalizar

### Cores

As cores principais podem ser alteradas editando as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #2c3e50;    /* Cor principal */
    --secondary-color: #3498db;  /* Cor secundária */
    --text-color: #333;          /* Cor do texto */
    --background-color: #f5f6fa; /* Cor de fundo */
    --section-background: #ffffff; /* Cor de fundo das seções */
}
```

### Conteúdo

Para atualizar o conteúdo:

1. Abra o arquivo `index.html`
2. Localize a seção que deseja modificar
3. Atualize o texto mantendo a estrutura HTML
4. Salve o arquivo e atualize o navegador

## Responsividade

O portfolio é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- Desktop (> 1200px)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## Compatibilidade

- Chrome (última versão)
- Firefox (última versão)
- Safari (última versão)
- Edge (última versão)

## Solução de Problemas

- **Os estilos não estão sendo aplicados**: Verifique se o arquivo `styles.css` está na mesma pasta que o `index.html`
- **As animações não funcionam**: Verifique se o arquivo `script.js` está na mesma pasta que o `index.html`
- **Os ícones não aparecem**: Verifique sua conexão com a internet, pois os ícones são carregados de um CDN
- **Problemas de responsividade**: Tente limpar o cache do navegador (Ctrl+F5 ou Cmd+Shift+R)


## Contato

Para sugestões ou dúvidas, entre em contato através do email: josefelipevaldevino@gmail.com 