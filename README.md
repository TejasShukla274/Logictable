import java.util.Scanner;
public class discrete{
    public static void main(String[] args ){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter your first choice = ");
        boolean a = sc.nextBoolean();
        System.out.println("Enter your second choice = ");
        boolean b  = sc.nextBoolean();
        if (a == true && b == true ){
            System.out.print("true");
        
        }
        else if (a == false && b == true || a == true && b == false ){
            System.out.print("false");
        }
        else{
            System.out.print("false ");
        }

        if(a == false && b== false){
        System.out.println("false ");
        }
        else{
            System.out.print(" true ");
        }
        System.out.println(!a);
}
}
 
