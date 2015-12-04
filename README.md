# ejecicio de mostrrar sobrecaga
package programacion;


	
	 class MostrarSobrecarga {
			
			public void disp(String c){
			System.out.println(c);
			}
			public void disp(String c, int num){
			System.out.println(c + "" + num); 
		}
			
			public void disp(int c, int num){
			System.out.println(c+" "+num);
			}
		 }
	 
	public class Ejemplo1 {
	public static void main(String[] args) {
		 MostrarSobrecarga  obj = new MostrarSobrecarga ();
		 obj.disp("ejemplo");
	     obj.disp("ejemplo" ,10);
	     obj.disp(1, 2);
	     Operacion.max(60, 89);
		 
	 }
}
**************************************************	
package programacion;

		 class MostrarSobrecarga2 {
				
				public void disp(String c){
				System.out.println(c);
				}
				
				public void disp(int c){
				System.out.println(c);
				}
			 }
		 
		public class Ejemplo2 {
		public static void main(String[] args) {
			 MostrarSobrecarga2  obj = new MostrarSobrecarga2 ();
			 
		     obj.disp("a");
		     obj.disp(5);
			 
		 }
	}
**************************************************************		
package programacion;

 class test {
	 
	 public int siMetodo(int num1, int num2){
		 System.out.println("mi metodo");
		 return num1+num2;
	 }
	 public int siMetodo(double var1, int var2){
		 System.out.println("mi metodo");
		 return(int) var1+var2;
	 }

}
public class Ejemplo3 {
	public static void main(String[] args) {
		
	}
}

*****************************************************************
package programacion;

public class Operacion {

	public static int max(int a,int b){
		if(a>b)
			return a;
		else
			return b;
	}

	public static void main(String[] args) {
		
		System.out.println(Operacion.max(5, 1));
    int val = max (4,max(3,max(10,5)));
    System.out.println(val);
    
	}

}
************************************************
// lamar desde otro paquete

package programacion;

public class principal {

	public static void main(String[] args) {
		int r 

	}

}
