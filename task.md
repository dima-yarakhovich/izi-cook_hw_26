# Домашнее задание. Структура веб-приложения

### Задание

Продолжим разрабатывать приложение для рецептов. Вам необходимо создать сервис, который будет хранить рецепты и возвращать рецепты по его идентификатору.

Храниться рецепты должны в карте в формате <номер рецепта, рецепт>.

Поля класса рецепта должны содержать:

- название в формате строки;
- время приготовления в минутах в формате целого положительного числа;
- ингредиенты в формате списка объектов;
- шаги приготовления в формате списка строк.

Поля класса ингредиента должны содержать:

- название в формате строки;
- количество ингредиентов в формате целого положительного числа;
- единица измерения в формате строки.



В сервисе должны быть реализованы методы:

1. Добавление нового рецепта.

   В метод передается заполненный объект класса рецепта, который сохраняется в карте и получает свой порядковый номер.

2. Получение рецепта.

   В метод передается порядковый номер рецепта, на выходе мы получаем из карты нужный объект.


Создайте такой же сервис, но для работы с ингредиентами:

- Храниться ингредиенты должны в карте в формате <идентификатор, ингредиент>.
- В сервисе должны быть методы для добавления нового ингредиента и получения его по идентификатору. Можно делать по аналогии с сервисом рецептов.

Создайте контроллеры и методы для создания и получения рецептов и ингредиентов.

<aside>
💡 Не забудьте проверить исключения в случае некорректно введенных данных или значения null. 
Какие данные будут считаться некорректными, определите самостоятельно исходя из условия задачи и описания формата параметров классов.

</aside>

- Критерии оценки
    - Создан класс Recipe (рецепт).
    - Создан класс Ingredient (ингредиент).
    - Созданы интерфейсы и классы сервисов с методами.
    - Созданы контроллеры для создания и получения рецептов и ингредиентов.