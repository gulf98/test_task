У вас есть файл `floors.json`, в котором хранится информация об этажах.

Задание:
- написать фикстуру, которая считывает данные из файла `floors.json`
- написать тест в котором:
    - используется фикстура для считывания данных
    - для этажа с `id = 4` проверяется:
        - что он есть в файле
        - что `house_id = 2`
        - что `is_metro_schema = True`
        - что `is_default = False`
    - для этажа с `id = 5` проверяется:
        - что он есть в файле
        - что `house_id = 2`
        - что `is_default = True`
        - что `is_metro_schema` отсутствует

В качестве тестового фреймворка использовать pytest. Тесты должны проходить независимо от порядка расположения этажей в файле.
