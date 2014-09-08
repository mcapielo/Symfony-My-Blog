#Symfony-My-Blog
===============

##Symfony2 Blog


##Installing

1. Clone the repository
2. Change 'app/config/parameters.ini' with your user and pass for Mysql database. 
3. Run 'php bin/vendors install --reinstall' to install all the required vendors
4. php app/console cache:clear ( Check for chmod 777 on cache directory and chmod 777 cache/* -R )
5. Create the database with 'php app/console doctrine:database:create'
6. Update schema with 'php app/console doctrine:schema:create'
7. Load fixtures with 'php app/console doctrine:fixtures:load'
8. Remember to put date.timezone on your php.ini
9. Remember to point your document root to your/path/web

** Note: You have to install sqlite3 ( With Ubuntu... apt-get install php5-sqlite ).
