# Vector-role
## Переменные
--------------
| Переменные  |  Описание|
|:-----|:----|
| vector_version | Версия для установки |
| vector_user    | Имя пользователя
| vector_group   | Группа |
| vector_bin_path | Каталог программы |
| vector_exec_name | Исполняемый файл |
| vector_log_output | Журнал логов |
| vector_data_dir | Каталог с данными |

Example Playbook
----------------

```yml
    - name: Install Vector
      hosts: servers
      roles:
        - vector-role
```

## Лицензия
MIT

## Автор
Иван Селезнев
