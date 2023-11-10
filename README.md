# IfElseIncadeado
IfElseIncadeado

package exemplos;

import java.util.Scanner;

//desvio condicional encadeado
public class IfElseIncadeado {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Digite a sua idade :");
		int idade=sc.nextInt();
		
		if(idade<16) {
			System.out.println("Voce é ainda nao pode votar !");
		}else if(idade <18){
			System.out.println("Voce pode votar , porem e opcional!");
		}else {
			System.out.println("Voce é pode votar !");
		}
		
		

	}

}

