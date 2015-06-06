correcthorse.logstash
=========

An ansible role for installing logstash.

Role Variables
--------------

| Variable				| Default			| Notes				|
| :---					| :---				| :---				|
| logstash_version			| 1.4				|				|
| logstash_indexer			| false				|				|
| logstash_shipper			| true				|				|
| logstash_input_httpd			| false				|				|

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.logstash }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)