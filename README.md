# Ansible Collection - netology.yandex_cloud_elk

---
## Документация к коллекции

---
Учебная коллеция:
----------

Содержит [модуль](my_own_namespace/yandex_cloud_elk/plugins/modules/my_own_module.py) создания файла.

---

**roles/my_single_role**:
-----------

    Моя учебная роль
---

roles/my_single_role/default:
------------
    path - путь до файла.
    content - содержимое файла. 


---
Пример использования роли:

```bash
---
- name: Local Test
  hosts: localhost
  roles:
    - my_own_namespace.yandex_cloud_elk.my_single_role
```

---

Лицензия:
------


MIT

---
Автор:
------
[EgorkinAleksandr](https://github.com/sash3939) 
