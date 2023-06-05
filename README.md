Необходимо превратить собранное на семинаре дерево поиска в полноценное левостороннее красно-черное дерево. И реализовать в нем метод добавления новых элементов с балансировкой.

Красно-черное дерево имеет следующие критерии: • Каждая нода имеет цвет (красный или черный) • Корень дерева всегда черный • Новая нода всегда красная • Красные ноды могут быть только левым ребенком • У краной ноды все дети черного цвета

Соответственно, чтобы данные условия выполнялись, после добавления элемента в дерево необходимо произвести балансировку, благодаря которой все критерии выше станут валидными. Для балансировки существует 3 операции – левый малый поворот, правый малый поворот и смена цвета.

(Провозился три дня, собрал франкинштейна)

Пример из терминала:

Введите целое число
6
поворот влево!!
6● 
Вы хотите продолжить? (введите y или n)
y
Введите целое число
3
вращение вправо
3● 6● 
Вы хотите продолжить? (введите y или n)
y
Введите целое число
67
поворот влево!!
3◯ 6◯ 67◯ 
Вы хотите продолжить? (введите y или n)
y
Введите целое число
12
поворот влево!!
вращение вправо
поворот влево!!
3◯ 6◯  12● 67◯ 
Вы хотите продолжить? (введите y или n)
y
Введите целое число
33
3◯ 6● 12◯ 33● 67◯ 
Вы хотите продолжить? (введите y или n)
