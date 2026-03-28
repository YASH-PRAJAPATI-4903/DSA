#☕ Java Basic Input/Output
﻿#﻿#🔹 1. Basic Structure of a Java Program
In Java, every program starts with a class and a main method.
'''
public class Main {
    public static void main(String[] args) {
        // Your code here
    }
}
'''

﻿#﻿#🔹 2. Output in Java (Printing)
In Java, we use:

System.out.print() → prints on same line
System.out.println() → prints with a new line

'''
public class Main {
    public static void main(String[] args) {
        System.out.print("Hey, Striver!");
    }
}
'''
Output:
'''
Hey, Striver!
'''

﻿#﻿#🔹 3. Printing on Multiple Lines
 '''
 public class Main {
    public static void main(String[] args) {
        System.out.println("Hey, Striver!");
        System.out.println("Hey, Striver!");
    }
}
'''
Output:
'''
Hey, Striver!
Hey, Striver!
'''

﻿#﻿#🔹 4. \n vs println()
 '''
 public class Main {
    public static void main(String[] args) {
        System.out.print("Hey, Striver!\n");
        System.out.print("Hey, Striver!");
    }
}
'''
✔ \n → newline character
✔ println() → automatically adds newline (cleaner & preferred)

﻿#﻿#🔹 5. Taking Input in Java (Scanner)
Java uses Scanner class for input.
'''
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int x = sc.nextInt();
        System.out.println("Value of x: " + x);
    }
}
'''

Input:
'''
10
'''
Output:
'''
Value of x: 10
'''

﻿#﻿#🔹 6. Taking Multiple Inputs
Input:
'''
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int x = sc.nextInt();
        int y = sc.nextInt();

        System.out.println("Value of x: " + x + " and y: " + y);
    }
}
'''
Input:
'''
10 20
'''
Output:
'''
Value of x: 10 and y: 20
'''

﻿#﻿#🔹 7. Important Notes (Java vs C++)


﻿#﻿#🔹 8. Shortcut like bits/stdc++.h?
❌ Java doesn’t have an exact equivalent
'''
import java.util.*;   // for Scanner, ArrayList, etc.
'''

But commonly used imports:
'''
BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
'''

🔥 Pro Tip (Important for DSA)
For fast input (competitive programming), prefer:

