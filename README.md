# Проект для тестирования docker

Данный репозиторий предназначен для тестирования сборки сервера на docker-compose конфигурации.

# Состав

В проекте находится:
 - backend на порту 3001 который ждёт ображения по route "http://localhost/api"
 - frontend на порту 3000 в /src/app.js которого прописано ждать data с responce
 
 В frontend\package.json прописан proxy на порт backend.