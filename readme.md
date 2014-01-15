wall-script is a lightweight social network script

Requirements

* PHP 5.3 or higher
* MySQL server

[Contact](mailto:mail@jefcarlier.nl) me for any questions.

## Install Instructions

This script is OS independend
`.httacces` included for Apache
`web.config` incuded for IIS

First, clone this repository as you normally would.

    $ git clone https://github.com/JefCarlier/wall-script

Next, Upload the contents to a webserver of your choice (Apache or IIS recommeded)
    
Create a new MySQL database with a name of choice and execute `wall-script.sql` to import table structure.

Then edit the database configuration located in `/includes/database.php`