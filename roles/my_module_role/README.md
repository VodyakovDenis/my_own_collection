# my_module_role 

Моя учебная роль

---
Учебная роль:
----------

Содержит роль создания файла.

---

default:
------------
    path - путь до файла.
    content - содержимое файла. 


---
Пример использования роли:

```bash
- name: MY Test
  hosts: localhost
  roles:
    - role: my_own_namespace.yandex_cloud_elk.my_module_role
```

---

Лицензия:
------


MIT

---
Автор:
------
[VodyakovDenis](https://github.com/VodyakovDenis) 