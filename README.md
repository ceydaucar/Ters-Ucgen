# Ters-Ucgen
Patika.dev > Java101 > Döngüler > Ödev3 - Ters Üçgen Yapımı

## Java ile basamak sayısının kullanıcıdan alınan ve döngüler kullanılarak, yıldızlar(*) ile ekrana ters üçgen çizen programı yazın.

      import java.util.*;

      public class mini_proje_11 {

        public static void main(String[] args) {
        
            Scanner sc = new Scanner(System.in);

            System.out.print("Enter a number: ");
            int n = sc.nextInt();

            for (int i=0; i<=n; i++) {
                for(int j=0; j<(i+1); j++)
                  System.out.print(" ");

                for (int k=1; k<2*(n-i); k++) 
                  System.out.print("*");
                System.out.println(" ");
            }
         }
      }
