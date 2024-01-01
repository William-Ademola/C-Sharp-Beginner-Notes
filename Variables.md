>[!Note]
>Console.ReadKey() ensures the program doesn't end until we press the enter key when getting output in the console.

Such as in other programming languages we can create our own variables and store numbers, characters , strings and bool.
I'm going to show how i can create my own variables in C-sharp.

>[!Variables in C#]
>Int , double, char, string, bool.

To create a variable we have two steps:
- Declaration - In C# you can declare a variable by specifying its type e.g. int, string , double and then giving the variable a name.
- Initialization - This is when you assign to a variable its **first** value at the time of its creation

```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args)
        {
          int x; //declaration
          int x = 2024; //initialization

          int z = 2023; //This is declaration +initialization

          int a = x + z;

          Console.WriteLine(x); //dispaly variable x in console
          Console.WriteLine(y); 
          Console.WriteLine(a); //you can also solve some addition
          Console.ReadKey();
        }
   }
} 
```

To better store things we can give more unique names that describe what kind of value that these variables contain.

```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args)
        {
            int age = 21; // only stores whole integer
            double height = 300.5;
            bool tall = false; // stores on truth vales true or false
            char symbol = '@' //just a single character

            Console.WriteLine("Your age is " + age); //age not in quotes
            Console.WriteLine("Your height is " + height + "cm");
            Console.WriteLine("Are you tall? " + tall);
            Console.WriteLine("Your symbol is " + symbol);
            Console.ReadKey();
        }
   }
}
```

