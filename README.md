## Content

* [About](#about)
* [Technology](#technology)
* [Quickstart](#quickstart)
* [Project structure](#project-structure)

## About

`SportClubAttendance` — Backend приложение для автоматизации системы учета и контроля посещений спортивного клуба клиентами

## Technology

- **JDK**: `21`
- **Система сборки**: Gradle `8.14.3`
- **Фреймворки**:
    + SpringFramework `3.5.7`
- **Доп. компоненты**:
    + Spring Web
    + Spring JPA
    + H2 Database

## Quickstart

Клонирование репозитория:
   ```bash
    git clone https://github.com/dev-srpo/sportClubAttendance.git
   ```

## Project structure

```
sportClubAttendance/
├── gradle/                                         # Gradle wrapper
├── main/         
│   ├── config/                                     # Конфигурационные классы
│   ├── controller/                                 # Web-запросы
│   ├── dto/                                        # Data transfer object
│   ├── exception/                                  # Кастомные ошибки
│   ├── model/                                      # Модели данных
│   ├── repository/                                 # Обращение к БД
│   ├── services/                                   # Сервисы
│   └── SportClubAttendanceApplication.java         # Точка входа в приложение
├── test/         
│   └── service/                                    # Тесты для бизнес логики
└── build.gradle                                    # Основной файл конфигурации Gradle
```