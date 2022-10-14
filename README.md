# Playbook для задания 08-ansible-02-playbook

Данный playbook устанавливает:  
1. Clickhouse, запускает его демон, а также создаёт базу "logs" + Vector и запускает его демон на серверы "clickhouse";
2. Vector и запускает его демон на серверы "vector";
3. Lighthouse + Nginx на серверы "lighthouse".

Переменные доступные для изменения в group_vars:
1. clickhouse_version;
2. clickhouse_packages.