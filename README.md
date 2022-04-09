# Snake_GuilhermeCalonga_Anthonny
Este é um Jogo para quem tem medo do PERIGOOOOO!
# Projeto Game Snake
O jogo da cobrinha tem como objetivo atingir uma cobra de maior dimensão possível. O jogo chega ao fim quando a cabeça da cobra encostar em qualquer parte de seu corpo ou se o jogador decidir encerrá-lo.

## Tecnologias Utilizadas 
-**HTML**: estrutura 
-_*_JS_*: Funcoes 

### Disponibilidade em 
[GitHubPage]( https://github.com/GuilhermeCalonga/Snake_GuilhermeCalonga_Anthonny.git)
### Prints Da Tela 
|  ID |   Primeira Tela | Segunda Tela | 
|-----|-----------------|--------------|
| 1 |  Game Snake | Game Snake
| 2 | ![image](https://user-images.githubusercontent.com/101648142/161781625-eb0946e6-3bba-44cf-9d18-2958c3e08362.png) | |

#### Função Principal
```js:
<!DOCTYPE html>
<html>
<head>
    <title>Game Snake</title>
</head>
<body>
    <canvas id="area" width="600" height="600"></canvas>
    <script type="text/javascript">
        window.onload = function(){

var area = document.getElementById('area');
var ctx = area.getContext("2d");
document.addEventListener("keydown", keyPush);
setInterval(game, 80);

const vel = 1;

var vx = vy = 0;
var px =10;
var py = 15;
var tp = 20;
var qp = 30;
var ax=ay=15;

var trail = [];
tail = 5;

function game(){
    px += vx;
    py += vy;
    if (px <0) {
        px = qp-1;
    }
    if (px > qp-1) {
        px = 0;
    }
    if (py < 0) {
        py = qp-1;
    }
    if (py > qp-1) {
        py = 0;
    }


```
#### Comando Git
Para Iniciar o Projeto
```bash:
git init 

```
