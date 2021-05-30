---
title: 'Pre-game: Antes mesmo de começar'
date: '2021-05-31'
tags: ['c', 'bash']
draft: false
summary: O que eu já aprendi antes mesmo de começar o basecamp
---

Já deu pra aprender algumas coisas antes mesmo de começar o Basecamp. Uma dela é o valor desse grupo formado, tem gente que sabe muito e ja estão compartilhando várias coisas - Vou compartilhar um pouco o que eu já aprendi.

## Links importantes

- [Guia de sobrevivência](https://www.notion.so/Guia-de-Sobreviv-ncia-42Basecamp-Maio-2021-c120a403dd4e4609a26440d79238e771) - O grande manual
- [VSCode interno](https://basecamp.42sp.org.br/) - O seu terminal online 😎
- [Intra da 42](https://profile.intra.42.fr/) - O sistema aonde tundo acontece
- [A Norma](https://www.notion.so/A-Norma-60a738d092ef4feb8224a54913ffccd2) - Boas práticas que devem ser seguida
- [Discord ](https://discord.com/) - O canal de comunicações 💬

## Um pouco de programação

Teve gente explicando sobre git, linux, aula de C, até sala pra assistir seriado.

## Shell

Abrindo o VSCode interno, dá pra criar um arquivo com final `.sh` , chamar no terminal `bash + nome_do_arquivo` e rodar o arquivo

![](/static/images/Kapture%202021-05-30%20at%2019.17.30.gif)

_Note: Touch é o comando para criar um arquivo_

## Linguagem C

Da mesma maneira, podemos criar um arquivo com final `.c`, mas para rodas precisa compilar, chamando `gcc + nome_do_arquivo` e depois rodar o arquivo output compilado

![](/static/images/Kapture%202021-05-30%20at%2019.26.02.gif)

- _a flag -o no comando gcc é para declarar o nome do arquivo do output_
- _o `#include <stdio.h>` no começo do arquivo sere para poder usar o
  printf, nem imprimir pra tela vem por padrão no C 😅_

## A Norma

Esse mesmo arquivo em C, inocente, tem vários problemas:

```c
#include <stdio.h>

int main(void){
    printf("hello, 42!\n");
}
```

Basta rodar no console o programa _norminette_ que ele diz o que fizemos de errado:
![](/static/images/7F03C462-F3A6-42DD-9488-C9B377BA1385.png)
Ele espera um TAB e não espaço depois das declarações, chaves sempre em nova linha… São mais regras de formatação que eles consideram boas práticas, e quando arrumamos a _norminette_ diz que está tudo OK!
![](/static/images/F7013820-3D10-41EF-BEAD-F5612C565A08.png)

Vale lembrar: O que vale é a **A NORMA**, não o programa auxiliar _norminette_. Na dúvida é melhor consultar [o arquivo oficial](https://www.notion.so/A-Norma-60a738d092ef4feb8224a54913ffccd2), o programa é mais recente e parece que não contém ainda todas as coisas.

Agora podem parar de ler esse texto, vão dormir, e bom basecamp!

Bjs
