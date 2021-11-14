# Запуск ansible

* Установка ansible

```sh
brew install ansible
```

* Установка пакетов

```sh
ansible-galaxy install geerlingguy.docker
```

* В файле invenory меняем наши хосты

* Запускаем ansible

```sh
ansible-playbook ./playbook.yml -i=./inventory
```
