 
package phamthiluyen_0711;

import java.util.ArrayList;

public class Exercise4 {

    public static void main(String[] args) {
        ArrayList<String> city = new ArrayList<>();
        city.add("Da Nang");
        city.add("Ho Chi Minh");
        city.add("Lon Don");
        city.add("Tam Ky");
        city.add("Hai Duong");
        if (city.contains("Lon Don")) {
            System.out.println("Yes");
        }else{
            System.out.println("No");
        }
    }
}
