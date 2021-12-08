# Ansible Collection - my_own_namespace.yandex_cloud_elk

Коллекция содержит модуль `my_own_module` и роль `my_own_role`.

Модуль `my_own_module` реализует задание по созданию файла с заранее определенным содержимым. 
Параметры модуля:
`path` - путь до файла
`content` - содержимое файла


Роль `my_own_role` содержит в себе один так по вызову модуля `my_own_module` с заранее определенными переменными:
`my_own_role_path` передается в параметр `path` модуля `my_own_module`, значение по умолчанию: /tmp/my_own_module.txt
`my_own_role_content` передается в параметр `content` модуля `my_own_module`, значение по умолчанию: Default string for role my_own_namespace.yandex_cloud_elk.my_own_module
