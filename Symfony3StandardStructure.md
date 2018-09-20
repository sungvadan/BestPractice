Symfony's standard structure
----------------------------

* app/
    * config/
        * config_dev.yml 
        * config_prod.yml 
        * config_test.yml 
        * config.yml
        * parameters.yml 
        * parameters.yml.dist
        * routing_dev.yml 
        * routing.yml
        * security.yml
        * services.yml
     * AppKernel.php
     * AppCache.php : the HTTP Proxy cache you can use in your web entry point
     * autoload.php
     * Resources/
        * views
        * translations
* bin/
* src/
    * AppBundle/
        * Command/
        * DependencyInjection/
        * Document/ Doctrine ODM documents (when not using annotations)
        * Controller/
        * Entity/
        * Repository/
        * EventListener/
        * Security
        * Resources/
            * config/
            * views/
            * translations/
        * Tests/
        * AppBundle.php
* tests/
* var/
* vendor/
* web/
        