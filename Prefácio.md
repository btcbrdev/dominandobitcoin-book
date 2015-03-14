# Escrevendo o livro Bitcoin

A primeira vez que ouvi falar em bitcoin foi em meados de 2011. Minha reação imediata foi mais ou menos essa "Pfft! Dinheiro de nerd!" e eu ignorei-o por mais seis meses, sem compreender a sua importância. Esta é uma reação que eu tenho observado com frequência entre muitas das pessoas mais inteligentes que conheço, o que me dá algum consolo. A segunda vez que me deparei com bitcoin, em uma lista de discussão, eu decidi ler o seu "manual de instruções" oficial, a _white page_, escrito pelo seu criador, Satoshi Nakamoto, para ver do que se tratava. Ainda me lembro do momento em que eu terminei de ler essas nove páginas, quando eu percebi que bitcoin não era simplesmente uma moeda digital, mas uma rede de confiança que também poderia servir de base para aplicações muito mais avançadas do que apenas moedas. Após constatar que o bitcoin não é dinheiro, mas sim uma rede de confiança descentralizada, comecei uma viagem de quatro meses para devorar cada pedaço de informação que eu poderia encontrar sobre o assunto. Eu me tornei obcecado e encantado, gastando 12 ou mais horas por dia colado ao monitor, lendo, escrevendo, codificando e aprendendo o máximo que pude. Após pular muitas refeições, saí desse período de obsessão 20 quilos mais leve e determinado a dedicar-me a trabalhar com bitcoin.

Two years later, after creating a number of small startups to explore various bitcoin-related services and products, I decided that it was time to write my first book. Bitcoin was the topic that had driven me into a frenzy of creativity and consumed my thoughts; it was the most exciting technology I had encountered since the Internet. It was now time to share my passion about this amazing technology with a broader audience.

## Público Alvo

Esse livro foi escrito principalmente para programadores. Se você sabe alguma linguagem de programação, esse livro irá ensiná-lo como as moedas criptográficas funcionam, como utilizá-las e como desenvolver softwares que trabalhem com elas. Os primeiros capítulos também são adequados como uma introdução aprofundada ao bitcoin para não-programadores, que queiram entender o funcionamento interno do bitcoin e das criptomoedas.

## Por que a capa do livro tem insetos?

A formiga leafcutter é uma espécie que possui um comportamente altamente complexo em um super-organismo de colônia, mas cada formiga individualmente opera sob um conjunto de regras simples dirigidas por interação social e pela troca de aromas químicos (feromônios). De acordo com a Wikipedia: "Depois dos humanos, as formigas leafcutter formam as maiores e maix complexas sociedades animais do planeta Terra". As formigas leafcutter de fato não comem as folhas, mas as utilizam para cultivar um fungo, que é a fonte central de comida da colônia. Você compreendeu isso? Essas formigas estão fazendo agricultura!

Embora as formigas formem uma sociedade baseada em castas e possuam uma rainha para produzir a prole, não há uma autoridade central ou um líder na colônia de formigas. O comportamento altamente inteligente e sofisticado exibido pela colônia composta por milhões de membros é uma propriedade que surge a partir da interação dos indivíduos em uma rede social.

A natureza demonstra que sistemas descentralizados podem ser versáteis e podem uma complexidade que evolui, além de uma sofisticação incrível, tudo isso sem a necessidade de uma autordade central, hierarquia ou partes complexas.

O Bitcoin é uma rede de confiança descentralizada altamente sofisticada que pode suportar uma grande diversidade de processos financeiros, No entanto, cada nodo na rede bitcoin segue algums poucas regras matemáticas simples. A interação entre os múltiplos nodos, e não uma complexidade inerente ou confiança em um nodo único, é o que leva à emergência de um comportamento sofisticado. Como uma colônia de formigas, a rede bitcoin é uma rede versátil de nodos simples, seguindo regras simples, que juntos podem fazer coisas incríveis, sem depender de uma coordenação central.

## Convenções Usadas Neste Livro

As seguintes convenções tipográficas são usadas neste livro:

<dl>
<dt>
<em>Itálico</em>
</dt>
<dd>
Indica novos termos, URLs, endereços de e-mail, nomes e extensões de arquivos.
</dd>
<dt>
Constant width
</dt>
<dd>
Used for program listings, as well as within paragraphs to refer to program elements such as variable or function names, databases, data types, environment variables, statements, and keywords.
</dd>
<dt>
Constant width bold
</dt>
<dd>
Shows commands or other text that should be typed literally by the user.
</dd>
<dt>Constant width italic</dt>
<dd>
Shows text that should be replaced with user-supplied values or by values determined by context.
</dd>
</dl>

> Esse ícone é usado em divas, sugestões ou notas em geral.

> Esse ícone indica uma mensagem de aviso ou cuidado.

## Code Examples

The examples are illustrated in Python, C++, and using the command line of a Unix-like operating system such as Linux or Mac OS X. All code snippets are available in the GitHub repository in the code subdirectory of the main repo. Fork the book code, try the code examples, or submit corrections via GitHub.

All the code snippets can be replicated on most operating systems with a minimal installation of compilers and interpreters for the corresponding languages. Where necessary, we provide basic installation instructions and step-by-step examples of the output of those instructions.

Some of the code snippets and code output have been reformatted for print. In all such cases, the lines have been split by a backslash (\) character, followed by a newline character. When transcribing the examples, remove those two characters and join the lines again and you should see identical results as shown in the example.

All the code snippets use real values and calculations where possible, so that you can build from example to example and see the same results in any code you write to calculate the same values. For example, the private keys and corresponding public keys and addresses are all real. The sample transactions, blocks, and blockchain references have all been introduced in the actual bitcoin blockchain and are part of the public ledger, so you can review them on any bitcoin system.

## Using Code Examples

This book is here to help you get your job done. In general, if example code is offered with this book, you may use it in your programs and documentation. You do not need to contact us for permission unless you’re reproducing a significant portion of the code. For example, writing a program that uses several chunks of code from this book does not require permission. Selling or distributing a CD-ROM of examples from O’Reilly books does require permission. Answering a question by citing this book and quoting example code does not require permission. Incorporating a significant amount of example code from this book into your product’s documentation does require permission.

We appreciate, but do not require, attribution. An attribution usually includes the title, author, publisher, and ISBN. For example: “Mastering Bitcoin by Andreas M. Antonopoulos (O’Reilly). Copyright 2015 Andreas M. Antonopoulos, 978-1-449-37404-4.”

Some editions of this book are offered under an open source license, such as CC-BY-NC (creativecommons.org), in which case the terms of that license apply.

If you feel your use of code examples falls outside fair use or the permission given above, feel free to contact us at <permissions@oreilly.com>.

## Safari® Books Online

> Safari Books Online is an on-demand digital library that delivers expert content in both book and video form from the world’s leading authors in technology and business.

Technology professionals, software developers, web designers, and business and creative professionals use Safari Books Online as their primary resource for research, problem solving, learning, and certification training.

Safari Books Online offers a range of product mixes and pricing programs for organizations, government agencies, and individuals. Subscribers have access to thousands of books, training videos, and prepublication manuscripts in one fully searchable database from publishers like O’Reilly Media, Prentice Hall Professional, Addison-Wesley Professional, Microsoft Press, Sams, Que, Peachpit Press, Focal Press, Cisco Press, John Wiley & Sons, Syngress, Morgan Kaufmann, IBM Redbooks, Packt, Adobe Press, FT Press, Apress, Manning, New Riders, McGraw-Hill, Jones & Bartlett, Course Technology, and dozens more. For more information about Safari Books Online, please visit us online.
