# Тестовое задание для поступления в QACloudCamp

Результаты выполнения тестового задания следует опубликовать на GitHub и отправить на почту **qacloudcamp@cloud.ru**. 
Практическое задание состоит из нескольких частей, при этом, даже если удалось решить только одну часть задания, присылайте её на рассмотрение.

## Процесс тестирования нового функционала

В Облачном сервисе хранения и обработки информации в базах данных появилась новая функциональность: можно развернуть базу данных PostgreSQL, заполнив форму в веб-интерфейсе и кликнув на кнопку создать. Обязательные поля: имя базы данных, регион размещения, размер.

Необходимо разработать стратегию тестирования нового функционала. 


### Технические требования:
- Ответ может быть представлен в свободной форме 
- На каждый вид тестирования по 2-5 кейсов

## Автоматизация тестирования API. Часть 1

Необходимо подготовить проект с автотестами, которые будут проверять работу всех API-эндпоинтов, описанных ниже.


### Технические требования:

- API url https://jsonplaceholder.typicode.com/
- Методы, требующие проверки:
GET /posts, POST /posts, DELETE /posts
- Методы могут принимать параметры userId, id, title, body
- В качестве языка программирования используйте python
- Добавьте в README инструкцию по поднятию проекта
- Используйте библиотеку requests, а также pytest


## Автоматизация тестирования API. Часть 2

Напишите Dockerfile к своему приложению по проверке API-методов из части 1.

### Технические требования:
- добавьте команду запуска в README.
