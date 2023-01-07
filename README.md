# Output-formatting
import java.util.Scanner;

public class Solution {

    public static void main(String[] args) {
            Scanner sc=new Scanner(System.in);
            System.out.println("================================");
            for(int i=0;i<3;i++)
            {
                String s1=sc.next();
                int x=sc.nextInt();
                System.out.print(s1);
                int j=s1.length();
                int k=(int)(Math.log10(x)+1);
               for(int m=j;m<15;m++)
               {
                   System.out.print(" ");
               }
               if(k<3)
               {
                   if(k==1)
                        System.out.println("00"+x);                   
                   if(k==2)
                        System.out.println("0"+x);
                    if(x==0)
                        System.out.println("00"+x);
                    
               }
               else
                    System.out.println(x);
                //Complete this line
                
            }
            System.out.println("================================");

    }
    
}



