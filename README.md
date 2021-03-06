# Решатель квадратных уравнений

Квадратное уравнение - уравнение второго порядка, вида `a*x**2 + b*x + c = 0` , где `а` не равно 0. Корни квадратного уравнения вычисляются через дискриминант по формуле `D = b**2 - 4*a*c`.

Если `D > 0`, то уравнение имеет два различных вещественных корня.
Если `D = 0`, то оба корня вещественны и равны.
Если `D < 0`, то оба корня являются комплексными числами.

Подробнее в [Википедии](https://ru.wikipedia.org/wiki/%D0%9A%D0%B2%D0%B0%D0%B4%D1%80%D0%B0%D1%82%D0%BD%D0%BE%D0%B5_%D1%83%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5).

# Как использовать
```python
>>> from quadratic_equation import get_roots
>>> get_roots(2, 3, 1)
(-1.0, -0.5)
>>> get_roots(9, 6, 1)
(-0.3333333333333333, None)
>>> get_roots(2, 3, 4)
(None, None)
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
