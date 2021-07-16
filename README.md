# sorted-arraylist
import java.util.*;

class sortedarray
{ 
      public static void main(String args[]) 

    { 

        ArrayList<Integer>a = new ArrayList<Integer>();

        a.add(31); 

        a.add(24); 

        a.add(10); 

        System.out.println("list a"+a);
        
        ArrayList<Integer>b = new ArrayList<Integer>();

        b.add(12); 
        
        b.add(50);
        
        b.add(30);
        
        System.out.println("list b"+b);
        
        a.addAll(b);
            
        System.out.println("combined array"+a); 
        Collections.sort(a);
        System.out.print("sortedarray"+a);

     } 
 } 
 
