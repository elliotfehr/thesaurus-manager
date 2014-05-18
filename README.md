**Warning** This project is still under developement.

Open Thesaurus Manager
======================



Install
-------

    composer install
    php artisan migrate
    php artisan db:seed


Check
-----

    chmod -R 775 app/storage
    chmod -R 777 app/storage



Cli tools
---------

**Add sample data to test**

    php artisan sampledata


**Get Suggestions From thesaurus.com**

    php artisan suggestions:thesaurus <word>


**Get Suggestions From google.com**

    php artisan suggestions:google <word>


Demo
----

    email: user@localhost.com
    password: user
