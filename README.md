# Dungeon Generator for D&D (C++)

Не очень сложный код, который генерирует случайную карту с ловушками Л, монстрами М, сундуками С, чем-то предельно невразумительным и таниснтвенным (?), входом () и выходом [] из подземелья.

Ввод параметров, таких как размер карты (width и height), сложность уровня (difficulty), которая влияет на количество предметов, коэффициент максимального размера одной комнаты (size_coefficient), количество комнат (count_rooms) и количество троп (count_trails) осуществляется через текстовый файл.

Также можно походить по карте, без взаимодействия, но при попытке войти в сундук вас об этом предупредят!

Пример генерации для width = 110, height = 40, difficulty = 5, size_coefficient = 0.2, count_rooms = 10, count_trails = 50 :

![image](https://github.com/Klapeyrof/D-D/assets/113589355/a6c217fd-a728-41c3-9650-43329a844a4c)
