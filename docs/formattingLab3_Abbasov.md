**жирный текст**
*курсив*
***жирный курсив***
~~зачеркнутый~~
`console.writeline("Hello");`

```csharp
string name;
name = Console.Readline();
Console.WriteLine();
```

# Задание: Комментированная программа на C#
Создайте консольное приложение на C#, которое демонстрирует все форматы
Markdown в комментариях к коду.
### Создайте консольное приложение на C#, которое демонстрирует все форматы
Markdown в комментариях к коду.

1. **Имя файла:** FormatDemo.cs
2. **Логика:**
    - Запрашивает у пользователя два числа;
    - Выполняет их сложение;
    - Выводит результаты в форматированном виде.
___
```csharp
Console.Writeline("введите первое число: ");
double number1 = Convert.ToDouble(Console.Readline());
Console.Writeline("введите первое число: ");
double number2 = Convert.ToDouble(Console.Readline());
double sum = number1 + nummber2;
Console.Writeline($"**Результаты операций: {sum}**");
```