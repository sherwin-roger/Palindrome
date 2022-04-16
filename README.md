# Palindrome


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
## Program:
```
using System;  
namespace palindrome  
{  
    class Program  
    {  
        static void Main(string[] args)  
        {  
            string s,revs="";  
            Console.WriteLine(" Enter string");  
            s = Console.ReadLine();  
            for (int i = s.Length-1; i >=0; i--) 
            {  
                revs += s[i].ToString();  
            }  
            if (revs == s) 
            {  
                Console.WriteLine("String is Palindrome");  
            }  
            else  
            {  
                Console.WriteLine("String is not Palindrome");  
            }  
        }  
    }  
}
```
## Output:
![image](https://user-images.githubusercontent.com/75235128/163684681-2371f78d-fb65-4251-a8f0-8c852ccb0036.png)
## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
