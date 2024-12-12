---
layout: post
title: "Тест Mermaid диаграмм"
date: 2024-11-23
---

# Тестирование Mermaid диаграмм

Пост должен был быть про диаграммы, но на самом деле он про Windsurf Editor.
По умолчанию Github Pages не показывает диаграммыв формате Mermaid.
Поэтому я как раз решил попробовать работу нового AI редактора кода.

Просто попросил его добавить такую функциональность в мой блог на github и...барабанная дробь...он всё сделал.
Я по прежнему не разбираюсь в программировании, поэтому для меня это отличный вариант решения.


Ну и да, ниже дефолтный текст, который AI подсунул для примера.

Ниже представлена простая диаграмма последовательности:

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

Вы также можете создавать другие типы диаграмм, например, блок-схемы:

```mermaid
graph TD
    A[Начало] --> B{Условие}
    B -- Да --> C[Действие 1]
    B -- Нет --> D[Действие 2]
    C --> E[Конец]
    D --> E
```
