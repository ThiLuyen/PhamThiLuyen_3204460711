 
package phamthiluyen_0711;

import java.util.ArrayList;

public class Exercise1 {
    public static void main(String[] args) {
        ArrayList<Integer> numbers = new ArrayList<>();
        for (int i = 1; i <= 10; i++) {
            numbers.add(i);
        }
        System.out.println("Cac phan tu:");
        for (Integer number : numbers) {
            System.out.print(number + " ");
        }
    }
}
