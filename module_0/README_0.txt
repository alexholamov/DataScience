«Project_0»
Это улучшенный алгоритм автора модуля, который позволяет угадать загаданное число за 18 попыток.

Итак, компьютер загадывает целое число от 1 до 100, и нам его нужно угадать. Под «угадать», конечно, подразумевается «написать программу, которая угадывает число». Процесс автоматизирован. Повторяется 1000 раз, чтоб понять, насколько быстро в среднем работает решение.

Функции:
1) game_core_v3() – Устанавливаем любое рандомное число, а потом уменьшаем или увеличиваем его в зависимости от условий кратности 2, 3, 5 или 7; больше или меньше загаданного числа). Функция принимает загаданное число и возвращает число попыток.
2) score_game() – Функция запускает игру 1000 раз, чтобы узнать, как быстро игра угадывает число.
