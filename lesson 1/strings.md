## Способы записи строковых знанчений

```js
// Используя одинарные кавычки
const text = 'Some awsome text'

// Используя двойные кавычки 
const message = "Let's study JavaScript together"

// Используя экранирование кавычек
const singleQuoteMsg = 'Let\'s use only single quotes'

// Используя обратные кавычки (Template Strings / шаблонные строки)
const templateString = `We can use backticks`
```

> Важно помнить, открывающие и закрывающие кавычки должны совпадать,
> т.е. мы не можем открыть строку одинарной кавычкой, а закрыть — двойной.

```js
const wrong_string = 'some string"
```

## Операции над строками

### Конкатинация строк

```js
const concatString = 'first string' + ' second string'
// "first string second string"
```

### Конкатинация строк, используя переменные
```js
const firstName = 'Dmitry'
const birthYear = 1988

const result = "My name is " + firstName + ", I'am " + (new Date().getFullYear() - birthYear) + " years old."
```

### Используя шаблонные строки
```js
const result = `My name is ${firstName}, I'm ${new Date().getFullYear() - birthYear} years old`
```

## Методы работы со строками
```js
// Проверка содержит ли строка нужные символы
'some test'.startsWith('so') // true
'some test'.endsWith('xt') // true
'some test'.includes('so') // true
'some test'.search(/text/) // 5

// Получение символов
'some test'.match(/some/g) // ["'some"]
'some test'.substr(2,3) // "me "
'some test'.substring(2, 3) // "m"

// Преобразование строки
'some test'.replace('x', 'S') // "some teSt"
'some test'.split(' ') // ["some", "text"]

// Конвертация регистра
'some test'.toUpperCase() // "SOME TEXT"
'SoMe TexT'.toLowerCase() // "some text"
```
