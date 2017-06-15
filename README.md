# primenumber
# display all prime umber
#display all prime number
# include<stdio.h>
void primedisplay(int n)
  {
    int i,j;
    for(i=2;i<n/2;i++)
      {
        if(n%i==0)
          {
            flag=1;
            break;
            }
          }
        if(flag==0)
          {
            printf("\nnumber is prime%d",n);
            }
            else
              {
                printf(number is not prime%d",n);
                }
              }  
