ZoopUrl Router Module
=================

Installation
------------

Go to your Zend Applications module directory then run

    git clone https://github.com/cj-ines/cZoopUrl.git
    cd ..
    php composer.phar self-update
    php composer.phar require doctrine/doctrine-orm-module": "0.7.*
    
Edit your application.config.php

    return array(
      'modules' => array(
      // ..
        'DoctrineModule', // add
        'DoctrineORMModule', // also this
    	  'CzoopUrl' // of course this also
      // ..

Copy doctrine.local.php to config/autoload/ 
Edit the ff 

       'host'     => 'database-host',
       'port'     => '3306',
       'user'     => 'root',
       'password' => 'password',
       'dbname'   => 'database',
