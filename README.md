package testing.automation;

public class PrintNumberInRange {
	
	public static void main(String[] agrs) {
		
		PrintNumberInRange pr= new PrintNumberInRange();
		pr.number(100, 200);
	}
		
		public void number(int startNumber, int endNumber) {
			for(int i=startNumber; i<=endNumber; i++) {
				System.out.println(i);
			}
		}
}

