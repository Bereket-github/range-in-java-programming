# range-in-java-programming
package range;
import java. util.*;
public class Range {   
public static void main(String[] args) {  
Scanner s =new Scanner(System.in);   
 int range, min, max, i;
 System. out. println("enter size"); 
 int n= s.nextInt();  
int a[]=new int[n];  
min=a[0];  
max=a[0];  
for(i=0;i&lt;n;i++)  
{   
 System.out.println("enter element"+ i);    
a[i]=s.nextInt();   
 if(a[i]>max)    
max=a[i]; 
 }  
for(i=0;i&lt;n;i++)  
{    
if(a[i]&lt;min)    
min=a[i];  
}
System. out. println("max= " + max);
System. out. println("min= " + min);
 range=(max-min);
System.out. println("range= " + range);
}
}
