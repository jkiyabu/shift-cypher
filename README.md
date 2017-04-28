
# Shift Cypher
-------------
A site made with Drupal where a user can encrypt a message by shifting each letter in that message a desired direction and amount.

## Installation
--------------
* Clone repository
* Set home directory as document root in MAMP web server
* Import dbase shift_cypher.sql.zip from "sites/all/db-backup" using php myadmin
* Create "cypher" user for database with password also set to "cypher"
* Browse to localhost:8888
* Log in as username "cypher" and password "cypher"

## Planning
----------
* Create link to form in menu
* Create form with 3 inputs - shift direction, shift amount, phrase
* Redirect to second page to show a result
* Add phrase encryption
* Add form validation

## License
---------
MIT license
Copyright(c) 2017 Jayeson Kiyabu All Rights Reserved
