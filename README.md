package raed;
import java.util.Scanner;

public class JavaPracts {

	
	    public static void main(String[] args) {
	        Scanner scanner = new Scanner(System.in);

	        System.out.print("ماهو الاقتباس؟ ");
	        String quote = scanner.nextLine();
	        
	        System.out.print("من قال ذلك؟ ");
	        String author = scanner.nextLine();

	        String output = author + " يقول، \"" + quote + "\"";
	        
	        System.out.println(output);
	        
	        scanner.close();
	    }
}
