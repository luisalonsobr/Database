# PHP-PDO-Wrapper-Class
An extension for PHP's PDO class designed to make running SQL statements easier. Based on http://www.imavex.com/php-pdo-wrapper-class/
Project Overview

This project provides a minimal extension for PHP's PDO (PHP Data Objects) class designed for ease-of-use and saving development time/effort. This is achived by providing methods - delete, insert, select, and update - for quickly building common SQL statements, handling exceptions when SQL errors are produced, and automatically returning results/number of affected rows for the appropriate SQL statement types.
System Requirements

    PHP 5
    PDO Extension
    Appropriate PDO Driver(s) - PDO_SQLITE, PDO_MYSQL, PDO_PGSQL
    Only MySQL, SQLite, and PostgreSQL database types are currently supported.

Checkout index.php and class.db.php for more info. 
