
#  Módulo 1 - HTML



## 1 - História da internet 🌐

Anotações desnecessárias devido a conhecimento prévio - todo conteúdo presente no [PDF do capítulo 1](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/01%20-%20História%20da%20Internet.pdf).

## 2 - Como a internet funciona? 🕵️

Conteúdo de apoio presente no [PDF do capítulo 2](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/02%20-%20Como%20funciona%20a%20Internet.pdf).

### 2.1 - Resumo

 - Bit
 - Tabela dos múltiplos do Bit
 - DNS - Domain name system
 - URL - Uniform resource locator
 - Protocolos de transferência
 - Domínio
 - Subdomínio
 - TLDs - Top level domain

### 2.2 - Bits e Bytes 

<dl>
    <dt>Bit</dt>
    <dd>Digito binário, representado por 0 ou 1.</dd>
    <dt>Byte</dt>
    <dd>conjunto de 8 bits, é a porção mínima para representar um dado.</dd>
    <dt>UTF-8</dt>
    <dd>UTF-8 (8-bit Unicode Transformation Format) é um tipo de codificação binária (Unicode), incluindo caracteres espciais como os acentos gráficos brasileiros.</dd>
    <dt>MB</dt>
    <dd>Representa Megabytes, geralmente representado para quantidades de *armazenamento*.</dd>
    <dt>Mb</dt>
    <dd>Representa Megabits, geralmente representado para quantidades de *transmissão*.</dd>
    <dt>Múltiplos</dt>
    <dd>Os múltiplos do byte e bit são representados pela multiplicação por 1024, não por 1000. Pois a representação é feita na base 2, ou seja. 2 elevado a 10 = 1024.  </dd>

</dl>

| Dados          | Múltiplo   | Equivalente em bytes      |
| -------------- | ---------- | ------------------------- |
| 1024 bytes     | 1 Kilobyte | 1.024                     |
| 1024 Kilobytes | 1 Megabyte | 1.048.576                 |
| 1024 Megabytes | 1 Gigabyte | 1.073.741.824             |
| 1024 Gigabytes | 1 Terabyte | 1.099.511.627.776         |
| 1024 Terabytes | 1 Petabyte | 1.125.899.906.842.624     |
| 1024 Petabytes | 1 Exabyte  | 1.152.921.504.606.846.976 |



### 2.3 - O que é domínio e hospedagem?  

<dl>
    <dt>DNS</dt>
    <dd>Domain name system é o sistema que guarda os endereços de IP dos servidores, ou seja, quando você acessa um link nominal como www.facebook.com, você acessa um servidor DNS e pergunta a esse servidor qual o IP do domínio www.facebook.com, recebendo o IP atual do site, por exemplo, 66.220.144.0. O que nós acessamos é o IP do site, não o nome.</dd>
    <dt>URL</dt>
    <dd>Uniform resource locator ou localizador de recurso uniforme é um endereço único que te aponta para um ponto específico na internet, ele pode ser formado por um ou mais dos seguintes componentes:</dd>
<pre>Protocolo de transferência
Subdomínio 
Domínio</pre>
    <dt>Protocolo de transferência</dt>
    <dd>É um sistema de comunicação de informação, indica quais regras serão utilizadas para a transferências de dados.</dd>
<pre>Http - Hypertext Transfer Protocol 
Https - Hyper Text Transfer Protocol Secure </pre>
    <p>
        Note que Https:// é um protocolo para troca de informações, sendo a letra S a representatividade de um nível de segurança.
    </p>
    <dt>Subdomnínio</dt>
    <dd>tem a função de separar áreas de um site cuja identificação será feita pelo subdomínio. Exemplo:</dd>
    <pre>loja.meusite.com    
blog.meusite.com    
eventos.meusite.com</pre>
    <p>
        É notório dizer que o subdomínio, além do que já foi falado, não tem uma função específica. Um site com WWW. ou sem terá a mesma fucionalidade.
        Resumidamente **a função principal é ter dois sites em um mesmo domínio que fazem funções diferentes como é visto nos seguintes casos**:
    </p>   
  <pre>google.com  
mail.google.com - indica que será acessado o Gmail dentro do domínio do google.  
maps.google.com - indica que será acessado o maps dentro do domínio do google.</pre>
    <dt>Domínio</dt>
    <dd>É um nome único que representa um servidor na internet. Exemplo: </dd>
    <pre>youtube.com  
facebook.com  
instagram.com  
google.com  </pre>
    <dt>TLDs</dt>
    <dd>Top level domains ou tlds normalmente tem a função de facilitar o acesso aos dados, eles fazem isso de forma a agrupar os dados em servidores DNS responsáveis por seus tlds, ou seja, quando dizemos que nosso site tem o tld **google.com.br**, estamos dizendo que podemos achar o endereço de IP do site em um dos servidores DNS **.com** ou **.br**.</dd>
<p>Este processo se da da seguinte forma: </p>   
<p><em><strong>Computador</strong></em> &rarr; <em><strong>provedor</strong></em> &rarr; <em><strong>servidor .br</strong></em> &rarr; <em><strong>servidor google</strong></em></p>
    <dt>GTlds</dt>
    <dd>Generic top level domain são representados por nomes genéricos que, normalmente, tem algum significado atrelado:</dd>
    <pre>.com - comercial
.edu - educacional
.gov - governamental
.org - ONGs</pre>
    <dt>ccTlds</dt>
    <dd>Country code top level domain são representados pela sigla de países:</dd>
    <pre>.br - Brasil  
.us - Estados Unidos  
.uk - Reino Unido  
.jp - Japão  </pre>
    <p>
        Note que um endereço sem tld não pode ser achado facilmente pois não está listado em nenhum servidor DNS podendo ser acessado ainda por IP, mas por uma forma muito mais dificil e não-prática.
    </p>
</dl> 

## 3 - Como funciona HTML e CSS? 🧑🏽‍💻
 
Anotações desnecessárias devido a conhecimento prévio - todo conteúdo presente no [PDF do capítulo 3](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/03%20-%20Como%20funciona%20HTML%20e%20CSS.pdf).

## 4 - Primeiros passos HTML. 🖥️

Anotações desnecessárias devido a conhecimento prévio - todo conteúdo presente no [PDF do capítulo 4](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/04%20-%20Primeiros%20passos%20HTML.pdf).



## 5 - Caracteres, parágrafos e quebras de linha. 📝

Conteúdo de apoio presente no [PDF do capítulo 5](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/05%20-%20Caracteres%2C%20parágrafos%20e%20quebras%20de%20linha.pdf).


### 5.1 - Resumo
<ul>
    <li>Comandos básicos HTML</li>
    <li>Símbolos Especiais</li>
    <li>Emojis</li>
</ul>

### 5.2 - Comandos TAGs

- __*&lt;H1&gt;*__ - indica título

- __*&lt;p&gt;*__ - indica parágrafo

- __*&lt;hr&gt;*__ - adiciona uma linha horizontal

- __*&lt;br&gt;*__ - quebra de linha


### 5.3 - Símbolos Especiais (precisam ter o ; no final para funcionar)

- __*&lt*__ substitui o símbolo &lt;.

- __*&gt*__ substitui o símbolo &gt;.

- __*&reg*__ - marca registrada &reg;.

- __*&copy*__ - copyright &copy;.

- __*&trade*__ - trademark symbol &trade;.

- __*&euro*__ - Euro &euro;

- __*&pound*__ - Libra esterlina &pound;.

- __*&yen*__ - Ienes &yen;.

- __*&cent*__ - Centavos americanos &cent;.

- __*&empty*__ - Vazio &empty;.

- __*&sum*__ - Soma &sum;.

- __*&Delta*__ - Delta &Delta;.

- __*&larr*__ - Seta esquerda &larr;.

- __*&uarr*__ - Seta para cima &uarr;.

- __*&rarr*__ - Seta direita &rarr;.

- __*&darr*__ - Seta para baixo &darr;.

Ainda existem uma grande variedade de símbolos que podem ser encontradas pesquisando por misc symbols ou acessando: https://www.w3schools.com/charsets/ref_utf_symbols.asp

### 5.4 - Emojis

😀
😃
😙
😝
😪

Os emojis podem ser encontrados pesquisando por emojipedia ou acessando: https://emojipedia.org/

    Note que copiar e colar não funciona para todos os navegadores, o processo correto é acessar a página, descer até a aba CODEPOINTS e copiar o código depois do U+. Exemplo:  

U+1F600 copiaremos apenas o 1F600.

Feito isso, dentro do arquivo HTML, colocaremos da seguinte forma:

&#x1F600

Note que para funcionar deve-se acrescentar o ; no final do código.



## 6 - Imagens 📷

Conteúdo de apoio presente no [PDF do capítulo 6](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/06%20-%20Imagens%20e%20Favicon.pdf).

### 6.1 - Resumo

- Imagens gratuitas para usar no seu site.
- Informações sobre formatos de imagens na web.
- Criação de favicon.

### 6.2 - Achando imagens na Web e editando.  

Busque nesses sites gratuitos:

- UnSplash
- Pexels
- FreePik
- Rawpixels
- Pixabay
- Libreshot

Software gratuito para edição de imagens

Gimp

### 6.3 - Formatos de imagens na Web.  

<dl>
    <dt>JPGE</dt>
    <dd>Compacta as imagens, pegando os pixels que tem a mesma cor e salvando a cor deles em um único lugar. Ao dar zoom, a imagem tende a se distorcer mais. Menor qualidade e tamanho compactado.</dd>
    <dt>PNG</dt>
    <dd>Imagens com transparência, maior tamanho e menor qualidade.</dd>
    <dt>GIF</dt>
    <dd>Transparência e animação.</dd>
</dl>

### 6.4 - Qual tamanho de imagem devo usar?

Normalmente as imagens da WEB tem que ser sempre leves para possibilitar que sejam carregadas em todas as conexões, ou seja, máximo de 1MB.

### 6.5 - Redimensionando imagem com o Gimp.

Imagem depois a opção redimencionar imagem

Ferramenta de corte, dimensionar corte, apertar ENTER.

### 6.6 - Favicon.  

Favicon é um ícone que aparece nas abas do navegador logo do lado do nome do site.

Sites que facilitam a criação de favicons
 
 https://favicon.io



## 7 - Hierarquia de Títulos. 📑

Anotações desnecessárias devido a conhecimento prévio - todo conteúdo presente no [PDF do capítulo 7](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/07%20-%20Hierarquia%20de%20títulos.pdf).



## 8 - Formatação de textos. 📖

Conteúdo de apoio presente no [PDF do capítulo 8](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/08%20-%20Formatação%20de%20Textos.pdf).

### 8.1 - TAGs de formatação.

- __*&lt;strong&gt;*__ - <strong>negrito</strong>, destaque

- __*&lt;em&gt;*__ - <em>italico</em>, enfase

- __*&lt;mark&gt;*__ - <mark>marca texto amarelo</mark>

- __*&lt;small&gt;*__ - <small>deixa o texto menor</small>

- __*&lt;del&gt;*__ - <del>texto deletado, riscado</del>

- __*&lt;ins&gt;*__ - <ins>texto inserido, sublinhado</ins>

- __*&lt;sup&gt;*__ - texto sobreescrito X<sup>20</sup>-3

- __*&lt;sub&gt;*__ - texto subescrito H<sub>2</sub>O

- __*&lt;code&gt;*__ - fonte modo espaçada, geralmente usada para códigos <code>document.getElementById('teste')</code>

- __*&lt;pre&gt;*__ - mantém a identação do código, significa pré-formatado.

 <pre>
        <code>
            num = int(input('Digite um número'))
            if num % 2 == 0
                print(f'0 número {num} é PAR)
            else:
                print(f'0 número {num} é ÍMPAR)
            print('Fim do programa')
        </code>
    </pre>

- __*&lt;q&gt;*__ - <q>deixa o texto como citação</q>

- __*&lt;blockquote&gt;*__ - cita um bloco de texto.

Note que ainda existe o parâmetro cite="link" para citar a fonte do texto.

<blockquote>
        A diferença entre elementos inline e um bloco de texto é importante. Os elementos HTML neste capítulo descrevem os blocos de texto.
</blockquote>

- __*&lt;abbr&gt;*__ - abreviações, ao passar o mouse em cima mostra o nome completo.

![Screenshot](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/abbr.PNG)

- __*&lt;bdo&gt;*__ - inverte o texto.

<bdo dir="rtl">.lmth me sasioc rairc a odnednerpa uotsE</bdo>

## 9 - Listas. 📜

Conteúdo de apoio presente no [PDF do capítulo 9](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/09%20-%20Listas%20HTML.pdf).

### 9.1 - Listas ordenadas ou Ordered list.

- A lista ordenada é por padrão uma lista númérica, ela ainda pode receber os argumentos __*type*__  e __*start*__.

    type indica o tipo de lista, podendo ser "1", representando úma lista numérica:

Código:

```
    <ol type ="1">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>

    <ol type ="A">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>

```

Resultado:


<ol type ="1">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>

<ol type ="A">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>


---

    start indica o índice de começo da lista:

Código:

```
    <ol start = "5">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>

    <ol type = "A" start = "5">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>


```

Resultado:

  <ol start = "5">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>

<ol type = "A" start = "5">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ol>

---

 ### 9.2 - Listas não-ordenadas ou Unordered lists.

- A lista ordenada é por padrão tem um símbolo circular, ela recebe apenas o argumento __*type*__.

type indica o tipo de lista, podendo ser circular, circular vazada ou quadrada.

Código:

```
     <ul type ="disc">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ul>

    <ul type ="square">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ul>

    <ul type ="circle">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ul>

```

Resultado:

<ul type ="disc">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ul>

<ul type ="square">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>
    </ul>

<ul type ="circle">
        <li>Acordar</li>
        <li>Tomar café</li>
        <li>Escovar os dentes</li>

---

### 9.3 - Listas de Definição ou Definition lists.

- São utilizadas para definir um termo, muito usadas quando queremos definir vários termos em sequência. Valorizada pelo algorítimo do google quando pesquisado por definições.Exemplo: 

Código

```
      <dl>
        <dt>Termo</dt>
        <dd>Linguagem de marcação para a criação do conteúdo de um site.</dd>
        <dt>CSS</dt>
        <dd>Linguagem de marcação para criação do design de um site.</dd>
        <dt>Javascript</dt>
        <dd>Linguagem de programação para a criação da interatividade de um site.</dd>
    </dl>

```
Resultado:

<dl>
        <dt>HTML</dt>
        <dd>Linguagem de marcação para a criação do conteúdo de um site.</dd>
        <dt>CSS</dt>
        <dd>Linguagem de marcação para criação do design de um site.</dd>
        <dt>Javascript</dt>
        <dd>Linguagem de programação para a criação da interatividade de um site.</dd>
    </dl>


---

### 9.4 - Junção de listas.

- As listas podem ser aninhadas.


```
    <ol type ="1">
        <li>To-do list</li>
            <ol type="A">
                <li>Acordar</li>
                <li>Tomar café</li>
                <li>Escovar os dentes</li>
            </ol>
        <li>To-do list 2</li>
         <ol type="A">
                <li>Acordar</li>
                <li>Tomar café</li>
             <li>Escovar os dentes</li>
         </ol>
    </ol>
```

Resultado:

<ol type ="1">
    <li>To-do list</li>
        <ol type="A">
             <li>Acordar</li>
            <li>Tomar café</li>
            <li>Escovar os dentes</li>
        </ol>
    <li>To-do list 2</li>
        <ol type="A">
            <li>Acordar</li>
            <li>Tomar café</li>
            <li>Escovar os dentes</li>
        </ol>
</ol>

## 10 - Links e Âncoras. 🔗

Conteúdo de apoio presente no [PDF do capítulo 10](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/10%20-%20Ligações%20em%20toda%20parte.pdf).

### 10.1 - Como fazer um link no HTML?

Para fazer um link em HTML utilizados a tag &lt;a&gt;. Exemplo:

Código:

```
<a href="https://github.com/luisredskill/">repositório público no github</a>
```

Resultado:

[repositório público no github](https://github.com/luisredskill/)

### 10.2 - Como abrir um link em outra janela?

Para abrir um link em uma nova janela utilizamos o parâmetro __*target = "_blank"*__.
Código:

```
<a href="https://github.com/luisredskill/" target = "_blank">repositório público no github</a>
```

### 10.3 - Como indicar que um link é externo ao seu site?

Para indicar a relação que aquele link tem com o seu site utilizamos o parâmetro __*_rel*__.

```
<a href="https://github.com/luisredskill/" rel = "_external">repositório público no github</a>
```
Alguns exemplos de tipos de relação possíveis são:  

- __*external*__ - Indica que o link é para a próxima parte do documento atual.

- __*next*__ - Indica que o link é para a parte anterior do documento atual.

- __*prev*__ - Indica que é um link para o site do autor do artigo atual. 

- __*author*__ - Indica que é um link para outro site que não faz parte do site.

- __*nofollow*__ - Indica que é um link para um site não endossado, como um link pago.

### 10.4 - Como linkar um download?

Para fazer um link de download utilizamos o parâmetro __*download*__ e __*type*__, indicando que o arquivo será um baixável e o tipo do arquivo que será baixado.

```
<a href="arquivos/arquivoParaBaixar" download ="arquivo.pdf" type ="application/pdf">download</a>
```
Alguns outros tipos possíveis de arquivos são:

- application/zip
- text/javascript
- video/mp4
- audio/mpeg
- font/ttf
- image/jpeg

Lista de [MEDIA TYPES](https://www.iana.org/assignments/media-types/media-types.xhtml) possíveis para HTML.

## 11 - Vídeos, áudios e imagens dinâmicas.

Conteúdo de apoio presente no [PDF do capítulo 11](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/PDFs/11%20-%20Imagens%20dinâmicas%2C%20áudios%20e%20vídeos.pdf).

### 11.1 - Como trocar a imagem sozinha baseada no tamanho de tela?

Para adicionar imagens de forma dinâmica no nosso site, devemos utilizar a tag &lt;picture&gt;, dentro dela, para carregar dinâmicamente um conteúdo devemos selecionar a tag __*source:media:type*__. Exemplo:

Menor para o maior:

```
  <picture>
        <source media="(max-width: 750px)" srcset="imagens/foto-300.png" type="image/png">

        <source media="(max-width: 1020px)" srcset="Imagens/foto-700.png" type="image/png">

        <img src="Imagens/foto-1000.png" alt="imagem flexível">
    </picture>
```

Note que para ter o funcionamento correto desse recurso, devemos sempre utilizar uma ordem de imagens do __*maior*__ para o __*menor*__ ou vice-versa. Exemplo reverso:

Maior para o menor:

```
  <picture>
       <picture>
        <source media="(min-width: 1000px)" srcset="imagens/foto-1000.png" type="image/png">

        <source media="(min-width: 750px)" srcset="Imagens/foto-700.png" type="image/png">

        <img src="Imagens/foto-300.png" alt="imagem flexível">
    </picture>
    </picture>
```

### 11.2 - Áudios.

Os áudios são adicionados por meio da tag &lt;audio&gt;, porém ele não é renderizado, apenas carregado na página.

```
<audio src="meu_audio.mp3" ></audio>
```

#### 11.2.1 - Como adicionar controles nos áudios?

Ao mesmo tempo, para que nosso áudio seja renderizado com os controles de áudio devemos utilizar o seguinte 

código:

```
<audio src="meu_audio.mp3" controls></audio>
```

Resultado:

![Screenshot](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/audio_controller1.PNG)

#### 11.2.2 - Otimização de Áudios nos sites.

Os áudios exigem ainda mais otimização na hora de adiconá-los em um site, uma música por exemplo, tem por volta de 5 MB de informação, o que já é muito mais pesado que qualquer imagem.

Em casos extremos, como um podcast, este arquivo pode ser de até 50 MB.

Existe um parâmetro dentro da tag &lt;audio&gt; que indica quando o áudio será carrega e se será carregado.

Dentro da tag audio, utilizados o parâmetro __*preload*__.

```
    <audio preload="">
        <source src="midias/as.mp3" type="audio/mpeg">
    </audio>
```

Dentro do parâmetro preload, podemos receber 3 valores:

| auto                                                                                       | metadata                                                                       | none                                                    |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------- |
| Carrega todo o áudio e só considera o carregamento da página completa após o carregamento. | Carrega apenas as informações essenciais como nome, tipo de arquivo e tamanho. | Não carrega nada, apenas por comandos do usuário ou JS. |

#### 11.2.3 - Áudio em loop.

Podemos deixar o áudio tocando em loop adicionando o parâmetro __*loop*__ dentro da tag &lt;audio&gt;.

#### 11.3.3 - __*IMPORTANTE*__ Adicionando backups.

Para garantir a compatibilidade em todos os navegadores, devemos ter alternativas de carregamento para nossas mídias! Podemos fazer isso utilizando a tag &lt;audio&gt;, porém em vez de indicar o caminho dentro da própria tag pelo parâmetro __*src=""*__, fazemos isso indicando entre as tag. Exemplo:

Código com apenas um arquivo de vídeo em apenas um formato:

```
<audio src="meu_audio.mp3"></audio>
```
Código com arquivos de backup em vários formatos garantindo a compatibilidade:

```
    <audio>
        <source src="meu_audio.mp3" type="audio/mpeg">
        <source src="meu_audio.wav" type="audio/wav">
        <source src="meu_audio.ogv" type="audio/ogg">
    </audio>
```

    Note que ele vai tentar carregar as midias de cima para baixo, ou seja, é interessante que o menor arquivo seja colocado primeiro.

### 11.3 - Vídeos

Os videos são adicionados por meio da tag &lt;video&gt;, porém diferente dos audios ele é sim renderizado.

```
<video src="meu_video.mp4" ></video>
```

Resultado:

![video_nocontrols](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/video_nocontrols_700.PNG)

    Note que o vídeo apenas é mostrado na tela, o usuário não consegue interagir com ele.

Para baixar vídeos gratuitos __*sem direitos autorais*__, podemos utilizar a plataforma da [Pexels](https://www.pexels.com/pt-br/).

Para conversão dos vídeos em formatos mais leves ou para mais formatos, [HandBrake](https://handbrake.fr).

#### 11.3.1 - Adicionando controles aos Vídeos

Para adicionar controles aos vídeos utilizados o parâmetro __*controls*__.

Código:

```
<video src="meu_video.mp4" controls></video>
```

Resultado:

![video_controls](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/video_controls_700.PNG)

#### 11.3.2 - Mudando o tamanho dos vídeos.

As vezes, a largura de um vídeo pode ser muito grande para a página em que ele será inserido. Podemos alterar a largura de um vídeo com o parâmetro __*width=""*__:

Código:

```
<video src="meu_video.mp4" controls width = "500"></video>
```

Resultado:

![video_controls_width_700](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/video_controls_width_700.PNG)

#### 11.3.3 Adicionando Thumbnails

Podemos adicionar uma thumbnail ao vídeo pelo parâmetro __*poster=""*__.

```
 <video src="meu_video.mp4" controls poster="minha_thumb.jpg"></video>
```

Resultado:

![poster_700](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/poster_700.PNG)

#### 11.3.4 __*IMPORTANTE!*__ Adicionando backups

Para garantir a compatibilidade em todos os navegadores, devemos ter alternativas de carregamento para nossas mídias! Podemos fazer isso utilizando a tag &lt;video&gt;, porém em vez de indicar o caminho dentro da própria tag pelo parâmetro __*src=""*__, fazemos isso indicando entre as tags. Exemplo:

Código com apenas um arquivo de vídeo em apenas um formato:

```
<video src="meu_video.mp4"></video>
```
Código com arquivos de backup em vários formatos garantindo a compatibilidade:

```
    <video controls>
        <source src="meu_video.mp4" type="video/mp4">
        <source src="meu_video.webm" type="video/webm">
        <source src="meu_video.ogv" type="video/ogv">
    </video>
```

    Note que ele vai tentar carregar as midias de cima para baixo, ou seja, é interessante que o menor arquivo seja colocado primeiro.

#### 11.3.5 - Incorporando vídeos externos.

As vatagens do __*Youtube*__ são melhores codecs de vídeo, deixando o vídeo mais leve permitindo o usuário reproduzir em velocidades mais baixas de internet.

__*Youtube*__ passo-a-passo:

![barra_yt](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/barra_yt.PNG)

![selecao_yt](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/selecao_yt.PNG)

![incorporado_yt](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/incorporado_yt.PNG)

As vantagens do __*Vimeo*__ são a qualidade do vídeo, porém tem vídeos maiores, se o usuário tiver uma internet pior o vídeo pode travar. Ele também permite uma maior privacidade, sendo a melhor opção quando queremos uma plataforma com vídeos próprios que não podem ser públicos.

__*Vimeo*__ passo-a-passo:

![barra_vimeo](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/barra_vimeo.PNG)

![selecao_vimeo](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/selecao_vimeo.PNG)

![incorporado_vimeo](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/incorporado_vimeo.PNG)




------------------------------------------------------------------------------

# Módulo 2 - CSS

## Comandos CSS

__*background-color*__ - muda a cor de fundo do elemento. Exemplo:

```
<p style="background-color: green;">Esta linha tem o fundo verde utilizando a propriedade background-color</p>
```

Resultado:

![background-color](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/background_color.PNG)

__*color*__ - muda a cor da fonte do texto do elemento selecionado

```
<p style="background-color: green;">Esta linha tem a letra verde utilizando a propriedade color</p>
```

Resultado:

![background-color](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/font_color.PNG)

__*font-size*__ - muda o tamanho do texto do elemento selecionado

```
<p style="background-color: green;">Esta linha tem a letra verde utilizando a propriedade color</p>
```

Resultado:

![background-color](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/font_size.PNG)

__* * *__ - O seletor * é uma configuração global, ou seja, afeta o documento inteiro.



## 12 - Tipos de estilização CSS.

Conteúdo de apoio presente no [PDF do capítulo 12](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/12%20-%20Trabalhando%20com%20estilos.pdf).

### 12.1 - Como adicionar CSS na linha? 

Dentro de uma tag podemos editar o estilo da seguinte forma:

```
<p style="background-color: green;"></p>
```

Utilizamos a tag style.

### 12.2 - Como adicionar CSS dentro do HEAD?

```
    <head>
        <style>
            mark {
                background-color: green;
            }
        </style>
    </head>
```

### 12.3 - Como adicionar CSS por arquivo externo?

```
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

Note que esta tag altera não apenas um elemento, mas todos os elementos da página atual!

Já abordado em aulas anteriores

### 12.4 - Hierarquia de tipos de estilização.

inline &rarr; HTML &rarr; extern

Inline prevalece sobre a alteração interna do HTML que, por sua vez, prevalece sobre a alteração feita no arquivo CSS externo.



## 13 - Cores.

Conteúdo de apoio presente no [PDF do capítulo 13](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/13%20-%20Cores.pdf).


### 13.1 - Como utilizar cores dentro do CSS?

#### 13.1.1 - Representação por nome.

A representação por nome é feita chamando um nome predefinido de cor no CSS, exemplo:
```
    <h2 style="background-color: blue; color: white;">Exemplo de cores</h2>
```

#### 13.1.2 - Representação por código hexadecimal.

##### 13.1.2.1 - Código hexadecimal. 

O código hexadecimal é representada por 6 dígitos cada um deles podento ter uma variedade de 16 carcteres que variam do 0 ao F e normalmente sendo acompanhado pelo símbolo de #. Sendo eles:

0 1 2 3 4 5 6 7 8 9 A B C D E F

Exemplo : #B156AD

     O código hexadecimal é dividido em três partes, cada uma delas representando uma cor primária.

![hexadecimal](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hexadecimal.PNG)

 O vermelho é representado pelos dois primeiros digitos. 

 Vermelho puro: #FF0000  
 ![hexadecimal_red](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hexadecimal_red.PNG)

 O verde pelos dois dígitos centrais. 

 Verde puro: #00FF00  
  ![hexadecimal_green](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hexadecimal_green.PNG)

 E o azul pelos dois últimos digitos. 

 Azul puro: #0000FF  
  ![hexadecimal_blue](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hexadecimal_blue.PNG)

##### 13.1.2.2 - Como funciona o código hexadecimal?

Cada campo do código de cor hexadecimal define a intensidade da sua cor respectivamente, sendo a mais fraca ou ausência de cor 00, e a mais forte FF.

Como o código é feito na base 16, cada campo representativo de cor possui 16x16 combinações possíveis, na base decimal seria convertido do 0 ao 255. Exemplo:

#FFFF00 representa respectivamente, 255 de vermelho, 255 de verde e 0 de azul resultando na cor amarela:  

![cor](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/cor.PNG)

#### 13.1.3 - Representação por RGB.

representa em código RGB, respectivamente vermelho, verde e Azul. A representação é dada do 0 ao 255. Exemplo:

255,255,255 - representa a cor branca.
255,0,0 - representa o vermelho puro.
0,255,0 - representa o verde puro.
0,0,255 - representa o azul puro.

#### - 13.1.4 - Transparência no CSS.

Tanto os modos RGB e Hexadecimal, possuem transparência acessível pelo editor VScode. Para acessar as configurações basta passar o mouse por cima da cor que deseja adicionar a transparência e, na janela agora aberta, mover o cursor ao lado da barra de cores.

![opcoes_cor](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/opcoes_cor.PNG)

### 13.2 Harmonia de cores e sua importância.

#### 13.2.1 - O que representa cada cor?

Cada cor pode ser associada a um tipo de sentimento ou estado, deve-se levar em consideração o que cada cor representa antes de usá-la em um projeto.

![associacoes](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/associacoes.png)

#### 13.2.2 - O que é círculo cromático?

O circulo cromático é uma representação das cores em formato de círculo.

![circulo_cromatico](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/circulo_cromatico.PNG)

##### 13.2.2.1 - Cores primárias.

Dentre essas classificações temos as cores primárias: Azul,Vermelho e Amarelo.

![primarias](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/primarias.PNG)

Essas cores são conhecidas por serem um pouco difíceis de se trabalhar por serem cores primárias e muito "duras".

##### 13.2.2.2 - Cores secundárias.

Dentre essas classificações temos as cores secundárias: Verde,Violeta e Laranja.

![secundarias](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/secundarias.PNG)

Essas cores também são conhecidas por serem um pouco difíceis de se trabalhar por serem cores muito "duras". 

##### 13.2.2.3 - Cores terciárias.

São o resultado de todas as cores vindas da mistura de uma cor primária e secundária

Essas cores geralmente são largamente utilizadas em projetos. Toda cor terciária fica entre uma cor primária e uma secundária, sendo nomeada com o nome da cor primária e, logo depois, a cor secundária. Exemplos:

Amarelo-esverdeado
Azul-esverdeado
Azul-arroxeado
Vermelho-arroxeado
Vermelho-alaranjado
Amarelo-alaranjado

![terciarias2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/terciarias2.webp)

##### 13.2.2.4 - Temperatura de cor.

As cores podem lembrar temperaturas específicas e passar a sensação de algo frio ou quente baseado apenas na tonalidade das cores.

![hotcold](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hotcold.png)


##### 13.2.2.5 - Complementares.

As cores complementares são as cores que possuem mais contraste entre si, geralmente elas trabalham bem juntas, mas deve-se tomar cuidado para que os tons não parecem muito fortes deixando a visualização desagradável. Também é um dos modelos de escolhas de cor mais comuns e geralmente utilizados.

![complementar](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/complementar1.png)

##### 13.2.2.6 - Análogas.

As cores análogas são o oposto das cores complementares, mas também trabalham bem juntas. Elas são as cores que possuem um contraste muito baixo entre si e tem uma harmonia natural.

![analogas](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/analogas.png)

##### 13.2.2.7 - Cores análogas e uma complementar.

Esta é uma tecnica muito utilizado no design, consiste em pegar 3 cores análogas e uma complementar gerando assim uma paleta de cores harmônica.

![analogascomplementar](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/analogascomplementar.jpeg)


##### 13.2.2.8 - Cores triádicas.

Técnica bastante utilizada e que garante uma grande riqueza de cores, onde escolhemos três pontos equidistantes no círculo cromático.
Esse esquema gera sempre um triângulo equilátero e cria uma opção que sempre possui um ótimo contraste entre as cores.:

![analogasrelacionada](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/triadicas.PNG)

##### 13.2.2.9 - Monocromia

Neste método, trabalhamos apenas com um tipo de cor em tônalidades diferentes, alterando apenas a saturação e o brilho. Exemplo:

![monocromia](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/monocromia.PNG)



### 13.3 - O que é uma paleta de cores?

#### 13.3.1 - Criando uma paleta de cores!

A paleta de cores de um projeto deve possuir de 3 a 5 cores no máximo e, geralmente, é escolhida através de um dos métodos relacionados ao círculo cromático.

Para criação de uma paleta podemos utilizar o serviço da [adobe Color](https://color.adobe.com/pt/create/color-wheel).

Este site permite a visualização das cores análogas, complementares, etc.

Exemplo de cores análogas:

![adobe color](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/adobecolor.PNG)

Exemplo de cores complementares:

![adobe color2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/adobecolor2.PNG)

#### 13.3.2 - Tem uma logo? Aqui está como ter acesso a sua paleta!

Usando a mesma ferramenta podemos utilizar a ferramenta __*Extrair tema*__, ela gera uma paleta de cores baseado na imagem inserida.

![extrairtema](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/extrairtema.PNG)

Ainda podemos formar um gradiente com a ferramenta __*Extrair Gradiente*__ baseado na imagem inserida:

![extrairgradiente](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/extrairgradiente.PNG)

#### 13.3.3 - Paletas prontas para serem usadas!

Na aba explorar do [adobe Color](https://color.adobe.com/pt/create/color-wheel), podemos achar uma paleta pronta de cores para ser utilizada.

![explorar](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/explorar.PNG)

Ainda dentro do explorar, podemos observar uma opção para mostrar as paletas mais usadas:

![menuexplorar](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/menuexplorar.PNG)

Resultado:

![paletasmaisusadas](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/paletasmaisusadas.PNG)

### 13.4 - Salvando cores no navegador.

Para evitar trabalho desnecessário utilizamos uma extensão chamada [CollorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=pt-BR) no chrome.

### 13.5 - Como criar um degradê no CSS? 

#### 13.5.1 - Degradê linear.

Para criar um degradê no css utilizamos o __*background-image*__. Este que receberá um função de nome __*linear-gradient*__.

Esta função recebe 3 argumentos, o primeiro é a direção do degradê podendo ser representado por direções ou graus, os outros dois são as cores.

Código:

```
body{
        background-image: linear-gradient(to right, white, blue)
           
    }
div{
        background-image: linear-gradient(90deg,#0000ff,#ffffff)
}
```
Resultado:

![gradiente](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/gradiente.PNG)

Podemos adicionar mais cores a essa função:

![gradiente2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/gradiente2.PNG)

Podemos indicar qual a porcentagem de tela que cada cor terá:

```
background-image: linear-gradient(90deg, #710CE8 33%, #0113DB 50%, #0C92E8);
````

Resultado:

![gradiente4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/gradiente4.PNG)

Note que diferente do senso comum, a porcentagem nesse caso não indica a quantidade de tela a ser tomada pela cor, mas sim o espaço restante que ainda não foi tomado por cores anteriores. Isso quer dizer que se a primeira cor tomar 70% do espaço, mesmo que a próxima ocupe 50%, o valor real ocupado do espaço horizontal será de apenas 15%.

Código:

```
background-image: linear-gradient(90deg, #710CE8 70%, #0113DB , #0C92E8 );
```

Resultado:

![gradiente5](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/gradiente5.PNG)





Note que é necessário usar o __*background-attachment: fixed;*__ nos casos em que o degradê não é para a direita ou para a esquerda e também a configuração global para deixar o body com 100% da altura da tela.

Respectivamente:

````
*{
    height: 100%;
    background-attachment:fixed;
}
````

#### 13.5.2 - Degradê radial.

Para criar um degradê radial no css utilizamos Para criar um degradê no css utilizamos o __*background-image*__. Este que receberá um função de nome __*radial-gradient*__.

Código:

```
background-image: radial-gradient(circle, #710CE8, #370CF2, #0113DB, #0C5CF2, #0C92E8);
```
Resultado:

![gradiente3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/gradiente3.PNG)




## 14 - Fontes

### 14.1 - História da tipografia.

História da tipografia, explicação sobre os estudos da tipografia presentes no conteúdo do pdf.

Conteúdo de apoio presente no [PDF do capítulo 14](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/14%20-%20Fontes.pdf).

### 14.2 - Como alterar uma fonte no CSS?

A fonte padrão dos navegadores é a __*Times New Roman*__.

Para alterar a fonte de um texto devemos selecionar o elemento no qual ele está inserido e utilizar o seguinte código:

```
seletor{
    font-family: 'fontName';
}
```

Respectivamente, fonte com alteração e sem.

![couriernew](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/couriernew.PNG)

![timesnewroman](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/timesnewroman.PNG)

- __*IMPORTANTE*__ - Esse comando utiliza a fonte já presente no dispositivo, isso quer dizer que se o dispositivo atual não tiver essa fonte, ele vai voltar à padrão. Para evitar essa situação podemos indicar fontes secundárias caso a primeira opção não esteja disponível:

Exemplo:

```
body{
  font-family: Arial, Verdana, sans-serif;
}
```

Respectivamente, resultado esperado, resultado secundário caso a primeira fonte não esteja disponivel no dispositivo atual e última opção.

![helvetica](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/helvetica.PNG)
![verdana](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/Verdana.PNG)
![franklin](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/franklin.PNG)

#### 14.3 - Como garantir que a minha fonte poderá ser usada?

Visto o problema exposto no tópico anterior, podemos evitar esse problema usando combinações de fontes que existem na maioria dos dispositivos por padrão. Para acha-las podemos utilizar o site W3School no tópico [CSS Web Safe Fonts](https://www.w3schools.com/cssref/css_websafe_fonts.asp).

Ainda temos a opção de importar as fonts do google fonts.

### 14.4 - Como alterar o tamanho da minha fonte?

Para alterar o tamanho das fonts, selecionamos o elemento a ser alterado e utiliza-mos o comando __*font-size*__:

```
seletor{
    font-size: ;
}
```

- __*IMPORTANTE*__ - Este comando pode receber medidas absolutas ou relativas.  


| Absolutas | Equivalente | Relativas | Equivalentes |
| --------- | ----------- | --------- | ------------ |
| cm        | centímetro  | em        | em           |
| mm        | milímetro   | ex        | ex           |
| in        | polegada    | rem       | rem          |
| px        | pixel       | vw        | viewWidth    |
| pt        | ponto       | vh        | viewHeight   |


No geral as medidas __*absolutas*__ não são recomendáveis, principalmente pt pois não se adapta bem ao desenvolvimento web.

- __*em*__ - medida relativa ao tamanho da fonte, utiliza a altura da letra M maiúcula como base.

- __*ex*__ - medida relativa ao tamanho da fonte, utiliza a altura da letra x minúscula como base.

- __*rem*__ - medida relativa ao tamanho da fonte, utiliza a o tamanho da fonte do arquivo HTML como base.

- __*vw*__ - medida relativa à largura da tela, utiliza a tela visível, ou seja todos os pixels visíveis atualmente na janela aberta.

- __*vh*__ - medida relativa à altura da tela, utiliza a tela visível, ou seja todos os pixels visíveis atualmente na janela aberta.

### 14.5 - Como adicionar negrito, itálico e sublinhado?

#### 14.5.1 - Negrito.

Para alterar o peso de uma fonte utilizamos o comando:

```
seletor{
    font-weight: ;
}
```

Este comando pode receber uma variedade de argumentos, assim podemos ter:

| Numérico | Semântico |
| -------- | --------- |
| 100      | lighter   |
| 200      |           |
| 300      |           |
| 400      | normal    |
| 500      |           |
| 600      |           |
| 700      | bold      |
| 800      |           |
| 900      | bolder    |

__*IMPORTANTE*__ - note que nem todas as fontes possuem esse espectro de peso! Algumas não possuem nem mesmo o negrito, apenas a fonte NORMAL ou 400.

#### 14.5.2 - Itálico.

Para adicionarmos itálico a um texto utilizamos o comando:

```
seletor{
    font-style: italic;
}
```
__*IMPORTANTE*__ - note que nem todas as fontes possuem o itálico!

#### 14.5.3 - Sublinhado.

Para adicionarmos sublinhado a um texto utilizamos o comando:

```
seletor{
   text-decoration: underline;
}
```

Retirando sublinhado:

```
seletor{
   text-decoration: none;
}
```


__*IMPORTANTE*__ - note que nem todas as fontes possuem o sublinhado!

### 14.6 - Fonte, tamanho, peso e estilo em uma única linha (Font Shorthand).

O CSS possibilita que declaremos todos esses aspectos em uma única linha. Isso é feito da seguinte forma:

font-style &rarr; font-weight &rarr; font-size &rarr; font-family

O que antes seria um bloco de código:

```
seletor{
  font-family: 'Work Sans';
  font-weight: bolder;
  font-style: italic;
  font-size: 16px;
}
```
É condensado em apenas uma linha:
```
seletor{
  font: italic bolder 3em 'Work Sans';
}

```

O resultado é o mesmo.

### 14.6 - Como importar uma fonte?

#### 14.6.1 - Como importar uma fonte externa online?


Para importar uma fonte externa devemos importá-la usando a declaração __*@import*__ dentro do CSS antes de qualquer outra declaração. Exemplo:
````
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');
````

Podemos utilizar o [Google Fonts](https://fonts.google.com) para achar fontes para nossos projetos.

Podemos importar uma fonte do google fonts diretamente para o CSS. Depois de selecionar a fonte desejada, clicamos no __*Select this style*__.

![select](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/select.PNG)

Depois clicamos neste ícone:

![select2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/select2.PNG)

Finalmente, selecionando a opção import.

![select3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/select3.PNG)


### 14.6.2 - Como importar uma fonte baixada? Servidor.

Primeiramente temos que baixar o arquivo de fonte, normalmente os formatos de fonte são __*.ttf*__ ou __*.otf*__, as diferenças entre eles são majoritariamente de compatibilidade com certos navegadores.

Para __*baixar*__ arquivos é recomendado o uso do [Google Fonts](https://fonts.google.com) para fontes gratuitas ou, para mais opções de fontes, é recomendado o [dafont](https://www.dafont.com/pt/).

Depois de baixados e extraidos:

Para importar uma fonte local utilizamos a declaração __*@font-face*__ no começo do arquivo CSS. Ela trabalha de forma a criar uma fonte nova a partir de um arquivo de fonte: 

````
@font-face{

}
````

Dentro do @font-face, declaramos o nome do arquivo que será importado:  
__*IMPORTANTE*__ - o nome declarado deve conter o nome exato, com espaços e símbolos.

````
@font-face{
src: url('fonts/love story.ttf')
}
````

Na mesma linha, declaramos o formato que é um parâmetro de compatibilidade não-obrigatório, porém recomendado:

````
@font-face{
src: url('love story.ttf') format ('truetype')
}
````
Note que o formato não é um padrão, mas __*NORMALMENTE*__ a melhor seleção de compatibilidade é:

| tipo              | formato  |
| ----------------- | -------- |
| ttf               | truetype |
| otf               | opentype |
| embedded-opentype |          |
| truetype-att      |          |
| svg               |          |

Finalmente, criamos o nome da fonte que não necessáriamente precisa ser o mesmo nome. Exemplo:

````
@font-face{
font-family: 'Anger';
src: url('fonts/love story.ttf') format ('truetype')
}
````
Assim, chamaremos essa fonte dentro de nosso código CSS de __*Anger*__, não de __*love story*__.

````
body{
font-family: 'Anger';
}
````

Resultado:

![Anger](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/Anger.PNG)

### 14.7 - Como identificar uma fonte de qualquer site?

#### 14.7.1 - Indentificando fontes textuais

As fontes de um site estão presentes no seu CSS e podem ser recuperadas por programas terceiros.

Para isso podemos utilizar extensões de navegadores especializadas e que podem recuperar essas informações.
  
No google chrome, [Fonts Ninja](https://chrome.google.com/webstore/detail/fonts-ninja/eljapbgkmlngdpckoiiibecpemleclhh).

![fontsninja](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/fontsninja.PNG)

#### 14.7.2 - Indentificando fontes de imagens.

[Whatfontis](https://www.whatfontis.com)   
[Font Squirrel](https://www.fontsquirrel.com/matcherator)   
[MyFonts](https://www.myfonts.com/WhatTheFont/)  

### 14.8 - Como alinhar texto?

O padrão de alinhamento de texto é alinhamento à __*esquerda*__.

A declaração utilizada para mudar o alinhamento de texto é o __*text-align*__.

Código:

````
seletor{
    text-align: ;
}
````

Existem 4 argumentos principais para a declaração:

1 - left, alinhamento à __*esquerda*__ padrão para todos os textos.


````
seletor{
    text-align: left ;
}
````

![left](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/left.PNG)


2 - right, alinhamento à __*direita*__.  <br>


````
seletor{
    text-align: right ;
}
````

![right](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/right.PNG)


3 - center, alinhamento __*centralizado*__.  <br>


````
seletor{
    text-align: center ;
}
````

![center](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/center.PNG)


4 - justify, alinhamento __*justificado*__.  <br>


````
seletor{
    text-align: justify ;
}
````

![justify](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/justify.PNG)

### 14.9 - Como criar um recuo de parágrafo?

Para fazer um recuo em todo parágrafo utilizamos a declaração __*text-indent*__.

Código:

````
seletor{
    text-indent: 20px;
}
````

Resultado:

![indent](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/indent.PNG))


__*IMPORTANTE*__ - Note que todos os elementos inclusos terão o recuo!

### 14.10 - Como alterar a altura da linha?

Para alterar a altura da linha utilizamos a declaração __*line-height*__.

Código:

````
seletor{
    line-height: 2em;
}
````

Resultado:

![espacoentrelinhas](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/espacoentrelinhas.PNG)

### 14.11 - Alterações de exibição de fonte em maiúscula e minúscula.

Há como alterar a visualização de um texto via CSS através dos comandos _*text-transform*_ e _*font-variant*_.

Exemplos:

- small-caps, deixa a letra inteira com a fortação de maiúscula porém os tamanhos não são alterados.

````
h1{
    font-variant: small-caps;
}
````
texto digitado _*"Cordel Moderno"*_:

![small-caps](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/small-caps.PNG)

- uppercase, transforma todas as letras em maiúsculas.

````
h1{
    text-transform: uppercase;
}
````
texto digitado _*"cordel moderno"*_:

![small-caps2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/small-caps2.PNG)


- lowercase, transforma todas as letras em minúsculas.

````
h1{
    text-transform: lowercase;
}
````

texto digitado _*"CORDEL MODERNO"*_:

![small-caps3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/small-caps3.PNG)

- capitalize, transforma a primeira letra de cada palavra em maiúscula:

````
h1{
    text-transform:capitalize;
}
````

texto digitado _*"cordel moderno"*_:

![small-caps4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/small-caps4.PNG)


## 15 - Seletores CSS

Conteúdo de apoio presente no [PDF do capítulo 15](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/15%20-Seletores%20personalizados.pdf).

### 15.1 - Hierarquia Class x ID.

ID &rarr; Class

As alterações no ID prevalecem sobre as alterações por class.

### 15.2 - Como selecionar um elemento HTML por TAG?

Para selecionar um elemento HTML que sofrerá alterações no CSS, utilizamos os seletores CSS. Os seletores CSS utilizam as TAGS HTML para selecionar todos os elementos que serão alterados.

Dentro do arquivo CSS, basta escrever o nome da TAG seguida por {}, todas as declarações dentro das {} serão aplicadas aos elementos selecionados.

Exemplo:

HTML

````
    <h1>Selecionando com CSS</h1>
    <h1>Aprendendo a Selecionar</h1>
````

CSS 

````
h1{
    color: red;
}
````

Resultado:

![seletores](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/seletores.PNG)

Note, ambos os títulos foram alterados.

### 15.3 - Como selecionar um elemento por ID? 

O primeiro passo para selecionar um elemento por ID é garantir que o elemento HTML possui este ID, ou seja, colocaremos o ID no elemento desejado.

Exemplo:

````
    <h1 id = "principal">Selecionando com CSS</h1>
    <h1>Aprendendo a Selecionar</h1>
````

Depois, no CSS, selecionaremos este elemento HTML pelo ID. Dentro do CSS o ID é representado pelo sinal de #. Isso quer dizer que estamos selecionando o elemento &lt;H1&gt; de ID principal.

````
h1#principal{
    color: red;
}
````

Resultado:

![seletores2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/seletores2.PNG)

### 15.4 - Como selecionar um elemento por classe?

A representação de classe no CSS é feito por ".".

No CSS, a seleção por classes serve para alterar inúmeros elementos ao mesmo tempo, enquanto um elemento pode ter apenas um ID, vários elementos podem ter a mesma classe.

Primeiro adicionamos uma classe aos elementos HTML:

````
<h1 class = "nomeClasse">Selecionando uma classe</h1>
<h2 class = "nomeClasse">Subtítulo 1</h1>
<h2 class = "nomeClasse">Subtítulo 2</h1>
````

Depois selecionamos esta classe, declarando suas alterações:

````
.nomeClasse{
color: blue;
}
````

Resultado:

![class](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/class.PNG)

__*IMPORTANTE*__ - Várias classes podem ser adicionadas ao mesmo elemento separadas por " ".

HTML.

````
<h1 class = "classeUm classeDois">Adicionando várias classes em um elemento</h1>

````

CSS

````
.classeUm{
color: white;
}
.classeDois{
    background-color: blueviolet;
}
````
Resultado:

![class2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/class2.PNG)

### 15.5 - Como selecionar elementos filho?

Para selecionar elementos filho usamos o sinal de &gt;.

````
  div > p{
            display: none;
        }
````

Neste caso estamos selecionando todos os parágrafos que são __*diretamente*__ filhos de divs. Note que a seguinte linha não seria afetada:

````
    <div>
        <article>
            <p>Parágrafo que não é afetado pelo div, pois não é filho direto de uma div</p>
        </article>
    </div>

````

#### 15.5.1 - Como selecionar todos os elementos dentro de uma tag.

Como foi apresentado no exemplo acima, se um elemento não for filho, não será afetado. Porém, para resolver isso podemos utilizar o seguinte código:

````
  div p{
            display: none;
        }
````

Assim, todos os parágrafos dentro de divs serão afetados.



### 15.6 - O que é uma pseudo-classe? Interatividade CSS!

As pseudo-classes são estados de elementos, ou seja, quando selecionamos uma pseudo-classe, estamos dizendo que aquelas declarações só entrarão em efeito quando o estado específicado do elemento selecionado estiver sendo executado.

Selecionamos o elemento juntamento com a pseudo-classe desejada:

````
div:hover{

}
````

#### 15.6.1 - Como funciona uma pseudo-classe? Hover.
````
div{
    display: inline-block;
    background-color: lightgray;
    height: 200px;
    width: 200px;
}
div:hover{
    background-color: yellow;
}
````

Neste caso estamos selecionando todas as divs, logo depois selecionamos a pseudo-classe (estado atual das divs) que terá a função de alterar a cor do função apenas quando o mouse estiver em cima da div.

Sem o mouse:

![hover](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hover.PNG)

Com o mouse em cima da div 01:

![hover2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/hover2.PNG)

### 15.6.2 - Procurando por uma pseudo-classe?

- __*visited*__ - altera um link que já foi visitado anteriormente

- __*active*__ - altera um elemento que está ativo.

- __*:nth-child(4n)*__ - seleciona um elemento filho a partir da sua posição intercalando a cada Xn elementos. Neste caso 4,8,12,16,etc.

### 15.7 - O que são pseudo-elementos?

Pseudo-elementos são elementos novos adicionados por CSS, normalmente utilizamos ele quando vamos repetir uma formatação em vários elementos. Eles são selecionados pelo símbolo de __*::*__.

````
a::before{
            content: '»';
        }
````
Neste exemplo, seria adicionado um pseudo elemento » antes de todos os links, exemplo:

![link](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/link.PNG)

Para adicionar emojis o correto é trocar U+1F600 por \1F600. 

````
a::before{
            content: '\1F600';
        }
````

__*IMPORTANTE*__ - O símbolo é uma contra barra!

Para adicionar um espaço entre o seguinte código é utilizado: \00A0

````
seletor::after{
    content: '\00A0\1F517'
}
````


### 15.8 - Exemplos práticos

Quando vemos as possibilidades de código a nossa frente é difícil pensar em como usá-los, aqui estão alguns exemplos simples, mas que podem abrir a sua mente para as possibilidades:

#### 15.8.1 - Parágrafo escondido?



````
    <style>
        div:hover{                             /* 01 */
            color: red;                        /* 02 */
        }

        div > p{                               /* 03 */
            display: none;                     /* 04 */
        }

        div:hover > p{                         /* 05 */
            display: block;                    /* 06 */
            color: white;                      /* 07 */
            background-color: red;             /* 08 */
        }
    </style>



    <h1>Exemplo de hover</h1>                  /* 09 */
    <p>Passe o mouse sobre o texto abaixo</p>  /* 10 */
    <div>Passe o mouse aqui                    /* 11 */
        <p>Texto escondido</p>                 /* 12 */
    </div>

````

O código acima cria um HTML com um título(09), uma parágrafo abaixo(10) e uma div(11) contendo um parágrafo(12).

Acima do HTML, no CSS temos 3 seletores, o primeiro seleciona os elementos div juntamento com a pseudo-classe hover(01), o segundo seleciona todos os parágrafos contidos em divs(03), o terceiro seleciona todos os elementos div enquanto o mouse estiver sobre eles, porém altera apenas os parágrafos dentro deles(05).

Sendo assim quando passamos o mouse sobre a div(11), acionamos o terceiro seletor que altera a visualização do parágrafo interno desta div para "block", mostrando o parágrafo ao passarmos o mouse e alterando a cor da letra(07) e a cor do fundo(08). Gerando o seguinte resultado:

Sem o mouse em cima da div(11).

![exemplohover](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/exemplohover.PNG)

Com o mouse em cima da div(11) ativando o seletor(05).

![exemplohover2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/exemplohover2.PNG)



## 16 - O que é modelo de caixas? Box-model.

Já abordado em aulas anteriores

Conteúdo de apoio presente no [PDF do capítulo 16](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/16%20-%20Modelo%20de%20Caixas.pdf).

O modelo de caixas se utiliza de aninhamento, ou seja, existe uma hierarquia de elementos dentro dos arquivos que utilizam o __*modelo de caixas*__. Ambas as linguagens CSS e HTML5 utilizam este sistema.

Para facilitar o entendimento será utilizado apenas HTML para a explicação e todas as cores de fundo serão alteradas para facilitar a visualização.

Todo elemento aparente em um site é contido em uma caixa, ou seja, quando criamos um elemento HTML, por exemplo um parágrafo, estamos criando uma caixa e inserindo texto dentro dela. Esta caixa estaria delimitada pela tag &lt;p&gt;.

````
<p>Este elemento está contido em uma caixa</p>
````

![caixa](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/caixa.PNG)

Note que esta caixa ocupa toda a linha, possui tanto uma altura quanto uma largura.

Alterando a sua largura e altura:

![caixa2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/caixa2.PNG)

### 16.1 - Como transformar um elemento box-level em inline-level e vice-versa?

````
display: block;
display: inline;
````

### 16.2 - O que é border?

Toda caixa possui uma delimitação de seu espaço interno, essa delimitação é chamada de border. Podemos observar em preto a borda:

![borda](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/borda.PNG)

#### 16.2.1 Adicionando uma borda.

A propriedade border é padrão de todas as divs, porém ela não é visível, para permitir que ela esteja visível temos que configurar sua cor, largura e estilo.

Código:

````
seletor{
    border-color: rgb(0, 0, 0);
    border-width: 5px;
    border-style: solid;
}
````

Resultado:

![borda2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/borda2.PNG)

- border-style - define o estilo da borda podendo ser:

dashed: traços 
dotted: pontinhada
double: borda dupla
groove: 3D

#### 16.2.2 Arredondando uma borda.

- border-radius - define o raio da borda

Código:

````
seletor{
    border-radius: 10px;
}
````

Resultado:

![borda3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/borda3.PNG)

- __*ShortHand*__ - define cada borda individualmente. Em ordem: superior esquerdo, superior direito, inferior direito, inferior esquerdo.

Código:

````
seletor{
    border-radius: 10px 20px 40px 80px;
}
````

Resultado:

![borda5](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/borda5.PNG)

Da mesma forma que o margin, podemos __*alterar em pares*__. Sendo eles: superior esquerdo/inferior direito, superior direito/inferior esquerdo.

Código:

````
seletor{
    border-radius: 10px 40px;
}
````

Resultado:

![borda7](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/borda7.PNG)





#### 16.2.3 - Border ShortHand.

O shorthand é feito na seguinte ordem: border-width, border-style, border-color.

Código:

````
seletor{ 
    border: 10px solid white;
}
````

![borda4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/borda4.PNG)

Resultado:

#### 16.2.4 - Bodas decoradas



### 16.3 - O que é padding?

Padding é o espaço entre o conteúdo de uma caixa e a sua borda, isso quer dizer que quando adicionamos um padding a um elemento, seu conteúdo se afastará da borda. Exemplo:

![padding](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/padding.PNG)

- padding-top - define o padding superior
- padding-lef - define o padding esquerdo
- padding- bottom - define o padding inferior
- padding-right - define o padding direito

#### 16.3.1 - padding ShortHad.

Define todos os paddings para a medida:

````
seletor{ 
    padding: 10px;
}
````
![padding1](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/padding1.PNG)

Define as medidas na seguinte ordem: superior, direita, inferior, esquerda.

````
span{
            border: 2px solid black;
            font-size: 100px;
            padding: 10px 20px 30px 40px;
        }
````

![padding2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/padding2.PNG)

Define as medidas em duplas: Superior e Inferior/ Esquerda e direita

````
span{
            border: 2px solid black;
            font-size: 100px;
            padding: 10px 20px;
        }
````

![padding3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/padding3.PNG)

### 16.4 - O que é margin?

Margin é o espaço entre a borda de uma caixa e seu elemento mais próximo, isso quer dizer que quando adicionamos um margin a um elemento, esse elemento se afastará dos elementos mais próximos a ele.

![margin](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/margin.PNG)

- margin-top - define o margin superior
- margin-lef - define o margin esquerdo
- margin-bottom - define o margin inferior
- margin-right - define o margin direito

#### 16.4.1 - margin ShortHad.

Define todos as margins para a medida:

````
seletor{ 
    margin: 10px;
}
````
![margin1](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/margin1.PNG)

Define as medidas na seguinte ordem: superior, direita, inferior, esquerda.

````
span{
            border: 2px solid black;
            font-size: 100px;
            margin: 10px 20px 30px 40px;
        }
````

![margin2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/margin2.PNG)

Define as medidas em duplas: Superior e Inferior/ Esquerda e direita

````
span{
            border: 2px solid black;
            font-size: 100px;
            margin: 10px 20px;
        }
````

![margin3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/margin3.PNG)

#### 16.4.2 - Margin auto.

Centraliza horizontalmente elementos box-level que ocupam a linha inteira independente da largura de tela.
````
span{
            margin: auto;
        }
````

### 16.5 - Sombra no CSS(shadow).

A sombra no CSS pode ser feita em caixas pelo declaração __*shadow-box*__. Esse comando é um ShortHand, sendo assim ele recebe mais de um argumento. Sendo eles: deslocamento horizontal, deslocamento vertical, espalhamento e cor.

Código:

````
seletor{
    box-shadow: 10px 50px 0px black;
}
````

Resultado:

![shadowbox](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/shadowbox.PNG)

Outro exemplo:

````
seletor{
   box-shadow: 50px 10px 30px black;
}
````

![shadowbox2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/shadowbox2.PNG)

Exemplo usável:

````
seletor{
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.486);
}
````

![shadowbox3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/shadowbox3.PNG)

Note que a sombra, nesse caso é parcialmente transparente para dar um efeito mais agradável visualmente. Note também que ela tem mais de 50% de transparencia gerando melhores resultados.

## 17 - Criando um site

Conteúdo de apoio presente no [PDF do capítulo 17](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/17%20-%20Primeiro%20mini-projeto.pdf).

### 17.1 - Criando o design no seu site

Foi recomendado durante o curso a ferramenta [mockflow](https://www.mockflow.com).

Essa ferramenta é boa para estrurar a primeira versão do site, ainda sem cores. Uma versão extremamente simples.

![mock](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/mock.PNG)

O segundo passo é criar uma versão mais fiel do site, com cores e muito próxima da versão real, para isso é recomendado o uso do [figma](https://www.figma.com).

![figma](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/figma.PNG)

### 17.2 - Organização do projeto.

#### 17.2.1 - Para que servem as variáveis CSS.

As variáveis no CSS facilitam o uso contínuo de atributos usados frequentemente no projeto, por exemplo: fontes e cores. 

Elas são criadas normalmente dentro do seletor __*:root*__.

Exemplo:

````
:root{

}
````

Dentro deste seletor, declaramos as variáveis que poderão ser chamadas em todo o arquivo CSS. Toda variável CSS começa com "--".

````
:root{
    --cor0: #c5ebd6;
    --cor1: #83e1ad;
    --cor2: #3ddc84;
    --cor3: #2fa866;
    --cor4: #1a5c37;
    --cor5: #063d1e;

    --fonte-padrao: Arial, Verdana, Helvetica, sans-serif;
    --fonte-destaque: 'Bebas Neue', 'cursive';
    --fonte-android: 'Android', 'cursive';
}
````

 Assim que uma variável for __*mudada*__, todo o arquivo CSS é mudado.

````
body{
    background-color: var(--cor0);
    font-family: var(--fonte-padrao);
}
````

Se, por exemplo, a fonte padrão for alterada, todos os elementos que receberam a variável --fonte-padrao serrão mudados, economizando tempo.


### 17.3 - Configurações globais CSS.

Para alterar todo o documento de uma vez utiliza-se o seletor __* * *__.

````
*{

}
````

Normalmente, as configurações mais comuns são:

````
*{
    margin: 0px;
    padding: 0px;
}
````

Essas configurações, resetam as pré-configurações dos navegadores e impedem que a criação de espaços indesejados.


### 17.4 - Responsividade CSS.

#### 17.4.1 - Como facilitar o trabalho de responsividade?

O [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=pt-br) é uma extensão do chrome que facilita a visualização da responsividade.

![windowresizer](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/windowresizer.PNG)

#### 17.4.2 - Como automatizar a centralização de um elemento?

Para centralizar um elemento utilizamos a função automática da propriedade CSS __*margin*__.

Sem margin auto:

````
seletor{
            width: 300px;
            height: 300px;
            background-color: gray;
        }
````

![marginauto](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/marginauto.PNG)

Com margin auto:

````
seletor{
            width: 300px;
            height: 300px;
            background-color: gray;
            margin: auto;
        }
````

![marginauto2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/marginauto2.PNG)

__*IMPORTANTE*__ - Como a div por padrão é um elemento blocklevel, ela ocupa a linha inteira, sendo assim o margin auto espaça as margens de forma igual de ambos os lados baseado na largura atual da tela, o que não ocorre com um elemento inlinelevel por não possuir margem.

### 17.4.3 - Container responsivo a largura de tela?

Para deixar qualquer container responsivo a maneira mais fácil é utilizando o __*max-width*__ e __*min-width*__.

Declaramos os valores máximos e minimos para aquele container.

Exemplo:

````
seletor{
    min-width: 300px;
    max-width: 1000px;  
}
````

Quando a largura de tela aumento acima de 1000px não há alteração, variando apenas entre 1000px e 300px.


#### 17.4.3 - Como deixar imagens responsivas?

O uso mais comum para se deixar imagens responsivas é atrelar a sua largura a largura do elemento pai. 

Exemplo:

CSS:

````
div > img{
    width: 100%;
}
````

Assim, quando alteramos a largura da __*div*__ alteramos a largura da imagem.

![giphy](https://media.giphy.com/media/0p70j2PKjoTjMDkzQe/giphy.gif)

### 17.4.4 - Como deixar um video responsivo? (aspect ratio).

#### 17.4.4.1 - Video externo

Um dos jeitos mais comuns que temos no CSS para tornar um video responsivo é criar uma div que comportará nosso vídeo.

Esta div, por sua vez, fará o papel de se manter proporcional ao aspect ratio desejado(16:9).

Assim sendo, a div já possui por padrão a mesma largura do elemento pai, restando para nós ligarmos esta largura a altura da div. Faremos isto por um padding:

````
seletor{
            background-color: green;
            padding-bottom: 56.25%;
}
````

Note que o número utilizado é exatamente 9/16 = 0.5625.

- 16/9 - 56.25%
- 18/9 - 50%
- 21/9 - 42.85%

Como resultado do código temos uma div de aspect ratio 16:9 responsiva a largura do elemento pai:

![aspect](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/aspect.PNG)

Agora só falta ligar o aspect ratio dessa div ao nosso vídeo integrado, faremos isso com o position:

````
div{
    padding-bottom: 56.25%; 
    position: relative;
}

video{
    position: absolute;

    top: 5%; // margem de 5% do valor total da altura
    left: 5%; // margem de 5% do valor total da largura

    width: 90%; // largura de 90% da largura do elemento pai
    height: 90%; // altura de 90% da altura do elemento pai
}
````
![videoexterno](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/videoexterno.PNG)

#### 17.4.4.2 - Video local

Para um video local o processo é mais simples, basta indicar a __*porcentagem*__ horizontal que o vídeo irá ocupar, assim a altura irá acompanhar.

````
 div {
            background-color: green;
        }
video{
            width: 95%;
            padding: 2.5%;
        }
````

![videolocal](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/videolocal.PNG)



### 17.5 - Variáveis CSS

As variáveis no CSS facilitam o uso contínuo de atributos usados frequentemente no projeto, por exemplo: fontes e cores. 

Elas são criadas normalmente dentro do seletor __*:root*__.

Exemplo:

````
:root{

}
````

Dentro deste seletor, declaramos as variáveis que poderão ser chamadas em todo o arquivo CSS. Toda variável CSS começa com "--".

````
:root{
    --cor0: #c5ebd6;
    --cor1: #83e1ad;
    --cor2: #3ddc84;
    --cor3: #2fa866;
    --cor4: #1a5c37;
    --cor5: #063d1e;

    --fonte-padrao: Arial, Verdana, Helvetica, sans-serif;
    --fonte-destaque: 'Bebas Neue', 'cursive';
    --fonte-android: 'Android', 'cursive';
}
````

 Assim que uma variável for __*mudada*__, todo o arquivo CSS é mudado.

````
body{
    background-color: var(--cor0);
    font-family: var(--fonte-padrao);
}
````

Se, por exemplo, a fonte padrão for alterada, todos os elementos que receberam a variável --fonte-padrao serrão mudados, economizando tempo.




## 18 - Github e Git

Boa parte do conteúdo já foi estudado anteriormente.

Conteúdo de apoio presente no [PDF do capítulo 18](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/18%20-%20Aprendendo%20Git%20e%20GitHub.pdf).

Link de download para o [Github Desktop](https://desktop.github.com). Ferramenta que facilita a utilização do git.

### 18.1 - Criando um site pelo Github pages!

Para criarmos um site no github pages, vamos utilizar até o repositório no qual desejamos criar a página ou criaremos um repositório novo diretamente no [github](https://github.com). Seguindo os seguintes passos:

![github.com](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/github.PNG)
![github2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/github2.PNG)
![github3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/github3.PNG)

Dentro de pages, selecionaremos a branch onde o projeto está e o diretório raiz.

![github4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/github4.PNG)

Depois, a página ficará disponível no endereço usuário.github.io/repositório. Dentro deste exemplo: https://luisredskill.github.io/HTML-CSS-Javascript/




## 19 - Imagens de Fundo

Conteúdo de apoio presente no [PDF do capítulo 19](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/19%20-%20Imagens%20de%20Fundo.pdf).

### 19.1 - Como adicionar uma imagem ao fundo a um elemento CSS?

Para adicionar uma imagem de background em um elemento CSS utilizamos o background-image:

```
div#A1{
background-color: skyblue;
}

div#A2{
    background-image: linear-gradient(to bottom, yellow, red);
}

/* NOTE que a div A3 possui uma imagem de background*/

div#A3{
    background-image: url('imagens/pattern003.png');
}
```

Resultado:

![fundo](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/fundo.PNG)

### 19.2 - Repetição de imagem de fundo.

#### 19.2.1 - Como repetir uma imagem de fundo?

A repetição de fundo no CSS é o padrão, ou seja, toda imagem que não cobrir a página inteira será repetida até cobrir. Exemplo:

![CSS3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/CSS3.PNG)

#### 19.2.2 - Como alterar o tamanho de uma imagem de fundo?

Podemos forçar um tamanho de imagem pela seguinte forma:

```
body{
    background-image: url('../imagens/CSS3.png');
    background-size: 100px 141px;
}
```

Resultado:

![CSS3_2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/CSS3_2.PNG)

#### 19.2.3 - Como NÃO repetir uma imagem de fundo?

```
body{
    background-repeat: no-repeat;
}
```

Resultado:

![CSS3_3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/CSS3_3.PNG)

#### 19.2.3 - Como repetir apenas verticalmente/horizontalmente?

Para repetir um fundo _*horizontalmente*_ utilizamos:

```
body{
    background-repeat: repeat-x;
}
```

Resultado:

![CSS3_4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/CSS3_4.PNG)

Para repetir um fundo _*verticalmente*_ utilizamos:

```
body{
    background-repeat: repeat-x;
}
```

Resultado:

![CSS3_5](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/CSS3_5.PNG)

### 19.3 - Como escolher a posição de referência da imagem de fundo?

#### 19.3.1 - Alterando a referência.

Por padrão é o canto _*esquerdo superior*_(left top).

Referência:

![posicaobg](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/posicaobg.PNG)

Para reposicionar a imagem de background devemos utilizar a declaração _*background-position*_.

Código:

```
div#q1{
background-position: left top;
}

div#q2{
    background-position: left center;
}

div#q3{
    background-position: right bottom;
}

div#q4{
    background-position: center center;
}
```

Resultado e imagem de referência:

![posicaobg2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/posicaobg2.PNG)

![posicaobg3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/posicaobg3.jpg)

#### 19.3.1 - O que alterar a referência significa para a responsividade?

Alterar a referência de uma imagem de fundo diz ao site qual parte do seu fundo é a mais importante e que sempre deve ser mostrada. Isso quer dizer que as dimensões de altura e largura partirão sempre do ponto de referência.

Vamos supor que nós temos uma imagem de _*300x300*_, e o navegador esteja sendo _*dimensionado*_ em _*200x200*_. As seguintes porções do fundo seriam mostradas:

 ![posicaobg4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/posicaobg4.PNG)

 ### 19.4 - Alterando o tamanho da imagem de background.

 #### 19.4.1 - Alteração por medidas absolutas.

Para alterar o tamanho de uma imagem de background utilizamos o _*background-size*_.

O _*background-size*_ define o tamanho horizontal e vertical que o fundo irá ocupar distorcendo a imagem para ocupar exatamente as proporções definidas.

Exemplo 500x500:

````
body{
    background-size: 500px 500px;  
}
````

Resultado:

 ![tamanhobg](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tamanhobg.PNG)

 #### 19.4.2 - Alteração por medidas relativas.

 Podemos também utilizar valores em porcentagem. Note que eles sempre ocuparão aquela porcentagem da _*altura*_ e da _*largura*_ deixando o background responsivo, porém distorcendo a imagem.

 ````
body{
    background-size: 100% 100%;  
}
````
![tamanhobg2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tamanhobg2.PNG)

![tamanhobg3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tamanhobg3.PNG)

 #### 19.4.1 - Como deixar o background responsivo? (cover, contain)

 As declarações mais utilizadas quando falamos de responsividade para fundos são o _*cover*_ e o _*contain*_:

 - Cover - Adapta o conteúdo para cobrir a tela inteira independente do tamanho e mantendo a resolução da imagem de fundo. Para isso, corta partes da imagem afim de manter a resolução.

 Código:

 ````
body{
    background-size: cover;  
}
````

Resultado:

![tamanhobg4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tamanhobg4.PNG)

- Contain - Adapta o conteúdo para mostrar toda a imagem sem distorcê-la. Para isso, permite a criação de espaços vazios laterais.

 Código:

 ````
body{
    background-size: contain;  
}
````

Resultado:

![tamanhobg5](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tamanhobg5.PNG)
![tamanhobg6](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tamanhobg6.PNG)

### 19.5 - Alterando a fixação do background (scroll, fixed)

Podemos alterar o comportamento da imagem de background para ela rolar junto com o conteúdo(padrão) ou ser fixa e apenas o conteúdo rolar através do _*background-attachment*_:

Código:

 ````
body{
     background-attachment: scroll;  
}
````
Resultado:

![scroll](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/scroll.gif)

Código:

 ````
body{
     background-attachment: fixed;  
}
````
Resultado:

![fixed](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/fixed.gif)

### 19.6 - Background ShortHand

Existe um shorthand para o background que inclui:

color &rarr; image &rarr; position &rarr; repeat &rarr; size &rarr; attachment.

Exemplo:

````
background: black url('../imagens/wallpaper002.jpg') center center no-repeat cover fixed;
````
*IMPORTANTE* - a declaração size atualmente não funciona na maioria dos navegadores, para poder ser utilizada de forma correta devemos utilizar o shorthand da seguinte forma:

color &rarr; image &rarr; position &rarr; repeat &rarr; attachment.

size

````
    background: black url('../imagens/wallpaper002.jpg') center center no-repeat fixed;

    background-size: cover;
````

Resultado:

![fixed](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/fixed.gif)


## 20 - Projeto Cordel

Conteúdo de apoio presente no [PDF do capítulo 20](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/PDFs/20%20-%20Mini-projeto%20Cordel.pdf).


Projeto feito com base nos conhecimentos anteriores e [capítulo 19](https://github.com/luisredskill/HTML-CSS-Javascript/tree/main/HTML-CSS/Exercicios#19---imagens-de-fundo).

Veja aqui o [projeto feito sozinho.](https://luisredskill.github.io/HTML-CSS-Javascript/HTML-CSS/Exercicios/Desafios-M3/Desafio%20012%20Efeito%20parallax/index.html) com alterações propositais.

![cordel](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/cordel.gif)

Veja aqui o [projeto feito em aula.](https://luisredskill.github.io/HTML-CSS-Javascript/HTML-CSS/Exercicios/Desafios-M3/Desafio%20012%20Efeito%20parallax%20feito%20em%20aula/index.html)


![cordelaula](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/cordelaula.gif)

## 21 - Tabelas em CSS

### 21.1 - Hierarquia de tabelas.



| TAG HTML          | significado                           |
| ----------------- | --------                              |
| table             | tabela                                |
| tr                | table row ou linha de tabela          |
| thead             | indica o cabeçalho da tabela          |
| th                | indica conteúdo do cabeçalho ou foot  |
| tbody             | corpo da tabela                       |
| td                | conteúdo do corpo                     |
| tfoot             | pé da tabela  |
| caption             | legenda da tabela  |

As tabelas em CSS possuem uma hierarquia, primeiro criamos uma &lt;table&gt;, que será a nossa tabela, dentro desta tabela criada, colocaremos linhas &lt;tr&gt; e, por fim, colocaremos dados dentro dessas linhas &lt;td&gt;.


Ainda podemos adicionar, na primeira linha, o cabeçalho da tabela &lt;th&gt;.

Código:

````
<table>
  <tr>
    <th>Nome</th>
    <th>Sobrenome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Luis Carlos</td>
    <td>Ribeiro</td>
    <td>22</td>
  </tr>
  <tr>
    <td>Raissa</td>
    <td>Castro</td>
    <td>25</td>
  </tr>
</table>
````

Resulado:

|       Nome        | Sobrenome   |     Idade       |
| ----------------- | --------    |   --------      |
| Luis Carlos       | Ribeiro     |      22         |
| Raissa            | Castro      |      25         |

````
    <table>
        <caption>População dos Estados</caption>
        <thead>
            <tr>
                <th>Estado</th>
                <th>População(2010)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>São Paulo</td>
                <td class = "num">41 262 199</td>
            </tr>
            <tr>
                <td>Minas Gerais</td>
                <td class = "num">19 597 330</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>Total de habitantes</td>
                <td><strong>210 147 125</strong></td>
            </tr>
        </tfoot>
    </table>
````

Resultado:

![tablehead](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tablehead.PNG)

- _*IMPORTANTE*_ - _*NÃO*_ é obrigatório o fechamento das tags &lt;td&gt; e &lt;tr&gt;. 

### 21.2 - Escopo de tabela (SEO).

#### 21.2.1 - Escopo simples

Para ajudar nas buscas e no rankeamento de sites, devemos definir um escopo para cada título de informação presente em nossa tabela.

Fazemos isso atribuindo aos títulos suas respectivas informações correspondentes, exemplo:

````
 <th scope="col">Estado</th>              
````

Isto indica que o título _*Estado*_ &lt;th&gt; se refere a coluna de informações &lt;td&gt; abaixo dele representado em vermelho:

![tablehead2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tablehead2.PNG)

O mesmo se aplica ao título _*População*_ &lt;th&gt; que se refere a coluna de informações &lt;td&gt; abaixo dele representado em verde.

![tablehead3](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tablehead3.PNG)

````
 <th scope="row">Estado</th>              
````

Também pode ser aplicado a linhas como é o caso do foot apresentado na tabela onde _*Total de Habitantes*_ &lt;th&gt; se refere à linha representado em amarelo:

![tablehead4](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tablehead4.PNG)

#### 21.2.2 - Escopo de grupo.

Quando executamos uma mesclagem de células de um título, queremos indicar que uma série de informações estão representadas por um mesmo título.

Exemplo:

![tablegroup](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tablegroup.PNG)

Note que Mulheres neste caso representa um grupo de linhas, não apenas uma linha.

Assim sendo, devemos utilizar o atributo _*row-group*_(verde) em vez de _*row*_ (vermelho).

![rowgroup](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/rowgroup.gif)


O mesmo se aplica ao título _*Filmes*_ onde devemos utilizar o _*col-group*_(verde) em vez de _*col*_(vermelho):


![colgroup](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/colgroup.gif)

### 21.3 - Mesclagem de tabelas.

Podemos mesclar as células de tabelas presentes em html utilizando o _*rowspan*_ e o _*colspan*_.

Dessa forma, mesclamos a célula ao número de colunas ou linhas especificado, exemplo:

O número três tem um rowspan, enquanto o 8 tem um colspan.

````
<td rowspan="2">3</td>
<td colspan="3">8</td>
````

Código presente neste [link](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Exercicios/M3-EX023/tabela004.html)

Resultado:

![mesclagem](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/mesclagem.PNG)


### 21.4 - Bordas de tabelas

Por padrão as _*bordas*_ de uma tabela CSS vem _*desativadas*_. Para ativá-las basta adicionar uma borda como já foi mostrado no [16.2.1](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Exercicios/README.md#1621-adicionando-uma-borda).

Porém uma nova propriedade é aplicada as bordas de tabela. Por padrão as bordas de uma tabela não colapsam gerando o seguinte efeito:

![table](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/table.PNG)

Para fazer com que as bordas _*colapsem*_, podemos utilizar o atributo _*border-collapse*_ que vem com o valor padrão em _*separate*_ alterando-o para _*collapse*_.

````
table{
    border-collapse: collapse;
}
````

![table2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/table2.PNG)

### 21.5 - Alinhamento do conteúdo em tabelas.

#### 21.5.1 - Alinhamento horizontal.

Para alinhar o conteúdo de uma célula em uma tabela _*horizontalmente*_ utilizamos o _*text-align*_. A posição padrão é à esquerda.

````
td{
    text-align: left;
    text-align: center;
    text-align: right;
}
````

Resultado:

![tablealign](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/tablealign.gif)

#### 21.5.2 - Alinhamento vertical.

Para alinhar o conteúdo de uma célula em uma tabela _*verticalmente*_ utilizamos o _*vertical-align*_. A posição padrão é ao centro.

````
td{
    vertical-align: top;
    vertical-align: middle;
    vertical-align: bottom;
}
````

Resultado:

![tablevertical](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/tablevertical.gif)

### 21.6 - Efeito zebrado em tabelas.

O efeito zebrado pode ser feito facilmente por uma pseudo-classe [já citada](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Exercicios/README.md#1562---procurando-por-uma-pseudo-classe) que seleciona elementos filho com base em suas posições relativas ao pai.

Código:

````
tbody > tr:nth-child(2n){
    background-color: lightgray;
}
````

Assim, primeiro é selecionado o corpo da tabela, depois a pseudo-classe que representa as _*linhas da tabela*_ intercaladas por um múltiplo de 2.

Resultado:

![tablezebra](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/tablezebra.PNG)

Ainda podemos utilizar _*2n-1*_, _*odd*_ e _*even*_ para obter o mesmo resultado diferenciando apenas qual será a primeira célula a ser aplicada o efeito.

### 21.7 - Personalizando colunas e linhas inteiras de tabelas.

#### 21.7.1 - Selecionando linhas de tabelas.

A personalização de linha é algo mais natural e intuitivo, fazemos isso a partir de uma classe inserida dentro de uma tag &lt;tr&gt; da seguinte forma:

Código:

````
<tr class ="destaque">
````

Resultado:

![selecionandocolunas](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/selecionandocolunas.PNG)

#### 21.7.2 - Selecionando colunas de tabelas.

Já a personalização de colunas é um pouco mais complicado, pois não temos uma coluna para selecionar, mas sim dados &lt;tr&gt;, forçando a inserção dado a dado.

Para isso temos uma ferramente que permite selecionar colunas inteiras muito parecido com o &lt;tr&gt;. Exemplo:

![selecionandocolunas2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/selecionandocolunas2.PNG)

````
    <colgroup>
        <col class="cnome">
        <col class="csexo">
        <col class="cidade">
        <col class="cprof">
    </colgroup>
````

Essa ferramenta permite a criação de um grupo de colunas &lt;colgroup&gt; onde cada elemento &lt;col&gt; inserido irá representar uma coluna em ordem da esquerda para a direita. Ou seja, ao alterar a classe .cnome, estaremos alterando toda a primeira coluna (verde claro).

O mesmo é válido para sexo(vermelho),cidade(cinza) e profissão(azul)

Código:
````
/* Cada um é aplicado individualmente no gif abaixo */

.cnome{
    background-color: lightgreen;
}

.csexo{
    background-color: red;
}

.cidade{
    background-color: gray;
}

.cprof{
    background-color: aqua;
}
````
Resultado:

![selecionandocolunas](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/selecionandocolunas.gif)

Ainda é possivel selecionar mais de uma coluna por tag &lt;col&gt; da seguinte forma:

HTML:

````
    <colgroup>
        <col class="cgroup1" span ="2">
        <col class="cgroup2" span ="2">
    </colgroup>
````

Assim serão aplicadas nas duas primeiras colunas a formatação da classe cgroup1 e nas duas últimas a formatação da cgroup2:

CSS:

````
/* Cada um é aplicado individualmente no gif abaixo e depois em conjunto */

.cgroup1{
    background-color: lightgreen;
}

.cgroup2{
    background-color: red;
}
````

Resultado:

![span](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/span.gif)


### 21.8 - Cabeçalho fixo para tabelas.

Podemos criar um cabeçalho fixo para nossa tabela da seguinte forma:

Primeiro declaramos que a posição da tabela é do tipo _*absolute*_

````
table{
    position: relative;
}
````

Depois, selecionamos o cabeçalho ou o título dentro do cabeçalho:

````
thead  {
    position: sticky;
    top: -1px;
}

/* podemos utilizar um código parecido de mesma função: */

thead > tr > th {
    position: sticky;
    top: -1px;
    background-color: gray;
}

````

### 21.9 - Tabelas responsivas

Quando trabalhamos com tabelas maiores enfrentamos um problema muito comum, caso a tela seja reduzida o html da página gera uma rolagem lateral da página inteira:

![tabelaresponsiva](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/tabelaresponsiva.gif)

Para evitar esse tipo de comportamento podemos utilizar a seguinte configuração:

Primeiro, no HTML, inserimos a nossa tabela dentro de uma div e damos um id para ela:

````
<div id ="container">
    <table>

    </table>
</div>
````

Depois, nas CSS, alteramos o atributo _*overflow-x*_:

````
div#container{
    overflow-x: auto ;
}
````

Resultado:

![tabelaresponsiva2](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/gifs/tabelaresponsiva2.gif)

### 21.10 - Desafio 14

Reconstruir tabela mostrada [em aula](https://www.youtube.com/watch?v=V2gVaqTSRmo&list=PLHz_AreHm4dmcAviDwiGgHbeEJToxbOpZ&index=37).

Resultado:

![desafio14](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/desafio14.PNG)

Código disponível [aqui](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Exercicios/Desafios-M3/Desafio%20014%20tabela%20de%20notas/index.html).

## 22 - Iframes

### 22.1 - O que é um iFrame?

iFrame é a abreviação de Inline Frame, essa ferramente permite que você exiba conteúdo de outra página na sua página web. Exemplos:

- Vídeo do youtube

![youtube](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/youtube.PNG)

- Google maps

![googlemaps](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/googlemaps.PNG)


Ele é parte do conteúdo do site, mas não é parte do site em si. Alguns sites não permitem que seu conteúdo seja colocado em iframes como o próprio google:

![google](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/google.PNG)

### 22.2 - Problemas com iFrame.

O iFrame possui uma série de problemas de compatibilidade, SEO e segurança. Dentre eles podem-se citar:

- Existem alguns problemas para indexação de conteúdo dentro de iFrames segundo o Google. O rankeamento pode ser prejudicado.

- Os softwares leitores de tela (acessibilidade para cegos) tem dificuldade para acessar o iFrame.

- O navegador pode se confundir ao entrar em um iFrame e acaba não conseguindo voltar a página no iFrame e voltando na principal.

- Abrir janelas possui o mesmo problema anterior.

- Caso o site não seja responsivo, ele não será propriamente exibido dentro do iFrame.

- A segurança do seu site pode ser comprometida, pois o site inserido no iFrame pode ser malicioso.Cross site e XSS são os tipos de ataques mais comuns.

### 22.3 - Como deixar os iFrames mais seguros?

#### 22.3.1 - Formulários.

Alguns códigos maliciosos utilizam-se de formulários para capturar informações do usuário para uso indevido.

Sabendo disso podemos impedir que um iFrame envie formulários através do atributo _*sandbox*_.

Exemplo:

````
<iframe src="paginaexemplo.html" frameborder="0" sandbox="sandbox">
````

Esta configuração não vai permitir que sejam enviados formulários.

- _*IMPORTANTE*_ - Este é o nível máximo de segurança, não apenas formulários são impeditos, mas uma série de funções podendo prejudicar a utilização do site.

Permitindo que formulários sejam executados:

````
<iframe src="paginaexemplo.html" frameborder="0" sandbox="allow-forms allow-scripts">
````

Note que os formulários utilizam javascript para serem executados.

#### 22.3.2 Informações do usuário.

Muitos sites utilizam os dados de navegação do usuário para mostrar propagandas, isso pode ser impedido através do seguinte código:
````
<iframe src="paginas-extras/pag004.html" frameborder="1" referrerpolicy="no-referrer">
````

### 22.4 - Como adicionar um iFrame?

O iframe pode ser adicionado através da tag &lt;iframe&gt;.

Código:

````
<iframe src="url-da-página.com.br" frameborder="0"> Seu navegador não possui compatibilidade com iframes</iframe> 
````
Note que o iframe por padrão vem com a propriedade de borda no 0, ou seja, não há borda. Caso essa propriedade tenha qualquer número acima de 0 é criado uma borda de 1px em volta do iframe.

- _*IMPORTANTE*_ - A informação colocada dentro do iframe só é exibida em caso de incompatibilidade com o recurso! Normalmente, um link é adicionado para direcionar o usuário ao site.

Podemos adicionar conteúdos como:

- Videos do youtube/vimeo
- Google maps
- Planilhas do google

### 22.5 - Como personalizar um iFrame?

#### 22.5.1 - Como alterar o tamanho de um iframe?

 Alteração inline.

O tamanho padrão de um iframe é de _*300x150*_.

Podemos alterar o tamanho do iframe inline:

````
<iframe width="500" height="500" src="http://www.google.com/"></iframe>
````

Alteração via CSS

````
iframe{
    width: 400px;
    height: 400px;
}
````

#### 22.5.2 - Como retirar a barra de rolagem?

Existe um parâmetro para iframes chamado de _*scrolling*_ e ele é utilizado para permitir ou não a rolagem do conteúdo. Ele pode receber 3 atributos: auto, yes e no.

- auto - o navegador vai decidir automaticamente
- yes - o navegador sempre vai criar a barra de rolagem
- no - o navegador não vai permitir a rolagem em nenhum caso

## 23 - Projeto Social


Projeto feito com base nos conhecimentos anteriores e [capítulo 22](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Exercicios/README.md#22---iframes).

Veja aqui o [projeto feito em aula.](https://luisredskill.github.io/HTML-CSS-Javascript/HTML-CSS/Exercicios/Desafios-M3/Desafio%20013%20Redes%20Sociais/index.html)


![projetosocial](https://github.com/luisredskill/HTML-CSS-Javascript/blob/main/HTML-CSS/Screenshots/projetosocial.PNG)

## 24 - Formulários em HTML.

### 24.1 O que são formulários em html?

Formulários html são campos de informações que permitem ao usuário fazer requisições http ao site, utilizadas comumente para o cadastro de um cliente, declaração de preferências, escolha de caracteristicas de produtos, etc. 

Não está limitado apenas à isso, qualquer informação do cliente pode ser coletada através de um formulário, sendo assim o maior ponto de interação entre usuário e site.

### 24.2 Criando formulários.

Para se criar um formulário em HTML utilizamos a tag &lt;_*form*_&gt;.

````
    <form>
        Este é um formulário.
    </form>
````

Normalmente, formulários são utilizados para aglomerar informações do usuário e enviá-las ao servidor. Para otimizar o SEO da página devemos ligar os campos de _*input*_ aos campos de _*nome*_, para isso podemos utilizar a tag &lt;_*label*_&gt;.

- _*IMPORTANTE*_ - Primeiro damos um _*id*_ ao _*input*_, depois usamos a tag &lt;_*label*_&gt; para conectar o input ao nome, assim as SEOs são otimizadas e funcionam melhor em nosso site

````
    <form>
        <label for="inome">Nome:</label> 
            <input type="text" name="nome" id="inome"></p>
    </form>
````

- _*IMPORTANTE*_ - o método padrão de envio é o _*GET*_, mandando as informações digitadas pela URL, para alterar isso utilizamos o parâmetro method que pode receber _*GET*_ ou _*POST*_.
````
    <form method="post">
        Seu formulário
    </form>
````
### 24.3 Desligando autocomplete.

````
    <form autocomplete="off">
        Seu formulário
    </form>
````
### 24.4 Enviando formulários em javascript.

Para enviar formulários em javascript devemos resgatar as informações do formulário dentro do código javascript, para isso devemos _*dar um id*_ para o nosso formulário:

HTML:

````
    <form id = 'form'>
        Seu formulário
    </form>
````

Javascript:
````
const form = document.getElementById("form")
````

Depois, devemos executar um script quando uma ação ocorrer a partir do usuário, por exemplo click no botão submit:

HTML:

````
<input type="submit" value="Enviar">
````

````
addEventListener( 'submit', (event) =>{
    alert("vai acontecer quando clicar no botão Enviar")
})
````
------------------------------------------------------------------------------
