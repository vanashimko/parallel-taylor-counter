Написать программу нахождения массива значений функции <b>y[i]=sin(2*PI*i/N) (i=0,1,2…N-1)</b> с использованием ряда Тейлора. 
Пользователь задаёт значения <b>N</b> и количество <b>n</b> членов ряда Тейлора.
Для расчета одного члена ряда Тейлора запускается отдельный процесс.
Каждый процесс выводит на экран и в файл промежуточных результатов (создать в каталоге <b>/tmp</b>) свой <b>pid, i</b> и рассчитанное значение ряда.
Головной процесс считывает из файла промежуточных результатов значения всех рассчитанных членов ряда Тейлора для каждого <b>i</b>, суммирует их и полученное значение <b>y[i]</b> записывает в файл результата в виде: <b>y[i] =значение</b>.

Проверить работу программы для <b>N=256 n=5; N=1024 n=10</b>.