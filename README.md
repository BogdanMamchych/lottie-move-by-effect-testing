# lottie_move_by_effect_testing

Тестування ефекту MoveByEffect на Flame. Flutter

## Опис
### MoveByEffect - Це ефект, який розміщає Flame-компонента відносно поточної позиції на задану величину offset.
### До цього компоненту також можна застосувати декілька ефектів переміщення одночасно. В такому випадку буде суперпозиція всіх ефектів;
## Атрибути:
### - offset: Vector2 - Це зсув позиції. Vector2 містить дві позиції: x - позиція по горизонталі, y - позиція по вертикалі. Якшо це Vector2.all(), то тільки одне значення value - позиція по горизонталі та вертикалі. Наприклад: Якщо поточна позиція - Vector2(150, 30), то якщо offset буде Vector(50, 20), тоді після зсуву поточна позиція буде Vector2(200, 50). А якщо до поточної позиції після зсуву примінити Vector2.all(70), то після зсуву поточна позиція матиме наступне значення Vector2(270, 120);
### - controller - контроллер ефекту, в якому можна задати такі значення, як duration - тривалість(до речі, чим менше тривалість, тим більша швидкість), infinite - чи є ефект безкінечним, alternate - чи буде виконання в зворотній бік після виконання і т.д;
