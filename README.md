# Calculations_2
This is a java code to calculate the square root of ( -(6.5)2 + (3.7)2 )

package calculations_2;

/**
 *
 * @author WHITEKABAR
 */
public class Calculations_2 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // The code is to work out the square root of (-(6.5)2 + (3.7)2)
        
        /* Creating double variables a, b, c, d, e, f, g, h to hold the various 
        values. */
        double a, b, c, d, f, g, h;
        
        /* double a will hold the value 6.5, while double b will hold the value
          3.7 */
        a = 6.5; b = 3.7;
        
        /* double c will hold the value of 6.5 raised to power of 2, using the 
        math.pow function and multiplying it by -1 */
        c = Math.pow(a, 2) * -1;
        
        /* double d will hold the value of 3.7 raised to power of 2, using the 
        math.pow function */
        d = Math.pow(b, 2);
        
        /* double f will hold the value of the sum of -(6.5)2 and (3.7)2, which
        are double c and d*/
        f = c + d;
        
        /* double g will hold the value the square root of double f using the 
        Math.sqrt function */
        g = Math.sqrt(f);
        
        // Printing out my result
        System.out.println(g);  
    }
    
}
// The result is a NaN because its a negative value
