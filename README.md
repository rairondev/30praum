# 30PRAUM – Site temático

## Tema

A gravadora independente **30PRAUM**, de Fortaleza (CE), e três de seus principais artistas: Matuê, WIU e Teto.

## Integrantes

- Rairon
- Rafael
- Ronald
- Anderson

## Descrição

Site informativo com 4 páginas HTML interligadas por um menu de navegação e um CSS externo compartilhado. Apresenta a história da gravadora e a biografia, a discografia e os prêmios de cada artista.

## Páginas

- index.html: apresentação da gravadora, sua história e cartões com links para as páginas dos artistas
- matue.html: biografia, carreira, discografia e premiações de Matuê
- wiu.html: biografia, discografia, singles e premiações de WIU
- teto.html: biografia, carreira, discografia, participações e premiações de Teto

Os estilos ficam em style.css e as imagens na pasta image/.

## Divisão de tarefas

- Rairon: index.html e style.css
- Ronald: matue.html
- Rafael: wiu.html
- Anderson: teto.html

## Uso do Flexbox

- **Menu de navegação** (nav): display: flex, justify-content: space-around, align-items: center, gap e flex-wrap: wrap. Os links <a> são os itens flexíveis.
- **Cartões de artistas** (ul.cards.artistas em index.html) e **discografia** (ul.discografia_* nas páginas dos artistas): display: flex, flex-wrap: wrap e gap. Cada li é um item flexível (flex: 1 1 ...) e quebra de linha em telas menores.
- **Dentro de cada cartão/álbum**: flex-direction: column e align-items: center para empilhar imagem, texto e botão.
- **Rodapé** (footer): display: flex, flex-wrap: wrap, `justify-content: space-around e gap.
- **Conteúdo** (main, section, body): display: flex com flex-direction: column e gap para espaçar os blocos.
- Em telas de até 700px (@media`), o menu se centraliza e o rodapé passa a ser uma coluna.

## Uso de IA

As decisões referentes ao tema, ao esquema visual e à programação foram tomadas pelos membros do grupo. A IA foi utilizada para auxiliar na correção de erros, e uma revisão foi realizada para verificar se ainda restava algum problema no código.
