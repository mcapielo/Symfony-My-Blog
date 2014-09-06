#Symfony-My-Blog
===============

##Symfony2 Blog


##Installing

1. Clone the repository
2. Change 'app/config/parameters.ini' with your user and pass for Mysql database. 
3. Create the database with 'php app/console doctrine:database:create'
4. Update schema with 'php app/console doctrine:schema:create'
5. Load fixtures with 'php app/console doctrine:fixtures:load'


** Note: You have to install sqlite3 ( With Ubuntu... apt-get install php5-sqlite ).
