# valoe
package day01;
import java.util.Scanner;

public class day3 {
    public static void main(String[] args) {
        Scanner scan= new Scanner(System.in);

        System.out.print("1.Kenarı Giriniz= ");
        int a = scan.nextInt();

        System.out.print("2.Kenarı Giriniz= ");
        int b = scan.nextInt();

        double c = Math.sqrt((a*a)+(b*b));

        System.out.print("Hipotenüs= "+ (int)c);

    }



}
