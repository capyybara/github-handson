# github-handson
#github-handson

public class Cat {
    public static void main(String[] args) {

        String catname[] = {"Tama", "Hachi", "Goro", "Nana"};
        int catage[] = {2, 13, 7, 4};


        for (int i = 0; i <= 3; i++)
            if(catage[i] % 2 ==0){
                System.out.println(catname[i] + "は" + catage[i] + "歳です");
            }else if (catage[i] >=10){
                System.out.println(catname[i] + "は"  + catage[i] + "歳で長生きです");
            }else{
                System.out.println(catname[i] + "　ニャー");
            }



        }
    }

