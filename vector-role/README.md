Vector-role
=========

Роль для установки Vector на ОС CentOS.

Requirements
------------

Роль работает только на дистрибутиве CentOS.
В файле конфигурации vector (vector.toml) необходимо изменить адрес сервера базы данных. 

Role Variables
--------------

vector_version - Версия Vector

Dependencies
------------

Иные зависимости не требуются. 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - name: Play name 
    hosts: servers
    roles:
      - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

[Git](https://github.com/zMaAlz/vector-role)

