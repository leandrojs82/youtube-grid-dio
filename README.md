# YouTube — Desafio Grid da DIO

Reprodução da página inicial do YouTube do Figma usando somente HTML5 e CSS3. O layout principal, o cabeçalho, a navegação e a listagem usam CSS Grid. Sem JavaScript, frameworks ou instalação.

## Abrir o projeto

Extraia o ZIP e abra `index.html` no navegador. Mantenha `styles.css` e a pasta `assets` ao lado do HTML. Imagens, ícones e fontes são locais, permitindo visualizar o layout sem internet.

## Estrutura

- `index.html`: cabeçalho, menu lateral e 12 vídeos na ordem do Figma.
- `styles.css`: estilos comentados, áreas de Grid, colunas e ajustes para tablet e celular.
- `assets/`: cinco miniaturas de 250 × 141 px, marca, avatares, ícones e fonte Roboto com licença.

## Responsividade

O modelo desktop tem quatro colunas e menu lateral de 218 px. Em telas menores, a grade passa a três, duas e uma coluna. A partir de 950 px, o menu mostra apenas ícones; em celulares de até 560 px, ele é ocultado e a busca passa para a segunda linha do cabeçalho. A versão mobile é uma adaptação da referência desktop.

## Escopo

Reprodução visual estática: os botões de menu e notificações são demonstrativos. A pesquisa abre resultados reais do YouTube. Os cards abrem uma pesquisa pelo título e os links laterais levam às seções correspondentes do YouTube; esses acessos exigem internet e podem exigir login.

## Referência e créditos

Design original: https://www.figma.com/design/KknwioExyqKD3D2eSVFrcW/Desafio-Grid---DIO?node-id=0-1

Marcas e imagens: YouTube, DIO e respectivos titulares. Miniaturas do desafio disponibilizadas em https://github.com/MarcosWinther/project-css-grid-listagem-videos-youtube/tree/main/assets/img/thumbnails

Marca, ícones do cabeçalho e avatares: recursos da referência anterior, disponíveis em https://github.com/ikro277/projeto-dio-css-2/tree/main/assets/img e https://github.com/deboradevsouza/Clone_Youtube/tree/main/assets

Ícones laterais: SVGs locais desenhados para esta reprodução.
Fonte Roboto: https://fonts.google.com/specimen/Roboto (licença em `assets/fonts/OFL.txt`).

Projeto de estudo, sem vínculo oficial com o YouTube.
