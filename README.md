Это полностью готовый проект, поэтому здесь не будет точек развития кода.

Целью данного проекта было изучение "Чисел Гурвица", программная реализация их вычисления.

Процесс его реализации и описание работы программы приведены в текстовом документе в папке с результатами.

В этом проекте реализован полный перебор с использованием параллелизма с "thread". Однако в коде используется нестандартный вызов конструктора класса потоков, это связано с ошибками при передачи параметров. В связи с чем были использованы лямбда функции для корректного вызова и передачи параметров.

На момент реализации проекта параллельное программирование было чемто сложным и стоящим далеко впереди в плане изучения.

В результате реализации трудностью так же была реализация "сложного" перебора для чисел с заданной размерностью и количеством разрядов в определенных диапазонах.

По итогу код приложения разбит на отдельные функции, в коде происходит отельно ввод данных, расчет дополнительных параметров для вычисления, отдельно происходит получение числа виртуальных потоков системы, параллелизация вычислений, и объединения и вывод результатов.

Так как на момент реализации дисциплина "Параллельное программирование" была еще впереди, то в ходе реализации были пропущены следующие моменты: изучение сложности реализованного алгоритма, исследование альтернативных алгоритмов вычисления и параллелизации, изучение и сравнение теоретического (расчетного) коэффициента ускорения на разных диапазонах с фактическим.

Поставленнные в данном проекте цели были достигнуты.
