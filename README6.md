# programs-in-c
print + , - series of power 3
void sumseries()
{
 int sign=-1;
 int f=1;
 int n,sum=0;
 printf("\n ENTER THE LAST TERM OF THE SERIES :");
 scanf("%d",&n);
 for(int i=1;i<=n;i++)
 {
  sum=sum+pow(f*sign,3);
  f=f+2;
  sign=sign*-1;
 }
 printf("\n THE SUM OF THE SERIES IS : %d",sum);
}
