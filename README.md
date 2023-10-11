# Exercicio @Devquest - Art Cards


#### Lista de Imagem faz parte dos exercícios de nivel avançado do curso de formação fullstack da Devquest @devemdobro.

## Índice

- [Capturas de telas](#capturas-de-telas)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Luis Fernando Guimaraes](#autor)

### Capturas de telas

#### Tela Desktop

<img src="./src/images/desktop.gif" alt="Tela desktop exibindo funcionalidades">

#### Tela Ipad

<img src="./src/images/ipad.gif" alt="Tela tablet exibindo funcionalidades">

#### Tela Mobile

<img src="./src/images/mobile.gif" alt="Exibindo responsividade no mobile">

### Links

- Site URL: https://luis92guimaraes.github.io/art-cards/

### Construído com

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">     
</div>

### O que aprendi

Esse exercicio foi proposto dentro do curso devquest da @Devemdobro, exercicio do modulo avançado de CSS. Nesse exercício aprimorei minhas habilidades em responsividade e posicionamento de elementos utilizando position relative e position absolute. Este exercicio me proporcionou uma compreensão das práticas de design responsivo e da manipulação de elementos HTML e CSS para criar interfaces funcionais em diversos tamanhos de tela.

## Trechos de códigos

```
.container {
    background-color: var(--bg-color);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
    height: 100vh;
}

.container .pintura {
    position: relative;
}

.pintura img {
    border: 1px solid var(--border-color);
    width: 335px;
    height: 430px;
}

.pintura .obra {
    font-weight: 700;
    font-size: 30px;
    margin-bottom: 8px;
    position: absolute;
    bottom: 60px;
    left: 20px;
}

.pintura .autor {
    font-weight: 300;
    font-size: 17px;
    position: absolute;
    bottom: 40px;
    left: 20px;
}

.container .pintura:hover {
    transform: scale(1.1);
    transition: 1.0 ease-in-out
}

```

### Desenvolvimento contínuo

Pretendo continuar aprendendo cada vez mais sobre as ferramentas utilizadas nesse projeto, ainda tem muita coisa pra ser absorvida mas sigo confiante e feliz em estar conseguindo realizar projetos como esse com mais clareza e confiança a cada dia de estudos.

### Recursos úteis

- [Mdn](https://developer.mozilla.org/en-US/) - O Mozilla Developer Network (MDN) desempenha um papel crucial ao fornecer recursos abrangentes e atualizados para desenvolvedores web em todo o mundo.
- [W3School](https://www.w3schools.com/css/default.asp) - Esse site sempre me ajuda a resolver qualquer problema relacionados a códigos de uma maneira fácil e muito rápida.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Luis Fernando Guimarães](https://www.linkedin.com/in/luisfguimaraes/)