# Ansible Playbook – Install NGINX Locally

Този проект демонстрира основна употреба на Ansible чрез инсталиране на уеб сървъра NGINX на локалната машина.

## 📁 Съдържание

- `hosts.ini` – Инвентарен файл, указващ локалния хост
- `playbook.yml` – Ansible playbook за инсталиране на nginx

## 🚀 Стартиране на Playbook

Използвай следната команда, за да стартираш Ansible playbook:

```bash
ansible-playbook -i hosts.ini playbook.yml

```

Проверяване дали nginx е изтеглен

```bash
nginx -v
```

## Link

http://localhost

