# Основные правила typescript-eslint

*В таблице не рассматриваются правила включенные в plugin:@typescript-eslint/recommended*

| rules | приемщество  | link  |
|--|--| -- |
| @typescript-eslint/member-delimiter-style  | единый стиль объявления типов/интерфейсов  | [link](https://github.comypescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/member-delimiter-style.md) |
| @typescript-eslint/ban-types | запрет использования определённых типов, <br> например запрет использоавть тип String <br> вместо string и т.д., а также позволяет добавить <br> собственное сообщение и вариант исправления  | [link](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/ban-types.md) |
| @typescript-eslint/no-invalid-void-type | Запрет использования типа void, за исключением <br> возвращаемого значения функций | [link](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-invalid-void-type.md) |
| @typescript-eslint/no-unnecessary-boolean-literal-compare | Сокращение кода, за счёт удаление ненужного <br> сравнения логических значений с логическими <br> литералами <br> напрмер: <br> ```const value: boolean; if (value === true) {}```  | [link](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-unnecessary-boolean-literal-compare.md) |
| @typescript-eslint/no-unnecessary-condition | Соркащение кода, за счёт удаление ненужных <br> логических условий, в которых значение всегда <br> являются только true/false | [link](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-unnecessary-condition.md) |
| @typescript-eslint/type-annotation-spacing | пробелы вокруг оператора присвоения типа | [link](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/type-annotation-spacing.md) |

