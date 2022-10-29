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
   System.out.println("Login Success \n welcome to university of sindh:");}
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
   System.out.println("Login Success\n University of sindh:");
   break;
     case 2:
   System.out.println(" Your Password is \n 212121212");
     System.out.println("Enter username");
   username=in.next();
   System.out.println("Enter password");
   password=in.next();
   if(username.equals("aneshrathore@gmail.com")&&password.equals("212121212"))
   System.out.println("Login Success\n welcome to university of Sindh:");
   break;
    case 3:
   System.out.println("Your Password is \n 212121212\nYour Email is \n aneshrathore1@gmail.com: ");
     System.out.println("Enter username");
   username=in.next();
   System.out.println("Enter password");
   password=in.next();
   if(username.equals("aneshrathore1@gmail.com")&&password.equals("212121212"))
   System.out.println("Login Success \n Wellcome to University of sindh:");
   break;
   
   default:
   System.out.println("Login again failed We APOLOGISE you please try next time:");}
   }
  }
 }
}




===========================================================
import java.util.Scanner;
class task6 {
    public static void main(String args[]) {
        while(true) {
         Scanner obj= new Scanner(System.in) ;
       int  chicken=1000,mutton=2500,beef=1700, patatos chips=200,icecream=200,baryani=300,tea=100,choice;
       int quantity,total;
       System.out.println("############### WELLCOME TO ANESH RATHORE RESTUARANT: ###############");
       System.out.println("  ");
       System.out.println("                1.Chicken                =  1000");
       System.out.println("                2.baryani                 =  300");
       System.out.println("                3.Beef                   =  1700");
       System.out.println("                4.Patotos chips         =  200");
       System.out.println("                5.Ice cream               =  200");
       System.out.println("                6.Motton              =  2500");
       System.out.println("                7.Tea                    =  100");
       System.out.println("     ");
       System.out.println(" ENTER YOUR CHOICE PLEASE:");
       choice=obj.nextInt();
       switch(choice){
       case 1:
       System.out.println(" you selected chicken :");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*chicken;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;

       case 2:
       System.out.println(" you selected Mutton :");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*mutton;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;

       case 3:
       System.out.println(" you selected Beef :");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*beef;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;

       case 4:
       System.out.println(" you selected Patatos chips :");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*chips;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;

       case 5:
       System.out.println(" you selected Ice cream :");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*icecream;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;

       case 6:
       System.out.println(" you selected baryani:");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*ladyfinger;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;
       case 7:
       System.out.println(" you selected Tea :");
       System.out.println(" ENTER Quantity:");
       quantity=obj.nextInt();
       total=quantity*tea;
       System.out.println("==========================================================");
       System.out.println(" *******YOUR BILL IS********");
       System.out.println(total);
       break;
       default:
       System.out.println(" YOU ENTERED INVALID NUMBER");
       }
     }
  }
}
≠===≠=≠≠≠≠===========≠=============================
import java.util.Scanner;
class task8
{
	public static void main(String[]args)
	{ while(true){
		Scanner in=new Scanner(System.in);
		int x;
		int y;
		int add,substract,multiplication,choice;
		float division;
		System.out.println("enter the the first element :");
		x=in.nextInt();
		System.out.println("enter the the second element :");
		y=in.nextInt();
        System.out.println("  ");
		System.out.println("============ENTER YOUR CHOICE============");
        System.out.println("        1.ADDITION");
        System.out.println("        2.SUBSTRACTION");
        System.out.println("        3.MULTIPLICATION");
        System.out.println("        4.DIVISION");
       		 choice=in.nextInt();
       		 switch( choice){
    		  case 1:  
      		  System.out.println(" you selected ADDITION");
      		  add=x+y;
       		 System.out.println(add);
                break;
                case 2:  
      		  System.out.println(" you selected SUBSTRACTION");
      		  substract=x-y;
       		 System.out.println(substract);
                break;
                case 3:  
      		  System.out.println(" you selected MULTIPLICATION");
      		  multiplication=x*y;
       		 System.out.println(multiplication);
                break;
                case 4:  
      		  System.out.println(" you selected DIVISION");
      		  division=x/y;
       		 System.out.println(division);
                break;
                default:
                System.out.println(" you ENTERED invalid CHOICE:");
	}
   }}
===============================================≠============

class task9 {
public static void main(String[]args) {
   int a=0,b=1,c;
for(int i=1;i<13;i++)
  {
 System.out.println(" "+a);
c=a+b;
a=b;
b=c;
}


}
}
