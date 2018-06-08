<!DOCTYPE html>
<html lang="es">
<head>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB" crossorigin="anonymous">
    <link href= "https://fonts.googleapis.com/css?family=Anton" rel="stylesheet">
    <title>ejemplo de estilizacion</title>
    <style>
    body{
        font-family: 'Anton', sans-serif;
        background-color: pink
    }
    .container {
        border: solid 5px;
        border-radius: 16px 179px 10px 14px;
        -moz-border-radius: 16px 179px 10px 14px;
        -webkit-border-radius: 16px 179px 10px 14px;
        border: 5px dotted #000000;
        -webkit-box-shadow: 33px 24px 79px 1px rgba(0,0,0,0.75);
        -moz-box-shadow: 33px 24px 79px 1px rgba(0,0,0,0.75);
        box-shadow: 33px 24px 79px 1px rgba(0,0,0,0.75);
    }
    .degradado{
        background: rgba(183,222,237,1);
        background: -moz-linear-gradient(left, rgba(183,222,237,1) 9%, rgba(135,211,238,1) 24%, rgba(113,206,239,1) 31%, rgba(33,180,226,1) 58%, rgba(142,210,234,1) 79%, rgba(183,222,237,1) 87%);
        background: -webkit-gradient(left top, right top, color-stop(9%, rgba(183,222,237,1)), color-stop(24%, rgba(135,211,238,1)), color-stop(31%, rgba(113,206,239,1)), color-stop(58%, rgba(33,180,226,1)), color-stop(79%, rgba(142,210,234,1)), color-stop(87%, rgba(183,222,237,1)));
        background: -webkit-linear-gradient(left, rgba(183,222,237,1) 9%, rgba(135,211,238,1) 24%, rgba(113,206,239,1) 31%, rgba(33,180,226,1) 58%, rgba(142,210,234,1) 79%, rgba(183,222,237,1) 87%);
        background: -o-linear-gradient(left, rgba(183,222,237,1) 9%, rgba(135,211,238,1) 24%, rgba(113,206,239,1) 31%, rgba(33,180,226,1) 58%, rgba(142,210,234,1) 79%, rgba(183,222,237,1) 87%);
        background: -ms-linear-gradient(left, rgba(183,222,237,1) 9%, rgba(135,211,238,1) 24%, rgba(113,206,239,1) 31%, rgba(33,180,226,1) 58%, rgba(142,210,234,1) 79%, rgba(183,222,237,1) 87%);
        background: linear-gradient(to right, rgba(183,222,237,1) 9%, rgba(135,211,238,1) 24%, rgba(113,206,239,1) 31%, rgba(33,180,226,1) 58%, rgba(142,210,234,1) 79%, rgba(183,222,237,1) 87%);
        filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#b7deed', endColorstr='#b7deed', GradientType=1 );
    }
    .ddoris{
        background: rgba(252,205,77,1);
background: -moz-linear-gradient(left, rgba(252,205,77,1) 0%, rgba(252,205,77,1) 3%, rgba(248,181,0,1) 51%, rgba(250,215,120,1) 91%, rgba(251,223,147,1) 100%);
background: -webkit-gradient(left top, right top, color-stop(0%, rgba(252,205,77,1)), color-stop(3%, rgba(252,205,77,1)), color-stop(51%, rgba(248,181,0,1)), color-stop(91%, rgba(250,215,120,1)), color-stop(100%, rgba(251,223,147,1)));
background: -webkit-linear-gradient(left, rgba(252,205,77,1) 0%, rgba(252,205,77,1) 3%, rgba(248,181,0,1) 51%, rgba(250,215,120,1) 91%, rgba(251,223,147,1) 100%);
background: -o-linear-gradient(left, rgba(252,205,77,1) 0%, rgba(252,205,77,1) 3%, rgba(248,181,0,1) 51%, rgba(250,215,120,1) 91%, rgba(251,223,147,1) 100%);
background: -ms-linear-gradient(left, rgba(252,205,77,1) 0%, rgba(252,205,77,1) 3%, rgba(248,181,0,1) 51%, rgba(250,215,120,1) 91%, rgba(251,223,147,1) 100%);
background: linear-gradient(to right, rgba(252,205,77,1) 0%, rgba(252,205,77,1) 3%, rgba(248,181,0,1) 51%, rgba(250,215,120,1) 91%, rgba(251,223,147,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#fccd4d', endColorstr='#fbdf93', GradientType=1 );
    }
    .elena{
        border-radius: 20px 20px 0px 45px;
-moz-border-radius: 20px 20px 0px 45px;
-webkit-border-radius: 20px 20px 0px 45px;
border: 9px double #000000;
    }
    </style>
<body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <a class="navbar-brand" href="#">menu</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
              
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav mr-auto">
                    <li class="nav-item active">
                      <a class="nav-link" href="#">inicio<span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Link</a>
                    </li>
                    <li class="nav-item dropdown">
                      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Dropdown
                      </a>
                      <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Accion</a>
                        <a class="dropdown-item" href="#">Anottar accion</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">hola</a>
                      </div>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link disabled" href="#">santiago montoya</a>
                    </li>
                  </ul>
                  <form class="form-inline my-2 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">buscar</button>
                  </form>
                </div>
              </nav>
    <div class="container degradado">
            <h1>lorem ipsum</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
    </div>

    <h1>
        Seleccion colombia
    </h1>
    <img src="http://as00.epimg.net/img/comunes/fotos/fichas/equipos/large/2087.png">
    
    <div class=" ddoris elena">
        <p>La selección de fútbol de Colombia es el equipo representativo de ese país para la práctica de este deporte, está dirigida por la Federación Colombiana de Fútbol, la cual está afiliada a la Confederación Sudamericana de Fútbol (Conmebol) y la Federación Internacional de Fútbol Asociado (FIFA), por lo que la selección participa en las competencias que estas entidades organizan y juegan. Su primer partido internacional lo disputó en la ciudad de Panamá el 10 de febrero de 1938.5​

                Su máximo logro internacional es la Copa América obtenida en 2001, siendo Colombia la sede del certamen; también ha alcanzado un subcampeonato en 1975 y llegado a instancias semifinales en 1987, 1991, 1993, 1995, 2004 y 2016.
                
                A nivel de selecciones menores ganó los Campeonatos Sudamericanos Sub-20 de 1987, 2005 y 2013, y el Campeonato Sudamericano Sub-17 de 1993. Así mismo, ocupó el tercer lugar en la Copa Mundial de Fútbol Sub-20 de 2003 realizada en Emiratos Árabes Unidos y posteriormente cuarto lugar en las Copas Mundiales de Fútbol Sub-17 de 2003 y 2009.
                
                Ha participado en seis Copas Mundiales de Fútbol (1962, 1990, 1994, 1998, 2014 y 2018). En Brasil 2014 logró la mejor participación terminando en el puesto 5 de 32 selecciones participantes.6​
                
                En 2003 participó en la Copa FIFA Confederaciones representando a la Conmebol como campeón de América del Sur; en esa sexta edición realizada en Francia, Colombia alcanzó el cuarto lugar.
                
                Ha competido cinco veces en Juegos Olímpicos, por primera vez en 1968, realizados en Ciudad de México.
                
                Fue invitado en tres ocasiones a la Copa de Oro de la Concacaf, torneo oficial de la confederación de Norte, Centroamérica y el Caribe. En el año 2000, cuando participan por primera vez, logran el subcampeonato.7​
                
                Entre los jugadores más destacados están el mediocampista Carlos Valderrama (considerado uno de los mejores jugadores de la historia de Colombia, ocupa el 39.º lugar en el ranking del mejor jugador sudamericano del siglo XX publicado por la IFFHS en 2004), el centrocampista Marcos Coll (autor del único gol olímpico anotado en una Copa Mundial de Fútbol), el portero René Higuita (elegido por la IFFHS como el octavo mejor golero sudamericano del siglo XX en 2004 y recordado por la jugada del Escorpión), los delanteros Faustino Asprilla (ocupó el sexto lugar en la elección del Jugador Mundial de la FIFA 1993), Radamel Falcao García (elegido quinto mejor jugador del mundo en 2012, según la votación del FIFA Balón de Oro 2012), James Rodríguez (Ganador de la Bota de Oro en la Copa Mundial Brasil 2014) y el portero Farid Mondragón (quien posee el récord como el jugador más longevo en disputar una Copa Mundial de Fútbol).
                
                En varias ocasiones se ha encontrado dentro de las diez mejores selecciones del mundo en la Clasificación mundial de la FIFA. Su máxima posición la ha conseguido durante los meses de julio y agosto de 2013,8​9​ de igual manera, desde septiembre de 2014 hasta abril de 2015,10​11​ cuando se ubicó en la tercera posición.</p>
    </div>
    <a href="http://www.losmundialesdefutbol.com/selecciones/colombia_seleccion.php" >estadisticas de colombia en los mundiales</a>

    <img src="https://cdn.memegenerator.es/descargar/17419493">
    

   
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T" crossorigin="anonymous"></script>
</body>
</html>
