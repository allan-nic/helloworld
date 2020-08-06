# HelloWorld
 Repositório criado para realização de **testes**.
 
 Num | Linguagem
 ---| ---
 1 | C++
 2 | Java
 3 | Python
 
 
 ~Teste~
 
 - [x] Listar a lógica de um programa.
 
 ```
 
	public static void main(String[] args) {
		
		//variaveis
		
		float p, m, quantidade;
		String e = "excesso";
		Scanner teclado = new Scanner (System.in);
		
		//entradas
		
		System.out.println ("Informe o peso do peixes: ");
		p = teclado.nextFloat();
		
		//processamento
		
		if (p > 50) {
			m = (float) (p-50) * (float) 4.00;
			quantidade = (float) (p-50);
			System.out.println ("Você deverá pagar R$ " + m + " em multas. \n" + "Excesso: " + quantidade + " quilos!");
		}else {
			m = 0;
			e = "0 quilos";
			System.out.println("Multas: " +m);
			System.out.println ("Excesso: "+e);
		}
		teclado.close();

	}

}
```
