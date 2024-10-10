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
