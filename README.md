# manav-hesaplama
// alınan ürünlerin kgsine göre toplam tutarı hesaplayan program

import java.util.Scanner;
public class main {
    public static void main (String[]args) {
        double karmut = 2.14, kelma = 3.67, kdomates = 1.11, kmuz = 0.95, kpatlican= 5.00;
        double armut, elma, domates, muz, patlican;
        Scanner input= new Scanner(System.in);
        System.out.print("Kaç kilo Armut aldınız?  ");
        armut = input.nextInt();
        Scanner inp= new Scanner(System.in);
        System.out.print("Kaç kilo Elma aldınız?  ");
        elma = inp.nextInt();
        Scanner abc= new Scanner(System.in);
        System.out.print("Kaç kilo Domates aldınız?  ");
        domates = abc.nextInt();
        Scanner def= new Scanner(System.in);
        System.out.print("Kaç kilo Muz aldınız?  ");
        muz = def.nextInt();
        Scanner ghj= new Scanner(System.in);
        System.out.print("Kaç kilo Patlıcan aldınız?  ");
        patlican = ghj.nextInt();
        double toplam;
        toplam = karmut*armut + kelma*elma + kdomates*domates + kmuz*muz + kpatlican*patlican;
        System.out.print("Toplam tutar:" + toplam);

    }
    
}
