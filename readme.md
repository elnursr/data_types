# C# Data Types with simple examples

### Convert to old **Main** method in Visual Studio

'Ctrl + . ' => like the picture below: 

![image](./assets/media/convert_to_program_main_style.jpg)

### Code example:
```csharp
int x = 7;
double y = 7.7;
string text = "This's string";
bool is_false = false;
char z = 'z';

double x = 7;
double y = 9;

double addition = x + y;
double subtraction = x - y;
double multipication = x * y;
double division = x / y;

Console.WriteLine("addition result: " + addition);
Console.WriteLine("subtraction result: " + subtraction);
Console.WriteLine("multipication result: " + multipication);
Console.WriteLine("division result: " + division);

int a = 5;
int b = 3;
int remainder = a % b;
Console.WriteLine("remainder result: " + remainder);

Console.Write("Please enter your age: ");
int age = int.Parse(Console.ReadLine());

if (age >= 18)
{
    Console.ForegroundColor = ConsoleColor.Green;
    Console.WriteLine("You can get to exam for driving");
}

else
{
    Console.ForegroundColor = ConsoleColor.Red;
    Console.WriteLine("You can't get to exam for driving!!!");
}
```