# Beat

Estudo de interface estatica com tema de arte, musica e fotografia, desenvolvido com HTML e CSS. A pagina organiza cabecalho, categorias, galeria visual e rodape em um layout baseado em Flexbox.

## O Que Existe No Projeto

- Cabecalho com titulo, imagem e itens visuais de navegacao.
- Categorias de arte, design, estilo, musica, ebooks e videos.
- Secao Aquarela com galeria de imagens.
- Rodape com icones e itens de navegacao.
- Media queries para adaptar partes do layout a diferentes tamanhos de tela.

## Tecnologias

HTML5 e CSS3, com Flexbox e media queries. Nao ha JavaScript, framework, backend ou etapa de build.

## Como Executar

```bash
git clone https://github.com/GabrielYuri1127/beat.git
cd beat
```

Abra `index.html` no navegador. Para servir por HTTP com Python 3:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Abra `http://localhost:8080/`.

## Organizacao

```text
index.html        Estrutura da pagina e referencias das imagens
styles.css        Layout, cores e regras de adaptacao
assets/           Imagem local preservada no repositorio
```

## Estado Atual E Limites

Este repositorio e um estudo visual, sem sistema de comentarios, compartilhamento ou carregamento de conteudo. Os itens de menu e o texto Veja Mais nao executam essas acoes.

As imagens usadas no HTML apontam para URLs assinadas do Figma com expiracao em 2022. Por isso, a versao atual pode abrir com imagens indisponiveis. A imagem local em `assets/` nao esta conectada ao HTML. Restaurar as imagens originais e servi-las localmente e uma melhoria pendente; este README nao afirma que a galeria esteja plenamente operacional.

Outros pontos de evolucao sao revisar acessibilidade, tornar a navegacao funcional e conferir o layout em dispositivos atuais.
