1. Аналіз та рефакторинг коду

У цій лабораторній роботі було проведено рефакторинг двох фрагментів коду на мові програмування Python. Нижче подано короткий опис аналізу та прийнятих рішень для кожного з них.

## Фрагмент коду 1

У першому фрагменті коду функція `calculate_score` мала велику кількість параметрів, що ускладнювало її розуміння та обслуговування. Для спрощення було вирішено згрупувати пов’язані параметри в клас `User`. Це зменшило кількість параметрів у функції та зробило код більш читабельним.

## Фрагмент коду 2

У другому фрагменті коду використовувалися числові значення для представлення типів користувачів і пов’язаних даних (наприклад, тип і номер телефону), що ускладнювало розуміння та підтримку коду. Для покращення було застосовано використання констант та іменованих параметрів у конструкторі класу `User`, а також методів для отримання зрозумілої інформації про користувача.

## Висновок

Рефакторинг покращив читабельність та обслуговування обох фрагментів коду, зробивши їх більш зрозумілими та гнучкими. Використання об'єктно-орієнтованого підходу та стандартних практик програмування сприяло підвищенню якості коду.