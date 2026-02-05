Указать данные сервера для развертывания Redmine в `inventory.yml`

Перед запуском деплоя установить зависимости:
`ansible-galaxy install -r requirements.yml`

Запустить playbook:
`ansible-playbook -i inventory.yml redmine-deploy.yml --ask-become-pass`
