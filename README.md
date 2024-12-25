# TubeCast
Um youtube player de audio via terminal (Utilizavel | Porém em construção/melhorias)

| Reproduzindo |
| -------------:|
| ![300x256](https://raw.githubusercontent.com/andryeltj/tubecast/refs/heads/main/galery.png) |

## Como usar:
 - Por um terminal use o comando `tubecast (SUA URL DO YOUTUBE)`

 ** Em caso do link ser uma playlist, apague tudo o que estiver fora do campo "`list=`", ficando como no exemplo:
 
 `https://youtube.com/watch?list=PLavcTjFDs2u5f6IDqbuIMUb_W5uBzyzuZ`
 
 - O seu histórico está em ~/.config/tubecast.hist

## Instalando:
 ** Debian | Arch e seus derivados
 - instale as dependencias:
 `sudo apt install yt-dlp ffmpeg webp-pixbuf-loader libsixel1 imagemagick`
 - baixe o arquivo do link abaixo, extraia o binário em /usr/bin no arquivo, para `/usr/bin` do seu sistema
 `https://archlinux.org/packages/extra/x86_64/viu/download/`
 - baixe o `tubecast`, mova para sua `/usr/bin`, concedendo as permissões de execução.

   
 ** Alpine OS
 - instale as dependencias:
 `sudo apk add bash viu ffmpeg yt-dlp imagemagick`
 - baixe o `tubecast`, mova para sua `/usr/bin`, concedendo as permissões de execução.
