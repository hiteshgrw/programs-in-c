# programs-in-c
factorial sum
void factorial()
{
 int n,sum=0,f=1;
 printf("\n ENTER THE END OF FACTORIAL SERIES :");
 scanf("%d",&n);
 for(int i = 1;i<=n;i++)
 {
  for(int j=i;j>=1;j--)
  {
   f=f*j;
  }
  sum=sum+f;
  f=1;
 }
 printf("\n THE SUM OF THE SERIES IS : %d",sum);
}
