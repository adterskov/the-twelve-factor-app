# the-twelve-factor-app
Демонстрационный мастер класс по языку Go &amp;&amp; 12-Factor App

Управление модуль для проекта:
```bash
go mod init github.com/adterskov/the-twelve-factor-app
```

Синхронизировать зависимости:
```bash
go mod tidy
```

Запустить приложение:
```bash
go run cmd/app/main.go 
```

Запустить приложение, задав переменные окуржения:
```bash
PORT=8080 go run cmd/app/main.go
```

Go-линтеры:
- gocritic
- golangci-lint

https://github.com/golangci/golangci-lint

Линтеры в Go. Как их готовить. Денис Исаев

https://habr.com/ru/post/457970/

Логгеры:
- **logrus**

https://github.com/sirupsen/logrus
- zap
- zerolog

Библиотека для работы с конфигурациями:
- viper

https://github.com/spf13/viper
- envconfig

https://github.com/kelseyhightower/envconfig

Переменные в Heroku
- PORT
- DB_PORT

Запускаем Go приложение на Heroku

https://github.com/heroku/heroku-buildpack-go

Ссылка на вебинар:
https://bit.ly/3jrK6fo

Двенадцатифакторное приложение:
https://12factor.net/ru/