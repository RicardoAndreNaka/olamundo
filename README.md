public class Multiplicacao{
   public static void main(String[] args) {
		int soma = 0;
		long produto = 1;
		for (int i = 1; i < 30; i+= 2) {
			soma += i;
			produto *= (i+1);
			System.out.println(i);
		}
		System.out.println(soma);
		System.out.println(produto);
   }
}
