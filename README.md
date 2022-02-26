# CvreAlanHesaplama

import java.util.Scanner;
public class hipotenus {
    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int k1,k2,k3;

        System.out.print("Birinci kenarı giriniz: ");
        k1=input.nextInt();

        System.out.print("İkinci kenarı giriniz: ");
        k2=input.nextInt();

        System.out.print("Üçüncü kenarı giriniz: ");
        k3=input.nextInt();

        double hipotenus= Math.sqrt((k1*k1)+ (k2*k2));
        double cevre= (k1+k2+k3)/2;
        double alan=Math.sqrt(cevre*(cevre-k1)*(cevre-k2)*(cevre-k3));
        
        System.out.println("Hipotenüs" + hipotenus);
        System.out.println("Çevre" + cevre);
        System.out.println("Alan" + alan);

    }
}
