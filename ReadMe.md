
Здесь находится описание работы Телеграм Ботов:
1) Бот-калькулятор комплексных и рациональных чисел
2) Бот для игры в крестики-нолики (PlayerVSPlayer)

# 1. Бот-калькулятор #
Состоит из трех модулей:
* calc_bot - основной модуль Бота
* calc_complex - содержит функцию для работы с комплексными числами (мнимая часть должна обозначаться буквой "j")
* calc_rational - содержит функции для работы с рациональными числами
Предназначен для работы с заданными числами и автоматически выбирает алгоритм расчета.

# 2. Бот крестики-нолики #
## Описание ##
Бот предназначен только ля игры "Игрок против Игрока". Состоит из одного модуля game_bot, в котором реализованы алгоритмы игры на поле 3х3 (потенциал ввода размера поля пользователем практически реализован). . Имеет две функции:
* /start - запуск игры
* /help - содержит правила ввода Игроком

