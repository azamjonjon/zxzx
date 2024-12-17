# Методы строк (String) в JavaScript

JavaScript предоставляет множество методов для работы со строками. Ниже приведён подробный обзор наиболее часто используемых методов строк, сопровождаемый примерами и краткими пояснениями.

## Содержание
1. [Базовые методы строк](#базовые-методы-строк)
   - `length`
   - `charAt()`
   - `includes()`
   - `indexOf()`
2. [Методы для работы со строками](#методы-для-работы-со-строками)
   - `slice()`
   - `substring()`
   - `toLowerCase()` / `toUpperCase()`
   - `trim()`
3. [Продвинутые методы](#продвинутые-методы)
   - `replace()`
   - `split()`
   - `repeat()`
   - `padStart()` / `padEnd()`

---

## 1. Базовые методы строк

### `length`
Возвращает длину строки.

```javascript
let str = "Hello, World!";
console.log(str.length); // Результат: 13
```

![Пример метода length](https://via.placeholder.com/500x150?text=Пример+метода+length)

### `charAt()`
Возвращает символ по указанному индексу.

```javascript
let str = "Hello";
console.log(str.charAt(0)); // Результат: H
```

![Пример метода charAt](https://via.placeholder.com/500x150?text=Пример+метода+charAt)

### `includes()`
Проверяет, содержит ли строка указанную подстроку.

```javascript
let str = "Hello, World!";
console.log(str.includes("World")); // Результат: true
```

### `indexOf()`
Возвращает индекс первого вхождения подстроки или -1, если подстрока не найдена.

```javascript
let str = "Hello, World!";
console.log(str.indexOf("World")); // Результат: 7
```

---

## 2. Методы для работы со строками

### `slice()`
Извлекает часть строки и возвращает её как новую строку.

```javascript
let str = "Hello, World!";
console.log(str.slice(7, 12)); // Результат: World
```

### `substring()`
Похож на `slice()`, но не принимает отрицательные индексы.

```javascript
let str = "Hello, World!";
console.log(str.substring(7, 12)); // Результат: World
```

### `toLowerCase()` / `toUpperCase()`
Преобразует строку в нижний или верхний регистр.

```javascript
let str = "Hello";
console.log(str.toUpperCase()); // Результат: HELLO
console.log(str.toLowerCase()); // Результат: hello
```

### `trim()`
Удаляет пробелы с начала и конца строки.

```javascript
let str = "   Hello, World!   ";
console.log(str.trim()); // Результат: "Hello, World!"
```

---

## 3. Продвинутые методы

### `replace()`
Заменяет указанную подстроку на другое значение.

```javascript
let str = "Hello, World!";
console.log(str.replace("World", "JavaScript")); // Результат: Hello, JavaScript!
```

![Пример метода replace](https://via.placeholder.com/500x150?text=Пример+метода+replace)

### `split()`
Разбивает строку на массив по указанному разделителю.

```javascript
let str = "apple,banana,cherry";
console.log(str.split(",")); // Результат: ["apple", "banana", "cherry"]
```

![Пример метода split](https://via.placeholder.com/500x150?text=Пример+метода+split)

### `repeat()`
Повторяет строку указанное количество раз.

```javascript
let str = "Hello! ";
console.log(str.repeat(3)); // Результат: Hello! Hello! Hello! 
```

### `padStart()` / `padEnd()`
Дополняет строку другими символами до достижения заданной длины.

```javascript
let str = "5";
console.log(str.padStart(3, "0")); // Результат: 005
console.log(str.padEnd(3, "0"));   // Результат: 500
```

---

## Заключение
Эти методы строк предоставляют мощные инструменты для работы с текстом в JavaScript. Понимание этих методов необходимо для эффективного написания кода.

