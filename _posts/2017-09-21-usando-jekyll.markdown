---
layout: post
title:  "Usando Jekyll"
subtitle: ""
date:   2017-09-23 22:18:24
---



Olá pessoal tudo bem?
Depois de um tempo procurando ferramentas para criar meu blog acabei me deparando por acaso com o  [jekyll](https://jekyllrb.com/), que é bem simples de se usar.

Neste primeiro artigo irei demonstrar o fácil uso dessa ferramenta em conjunto com o Github Pages.

## Ferramentas necessárias:
* Ruby
* Conta no Git Hub

## Procedimentos

Primeiro iremos criar nosso repositorio onde ficará  nosso blog.
Acesse o Git Hub e crie um repositorio com essa nomeclatura: 
```
seunicknogithub.github.io
```

Para o próximo passo você terá que ter o ruby instalado em sua máquina, você pode obtelo por [aqui](https://www.ruby-lang.org/pt/documentation/installation/).

Após instala-lo certifique que o Ruby está rodando na sua máquina através do comando:
```
$ ruby -v
```


Beleza, agora vamos finalmente install o jekyll! Para instala-lo é simples bastar usar o seguinte comando:
```
$ gem install jekyll
```

Agora já podemos trabalhar em nosso blog, escolha um tema para usar em seu blog nesse [site](http://jekyllthemes.org/), e clone o fonte dele em sua máquina.

Agora mova o fonte para o seu repositôrio local:
```
$ mv meutema/*  seunicknogithub.github.io/
```

Bom agora vamos ver se está funcionando nosso tema, dentro do seu repositório vamos executar nosso blog para ver se está tudo ok.

```
$ jekyll serve 
```
Se estiver tudo ok, você poderar ver seu tema rodando localmente em sua máquina no endereço http://127.0.0.1:4000 .

Agora é a melhor parte, você poderá customizar seu blog como bem entender :D


Apos customizar seu blog, comite-o para seu github, e alguns minutos depois acesse o endereço: https://seunicknogithub.github.io.

Simples e rápido!
