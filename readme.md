# Title Here 
 
You can add a README file to a repository to communicate important information about your project. A README, along with a repository license, citation file, contribution guidelines, and a code of conduct, communicates expectations for your project and helps you manage contributions.
 
<br><br>
 
 

 
 
##  **Installation of Database**
 
1. Create your database schema on **_phpmyadmin_**.
 
2. Add table and columns that you need.
 
3. Goto your project setup your database connection.
4. Create config file "**_config.php_**".
 
   ```
    <?php
 
   	define('ROOT_URL', 'http://localhost/REDEMPLE/logApp-scaling-octo');
   	define('DB_HOST', '"localhost');
   	define('DB_USER', 'Your database user');
   	define('DB_PASS', 'Your Database Password');
   	define('DB_NAME', 'Your Database Name');
 
      ?>
   ```
 
5. Create "**_db.php_**" file and paste this code.
 
```
<?php
 
// Create Connection
$conn = mysqli_connect(DB_HOST, DB_USER, DB_PASS, DB_NAME);
 
// Check Connection
if(mysqli_connect_errno()){
// Connection Failed
echo 'Failed to connect to MySQL '. mysqli_connect_errno();
}
 
?>
```
 
<br><br>
 
## **Author** 
 
## <img src="12.jpg" alt="me" style="width:500px;"/>
 
### Bautista, John Paul P.
 
#### BSCS3 - B1