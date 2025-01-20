 
package phamthiluyen_0711;

import java.util.ArrayList;

public class Exercise2 {
    public static void main(String[] args) {
        ArrayList<String>colors=new ArrayList<>();
        colors.add("Red");
        colors.add("Blue");
        colors.add("Black");
        colors.add("White");
        for (int i = 0; i < colors.size(); i++) {
            System.out.println(colors.get(i));
        }
        colors.set(1,"Yellow");
        System.out.println(colors);
    }
}
