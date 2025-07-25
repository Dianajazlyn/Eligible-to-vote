# Eligible-to-vote
import java.util.Scanner;
class main
{
Public Static void main(String args[])
{
Scanner sc=new Scanner ("System.in");
System.out.print("Enter a age:");
int Age=sc.nextInt();
if(Age>=18)
{
System.out.println("Valid to Vote");
}
else
{
System.out.println("Invalid");
}
}
}
