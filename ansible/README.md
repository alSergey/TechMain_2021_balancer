# Запуск ansible

* Установка ansible

```sh
brew install ansible
```

* Установка пакетов

```sh
ansible-galaxy install geerlingguy.docker
ansible-galaxy install geerlingguy.nginx
ansible-galaxy install geerlingguy.nodejs
ansible-galaxy install geerlingguy.go
```

* В файле invenory меняем наши хосты

* Запускаем ansible

```sh
ansible-playbook ./playbook.yml -i=./inventory
```
