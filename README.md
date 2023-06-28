# Ansible Collection - netology.yandex_cloud_elk

---
## Документация к коллекции

---
Учебная коллеция:
----------

Содержит [модуль](plugins/modules/my_own_module.py) создания файла.

---

**roles/my_module_role**:
-----------

    Моя учебная роль
---

roles/my_module_role/default:
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