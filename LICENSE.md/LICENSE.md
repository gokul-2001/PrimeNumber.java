import java.util.Scanner;

class PrimeNumber{
public static void main (String[] args){
int n;
Scanner sc = new Scanner(System.in);
System.out.println("Please insert any number");
n = sc.nextInt();
if(n > 1)
System.out.println(n+ "is a prime number");
else
System.out.println(n+ "is not a prime number");
}
}
