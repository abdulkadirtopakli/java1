public class Main {
    public static void main(String[] args) {

        String internetSubesiButonu = "İnternet Şubesi";
        double dolarDun = 8.15;
        double dolarBugun = 8.15;
        int vade = 36;
        boolean dustuMu = false;

        System.out.print(internetSubesiButonu);

        if (dolarBugun < dolarDun) {
            System.out.println("Dolar üştü.");
        } else if (dolarBugun > dolarDun) {
            System.out.println("Dolar yükseldi.");
        } else {
            System.out.println("dolar eşittir.");
        }

        String kredi1 = "Hızlı Kredi";
        String kredi2 = "Taşıt Kredisi";
        String kredi3 = "Konut kredisi";
        String kredi4 = "msb kredisi";
        String kredi5 = "çiftçi kredisi";
        String kredi6 = "meb kredisi";

        System.out.println(kredi1);
        System.out.println(kredi2);
        System.out.println(kredi3);
        System.out.println(kredi4);
        System.out.println(kredi5);
        System.out.println(kredi6);

        String[] krediler = {
                "Hızlı Kredi",
                "Taşıt Kredisi",
                "Konut kredisi",
                "msb kredisi",
                "çiftçi kredisi",
                "meb kredisi"
        };
        //foreach
        for (String kredi : krediler) {
            System.out.println(kredi);
        }

        for(int i = 0; i<krediler.length;i++) {
            System.out.println(krediler[i]);

        }
        int sayi1 = 10;
        int sayi2 = 20;
        sayi1 = sayi2;
        sayi2 = 100;
        System.out.println(sayi1);

        int[] sayilar1 = {1,2,3,4,5};
        int[] sayilar2 = {10,20,30,40,50};
        sayilar1 = sayilar2;
        sayilar2[0] = 100;
        System.out.println(sayilar1[0]);

        String sehir1 = "ankara";
        String sehir2 = "istanbul";
        sehir1 = sehir2;
        sehir2 = "izmir";
        System.out.println(sehir1);



    }

}
