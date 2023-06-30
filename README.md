# github-handson
#github-handson



 import java.util.List;

public class Cat {
        public static void main(String[] args) {
        
        List<String> cats = List.of("Tama", "Hachi", "Goro", "Nana", "Koo");
        List<Integer> catage = List.of(2, 13, 7, 4, 5);

        for (int i=0; i <5; i++){
            if(catage.get(i) %2 ==0){
                System.out.println(cats.get(i) + "は" + catage.get(i) + "歳です");
            }else if(catage.get(i) >10){
                System.out.println(cats.get(i) + "は" + catage.get(i) + "歳で長生きで    す");
            }else{
                System.out.println(cats.get(i) + "　ニャー");
            }


        }



    }










}


