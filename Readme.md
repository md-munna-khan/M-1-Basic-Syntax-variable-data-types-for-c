## M-1-Basic-Syntax-variable-data-types-for-c

### what is programming 
- the process of creating specific instructions—or code—that tell a computer how to perform tasks, solve problems, or automate processes

### what is programming  Language 
- when we talk to  chinese person need talk to him in chinese language 
same to same computer only understand programming language 
- thousand of language have 

### why choose C ?
- c is a structured language and mother of programming language 
- there is no built in library or function so we can learn from zero 

### 1-1 Introduction

- what will we learn?
1.Basic structure of a C program
2. Printing in C
3. Taking Input in C
4. Variable and Data types 
5. Data Types Limitation
6. Variable naming Rules 

## 1-2 Basic Structure of C Programming Animated
- it has two parts 
  1. **Head Part** - hold the header files (saves time and make us avoid some complicated code running behind the scene) 
  2. **Main Part** - Holds the main code

  ## 1-3 First C Program Animated
  - c programming syntax

  ```c
  # include <stdio.h> // as like brain he provide signal in main code 
  int main ()
  {
    printf("Hello world");// printf mean output print in terminal
    return 0;
  }
  ```
  - stdio = standard input and output 

  ## 1-4 Running our first code
  
```c
# include <stdio.h>
int main () // this is the main function and its a function return type

{
    printf("hello world"); // we have not wrote the function of printing its coming from header file 
    return 0; // return 0 means the code has run successfully
}
```
- c programming starts to execute from main function 

## 1-5 Printing in C


```c
#include<stdio.h>
int main()
{
    printf("I am Sazid\n"); // for printing with brake \n is used 
    printf("demon\n");
    printf("dem\ton");
    return 0;
}
```

- for printing with brake **\n** is used
- for the *Tab Space* we can use *\t*

## 1-6 Variables and Data Types Animated

###  what is variable ?
- for example you going to shop buy vegetables
in there vegetables is data and your bag is variable 
- variable is store of data 


### Variable and Data Type

1. *int* -> -100, 0, 100
2. *float* -> -2.5, 5.46
3. *char* -> 'a', 'A', '@', 'H'
4. *boolean* -> True or False

## 1-7 Variables in C


```
data-type variable name 
```

```c
#include<stdio.h>
int main()
{
    int num; // declaring avariable will be stored in memory and we will assign data. 
    num=10;
    // or we can also write 
    int num1 = 10; 
    num1 = 20;
    float f = 3.56;
    char c = 'i am sazid';
    return 0;
}
```
- variable is stored in memory and value is assigned and the code will be executed line by line 

- *int* holds *4 byte space* in memory, *float* holds *4 byte space* in memory, *char* holds *1 byte space* in memory
 
- *1 byte* means *8 bit*. 010101(here is 6 bit) as compute understand 0 and 1 these are bit. 
- *1024 bit* means *1 kb*
- *1024 kb* means *1 mb*
- *1024 mb* means *1 gb*
- *1024 gb* means *1 tb*