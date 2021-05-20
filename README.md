#command-line-interface

https://nodejs.org/en/

- npm install --save-dev nodemon
- npm install --save-dev commander

# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list

# Получаем контакт по id

node index.js --action get --id 5

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

# Удаляем контакт

node index.js --action remove --id=3

Команды:
npm start — старт сервера в режиме production
npm run start:dev — старт сервера в режиме разработки (development)
npm run lint — запустить выполнение проверки кода с eslint, необходимо выполнять перед каждым PR и исправлять все ошибки линтера
npm lint:fix — та же проверка линтера, но с автоматическими исправлениями простых ошибок
