# GoogleCompetition

Java template
```
import java.util.Scanner;
public class Solution {
    public static int solve(int input) {
        return input;
    }
    
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int testCases = sc.nextInt();
        
        int input;
        for (int i = 1; i <= testCases; i++) {
            input = sc.nextInt();
            System.out.println("Case #" + i + ": " + solve(input));
        }
    }
}
```
