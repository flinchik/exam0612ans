# Exam 06.12 (Автоматизація розгортання веб-додатку) - Метод через Ansible

## Опис
Цей проект містить простий Flask веб-додаток з Redis для зберігання лічильника відвідувань. Проект автоматизовано розгортається за допомогою Docker (Docker Compose) та Ansible.

## Інструкція

### Необхідні інструменти
- Git/Github
- Docker
- Ansible
- Python 3.x

#### Встановлення Ansible - sudo apt install ansible

#### Файли додатку + requirements.txt + файли докеру (Dockerfile + docker-compose.yml) знаходяться в ansible/app.

### ВАЖЛИВО: Перед запуском проекту, не забудьте відредагувати inventory.ini в Ansible, замінивши айпі та ім'я користувача на свої дані.

### Запуск
#### 1. Запуск:
1) git clone https://github.com/flinchik/exam0612ans.git

2) cd exam0612ans

3) cd ansible

4) ansible-playbook -i inventory.ini playbook.yml

#### 2. Якщо запуск вдалий, перейдіть по http://localhost:5000 або http://YOUR-IP:5000


