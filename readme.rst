###################
Que es CodeIgniter
###################

CodeIgniter is an Application Development Framework - a toolkit - for people
who build web sites using PHP. Its goal is to enable you to develop projects
much faster than you could if you were writing code from scratch, by providing
a rich set of libraries for commonly needed tasks, as well as a simple
interface and logical structure to access these libraries. CodeIgniter lets
you creatively focus on your project by minimizing the amount of code needed
for a given task.

Hay que configurar en el archivo config.php la constante base_url para que apunte 
al directorio donde está el framework del codeigniter. Puede usarse con $_SERVER['HTTP_HOST']:

$config['base_url']

En el archivo autoload.php se deben setear los arrays libraries y helper con los valores:
$autoload['libraries'] = array('database','session');
$autoload['helper'] = array('url','form','html');

El archivo database.php se deben setear los valores de la variable $db['default']
con el username, password y database con los valores correspondientes