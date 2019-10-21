import java.util.*;   
public class PalindromeTest
{  
   public static void main(String args[])  
   {  
      String original = "Refer"; 
      String  reverse = "";
      original = original.toLowerCase();
      original = original.replaceAll("\\s","");
       for ( int i = original.length() - 1; i >= 0; i-- ) { 
             reverse = reverse + original.charAt(i);
             System.out.println(reverse);
     }
      if (original.equals(reverse))  
         System.out.println("Entered original " +   original    +    " is  matching with the "+ reverse +"  a palindrome.");  
      else  
         System.out.println("Entered original " +   original    +    " is not matching with the "+ reverse +" hence not a palindrome.");   
   }  
}
