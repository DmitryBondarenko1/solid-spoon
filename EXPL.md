**Отчет о выполненном тестовом задании.**

**Постановка задачи.**

В качестве тестового задания требуется переписать одну из глав руководства пользователя IntelliJ IDEA:

https://www.jetbrains.com/help/idea/working-with-consoles.html

Допускаются любые необходимые изменения. Результат должен представлять собой README.md, опубликованный в отдельном репозитории на GitHub. При необходимости, репозиторий может содержать и другие файлы, на которые README.md может ссылаться.

Срок выполнения задания – 2 недели.

**Выполнение задания.**

Выполение задания проведем в несколько этапов:

 1. Анализ существующей документации
 2. Анализ запросов пользователей на тему консолей
 3. Формирование документации
 4. Подготовка контента

**1. Анализ существующей документации.**

Раздел **Managing Consoles**, располагается в главе **Configuring IDE** IntelliJ IDEA Help и содержит статьи:

 - Running Console
 - Configuring Output Encoding
 - Configuring Color Scheme for Consoles
 - Using Consoles
 - Working with Embedded Local Terminal

Сначала отметим общие замечания к предлагаемой документации:

 - Несоответствие темы главы **Configuring IDE** и тем раздела **Running Console**, **Using Consoles**, **Working with Embedded Local Terminal**. Конфигурация не имеет отношения к запуску или использованию консоли.
 
 - Неточности. В разделе описывается функционал консолей, однако нет разделения между обычными консолями приложения и специфическими консолями - **JShell**, **Terminal**, **Groovy**, **TypeScript**, **JPA**. Это неверно, т.к. функционал обычных консолей не применим к вышеперечисленным (например, в обычных консолях недоступны функции **Code completion**, **Syntax check with inspections**, **Automated insertion of paired brackets, quotes and braces**, **Scrolling through the history of commands using the arrow keys**, **Quick documentation lookup**).
 
 - Нарушен порядок следования тем - **Running**, **Configuring**, **Using**
 
 - Отсутствуют примеры. Теоретический материал должен быть подкреплен практическими примерами.
 
 - Для анализа посещаемости сайта с документацией я бы по возможности использовал инструменты автоматического трекинга пользовательской активности типа Google Analytics. Но т.к. доступ к этому инструментарию для предлагаемой документации отсутствует, это не представляется возможным. В принципе, этот инструмент позволяет понять, насколько темы, включенные в документацию актуальны и востребованы пользователями и как следствие добавить новые разделы или исключить нерелевантные.
 
  - Неполная информация/не раскрыты некоторые потенциально актуальные темы. Например, нет описания выбора шрифта консоли или функции изменения размера консоли. 
  
**2. Анализ запросов пользователей на тему использования консолей в приложении.**

Для анализа запросов пользователей на тему консолей в **IntelliJ IDEA** проведем исследование community **StackOverflow**. 

В результате проведенного исследования составим список вопросов, которые впоследствии мы сможем использовать для формирования структуры нашей документации.

| Use case | Тема документации |
|--|--|
| How / can I display a console window in Intellij IDEA? | How to open Terminal, Using Terminal |
| How to delete SQL Consoles from Intellij IDEA Database plugin? | How to delete a database console, Using Database console |
| How to display console tab of intellij | How to open Terminal, Using Terminal, Running Consoles |
| IntelliJ IDEA - How to reattach and place Console tab back to IDE | Managing Consoles |
| java - How do I color my output in the console in Intellij using | Customizing Console Colors |
| Colorize console output in Intellij products | Customizing Console Colors  |
| java - IntelliJ and Console Output Colors | Customizing Console Colors |
| java - How to color System.out.println output?  | Customizing Console Colors, ANSI |
| Intellij 14 console not respecting ANSI colors  | Customizing Console Colors, ANSI |
| can't adjust console color scheme – IDEs Support | Selecting Color Scheme |
| How to set different color scheme for console in | Selecting Color Scheme |
| Is it possible to change the console font size in IntelliJ IDEA | Customizing Console Font |
| Set terminal font size in PhpStorm? | Customizing Console Font |
| How to increase fonts in all UI elements in IntelliJ IDEA? | Customizing Console Font |
| Displaying Console and Debugger at same time in IntelliJ?| Managing Console, Float, Move |
| development environment - Intellij: Search console output | Managing Console, Find |
| IntelliJ IDEA - How to reattach and place Console tab back to IDE | Managing Console, Float |
| How to see Maven console in IntelliJ? | Running Console |
| Where does IntelliJ IDEA store database console scripts? | Other Hacks |
| debugging - IntelliJ IDEA set default debug view to console view | Managing Consoles, Focus On Startup |
| java - Intellij Idea incorrect encoding in console output | Fixing Output Encoding |
| How to open two terminal windows in IntelliJ IDEA, PyCharm? | Using Terminal |
| java - How do I color my output in the console in Intellij using | Customizing Console Colors |
| Как настроить отдельный терминал Intellij IDEA?| Managing Console |
| java - How to use IntelliJ Groovy interactive console as | Groovy Console|
| IntelliJ IDEA groovy console in Java maven project | Groovy Console |
| Javascript in IntelliJ's “IDE scripting console” | Typescript Console |

**3. Формирование документации**

Таким образом, на основе вышеперечисленных отзывов и анализируя функционал приложения, формируем структуру будущей документации, см. файл ниже. Жирным в тексте отмечены разделы, непосредственно затрагивающие тему консолей. В процессе наполнния информацией, структура может меняться. В каждой статье предусмотрены перекрестные ссылки на релевантные разделы.

[**Содержание**](Contents.md)

**4. Подготовка контента**.

В качестве примера, подготовил две статьи на тему конфигурации внешнего вида консоли. Первая статья написана в стиле user guide, соответствующий раздел встроен в содержание из предыдущего пункта. Вторая - в формате блога или туториала.

 - **[Customizing Console Colors](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/ConsoleColor.md)** 
 - **[Customizing, Running, and Managing Consoles](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/Console.md)** 

**Преимущества первого подхода**

 - Формальное изложение, подходит для официальной документации, юзер гайда
 - Тематический подход с разделением на конкретные задачи, позволяет отвечать на вопросы как продвинутых так и новых пользователей
 - Имеются ссылки на релевантные аналогичные статьи по этой же тематике

**Преимущества второго подхода**

 - Неформальное изложение, можно использовать материал на различных площадках, блогах
 - Сценарный подход, т.е. быстрое вовлечение новых пользователей, не знакомых с продуктом
 - При необходимости можно легко адаптировать под другой формат, референс, например
 - Имеются ссылки на релевантные аналогичные статьи по этой же тематике
 - Освещаются наиболее популярные сценарии пользователей по теме на основе реальных запросов в интернете
 - Наличие изображений, отсутствие длинных описаний, относительно небольшой размер статьи, нет переполнения информацией, это облегчает восприятие информации, позволяет сканировать текст быстро. Это актуально для современного динамичного читателя
 - Не тратится время читателя на очевидные вещи, сохраняется основной смысл без погружения в детали
















  
