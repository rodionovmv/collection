# Ansible Collection - my_netology.my_collection

* namespace: my_netology
* name: my_collection
* version: 1.0.0
* readme: README.md
* authors: Mikhail Rodionov
* description: This is a test role for ansible-collection
* repository: https://github.com/rodionovmv/collection

О роли:

My_role
=========

Роль для тестирования коллекций ansible

Requirements
------------

Тестирование осуществлялось на ubuntu 20.04 

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| test_path | "/tmp/test_file.txt" | Параметр, определяющий путь для нового файла, а также имя нового файла |
| test_content | "Test module in task\nHello, netology!\n" | Строка, которая записывается в новый файл |
