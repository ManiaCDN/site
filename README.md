# ManiaCDN About site & periodic checker
This project contains the about website of ManiaCDN and the periodic checking logic for updating the DNS records 
automatically when server states are changing.

**Requirements**
* Python 3.5+
* Pip
* MySQL or other Django supported database engine (Project only tested in MySQL).


## Installation
A short list of steps to get the server up-and-running.

1. Create a virtualenv
2. Install requirements
3. Create database and user.
4. Copy local_settings.default.py to local_settings.py and adjust the configuration entries.
5. Migrate (manage.py migrate).
6. Start (manage.py runserver_plus) *Use `runserver` in production*
