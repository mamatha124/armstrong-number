# armstrong-number
import java.util.*;
class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int temp=n;
        int a=0;
        int b=0;
        while(n>0){
            a=n%10;
            b=b+a*a*a;
            n=n/10;
        }
        if(temp==b){
            System.out.println("armstrong number");
        }else{
            System.out.println("not a armstrong number");
        }
    }
}
