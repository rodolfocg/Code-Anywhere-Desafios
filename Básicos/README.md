<h2>Desafio Básico</h2>


Exibindo Números Pares:

import java.util.Scanner;

public class Rodolfo {

    public static void main(String[] args) {

        Scanner reader = new Scanner(System.in);

        System.out.print("");
        int num = reader.nextInt();

        int limit = num;
        for(int i=1; i <= limit; i++){

            if( i % 2 == 0){
                System.out.print(i + "\n ");
            }
        }
    }
}

------------------------------------------------------------------------


