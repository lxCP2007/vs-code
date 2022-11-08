la carpeta src es donde se guarda la estructura del codigo fuente del programa

Para guardar el atajo en el teclado es ctrl+s


************************************** BARRA DE ESTADO ********************************

Es la barra que se encuentra en la parte interior de la pantalla y en ella se muestran herramientas que hacen referencia al estado de los elemetos con loos que se esta interactuando.

Indicadores de Error:
    En la parte derecha estan los indicadores de error, ellos notifican se se encuantra algun error o alguna advertencia en el codigo 

Ln y col:
    En la zona derecha existe otras herramientas, la primera es "Ln y col", ambas representan la columna y linea respectivamente en la que se encuentra en cursor en ese mometo. Se puede desplegar un buscador el cual permite dirigir el buscador al la linea y colimna que se desee, esto se hace clickendo en Ln, Col escribiendo primero el numero de linea una coma y despues la columna correspondiete

Spaces:
    La siguente herramienta es "spaces:" esta muestra el como se esta manejando la separación del codigo en el proyecto, al clickear en este se habre un buscador que permite cambiar la configuración de los espacios. La configuración por defecto es 4, es decir en base a 4 espacios, por lo tanto al undir tab este aplicara una distancia igual a cuatro espacios

Codofocación:
    Luego sigue el indicador de la codificación con la que se esta trabajando, la de defecto es UTF-8 ya que es la mas popular en internet

Saltos de linea del Sistema:
    Despues sigue un indicador que dice "CRLF" este hace referencia al como el sistema operativo traspasa los saltos de linea al binario para que la computadora lo interprete, es relevante tenerlo en cuanta ya que si algun compañero trabaja en un sistema operativo diferente, estos saltos de linea se manejan dijerente, por lo tanto son detalles de compativilidad que de no tenerse en cuenta producirian errores en la aplicación 

Tipo de archivo:
    Siguente esta el indicador del tipo de archivo en el que se esta trabajando, de ser necesario se puede modificar el leenguaje clickeando en este, lo que desplegara una lista con todos los leenguajes que soporta vs code


**************************************** Barras de Actividades *****************************************

Explorador de archivos:
    Su función es la de explorar los repositorios y abrir una carpeta o un archivo en especifico, para serrar la carpeta se usa la opción "close folder" del menú "file"

Buscador:
    Es la segunda herramienta y se utiliza para realizar busquedas detalladas dentro del proyecto:
        -Filtrar mayusculas: 
            Se pueden filtrar la busqeuda segun las mayusculas utilizando la opción de match case, esta se activa undiendo el icono de "Aa" que esta en el lateral del cuadro de texro.
        -Buscar palabras con exactitud: 
            Se pueden buscar palabras en especifico clickeando el icono de "ab" que se ancuentra en el cuadro de texto, esta filtra la busqueda de modo que solo ubique la palabra exacta que se necesite.
        -Remplazar palabras:
            Se puede hacer luego se realizar la busqueda de la palabra que sera remplazada, la que la sustituira se ingresa en el cuadro de texto secundario que dice "Replace", luego se confirma el cambio a realizar
    
Control de verciones:
    Es la herramienta que nos ayuda a utlizar Git desde Vs Code, al inicializar un reoisitorio:
        -El cuadro de texto:
            Es para escribir el mensaje de registro del commit  
        -Boton commit: 
            Ejecutara en commit y se puede alternar entre commit push y commit Sync 
        -Lista de status:
            Es donde se muestran los archivos del repositorio y los cambios que se han hecho

    Herramientas De archivos:
        -Open file:
            Es el primer icono de izquierda a drecha, abre el archivo
        -Discard Changes:
            Es la segunda herramienta y es para descargar los cambios del archivo
        -Stages:
        Es la tercera herrramienta, tiene el icono de una cruz, se usa para selecionar los documentos cuyos cambios se enviaran en el commit 
        
    Usar Git desde Vs code:
        -Subir un repositorio GitHub:
            despues de selecionados los cambios y archivos que se enviaran en el summit, e iniciada la seción y configurado git, se unde en publish Branch para enviar los archivos al GitHub.
    Crear una rama in GitHub:
        -Para crear una desde 0 se puede clickear en el icono de tres puntos (Más aciones) que se encuentra en alado de "SOURSE CONTROL", en la parte superior de del meú de la herramienta de control de verciones, dentro de este se busca la opción de "Branch" y dentro de ella la opción de "create branch" 
        
        -El indicador de la ubicacón del repositorio en la que nos encontramos trabajando, se encuentra en la barra de estado en la esquina inferior izquierda de la pantalla, clickeandolo despliega un listado de las ramas del repositorio, tambien permite crear una nueva rama de forma rapida.

    Pasar los datos de un rama al Master:
        -Se clickea el indicador de ubicación git, nos movemos al master y en este clickeamos el icono de tres puntos del menú del control de verciones, buscamos la opcion "Branch" y luego la que se llama "Merge Branch", se seleciona la rama deseada y con esto el se pueden visualizar los cambios en master, para confirmar los cambios clickeamos Sync changes y de esa forma se junta una rama co el master 