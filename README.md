## starter3.1

This project can be used as a starter for a webapp built with CodeIgniter 3.1.

The [user guide](http://www.codeigniter.com/user_guide/) can be accessed online,
and is not bundled here.

Additionally, **index.php** has been moved to a **public** folder, and an
**.htaccess** file added there, for improved security. 

**index.php** has been modified to reference the correct relative location 
of CodeIgniter's **system** and **application** folders.
The **application/config/config.php** settings have been modified with
defaults for the *base_url* and *index_page* config settings.

Configure your web server or virtual host so that your project's
document root maps to this **public** folder inside your project.

If you wish to run your app from the command line, for testing,
then the following, from your project root, would run it on port 8000:

    cd public
    php -S localhost:8000

##Installation

This project is meant to be composer-installed:

    composer create-project codeigniter/starter3.1
    composer update

Updates to the framework can then be incorporated with

    composer update
