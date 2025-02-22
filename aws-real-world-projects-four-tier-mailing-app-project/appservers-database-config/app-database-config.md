## Create a Database config file in the application servers 
vi dbinfo.inc

## Copy and Past the Below Data in the file after updating
```bash
<?php

define('DB_SERVER', 'prod-database.cn6m60a826nk.us-east-1.rds.amazonaws.com');
define('DB_USERNAME', 'admin');
define('DB_PASSWORD', 'admin12345');
define('DB_DATABASE', 'phpappdatabase');

?>
```