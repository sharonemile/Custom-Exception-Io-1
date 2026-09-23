package customexceptionio;

public class Main {

	 static void checkMarks (int marks) throws MyException {
		 if(marks<40) {
			 throw new MyException("Student is Fail");
		 }
		 else {
			 System.out.println("Student is pass");
		 }
	}
	 public static void main(String[]args) {
		 try {
			 checkMarks(90);
		 }
		 catch(MyException e) {
			 System.out.println(e.getMessage());
			 
		 }
	 }

}
