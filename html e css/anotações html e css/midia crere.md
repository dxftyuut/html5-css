
midia crere e como o seu site se comporta em diferentes telas

paara criar uma media crery você ceia um arquivo css e na frente do link coloque media e o tipo de media que você deseja, isso também vai ser ultilizado para fazer Media Features, que não e a mesma coisa, mas e bem parecido

Reunindo tudo em um único CSS - Pode ser feito usando a tag <style, dentro de <head>, usando @media para especificar o tipo de mídia e 'and' para unir os 'media features'; - Além disso pode ser feito também usando o 'link:css' para criar um arquivo de estilo separado. Ex: @charset "UTF-8"; /* declarações gerais */ @media all { h1 { color: white; text-shadow: 2px 2px 0px [#1526a7](https://www.youtube.com/hashtag/1526a7); padding: 10px; } } /* declarações retrato */ @media screen and (orientation: portrait) { body { background-image: url(../imagens/cev-portrait.jpg); background-position: center bottom; } } /* declarações paisagem */ @media screen and (orientation: landscape) { body { background-image: url(../imagens/cev-landscape.jpg); background-position: left bottom; } } *Obs: Atalho para identar o código dentro do VS Code: Shift + Alt + F







para fazer sites para diferentes dispositivos, você pode criar um link de css e dentro dele você vai criar varios @media screen and (minimo de pixels)

depois abra { e coloque as configurações}

isso e chamado de Device breakpoints

