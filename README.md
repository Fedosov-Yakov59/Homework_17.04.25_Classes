Описание класса и методов:
Импорт библиотеки: В начале кода импортируется модуль math, который предоставляет доступ к математическим функциям и константам, таким как число π (пи).

Класс VolumeCalculator: Это основной класс, содержащий методы для вычисления объемов.

Метод cube(self, side_length):

Описание: Вычисляет объем куба на основе длины его стороны.
Параметр: side_length — длина стороны куба (должна быть положительным числом).
Возвращаемое значение: Объем куба, вычисляемый по формуле ( V = a^3 ), где ( a ) — длина стороны.
Исключение: Если side_length меньше или равно нулю, выбрасывается исключение ValueError с соответствующим сообщением.
Метод sphere(self, radius):

Описание: Вычисляет объем сферы на основе радиуса.
Параметр: radius — радиус сферы (должен быть положительным числом).
Возвращаемое значение: Объем сферы, вычисляемый по формуле ( V = \frac{4}{3} \pi r^3 ), где ( r ) — радиус.
Исключение: Если radius меньше или равно нулю, выбрасывается исключение ValueError с соответствующим сообщением.
Метод cylinder(self, radius, height):

Описание: Вычисляет объем цилиндра на основе радиуса основания и высоты.
Параметры:
radius — радиус основания цилиндра (должен быть положительным числом).
height — высота цилиндра (должна быть положительным числом).
Возвращаемое значение: Объем цилиндра, вычисляемый по формуле ( V = \pi r^2 h ), где ( r ) — радиус основания, а ( h ) — высота.
Исключение: Если radius или height меньше или равно нулю, выбрасывается исключение ValueError с соответствующим сообщением.
Применение:
Класс VolumeCalculator может быть использован в различных приложениях, где требуется вычисление объемов геометрических фигур, например, в инженерии, архитектуре или образовательных целях.
