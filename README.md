# TodoApi — Записная книжка / Список задач на ASP.NET Core

Простое веб-приложение (Web API) для управления заметками/задачами с базовыми CRUD-операциями.

## Технологии
- ASP.NET Core
- C#
- Entity Framework (или in-memory для простоты)
- REST API (GET/POST/PUT/DELETE)

## Основные файлы
- Todo.cs — модель задачи
- TodoItemDTO.cs — DTO для передачи данных
- TodoDb.cs — контекст данных
- TodoApi.http — примеры запросов для тестирования

## Как запустить
1. `dotnet restore`
2. `dotnet run`
3. Открыть в браузере / Swagger или через .http-файл

Проект создан для демонстрации базовых навыков backend на C#.
