# Задача :

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.

# Решение:

Было обучены 2 модели : случайного леса и логистической регрессии. Для модели случайного леса подобраны оптимальные значения максимальной глубины деревьев и кол-ва естиматоров: 13 и 40 соотвественно. Достигнуто максимальное значение метрики F1 равное 0.5691. 
Модель логистической регрессии показала на данной обучающей выбьорке лучший результат при значении solver = liblinear, при этом значени F1 = 0.4934 - меньше чем у модели случ.леса