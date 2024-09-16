# Projeto-Conta-Terminal

import java.util.Scanner;

public class contaTerminal {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner usuario = new Scanner(System.in);
		
		System.out.println("Por favor, Digite seu nome: ");
		String nome = usuario.next();
		
		
		System.out.println("Por favor, Digite sua agência: ");
		String agencia = usuario.next();
		
		
		System.out.println("Por favor, Digite sua conta: ");
		int numero = usuario.nextInt();
		
		System.out.println("Por favor, Digite seu Saldo: ");
		double saldo = usuario.nextDouble();
		
		
		System.out.println("Olá " + nome + ", obrigado por criar uma conta em nosso banco, sua agência é " + agencia +  " ,conta " + numero + " , e seu Saldo R$" + saldo + " já está disponível para saque. ");
		

	}

}


