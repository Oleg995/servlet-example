# Сервлеты

## Ссылки

* [Документация Tomcat](http://tomcat.apache.org/tomcat-8.5-doc/api/index.html)
* [Сервлеты и контейнеры сервлетов](https://www.baeldung.com/java-servlets-containers-intro)
* [курс Протокол HTTP](https://ru.hexlet.io/courses/http_protocol)

## WelcomeServlet.java

## Задачи

* Реализуйте сервлет, который принимает *GET* запрос и в ответ отправляет строку `Hello, Hexlet!`.

## App.java

Класс `App` содержит метод `getApp()`, который принимает на вход порт на котором должен работать сервер и возвращает инстанс контейнера сервлетов *Tomcat*.

## Задачи

* Зарегистрируйте в контейнере сервлет `WelcomeServlet`, так чтобы он обрабатывал запросы по корневому пути `/`.

* Для проверки работы приложения запустите сервер, используя команду `make start`. Откройте приложение в браузере по адресу *http://localhost:5000* и проверьте что на странице выводится текст `Hello, Hexlet!`.
# servlet-example
