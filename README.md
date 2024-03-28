# Телефонный справочник

Простое приложение для управления контактами в телефонной книге.

## Описание

Программа "Телефонный справочник" представляет собой приложение для управления контактами. Она позволяет добавлять, просматривать, редактировать и удалять контакты, а также экспортировать и импортировать данные.

## Инструкция по установке и запуску

1. Клонируйте репозиторий на свой компьютер:

```bash
git clone https://github.com/your-repository.git
```

2. Установить необходимые зависимости:

```bash
pip install -r requirements.txt
```

3. Запустить приложение:

```bash
python main.py
```

## Зависимости
Python 3.x
sqlite3
tkinter

## Использование

- Добавляйте новые контакты, указывая имя и номер телефона.
- Удаляйте контакты по их идентификатору.
- Просматривайте список всех контактов в телефонной книге.

## Структура проекта для телефонного справочника:

1. main.py: Главный файл приложения, который запускает GUI и основную логику.
2. gui.py: Модуль для создания графического интерфейса.
> * Отвечает за отображение пользовательского интерфейса и взаимодействие с пользователем.
> * Используйте библиотеку Tkinter, PyQt или другие для создания графического интерфейса.

data_storage.py: Модуль для работы с хранилищем данных.
> * Отвечает за хранение информации о контактах.
> * Может быть реализовано с использованием базы данных (например, SQLite) или файловой системы.

data_handler.py: Модуль для работы с данными (CRUD операции).
> * Реализует основной функционал (просмотр, сохранение, импорт, поиск, удаление, изменение данных, слияние).
> * Включает методы для выполнения операций над контактами (добавление, удаление, обновление, поиск и т.д.).

import_export.py: Модуль для импорта и экспорта данных.
> * Отвечает за импорт и экспорт контактов из/в различные форматы (например, CSV, JSON).