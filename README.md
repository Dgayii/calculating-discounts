# calculating-discounts
import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int amount = sc.nextInt();
        if(amount>500 && amount<=1000) {
            double discount=amount*0.1;
            System.out.println(amount-discount);
        } 
        else if(amount>1000 && amount<=2000) {
            double discount=amount*0.2;
            System.out.println(amount-discount);
            
        }
        else if(amount>2000 && amount<=5000)
        {
            double discount=amount*0.3;
            System.out.println(amount-discount); 
        }
        else{
            System.out.println("not discount");
            
        }
    }
}
