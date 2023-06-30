# github-handson
#github-handson

import java.util.HashMap;
import java.util.Map;


public class Cat2 {
    public static void main(String[] args){
        Map<Integer, String> map = new HashMap<>();
        map.put(2, "Tama");
        map.put(13, "Hachi");
        map.put(7, "Goro");
        map.put(4, "Nana");
        map.put(5, "Koo");

        for(Map.Entry<Integer, String> e : map.entrySet()){
            //getValue＝catname , getkey = catageに対応？
            if(e.getKey() % 2 == 0) {
                System.out.println(e.getValue() + "は" + e.getKey() + "歳です" );
            }else if(e.getKey() >=10){
                System.out.println(e.getValue() + "は" + e.getKey() +"歳で長生きです");
            }else{
                System.out.println(e.getValue() + "　にゃー");
            }

        }

    }

}
