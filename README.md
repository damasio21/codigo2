# codigo2

import java.util.Scanner;
 
public class exericio19 {
 
    // 19.    Coloque em ordem crescente dois números quaisquer.
 
    public static void main(String[] args) {
     int n1,n2;
     System.out.println("entre com o primeiro numero");
        n1=new Scanner(System.in).nextInt();
 
        System.out.println("entre com o segundo numero");
        n2=new Scanner(System.in).nextInt();
 
        if(n1<n2)
            System.out.println("a ordem é " +n1+ " "+n2);
        else
            System.out.println("a ordem é "+n2+ " " +n1);
 
        }
 
}


*Formatação Horizontal:
 Qual deve ser o tamanho de uma linha? Os programadores claramente preferem linhas
 curtas. O antigo limite de 80 de HOLLERITH é um pouco arbitrário. Costumava-se seguir a regra
 na qual jamais se deve ter de rolar a tela para a direita
