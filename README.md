## Урок 4. Структуры данных дерево и хэш-таблица
Необходимо превратить собранное на семинаре дерево поиска в полноценное левостороннее красно-черное дерево. И реализовать в нем метод добавления новых элементов с балансировкой.
Красно-черное дерево имеет следующие критерии:
* Каждая нода имеет цвет (красный или черный)
* Корень дерева всегда черный
* Новая нода всегда красная
* Красные ноды могут быть только левым ребенком
* У краной ноды все дети черного цвета