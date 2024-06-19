###################
Que es CodeIgniter
###################

CodeIgniter es un framework para el desarrollo de aplicaciones en php, que utiliza el MVC. Esto 
permite a los programadores o desarrolladores Web mejorar su forma de trabajar, además de dar 
una mayor velocidad a la hora de crear páginas Webs.
El MVC o Modelo Vista Controlador es un patrón de arquitectura de software que separa la lógica 
de control, la interfaz del usuario y los datos del sistema. Para ello MVC propone la construcción 
de tres componentes distintos que son el modelo, la vista y el controlador, es decir por un lado 
define los componentes para la representación de la información y por otro lado la interacción del usuario

Hay que configurar en el archivo config.php la constante $config['base_url'] para que apunte 
al directorio donde está el framework del codeigniter. Puede usarse con $_SERVER['HTTP_HOST']:

En el archivo autoload.php se deben setear los arrays libraries y helper con los valores:
$autoload['libraries'] = array('database','session');
$autoload['helper'] = array('url','form','html');

El archivo database.php se deben setear los valores de la variable $db['default']
con el username, password y database con los valores correspondientes