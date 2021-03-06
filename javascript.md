## Общие требования к написанию javascript

1. **Важно** ❗️Для написания нового функционала/логики запрещено использование библиотеки jQuery. JQuery разрешено использовать если нет других вариантов расширения функционала плагинов и библиотек (прим. WooCommerce).
2. **Важно** ❗️При написании нового функционала/логики необходимо использовать возможности стандарта ECMAScript 2015 и выше.
3. При объявлении переменных предпочтение отдается ключевым словам `let` и `const`. Переменные объявляются через `var` только при наличии проблем с поддержкой ECMAScript 2015
4. Все переменные должны быть названы в верблюжьем регистре (camelCase). Исключения составляют константы, которые должны именоваться прописными буквами в константном регистре (CONSTANT_CASE) и названия классов, функций-конструкторов и перечислений, которые именуются с заглавной буквы (PascalCase)
5. Запрещено использовать имена переменных, которые используются во внешних областях видимости
6. Запрещено называть переменные и свойства [ключевыми словами JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#Keywords)
7. Запрещено использовать переменные, не объявленные ранее. При использовании переменной, объявленной в другом модуле в глобальной области видимости, нужно обращаться к ней как к свойству объекта** `window`
8. Запрещено напрямую обращаться к значению `undefined`. Для проверки типа рекомендуется использовать `typeof`. Исключение составляет явная передача `undefined` при вызове функции вместо аргумента, чтобы использовать значение параметра по умолчанию
9. Все точки с запятой должны быть проставлены явно.
10.
11. Новые функции не создаются с помощью конструктора `Function`
12. В стрелочных функциях всегда используются скобки для параметров, даже если параметр один
13. Вместо коллекции `arguments`, используется rest-оператор, если это позволяет версия языка
14. В коде не используются оставленные выводы в консоль
15. В коде нет забытых инструкций`debugger`
