# iasmin

## 1. construção de textos e parágrafos com HTML

### A. criação de paraǵrafos ou frases

#### Exemplos:

<p id ="p1" onclick = "mudar_cor()">Aqui vai qualquer texto ou frase que queira</p>

### B.Adicionados CSS aos parágrafos

#### Exemplos adicionando cores:

#p1{

    color: blue;

}

### C.Adicionando Javascript aos paraǵrafos 

#### Exemplos mudando cores:

function mudar_cor(){

    document.getElementbyId("p1").style.color = "brown";

}

#### Observe que o mesmo p1 está sendo repetido no HTML, CSS e JavaScript!!!

<br>

## 2. Construção de titulos e subtitulos


### A. Toda página possui um único tema. para isso, use h1.

<h1 id ="h1" onclick = "mudar_h1()">Tema da minha página</h1>

<br>

### B. Adicionando CSS ao tema 

#### Exemplos adicionando um tipo de capitalização:

#h1{

    text-transform: lowercase;

}

<br>

### C. Adicionando JavaScript ao tema

#### Exemplos mudando a capitalização padrão do CSS:

function mudar_h1(){ 

    document.getElementByd("h1").style.textTransform = "uppercase";

}

### D. Toda página pode ter subtítulo para cada pedaço de conteúdo, assim como um mercado possui um nome para cada corredor. Para isso, use h2.

<h2 id = "h2" onclick = "mudar_h2()" >subtítulo da seção de frios</h2>

<h2 id = "h_2" onmouseenter="mudar_h_2()">subtítulo da seção de frios</h2>

<br>

### E. Adicionando CSS aos subtítulos 

#### Exemplos adicionando cor de fundo e alterando alinhamento:

#h2{

    background-color: cyan;
}

#h_2{  

    text-right;
}

<br>

### F. Adicionando JavaScript ao subtítulos

#### Exemplo mudando a cor de fundo e o alinhamento padrão do CSS.

function mudar_h2(){

    document.getElementById("h2").style.backgroudColor = "yellow";
}

function mudar_h_2(){

    document.getElement("h2").style.textAlign = "left"; 
}

<br>

## <3>. Contrução listas ordenadas e desordenadas 

<br>

### A) Listas Ordenadas: agrupar itens que possuem uma relação de ordem crescente ou decrescente entre si.

### Exemplos

<h1>Seleções nacionais mais vencedoras da copa do mundo FIFA:<h1>

<ol id ="ol1" onclick ="mudar_()">
    <li>Brasil - 5</li>
    <li>Alemanha - 4</li>
    <li>Itália - 4</li>
    <li>Argentina - 3</li>
    <li>Uruguai - 2</li>
    <li>França - 2</li>
    <li>Espanha - 2</li>
    <li>Inglaterra - 1</li>
</o1>

<br>

### B) Customizando com o CSS

#### Exemplos alterando o tipo de ordenamento e sua cor:

#ol1{

    list-syle-type: lower alpha;

}

#ol1 > li : :marker{

    color: red;

}

<br>

### C) Adicionando interação com o JS.

#### Exemplos modificando o tipo de ordenamento:

function mudar_ol1(){

    document.getElementbyId("ol1")>style.listStyleType = "decimal";

}

<br>

### D) Listas não Ordenadas: agrupar itens não possuem uma relação de ordem crescente ou decrescente entre si.

### Exemplo

<h1>Os assuntos mais comuns em Estatisticas</h1>

<ul id = "ul1" onclick = "muda_ul1()">
    <li>Média</li>
    <li>Moda</li>
    <li>Mediana</li>
    <li>Variância</li>
    <li>Amostragem</li>
    <li>Desvio Padrão</li>
    <li>Intervalo de confiança</li>
</ul>

<br>

### E) Customizando com o CSS

#### Exemplos alterando o simbolo de destaque ao lado do nome e sua cor:

#ul1{

    list-style-type: square;

}

#ul1 > li : : marker{

    color: coral:

}

<br>

### F) Adicionando interação com o JS.

#### Exemplo modificando o simbolo de destaque 

function mudar_ul1(){

    document.getElementById("ul1").style.listStyleType = "circle";                                                                                                                                                                        
}

<br>

### 4. Imagens

<br>

### A) Imagens por padrão em um site:

#### Exemplos:

<figure>

    <img id = "gif0" onmuseenter = "mudar_gif0()" src=" ./imagens/html-css-js.gif" alta="GIF com a diferença entre HTML, CSS e Javascript" width="480" height="480"> 

</figure>

<br>

### B) Customizando com o CSS

#### Exemplos adicionando arredondamento da borda, opacidade, borrão, brilho e sombreado de uma imagem:

<br>

#gif{

    border-radius: 30px;
    opacity: o.8;
    filter: blur(2px) brightness(150%) drop-shadow(10px 10px 1px red);

}

<br>

### C) Adicionando interação com o JS.

#### Exemplos mudar_gif0(){
    
    document.getElementbyId("gif0").style.borderradius = "15px"; 
    document.getElementbyId("gif0").style.opactiy = "0,7";
    document.getElementbyId("gif0").style.filter = "blur(3px)";
    document.getElementbyId("gif0").style.filter = "brightness(70%)";
    document.getElementbyId("gif0").style.filter = "drop-shadow(6px 7px 2 px coral)";

}

<br>

## 5. Videos

<br>

### A) Videos por padrão em um site

#### Exemplos:

<video id="video_0" width ="640" height="360" controls>

  <source src="./videos/movie1.mp4" type="video/mp4">

</video>

<br>

### B) Videos vindo do Youtube com iframe

#### Exemplos:

<iframe width="640" heigth="360" src="https://www.youtube.com/embed/LXb3EKWsInQ"
title="COSTA RICA IN 4K 60fps HDR (ULTRA HD)" allowfullscreen<>/iframe>

<br>

### C) Exemplos adicionando arredondamento da borda e sombreado no video:

<br>

#video_0{

    border-radius: 10px;
    filter: drop-shadow(2px 2px 5px gray);

}
<br>

## 6. Hiperlinks 

<br>

### A) Hiperlinks para outros sites 

#### Exemplos abrindo o link em outra aba do navegador:

<nav>

<a id="link_0" href ="https://www.google.com" target ="_blank">google</a>

</nav>

#### Exemplos abrindo o link na mesma aba do navegador:

<nav>

<a id="link_1" href ="https://www.youtube.com">Youtube</a>

</nav>

<br>

### C) Customizando com o CSS

#### Exemplos com os 4 estados de um link:

<br>

/* a aparência padrão do link */
#link_0:link {

    color: magenta;
    transition: font-size 2s;

}

/* segundos após o link ser clicado a aparência do link é alterada*/
#link_0:visited {

    color: none;

}

/* altera a aparência quando o mouse passa por cima (houver) do link /*
#link_0:houver {

    color: hotpink;
    font-size: 2em;
    transition: font-size 2s;

}

/* altera a cor no exato momento que o link é clicado com o mouse /*
#link_0:active {

    color: none;
    
}