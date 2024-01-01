```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
              Console.WriteLine("Hello World!");
        }
   }
}
```
This is the boilerplate for a running a c-sharp program in the editor. Its pretty similar to Java. (using system) seems to give access to the OS while namespace is just the project name. The program prints hello world to the console. By the way for now take  static void Main(string[] args) as a set of magical words that you need to make your program run.

```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
              Console.WriteLine("I like dq");
              Console.WriteLine("I like codm");
              Console.Beep();
        }
   }
}
```
 
 This code prints out the words in the Writeline method and the Beep method just makes you console beep which is fun cause i didn't know programming languages could make your console do that.

The console in (console.) is know as a class and it represents the standard input, output, and error streams for console applications. This class cannot be inherited.

>[!Important note]
>If you set up your machine to run .NET 6, which includes the C# 10 compiler. t=Then you get a feature called top level statements.
>Top-level statements enable you to avoid the extra ceremony required by placing your program's entry point in a static method in a class.

This syntax
```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
              Console.WriteLine("Hello World!");
        }
   }
}

```

Becomes this
```C#
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
```
