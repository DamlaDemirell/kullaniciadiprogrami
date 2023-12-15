import java.util.Scanner;

public class test {
    public static void main(String[] args) {
        String username,password;

        Scanner input= new Scanner(System.in);

        System.out.print("Kullanici Adınız: ");
        username = input.nextLine();

        System.out.println("Şifreniz:");
        password = input.nextLine();
        if(username.equals("patika") && (password.equals("java123"))){
            System.out.println("Giriş yaptınız!");
        } else{
            System.out.println("Girilen Kullanıcı adı veya Şifre yanlış.");
        }
    }
}
