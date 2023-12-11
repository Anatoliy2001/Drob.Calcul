План тестирования
Модульное тестирование класса Fraction:

Тест кейс 1: Проверка метода to_decimal для дроби self.fraction1 (Fraction(1, 2))
Ожидаемый результат: Результат преобразования дроби в десятичное число равен 0.5.
Тест кейс 2: Проверка метода to_decimal для дроби self.fraction2 (Fraction(3, 4))
Ожидаемый результат: Результат преобразования дроби в десятичное число равен 0.75.
Модульное тестирование класса FractionCalculator:

Тест кейс 3: Проверка метода add() для сложения дробей Fraction(1, 2) и Fraction(3, 4)
Ожидаемый результат: Результатом сложения дробей будет Fraction(10, 8).
Тест кейс 4: Проверка метода subtract() для вычитания дробей Fraction(1, 2) и Fraction(3, 4)
Ожидаемый результат: Результатом вычитания дробей будет Fraction(-2, 8).
Тест кейс 5: Проверка метода multiply() для умножения дробей Fraction(1, 2) и Fraction(3, 4)
Ожидаемый результат: Результатом умножения дробей будет Fraction(3, 8).
Тест кейс 6: Проверка метода divide() для деления дробей Fraction(1, 2) и Fraction(3, 4)
Ожидаемый результат: Результатом деления дробей будет Fraction(4, 6).
Дополнительные сценарии тестирования:

Тест кейс 7: Проверка обработки деления на ноль или нулевой дроби.
Тест кейс 8: Тестирование производительности для больших дробей.
Документирование и отчетность:

Требуется документация о процессе запуска тестов и ожидаемых результатах для каждого теста.
Отчет о результатах тестирования должен содержать информацию о прохождении/не прохождении тестов.
Выполнение тестов и автоматизация:

Тесты должны быть включены в автоматический запуск в среде непрерывной интеграции.
Обзор и совершенствование:

После завершения тестирования следует провести обзор результатов для их улучшения в будущем.
