# patika.dev 

vucutkitle
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        // Kilo (kg) / Boy(m) * Boy(m)

        double kg , boy ;

        Scanner inp = new Scanner(System.in);
        System.out.print("Kilo giriniz: ");
        kg = inp.nextDouble();
        
        System.out.print("Boy giriniz: ");
        boy = inp.nextDouble();
        
        double ind = kg / boy * boy ;
        System.out.println("İndexsiniz : " + ind);

    }
}
