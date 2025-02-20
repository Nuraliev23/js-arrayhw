# Array
Массивы в JavaScript — это структуры данных, которые позволяют хранить несколько значений в одном контейнере. Массивы являются упорядоченными коллекциями, и каждый элемент массива имеет свой индекс, начиная с 0.
## Основные особенности массивов:
1.Индексированность: элементы массива имеют числовые индексы, начиная с 0.
2.Типы данных: массивы могут содержать данные разных типов — числа, строки, объекты, функции и т.д.
3.Динамичность: размер массива может изменяться — элементы можно добавлять или удалять.

## Как создаются массивы
Массив можно создать с помощью литерала массива или конструктора Array:
let fruits = ['apple', 'banana', 'orange'];
console.log(fruits);  // ["apple", "banana", "orange"]

Также можно создать пустой массив:
let emptyArray = [];

## Доступ к элементам массива
Для получения элемента массива используется его индекс:
let fruits = ['apple', 'banana', 'orange'];
console.log(fruits[0]);  // "apple"
console.log(fruits[2]);  // "orange"

## Примеры задач с массивами
Напишите функцию, которая принимает массив и возвращает его в обратном порядке.
function reverseArray(arr) {
  return arr.reverse();
}

let numbers = [1, 2, 3, 4, 5];
console.log(reverseArray(numbers));  // [5, 4, 3, 2, 1]

## 2. Задача: Подсчитать количество элементов в массиве
Напишите функцию, которая возвращает количество элементов в массиве.
function countElements(arr) {
  return arr.length;
}

let animals = ['cat', 'dog', 'elephant'];
console.log(countElements(animals));  // 3

## 3. Задача: Найти максимальное число в массиве
function findMax(arr) {
  return Math.max(...arr);
}

let numbers = [10, 20, 5, 50, 30];
console.log(findMax(numbers));  // 50

## 4. Задача: Проверить, есть ли элемент в массиве
   Напишите функцию, которая проверяет, содержится ли определённый элемент в массиве.
   function contains(arr, value) {
  return arr.includes(value);
}

let fruits = ['apple', 'banana', 'orange'];
console.log(contains(fruits, 'banana'));  // true
console.log(contains(fruits, 'grape'));   // false

## Основные методы массивов:
push() — добавляет элемент в конец массива.
pop() — удаляет последний элемент массива.
shift() — удаляет первый элемент массива.
unshift() — добавляет элемент в начало массива.
forEach() — выполняет функцию для каждого элемента массива.
map() — создает новый массив, применяя функцию к каждому элементу исходного массива.
filter() — создает новый массив, включающий только те элементы, которые удовлетворяют условию.
reduce() — применяет функцию для накопления результата из всех элементов массива.

## Когда использовать массивы?
Массивы удобны для работы с упорядоченными данными, например, для хранения списков, очередей, стеков и других коллекций, где порядок элементов имеет значение.
Массивы являются мощным инструментом в JavaScript для обработки данных и их манипуляций!
