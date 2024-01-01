```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
              Console.WriteLine();
              Console.Write();
        }
   }
}
```
In this block of code there are two ways to display output in your console.
The WriteLine method which prints the output on a new line and the Write method which prints the output on the same line and it doesn't create a new line

```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
              Console.WriteLine("Hello World");
              Console.WriteLine("this is a program");
              Console.Write("Hey!");
              Console.Write("Williams");
        }
   }
}
```
This prints out in the console as:
*Hello world
this is a program
Hey! Williams*

# <u>Comments</u>

```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
            Console.WriteLine("commenst are fun");

            //This a comment
            /*This 
            *is
            *a
            *multi
            *line   
            *comment
            */
            Console.Write("Interesting");
   }
}
```


# <u>Escape Sequences</u>
To format our output we can add an escape sequence to a string.
The following list shows some of the widely used **escape sequences in C#**.

- `\’` – Output a **Single quote**
- `\”` – Output a **double quote** - If you want to embed quotes into an already quoted string
- `\` – Output a **Backslash** 
- `\n` – Insert a **newline**
- `\r` – Insert a **carriage-return**
- `\t` – Insert a **tab**
- `\0` – Insert a **null character**
- `\b` – Insert a **backspace**

```C#
using System;

namespace MyFirstProgram{

   class Program{
        static void Main(string[] args){
            Console.WriteLine("Escape\nSequence");
            Console.WriteLine("this is not \"Interesting"."); 
            Console.WriteLine("I \"like\" dq"); //this outputs a double quote
            Console.WriteLine("I l\tike codm"); //this outputs a tab
            
            
   }
}

```