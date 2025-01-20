package phamthiluyen_0711;

import java.util.ArrayList;
import java.util.Random;

public class Exercise5 {

    public static void main(String[] args) {
        ArrayList<Integer> digit = new ArrayList<>();
        Random random = new Random();
        for (int i = 0; i < 10; i++) {
            int randomDigit = random.nextInt(100) + 1;
            digit.add(randomDigit);
        }
        System.out.println("Danh sach sau khi random:" + digit);
        System.out.println("Danh sach sau khi xoa:");
        
        digit.remove(3);
        System.out.println(digit);
    }
}
