# Assignment-3.6
1) Can you overload a method with same return type.? Explain your answer with proper logic.
YES I CAN OVERLOAD METHOD WITH SAME RETURN TYPE.AS,OVERLOADING DEPENDS ONLY ON THE NUMBER AND TYPE OF ARGUMENTS PASSED TO THE METHOD AND IT IS INDEPENDENT ON THE RETURN TYPE
please refer to image 3.6a for example

2) Write a program in java using Arrays, that sorts the element in descending order.
java.util.Scanner;

public class acad { public static void main(String args[]) { Scanner s=new Scanner(System.in); System.out.println("Enter the number of elements in array "); int n=s.nextInt(); //getting the size of the array System.out.println("Enter the elements in array"); int[] a=new int[n]; //defining an integer array of size n for(int i=0;i=0;i--) //loop which is used to print it in a reverse order { System.out.println(a[i]); } } }
