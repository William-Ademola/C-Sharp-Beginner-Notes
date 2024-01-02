In C# type casting is the process of converting on data type to another.
In C#, there are two types of casting:

- **Implicit Casting** (automatically) - converting a smaller type to a larger type size  
    `char` -> `int` -> `long` -> `float` -> `double`  
      
- **Explicit Casting** (manually) - converting a larger type to a smaller size type  
    `double` -> `float` -> `long` -> `int` -> `char`

Remember, type casting is only possible if both the data types are compatible with each other. If they are not, you will get a compile-time error.
```C#
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
String str = "300";
int num = int(str);//this will result in a compile error

```

Ok back to typecasting and don't mind the lack of top level statements. Sometimes i like my magical spells.
```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
              Console.WriteLine("Wingardium");
             

              //Implicit Casting
              int sum = 200;
              double num = sum;

              //Explicit casting
              int number = 20;
              double age =25;
              bool fact = true;


             Console.WriteLine(Convert.ToString(number));//int to string
             Console.WriteLine(Convert.ToInt32(age));//double to string
             Console.WriteLine(Convert.ToString(fact));//bool to string
        }
   }
}
```
