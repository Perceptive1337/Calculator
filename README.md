# Calculator
/*Excercise 2.19 minor calculator 2017-03-31*/                                                                                          
#include <stdio.h>

int main(void)
{
 int Num1, Num2, Num3;
 printf("Input three different integers: ");
 scanf("%d%d%d", &Num1, &Num2, &Num3); 
 printf("Sum is %d\n", Num1+Num2+Num3);
 printf("Average is %d\n", (Num1+Num2+Num3)/3);
 printf("Product is %d\n", Num1*Num2*Num3);
 
  /*Determine smallest*/
 int Smallest;
 if (Num1 < Num2 && (Num1 < Num3))
  {
   Smallest = Num1;
  }

 else if (Num2 < Num1 && (Num2 < Num3))
  {
   Smallest = Num2;
  }

 else if (Num3 < Num1 && (Num3 < Num2))
  {
   Smallest = Num3;
  }
 else
 {
  Smallest = Num1;
 }
  printf("Smallest is %d\n", Smallest);
 
  /*Determine largest*/
  int Largest;
  if (Num1 > Num2 && (Num1 > Num3))
  {
   Largest = Num1;
  }

  else if (Num2 > Num1 && (Num2 > Num3))
  {
   Largest = Num2;
  }

  else if (Num3 > Num1 && (Num3 > Num2))
  {
   Largest = Num3;
  }
  else
  {
   Largest = Num1;
  }
  printf("Largest is %d\n", Largest);

 while(getchar()!=EOF)
 {

 }
 return(0);                              /*Program ended with success*/
}
