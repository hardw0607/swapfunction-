# swapfunction-
swapfunction 
package mypackages;
public class swapfunction {

    public static void swap(int a , int b){
        int temp = a;
        a = b;
        b = temp;

        System.out.println("inside swapping function ");
        System.out.println("a = " + a);
        System.out.println("b = " + b);
    } 
    public static void main(String[] args) {
        int x = 5;
        int y = 6;

        System.out.println("befour Swapping");
        System.out.println("x = " + x);
        System.out.println("y = " + y);

        swap(x ,y);

        System.out.println("Swappin in main ");
        System.out.println(" x = " + x);
        System.out.println(" y =" + y);
    }
    
}
//output 
inside swapping function 
a = 6
b = 5
Swappin in main 
 x = 5
 y =6
