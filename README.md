# Плагин !!!КРАСАВИЧК!!!

### Автор:  Талдыкин Григорий Александрович, группа М3120

## Описание

Этот плагин предназначен для демонстрации базового принципа работы с API выбранной IDE и вывода сообщения "!!!КРАСАВЧИК!!!" в консоль. 

## Возможности

- Выводит сообщение "!!!КРАСАВЧИК!!!" в консоль IDE.
- Демонстрирует основу архитектуры плагина и его взаимодействие с IDE.


## Использование

После установки плагина выполните следующие шаги, чтобы увидеть сообщение "Hello, World!" в консоли IDE:
1. Откройте консоль.
2. Выполните команду !!!КРАСАВЧИК!!! (или используйте доступ к плагину через меню или горячие клавиши, если таковые настроены).
3. В консоли IDE должно появиться сообщение "!!!КРАСАВИЧК!!!".

## Архитектура

Данный плагин разработан на основе API выбранной IDE, поддерживающего интеграцию сторонних инструментов. Основные компоненты плагина включают:

- Точка входа плагина: Определяет основной класс, отвечающий за инициализацию и завершение работы плагина.
- Функциональность вывода сообщения: Метод, который выполняется при запуске плагина и выводит "!!!КРАСАВИЧК!!!" в консоль.
  
Процесс интеграции плагина с IDE включает инициализацию точек входа плагина через API IDE, что позволяет подключать сторонние инструменты.

## Требования

- Версия IDE: Убедитесь, что используемая версия поддерживает плагины.
- JDK версии 11+
