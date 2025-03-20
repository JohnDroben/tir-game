Тир (Apple Shooting Game)
Добро пожаловать в игру «Тир»! 
Это простая игра на Python с использованием библиотеки Py



![2025-03-20_22-42-58](https://github.com/user-attachments/assets/15250f53-7352-46fa-afd3-d765638c3230)



Содержание
Описание
Установка
Как играть
Структура проекта
Лицензия
Описание
Игра «Тир» создана для развлечения и обучения основам работы с библиотекой Pygame. Она демонстрирует базовые принципы программирования игр, такие как:

Обработка событий мыши.
Работа с графикой.
Генерация случайных чисел.
Управление игров
Цель игры — мышкой попасть по яблоку

Установка
Требования
Для запуска

Python 3.6 или выше
Библиотека Pygame (pip install pygame)
Шаги для установки
Клонируйте репозиторий:https://github.com/JohnDroben/tir-game.git

Установите зависимости:
pip install -r requirements.txt (если файл requirements.txt отсутствует),
pip install pygame
Запустите игру: python main.py
Как играть:
Запустите игру, выполнив команду python main.py.
На экране появиться яблоко.
При попадании:
Яблоко переместится на новую случайную позицию.
Цвет фона изменится.
Игра продолжается бесконечно, пока вы не закроете окно.

Структура проекта
Проект организован следующим образом:

project-folder/
├── img/
│   ├── apple.png       # Изображение яблока (цель)
│   └── icon.png        # Иконка игры
├── main.py             # Основной файл игры
├── README.md           # Документация проекта
└── requirements.txt    # Список зависимостей (опционально)
Файлы:
main.py: Главный файл игры, содержащий весь код.
img/apple.png: Изображение яблока, используемое как цель.
img/icon.png: Иконка игры, отображаемая в заголовке окна.
README.md: Документация проекта.
requirements.txt: Список зависимостей для установки через pip.
Лицензия
Этот проект распространяется по лицензии MIT License . Вы можете свободно использовать, изменять и распространять этот код, сохраняя при этом упоминание об авторстве.
