# Playbook для задания 08-ansible-02-playbook

Данный playbook устанавливает:  
1. Clickhouse, запускает его демон, а также создаёт базу "logs";
2. Vector и запускает его демон.

Переменные доступные для изменения в group_vars:
1. clickhouse_version;
2. clickhouse_packages.