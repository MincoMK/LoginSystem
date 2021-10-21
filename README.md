# LoginSystem
## Usage
You can analyze my code. Please understand that I made this code when I was VERY NOOB CODER!
### Database Installation
I made this code with MySQL database. Please use it.  
Create `db.php` at the project root.
```php
<?php
define("__ROOT__", $_SERVER['DOCUMENT_ROOT']);
ini_set("display_errors", 1);
ini_set("display_startup_errors", 1);
error_reporting(E_ALL);
return mysqli_connect("<Address>", "<ID>", "<PW>", "<DB>");
?>
```
