##Не надо исправлять или дописывать что-то в файлы сданных ранее работ. Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

|Прозвішча                      |  ДЗ1|ДЗ2-3| ДЗ4 | ДЗ5 | ДЗ6 |iтог  |комментарии |
|:------------------------------|:---:|----:|:---:|----:|:---:|----:|---:|
|Асонов Дмитрий Геннадьевич     |  0  |5+0  |  0  |     |     |     | 
|Богданович Вероника Викторовна |  7  |6+?  |  3  |     |     |     | подозрение в №1-5.cpp |
|Давыденко Александра Викторовна|  -5 | 0+0 |  1  |     |     |     |
|Демянович Владислав Павлович   |  0  | 6   |  5  |     |     |     |
|Киселев Артем Рональдович      |  2  | 3+? |  1  |     |     |     |
|Круковский Сергей              |     | ?+? |  2  |     |     |     |указатели? Круто, но не верю... 3-3хорошо|
|Линник Дмитрий Васильевич      |  0  | 4+3 |  3  |     |     |     |
|Савко Тимур Леонидович         | -10 |     |  2  |     |     |     |
|Станкевич Александр Олегович   |  7  |     |  2  |     |     |     |
|Семенович Роман                |  7  |     |     |     |     |     |
|Утлик Павел Дмитриевич         |  0  | 3+1 |  0  |     |     |     |
|Федосов Андрей Игоревич        | -10 |     |     |     |     |     | штраф за воровство кода|
|Шавеко Иван Геннадьевич        | -10 | 5+7 |  1  |     |     |     | штраф за воровство кода|
|Шишкарёв Иван Анатольевич      |  8  |     |     |     |     |     |

----------------------------------
#Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий также надо вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)

• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.

• имена переменных и функций должны соответствовать общепринятым нормам.
_________________________________
##Задание на 9/11/2016 
### НЕ НАДО исправлять предыдущие работы 

`Записать файлы в _кодировке UNICODE_ с именами     
4-1.cpp (тут решение 1-й задачи), 4-2.cpp (тут решение второй задачи)...`

0) Построить график функции y=sin(2x)/x на промежутке [-6,6] с шагом 0.1 ![Смотри картинку...](https://github.com/BSU2016gr09/_Workflow/blob/master/sin2x_frac_x.gif) 

1) Реализовать операции целочисленной арифметики на массивах размера MAX_SIZE=100 (глобальная константа). В цикле вычислить максимальное возможное на этих массивах число Фибоначчи 1,1,2,3,.... и (**для желающих получить 9-10 на экзамене**) максимально возможный факториал.     
Тех, кто **самостоятельно** реализует операцию деления выведите для последних трех чисел Фибоначчи их отношение.

2) Напишите игру в пьяницу на стеке между компьютером и компьютером. Колода перетусовывается и раздаётся пополам. Они по очереди достают по карте сверху колоды. Забирает карты и кладёт себе вниз колоды тот у кого очков больше на вытянутых картах (6-ка берет туза, 7-ка берет короля). Игра заканчивается если один не может сделать ход. Запоминать кол-во ходов в законченной игре. Провести 5000 партий. Вывести макс./мин./среднее кол-во ходов в этих партиях.

3)  **для желающих получить 9-10 на экзамене** В программе задано выражение представляющее собой обратную польскую запись, например, char test[]="124 222 + 43 × 31 +"; в виде **многоциферных** чисел и знаков **разделенных пробелом**. Посчитать результат записи полагая что числа вещественные.    
_Понадобятся функции для преобразования сроки в число из заголовочного файла <cstdlib> **atof(char)**. Функция преобразует строку, содержащую символьное представление целого или вещественного числа, в соответствующее вещественное число с двойной точностью. В качестве признака конца числа служит **первый символ, который не может быть интерпретирован как принадлежащий числу**. Значит, достаточно из массива test[] подавать на вход функции atof() строку начиная с текущей ( а не начальной) позиции

_________________________________
##Задание на 2/11/2016 
### НЕ НАДО исправлять предыдущие работы 

`Записать файлы в _кодировке UNICODE_ с именами     
3-1.cpp (тут решение 1-й задачи), 3-2.cpp (тут решение второй задачи)...`

1) Напишите игру в кости между человеком и компьютером. Они по очереди кидают по
два кубика. Побеждает тот у кого сумма больше. Игра заканчивается если набрана сумма >50. Кубики рисуйте в отдельной ф-ции псевдографикой (см. рисунок в качестве примера). Используйте system("cls"); для очистки экрана.
+---+   
|O  |    
|   O |    
|  O|    
+---+    

2) В массиве размера N, заполненного случ.числами от 0 до 10, подсчитать количество элементов, встречающихся более одного раза.

3) В массиве размера N, заполненного случ.числами от 0 до 10, определить максимальную длину последовательности равных элементов.

4) Окончательно реализовать функции для работы стека на массиве. Сделать парные ф-ции push/pop для массива double и для массива char. Создать стек чисел и стек символов. Продемонстрировать их работоспособность вызывая их из main. В частности, показать, что стек не переполняется. 
 
5) В программе задана последовательность из открывающихся и закрывающихся скобочек 3 видов. Например, char test[]="(aa[b(c)ddd]e{ee})";    Проверить правильность растановки скобок в этом выражении c помощью стека в котором хранятся char. Чтобы использовать очередной элемент строки (aa[b(c)ddd]e{ee}) достаточно написать test[0], test[1] ит..д. т.е. в цикле test[i]. 

6)  **для желающих получить 9-10 на экзамене** В программе задано выражение представляющее собой обратную польскую запись, например, char test[]="1 2 + 4 × 3 +"; в виде **одноциферных** чисел и знаков **без пробелов**. Посчитать результат записи полагая что числа вещественные.    
_Обратная польская запись (см.wiki) — это один из способов записи математических выражений. Удобен тем, что для него нет необходимости понятия приоритета операций, так как само положение операторов целиком и полностью определяет порядок вычисления.    С помощью стека обратная польская запись легко вычисляется. Если встречается число (**при этом придётся преобразовывать char в число таким образом: char symb;double number; number=symb-48;**), то оно заносится в стек, если встречается оператор, то извлекается два элемента (учитывая порядок),
над ними производится операция, результат которой заносится в стек. После чтения всего
выражения в стеке будет только одно число — результат выражения.   
Для создания своего выражения можно использовать, например,_ primat.org/news/obratnaja_polskaja_zapis/2016-04-09-1181 

7) На *4/11/2016* Реализовать функции для работы с очередью. Продемонстрировать их работоспособность вызывая из main. Показать, что очередь размера 4 не переполняется. Если добавить 3 элемента, потом удалить 2, а потом еще раз добавить 3 элемента.

-----------------------------------

##Задание на 28/10/2016 
### НЕ НАДО исправлять предыдущие работы 
`(в СВОЙ РЕПОЗИТОРИЙ записать файлы в кодировке UNICODE с именами     
2-1.cpp (тут решение 1-й задачи), 2-2.cpp (тут решение второй задачи)...`

1) Массив чисел размера N проинициализировать случайными числами из промежутка от 1 до N. "Перевернуть" массив (последний элемент станет первым, 1-й станет последним, 2-й поменяется с предпоследним и т.д.) **Внимательно проверьте случай нечетного N** Нельзя, естественно, использовать дополнительный массив!

2) Массив чисел размера N проинициализировать случайными числами из промежутка от -N до N. Циклически сдвинуть (**не переставить, а именно сдвинуть!** Т.е. нельзя использовать swap или аналоги надо использовать только присваивание a[i]=a[....];) элементы массива вправо на 1 элемент (последний элемент станет первым, 1-й станет 2-м, 2-й станет 3-м и т.д.) потом циклически сдвинуть элементы массива влево на 1 элемент (первый элемент станет последним, 2-й станет 1-м и т.д) Нельзя, естественно, использовать дополнительный массив!

3) **_для желающих получить 9-10 на экзамене** Массив А чисел размера N проинициализировать случайными числами из промежутка от -N до N. **Не используя функции из задачи 2-2** Написать функции (без swap и аналогов) циклического сдвига элементов массива вправо на k элементов (1-й станет 1+k -ым, 2-й станет 2+k -ым и т.д.) и влево на k элементов. В main написать вызов этих функций для числа k, которое вводит пользователь. **(k может быть в частности =0, тогда сдвига нет, k=1 - задача аналогично предыдущей 2-2.cpp и т.д)**    
_Надо придумать формулу вычисления нового индекса элемента чтобы **обойтись одним циклом по массиву А.**, а не двумя вложенными циклами!_ Нельзя, естественно, использовать дополнительный массив!

4) Массив целых чисел размера N проинициализировать последовательными числами от 1 до N. "Перетусовать" элементы массива двумя способами, предложенными на паре: с использованием доп.массива и просто меняя местами случайные элементы.

---------------------
##Задание на 26/10/2016 

`(в СВОЙ РЕПОЗИТОРИЙ записать 5 или 6 файлов с именами     
1-1.cpp (тут решение 1-й задачи), 1-2.cpp (тут решение второй задачи), 1-3.cpp, 1-4.cpp, 1-5.cpp, 1-6.cpp)`

0) Пройти на http://euniversity.bsu.by входной тест Галкина.

1) Пользователь вводит с клавиатуры натуральное число, проверить корректность ввода, вычислить и вывести на экран сумму цифр введённого пользователем числа.

2)* Пользователь вводит с клавиатуры пятизначное натуральное число, которое сохраняется в переменную n, проверить корректность ввода, составить и вывести на экран число из цифр введённого числа n, так, чтобы выведенное число оказалось максимальным из возможных. Например, если пользователь ввёл число 22195, то программа должна вывести число 95221.

3) Пользователь вводит с клавиатуры натуральное число не большее 100, которое сохраняется в переменную n, проверить корректность ввода, создать массив из 10 случайных целых чисел из отрезка [-2n;n], вывести массив на экран в строку, подсчитать и и вывести на экран количество положительных чётных чисел в массиве.

4) Объявить массив вещественных чисел размера N (число N объявить как константу). Проинициализировать значения элементов массива случайными числами из промежутка от -50 до 50. 

Вывести значения сначала элементов с нечетными коэффициентами (1-й, 3-й, 5-й,...) а затем - с четными.

5) Объявить массив А вещественных чисел размера N (число N объявить как константу). Проинициализировать значения элементов массива случайными числами из промежутка от -50 до 50.

"Разделить" массив А на два массива: положительные записать в массив В, отрицательные - в С.

6)**_для желающих_  Объявить массив А вещественных чисел размера N (число N объявить как
константу).Проинициализировать значения элементов массива случайными числами из промежутка
от -50 до 50.

"Отсортировать" массив А на месте (т.е. не используя вспомогательных массивов В
и С) таким образом:положительные значения массива А переместить в начало, отрицательные переместить
в конец массива А.

(Проверить потом, что программа работает когда все элементы одного знака!)
_________________________________
###Дополнительные плюсы  студентам, выжившим после капустника 13/10:

_Асомов,Богданович,Демянович,Киселев,Круковский,Савко,Семенеович_
