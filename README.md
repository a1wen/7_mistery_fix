# Решатель квадратных уравнений

Программа решает квадратные уравнения, файл test.py производит тестирование корректности работы программы. 

# Как использовать

Функция get_roots(a,b,c) принимает на вход 3 значения, равным коэффициентам квадратного уравнения.
Возвращает 2 значения корней уравнения, если корень извлечь не удается возвращаемое значение равно None. Пример использования:

```python
import quadratic_equation

#Решаем квадратное уравнение вызовом функции get_roots()

root1, root2 = quadratic_equation.get_roots(a, b, c) #где параметры соответствуют ax**2 + bx + c = 0

```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
