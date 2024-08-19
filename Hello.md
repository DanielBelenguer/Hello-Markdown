<!-- Encabezados -->
# Mi titulo h1
## Mi titulo h2
### Mi titulo h3
#### Mi titulo h4
##### Mi titulo h5
###### Mi titulo h6

<!-- Tipos de letra -->
Esto es un texto en *italic* 

Esto es un texto en **strong**

Esto es un ~~texto~~ tachado

<!--Listas desordenadas-->
* manzana
  * manzana 2
* pera
  * pera 2
* etc

<!-- Lista ordenada -->
1. manzana
   1. manzana 2
2. pera
   1. pera 2
3. etc

<!-- Enlaces -->

[google.com](https://www.google.com)

[google.com](https://www.google.com "Titulo personalizado")

> Esto es una cita

<!-- Lineas como el hr -->
---
___

<!-- Para poner codigo -->
`console. log('Hello world')`

<!-- Para muchas lineas de codigo -->

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./css/main.css">
</head>
<body>
    <header>
        <nav class="nav">
            <img class="nav-logo" src="./img/logo_pokedex.png" alt="Logo Pokédex">
            <ul class="nav-list">
                <li class="nav-iten"><button class="btn btn-header" id="ver-todos">Ver todos</button></li>
                <li class="nav-iten"><button class="btn btn-header normal" id="normal">Normal</button></li>
                <li class="nav-iten"><button class="btn btn-header fire" id="fire">Fuego</button></li>
                <li class="nav-iten"><button class="btn btn-header water" id="water">Agua</button></li>
                <li class="nav-iten"><button class="btn btn-header grass" id="grass">Planta</button></li>
                <li class="nav-iten"><button class="btn btn-header electric" id="electric">Electrico</button></li>
                <li class="nav-iten"><button class="btn btn-header ice" id="ice">Hielo</button></li>
                <li class="nav-iten"><button class="btn btn-header fighting" id="fighting">Lucha</button></li>
                <li class="nav-iten"><button class="btn btn-header poison" id="poison">Veneno</button></li>
                <li class="nav-iten"><button class="btn btn-header ground" id="ground">Tierra</button></li>
                <li class="nav-iten"><button class="btn btn-header flying" id="flying">Volador</button></li>
                <li class="nav-iten"><button class="btn btn-header psychic" id="psychic">Psyquico</button></li>
                <li class="nav-iten"><button class="btn btn-header bug" id="bug">Bicho</button></li>
                <li class="nav-iten"><button class="btn btn-header rock" id="rock">Roca</button></li>
                <li class="nav-iten"><button class="btn btn-header ghost" id="ghost">Fantasma</button></li>
                <li class="nav-iten"><button class="btn btn-header dragon" id="dragon">Dragon</button></li>
                <li class="nav-iten"><button class="btn btn-header dark" id="dark">Oscuro</button></li>
                <li class="nav-iten"><button class="btn btn-header steel" id="steel">Acero</button></li>
                <li class="nav-iten"><button class="btn btn-header fairy" id="fairy">Hada</button></li>
            </ul>
        </nav>
    </header>
    <main>
        <div id="todos">
            <div class="pokemon-todos" id="listaPokemon">
                <!--<div class="pokemon">
                    <p class="pokemon-id-back">#025</p>
                    <div class="pokemon-imagen">
                        <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/25.png" alt="Pikachu">
                    </div>
                    <div class="pokemon-info">
                        <div class="nombre-contenedor">
                            <p class="pokemon-id">#025</p>
                            <h2 class="pokemon-nombre">Pikachu</h2>
                        </div>
                        <div class="pokemon-tipos">
                            <p class="electric tipo">ELECTRICO</p>
                            <p class="normal tipo">NORMAL</p>
                        </div>
                        <div class="pokemon-stats">
                            <p class="stat">4m</p>
                            <p class="stat">60kg</p>
                        </div>
                    </div>
                </div>-->
            </div>
        </div>
    </main>
    <script src="./js/main.js"></script>
</body>
</html>
```
<!-- Tablas -->

| Tables        | Are           | Cool  |
|---------------|---------------|-------|
| col 3 is      | right-aligned | 1600€ |
| col 2 is      | centered      |   12€ |
| zebra stripes | are neat      |    1€ |

![logo markdown] (https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT904XZ8kpOic417aETQDdVWE2u5LpQ6XJhNQ&s)

![logo markdown] (logo-markdown.png)

<!-- GITHUB MARKDOWN -->

<!-- TODO -->
* [x] Task 1
* [ ] Task 2

<!-- Mencionar a gente de github -->
@DanielBelenguer

<!-- Emotes -->
:smiley:

:+1:
