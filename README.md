php
=========

Ansible role for downloading Php source archives to the control server, then extracting them to the target host.

Role Variables
--------------
Set the ```php_version``` parameter to install other versions of Php

        php_version: 7.0.11
        
Available versions:

    7.1.0RC3
    7.0.11
    5.6.26

Set the ```prefix``` parameter to install somewhere other than ```opt/php```

        prefix: "opt/php"
        
License
-------

MIT

Testing
-------
Run the following command:

        ansible-playbook php/tests/test.yml

