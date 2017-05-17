# cajero
import java.util.Scanner;

public class clasedesarrolofinal {

    public static void main(String[] args) {

        int cantidad;
        try (Scanner Cantidad = new Scanner(System.in)) {
            System.out.print("damee: ");
            cantidad = Cantidad.nextInt();
        }


	int contador1 = 0;
	int contador2 = 0;
	int contador3 = 0;
	int contador4 = 0;
	int contador5 = 0; 
        
       
        if (cantidad >= 1000 ){
            while(cantidad >= 20000){
        	cantidad = cantidad - 20000;
        	++contador5;
            }
            while(cantidad >= 10000){
        	cantidad = cantidad - 10000;
        	++contador4;
        		
            }
            while(cantidad >= 5000){
        	cantidad = cantidad-5000;
                ++contador3;
        		 
            }
            while(cantidad >= 2000){
        	cantidad = cantidad-2000;
                ++contador2;
        		
            }
            while(cantidad >= 1000){
        	cantidad = cantidad-1000;
                ++contador1;
        		
            }
            
            System.out.println(""
        		+ "$20000 = "+ contador5
        		+ "\n$10000 = "+ contador4
        		+ "\n$5000  = "+ contador3
        		+ "\n$2000  = "+ contador2
        		+ "\n$1000  = "+ contador1);
        }

        else{
            System.out.println("no sea tonto"); 
        }
        
    }
    
}
