# programs-in-c
series sum till 100 power 4
void series()
{
 long int sum=0;
 for(int i=1;i<=100;i+=2)
 {
  sum=sum+pow(i,4);
 }
 printf("\n THE SUM OF SERIES IS : %ld",sum);
}
