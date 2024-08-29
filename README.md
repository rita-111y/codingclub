import java.lang.*;
class fib
{
    public static void main(String args[])
    {
        Scanner scn=new Scanner(System.in);
        int ft=0;
        int st=1;
        int nt=0;
        System.out.println("enter number of term");
        int n=scn.nextInt();
        if(n==0)
        {
            System.out.println("enter a valid term");
        }
        else if(n==1)
        { 
            System.out.print(ft+" ");  
        }
        else if(n==2)
        {
            System.out.println(ft+" ");
            System.out.println(st+" "); 
        }
        else
        {
            System.out.print(ft+" ");
            System.out.print(st+" ");
          for(int i=3;i<=n;i++)
           {
              nt=ft+st;
               ft=st;
              st=nt;
              System.out.print(nt+" ");

           }
        }
    }
}
