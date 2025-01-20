 

package phamthiluyen_0711;
import java.util.ArrayList;

public class Exercise3 {
    public static void main(String[] args) {
        ArrayList<Double> gia = new ArrayList<>();
        gia.add(17.5);
        gia.add(8.5);
        gia.add(12.99);
        gia.add(3.99);
        gia.add(29.5);
        System.out.println("Danh sach!");
        for (int i = 0; i < gia.size(); i++) {
            System.out.println("Gia " + (i) + ": " + gia.get(i));
        }
    }
}
