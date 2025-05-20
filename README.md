
# BulletHell (DodgeTheRock)

> 🌍 [English](#english-version) | [Русский](#русская-версия)

---

# English Version

## Description

**BulletHell** is a arcade-style bullet hell game developed using **Unreal Engine**. The project showcases key gameplay systems including randomized buff spawning, damage mitigation, and persistent high score tracking.

---

## Features

- **Buff System**
  - Buffs spawn at random among predefined spawn points on a timer.
  - Implemented Buffs:
    - 🩹 **Medkit** – restores player health.
    - 🛡 **Bubble** – grants a one-hit protective shield.
  - Buff spawn points are visually highlighted before spawn.

- **Save System**
  - Best score is saved and persists across sessions.
  - Save data is stored locally:
    ```
    C:\Users\<username>\AppData\Local\DodgeTheRock\Saved\SaveGames\
    ```

- **Performance Optimization**
  - Texture quality was manually reduced to improve performance on low-spec hardware.

- **Code Architecture**
  - Adheres to **Object-Oriented Programming (OOP)** principles.

---

## Controls

| Action          | Input          |
|-----------------|----------------|
| Move            | WASD           |
| Collect Buff    | Walk into buff |
| Survive         | Don't get hit  |

---

## Planned Features

- More buff types (e.g. Speed Boost, Damage Boost)
- UI improvements
- Sound effects and background music

---

# Русская Версия

## Описание

**BulletHell** — аркадная игра в жанре bullet hell, разработанная на **Unreal Engine**. Проект реализует ключевые игровые механики: случайный спавн баффов, механику поглощения урона и сохранение лучшего результата между сессиями.

---

## Особенности

- **Система Баффов**
  - Баффы появляются случайным образом в одной из заранее заданных **точек спавна** по таймеру.
  - Реализованные типы баффов:
    - 🩹 **Medkit** — восстанавливает здоровье игрока.
    - 🛡 **Bubble** — даёт щит, поглощающий одно попадание.
  - Точка спавна визуально **подсвечивается** перед появлением баффа.

- **Система Сохранения**
  - Игра сохраняет **лучший результат** между сессиями.
  - Файлы сохранений хранятся по пути:
    ```
    C:\Users\<username>\AppData\Local\DodgeTheRock\Saved\SaveGames\
    ```

- **Оптимизация Производительности**
  - Качество текстур **умышленно снижено вручную** для повышения производительности на слабых устройствах.

- **Архитектура Кода**
  - Соблюдены принципы **объектно-ориентированного программирования (ООП)**.

---

## Управление

| Действие        | Клавиши                 |
|-----------------|-------------------------|
| Движение        | WASD                    |
| Подбор баффа    | Подойти к баффу         |
| Цель игры       | Выжить как можно дольше |

---

## Планируемые функции

- Новые типы баффов
- Улучшение пользовательского интерфейса (UI)
- Добавление звуковых эффектов и фоновой музыки

---
