#data.py

data.py (пустий файл для зберігання даних)




#main.py

from game_logic import гра: Цей рядок імпортує функцію гри з іншого файлу з назвою game_logic. Це передбачає, що в іншому файлі є визначена функція гра().

if name == "main": Ця конструкція перевіряє, чи цей файл є головним (основним) модулем, а не модулем, імпортованим з іншого файлу. Це важливо, оскільки головний модуль запускається автоматично при виклику програми, а інші модулі можуть бути імпортовані в інші частини коду.

гра(): Цей рядок викликає головну функцію гри, розпочинаючи виконання гри, коли цей файл запускається.




#game_logical.py
 Гра "Вгадай число"

Ця гра є консольною програмою, в якій користувач повинен вгадати випадкове число від 1 до 100.

 Як грати

1. Запустіть програму, виконавши файл `game_logic.py`.
2. Слідуйте вказівкам на екрані та вводьте свої спроби вгадати число.
3. Гра надасть вам підказки щодо того, чи ваше число більше чи менше за загадане.
4. Продовжуйте вгадувати, доки не відгадаєте число або не закриєте гру.

 Додаткові функції

- Підказки: Гра надає підказки щодо того, чи ваше число більше чи менше за загадане.
- Перезапуск гри: Після закінчення гри ви можете вибрати, чи хочете ви перезапустити гру.

 Як встановити

1. Завантажте код гри.
2. Запустіть гру, використовуючи команду `python game_logic.py`.

 Вимоги

Гра використовує мову програмування Python. Вам слід мати встановлену версію Python 3 для коректної роботи.

