Task1:- nested if
----------------->

*The nested if statement represents the if block within another if block. Here, the inner if block condition executes only when outer if block condition is true

*Genarally this condtion works like yes (or) No type if the condition satisfies, it executes some block of code. Otherwise, it doesn’t execute the code


Program:

class NestedIf
{   
    public static void main(String args[]) 
    { 
          int a=10; 
          int b=20; 
        
        if(a==10){ 
  
            if(b!=20){ 
                System.out.println("Successfully executes"); //Here inner if the condition is not true. Hence else part is executed.
            } 
            
            else{ 
                System.out.println("Execution Failed"); 
            } 
        } 
    } 
} 

Output:
-------
Execution Failed

Task2: when for loop becomes infinite.

class infiniteLoop
{
  public static void main(String args[])
  {
    for(;;)
     {
       System.out.println("Java is Awesome");
     }
}


Output:-
--------
Java 
java 
java 
.
.
.
Infinite times
