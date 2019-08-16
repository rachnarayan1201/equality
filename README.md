
#include<stdio.h>
int main()
{
  int array1[5],array2[5];
  int i;
  for(i=0;i<5;i++)
  {
    printf("enter numbers: ");
    scanf("%d",&array2);
    }
    for(i=0;i<5;i++)
    {
    if(array1[i]!=array2[i])
      {
        printf("array not equal");
       }
       else
       {
        printf("arrays are equal");
        }
        }
}
