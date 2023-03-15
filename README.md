# TaskManagerPackage

**TaskManagerPackage** - это пакет программ, позволяющий реализовывать объекты задач и менять их состояния относительно выполнения.
Задачи разделяются на простые и сложные, сложные обладают дополнительным функционалом - срочностью. 
Просроченные задачи отмечаются розовым цветом.

В проекте используются следующие шаблоны проектирования:
- Decorator

## L2M3 Home Work

- Выделение бизнес логики приложение в отдельный программный пакет. 

## Getting Started

```
cd ~/Developer
git clone https://github.com/some/TodoList.git
cd ./TodoList
xed .
```
## Features

- Реализация прострых задач;
- Реализация сложных задач;
- У важных задач есть 3 варианта приоритета: высокий, средний и низкий;
- Реализация сортированных по приоритету массивов задач.
- Возможность менять состояние выполненности задач.
- Подсветка просроченных задач.

## Требования

- Написано на Swift 5;
- Поддерживается версия iOS 14;
- Зависимостей от сторонних библиотек нет;
- Необходим Xcode 14 или выше.

## В планах

- Написать тесты
