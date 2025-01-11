import java.util.*;
import java.lang.*;
import java.io.*;

class Main
{
public static void main (String[] args) throws java.lang.Exception
{
Scanner S=new Scanner(System.in);
int t=S.nextInt();
while(t-->0)
{
int arr[]=new int[3];
for (int i = 0; i < arr.length; i++)
{
arr[i] = S.nextInt();
}
int max=arr[0];
int max2=arr[0];
for(int i=0;i<arr.length;i++)
{
   if(arr[i]>max)
   {
       max=arr[i];
   }
}
for(int i=0;i<arr.length;i++)

{
   if(arr[i]<max && arr[i]>max2)
   {
       max2=arr[i];
         
   }
   
}
 System.out.println(max2);
 
}

}
}
