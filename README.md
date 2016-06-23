# Estudos 2016

Este repositório tem por objetivo, agregar tópicos relacionados a tecnologia e conhecimentos básicos que devem ser adquiridos.

---

## Sumário
* [01 - HTML e CSS](#html-e-css)
* [02 - Javascript](#javascript)
* [03 - PHP](#php)
* [04 - Boas Práticas](#boas-práticas)
* [05 - Workflow](#workflow)

---

### HTML e CSS
#### Plano de Estudos
* *1.* HTML 5
	* [O que é tableless¹](http://tableless.com.br/o-que-etableless/)
	* [O que é tableless²](https://pt.wikipedia.org/wiki/Tableless)
	* [O que é tableless³](https://www.oficinadanet.com.br/post/306-o_que_e_tableless_e_como_funciona_essa_metodologia39)
	* [Dive into HTML5 - Bem explicado as diferenças e coisas novas](https://diveintohtml5.com.br/)
	* [HTML e HTML5 - Qual a diferença ? O que muda?](http://www.htmlprogressivo.net/2014/02/HTML-HTML5-Qual-a-Diferenca-O-que-muda.html)
	* [Principais mudanças na estruturação de uma página HTML5](http://www.linhadecodigo.com.br/artigo/3518/principais-mudancas-na-estruturacao-de-uma-pagina-com-html-5.aspx)
	* [A Look into Proper HTML 5 Semantics](http://www.hongkiat.com/blog/html-5-semantics/)
	* [Whats makes for a Semantic Class Name?](https://css-tricks.com/semantic-class-names/)
* *2.* CSS 3
	* [Introdução a CSS3](http://www.criarweb.com/artigos/introducao-a-css3.html)
	* [11 regras CSS que todo desenvolvedor web deve saber](http://wpmidia.com.br/desenvolvimento-web/11-regras-css-todo-desenvolvedor-web-deve-saber/)
	* [CSS Transition e CSS Animation](http://tableless.com.br/transition-e-animation/)
	* [CSS3 Animation Keyframe](http://tableless.com.br/css3-animation-keyframe/)
	* [OOCSS, ACSS, BEM, SMACSS: what are they? What should I use?](http://clubmate.fi/oocss-acss-bem-smacss-what-are-they-what-should-i-use/)
* *3.* Extra
	* [Leveling up in CSS](https://medium.freecodecamp.com/leveling-up-css-44b5045a2667#.vjrbwbvp2) -> _Este artigo poderia estar em ambos os casos, html5 e css3, mas decidi optar por colocar como extra para evitar repetir conteúdo e além do fato que para bom entendimento dele, ter um conhecimento prévio dos textos acima será de muita ajuda._
	* [Do zero a herói front-end (parte 1)](http://imasters.com.br/front-end/do-zero-heroi-front-end-parte-01/?utm_source=iMasters&utm_campaign=b9f7ba5506-ds_2015_08_18&utm_medium=email&utm_term=0_c1528e6ab3-b9f7ba5506-360665793)
	* [From Zero to Front-End Hero (part 1 - original version)](https://medium.freecodecamp.com/from-zero-to-front-end-hero-part-1-7d4f7f0bff02)
	* [From Zero to Front-End Hero (part 2)](https://medium.freecodecamp.com/from-zero-to-front-end-hero-part-2-adfa4824da9b#.ksbfdjpru)

---

### Javascript
#### Plano de estudos

* *1.* Fluência na linguagem JavaScript:
	* escopo
	* funções anônimas e closures
	* funções autoexecutáveis
	* promises
	* eventos (pubsub/observer)
	* ajax
	* orientação a objetos por protótipos (função construtora, método estático, método privado e herança)
	* simulação de namespaces
* *2.* Bibliotecas mais utilizadas:
	* jQuery (entender os módulos de manipulação do DOM, eventos, ajax e promises separadamente)
	* Lodash
* *3.* Modularização e *bundling*:
	* modularização manual
	* modularização assíncrona (AMD)
	* modularização do Node.js (CommonJS)
	* Require.js para AMD
	* Browserify ou Webpack para CommonJS
* *4.* *Two-way data-binding*, usado pelo Angular e *unidirectional dataflow*, usado pelo React
* *5.* Conhecimento básico das bibliotecas mais utilizadas:
	* Backbone
	* Angular
	* Ember
	* Vue.js
	* React
* *6.* Testes:
	* Jasmine
	* Mocha, Chai e Sinon
* *7.* ES6 e programação funcional

#### Referências

#### Parte 01

* [Entendendo Javascript escopo e a palavra chave this](http://www.abequar.net/posts/entendendo-javascript-escopo-e-a-palavra-chave-this)
* [JavaScript: entendendo o this](http://tableless.com.br/javascript-entendendo-o-this/#.Ut2RwnlpRm0)
* [The "this" Keyword](http://code.tutsplus.com/tutorials/the-this-keyword--net-36027)
* [Hoisting e escopo em JavaScript](http://loopinfinito.com.br/2014/10/29/hoisting-e-escopo-em-javascript/)
* [Javascript Hoisting](http://www.abequar.net/posts/javascript-hoisting)
* [The Definitive Guide to Object-Oriented JavaScript](https://www.youtube.com/watch?v=PMfcsYzj-9M&list=PLiY_jvnZ_8vWa-c6klgQ3d34aPGXyhspQ)
* [Fazendo Javascript OO de forma fácil](http://www.klauslaube.com.br/2011/05/16/fazendo-javascript-oo-de-forma-facil.html)
* [Javascript: A diferença entre Constructor Function e Object Literal](http://www.klauslaube.com.br/2011/10/23/javascript-constructor-function-object-literal.html)
* [Objetos, Funções e Classes em Javascript](http://www.abequar.net/posts/objetos,--fun%C3%A7%C3%B5es-e-classes-em-javascript)
* [The Basics of Object-Oriented JavaScript](http://code.tutsplus.com/tutorials/the-basics-of-object-oriented-javascript--net-7670)
* [Criando bons construtores em Javascript](http://jcemer.com/construtores-em-javascript.html)
* [Prototypes in JavaScript](http://code.tutsplus.com/tutorials/prototypes-in-javascript-what-you-need-to-know--net-24949)
* [Herança em JavaScript parte I](http://loopinfinito.com.br/2012/05/04/heranca-em-javascript-parte-1/)
* [Herança em JavaScript parte II](http://loopinfinito.com.br/2013/02/05/heranca-em-javascript-parte-2/)
* [Os segredos da IIFE](http://blog.da2k.com.br/2015/02/20/os-segredos-da-iife/)
* [Entendendo captura e propagação de eventos](http://loopinfinito.com.br/2013/05/14/entendendo-captura-e-propagacao-de-eventos/)
* [Fluxo de execução assíncrono em JavaScript – Callbacks](http://tableless.com.br/fluxo-de-execucao-assincrono-em-javascript-callbacks/)
* [Fluxo de execução assíncrono em JavaScript – Promises](http://tableless.com.br/fluxo-de-execucao-assincrono-em-javascript-promises/)
* [Javascript - entendendo e criando suas próprias Promises](http://blog.da2k.com.br/2015/03/05/javascript-entendendo-e-criando-suas-proprias-promises/)
* [Javascript - Criando um módulo Ajax com Promises - Parte 2](http://blog.da2k.com.br/2015/03/08/javascript-criando-um-modulo-ajax-com-promises-parte-2/)
* [Javascript - Criando um módulo Ajax com Promises - Parte 3](http://blog.da2k.com.br/2015/03/08/javascript-criando-um-modulo-ajax-com-promises-parte-3/)
* [Javascript - Criando um módulo Ajax com Promises - Parte 4](http://blog.da2k.com.br/2015/03/08/javascript-criando-um-modulo-ajax-com-promises-parte-4/)
* [Javascript - Criando um módulo Ajax com Promises - Parte 5](http://blog.da2k.com.br/2015/03/08/javascript-criando-um-modulo-ajax-com-promises-parte-5/)
* [O que são promessas no JavaScript?](http://blog.taller.net.br/o-que-sao-promessas-javascript/)
* [Javascript Namespaces and Modules](https://www.kenneth-truyers.net/2013/04/27/javascript-namespaces-and-modules/)

---

### PHP
#### Plano de estudos
* *1.* [PHP do jeito certo](http://br.phptherightway.com/)
* *2.* Orientação a Objetos
	* [Introdução a PHP Orientada a objetos](http://www.kadunew.com/blog/php/introducao-php-orientado-a-objetos-objetos-e-classes)
	* [PHP Orientado a Objetos¹](http://www.adianti.com.br/phpoo_mostra.pdf)
	* [PHP Orientado a Objetos²](http://code.tutsplus.com/pt/tutorials/object-oriented-php-for-beginners--net-12762)
	* [5 coisas que um programador PHP deve saber](http://phpsp.org.br/5-coisas-que-um-programador-php-precisa/)
	* [10 ferramentas e outras coisas que um programador PHP deve saber](https://www.webdevbr.com.br/10-ferramentas-e-outras-coisas-que-todo-desenvolvedor-php-deve-dominar)
	* [Composer para iniciantes](http://tableless.com.br/composer-para-iniciantes/)
	* [Gerenciando dependências com o Composer](http://blog.thiagobelem.net/gerenciando-dependencias-com-o-composer)
* *3.* [Design Patterns em PHP](http://br.phptherightway.com/pages/Design-Patterns.html)

---

### Boas Práticas
* *1.* Conceito KISS
	* [K.I.S.S. - Keep It Simple, Stupid](https://pt.wikipedia.org/wiki/Keep_It_Simple)
	* [K.I.S.S (M.I.S.E - Mantenha Isto Simples Estúpido)](https://tisimples.wordpress.com/2009/04/29/kiss-keep-it-simple-stupid-mantenha-isto-simples-estupido/)
* *2.* Conceito DRY
	* [D.R.Y. - Don't Repeat Yourself](https://pt.wikipedia.org/wiki/Don%27t_repeat_yourself)
	* [D.R.Y. - O que é DRY](http://abap101.com/2009/05/28/o-que-e-ser-dry/)
	* [O princípio do 'Não se repita'](https://www.profissionaisti.com.br/2014/06/o-principio-do-nao-se-repita-dry/)
* *3.* Extra
	* [Filosofias de Desenvolvimento](http://wbruno.com.br/php/boas-praticas-de-programacao-filosofias-de-desenvolvimento/)

---

### Workflow
* *1.* Tasks Runners
	* [GulpJS - Um gole de otimização no seu workflow](http://blog.da2k.com.br/2015/01/24/gulpjs-um-gole-de-otimizacao-no-seu-workflow/)
	* [Gulp](http://desenvolvimentoparaweb.com/javascript/gulp/)
	* [GruntJS](http://www.webcis.com.br/o-que-e-o-gruntjs-por-onde-comecar-como-usar-o-gruntjs.html)
	* [A moderna caixa de ferramentas do desenvolvedor javascript](https://www.infoq.com/br/articles/modern-javascript-toolbox)
