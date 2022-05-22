Vector-role
=========

Роль для Ansible 2.10 и новее для установки Vector на ОС CentOS.

Requirements
------------

Роль работает только на дистрибутиве CentOS.
В файле конфигурации vector (vector.toml) необходимо указать адрес сервера базы данных clickhouse. 

Role Variables
--------------

vector_version - Версия Vector

Dependencies
------------

Иные зависимости не требуются. 

Example Playbook
----------------

Пример использования:

---
- name: Install vector
  hosts: all
  roles:
    - vector-role

License
-------

MIT

Author Information
------------------

[Git](https://github.com/zMaAlz/vector-role)

