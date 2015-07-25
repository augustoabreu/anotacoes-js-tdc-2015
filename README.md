# TDC 2015 - Trilha Javascript

Olá, abaixo estão minhas considerações/anotações da trilha de Javascript do TDC 2015.


## Utilizando CommonJS no Browser - Giovanni Bassi

O Giovanni veio com a proposta de apresentar quais são e como funcionam os métodos de modularizar o JavaScript no browser dando ênfase ao CommonJS. Ele começou a palestra falando um pouco sobre como o Javascript era utilizado no começo da web, ou seja, o código js era inserido diretamente na própria página HTML e praticamente nenhuma inserção de arquivos .js externos. 

Depois explicou a mudança que houve com o advento do XHR: ocorreu um aumento de arquivos .js nas páginas pois, diferentemente do passado, o Javascript começou a se tornar protagonista na cena do desenvolvimento web. Depois falou sobre o Require.js, AMD, Imports do ES6 e como utilizar o CommonJS no browser com o Browserify, o porquê de usá-lo ao invés de métodos como o AMD e Require.js. Mostrou as vantagens do CommonJS perante os outros, suas relações com o ES6 e HTTP2 e algumas mágicas para seu bom funcionamento. Eu particulamente gostei bastante da palestra, ele foi direto do começo ao fim e demonstrou saber de verdade o que estava falando. No final, sobrou pouco tempo para perguntas.


## Javascript para Adultos - Maurício Soares

Antes da palestra não tinha entendido o título, mas no decorrer da mesma fui entendendo e tive que concordar com o Maurício. Ele apresentou partes do Javascript que não são fáceis de entender logo de primeira mesmo! Começou apresentando uma agenda de tópicos e entre eles estavam escopo de funções, hoisting, closures, o funcionamento do this, IIFE, funções construtoras, prototype chain e passagem de objectos por referência. 

O Maurício é quem está por trás do Pin.js, um projeto que achei muito foda, então o cara manja! Tanto é que apresentou muito bem a maioria dos tópicos propostos, entretanto o único que achei que ele deixou a desejar foi o de prototype chain, não por não saber sobre o assunto (procure pelo seu github) mas sim por falta de tempo. Acho que é um tópico bem dificil de pegar de primeira e se a palestra tivesse um pouco mais de tempo sobrando ele teria explicado com muito mais detalhes. No final, sobrou pouco tempo para perguntas também.

[Slides](https://speakerdeck.com/mauriciosoares/javascript-para-adultos)


*-- Intervalo para o almoço: o TDC distribuíu lanches do subway e refri para todo mundo.*


## NativeScript: "write once, run anywhere mobile" com Javascript? - José Yoshiriro Ajisaka Ramos

A ideia do Yoshi era informar. Logo no início ele disse que não faria live coding e nem demonstrações de apps feitos com NativeScript mas que tentaria mostrar a todos as features dessa nova tecnologia para que, como ele mesmo disse, caso bombasse no mercado pudessemos estar à frente no quesito conhecimento. E foi o que ele fez, explicou como funciona o NativeScript e o seu sistema de "linkagem" com as APIs nativas dos sistemas mobile, falou sobre a diferença com aplicativos híbridos feitos com Phonegap, Cordova e afins, além de apresentar gráficos e dados sobre a tecnologia. 

A palestra em si foi um overview do NativeScript, tecnologia nova mas muito promissora! Para os próximos meses eles já têm muitas coisas legais para implementar, acho que vale a pena ficar atento. Esta palestra foi na trilha Stadium transmitida no TDC Online e acho que foi a que a galera mais fez perguntas.

[NativeScript](https://www.nativescript.org/)


*-- Nesse momento tive que sair da palestra por conta de um job que estava dando pau em produção (acontece né rs)*


## Testes Automatizados de todos os Tipos com Bibliotecas Javascript - Stefan Raphael de Araújo Teixeira

Acabei perdendo cerca de 20 minutos da talk do Stefan por conta do job que estava dando problema. Vi os primeiros slides posteriormente no Slideshare (link disponibilizado abaixo). O Stefan trouxe para a trilha diversos exemplos de testes feitos apenas com libs Javascript. Primeiro ele começou falando sobre padrões e anti-padrões de testes (ex: testes manuais), depois apresentou algumas libs de testes unitários, mocks, stubs e spies além de libs de assertion como o Chai e ShouldJS.

Cobertura de código e análise de complexidade de código também estavam na agenda da talk e como exemplo ele apresentou o Istanbul, o Blanket.JS, Plato e o Complexity-Report como soluções interessantes. A partir deste momento eu entrei na talk e acompanhei os tópicos de testes de API, com destaque para o Supertest, testes de UI, onde o Stefan apresentou várias libs e em cada uma deu um exemplo de como ele já utilizou algumas delas. Ainda tivemos uma introdução aos testes de visual regression e de performance com YSlow com PhatomJS! Infelizmente o tempo foi curto denovo, e a demonstração de exemplos que o Stefan havia preparado não pode ser apresentada 100%. Na verdade ele apresentou alguns testes que já havia feito mas foi muito rápido, no final apenas uma pergunta pôde ser feita.

[Slides](http://www.slideshare.net/stefanteixeira/tdc-2015-so-paulo-testes-automatizados-de-todos-os-tipos-usando-bibliotecas-javascript)


*-- Coffe-break: a organização do TDC distribuiu um 'kit' com suco, salgados e um bombom*


## Building Modern Webapp with React/Flux - Keuller Magalães

Essa era uma palestra que eu queria ver muito. Mas o Macbook do Keuller parou de funcionar e acabou que o Eduardo Matos se apresentou antes enquanto o Keuller tentava arrumar seu PC.


## ServiceWorkers e o futuro das aplicações no seu browser - Eduardo Júlio de Matos

Eu já tinha visto uma palestra do Eduardo na Conferência CSS Brasil 2015 e já tinha achado que ele mandava muito bem. Confirmou-se ainda mais nessa palestra, ele falou sobre cache com ServiceWorks e como ele pode resolver os problemas envolvidos com o ApplicationCache (manifest). 

Primeiro ele fez uma breve comparação/diferenciação entre Workers Javascript e ServiceWorkers, depois falou sobre o método de cache com ApplicationCache do HTML5 e os problemas que ele passou com essa API. Voltando ao ServiceWorker, o Eduardo apresentou diversos códigos mostrando o funcionamento e exemplos de como aplicações Javascript podem efetuar cache de arquivos corretamente com ele. Falou sobre a segurança por trás dos ServiceWorkers (só funcionam via https e possuem escopo por domínios). No final, ainda mostrou APIs que estão sendo desenvolvidas que irão ampliar o poder dos ServiceWorkers.

[Slides](https://github.com/eduardojmatos/service-worker-tdc-sp-2015)


## Ionic - Loiane Groner

O Keuller não conseguiu fazer seu Macbook funcionar mesmo após a palestra da Eduardo e como o Suissa ainda não havia chegado no TDC a Loiane Groner (coordenadora da trilha de Javascript) resolveu assumir o posto e apresentou uma talk sobre Ionic - o pessoal da sala escolheu a talk, que na verdade é um curso que a Loiane ministra. Ela começou falando sobre os problemas em desenvolver para diferentes plataformas mobile como, po exemplo, diferentes linguagens de programação, diferentes IDEs e incompatibilidade entre sistemas operacionais. 

Depois explicou as principais diferenças entre Cordova e Phonegap, como os dois surgiram e como funciona o desenvolvimento de aplicações mobile com tecnologias web. Após essa introdução, a Loiane falou sobre alguns frameworks e bibliotecas (jQueryUI, KendoUI, Sencha, etc) e começou a parte específica de Ionic. Ela falou sobre a comunidade de plugins, sobre como o Ionic faz uso do AngularJS, ngCordova e produtos que fazem ou farão parte de toda a Stack Ionic: Ionic Puash (push notifications), Ionic Deploy, Ionic Analytics, Ionic Package, Ionic Creator. Fora isso ainda falou sobre dicas do desenvolvimento mobile com tecnologia web. Ela conseguiu terminar a palestra um pouco antes, explicou que os slides eram de um curso de 4 horas e ainda abriu espaço para perguntas.

[Guia do Desenvolvedor Ionic Brazil](https://github.com/loiane/guia-do-desenvolvedor)


## JS Funcional com ES6 - Suissa

Já havia visto algumas talks do Suissa mas só pela internet e dessa vez ele iria falar sobre um tema relativamente recente e que pode agregar muito a qualquer projeto: Javascript Funcional. Ele disse que não irira dar a talk, mas foi convidado em cima da hora e acabou saindo de Curitiba pela manhã para chegar em SP a tarde para se apresentar. Acabou se atrasanso um pouco, talvez uns 10/15 minutos e quando começou a palestra se desculpou por isso e pelos slides que estaríam incompletos (segundo o Suissa, ele fez os slides no caminho curitiba-sp). 

Os slides estavam incompletos mesmo, alguns estavam fora da ordem e infelizmente com pouco código. Apesar disso, acredito que ele consiguiu explicar bem os tópicos de Programação Funcional: concorrência, calculo lambda, pure functions, high-order functions, first-class functions, currying, além de várias features novas do ES2015/ES6 como spread operators, variáveis com let, yields, etc. Ele ficou de disponibilizar os slides completos e convidou todos a participarem do Workshop de JS Funcional que está ministrando. Novamente tivemos pouco tempo para perguntas.

[Workshop JS Funcional](https://github.com/Webschool-io/workshop-js-funcional-free)


## Fim

Este foi meu primeiro TDC, desde o ano passado quando vi as trilhas e palestra estava com vontade de ir e pra ser sincero eu gostei bastante do evento. A organização estava ótima, o checkin foi tranquilo e sem filas e foi super fácil encontrar a sala da trilha de Javascript. 

Os pontos negativos que tenho para listar são apenas dois: o tempo das talks era cronometrado praticamente, na maioria delas sobrou pouco tempo para perguntas aos palestrantes; a localização poderia ser mais próxima do metrô para facilitar a locomoção da maioria das pessoas. 

No geral o evento estava bem legal, não fui em outras trilhas, apenas participei de uma talk da trilha Stadium que estava sendo feita com streaming on demand e que fazia parte da trilha de Javascript também (ainda assim assisti uma talk via TDC Online).
