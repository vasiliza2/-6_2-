# Лабораторная работа № 6
## Выполнила: Васильева Е.Д., ИВТ 2.1
## Шаг 1: переписать функции для нахождения чисел с помощью Cython
### Готовим файлы для компиляции Cython
Переписанная функция на [Cython](https://github.com/vasiliza2/-6_2-/blob/main/ferma_fact.pyx) и [setup.py](https://github.com/vasiliza2/-6_2-/blob/main/setup.py)
### Компилируем Cython
``` python
python setup.py build_ext --inplace
```
### Создаём файл для сравнения Python и Cython
[Файл](https://github.com/vasiliza2/-6_2-/blob/main/ferma_2.py) запускает timeit с аналогичными параметрами и сравнивает два варианта и строит графики
### Результаты сравнения Python и Cython
![image](https://github.com/vasiliza2/-6_2-/blob/05a76db3c637cf8c29249610b5b4506689cb4d67/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-11%20182725.png)
### Сравнение общего времени выполнения Python и Cython
![image](https://github.com/vasiliza2/-6_2-/blob/05a76db3c637cf8c29249610b5b4506689cb4d67/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-11%20183208.png)
### Сравнение времени выполнения для каждого числа
![image](https://github.com/vasiliza2/-6_2-/blob/05a76db3c637cf8c29249610b5b4506689cb4d67/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-11%20183229.png)
