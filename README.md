# Course Platform (Monorepo)

Монорепозиторий курса: отдельные сервисы + инфраструктура + документация.

## Структура
- services/ — микросервисы (каждый сервис — отдельный модуль)
- infra/ — инфраструктура (gateway, monitoring)
- compose/ — сборки окружений (dev/prod)
- docs/ — документация курса и проекта

## Базовые правила
- Все изменения — через pull request
- Каждый сервис имеет /health и /version
- Конфигурация — через env

не могу папки закинуть
<img width="1118" height="292" alt="image" src="https://github.com/user-attachments/assets/c86315b1-60d0-4f01-b111-368bb624b1ae" />
