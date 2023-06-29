# github-handson
#github-handson

import java.util.ArrayList;
import java.util.List;

public class Cat2 {
    public static void main(String[] args) {
        List<String> cats = List.of("Tama", "Hachi", "Goro", "Nana");
        List<String> dogs = new ArrayList<>();;
        dogs.add("Pochi");
        dogs.add("Shiro");
        dogs.add("Kuro");

        // catsの名前を出力
        for (String cat : cats) {
            System.out.println(cat);
        }

        // dogの名前を出力
        for (String dog : dogs) {
            System.out.println(dog);
        }
    }
}
