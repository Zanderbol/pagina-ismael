 <html>
    <title>Tarjetas Graficas</title>
</html>
<div class="jumbotron">
    <h1 class="display-4">Hola Mundo!</h1>
    <p class="lead">Esto es un servidor web de cosas varias</p>
    <hr class="my-4">
    <p></p>
    <p class="lead">
      <a class="btn btn-primary btn-lg" href="file:///G:/HTML%20+%20DEBIAN/html/html%20bootstrap/Leer%20mas.html" role="button">Leer mas</a>
    </p>
  </div>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
 
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Menu Horizontal</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="https://www.muycomputer.com/2019/10/27/diez-tarjetas-graficas-interesantes-para-actualizar-un-pc-sin-arruinarte-en-el-intento/">Fuentes <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.youtube.com/watch?v=FXruzug7A54">Video Gracioso</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.google.com/search?q=tarjeta+grafica&client=firefox-b-d&sxsrf=ACYBGNSkDIb43RP6iEDi-1e7Z2zwZW_YyQ:1573296326341&source=lnms&tbm=isch&sa=X&ved=0ahUKEwj9s6HF-dzlAhURdxoKHYn9AG8Q_AUIESgB&biw=1366&bih=632">Tarjeta Grafica</a>
            </li>
          </ul>
        </div>
      </nav>
      
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
 <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="https://assets.pcmag.com/media/images/518866-nvidia-geforce-rtx-2080-founders-edition-7.jpg?width=810&height=456" alt="First slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://images-na.ssl-images-amazon.com/images/I/61EsTrsJZ5L._SX466_.jpg" alt="Second slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://images-na.ssl-images-amazon.com/images/I/71fS10HLsdL._SX466_.jpg" alt="Third slide">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>

  <a href="https://www.google.com/search?q=victoria+magistral&client=firefox-b-d&sxsrf=ACYBGNTcONTfZX4qXlg-ATBFpld0uYA1QA:1573298350619&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiNxMGKgd3lAhUvzYUKHW6yAv0Q_AUIESgB&biw=1366&bih=632"><button type="button" class="btn btn-primary">Primary</button></a>
  <a href="https://www.youtube.com/watch?v=FsfrsLxt0l8"><button type="button" class="btn btn-danger">Danger</button></a>

  <form>
        <div class="form-group">
          <label for="exampleInputEmail1">Email address</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
          <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Password</label>
          <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
        </div>
        <div class="form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label" for="exampleCheck1">Check me out</label>
        </div>
        <a href="file:///G:/HTML%20+%20DEBIAN/html/html%20bootstrap/parte%20II.html"><button type="submit" class="btn btn-primary">Enviar</button></a>
      </form>
     
  <?php
	$H= 5; 		//filas
	$V= 5; 		//Columnes
	$B= 7; 		//Bombas
	$total_casillas= $H*$V; //Guardo el total de las casillas para moverme luego en un for
	$vector;	//declaramos el vector vacio
 
 
	//vector vacio pero con todas las posiciones
	function vector_v(&$vector,$total_casillas,$V){
	$j=0;
	$p=0;
	for($i=1;$i <= $total_casillas;$i++){
		$vector[$p][$j]= "&nbsp"; //Primero dejamos las posiciones vacias para luego poner los asteriscos
			if($i % $V == 0){ //Si el modulo de $i con las columnas es 0 creamos otra fila y empezamos otra columna.
				$p++;
				$j=0;
			}else{ //Si no es l modulo segimos creand casillas de columna.
			$j++;
			}
		}
	  return $vector;
	}
 
 
 
	//Esta funcion introduce las minas aleatoriamente en el vector
	function poner_m($B,$V,$H,&$vector){
	$total=1;//usaremos esta variable para controlar que se escriban correctamente las minas.
	while($total <= $B){
	$h=rand(0,$H-1);//creamos un numero aleatorio para movernos por las filas
	$v=rand(0,$V-1);//creamos un numero para movernos por las columnas.
            if ($vector[$h][$v] == "*"){//Si en esa posición aleatoria hay un asterisco que no haga nada
 
			}else{//Si no hay un asterisco que lo ponga y que incremente el contador.
			$vector[$h][$v] = "*";
			$total++;
			}
		}
		return $vector;
	}
 
	//Esta funcion pone los números que indican las posiciones de las minas
	function poner_n($H,$V,&$vector){
 
	for($I=0;$I < $H;$I++){				//hacemos 2 fors que nos recorran el vector (columnas y filas)
		for($J=0;$J < $V;$J++){			//Tenemos 8 if's que miran las posiciones que rodean dónde nos encontremos
			 if($vector[$I][$J+1]=="*"){ //miramos si delante hay un asterisco	
				if($vector[$I][$J]=="*"){//Si lo hay, ahí no hacemos nada.
 
				}else{ 
					$vector[$I][$J]=$vector[$I][$J]+1;//Si delante a avido un número incrementamos en la posicion q estamos.
					}
			}if($vector[$I][$J-1]=="*"){//A partir de aquí es lo mismo todo el rato pero cambiando la posicion.
				if($vector[$I][$J]=="*"){//Miramos detras, arriba,abajo,etc.
 
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
			}if($vector[$I-1][$J-1]=="*"){
				if($vector[$I][$J]=="*"){
 
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
			}if($vector[$I+1][$J-1]=="*"){
				if($vector[$I][$J]=="*"){
 
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
 
			}if($vector[$I-1][$J]=="*"){
				if($vector[$I][$J]=="*"){
 
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
			}if($vector[$I+1][$J]=="*"){
				if($vector[$I][$J]=="*"){
 
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
			}if($vector[$I-1][$J+1]=="*"){
				if($vector[$I][$J]=="*"){
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
			}
			if($vector[$I+1][$J+1]=="*"){
				if($vector[$I][$J]=="*"){
 
				}else{
				$vector[$I][$J]=$vector[$I][$J]+1;
				}
			}
		}
	}
	return $vector;
}	
 
 
//Llamamos a todas las funciones para que se genere el array con el juego hecho.
vector_v($vector,$total_casillas,$V);
poner_m($B,$V,$H,$vector);
poner_n($H,$V,$vector);
 
echo "<center>";
echo "<h1><b>JUEGO DEL BUSCAMINAS</b></h1>";//Presentamos el juego
echo "Usamos $H filas, $V columnas y $B minas";
 
	echo "<table border='3'cellpadding='20'>";//Mostramos la tabla con 2 fors que hacen las columnas y las filas
	for ($i=0;$i < $H; $i++){
		echo "<tr>";
		for($j=0;$j < $V;$j++){
			echo "<td>".$vector[$i][$j]."</td>";//Aqui nos escribe el array dentro de la tabla
		}
		echo "</tr>";
	}
	echo "</table>";
 
echo "</center>";
?>

