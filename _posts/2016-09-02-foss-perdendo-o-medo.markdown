---
layout: post
title:  "Open Source: Perdendo o Medo de Contribuir"
link: foss-losing-the-fear
date: 2016-09-02 16:00:00 -0300
categories: mobile
comments: true
lang: pt
---

Oi, gente! Neste post vou falar um pouco dos meus primeiros passos com a colaboração em projetos Open Source!
Eu já havia lido que colaborar nos ajuda a ganhar experiência e podemos aprender com os outros. Porém, eu sempre tive um pouco de medo por eu não ter muita experiência ou por minha contribuição não ser boa o suficiente. Recentemente, resolvi me arriscar e fiz algumas contribuições bem simples que me ensinaram bastante! Vou falar sobre elas neste post.

### Meu primeiro Pull Request ( no site da PythonRio !)

O primeiro lugar para se buscar projetos para colaborar é o Github! Nele, podemos encontrar vários projetos acontecendo e precisando de colaboradores. Eu já usava o Github há algum tempo para colocar meus projetos escolares, mas ainda não o havia usado como plataforma de colaboração.

Bem, aqui no Rio temos o grupo [PythonRio](http://pythonrio.python.org.br/) que se reune todos os meses. O grupo possui um site em feito em [Lektor](https://www.getlektor.com/) e precisava de ajuda para melhorá-lo. A primeira coisa que eu fiz foi ler a lista de issues que estavam no projeto e dentre estas estava que precisávamos criar uma seção de blog do site.

Eu forkei o projeto e comecei a trabalhar nisso. Eu havia assistido uma palestra do [Luciano](https://lucianoratamero.github.io/) em um dos encontros do PythonRio e o Lektor é bem simples de se trabalhar.

Feito o meu trabalho na minha máquina local, eu enviei os meus [Pull Requests](https://github.com/pythonrio/pythonrio.github.io/pulls?q=is%3Apr+is%3Aclosed+author%3Atfalbo)! O Luciano me ajudou bastante na época e eu pude ver o quando é simples!

Depois de enviado o Pull Request, pode-se ver o quanto que os meus commits são compatíveis com o código que já está no projeto. Isso facilita para que o dono do projeto possa analisar e aprovar o Pull Request!


### Ajudando na tradução do tutorial do Django Girls!

Isso eu não sabia antes, mas pode-se colaborar com Open Source sem nem mesmo saber programar! É isso mesmo! Há vários projetos que precisam de documentação ou tradução! 

No começo do ano, as meninas do Pyladies aqui do Rio organizaram um [Django Girls (tem um post no blog sobre o evento)](http://blog.thaissa.eng.br/django/2016/03/14/meu-primeiro-django-girls/). Entre uma das coisa que precisávamos trabalhar era na tradução do tutorial! O tutorial original em inglês costuma ter muitas mudanças e é sempre bom que a tradução acompanhe. 

Eu perguntei para as meninas o que poderia fazer pra ajudar e elas passaram o [link do Crowdin do tutorial](https://crowdin.com/project/django-girls-tutorial/pt-BR#). Ali, qualquer pessoa pode postar a sua sugestão de tradução para que ela possa ser votada.

Depois de um tempo escrevendo as sugestões, eu resolvi ir mais além: mandei um e-mail para as organizadoras do projeto pedindo que eu pudesse revisar as traduções!
A partir daí, pude começar a revisar as traduções do tutorial do Django Girls para o português! 


### Enviando patches pro Kernel! xD

Até o ano passado eu fazia estágio em Sistemas Operacionais. Também, depois que puxei a disciplina de SO na faculdade, passei a me interessar mais pelo assunto. Logo depois, eu fiquei sabendo do [Outreachy](https://www.gnome.org/outreachy/) e que dentro de seus projetos está o [Kernel do Linux](https://kernelnewbies.org/OutreachyIntro)!

O Outreachy abre inscrições duas vezes ao ano e a inscrição inclui fazer colaborações ao projeto de seu interesse! Eu tava super animada e comecei a trabalhar nisso. Segui o tutorial da [wiki do projeto](https://kernelnewbies.org/OutreachyIntro) e comecei a enviar os meus patches. 

Eram patches bem bobinhos e mais relacionados ao padrão de código do projeto, mas serviram como um aprendizado para mim! Aprendi a compilar o kernel, a usar o mutt e a enviar commits por e-mail. Para minha surpresa, tive alguns [patches aceitos](http://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=thaissa) e [meu nome está entre os colaboradores da release 4.6](https://github.com/gregkh/kernel-history/blob/master/email/addresses-4.6)!



#### Conclusão

Posso dizer que é bem simples colaborar com Open Source! Sempre acontecem dúvdas e em alguns momentos eu me senti perdida. Nesses momentos, a melhor opção é PEDIR AJUDA! Acredito que a comunidade está acima de tudo no Open Source, então não há problema em pedir ajuda. Sempre haverá alguém disposto a ajudar! :)


