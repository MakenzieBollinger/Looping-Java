# Looping-Java

import java.util.*;
public class Looping {
	public static void main(String[] args){
	
	//Part 1
	int whileLoopAmount;
	whileLoopAmount = 3;
	int count = 1;
	while (count <= whileLoopAmount){
	System.out.println("I am a while loop");
	count++;
	}
	
	//Part 2
	int doWhileLoopAmount;
	doWhileLoopAmount = 0;
	do{
		System.out.println("I am a do while loop");
		doWhileLoopAmount++;
	} while (doWhileLoopAmount < 3);
	
	//Part 3
	int userNumber;
	int result = 0;
	int sum = 0;
	Scanner keyboard = new Scanner(System.in);
	System.out.println("Please enter a number");
	userNumber = keyboard.nextInt();
	for ( int i = 0; i <= userNumber; i++){
		sum += i;
		result = result + i;
	}
	System.out.println("The sum of 0 to " + userNumber + " is " + result);

}
}
