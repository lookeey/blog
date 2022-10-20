---

author: "lookee"
title: "o melhor framework que você vai usar para o seu próximo projeto de desenvolvimento web"
date: "2022-10-20"
description: "às vezes o mais legal não é o melhor"
tags: ["tecnologia", "desenvolvimento"]
categorias: ["Pensamentos"]
url: posts/o-melhor-framework
aliases: ["web"]
ShowToc: true
TocOpen: true
weight: 2

---

Recentemente, eu decidi começar um blog. Um lugar para exibir as coisas que faço, elaborar pensamentos e organizar minhas ideias em algum lugar mais coerente do que minha mente.

Até agora, este é o meu segundo post, mas tenho certeza que poderia ter escrito mais agora. Este é um problema que se tornou óbvio e quase preocupante às vezes para mim: frequentemente perco mais tempo configurando e arrumando as coisas do que fazendo elas de fato. Estou realmente orgulhoso de escrever este segundo post, mostra o quão longe cheguei neste projeto. Mesmo se eu levasse algum tempo para configurar isso, eu poderia ter demorado muito mais. Isso se deve a uma mudança recente em minha mentalidade que acredito que vai me ajudar muito agora e no futuro.

## Tecnologias Web

Vou usar o desenvolvimento web como exemplo aqui, pois é a área em que tenho mais *insights*, mas não afirmo que esses problemas são os mesmos em todas as outras partes da indústria de desenvolvimento de software.

A tecnologia da Web é um departamento *muito* ativo. A web está em todos os lugares que você olha e, além dos back-ends, ela é baseada em nosso antigo conjunto de linguagens em constante evolução: HTML, CSS e JavaScript. Alguns podem dizer que outras formas de desenvolvimento de aplicativos cresceram e conquistaram espaço na indústria, como aquelas usadas para construir aplicativos para dispositivos móveis. Mas a verdade é que os desenvolvedores parecem gostar muito de HTML, CSS e JS. Dê uma olhada nos principais *frameworks* usados para desenvolvimento móvel abaixo. (a propósito, são vários, não é verdade?)

![Estatísticas](stats.png)

Se você pretende distribuir seu aplicativo para pelo menos duas plataformas diferentes, como Android e iOS (o que é muito provável), você se beneficiará muito ao usar uma dessas plataformas. Entre eles, temos: *React* Native, Cordova, Ionic, NativeScript e PhoneGap. Juntos, elas compunham a maior parcela desse mercado no ano passado. Mesmo que haja um aumento de aplicativos que usam o novo framework de UI Flutter, a nossa velha *stack* da Web ainda domina o mercado.

Além disso, como você deve saber, o JavaScript também está do mundo dos aplicativos de desktop. O Electron é uma estrutura que usa o mecanismo V8 do Chrome para essencialmente rodar uma janela do navegador da Web com acesso a APIs Node.JS. Uma abordagem polêmica, com certeza, mas é uma ideia que teve grande sucesso.
  
Sim, este é o maior ecossistema de desenvolvimento de cliente para usuários que existe e, como você pode esperar, ele oferece uma ampla variedade de opções de frameworks, bibliotecas e plataformas para desenvolvimento. Parece ótimo, certo?

## Dependency hell, mas de outro jeito

É muito fácil se perder no mar de frameworks disponíveis. Novos produtos chegam para resolver problemas e tornar os produtos anteriores obsoletos, de modo que cada novo framework é rotulado como o futuro do desenvolvimento, comercializado com a promessa de que resolverá seus problemas como desenvolvedor e, ao mesmo tempo, proporcionará uma melhor experiência para o usuário final.

Quando um desenvolvedor com força de vontade suficiente decide que uma solução existente não é boa o suficiente, eles tentam *criar* outra solução. Assim, este conhecido quadrinho do [xkcd](https://xkcd.com/) entra em ação.

![Quadrinho sobre padrões](https://imgs.xkcd.com/comics/standards.png)

É bom que existam pessoas fortes e ousadas dispostas a mudar a forma como o software é feito e melhorá-lo, e na verdade, é isso que impulsiona tudo no desenvolvimento de código aberto. Mas em uma situação como esta, você tem que ter cuidado.

## Tirando as coisas do papel

Eu queria criar um blog. A primeira coisa que me veio à mente foi algum tipo de solução SSG (Geração de Site Estático). Então comecei a procurar os melhores frameworks por aí. Eu não precisaria de nenhum tipo de editor WYSIWYG sofisticado ou gerenciamento de banco de dados, pois eu mesmo estaria no controle de tudo, desde o código até o conteúdo. Então você tem Next.JS, Nuxt, VuePress, Jekyll, Gatsby, VitePress à sua disposição, e a lista continua. Quero dizer, [*realmente continua*](https://jamstack.org/generators/). Meus requisitos eram que houvesse bom suporte a TypeScript, suporte a pré-processadores de CSS e que oferecesse uma boa estrutura para o projeto. Eu também queria aprender mais sobre o Vue, já que é uma opção em tendência no momento. Então escolhi o Nuxt: com geração de conteúdo prática e controle total do layout usando Vue.

Quando comecei a configurar meu projeto, a primeira decisão que tive que tomar foi entre usar o Nuxt versão 2 ou 3. A versão 2 era a estável, construída usando JS. Assim que montei um projeto TypeScript usando a ferramenta CLI fornecida e comecei a fazer um layout, encontrei alguns problemas. Mais tarde, insatisfeito com tudo, pensei em usar o Nuxt 3 (release candidate, não estável). Vasculhando a documentação incompleta e resolvendo problemas de configuração do projeto, finalmente pude começar a criar meu blog.

Nesse ponto, eu estava esgotado e comecei a me perguntar se teria conteúdo para escrever para isso. Então deixei tudo de lado por alguns dias.

Alguns dias depois, algumas ideias vagas sobre arte passaram pela minha cabeça e tive vontade de escrever sobre isso. "Ah! Um tema tão bom para um post no blog!" Eu pensei. Mas não havia blog.

Desta vez eu sabia que tinha que fazer isso rápido. Então agora eu estava procurando a coisa mais fácil possível que pudesse ser configurada no menor tempo possível. Rapidamente, lembrei-me do software Jekyll, que eu tinha visto enquanto explorando recursos do GitHub há algum tempo. Pesquisando sobre Jekyll, logo encontrei o Hugo, que supostamente era simplesmente um Jekyll só que mais rápido. Já que eu não teria que me preocupar com os detalhes de implementação no início, era isso. Em poucos minutos eu tinha um projeto do Hugo montado com um tema pronto bem legal. Só tive que preencher minhas informações e começar a escrever imediatamente. Agora eu não tinha uma estrutura de layout de componentes, TypeScript ou pacotes de Node.JS. Mas eu tinha o que era mais importante: um blog. Ainda estou no processo de customizar deste site, deixando-o mais bonito e adicionando um visual pessoal, mas tenho certeza que não será difícil.

## Atenha-se aos seus objetivos

O desenvolvimento Web tem uma comunidade muito grande e, portanto, muitas opções são dadas a você como desenvolvedor para escolher quando precisar fazer um trabalho. Mas lembre-se sempre de definir uma meta e cumpri-la, caso contrário, sua produtividade vai desabar. Se você quer aprender sobre um novo framework, é melhor fazer algo *para aprender sobre um novo framework*, e reservar seu tempo especificamente para isso.

# Resolvendo o problema e terminando o serviço

Dependendo do que você está tentando fazer, você deve considerar uma série de fatores para escolher a melhor ferramenta para suas necessidades. E o primeiro é:

- Quanto tempo você realmente tem (ou deveria usar) para encontrar a melhor solução?

Não se esqueça dos seus objetivos. Às vezes você só precisa de uma ferramenta simples para um trabalho simples, como foi o meu caso ao criar este blog. Caso contrário, se você for trabalhar em um grande projeto ou trabalhar com outros desenvolvedores, fazer uma escolha bem pensada será útil a longo prazo.

### Usando o novo framework revolucionário

Existem muitos frameworks novos baseados em grandes ideias, como Solid.JS ou Svelte, dois projetos que trazem melhorias incríveis no desempenho. Pessoalmente, estou muito animado para ver o crescimento e a adoção deles no mercado. Mas realmente usá-los é outra coisa. Eles estão na sua infância e não são muito sólidos, então é provável que você enfrente problemas. Lembre-se sempre de que os softwares que alguns consideram legados costumam ser os mais sólidos.

Para meu próximo projeto para um cliente (que envolve um site para uma empresa com um blog), vou usar o Next.JS, que é baseado em React. Eu sei que não é o mais rápido nem o mais elegante, mas com certeza, para mim como desenvolvedor solo, essa será uma boa escolha.