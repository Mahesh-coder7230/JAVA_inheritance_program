
 import java.util.Scanner;
public class operat1 {
  public static void main(String[] args) {
class operat {
   Scanner c =new Scanner(System.in);
   double a;
   double b;

   operat() {
      
      this.a = this.c.nextDouble();
      this.b = this.c.nextDouble();
   }
}
class AddSub extends operat {
   AddSub() {
      System.out.println(this.a + this.b);
      System.out.println(this.a - this.b);
   }
}
 }
 class MulDiv extends AddSub {
   MulDiv() {
      System.out.println(this.a * this.b);
      System.out.println(this.a / this.b);
   }
}

}

