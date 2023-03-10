# Yandex_TestTask
Тестовая задача из Яндекс.Контеста.
____
# А. Числовые ребусы.
|   |   |
|----------------|:---------:|
| Ограничение времени | 1 секунда |
| Ограничение памяти | 512Mb |
| Ввод | Стандартный ввод или input.txt |
| Ограничение времени | Стандартный вывод или output.txt |

Алиса изучает английский язык. Ей надоела обычная речь, поэтому она решила говорить обычными ребусами:
+ Каждой строчной букве латинского алфавита Алиса сопоставила двоичный разряд, начиная с младшего: *a* - 0-й разряд, ..., *z* - 25-й разряд.
+ Чтобы произнести букву, Алиса инвертирует соответствующей букве бит в специальной переменной **W** и сообщает новое значение **W** в десятичной системе.
+ Также Алиса произносит пробел, используя для этого 26-й разряд.

## Формат ввода
В первой строке содержится единственное целое число **n (1 <= n <= 500)** - количество чисел, сказанных Алисой.
Во второй строке расположено *n* целых чисел **Wi (0 <= Wi <= 2^27)** - значения переменной **W** после произнесения Алисой *i*-го символа.

## Формат вывода
##### Пример 1
| Ввод | Вывод |
|----------------|:---------:|
| 5 | alice |
| 1 2049 2305 2309 2325 | |   |
##### Пример 2
| Ввод | Вывод |
|----------------|:---------:|
| 3 | aba |
| 1 3 2 | |   |
