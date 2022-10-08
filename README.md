//VucutKitleEndeksi

import java.util.Scanner;

public class VucutKitleEndeksi {

    public static void main(String[] args) {

        float boy;
        double kilo, endeks;

        Scanner input = new Scanner(System.in);

        System.out.print("Lütfen boyunuzu metre cinsinden giriniz: ");
        boy = input.nextFloat();
        System.out.print("Lütfen kilonuzu kilogram cinsinden giriniz: ");
        kilo = input.nextInt();

        boy = boy/100;
        endeks=kilo/(boy*boy);

        System.out.println("Vücut kitle endeksiniz: " + endeks);

    }
}
