# Счётчики покрытия кода тестами

1. **INSTRUCTION.** Самая маленькая единица измерения JaCoCo - это одиночные инструкции кода байта Java. Покрытие инструкции предоставляет информацию о количестве кода, который был выполнен или пропущен.
2. **LINE.** Определяет покрытие строк кода тестами. Исходная строка считается выполненной, если была выполнена хотя бы одна инструкция, назначенная этой строке.
3. **BRANCH.** Показывает покрытие кода тестами по веткам if и switch. Эта метрика подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных ветвей. (Выбрала этот метод, потому что в коде использовался цикл if)
4. **COMPLEXITY.** Определение количества тестов, необходимых для полного покрытия кода