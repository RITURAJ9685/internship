import java.util.Scanner;
import java.lang.Math;
//name-Rituraj vishwakarma
public class No_game {
    public static void main(String[] args) {
       
        int number = (int) (Math.random() * 100) + 1;
        int num=1;
        
        
        Scanner sc = new Scanner(System.in);
		        
       
        System. out.println("I am thinking the 98 number between 1 and 100.\nyou have to guess the number");
        System. out.println("Enter your guess: ");
            int guess = sc.nextInt();
            while (guess!=number) {
             
            
            
             if (guess > number) {
                System.out.println("Your guess is high.\ntry again!");
                  guess = sc.nextInt();
                  num++;
            }
            
            else {
                System.out.println("Your guess is low.\ntry again ");
                 guess = sc.nextInt();
                  num++;
            }
            
            
        }
    System. out.println("You guessed the number!\nYou win!");
                
		
    }
    }
