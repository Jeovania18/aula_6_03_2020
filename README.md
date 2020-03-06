# aula_6_03_2020
O que é o CSS?
CSS é o acrônimo de Cascading Style Sheets que em português seria algo como “folhas de estilo em cascata”. É uma especificação que define como os elementos que compõem uma página, um documento ou aplicação Web serão exibidos.25/07/2012
Como funciona o CSS?
Informação: Como o CSS funciona
Ele processa o documento em duas etapas: O navegador converte a linguagem de marcação e o CSS no DOM (Modelo de Objeto de Documento). O DOM representa o documento na memória do computador. Ele combina o conteúdo do documento com seu estilo.
Seletores

Seletor	Exemplo	Descrição
.class	.intro	Seleciona todos os elementos com class="intro"
#id	#firstname	Seleciona o elemento com id="firstname"
*	*	Seleciona todos os elementos
elemento	p	Seleciona todos <p>
elemento, elemento	div, p	Seleciona todos <div> e todos elementos <p>
elemento elemento	div p	Seleciona todos elementos <p> dentro de elementos <div>
elemento > elemento	div > p	Seleciona todos <p> onde o pai é um elemento <div>
elemento+elemento	div + p	Seleciona todos <p> que estão imediatamente depois de um elemento <div>
elemento1 ~ elemento2	p ~ ul	Seleciona todo elemento <ul> que precede um elemento <p>
[attribute]	[target]	Seleciona todos os elementos com um atributo target
[attribute=value]	[target=_blank]	Seleciona todos os elementos com target="_blank"
[attribute~=value]	[title~=flower]	Seleciona todos os elementos com um atributo title contendo a palavra "flower"
[attribute|=value]	[lang|=pt-br]	Seleciona todos os elementos com um atributo lang, cujo o atributo valor comece com "pt-br"
[attribute^=value]	a[href^="https"]	Seleciona todo elemento <a> que tem um atributo href com o valor começando com "https"
[attribute$=value]	a[href$=".pdf"]	Seleciona todo elemento <a> que tem um atributo href com o valor termina com ".pdf"
[attribute*=value]	a[href*="tableless"]	Seleciona todo elemento <a> que tem um atributo href com o valor contém "tableless"
:active	a:active	Seleciona o link ativo
::after	p::after	Insere conteúdo depois de cada elemento <p>
::before	p::before	Insere conteúdo antes de cada elemento <p>
:checked	input:checked	Seleciona todo elemento <input> checked
:default	input:default	Seleciona os <input> padrão
:disabled	input:disabled	Seleciona todo <input> desabilitado
:empty	p:empty	Seleciona todo elemento <p> que não tem filhos, incluindo texto
:enabled	input:enabled	Seleciona todo <input> habilitado
:first-child	p:first-child	Seleciona todo elemento <p> que é o primeiro filho do seu pai
::first-letter	p::first-letter	Seleciona a primeira letra de todo elemento <p>
::first-line	p::first-line	Seleciona a primeira linha de todo elemento <p>
ype.asp">:first-of-type	p:first-of-type	Seleciona todo elemento <p> que é o primeiro filho do seu pai
:focus	input:focus	Seleciona o <input> que tem focus
:hover	a:hover	Seleciona links quando o mouse passa por cima
sp">:in-range	input:in-range	Seleciona o elemento <input> com o atributo value dentro de um range especificado
:indeterminate	input:indeterminate	Seleciona o elemento <input> tem um estado indeterminado
:invalid	input:invalid	Seleciona todos <input> elementos com um valor inválido
:lang(language)	p:lang(pt-br)	Seleciona todo elemento <p> com a atributo lang igual a "pt-br"
sp">:last-child	p:last-child	Seleciona todo elemento <p> que é o último filho de seu pai
ype.asp">:last-of-type	p:last-of-type	Seleciona todo elemento <p> que é o último elemento do tipo <p> do seu pai
:link	a:link	Seleciona todos links não visitados
:not(Seletor)	:not(p)	Seleciona todo elemento elemento que não é um elemento <p>
sp">:nth-child(n)	p:nth-child(2)	Seleciona todo elemento <p> que é o segundo filho do seu pai
hild.asp">:nth-last-child(n)	p:nth-last-child(2)	Seleciona todo elemento <p> que é o segundo filho do seu pai, contando com o último filho
f-type.asp">:nth-last-of-type(n)	p:nth-last-of-type(2)	Seleciona todo elemento <p> que é o segundo <p> of its parent, contando com o último filho
ype.asp">:nth-of-type(n)	p:nth-of-type(2)	Seleciona todo elemento <p> que é o segundo <p> do seu pai
ype.asp">:only-of-type	p:only-of-type	Seleciona todo elemento <p> that is the only <p> do seu pai
sp">:only-child	p:only-child	Seleciona todo elemento <p> que é o único filho do seu pai
:optional	input:optional	Seleciona o elemento <input> com sem o atributo "required"
ange.asp">:out-of-range	input:out-of-range	Seleciona o elemento <input> com o atributo value fora do range especificado
::placeholder	input::placeholder	Seleciona o elemento <input> com texto placeholder
sp">:read-only	input:read-only	Seleciona o elemento <input> com o atributo "readonly" especificado
sp">:read-write	input:read-write	Seleciona o elemento <input> com o atributo "readonly" não especificado
:required	input:required	Seleciona o elemento <input> com the "required" atributo especificado
:root	:root	Seleciona o elemento root
::selection	::selection	Seleciona a porção de um elemento que está selecionado pelo usuário
:target	#news:target	Seleciona o elemento atual ativo #news (clicado pelo usuário na URL contendo o nome ancora)
:valid	input:valid	Seleciona todos <input> elementos com um valor válido
:visited	a:visited	Seleciona todos links já visitados
  Refêrencia
  https://tableless.com.br/referencia-seletores-css/
  https://s3.novatec.com.br/capitulos/capitulo-9788575222201.pdf
  
  O Bootstrap é importante?
Mais do que outros framework front-end, o Bootstrap tem se tornado ao longo dos anos uma das ferramentas mais importantes para a criação de websites. Isto porque seus padrões seguem os princípios de usabilidade e as tendências de design para interfaces.

Além disso, sua padronização permite que os sites tenham um melhor aspecto, sendo uma forma de criar páginas esteticamente agradáveis. E você sabe que quanto melhor o design de uma página, maior a taxa de satisfação dos usuários.

Os melhores templates de Bootstrap



FAÇA O DOWNLOAD


Características e Vantagens do Bootstrap
Agora, vamos ver mais a fundo as características que fazem o Bootstrap valer a pena. Entre elas:

Biblioteca de componentes
Reuso de código
Documentação e comunidade
Padrão visual
Responsividade
E muito mais!
Biblioteca de componentes
Talvez uma das características mais interessantes deste framework é o fato dele possuir uma extensa biblioteca de componentes, como ícones, caixas de texto, painéis e cores em links. Veja um bom exemplo abaixo:

XHTML
<div class="alert alert-danger" role="alert">
Esta é uma caixa de texto vermelha!
</div>
1
2
3
<div class="alert alert-danger" role="alert">
Esta é uma caixa de texto vermelha!
</div>
Como visto acima, a formatação que a caixa recebeu foi implementada apenas pela chamada de uma determinada classe. Este é um outro recurso muito interessante do Bootstrap. Nada de muita codificação.

Reuso de código
Assim como é objetivo de todo framework, o Bootstrap permite que menos código possa ser escrito, já que ele entrega uma série de formatações visuais prontas. A única necessidade do desenvolvedor é saber qual a classe ele deve chamar.

Como mostramos no exemplo acima, o classe alert alert-danger sozinha consegue mudar não apenas as cores de fundo do texto, mas cria também uma borda para o painel e a cor da fonte. Tudo isso com uma simples linha de código com 26 caracteres.

Se você já é desenvolvedor, deve saber como este recurso pode ser útil na sua vida. Menos código digitado significa menos dor de cabeça para encontrar problemas de sintaxe, além de ser uma excelente forma de ganhar tempo.

Documentação farta e comunidade ativa
Documentação é algo que poucos programadores gostam de fazer, mas é algo essencial para que uma linguagem ou framework evoluam. E este é o caso do Bootstrap. Por ter uma documentação sempre atualizada e de fácil acesso, tirar dúvidas da ferramenta é extremamente fácil.

Não apenas dúvidas, mas uma documentação atualizada permite que as melhores práticas de programação com o framework sejam conhecidas. Isto aumenta a chance de novos projetos serem feitos com qualidade visual e técnica, o que é ótimo para o valor final do produto.


 

 
Responsividade
Além de padronizar uma série de parâmetros, o Bootstrap é uma das formas mais fáceis de deixar um site responsivo. Se você não sabe o que significa o termo, ele quer dizer que um site é adaptável a diferentes tipos de tela, como celular, tablet ou computador.

Hoje, indica-se que todos os sites devem ser responsivos para melhorar a experiência do usuário e trazer benefícios para rankeamento do Google. Com o Bootstrap, isso é algo extremamente facilitado. Com apenas uma linha de código é possível deixar todo o projeto responsivo e melhorar a exibição do conteúdo de acordo com tags específicas.

Quem usa Bootstrap hoje?
Muitos sites famosos no Brasil e exterior utilizam o Bootstrap como framework front-end. Fora do país, podemos citar o site da site da NBA, Target e Walmart. No mercado nacional, a grande maioria dos sites da Globo utilizam o framework, o que explica o excelente padrão visual que eles possuem.

Além disso, é possível criar aplicativos web com o Bootstrap, usando ferramentas como o Bootstrap Studio. Com essas ferramentas, você simplesmente arrasta o conteúdo e monta as interfaces visualmente. Toda a estrutura de código será feita pelo sistema.

Claro, esta não é a ferramenta mais indicada para quem quer trabalhar pra valer na área, mas pode quebrar um galho às vezes. Para profissionais, recomendamos aprender o framework em detalhes.

Existem desvantagens?
Se a gente falasse que não existem desvantagens ao utilizar o Bootstrap, estaríamos sendo parciais. Sendo assim, vamos apontar aqui algumas críticas que o framework recebe, mas que nem assim invalidam sua escolha na hora dos estudos e trabalho.

Excesso de padronização
Por mais que a padronização seja algo buscado com o Bootstrap, o resultado pode acabar sendo muito parecido com demais sites. Existem muitas opções de botões, painéis e ícones, mas ainda assim é comum você ver os mesmos elementos em diferentes portais. Isso acontece porque o framework é muito famoso. Pesquisas afirmam que cerca de 7 milhões de sites utilizam o Bootstrap.

A solução para isso é trabalhar em cima do Bootstrap ao invés de simplesmente chamar seus elementos. Se você souber adaptar o Bootstrap ao seu projeto, isso deixará de ser um problema.

Solução caseira pode ser melhor
Programadores experientes em front-end costumam não gostar do Bootstrap porque ele entrega muito código que não será usado, o que pode deixar os sistemas lentos. Dessa forma, eles acabam preferindo desenvolver soluções próprias, codificando “na unha”.

Isso não invalida o uso do Bootstrap. Muitas empresas utilizam ele, até mesmo as grandes, como você pôde ver. A decisão de trabalhar ou não com o framework vai depender do que você quer fazer na sua carreira. Sendo assim, indicamos que conheça o framework para ver se ele atende às suas necessidades, porque oportunidades para atuar com ele não faltam!

Como posso começar a usar o Bootstrap?
Existe uma série de coisas que você pode fazer para começar a trabalhar com o Bootstrap, e elas podem começar aí da sua casa! Veja abaixo:

Pontapé inicial: estudos!
Para começar a tirar o maior proveito possível do framework Bootstrap, indicamos que você faça o nosso curso. Ele tem tudo o que você precisa para entender os primeiros passos do framework e como ele funciona. Mas para fazer o curso, é interessante que você já possua alguns conhecimentos técnicos. Olhe quais são esses requisitos abaixo.

Linguagens básicas
As três linguagens para quem quer trabalhar com Bootstrap são o HTML, o CSS e JavaScript. Por mais que já existam classes e funções prontas, pode ser que seja necessário fazer alterações pontuais. Ou você pode precisar entender como funcionam as funções utilizadas.

Portanto, se você ainda não conhece HTML, CSS e JS, estude estas três linguagens. Dessa forma você saberá como fazer milagres com o Bootstrap! Se você não tiver como investir seu tempo e dinheiro em aprender essas linguagens agora, dê uma olhada em nosso guia para iniciantes em HTML e CSS. Esperamos que você goste!

Temas e mais temas
Uma das coisas legais do Bootstrap é que ele pode ser trabalhado por outras empresas, que acabam criando temas para a comunidade. Os sites abaixo são bem interessantes para encontrar templates bootstrap para você usar em seus projetos:

Bootstrap Zero
Start Bootstrap
BootstrapMade
Pronto para usar Bootstrap em seus projetos?
Esperamos que você tenha gostado de conhecer o Bootstrap e esteja empolgado para começar a usá-lo em seus projetos. Eu com certeza gostei de fazer um post explicando a ferramenta. Qualquer dúvida que tenha surgido, não deixe de comentar abaixo. Abraços e até a próxima!

 

[Ebook] Guia do HTML e CSS

366
SHARES
Leonello de Leone
Escrito por Leonello de Leone
Estudante de Ciência da Computação pela UFRGS. Iniciou como estagiário da área de Suporte e hoje atua como Desenvolvedor Web na TargetTrust e Becode. Possui conhecimentos em Angular 4+, Node.js, jQuery, PHP, JavaScript e por aí vai. Entusiasta das áreas de Machine Learning, Inteligência Artificial e Desenvolvimento de Jogos. Ranzinza nas horas vagas.

facebook
2 COMENTÁRIOS
LEAVE A REPLY
AvatarRICARDO MELLO FERREIRA há um ano
SÃO PESSOAS COMO VOCÊ QUE PRECISAMOS PARA CADA VEZ MAIS DISSEMINARMOS CONTEÚDOS COMO ESTE, PARA QUE MAIS E MAIS PESSOAS POSSAM APRENDER E TAMBÉM COMPARTILHAR INFORMAÇÕES INDISPENSÁVEIS AO DESENVOLVIMENTO E AMPLIAÇÃO DO CONHECIMENTO TÉCNICO EM NOSSO PAÍS.
PARABÉNS PELA SUA INICIATIVA!
E OBRIGADO.

Responder
AvatarDavid Cesar há um ano
Uma coisa que me interessa muito no Bootstrap é o sistema de Grid, ainda vou criar um projeto utilizando-o.

Responder
DEIXE UMA RESPOSTA
O seu endereço de e-mail não será publicado. Campos obrigatórios são marcados com *

Comentário
Comentário*

Nome *
Name*

E-mail *
Email*

Site
Website

VEJA MAIS FRONT-END
E se as seleções da copa do mundo fossem editores de texto e IDEs? | Becode
298Shares3.7kVisualizações10Comentários Back-end, Front-end
E se as seleções da Copa do Mundo fossem editores de texto e IDEs?
por Danilo SoaresDanilo Soares
há 2 anos
 
A imagem mostra um computador com o logo do Vue.js no centro de sua tela.
210Shares6.8kVisualizações4Comentários Front-end
(TUTORIAL) Como criar seu primeiro app com Vue.js
por André LugAndré Lug
há 2 anos
 
Os 6 frameworks e bibliotecas JavaScript que você deveria conhecer!
241Shares30.6kVisualizações7Comentários Back-end, Front-end
Os 6 frameworks e bibliotecas JavaScript que você deveria conhecer!
por Danilo SoaresDanilo Soares
há 2 anos
 
A imagem mostra uma aplicação web sendo criada com as tecnologias HTML, CSS e JavaScript.
280Shares26.6kVisualizações2Comentários Front-end, Primeiros Passos
5 aplicações que podem ser criadas aprendendo apenas HTML, CSS e JS
por Erick ScuderoErick Scudero
há 2 anos
 
5 motivos para aprender jQuery e usá-lo nos seus projetos JavaScript!
193Shares3.3kVisualizações2Comentários Front-end, Primeiros Passos
5 motivos para aprender jQuery e usá-lo nos seus projetos JavaScript!
por Leonello de LeoneLeonello de Leone
há 2 anos
 
A imagem ilustra três engenheiros construindo um website como se fosse um prédio em construção. Usando guindastes, caminhões e ferramentas de obra. A diferença é que, invés de um prédio, os engenheiros estão projetando a interface apresentada no monitor de um computador.
Popular
215Shares49.3kVisualizações7Comentários Front-end
Os 6 frameworks front-end mais amados no mundo (segundo o GitHub)
por Erick ScuderoErick Scudero
há 2 anos

 
O QUE VOCÊ PROCURA?
Search for:
O que você procura?
PESQUISE
MAIS LIDOS DO DIA
Os 5 principais cursos superiores de TI e suas diferenças!
550Shares158.9kVisualizações
Os 5 principais cursos superiores de TI e suas diferenças!
 
Os 10 comandos SQL que você não pode viver sem! | Becode
Os 10 comandos SQL que você não pode viver sem!
 
O que é API? REST e RESTful? Conheça as definições e diferenças!
O que é API? REST e RESTful? Conheça as definições e diferenças!
 
As 15 principais linguagens de programação no mundo! | Becode
As 15 principais linguagens de programação do mundo!
 
A melhor forma de aprender lógica de programação | Becode
A melhor forma de aprender lógica de programação!
SIGA A BECODE
facebook 
twitter 
linkedin 
youtube

CSS com uma pegada mínima.
Puro é ridiculamente pequeno. Todo o conjunto de módulos possui 3,8 KB * de tamanho reduzido e compactado com gzip . Criado com dispositivos móveis, era importante para nós manter nossos tamanhos de arquivo pequenos e todas as linhas de CSS eram cuidadosamente consideradas. Se você decidir usar apenas um subconjunto desses módulos, economizará ainda mais bytes.
