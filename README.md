Указать данные сервера для развертывания Redmine в `inventory.yml`

Перед запуском деплоя установить зависимости:
`ansible-galaxy install -r requirements.yml`

Запустить playbook:
`ansible-playbook -i inventory.yml redmine-deploy.yml --ask-become-pass`

Проверка:
Открыть в браузере `https://80.74.29.73:8443`
