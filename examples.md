| Исход                | Цена А | Цена Б |
| ------------------------- | ----------- | ----------- |
| Конверсия        | 200         | 182         |
| Нет конверсии | 23 539      | 22 406      |

Слепое исследование

Двойное слепое исследование

# Термины

1. Нулевая гипотеза
2. Альтернативная гипотеза
3. Односторонняя и двусторонняя проверка

Альфа (альфа, уровень значимости) - задаемся уровнем значимости результата 0.9

Р значение (п значение)  - фактическое значение вероятности из статистики 0.96

Ошибки первого рода: эффект является реальным (но это не так)

Ошибки второго рода: эффект не является реальным (но все наоборот)

Выборка может не отражать то распределение, по которому производится проверка (Не гауссово, Не Хи, Не Пуассона)

# *Регрессия*

1. Отклик - та величина, которую предсказываем
2. Независимая переменная () - предиктор, фича, признак
3. Запись - x1, x2, ... xn -> y_fact
4. Пересечение, сдвиг bo
5. Коэффициент регрессии b1
6. Подогнанные значения (fitted values) - получены ииз регрессионной прямой
7. Остатки (residuals)
8. МНК - метод наименьших квадратов

# Как оценить качество модели?

Порядок деления 

1. Обучающая-тестовая
2. Обучающая-валидационная

Обучающая выборка - тренируем модель (feature + outcome) 60-80%

Валидационная выборка - 0-20% проверяем выбранную модель в процессе обучения, выбираем лучшую

Тестовая выборка - 10-20% - финальная проверка качества модели



Предсказываем цифры - регрессия - обучение с учителем

Предсказываем классы - классификация - обучение с учителем

Группируем объекты - Кластеризация - обучение без учителя
