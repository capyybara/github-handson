# github-handson
#github-handson


import java.util.List;

public class Cat2 {
    public static void main(String[] args) {


        List<String> cats = List.of("Tama", "Hachi", "Goro", "Nana");
        //cats と catage の要素数？を連携させたい
        List<Integer> catage = List.of(2, 13, 7, 4);

        

        // catsの名前を出力
        for (String cat : cats) {
            System.out.println(cat + catage);
        }


    }
}
