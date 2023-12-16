public class Main {

    public static void main(String[] args) {
       Seosen seosen = Seosen.summer;
        System.out.println("Температура равнa: " + seosen.getTemerature());


        switch(seosen){
            case summer:
                System.out.println("summer");
                System.out.println(seosen);
                break;
            case winter:
                System.out.println("winter");
                System.out.println(seosen);
                break;
            case autumn:
                System.out.println("autumn");
                System.out.println(seosen);
                break;
            case spring:
                System.out.println("spring");
                System.out.println(seosen);
                break;
            default:
                System.out.println("не найдено");
        }
        

    }
}
