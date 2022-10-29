# Task-5-to-9
import java.util.Scanner;
class lab5
 {
  public static void main(String[] args) 
  { 
   Scanner in=new Scanner(System.in);
   String username="aneshrathore",password="212121212";
   int choice;
   System.out.println("Enter username");
   username=in.next();
   System.out.println("Enter password");
   password=in.next();
   if(username.equals("aneahrathore1@gmail.com")&&password.equals("212121212"))
   {
   System.out.println("Login Success \n Anesh Rathore here:");}
   else {
   System.out.println("Login Failed!!!");
   System.out.println("        ");
   System.out.println(" *********LOGIN HINT:**********");
   System.out.println("Forgotten email or password Don't worry . we will help you in Signing in :\nPLEASE Select the choice in which you want hint:");
   System.out.println("1.Email \n2.Password \n3.Email and Password both");
   choice=in.nextInt();
   switch (choice) {
   case 1:
   System.out.println(" Your Email is \n aneshrathore1@gmail.com");
     System.out.println("Enter username");
   username=in.next();
   System.out.println("Enter password");
   password=in.next();
   if(username.equals("aneshrathore@gmail.com")&&password.equals("212121212"))
   System.out.println("Login Success\n Anesh Rathore here:");
   break;
     case 2:
   System.out.println(" Your Password is \n 212121212");
     System.out.println("Enter username");
   username=in.next();
   System.out.println("Enter password");
   password=in.next();
   if(username.equals("aneshrathore@gmail.com")&&password.equals("212121212"))
   System.out.println("Login Success\n Anesh Rathore here:");
   break;
    case 3:
   System.out.println("Your Password is \n 212121212\nYour Email is \n aneshrathore1@gmail.com: ");
     System.out.println("Enter username");
   username=in.next();
   System.out.println("Enter password");
   password=in.next();
   if(username.equals("aneshrathore1@gmail.com")&&password.equals("212121212"))
   System.out.println("Login Success \n Wellcome to Rishta website:");
   break;
   
   default:
   System.out.println("Login again failed We APOLOGISE you please try next time:");}
   }
  }
 }
}
