## Итоговая проверочная работа
Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе разработчик. Мы должны убедиться что базовое знакомство с it прошло успешно
Задача алгоритмически не самая сложная, однако для полноценного выполненияя проверочной работы необходимо:
1. Создать репозиторий на GitHub
2. Нарисовать блоксхему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы ваыделяете ее в отдельбный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения файл (README.md)
4. написать программу, решающую посмтавленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что все залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

## Задача 
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно вывести с клавиатуры, либо задать на старте выполнения
алгоритма. При решение не рекомендуем пользоваться коллекциями, лучше обойтись исключительно массивами.

## Описание решения
Сначало объявляется два массива: изначальный и вторый такой же длины. Потом метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива. Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
