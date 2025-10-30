# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```c#
// See https://aka.ms/new-console-template for more information
int[] arr = new int[3];
Console.WriteLine("Enter the 3 numbers");
for(int i=0;i<arr.Length;i++)
{
    arr[i]=Convert.ToInt32(Console.ReadLine());
}
if(arr[0]>arr[1] && arr[0]>arr[2])
{
    Console.WriteLine("The largest number : "+arr[0]);
}
else if(arr[1]>arr[0] && arr[1]>arr[2])
{
    Console.WriteLine("The largest number : "+arr[1]);
}
else
{
    Console.WriteLine("The largest number : "+arr[2]);
}
```

## Output:
![c#](https://user-images.githubusercontent.com/75234588/188310185-aee29ae4-d04f-47a8-a26d-13809c23c812.PNG)


## Result:
Thus the C# program to find the largest of three numbers is executed successfully
