```import java.util.Scanner;
public class notOrtalamasi {
public static void main(String[] args) {
Scanner input = new Scanner(System.in);
int fizik , kimya , matematik , biyoloji ;

        System.out.println("Fizik Notunuz : ");
        fizik = input.nextInt();

        System.out.println("Kimya Notunuz : ");
        kimya = input.nextInt();

        System.out.println("Matematik Notunuz : ");
        matematik = input.nextInt();

        System.out.println("Biyoloji Notunuz : ");
        biyoloji = input.nextInt();

        int toplam = (fizik + kimya + matematik + biyoloji);
        double sonuc = toplam/4;
        System.out.println("Not Ortalamanız : " + sonuc);

        boolean sonucSon=(sonuc>=50);

        String str = (sonucSon) ? "Sınıfı Geçtiniz" : "Sınıfta Kaldınız";


        System.out.println(str);





    }
}
