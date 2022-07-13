# Java-program-to-convert-seconds-to-hours-minutes-seconds
import java.util.Scanner;
public class time
{
public static void main(String args[])
{
Scanner s=new Scanner(System.in);   
int num,hour,min,sec;

System.out.print("Enter the number:");
num=s.nextInt();

hour=num/3600;
System.out.println("hour="+hour);

min=num/60;
System.out.println("minute="+min);

sec=num%60;
System.out.println("second="+sec);
}       
}
