# perro-y-gato
codigo de perro y gato con metodos 
package metodo_perro;

public class Perro {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int sueño = 10;
		mostrarNivelSueño(sueño);
		int hambre = 50;
		mostrarHambre(hambre);
		int alegria = 100;
		mostrarAlegria(alegria);
		int melancolia = 100;
		mostrarTristeza(melancolia);
		int diversion = 75;
		mostrarDiversion(diversion);
	}
	
	public static void mostrarNivelSueño(int sueño) {
		
		if (sueño >=75){
			System.out.println( "tengo mucho sueño");
		}
		else if (sueño >=50) {
			System.out.println("tengo algo de sueño");
		}
		else {
			System.out.println("No tengo sueño");
		}

}	
	 int hambre = 100;
     public static void mostrarHambre(int hambre) {
    	 
    	 if(hambre <= 30) {
    		 System.out.println("tengo mucha hambre");
    	 }
    	 else if (hambre <=60){
    		 System.out.println("tengo algo de hambre");
    		 
    	 }
    	 
    	 else {
    		 System.out.println("no tengo hambre");
    	 }
	}
     int alegria = 100;
     public static void mostrarAlegria(int alegria) {
    	 
    	 if(alegria >= 75) {
    		 System.out.println("me siento muy eliz");
    	 }
    	 else if (alegria >=50){
    		 System.out.println("estoy feliz, dame amor");
    		 
    	 }
    	 
    	 else {
    		 System.out.println("estoy triste, kereme sapa");
    	 }
	}
     int melancolia = 100;
     public static void mostrarTristeza(int melancolia) {
    	 
    	 if(melancolia >=80) {
    		 System.out.println("Llevenme a otro hogar");
    	 }
    	 else if (melancolia >=60) {
    		 System.out.println("Realmente me quieres?");
    	 }
    	 else if (melancolia >=20) {
    		 System.out.println("necesito que me des amor");
    		 
    	 }
    	 else {
    		 System.out.println("aun esta contento");
    	 }
     }
     int diversion = 100;
     public static void mostrarDiversion(int diversion) {
    	 
    	 if(diversion >= 75) {
    		 System.out.println("Esto es muy Divertido :D");
    	 }
    	 else if (diversion >=50){
    		 System.out.println("Es divertido");
    		 
    	 }
    	 
    	 else {
    		 System.out.println("Todo bien ");
    	 }
     }
	
}
