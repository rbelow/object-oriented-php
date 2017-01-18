# ShareBoard: Object Oriented PHP Web App

####How to intall####

1. Create a MySQL database

2. Import in your new database the **Database/shareboard.sql** file

   * If you get trouble importing the database change line 36 with:

     ```sql
     `create_date` TIMESTAMP NOT NULL DEFAULT NOW()
     ```

   * And line 61 with:

     ```sql
     `register_date` TIMESTAMP NOT NULL DEFAULT NOW()
     ```

2. Add a config.php file in the root folder with:

```php
<?php

// Define DB Params
define("DB_HOST", "localhost");
define("DB_USER", "root");
define("DB_PASS", "");
define("DB_NAME", "my-database-name");

// Define URL
define("ROOT_PATH", "/my-app-folder/");
define("ROOT_URL", "http://localhost/my-app-folder/");
```

*Enjoy!*
