import java.lang.*;
class fib
{
    public static void main(String args[])
    {
        Scanner scn=new Scanner(System.in);
        int ft=0;
        int st=1;
        System.out.println("enter number of term");
        int n=scn.nextInt();
        int nt=1;
        System.out.print(ft+" ");
        System.out.print(st+" ");
        
        for(int i=1;i<=n;i++)
        {
           
            ft=st;
            st=nt;
            nt=ft+st;
            System.out.print(nt+" ");
            
        }
        
    }
}
