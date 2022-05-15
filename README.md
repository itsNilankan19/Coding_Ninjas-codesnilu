# Coding_Ninjas-codesnilu
public class Solution {

	public static int power(int x, int n) {
		/* Your class should be named Solution
		 * Don't write main().
		 * Don't read input, it is passed as function argument.
		 * Return output and don't print it.
		 * Taking input and printing output is handled automatically.
		 */
// 		if (n == 0)
//     	{
//         	return 1;
//     	}
//         else if (x == 0)
//         {
//             return 0;
//         }
//         else if (x == 0 && n == 0)
//         {
//             return -1;
//         }
//         else if (n == 1)
//         {
//             return x;
//         }
//         else
//         {
//             return n * power(x, n-1);
//         }
        
// 	}
//     public static void main(String args[])
//     {
//         int x = 2;
//         int n = 3;
//         System.out.println(power(2,3));
        
        
        if(n==0)
            return 1;
        
        return power(x,n-1)*x;
     }
}
