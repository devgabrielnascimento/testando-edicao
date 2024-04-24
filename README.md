# testando-edicao
<style>
.magic-button, a[href$="#magic-button"] {
    display: inline-block;
    padding: 5px;
    position: relative;
    background: red;
    color: white;
    text-shadow: 0 1px #006bb3;
    border-radius: 3px;
    box-shadow: inset 0 0 0 1px #006bb3,
        0 1px 2px rgba(0,0,0,0.1);
    text-decoration: none;
    font-family: "Trebuchet MS", sans-serif;
}
.magic-button::after, a[href$="#magic-button"]::after {
    box-sizing: border-box;
    display: block;
    content: attr(title);
    background: green;
    border-radius: 3px;
    box-shadow: inset 0 0 0 1px darken(green, 20%);
    text-shadow: 0 1px darken(green, 20%);
    display: inline-block;
    height: 0;
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    transition: 200ms;
    padding: 0 5px;
    text-align: center;
    overflow: hidden;
    
}
.magic-button:hover::after, .magic-button:active::after,
a[href$="#magic-button"]:hover::after, a[href$="#magic-button"]:active::after {
    height: 100%;
    padding: 5px;
}
.magic-button:active::after,
a[href$="#magic-button"]:active::after {
    background: darken(red, 10%);
}
</style>


<a href="#" class="magic-button" title="Hover text">Normal text</a>







<div>
<img src="img/Ellipse 18.svg" alt= "teste">
</div>
<img src="img/quadro_teste.svg" alt="teste">

<a href="https://instagram.com/devgabrielnascimento"> <img src="img/_a_frame01instagram.svg" alt="teste"> </a>






<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/devgabrielnascimento/testando-edicao/981452ffbeb1b25544c61774f5286021d2f0da29/img/sun_icon.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/devgabrielnascimento/testando-edicao/981452ffbeb1b25544c61774f5286021d2f0da29/img/moon_icon.svg">
  <img alt=".." src="img/moon_icon.svg">
</picture>