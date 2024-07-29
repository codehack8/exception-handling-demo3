# exception-handling-demo3
package com.qis.corejava.exceptionhandling;


public class ExceptionDemo3 {
      String name="null";
	 public void mydata()
	 { try {
		 System.out.println("One");
	       System.out.println(name.length());
	      int n=10/0;
	       
	       System.out.println("End");
	 }
	 catch(NullPointerException e) {
		 System.out.println("I can handle :"+e);
	 }
	 catch(ArithmeticException  e) {
		 System.out.println("I can handle :"+e);
	 }	 
	 }	
	public static void main(String[] args) {
		ExceptionDemo3 ed1=new ExceptionDemo3();
		ed1.mydata();

	}

}
