# Nested_if_statement

public static void main(String[] args) {

        //nested_if_statement
        boolean x = true;
        boolean y = false;
        if (x == true) {
            System.out.println("x esittir true");
            if (y == true) {
                System.out.println("y esittir true");
            } else {
                System.out.println("' y esit degildir true");}
        }else{
            System.out.println("x esit degildir true");
        }
        

//TASK  6 ile bolunebilme
       int sayi = 18;
        if (sayi % 2 == 0)
        {
            System.out.println("sayi 2 ile bolunebiliyor");
            if (sayi % 3 == 0) {
                System.out.println("sayi 3 ile bolunebiliyor");
                System.out.println("sayi 6 ile bolunebiliyor");
            } else {
                System.out.println("sayi 2 ile bolunebiliyor fakat 3 ve 6 ile bolunemiyor");

            }


        }else{
            System.out.println("sayi 2 ile bolunemiyor dolayisiyla 6 ile bolunemiyor");
        }

        //TASK
       
final String kullaniciAdi="kullanici Adi";
final String parola="Parola";
if (kullaniciAdi=="kullanici adi"){
    System.out.println("kullanici adi dogru");
if (parola=="parola"){
    System.out.println("parola dogru");
    System.out.println("sisteme basarili bir sekilde giris yaptiniz!!!");
}else{
    System.out.println("Parola yanlis, lutfen dogru parolayi giriniz");

}


}else{
    System.out.println("kullanici adi dogru degil, lutfen dogru kullanici adini girin");

}


        //TASK
        int a=5;
        int b=5;
        int c=6;
        if(a+b>c){
            System.out.println("a+b nin toplami c den buyuktur");
            }else if(a+c>b){
                System.out.println("a+c nin toplami b den buyuktur");

            }else if(b+c>a){
                System.out.println("b+c nin toplami a dan buyuktur");

            }else{
                System.out.println("gecersiz toplam");
            }

//TASK
        int h=6;
        if (h==1){
            System.out.println("bu gun gunlerden Pazartesi");
        }else if(h==2){
            System.out.println("Bu Gun Gunlerden Sali");
        }else if(h==3){
            System.out.println("Bu Gun Gunlerden Carsamba");
        }else if(h==4){
            System.out.println("Bu Gun Gunlerden Persembe");
        }else if (h==5){
            System.out.println("Bu Gun Gunlerden Cuma");
        }else if (h==6){
            System.out.println("Bu Gun Gunlerden Cumartesi");
        }else if (h==7){
            System.out.println("Bu Gun Gunlerden Pazar");
        }


        //TERNARY OPERATORS
        
        int time=15;
        if (time<18){
            System.out.println("Good day.");
        }else{
            System.out.println("Good evening.");
        }
        String result =(time<18)? "good day.":"Good evening.";
        System.out.println(result);


//TASK  statu=deger
        
        boolean deger=false;

        String sonuc =(deger =true)? "deger:true":"deger:false";
        System.out.println(sonuc);

//TASK
        int x =5;
        int y=6;
        int buyuksayi=(x>y)? x: y;   //int buyksayi=y
        System.out.println(buyuksayi);



        //TASK
        int w=9;
        if (w%2==0){
            System.out.println("Bu sayi cift bir sayidir");
        }else{
            System.out.println("Bu sayi Tektir");
       }
       

        //TASK   
        char g='D';

        String message=(g=='A')?"Execellent Job":
                (g=='B')?"Good Job":
        (g=='C')?"Avarage Job":
                (g=='D')?"Below Avarage Job":
                        (g=='E')?"You Failed":
        "Invalid grade entered.";
        System.out.println(message);


        //Task
        String day = "Saturday";
        String message = ((day == "Saturday") || (day == "Sunday")) ? "Weekend" : "Weekday";
        System.out.println(day += "is a" + message + "day.");
        System.out.println(message);

    }
}

  
