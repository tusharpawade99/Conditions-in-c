# Conditions-in-c
Condtions allow a program to think for itself. Many times there will be moments when you want your program to decide from different options depending on the input you give to it.


1) If Statement
Syntax :
   if(x > y) 
   { 
   printf("x is greater than y");
   }
   
Example:
  #include<stdio.h>
  #include<conio.h>
  void main()
  {
    int x=5;
    if(x>0)
    {
        printf("%d",x);
    }
  }
  
2)If Else Statement
Syntax :
       if(x > y) 
   { 
   printf("x is greater than y");
   }else
   {
    printf("y is greater than x");
    }
    
 Example:
  #include<stdio.h>
  #include<conio.h>
  void main()
  {
    int x=5;
    if(x>10)
    {
        printf("x is greater than 10");
    }else
   {
    printf("x is smaller than 10");
    }
  }
  
  
  3)Else If Statement
  Syntax:
      if (condition1) 
      {
         //These statements would execute if the condition1 is true
      }
      else if(condition2) 
      {
         //These statements would execute if the condition2 is true
      }
      else if (condition3) 
      {
         //These statements would execute if the condition3 is true
      }
    Example:
               #include <stdio.h>
              int main()
              {
                 int var1, var2;
                 printf("Input the value of var1:");
                 scanf("%d", &var1);
                 printf("Input the value of var2:");
                 scanf("%d",&var2);
                 if (var1 != var2)
                 {
                printf("var1 is not equal to var2\n");
                //Nested if else
                if (var1 > var2)
                {
                  printf("var1 is greater than var2\n");
                }
                else
                {
                  printf("var2 is greater than var1\n");
                }
                 }
                 else
                 {
                printf("var1 is equal to var2\n");
                 }
                 return 0;
              }
              
   
4) Conditional Operators

   
 Syntax     : 
 (Condition? true_value: false_value);  
   
Example :   
          #include <stdio.h>
           int main()
          {
             int x=1, y ;
             y = ( x ==1 ? 2 : 0 ) ;
             printf("x value is %d\n", x);
             printf("y value is %d", y);
          }
