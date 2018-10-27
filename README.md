 





import java.util.Scanner;

public class CurrencyConverter
{
  public static void main (String[] args){
     Scanner keyboard = new Scanner( System.in );     
         
        // Ask user for currency input
        System.out.println("How much money in US currency do you have?");
        System.out.println("Do you want to convert to Pesos or Yen?");
        Scanner in = new Scanner(System.in);
        System.out.println(in.nextLine());        
        in.close();
   
        // After choosing input assign currency
        char currencyType;
        currencyType = keyboard.next().charAt(0);
        keyboard.close();
        switch (currencyType) {
        case 'P': System.out.println("Pesos"); break;  
        case 'p': System.out.println("Pesos"); break;
        case 'Y': System.out.println("Yen"); break;
        case 'y': System.out.println("Yen"); break;
        default: System.out.println("Sorry invalid currency type");
        }
        
        // Return different outputs based on users input at start of program
        double x = 1001;
        if(x >= 1000); {
          System.out.println("You're going to have a blast in Mexico");
        }
         if(x > 5000);{
          System.out.println("Have a great time in Japan!");
        }             
         if(x < 10); {
          System.out.println("Haha your broke");
        }
         
            } 
      }
            
