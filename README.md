# Galeria do Espaço

Projeto simples desenvolvido em HTML e CSS para a atividade de Introdução ao Front-End.

O site possui duas páginas: uma página inicial com imagens e uma página com vídeos locais. Os arquivos foram organizados em pastas usando comandos do CMD, como `mkdir`, `ren`, `move`, `dir`, `cd`, `tree /f` e `doskey /history`.

## Páginas do projeto

* `index.html`: página inicial com a galeria de imagens.
* `videos.html`: página com dois vídeos locais.
* `estilo.css`: arquivo de estilo da página inicial.
* `videos.css`: arquivo de estilo da página de vídeos.

## Estrutura de pastas

```txt
projeto
│   index.html
│   videos.html
│   estilo.css
│   videos.css
│   historico.txt
│
├───imagens
│       imagem1.jpg
│       imagem2.jpg
│       imagem3.jpg
│       imagem4.jpg
│       imagem5.jpg
│       imagem6.jpg
│
└───videos
        video1.mp4
        video2.mp4
```

## Tecnologias utilizadas

* HTML5
* CSS3
* CMD do Windows

## Comandos utilizados no CMD

Durante a organização do projeto, foram utilizados comandos básicos do Prompt de Comando:

```cmd
cd /d "%USERPROFILE%\Downloads\Projeto"

dir

mkdir imgs
mkdir vids

ren imgs imagens
ren vids videos

move imagem1.jpg imagens\imagem1.jpg
move imagem2.jpg imagens\imagem2.jpg
move imagem3.jpg imagens\imagem3.jpg
move imagem4.jpg imagens\imagem4.jpg
move imagem5.jpg imagens\imagem5.jpg
move imagem6.jpg imagens\imagem6.jpg

move video1.mp4 videos\video1.mp4
move video2.mp4 videos\video2.mp4

dir

tree /f

doskey /history > historico.txt
```

## Como abrir o projeto

Para visualizar o site, basta abrir o arquivo `index.html` no navegador.

Também é possível navegar para a página de vídeos clicando no link **Vídeos** no menu superior.

## Observação

Os vídeos foram compactados para deixar o projeto mais leve e facilitar o envio para o GitHub, mantendo os mesmos nomes dos arquivos para não alterar o funcionamento do HTML.
