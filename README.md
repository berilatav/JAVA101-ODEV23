Program to find the harmonic series of a number entered in Java

Harmonik seri formulü:1+(1/2)+(1/3)+...+(1/n)

import java.util.Scanner;
public class Odev23 {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.println("Enter the number: ");
        int n = input.nextInt();
        double result = 0.0;                             // Sonuç küsürlü bir sayı olduğu için double kullandım.

        for(int i = 1; i <= n; i++){
            result += (1.0/i);                           // Double bir sayı integer bir sayıya bölündüğünde sonuç double çıkar.  
        }

        System.out.println("Harmonic Series result: " + result);


    }
}
