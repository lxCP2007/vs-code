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
        -Se clickea el indicador de ubicación git.

        -Nos movemos al master y en este clickeamos el icono de tres puntos del menú del control de verciones, 

        -Buscamos la opcion "Branch" y luego la que se llama "Merge Branch", se seleciona la rama deseada y con esto el se pueden visualizar los cambios en master.

        -Para confirmar los cambios clickeamos Sync changes y de esa forma se junta una rama co el master 

    Borrar una Rama:
        -Se clickea el icono de tres puntos de menú control de verciones

        -Buscamos la opcion "Branch" y luego la llamada "Delet Branch", esto procede a mostrar las ramas existentes 

        -Seleccionamos y borramos la rama deseada.

Depurador:
    Iniciarlo:
        -Se clickea en el cuarto icono de la barra de actividades

        -Precionamos el boton que de inicio (Run and Debug),

        -Selecionamos el navegador con el que haremos el testeo, y el depurador empezara a ejecutar el codigo, para que todo se lleve a cabo adecuadamente, al momento de activarlo se tiene que estar dentro del archivo HTML correspondiente al codigo que deseamos ejecutar, ya que de lo contrario no se visualizara nada

        -Herramientas de control:
            En el lateral izquierdo se visualizaran todos las varibles, constantes y funciones locales, globales y del scrypt con las que estemos interactuando

            Para desplegar la consola es necesario clickear el segundo icono de la esquina superior derecha de la pantalla (toggle panel), este icono muestra un cuadrado sobre un rectangulo

            Es posible agragar un break point, es decir cliqueando a la izquierda del numero de linea se puede marcar un punto el cual pausara el depurador al llegar a esa linea, 

            Tambien se desplegara un menu de erramientas el cual contiene: 
                +Boton de play y pause
                +Step Over: este boton salta a la linea siguente y ejecuta el codigo de esta
                +Step Into: Si se esta ejecutando una función este boton se mete en ella para poder depurarla linea por linea 
                +Step Out: En caso de terminar o querer detener la depuración de la función se utiliza este boton
                +Boton Retry
                +Boton de Stop:  detiene el depurador 

Extenciones:
    Para descargarlas se clickea en el quito icono de la barra de actividades, esto despliega una lista de extenciones, así como un buscador para encontrar cualquier extención disponible

    Para cambiar los temas se unde Ctrl+Shif+p, lo que despliega un menu de configuraciones, el cual posee un buscador, en el cual se buca "theme" y en el resultado llamado "preferences:color theme" se despliegan todas las opciones de temas para vs Code



******************************************************* Otros ******************************************************

Atajos de teclado:
    1-La tecla "Fin": al undir esta tecla el cursor se movera al final de la linea en la que este ubicado
    2-Tecla "Inicio": Mueve el cursor al principio de la linea en la que se encuentre en ese momento
    3-Alt+flechas superior e inferior: Hace que se puede desplazar hacia arriba o hacia abajo la linea completa
    4-Ctrl+flechas laterales: El cursor se desplaza de palabra en palabra a lo largo de la linea
    5-Ctrl+flechas superior e inferior sube o baja la pantalla a lo largo del archivo
    6-Shift+flechas laterales: de esta forma se puede ir selecionando texto seguún abanza el cursor
    7-Shift+Flechas superior e inferior: seleciona lineas completas
    8-tab: añade cuatro espacios a la vez 
     9-shift+Tab: Hara un Tab pero hacia la izquierda 
    10-Ctrl+ç: abre un comentario del lenguaje que se este usando forma automatíca
    11-Ctrl+"+": añade un acercamiento a la pantalla
    12-Ctrl+"-": Aleja la pantalla
    13-Ctrl+z: deshacer el ultimo cambioç
    14-Ctrl+Espacio:Muestra las sugerencias de autocompletado
    15-Ctrl+shift+p: habre la paleta de comandos,  sepuede realizar buscaqueda de cualquier funcionalidad de vs code de forma rapida, configuracion etc.
    16-Ctrl+p: despliega un buscador de archivos del proyecto, muestra los recientes y busca por nombre
    17-Ctrl+b: retrae o abre el meú de actividad lateral
    18-Ctrl+",": abre la configuración de VS Code
    19-Ctrl+k+p: abre una lista de las pestañas que estan aviertas en este momento 
    20-Ctrl+shift+E: si el explorador de archivos esta avierto centra el foco del cursor en este, se puede navegar entre los archivos y con espacio se puede previsualizar alguno, para ingresar a alguno es con enter
    21-Ctrl+W:Cierra la pestaña actual
    22- A: Si el foco esta en el navegador de arcgivos, con undir la tecla "A" se podra crear un nuevo archivo
    23-Ctrl+Ñ: Abre y cerra el terminal

Snippets (atajos de teclado para codigos):
    1-Clickeamos en el icono de configuracón que se encuentra en el costado inferior izquierdo, selecionamos la opción llamda "Configure User Snippets".
    2-Se define el si el snippets sera global u unicamente aplicara para el proyecto
    3-Otra opción es la de escribir el leguaje en el cuadro texto, se selecionar y de esa forma se abrira el archivo en el que se registraran todos los snippets que aplicaran a ese lenguaje 
    4-El formato de codigo es el siguiente:

            "Print to console":{//esta es la refencia que se da el snipper en el autocompletado
		"prefix": "log", // prefix son los caracteres que dispararan al snippets
		"body": [//Es el que colocara el snippets en el codigo al ejecutarse 
			"console.log('$1');",// el simbolo de dolar sigifica la posicion del cursor al ejecutarse
			"$2" // esta es la segunda posicion, el numero corrsponde al numero de posocion 
		], //nota, para saltar a la sigiente posocion establecida es undiendo "tab"
		"description": "Log output to console" //descripcion del snippets
	}
}   
    5-Seguardan los cambios hechos en el archivo y de ese modo se acrtiva el Snippets
    6-De ese modo se pueden creear todos los snippets que sean necesarios
    7-Tambien se pueden descargar extenciones de snippets ya hechos para cualquier lenguaje

Atajos de teclado:
    1-Se abre el meú de "file" 
    2-Selecionamos "preferencias"
    3-selecionamos Keyboard shortcuts 
    4-O se puede usar el atajo de teclado (Ctrl+k Ctrl+s)
    5-Se abre el archivo lista de todos los atajos de sistema, aqui se pueden configurar cualquiera de ellos
    6-Buscamos la acion de la cual se desee designar o cambier un atajo
    7-Se clickea dos veces en la columna de Keybindibg, luego se presionan la combinacion de teclas deseada y se ingresa con el enter
    8-Para añadir un condicional al atajo click derecho en la columna de "When" e se seleciona la opción "Change when Expresion" o el atajo (Ctrl+k Ctrl+E)
    9-en esta configuración es necesario saber como escribir la condional para que el sistema lo entienda, no se puede escribir cualquier cosa