
# Java Script Lecture_5_2
##   Data and Time в JavaScript

#### Date в JS

JavaScript предоставляет мощные возможности для работы с датой и временем. Встроенный объект Date позволяет создавать и манипулировать датами, а также выполнять различные операции с временем. Давайте рассмотрим основные концепции и методы работы с датой и временем в JavaScript.
Одним из самых распространенных классов в JavaScript для работы с датами и временем является класс `Date`. Вот несколько основных методов, которые предоставляет этот класс:

1. `getDate()`: Возвращает день месяца от 1 до 31 в соответствии с местным временем.
   ```javascript
   const date = new Date();
   const day = date.getDate(); // Возвращает текущий день месяца (например, 24)
   ```

2. `getMonth()`: Возвращает месяц от 0 до 11 в соответствии с местным временем. Обратите внимание, что значения начинаются с 0 для января и заканчиваются 11 для декабря.
   ```javascript
   const date = new Date();
   const month = date.getMonth(); // Возвращает текущий месяц (например, 4 для мая)
   ```

3. `getFullYear()`: Возвращает год с указанием года (4 цифры) в соответствии с местным временем.
   ```javascript
   const date = new Date();
   const year = date.getFullYear(); // Возвращает текущий год (например, 2023)
   ```

4. `getHours()`: Возвращает часы от 0 до 23 в соответствии с местным временем.
   ```javascript
   const date = new Date();
   const hours = date.getHours(); // Возвращает текущее значение часов (например, 10)
   ```

5. `getMinutes()`: Возвращает минуты от 0 до 59 в соответствии с местным временем.
   ```javascript
   const date = new Date();
   const minutes = date.getMinutes(); // Возвращает текущие минуты (например, 30)
   ```

6. `getSeconds()`: Возвращает секунды от 0 до 59 в соответствии с местным временем.
   ```javascript
   const date = new Date();
   const seconds = date.getSeconds(); // Возвращает текущие секунды (например, 45)
   ```

7. `getMilliseconds()`: Возвращает миллисекунды от 0 до 999 в соответствии с местным временем.
   ```javascript
   const date = new Date();
   const milliseconds = date.getMilliseconds(); // Возвращает текущие миллисекунды (например, 123)
   ```

8. `getTime()`: Возвращает количество миллисекунд, прошедших с 1 января 1970 года 00:00:00 UTC до указанной даты.
   ```javascript
   const date = new Date();
   const timestamp = date.getTime(); // Возвращает текущее значение времени в миллисекундах
   ```

   Вы также можете использовать методы класса `Date` для установки значений даты и времени, например:

   - `setFullYear(year)`: Устанавливает год с указанием года (4 цифры).
   - `setMonth(month)`: Устанавливает месяц от 0 до 11.
   - `setDate(day)`: Устанавливает день месяца от 1 до 31.
   - `setHours(hours)`: Устанавливает часы от 0 до 23.
   - `setMinutes(minutes)`: Устанавливает минуты от 0 до 59.
   - `setSeconds(seconds)`: Устанавливает секунды от 0 до 59.
   - `setMilliseconds(milliseconds)`: Устанавливает миллисекунды от 0 до 999.
