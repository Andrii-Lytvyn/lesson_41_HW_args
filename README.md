# lesson_41_HW_args
Задача 1
Создайте своё собственное исключение IncorrectWeightException и унаследуйте его от IllegalArgumentException.

Добавьте ему конструктор, в который можно передавать одно целое число.

При этом супер-класс IllegalArgumentException должен создаваться с сообщением об ошибке вида "Вес не может быть отрицательным: [некоректный вес]"

Дополните файл Pizza.java из классной работы, выбросив в конструкторе исключение IncorrectWeightException при попытке создать пиццу с отрицательной массой.
