# 🔄 CI/CD для сервиса отслеживания посылок

GitHub Actions workflow для автоматического тестирования и публикации Docker-образа в DockerHub.

## 🔧 Что сделано

- **Job 1:** Проверка кода и запуск тестов при push и pull request
- **Job 2:** Сборка и публикация Docker-образа при добавлении тега

## 🛠️ Стек

- Golang
- SQLite
- Docker
- GitHub Actions

## 🚀 Workflow

| Триггер | Действие |
|---------|----------|
| `push`, `pull_request` | Тестирование |
| `tags: v*` | Публикация в DockerHub |

