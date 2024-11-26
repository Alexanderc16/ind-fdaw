# Описание проекта:

Это CRUD-приложение для управления товарами, построенное на Java с использованием Spring Boot. Оно включает REST API для создания, чтения, обновления и удаления товаров. Данные сохраняются в памяти с использованием H2 Database (можно заменить на любую другую СУБД).

# Технологии:

Backend: Java, Spring Boot

База данных: H2 (встроенная), JPA/Hibernate

Валидация: Hibernate Validator (Bean Validation)

Документация API: Swagger/OpenAPI (Springdoc)

# Чтобы запустить:
mvn clean spring-boot:run

# Структура проекта:
<b>application.properties</b> - Конфигурация базы данных и сервера Spring Boot.

<b>ProductCrudApplication.java</b> - Главный класс приложения Spring Boot.

<b>Product.java</b> - Модель данных для товара. Представляет сущность Product, используемую в базе данных и в приложении.

<b>ProductController.java</b> - REST-контроллер для обработки HTTP-запросов, таких как создание, чтение, обновление и удаление товаров.

<b>ProductRepository.java</b> - Интерфейс репозитория Spring Data JPA для работы с базой данных.

<b>GlobalExceptionHandler.java</b> - Глобальный обработчик ошибок для обработки исключений, таких как ошибки валидации.

<b>data.sql</b> - Тестовые данные для Базы Данных

<b>pom.xml</b> - Maven-конфигурация для добавления зависимостей.