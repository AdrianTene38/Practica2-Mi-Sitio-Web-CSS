# Practica2-Mi-Sitio-Web-CSS
RESULTADO(S) OBTENIDO(S):
1.	Se crea la principan la Index.html
Esta se creara bajo el modelo de DosColumnas de CSS, esta será la base para realizar las demás paginas correspondientes.


<header class="centrar_imagen">
        <div class="redondo">
            <img src="Imagenes/Captura2.JPG" alt="Ecuador " />
        </div>
    </header>

Con el siguiente código se coloca la imagen base para la página index.html
Dentro de Styles.css se encuentra los estilos que vamos dando a la imagen, títulos, párrafos, etc. Estas medidas se las debe hacer con una resolución relativa ya que si no se hace esto no se vera muy bien
 
2.	Cambios estilos H1,H2,H3
Cambios en h1,h2,h3 ya que lo solicitado es que tengan resoluciones distintas
h1{
  color: white;
    font-size: 30px;
}


h2{
  color: white;
    font-size: 30px;
}




h3{
  color: white;
}


3.	Menu Redondeado
Se solicita también que el menú sea redondeado por lo que se realiza lo siguiente:
.menu {
    background-color: brown;
    width: 10%;
    float:left;
    min-width: 120px;
    padding:2%;
    border-radius: 10%; 
    color: black;
    margin: 5px;
  }


Donde se le da un borde de 10% con un fondi Brown
 

4.	Ventana de Contactos
 <div id="contactar">
            <div>
                <label for="nombre">Ingrese_Nombre:</label>
                <input type="text" id="nombre" />
            </div>
            <div>
                <label for="telefono">Ingrese_telefono:</label>
                <input type="number" id="telefono" />
            </div>
            <div>
                <label for="msg">Comentarios:</label>
                <textarea id="msg"></textarea>
            </div>
            <div class="button">
                <button type="submit">Enviar</button>
            </div>
        </div>

#contactar {

    margin-left: 200px;
 float: left;
  }
  


label {
  display: inline-block;
  width: 200px;
  text-align: right;
  color: white;
}

input,
textarea {
  width: 350px;
  box-sizing: border-box;
}

textarea {
  vertical-align: top;
  height: 5em;
  resize: vertical;
}

.button {
  padding-left: 175px;
  color-adjust: red;
}

5.	Paginas Bien Elaboradas

      



6.	Validacion W3C Validator

      




7.	Link Git-Hub
Usuario: AdrianTene38
Link: https://github.com/AdrianTene38/Practica2-Mi-Sitio-Web-CSS




