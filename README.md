Домашнее задание №5 "Стенд Vagrant для NFS"

Цель: развёртывание сервиса NFS с использованием Vagrant и Ansible и подключение к нему клиента

I. Создание стенда

В предлагаемом Vagrantfile создаются две виртуальные машины: nfss(сервер ip 192.168.50.10) и nfsc(клиент ip 192.168.50.11)

При старте обоих ВМ для установки необходимого ПО и настройки ВМ используется ansible.
Структура каталога проекта:

![Вывод команды tree](https://github.com/DmitryV81/HW5_nfs_v2/blob/main/ansible.JPG)
