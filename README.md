# fibo
import java.util.Scanner;
public class fibonashi {
    public static int Fibonashi(int n){
            if (n<=1) {
                return n;
            }
            else {
                return Fibonashi(n-1)+Fibonashi(n-2);
            }
        }
    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        int n;
        System.out.println("Introduce el numero para aplicor Fibonashi");
        n=s.nextInt();
        Fibonashi(n);
    }
}
