# Bodik_Tyskivski
У цій програмі ми використовуємо цикл while, щоб дозволити користувачеві аналізувати декілька файлів підряд. 
Для кожного файлу ми спочатку запитуємо користувача про його шлях, а потім аналізуємо його.
Ми відкриваємо файл у режимі "r" (тобто для читання) та використовуємо метод readlines(), 
щоб зчитати всі рядки у список. Потім ми проходимося по кожному рядку та виконуємо різні перевірки для статистики.
Для визначення кількості порожніх рядків ми використовуємо метод strip() для видалення всіх пробільних символів з початку та кінця рядка. Якщо після цього рядок порожній, то ми збільшуємо лічильник порожніх рядкі
