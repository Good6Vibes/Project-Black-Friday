# Тестирование User tg
## Баг-репорты
##### Баг-репорт №1

| Заголовок | На странице регистрации, поле ввода даты рождения уменьшилось в размере и осталовь без надписи |
| ------ | ------ |
| Описание | Поле ввода даты рождения не того размера и без надписи |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/tg] <br> 2. Нажать на кнопку "Давайте начнём!" |
| Текущий результат | ![](screenshots/user/1.jpg) |
| Ожидаемый результат | ![](screenshots/user/7.jpg) |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №2

| Заголовок | На странице регистрации, при вводе реферального кода, клавиатура переключается на буквенную раскладку после ввода каждой цифры|
| ------ | ------ |
| Описание | После ввода каждой цифры клавиатура переключается на буквенную раскладку |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/tg] <br> 2. Нажать на кнопку "Давайте начнём!" |
| Текущий результат | ![](screenshots/user/2.jpg) |
| Ожидаемый результат | При вводе реферального кода клавиатура остается на числовой раскладке  |
| Тестовое окружение | iPhone 13 |
| Разрешение | 2532х1170 |
| Критичность | Значительный |

##### Баг-репорт №3

| Заголовок | На странице регистрации поле ввода имени не имеет ограничений |
| ------ | ------ |
| Описание | Поле ввода имени не имеет ограничений |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/tg] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на поле ввода "Введите имя" <br> 4. Ввести бесконечное количество чисел и символов |
| Текущий результат | ![](screenshots/user/8.jpg) |
| Ожидаемый результат | Поле ввода имени имеет примерные ограничения: <br> *Минимум: 2 символа <br> *Максимум: 50 символов <br> *Допустимые символы: только буквы, пробелы, дефисы и апострофы  |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №4

| Заголовок | На странице регистрации поле ввода не получает визуального выделения, если оно остается пустым |
| ------ | ------ |
| Описание | Поле ввода не получает визуального выделения, если оно остается пустым |
| Шаги воспроизведения | 1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/tg] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на поле ввода "Введите имя" <br> 4. Ничего не вводить <br> 5. Нажать на кнопку "Зарегистрироваться" |
| Текущий результат | Поле ввода не получает визуального выделения, если оно остается пустым |
| Ожидаемый результат | Поле ввода имени визуально выделяется, если не заполняется |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №5

| Заголовок | На странице регистрации кнопка "Зарегистрироваться" активна при невыбранном чекбоксе о персональных данных |
| ------ | ------ |
| Описание | На странице регистрации кнопка "Зарегистрироваться" активна при невыбранном чекбоксе о персональных данных |
| Шаги воспроизведения | 1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/tg] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на поле ввода "Введите имя" <br> 4. Ввести имя <br> 5. Нажать кнопку "Зарегистрироваться" |
| Текущий результат | ![](screenshots/user/9.jpg) |
| Ожидаемый результат | Кнопка "Зарегистрироваться" не активна при невыбранном чекбоксе о персональных данных |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №6

| Заголовок | На странице главного меню не работает кнопка возвращения назад |
| ------ | ------ |
| Описание | Кнопка не реагирует на нажатие |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/tg] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на кнопку "Зарегистрироваться" <br> 4. Нажать на иконку возвращения назад |
| Текущий результат | ![](screenshots/user/3.jpg) |
| Ожидаемый результат | При нажатии на иконку происходит возвращение на страницу регистрации |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №7

| Заголовок | На странице реферальной системы иконки копирования не кликабельны |
| ------ | ------ |
| Описание | На странице реферальной системы иконки копирования не кликабельны |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на кнопку "Зарегистрироваться" <br> 4. Нажать на иконку настроек в хедере <br> 5. Нажать на "Реферальная система" <br> 6. Нажать на иконку копирования | 
| Текущий результат | ![](screenshots/user/12.jpg) |
| Ожидаемый результат | Иконки кликабельны и происходит успешное копирование информации |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |


##### Баг-репорт №8

| Заголовок | На странице системных настроек поле ввода ФИО не имеет ограничений |
| ------ | ------ |
| Описание | На странице системных настроек поле ввода ФИО не имеет ограничений  |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на кнопку "Зарегистрироваться" <br> 4. Нажать на иконку настроек в хедере <br> 5. Нажать на "Системные настройки" <br> 6. Нажать поле ввода ФИО <br> 7. Ввести любые символьные или числовые значения |
| Текущий результат | ![](screenshots/user/13.jpg) |
| Ожидаемый результат | Поле ввода имени имеет примерные ограничения: <br> *Минимум: 2 символа <br> *Максимум: 50 символов <br> *Допустимые символы: только буквы, пробелы, дефисы и апострофы  |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №9

| Заголовок | На странице системных настроек, поле ввода даты рождения уменьшилось в размере и осталось без надписи |
| ------ | ------ |
| Описание | Поле ввода даты рождения не того размера и без надписи   |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на кнопку "Зарегистрироваться" <br> 4. Нажать на иконку настроек в хедере <br> 5. Нажать на "Системные настройки" <br> |
| Текущий результат | ![](screenshots/user/14.jpg) |
| Ожидаемый результат | ![](screenshots/user/15.jpg)  |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №10

| Заголовок | На странице системных настроек поля ввода банковских данных не имеет ограничений и шаблонов ввода | 
| ------ | ------ |
| Описание | Поля ввода банковских данных не исеют ограничений и шаблонов ввода   |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на кнопку "Зарегистрироваться" <br> 4. Нажать на иконку настроек в хедере <br> 5. Нажать на "Системные настройки" <br> 6. Заполнить поля ввода с банковскими данными любыми значениями |
| Текущий результат | ![](screenshots/user/16.jpg) |
| Ожидаемый результат | ![](screenshots/user/17.jpg)  |
| Тестовое окружение | iPhone 13, Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 2532х1170, 720 x 1600, 2560x1600 |
| Критичность | Значительный |

##### Баг-репорт №11

| Заголовок | На странице регистрации текст чекбокса имеет некрасивый перенос | 
| ------ | ------ |
| Описание | На странице регистрации текст чекбокса имеет некрасивый перенос   |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать на кнопку "Давайте начнём!" |
| Текущий результат | ![](screenshots/user/18.jpg) |
| Ожидаемый результат | ![](screenshots/user/19.jpg)  |
| Тестовое окружение | Samsung Galaxy A12 |
| Разрешение | 720 x 1600 |
| Критичность | Тривиальный |

##### Баг-репорт №12

| Заголовок | На странице оформления подписки и главного меню, при альбомной ориентации, пропадают сертификаты | 
| ------ | ------ |
| Описание | При альбомной ориентации пропадают сертификаты на двух страницах   |
| Шаги воспроизведения |  1. Перейти по ссылке [https://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать на кнопку "Давайте начнём!" <br> 3. Нажать на кнопку "Зарегистрироваться"  <br> 4. Нажать на кнопку "Посмотреть предложения" |
| Текущий результат | ![](screenshots/user/20.jpg) |
| Ожидаемый результат | На странице главного меню видны все сертификаты |
| Тестовое окружение | Samsung Galaxy A12, Samsung Tab S9 |
| Разрешение | 720 x 1600, 2560х1500 |
| Критичность | Значительный |
