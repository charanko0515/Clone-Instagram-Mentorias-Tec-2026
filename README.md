# Projeto Clone do Instagram com Tailwind CSS

Projeto prático das Mentorias TEC 2026 (Avaliação 2): um feed de fotos responsivo feito com HTML, Tailwind CSS e ícones do Boxicons, pensado primeiro para o celular (*mobile first*).

Projeto de estudo inspirado no Instagram, sem ligação com a empresa. Por isso a página se chama "Fotogram".

## O que tem aqui

| Pasta | Conteúdo |
|---|---|
| [`modelo-1/`](modelo-1/) | Modelo base claro, seguindo os slides da aula |
| [`modelo-2/`](modelo-2/) | O mesmo layout com tema escuro, outras cores e cantos diferentes |
| [`feed-jojo/`](feed-jojo/) | Exemplo de personalização: um feed de fãs de JoJo's Bizarre Adventure |

## Como usar

1. Baixe o repositório pelo botão **Code > Download ZIP** e extraia os arquivos.
2. Escolha um modelo e abra o `index.html` no navegador. É preciso estar com internet, porque o Tailwind e os ícones vêm de CDN.
3. Mude as cores no bloco `<style>` do topo do arquivo: as classes `bg-card`, `bg-muted`, `text-muted` e as outras mudam o site inteiro.
4. Para criar outra postagem, copie um `<article>` inteiro. Para outro story, copie a `div` de um story.
5. Teste em tela estreita e larga: o menu inferior aparece só no celular, e a barra lateral só em telas grandes.

## O que muda em cada tamanho de tela

| Tela | O que aparece |
|---|---|
| Celular | Menu inferior fixo e botão de menu no topo |
| A partir de 768px (`md`) | Busca e ícones no topo; o menu inferior some |
| A partir de 1024px (`lg`) | Barra lateral com perfil e sugestões |

## Sobre o feed de JoJo

JoJo's Bizarre Adventure é uma obra de Hirohiko Araki. Os perfis são fictícios, e as imagens são ilustrações próprias, sem nenhuma arte oficial.
