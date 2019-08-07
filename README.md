# ceres-backend

## Запуск
Для запуска проекта в режиме разработки необходимо:
  - запустить команду ```npm install```
  - в файле .env заполнить APP_KEY строкой из 32 символов (можно воспользоваться [онлайн генератором](http://www.unit-conversion.info/texttools/random-string-generator/))
  - запустить команду ```docker-compose up -d``` Эта команду запустит MariaDB сервер. Если не используется docker, необходимо самостоятельно установить MariaDB сервер.
  - запустить команду ```npm run dev```

После это проект будет доступен по адресу [http://localhost:4000](http://localhost:4000)

База данных будет доступна локально на порте 4001

Порты можно изменить в файле .env
