# Try-and-catch
 class allblockdemo {
 public static void main(String args[])
{
String citylist[]= {"Ahmedabad" ,"Baroda" ,"Rajkot","Surat"};
int numerator=15, denominator=0, answer;
System.out.println("Statement to executable before try block");
try
{
System.out.println("Begining of try block...");
System.out.println(citylist[5]); // Generates ArrayindexOutOfBoundsException
answer= numerator / denominator; // Generates ArithmaticException
System.out.println("End of Try Block......");
}
catch(ArrayIndexOutOfBoundsException eobj)
{
System.out.println("Within first catch block, exception caught :" + eobj);
}
catch(ArithmeticException eobj)
{
System.out.println("Within second catch block, exception caught + eobj");
}
