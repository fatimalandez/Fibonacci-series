# Fibonacci-series
To print the fibonacci series in java

package fibonacciexample;


public class FibonacciExample {

   
    public static void main(String[] args) {
        int n1=0, n2=1, c;
        System.out.print(n1+""+n2);
        for(int i=1; i<=10;i++){
            c=n1+n2;
            System.out.println(c);
            n1=n2;
            n2=c;
       }
    }
    
}
