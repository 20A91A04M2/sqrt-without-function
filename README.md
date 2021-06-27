package pack1;
import java.util.*;
public class sqrt without function{
   public static void main( strings[]args){
scanner sc=new scanner(system.in);
system.out.println("enter new number");
int n=sc.nextInt();
float sqrt,t=0;
//sqrt half of given number
sqrt =n/2;
if(n==1)
system.out.println("square root of "+n" is "+n);
else{
while (sqrt!=t){
t=sqrt;
sqrt=(n/t+t)/2;
}
system.out.println("square root of "+n" is "+sqrt);
}
}
}

   
