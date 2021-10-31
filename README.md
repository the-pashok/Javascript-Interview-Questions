# Javascript-Interview-Questions


### 1. Что такое замыкание?
<p>Замыкание - это функция в функции. Внутренняя функция имеет доступ к области видимости и параметрам внешней функции даже после возврата внешней функции.</p>

### 2. В чем разница между call, apply и bind?
<p>call и apply немедленно вызывают функцию, в то время как bind создает новую функцию, которая может быть вызвана в будущем. Аргументы в call передаются по одному, разделенные запятой, в то время как apply ожидает массив в качестве аргумента.</p>

### 3. Что такое event loop?
<p>An event loop отвечает за выполнение кода javascript, сбор и обработку событий, а также выполнение поставленных в очередь подзадач.</p>

### 4. Что такое currying function?
<p> Функция currying - это процесс преобразования функции с несколькими аргументами в последовательность функций с одним аргументом.</p>
<p>Curried functions - это отличный способ улучшить многократное использование кода и функциональную композицию</p>

### 5. Что такое прототип в javascript?
<p>Прототипы - это механизм, с помощью которого объекты JavaScript наследуются от другого объекта.</p>

### 6. Что такое memoization?
<p>Memoization - это техника оптимизации, позволяющая сохранять результат дорогостоящих вызовов функций и возвращать кэшированные результаты, когда те же самые входы повторяются.</p>

### 7. Что такое функция высшего порядка?
<p>Функция высшего порядка - это функция, которая принимает другую функцию в качестве аргумента или возвращает функцию в качестве возвращаемого значения, или и то, и другое.</p>
<p>Map, filter и reduce - это некоторые примеры функций высшего порядка, которые уже встроены в JavaScript.</p>

### 8. Что такое делегирование событий (event delegation)?
<p>Делегирование событий - это шаблон добавления одного слушателя событий к родительскому элементу вместо нескольких элементов.</p>

### 9. Назовите некоторые способы обработки асинхронных операций в javascript
<p><li>Callback - это функция, которая используется для уведомления вызывающего экземпляра</li></p>
<p><li>Promise - это объект, представляющий возможное завершение или неудачу асинхронной операции. Ожидающее обещание может быть либо выполнено со значением, либо отклонено с указанием причины.
<p><li>К возвращаемым promise прикрепляются обратные вызовы, которые делают работу с асинхронным кодом более простой и читабельной.</li></p>
<p><li>async/await - это новое дополнение к ES2017, которое представляет собой синтаксический сахар поверх обещаний и делает асинхронный код похожим на синхронный код</li></p>

### 10. Что такое рекурсия?
<p>Рекурсия - это техника итерации операций, когда функция многократно вызывает саму себя, пока не получит результат.</p>
<p>Это наиболее эффективно для решения таких задач, как сортировка или обход узлов сложных или нелинейных структур данных</p>

### 11. Что такое promise?
<p>Это объект, который может выдать одно значение когда-нибудь в будущем, либо с разрешенным значением, либо с причиной, по которой оно не было разрешено</p>

### 12. Что такое strict mode в JS?
<p>Это полезно для написания безопасного JS-кода. Он предотвращает возникновение некоторых ошибок и выбрасывает больше исключений.</p>

### 13. В чем разница между null и undefined?
<p> тип null - это объект, который явно присвоен переменной.</p>
<p>неопределенный тип - это неопределенный тип, когда переменная была объявлена, но не имеет присвоенного значения</p>

### 15. Объясните разницу между синхронным и асинхронным.
<p>Синхронная операция является блокирующей, а асинхронная - нет. Синхронный завершает текущий код до выполнения следующего кода, а асинхронный продолжает выполнение следующего кода, не завершив текущий</p>

### 16. В чем разница между var, let и const
<p>var относится к функции. let и const относятся к блокам. Доступны до ближайших фигурных скобок (функция, if-else, for-loop)</p>

### 17. Что такое DOM?
<p>Это расшифровывается как Document Object Model. Она может использоваться для доступа и изменения структуры, стиля и содержания документа.</p>
  
<br />
<br />
<br />
  
ENG

# Javascript-Interview-Questions


### 1. What is a closure?
<p>Closure is a function in a function. The inner function has access to the outer's function scope and parameters even after the outer function has returned.</p>

### 2. What are the differences between call, apply, and bind?
<p>call and apply immediately calls a function while bind creates a new function that can be invoked in the future. Arguments with call are passed in one by one, separated with a comma while apply expects an array as its argument.</p>

### 3. What is an event loop?
<p>An event loop is responsible for executing javascript code, collecting and processing events, and executing queued sub-tasks.</p>

### 4. What is currying function?
<p>A currying function is the process of taking a function with multiple arguments and turning it into a sequence of functions each with a single argument.</p>
<p>Curried functions are a great way to improve code reusability and functional composition</p>

### 5. What is prototype in javascript?
<p>Prototypes are the mechanism by which JavaScript objects inherit from another object.</p>

### 6. What is memoization?
<p>Memoization is an optimization technique by storing the result of expensive function calls and returning the cached results when the same inputs occur again.</p>

### 7. What is a higher-order function?
<p>a higher-order function is a function that accepts another function as an argument or returns a function as a return value or both of them.</p>
<p>Map, filter and reduce are some examples of higher-order functions that are already built-in to JavaScript.</p>

### 8. What is event delegation?
<p>Event delegation is a pattern of adding a single event listener to a parent element instead of multiple elements.</p>

### 9. Name some ways to handle asynchronous operation in javascript
<p><li>Callback is a function that is used to notify the calling instance</li></p>
<p><li>Promise is an object representing the eventual completion or failure of an asynchronous operation. A pending promise can either be fulfilled with a value or rejected with a reason.</li></p>
<p><li>Callbacks are attached to the returned promises that make handling of asynchronous code easier and more readable.</li></p>
<p><li>async/await is a new addition to ES2017 which is syntactic sugar on top of promises and make asynchronous code look synchronous code</li></p>

### 10. What is recursion?
<p>Recursion is a technique for iterating over an operation by having a function call itself repeatedly until it arrives at a result.</p>
<p>This is most effective for solving problems like sorting or traversing the nodes of complex or non-linear data structures</p>

### 11. What is a promise?
<p>is an object that may produce a single value sometime in the future with either a resolved value or a reason for not being resolved</p>

### 12. What is strict mode in JS?
<p>it is useful for writing secure JS code. It prevents some bugs from happening and throws more exceptions.</p>

### 13. What is the difference between null and undefined?
<p>null type is an object that is explicitly assigned to a variable.</p>
<p>undefined type is undefined where the variable has been declared but has no assigned value</p>

### 14. What is AJAX?
<p>stands for Asynchronous JavaScript and XML. We can send data to the server and get data without refreshing the page.</p>

### 15. Explain the difference between synchronous and asynchronous.
<p>Synchronous is blocking operation while asynchronous is not. Synchronous complete the current code before the next code is executed while asynchronous continue on the next code without completing the current code</p>

### 16. What are the differences between var, let, and const
<p>var is scoped to a function. let and const are block-scoped. Accessible to nearest curly braces (function, if-else, for-loop)</p>

### 17. What is the DOM?
<p>It stands for Document Object Model. This can be used to access and change the document structure, style, and content.</p>
