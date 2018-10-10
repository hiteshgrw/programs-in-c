# programs-in-c
fibonacci series and sum
void fibo()
{
 int n,sum=0;
 int f=0;
 int s=1;
 printf("\n ENTER THE LAST TERN OF FIB0NACCI SERIES :");
 scanf("%d",&n);
 printf("%d",f," ");
 fo	r(int i=1;i<n;i++)
 {
  printf("%d ",s);
  sum=sum+s;
  int t=f+s;
  f=s;
  s=t;
 }
 printf("\n THE SUM OF THE SERIES IS : %d",sum);
}
