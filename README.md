# Esp32-DevKit-v1-Step-Motor
Керування кроковим двигуном
код під arduino ide для ESP32 Devkit v1, щоб керувати кроковим двигуном 28BYJ-48 dc 5v (діаметр валу протяжки = 5 см) з драйвером на базі ULN2003APG.
Підключення:
ESP32 пін D23 - IN1 на драйвері
ESP32 пін D22 - IN2 на драйвері
ESP32 пін D21 - IN3 на драйвері
ESP32 пін D19 - IN4 на драйвері
ESP32 пін D15 через імпульсну кнопку на ESP32 пін GND для запуску виконання коду, виконати необхідну кількість кроків, за умови розміру валу, для протягування 10 см кабелю.
ESP32 пін D13 через імпульсну кнопку на ESP32 пін GND для запуску виконання коду, виконати необхідну кількість кроків, за умови розміру валу, для протягування 20.5 см
