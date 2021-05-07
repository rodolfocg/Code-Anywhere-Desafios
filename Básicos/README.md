

Desafio
Crie um programa que leia um número e mostre os números pares até esse número, inclusive ele mesmo.

Entrada
Você receberá 1 valor inteiro N, onde N > 0.

Saída
Exiba todos os números pares até o valor de entrada, sendo um em cada linha.

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




------------------------------------------------------------------

Desafio
Elabore um programa que possuas as características abaixo:

Leia os dados de um CPF no formato XXX.YYY.ZZZ-DD;
Imprima os quatro grupos numéricos, sendo um valor por linha.
Entrada
A entrada consiste vários arquivos de teste e cada um possuindo uma linha com formato XXX.YYY.ZZZ-DD, onde XXX, YYY, ZZZ, DD são números inteiros.

Saída
Para cada arquivo da entrada, tem que ter um arquivo de saída com quatro linhas, e em cada linha um número inteiro de acordo com procedimento 2 descrito no Desafio. Confira o exemplo abaixo:


import java.util.Scanner;
public class rodolfo {

public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        String STR = leitor.next();
        String A = STR.substring(0, 3);
        String B = STR.substring(4, 7);
        String C = STR.substring(8, 11);
        String D = STR.substring(12, 14);
        System.out.println(A);
        System.out.println(B);
        System.out.println(C);
        System.out.println(D);
        }

        }

--------------------------------------------------------------------
Leia um número inteiro que representa um código de DDD para discagem interurbana. Em seguida, informe à qual cidade o DDD pertence, considerando a tabela abaixo:

 


Se a entrada for qualquer outro DDD que não esteja presente na tabela acima, o programa deverá informar:
DDD nao cadastrado

Entrada
A entrada consiste de um único valor inteiro.

Saída
Imprima o nome da cidade correspondente ao DDD existente na entrada. Imprima DDD nao cadastrado caso não existir DDD correspondente ao número digitado.



import java.util.Scanner;
public class rodolfo {

    public static void main(String[] args) {

        Scanner teclado = new Scanner(System.in);

        int DDD;

        System.out.println("");

        DDD = teclado.nextInt();

        switch(DDD){

            case 61:

                System.out.println("Brasilia");break;

            case 71:

                System.out.println("Salvador");break;

            case 11:

                System.out.println("Sao Paulo");break;

            case 21:

                System.out.println("Rio de Janeiro");break;

            case 32:

                System.out.println("Juiz de Fora");break;
                
            case 19:

                System.out.println("Campinas");break;
                
            case 27:

                System.out.println("Vitoria");break;
                
            case 31:
              
                System.out.println("Belo Horizonte");break;

            default:

                System.out.println("DDD nao cadastrado");

        }

        teclado.close();

    }

}

Observação: Irei atualizar com explicação do que foi realizado e o motivo.
