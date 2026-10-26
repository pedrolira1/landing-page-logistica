# RotaLog — Landing page de logística

Landing page de uma transportadora fictícia, a **RotaLog**, que oferece frete marítimo, aéreo e rodoviário, armazenagem e rastreamento de cargas.

🔗 **Página publicada:** https://pedrolira1.github.io/landing-page-logistica/

## Sobre o projeto

Este projeto começou como um trabalho da faculdade, feito a partir de um template da [W3layouts](https://w3layouts.com/). Anos depois, voltei a ele para transformá-lo em uma peça de portfólio: a versão original não funcionava publicada (as imagens não existiam no repositório e o CSS não carregava no GitHub Pages) e ainda tinha textos de exemplo.

## O que eu melhorei

- **CSS carregando no GitHub Pages:** o HTML pedia `style.css`, mas o arquivo se chamava `Style.css`. No Windows isso funciona, mas o GitHub Pages diferencia maiúsculas de minúsculas. Renomeei o arquivo com `git mv`.
- **Imagens:** as imagens que faltavam foram substituídas por ícones SVG da biblioteca Lucide e por fotos livres de direitos do Unsplash, já redimensionadas para a página carregar rápido. Também corrigi o caminho errado da imagem de fundo do topo.
- **Acessibilidade:** as fotos ganharam texto alternativo (`alt`) para leitores de tela, e o campo de e-mail passou a ser `type="email"`.
- **Conteúdo:** troquei o "lorem ipsum" e as frases em inglês por textos em português, corrigi erros de digitação e removi cards repetidos.
- **Navegação:** os links do menu, do rodapé e os botões levam até as seções da página, com rolagem suave.
- **Responsividade:** troquei alturas e larguras fixas por medidas flexíveis (Flexbox com `flex-wrap`, `max-width`, `clamp()`) e criei uma media query para celulares. A página foi testada em 375px, 768px e 1366px de largura.

## Tecnologias

- HTML5
- CSS3 (Flexbox e media queries)
- GitHub Pages para a publicação

Não há JavaScript nem bibliotecas para instalar.

## Como ver no seu computador

1. Clone o repositório:
   ```bash
   git clone https://github.com/pedrolira1/landing-page-logistica.git
   ```
2. Abra o arquivo `index.html` no navegador.

## Estrutura

```
index.html        → estrutura e conteúdo da página
style.css         → estilos e regras para celular
imagem/           → fotos
imagem/icones/    → ícones SVG
```

## Créditos

- **Layout original:** template da [W3layouts](https://w3layouts.com/). O crédito também está no rodapé da página.
- **Ícones:** [Lucide](https://lucide.dev), licença ISC.
- **Fotos** (todas pela [Licença Unsplash](https://unsplash.com/license)):
  - Banner: porto à noite, por [Bob Brewer](https://unsplash.com/photos/a-cargo-ship-is-docked-at-night-with-its-lights-on-fesixzjRHdY)
  - Navio de contêineres em Hamburgo, por [Pix Tresa](https://unsplash.com/photos/cargo-ship-being-loaded-with-containers-at-a-port-NjcRX8Vfzk8)
  - Caminhão na rodovia, por [Karl Callwood](https://unsplash.com/photos/a-truck-driving-down-the-road-d9EIdaMZCOw)
  - Empilhadeira no armazém, por [Bernd Dittrich](https://unsplash.com/photos/a-forklift-driving-through-a-warehouse-filled-with-pallets-F2C_mSrb6iM)
  - Caminhão verde na estrada, por [Fabio Sasso](https://unsplash.com/photos/green-semi-truck-on-highway-with-dry-landscape-and-wind-turbines-9lNE4qc6LLc)

> A RotaLog é uma empresa fictícia. Nomes, telefones, e-mails e números exibidos na página são apenas ilustrativos.
