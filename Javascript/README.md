# Conteúdo de suporte de comandos UC08 - Lógica de Programação
-------------------------------------------------------------------------------

## Variáveis

- **_var número = 10_** - declara uma variável que receberá um tipo de dano, podendo ser um número ou um nome e receber novos dados que substituem essa variável.

- **_let nome = João_** - declara uma variável que receberá um tipo de dano, podendo ser um número ou um nome e receber novos dados que substituem essa variável.

- **_Const Pi = 3,14_** - declara uma constante que receberá um tipo de dano, não podendo ser alterada.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Operadores Lógicos

- **_Exemplificacao do operador AND (E) simbolo &&_** - O operador AND true retornará se ambos os operands são true e retornarão caso false contrário.  

true && true > true  
true && false > false  
false && true > false  
false && false > false  



**_Exemplificacao do operador OR (OU), simbolo ||_** - O operador OR true retornará se qualquer um dos operands ou ambos for true e retornarão caso false contrário.  

true || true > true  
true || false > true  
false || true > true  
false || false > false  

**_Exemplificacao do operador NOT (NÃO), simbolo !_** - Inverte o resultado. O resultado será true se o operand convertido for false ; o resultado será se o false operand convertido for true . O resultado é do tipo bool .

!true > false  
!false > true  

**IMPORTANTE!**, existe uma ordem de precedencia, onde se e resolvido em uma ordem especifica os operadores logicos, esta ordem é !,&& e ||.

**_Exemplificacao do operador %(resto da divisão)_** - Faz uma divisão entre dois números e o resultado é o resto da divisão. Exemplo:

5%2 = 1
6%2 = 0

**_Exemplificacao do operador **(potencia)_** - faz um numero elevado ao outro. Exemplo:

 5**2 = 25
 3**2 = 9

**_Exemplificacao do operador ==(igual) e !=(diferente)_** - mostra igualdade entre duas grandezas ou mostra que duas grandezas sao diferentes, respectivamente.Exemplo:

5==5 = true 
5==2 = false
5!=6 = true
5!=5 = false

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Comandos de decisão

- **_Condição SE(IF), faz algo se a condição for cumprida.Exemplo:_**

if(condition){  
	what happens if the condition is true  
}  
if(numero == 10){    
	console.log("O numero contido na variavel numero **é** 10")    
}  


- **_Condição IF ELSE(SE NÃO), é utilizado sempre junto com um if anterior, onde esta condição é verificada apenas quando o resultado do if anterior tem um resultado FALSE,_** 

"**SE** a condição antiror **NÃO** for atendida".**_Exemplo:_**

else if(condition){  
	what happens if the condition is true  
}  
else if(numero < 10){    
	console.log("O número contido na variavel numero é **menor** que 10")    
}  


- **_Condição ELSE(OUTRO), é utilizado sempre junto com um if anterior E/OU else if, onde é executado apenas quando todos os if e/ou else if dão um resultado FALSE,_** 

"se todas as **OUTRAS** condições anteriores **NÃO** forem atendidas".**_Exemplo:_**

else{  
	what happens if all the conditions resulted in false  
}  
else{   
	console.log("O número contido na variavel numero é **maior** que 10")    
}  

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Estruturas de repetição

- **_While(Enquanto)_** - Este comando verifica a condição e, caso ela seja verdadeira ele executa o comando, repetindo o processo até que a condição seja falsa.Exemplo:

let listaDeAlunos = ["Marcelo","Juh", "Cleber", "Wesley","Adriano"]  
let contador = 0  
while(contador < listaDeAlunos.lenght){  
	console.log(listaDeAlunos[contador])  
	contador++  
}

- **_DO While(Faça Enquanto)_** - Este comando executa antes de verificar a condição pelo menos uma vez e, caso ela seja verdadeira, continua a executar o comando até ela se tornar falsa.Exemplo:

let listaDeAlunos = ["Marcelo","Juh", "Cleber", "Wesley","Adriano"]  
let contador = 0  
do{  
	console.log(listaDeAlunos[contador])  
	contador++  
}  
while  (contador < listaDeAlunos.length) 

- **_FOR(PARA)_** - O comando for permite que um certo trecho de programa seja executado um determinado número de vezes. No exemplo abaixo o comando for faz a contagem dos numeros informando se são pares ou impares.

let numeroDeAlunos = 10;  

for (let contador = 0; contador <= numeroDeAlunos; contador++) {  
   if (contador === 0) {    
       console.log("O número atual é Zero")    
       } else if (contador%2 == 0) {     
        console.log("O número " + contador +" é Par")    
       } else {  
           console.log("O número " + contador +" é Ímpar")    
    }  
}  

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Mais estruturas de repetição

- **_FOR OF(PARA DE)_** - Percorre objetos iterativos (incluindo Array, Map, Set, o objeto arguments e assim por diante), chamando uma função personalizada com instruções a serem executadas para o valor de cada objeto distinto.

let listaDeAlunos = ["Marcelo","Juh", "Cleber", "Wesley","Adriano"]  
for (const aluno of listaDeAlunos){  
console.log(aluno)  
}

- **_FOR EACH(PARA CADA)_** - O método forEach() executa uma dada função em cada elemento de um array.

let listaDeAlunos = ["Marcelo","Juh", "Cleber", "Wesley","Adriano"]  
listaDeAlunos.forEach(aluno => {  
    console.log(aluno)  
});  

Dentro do argumento da estrutura de repetição podem ser usados ainda argumentos como funções, Exemplo:  

function listadepecas(element, index, array) {      
 lista.innerHTML += `<p>${element} [${index + 1}] ${pesos[index]} gramas</p>`  
 }    
 pecas.forEach(listadepecas)   
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Mais Comandos Aprendidos nesta unidade

- **DATE**_ - É um objeto do tipo DATE, que armazena uma série de funções dentro dele permitindo o acesso rápido a funções ligadas a hora, dia, mes e ano atuais. É muito útil em processos que dependem de tempo para serem feitos ou cadastrados.

**let** - Declara a váriavel que irá conter o objeto, sempre que chamarmos essa váriavel seguida de ".", estaremos chamando as funções dentro dele. Exemplo
**new** - Declara que existe um objeto dentro da variável, sem isto seria criado uma váriavel contendo a string "DATE"
**Date()** - Declara o objeto especifico com suas funcionalidades

Exemplo:

let a = **new** Date()  
a.GetMonth() - chama a função que dirá o mês atual  
a.getFullYear() - Ano  
a.getDate() - Dia  

Exemplo de sintaxe completa:

let dataAtual = new Date()  
let ano = 2021 - informacao digitada pelo usuario  

if (ano > dataAtual.getFullYear()){  
    console.log("Esta data é no ano que vem")   
}  

**style.display** - Recebe os valores "none" e "block", o none deixa o texto, elementos em questao invisiveis e o block os mostra de novo.  

<**div id="contextText"**><**p**>Texto que vai sumir<**/p**><**/div**>  
var x = document.getElementById('contextText');    
x.style.display ==='none' - deixa o texto invisivel  
x.style.display = 'block' - deixa o texto visivel

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Classes Jquery

    Um exemplo prático para o uso das classes ocorre quando você tem uma div pai que contém diversas tags p e você deseja estilizar apenas uma. Nessa situação, você pode adicionar uma class para essa tag específica e, no JavaScript, você irá chamá-la utilizando esse método e passando como condição a estilização.

**.addClass() E .removeClass()** - .addClass e .removeClass adicionam e removem, respectivamente, a class dos elementos do HTML, alterando seu estado, ou seja, sua estilização.  

$("p").addClass("#demo");     
$("p").removeClass("#demo").addClass(".textStyle");  

o **id** ou **class** é selecionado pelo simbolo de # ou ., para definir se será adicionado uma class ou um id.  

_**.hasClass()**_ - .hasClass é um método que retorna true ou false, pois ele irá comparar a class atribuída ao elemento do HTML.  

<**div id ="mydiv" class="foo bar"**><**/div**>
$("#mydiv").hasClass("foo")

# Conteúdo de suporte de comandos Curso em Video
------------------------------------------------------------------------------

## Comandos 

- **_window.alert_** - Mostra uma mensagem ao usuário

- **_window.confirm_** - pergunta algo ao usuário gerando uma resposta true or false

- **_window.prompt_** - abre um espaço para o usuário digitar uma informação que sempre será guardada em formato de sting.

- **_document.writeIn()_** - Escreve na página o conteúdo digitado entre parenteses.

 - **_document.write()_** - Busca conteúdo de texto armazenada em variáveis
Exemplo:  

var nome = window.prompt("Qual e o seu nome?")
       window.alert('É um grande prazer te conhecer '+nome)    

- **_array vazio_** - para criar um array vazio utilizado para inserção de variáveis é utilizado a seguinte forma  

var nomes = []

- **_inserir elementos em um array_** - comando utilizado:  

nome.push(nomes)





 

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Comandos de Utilidade


- **_Number.parseInt_** , **_Number.parseFloat_** e **_Number_**- transforma o tipo de dado em número **INTEIRO** e **REAL**, respectivamente. 

var n1 = Number.parseInt(window.prompt('digite um numero'))   
var n2 = Number.parseFloat(window.prompt('digite o código de segurança')) 
var n3 = Number(numero) - numero neste caso é uma variável string que será convertida.  


- **_toUpperCase()_** e **_toLowerCase()_** - Transforma uma cadeia de caracteres em todos maiusculos ou todos minusculos, respectivamente.

 document.writeln(`Seu nome em minusculas é ${nome.toLowerCase()}`)
 document.writeln(`Seu nome em maiuculas é ${nome.toUpperCase()}.`)  

- **_Place Holder_** - placeholder é uma forma mais simples de concatenar consiste em declarar o placeholder com o simbolo "$" e depois declarar a variavel ou função entre colchetes, para isso é necessário usar crase. Exemplo:

var n1 = 2  
var n2 = 5  
var s = n1+n2  

window.alert("A soma entre ${n1} e ${n2} é igual a ${s}."), o resultado disso sera:

A soma entre 2 e 5 é igual a 7.

- **_toFixed()_** e **_toFixed().replace()_**  - fixa o número de casas decimais de um número e troca algum dos termos que aparecerão por outro. Exemplo 1:  

n1 = 10.5  
n1.toFixed(2)
n1 = 10.50  

Exemplo 2:  

n1 = 10.5  
n1.toFixed(2).replace(".",",") - trocar ponto por vírgula
n1 = 10,50  

**_Converter Moeda para Real_**  

n1.toLocaleSting("pt-BR", {style: "currency", currency: "BRL"})

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Comandos de Busca (1/2)

- **_1 - getElementsByTagName(ache os elementos por tag)_** - Este buscador busca elementos do texto pela tag, por exemplo, buscar um paragrafo (tag p):

<.p> Primeiro paragrafo, **negrito** <./p>  
var A = window.document.getElementsByTagName("p")[0]  

Agora o conteúdo da variável A é o primeiro parágrafo.  

- **_IMPORTANTE:.innerText_** e **_.innerHTML_** - o primeiro busca apenas o texto dentro de um arquivo, enquanto o segundo busca o texto e a formatação presente no HTML. Exemplo:

document.write(A.innerText) > Primeiro paragrafo, negrito     

document.write(A.innerHTML) Primeiro paragrafo, **negrito**   

- **_2 - getElementById (ache O elemento por ID)_** - busca UM elemento que tem o ID especifico. Exemplo:

var d = window.document.getElementById("msg")

- **_3 - getElementByName (ache O elemento por nome)_** - busca TODOS os elementos que tem o NOME especifico e apresenta um deles. Exemplo:

var d = window.document.getElementByName("msg")[0]

- **_3 - querySelector() ou querySelectorAll()_** - seleciona um arquivo de forma a constar nos argumentos a TAG e outro identificador. Exemplo:

var d = window.document.querySelector("div#msg")  

Note que div é uma tag e msg é o ID dado a frase.

**IMPORTANTE** - durante o uso do querySelector, deve-se notar que toda div é representada por "#", toda classe é representada por ".".

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Identificadores para busca (2/2)

- **_1 - Tag_** - identifica partes do texto por uma marcação, como o começo e o final de um parágrado do texto, da parte de javascript, CSS ou até mesmo se uma palavra está em negrito ou não. Ignore os pontos.

<.p></.p> - <.script></.script> - <.style></.style> - <.body></.body>

- **_2 - ID_** - identifica partes do seu documento com um identificador, facilitando a organização e a busca futura dessa informações, so pode ser usado um ID com o mesmo nome por vez, isto e, so pode ser utilizado uma vez por ID. Ignore os pontos.

<.div id = "msg"></.div>

todo vez que for buscado o ID msg, o resultado será o conteúdo dessa div.

- **_2 - NAME_** - identifica partes do seu documento com um nome, possibilitando a busca de todos os elementos com este nome. Ignore os pontos.

<.div name = "msg"></.div>

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Comandos de eventos  

- **_addEventListener_** - adiciona um ouvidor que sempre estara atento ao evento. Exemplo:   

objeto_a_ser_monitorado.addEventListener("nome_do_evento", nome_da_funcao)
a.addEventListener("click", clicar)

Neste exemplo, o ouvidor ira trabalhar dentro do objeto a, toda vez que o mouse clicar dentro da area do objeto a, ele ira executar a funcao clicar.


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## HTML - input  

- **_input_** - adiciona um tipo de caixa de interacao com o usuario que permite a ele colocar informacoes como datas, numeros, documentos, textos, e interagir de diversas formas.  

<input type="number" name ="n1" id="n1">  
<input type="button" value="Somar" onclick="somar()">

var a = document.getElementById ("txtn1")

no primeiro exemplo, temos uma area para a digitacao de um numero que sera salvo pela variavel a

no segundo exemplo, temos uma area criada para um botao que pode interagir com o usuario de forma a fazer algo, no caso executa uma funcao que tem o nome de somar e sera executada ao clicar em cima da area do botao.

## Javascript - input

- **_input_** - para armazenar um input em uma variável devemos usar a seguinte estrutura:

<input type="text" name ="txtn1" id="txtn1"> 
var nome = document.getElementById("txtn1") - Este tipo de var retorna HTML element
var nome1 = nome.value - Este tipo de var retorna o valor do elemento, no caso, o nome.





- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Edição de Texto

- **_font_** - edita a fonte da pagina na parte de css, exemplo:  

font: normal 20pt Arial;  

- **_background_** - edita a cor da pagina ou area selecionada na parte de css, exemplo:  

 background: green;

- **_color_** - Edita a cor do elemento (letra no exemplo)  

 color:white;

- **_width e  height_** - Define a largura do objeto selecionado ou da pagina. Exemplo:  
 
 width: 200px;
 height: 200px;

 - **_line-height e  text-align_** - Define a altura da linha em que o texto esta e define o tipo de alinhamento que sera aplicado no texto. Exemplo:  

  line-height: 200px;
  text-align: center;

## Eventos uteis   
https://developer.mozilla.org/pt-BR/docs/Web/Events - referencia de eventos da mozila, caso nao ache um evento provavelmente ele estara aqui
### Eventos de mouse   

- **_mouseenter_** - Aciona algo quando o mouse entra em um area  
- **_mousemove_** - Aciona algo quando o mouse se move em um area  
- **_mouseup_** - Aciona algo quando o mouse sobe em um area
- **_mousedown_** - Aciona algo quando o mouse e pressionado para baixo com o botao esquerdo dentro de uma area  
- **_click_** - Aciona algo quando o mouse clica em uma area  
- **_mouseout_** - Aciona algo quando o mouse sai de uma area  






