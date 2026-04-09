# Лабораторная работа №18 - Введение в JavaScript

**ФИО:** Лойко Арина Станиславна
**Группа:** ИСП-232
**Дата:** 16.02.2026

## Описание (что изучили)

- познакомились с языком JavaScript и его местом в веб-разработке
- разобрали основные типы данных: string, number, boolean, null, undefined, object, array
- научились объявлять переменные через let и const
- изучили явное и неявное преобразование типов
- разобрали разницу между == и ===
- поработали с консолью браузера и DevTools
- установили Node.js и запустили скрипт через терминал
- изучили условные операторы if/else, тернарный оператор и switch/case
- сравнили синтаксис JavaScript и C#

## Структура проекта

```
Lab18_LearnJs_Loiko/
├── index.html
├── main.js
├── README.md
├── .gitignore
└── img/
    ├── gitPushLab18_Loiko.png
    ├── step6_variablesLab18_Loiko.png
    ├── step7_typeofLab18_Loiko.png
    ├── step8_typeConversionLab18_Loiko.png
    ├── step9_strictLab18_Loiko.png
    ├── step10_consoleLab18_Loiko.png
    ├── step11_nodeLab18_Loiko.png
    └── step12_conditionsLab18_Loiko.png
```

## JavaScript vs C#

| Аспект | C# | JavaScript |
|---|---|---|
| Типизация | Статическая | Динамическая |
| Компиляция | Да (в IL-код) | Нет (интерпретация/JIT) |
| Точка входа | Main() | Отсутствует |
| Переменные | int x = 5; | let x = 5; |
| Константы | const int X = 5; | const X = 5; |
| Вывод в консоль | Console.WriteLine() | console.log() |
| Проверка типа | Во время компиляции | typeof |
| Сравнение | == (по значению) | === (строгое) |
| Условия | if/else/switch | if/else/switch + тернарный |
| Циклы | for/while/do-while/foreach | for/while/do-while/for...of |
| Функции | Методы с типами | Функции без типов |
| Массивы | int[] arr = new int[5]; | let arr = []; |
| Объекты | Требуют класс | Можно создать литералом |
| ООП | Классическое | Прототипное |
| Null | null | null и undefined |
| Строгость | Высокая (компилятор) | Низкая (нужна дисциплина) |

## Главные выводы

1. JavaScript гибче C# - можно менять типы переменных
2. JavaScript проще синтаксически - меньше церемоний
3. JavaScript опаснее - ошибки находятся во время выполнения
4. C# безопаснее - компилятор не даст допустить многие ошибки
