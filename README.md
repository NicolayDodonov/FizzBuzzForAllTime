# FizzBuzz for all programm!

Это небольшая сборка реализации задачи FizzBuzz для всех возможных языков программирования:
От популярных и общепризнанных до странных, неожиданных и чаще всего - бессмысленных.<br>
Сейчас реализованы: GO, Python, PascalABC

Автор: Додонов Н.А.

### Что такое FizzBuzz?

Fizz buzz – это групповая детская игра для обучения правилам деления. 
Игроки по очереди считают по возрастающей, заменяя любое число, кратное трем, словом "fizz", 
а любое число, кратное пяти, словом "buzz".

FizzBuzz используется в качестве метода проверки подготовки на собеседовании программистов. 
Написание программы для вывода первых 100 чисел FizzBuzz является тривиальной проблемой для 
любого потенциального программиста, поэтому интервьюеры могут легко отфильтровать тех, у кого 
недостаточно возможностей для программирования.

### Алгоритм FizzBuzz

Все (или практически все) программы в этой подборке реализуют решение задачи следующим способом:<br>
* Создаётся основной цикл программы main от 1 до 100 вызывающий функцию FizzBuzz()
* Функция FizzBuzz() принимает целочисленное число number, а возвращает строку string
* Проверяем, делиться ли число целочисленно на 3, если да - добавляем строке Fizz
* Проверяем, делиться ли число целочисленно на 5, если да - добавляес строке Buzz
* Проверяем, осталась ли строка результата пуста, если да - конвертируем nubmer в строку
* Выводим результат FizzBuzz() в основной цикл main, где выводим его на экран
