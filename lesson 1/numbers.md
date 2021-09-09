## Числа в JS

```js
// Целое число
const number = 1234
typeof number // number
// Десятичная дробь
const numberDec = 3.14
typeof numberDec // number
```

## Операции над числами
[Операторы в JS](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators)

```js
// Сложение
5 + 7 // 12
// Вычитаение
12 - 8 // 4
// Умножение
4 * 5 // 20
// Деление
10 / 2 // 5
// Возведение в степень
2 ** 3 // 8
// Остаток от деления
10 % 2 // 0
10 % 3 // 1
```

Арифметические операторы можно применять как над числами, так и над переменными, хранящими значения чисел
```js
const a = 10
const b = 5

a + b // 15
a * b // 50
```

## Объект Number
[Документация](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Number)

```js
Number.isInteger(1234) // true
Number.isInteger(3.14) // false
```

## Явное приведение строки к числу

```js
// Приведение к целому числу
Number.parseInt('123', 10) // 123
Number.parseInt('3.14', 10) // 3

//Приведение к десятичной дроби
Number.parseFloat('123') // 123
Number.parseFloat('3.14') // 3.14
// Разделитель целой и дробной части - точка
Number.parseFloat('3,14') // 3

// Используя конструктор Number
Number('123') // 123
Number('3.14') // 3.14
```

## Объект Math
[Документация](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Math)

### Math.ceil

Округляет аргумент до ближайшего большего целого.
```js
Math.ceil(.95);    // 1
Math.ceil(4);      // 4
Math.ceil(7.004);  // 8
Math.ceil(-7.004); // -7
```

### Math.floor
Округляет аргумент до ближайшего меньшего целого.
```js
Math.floor( 45.95); //  45
Math.floor(-45.95); // -46
```

### Math.random
Возвращает псевдослучайное число с плавающей запятой из диапазона от 0 (включительно) до 1 (не включительно) 
```js
Math.random() // 0.888564701982437
Math.random() // 0.9151106882899831
```
