Reverse String

/* package whatever; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
	public static void main (String[] args) 
	{
		// your code goes here
		
	 char[] s = {'g', 'o', 'u', 't', 'a', 'm'};

        int l = 0;
        int r = s.length - 1;
        
        while (l < r) {
            char t = s[l];
            s[l] = s[r];
            s[r] = t;

            l++;
            r--;
        }

        System.out.println(Arrays.toString(s));
	}
}

==================================================================================================================================


