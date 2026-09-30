# Card de Prévia de Estatísticas

Projeto desenvolvido como atividade de HTML e CSS, baseado no desafio **Stats Preview Card Component**.

O objetivo foi reproduzir o layout proposto utilizando HTML e CSS, criando uma página responsiva que se adapta tanto para computadores quanto para dispositivos móveis.

## Resultado

O projeto pode ser acessado pelo GitHub Pages:

https://zevitu-dev.github.io/TrabalhoCards/

## Tecnologias utilizadas

- HTML5
- CSS3
- Flexbox
- Media Queries
- Google Fonts
- Git e GitHub
- GitHub Pages

## Estrutura do projeto

O HTML foi organizado utilizando um elemento principal para representar o card.

O card foi dividido em duas partes principais:

- Área de conteúdo;
- Área da imagem.

Na área de conteúdo foram adicionados:

- Título principal;
- Texto de descrição;
- Três estatísticas;
- Valores e rótulos de cada estatística.

A área da imagem possui a fotografia fornecida pelo desafio e um efeito de cor roxa aplicado através do CSS.

## Estilização

Para organizar os elementos foi utilizado principalmente **Flexbox**.

No desktop, o card é dividido horizontalmente:

- Conteúdo no lado esquerdo;
- Imagem no lado direito.

Cada área ocupa aproximadamente 50% da largura do card.

Também foram utilizadas as fontes **Inter** e **Lexend Deca**, disponibilizadas pelo Google Fonts.

As cores utilizadas seguem o guia de estilos fornecido no desafio.

A palavra `insights` recebeu uma classe própria para aplicar a cor roxa de destaque.

## Estatísticas

As estatísticas foram organizadas utilizando Flexbox.

No desktop elas aparecem lado a lado:

10K+ | 314 | 12M+

Enquanto os rótulos aparecem abaixo de cada valor:

- Companies
- Templates
- Queries

Os valores possuem maior tamanho e peso de fonte, enquanto os rótulos utilizam uma fonte menor e uma cor mais suave.

## Imagem

A imagem foi colocada dentro de um container próprio.

Para produzir o efeito roxo presente no design original foram utilizadas as propriedades:

- `background-color`
- `mix-blend-mode`
- `opacity`

Também foi utilizado:

`object-fit: cover`

para manter a proporção da imagem sem deformá-la.

## Responsividade

Para adaptar o projeto para dispositivos móveis foi utilizada uma Media Query:

```css
@media (max-width: 768px)