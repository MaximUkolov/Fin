1. Создаем локальный реп
2. Инициализируем его командой git init
3. Добавляем в отслеживание всю папку командой git add .
4. Кодим решение задачи, поэтапно сохраняем командой git commit -am "  ". В ковычках прописываем выполненный объем.
5. Создаем удаленный реп и пушим туда нашу задачу.
6. Ждем оценки.

Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
Описание алгоритма решения:
Сначало объявляется два массива: изначальный и вторый такой же длины. Потом метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива. Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
