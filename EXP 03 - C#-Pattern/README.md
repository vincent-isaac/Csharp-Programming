# Ex03- Pattern

## Aim: To write a C# program for a pascal's triangle.

## Algorithm:

### Step 1: 
Initialize the necessary attributes.
### Step 2:
Get the limit from the user.
### Step 3:
using for loop print the rows and columns and space.
### Step 4:
Check the first and last rows of the triange is 1 using if condition.
### Step 5:
Otherwise use else to print the inner value

val = val * (i - j + 1) / j;
### Step 6:
Check the program for any error.

if not.
### Step 7:
print the program.


## Program:
```c#
namespace program4;
    public class Class1
    {
        static void Main(string[] args)
        {
            int num,value=1;
            Console.WriteLine("Enter the size of the pascal's triangle :");
            num=Convert.ToInt32(Console.ReadLine());
            for(int i =0;i<num;i++)
            {
                for(int space=0;space<num-i;space++)
                    Console.Write(" ");
                for(int j=0;j<=i;j++)
                {
                    if(i==0 || j==0)
                        value=1;
                    else
                        value=value*(i-j+1)/j;
                    Console.Write(value+" ");
                }
            Console.WriteLine();
                
            }        
        }
    }
```
## Output:

![c# ex3](https://user-images.githubusercontent.com/75234588/189466049-6aa61089-3c5d-4ca9-8531-a04a05b1a790.PNG)

## Result: 
Thus the C# program to display for a pascal's triangle is executed successfully.
