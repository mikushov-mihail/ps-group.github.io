---
title: 'Основной проект курса: 2D игра'
subtitle: 'Цель проекта - самостоятельно написать комплексную программу, клон небольшой игры'
preview: 'img/preview/project.png'
---

## Как выбрать жанр и ограничения

Есть три популярных варианта:

1. (лёгкий) простые игры со свободным перемещением
2. (лёгкий или средний) клеточная аркадная/логическая игра
3. (средний или сложный) комплексная бродилка/платформер

## Простые игры со свободным перемещением 

Сложность разработки такой игры сопоставима с разработкой клеточной: будет меньше особенностей геймплея и разнообразия, но больше векторной алгебры и обработки столкновений. Примеры игр такого жанра:

- Flappy Bird
- Asteroids
- Snowballs
- Air Hockey
- Ping Pong
- [Осмос (Osmos)](https://ru.wikipedia.org/wiki/Osmos)

## Клеточная (аркадная или логическая) игра

Для реализации такой игры хватит базового курса по SFML и примера, в котором реализован клон PacMan. Потребуется смекалка, чтобы решить небольшие математические проблемы и организовать код.

![Скриншот](img/project/packman.png)

Примеры игр:

- Пакман (PacMan)
- [Сокобан (Sokoban)](https://ru.wikipedia.org/wiki/Sokoban)
- [Сапёр](https://ru.wikipedia.org/wiki/%D0%A1%D0%B0%D0%BF%D1%91%D1%80_(%D0%B8%D0%B3%D1%80%D0%B0))
- [Тетрис (Tetris)](https://ru.wikipedia.org/wiki/%D0%A2%D0%B5%D1%82%D1%80%D0%B8%D1%81)
- [Battle City](https://ru.wikipedia.org/wiki/Battle_City)
- Chess (Шахматы)
- Checkers (Шашки)
- Go-Moku
- Sea Battle (Морской бой)
- [Arkanoid](https://ru.wikipedia.org/wiki/Arkanoid)
- [Space Invanders](https://ru.wikipedia.org/wiki/Space_Invaders)
- [Lines](https://ru.wikipedia.org/wiki/Lines)

Известные аркадные игры зачастую имеют небольшие, но крайне важные для геймплея детали. Например, в игре "Сапёр" (Miner) мины расставляются после первого хода, поэтому проиграть в неё невозможно. Поведение привидений в классической игре PacMan настолько сложное, что удостоилось целой статьи ["Алгоритм поведения привидений в игре Pac-Man"](https://habrahabr.ru/post/109406/). Реализация таких деталей делает разработку на уровень сложнее.

## Комплексный платформер или бродилка

Для игр такого жанра требуется реализовать множество деталей:

- свободное перемещение персонажа
- враги и их интеллект
- бонусы, которые можно собирать
- статичное окружение

Такую игру писать интереснее, но потребуется гораздо больше времени и усилий, в том числе по полировке и подготовке графических ресурсов. Также потребуется прочитать большое количество статей и посмотреть большое число примеров в Интернете.

Скорее всего, будете иметь дело со следующими сложностями:

- генерация случайных чисел и связанных цепочек чисел
- обработка физики в 2D мире
- поиск пути на 2D карте
- программирование анимаций
- подготовка графических ресурсов
- программирование элементов интерфейса (меню, кнопок, индикаторов)
- программирование смены режимов игры (стартовый экран, игра, конец игры)
- программирование движения и атаки вражеских персонажей
- подсчёт урона, очков и других параметров для врагов и персонажа

Примеры игр такого жанра:

- Mario
- Doodle Jump