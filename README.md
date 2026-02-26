# RU

# Циклические алгоритмы и тесты на простоту

Данная работа посвящена изучению циклических алгоритмов и программированию циклического вычислительного процесса.  
В рамках работы реализованы задачи, включающие вычисление значений функции, тесты на простоту, вычисление суммы ряда, игровую задачу и моделирование процесса остывания кофе.

---

## Цели работы

- Изучение циклических алгоритмов  
- Освоение операторов цикла  
- Построение циклических вычислительных процессов  
- Анализ численных методов  

---

## Задания

### **Задание 1**

Вычисление и вывод в виде таблицы значений функции, заданной графически,  
на интервале от `Xнач` до `Xкон` с шагом `dx`.

Интервал и шаг подбираются так, чтобы были проверены все ветви программы.

---

### **Задание 2**

Реализация тестов на простоту:

- Метод перебора делителей  
- Тест Миллера  
- Тест Поклингтона  
- Генерация простых чисел по ГОСТ Р 34.10-94  

Дополнительно реализовано:

- Построение таблицы простых чисел, меньших 500 (решето Эратосфена)  
- Генерация простых чисел заданной длины  
- Проверка вероятностным тестом (вероятность ошибки ≤ 0.1)  
- Подсчет количества чисел, ошибочно признанных простыми  

---

### **Задание 3**

Вычисление суммы ряда:
∞
Σ (n^a / b^n)
n=1

В зависимости от параметров:

- если ряд расходится — выводится `infinity`
- если сумма рациональна — выводится в виде несократимой дроби
- если сумма иррациональна — выводится `irrational`

---

### **Задание 4**

Задача «Увлекательная игра»:

- Игроки по очереди выбирают от 1 до `m` чисел из начала последовательности  
- Выбранные числа удаляются  
- Их сумма прибавляется к счету игрока  
- Игра продолжается до удаления всех чисел  
- Оба игрока действуют оптимально  
- Требуется определить победителя  

---

### **Задание 5***

Моделирование процесса остывания кофе по закону Ньютона:
dT/dt = -r (T - Ts)

Реализовано:

- Моделирование изменения температуры во времени  
- Построение таблиц зависимости температуры от времени  
- Линейная аппроксимация экспериментальных данных  
- Вычисление коэффициента корреляции  
- Вычисление коэффициента детерминации  

---

## Используемые языки программирования

- C++  
- Дополнительные языки программирования (по заданию)  

---

## Как использовать

1. Открыть соответствующий файл задания.
2. Скомпилировать программу выбранного языка.
3. Запустить программу.
4. Ввести необходимые параметры.
5. Получить результат вычислений в консоли.

---

# EN

# Cyclic Algorithms and Primality Tests

This laboratory work is devoted to studying cyclic algorithms and implementing cyclic computational processes.  
The tasks include function evaluation, primality testing, infinite series calculation, a game theory problem, and coffee cooling simulation.

---

## Objectives

- Study cyclic algorithms  
- Work with loop operators  
- Implement cyclic computational processes  
- Analyze numerical methods  

---

## Tasks

### **Task 1**

Calculate and display in table form the values of a function defined graphically  
on the interval from `Xstart` to `Xend` with step `dx`.

The interval and step are chosen to test all branches of the program.

---

### **Task 2**

Implementation of primality tests:

- Trial division method  
- Miller test  
- Pocklington test  
- Prime number generation according to GOST R 34.10-94  

Additionally implemented:

- Sieve of Eratosthenes (primes less than 500)  
- Generation of prime numbers of given length  
- Probabilistic testing (error probability ≤ 0.1)  
- Counting false positives  

---

### **Task 3**

Calculation of the infinite series:
∞
Σ (n^a / b^n)
n=1

Depending on parameters:

- if the series diverges — output `infinity`
- if the sum is rational — output as an irreducible fraction
- if the sum is irrational — output `irrational`

---

### **Task 4**

Game problem:

- Players alternately take from 1 to `m` numbers from the beginning of a sequence  
- Taken numbers are removed  
- Their sum is added to the player's score  
- The game continues until all numbers are removed  
- Both players act optimally  
- Determine the winner  

---

### **Task 5***

Coffee cooling simulation based on Newton’s law:
dT/dt = -r (T - Ts)

Implemented:

- Temperature simulation over time  
- Data tables  
- Linear approximation  
- Correlation coefficient  
- Determination coefficient  

---

## Usage

1. Compile the required source file.
2. Run the program.
3. Enter input parameters.
4. View the results in the console.
