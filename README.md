# Prueba_Examen_RA2
## Ejercicio 1
### *1A Pregunta*
Porque el display flex lo estaba bloqueando en su lugar se cambia por un display grid con justify-items: center;

### *1B Soluciona de dos formas diferentes*
*Primera solucion* 
Usar un display grid con justify-items: center;
*Segunda solucion*
Lo mismo que la anterior solamente usando un display flex con justify-content center;

### *1C Convertir la cabecera en dos filas*
Para hacer esto en el site-header he incluido un display grid con un text-aling:center; y al main-nav lo mismo solamente que le añado un padding-top:30px auto;

### *1D Dar relieve y separacion visual al header*
Para que la cabecera tenga un color distinto le añadiremos un background-color: aqua;
Para la separacion visual clara tan simple como un border-bottom-style: solid; y border-bottom-width: 50px;
Para que no quede "pegado" le añadiremos un padding: 20px;

## Ejercicio 2 
### *Reorganización del header con tres elementos*
Para reorganizar el header es tan sencillo como en el html añadir <button class="open-menu" aria-label="Abrir menú lateral">☰</button> despues el h1 y por ultimo el nav, una vez realizado esto en el CSS en el .site-header quitaremos el 
justify-content center; para añadir un justify-content space-around; cambiando de antemano el display grid por display flex

## Ejercicio3
### *Miniaturas, zoom y enlace a la imagen original*
### 3A Crear miniaturas
Las imagenes son las mismas que ya estan puestas en la pagina web solo que mas pequeñas
### 3B Efecto hover
Para las sombras he usado un box-shadow con un inset y para el zoom un transdorm: scale
### 3C Enlace a la imagen original
*CSS del zoom y marco:*

.leviatanes-grid img:hover {
  transform: scale(1.08);
  box-shadow: 0 0 25px #00eaff80, 0 0 50px #00c8ff50 inset;
}

*HTML de los enlaces:*
   
    <a href="../miniaturas/ghost.html"><img src="./img/leviatanes/Caminante_Marino.webp" alt="Caminante Marino" width="500px"></a>
    <a href="../miniaturas/arrecife.html"><img src="./img/leviatanes/Portarrecife.webp" alt="Portarrecife" width="500px"></a>
    <a href="../miniaturas/sea.html"><img src="./img/leviatanes/SEA_LEVIATAN.webp" alt="Sea Leviathan" width="500px"></a>
    <a href="../miniaturas/reaper.html"><img src="./img/leviatanes/Reaper_Leviathan.webp" alt="Reaper Leviathan" width="500px"></a>
    <a href="../miniaturas/ghost.html"><img src="./img/leviatanes/GOSHT_LEVIATAN.webp" alt="Ghost Leviathan" width="500px"></a>
    <a href="../miniaturas/emperor.html"><img src="./img/leviatanes/Sea_Emperor_Fauna.png" alt="Sea Emperor" width="500px"></a>







