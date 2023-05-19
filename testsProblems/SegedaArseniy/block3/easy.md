Задача 1 (легкий):
Вам даны главы двух отсортированных связанных списков list1и list2.
Объедините два списка в один отсортированный список. Список должен быть составлен путем соединения узлов первых двух списков.
Возвращает заголовок объединенного связанного списка.

Пример 1:
Ввод: список1 = [1,2,4], список2 = [1,3,4]
Вывод: [1,1,2,3,4,4]
Пример 2:
Ввод: список1 = [], список2 = []
Вывод: []
Пример 3:
Ввод: список1 = [], список2 = [0]
Выход: [0]
 
Ограничения:
1.	Количество узлов в обоих списках находится в диапазоне [0, 50].
2.	-100 <= Node.val <= 100
3.	Оба list1и list2 отсортированы в неубывающем порядке.