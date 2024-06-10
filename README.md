Framework CSS baseado em SASS

Paulo Sergio Nascimento Gomes – 37022263

Documentação

Para utilizar o ‘’FastCss’’ é preciso ter o ‘’SASS’’ instalado e configurado
https://sass-lang.com/install/
Após a instalar e configurar o SASS, faça o download do FastCss e o coloque na pasta do seu arquivo em desenvolvimento
https://github.com/Paulo-S-Nascimento/FastCss
Coloque para compilar o arquivo ‘’Base.scss”.

Insira esse código em seu HTML:
<link rel="stylesheet" href="/css/base.css">

Você está pronto (a) para utilizar o FastCss!


Normalize

Esse arquivo possui um conjunto básico de estilos CSS, é usado para garantir uma aparência consistente em diferentes navegadores.

Ultilidades

Botões:
Classes: button-p, button-m, button-g, button-gg
Botões de tamanhos variados com ‘’hover’’, para obter o resultado, insira a classe uma das classes mencionadas no botão.

Input  
Classes: input-p, input-m, input-g, input-gg
Input de tamanhos variados com ‘’focus’’, para obter o resultado, insira a classe uma das classes mencionadas no input.



Header-model (simples – responsivo) 

Para obter esse resultado é necessário fazer o seguinte ‘’HTML’’ e colocar no header a classe “header-model” e no button a classe “button-p”.


 <header class="header-model">
    <div>
        <div>
            <img src="/img/logo.png" alt="Sua Logo Aqui">
            <h1>Sua Logo Aqui</h1>
        </div>

        <nav>
            <a href="#">Início</a>
            <a href="#">Contatos</a>
            <a href="#">Sobre</a>
            <a href="#">Ajuda</a>
            <a href="#"> <img src="/icon/padlock.png"alt=""> Entrar </a>   

            <button class="button-p">cadastre-se</button>
        </nav>
    </div>

    <hr>
 </header>



Hero-model (simples-responsivo)

Para obter esse resultado é necessário fazer o seguinte ‘’HTML’’ e colocar na div a classe “hero-model” e no button a classe “button-g”.


<div class="hero-model">
    <div> 
        <h1> Hero-model </h1>
        <P> Lorem ipsum dolor sit amet consectetur adipisicing elit.
             Excepturi asperiores voluptatem et quasi minus doloribus iste                  
             dolor nesciunt explicabo dolorem nisi fuga at 
             laboriosam quibusdam, porro magnam illo cum?</P>
        <button class="button-g">Clique aqui</button>
    </div>

    <img src="/img/hero.webp" alt="interrogação">
</div>


