Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Блок ввода массива из строк:
В соответствии с  заданием, первоначальный массив вводится с клавиатуры. 
Нужно ввести количество планируемых элементов массива строк (ввод реализован в виде функции InputNumbers), а после заполнить этот массив.
Переменная lengthLimit - согласно заданию равна 3
CheckArray - Метод подсчёта количества элементов, размер которых меньше lengthLimit
Подсчёт осуществляется перебором элементов массива array и сравнением количества их элементов с переменной lengthLimit.
Результат выводится в переменную nObjects 
Инициализируется новый массив строк newArray, размером, равным переменной nObjects
FillNewArray - Метод формирования нового массива строк
Формирование осуществляется перебором элементов массива array, сравнением количества их элементов с переменной  lengthLimit и добавлением в массив newArray элемента, удовлетворяющего условию.
На выходе метода получается заполненный массив строк newArray, удовлетворяющий условию, что и является решением задачи.
Выводим его на экран с помощью метода PrintArray.