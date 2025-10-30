### EX NO : 02
### DATE  : 
# <p align="center">Palindrome</p>



## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare two variable with string datatype
### Step3:
Loop over the entire string and reverse it
### Step4:
Use if condition to check whether the string and the reversed string is equal or not
### Step5:
print palindrome if it's equal else print not a palindrome.
### Step6:
stop
<br/><br/><br/><br/><br/><br/><br/>

## Program:
```c#
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string name;
            Console.WriteLine("Enter then string to check palindrom");
            name=(Console.ReadLine());
            string temp = new string(name.Reverse().ToArray());
            if(name==temp)
            {
                Console.WriteLine("Palindrome :"+temp);
            }
            else{
                Console.WriteLine("Not a palindrome :"+temp);
            }
        }
    }
}
```

## Output:

![c# ex2](https://user-images.githubusercontent.com/75234588/189261907-b1091051-2aea-4a54-8a2e-4827d1b52a8e.PNG)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
