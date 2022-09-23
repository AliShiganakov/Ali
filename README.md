
public class Main {
    public static void main(String[] args) {


        int x = 5;
        int a = 4;
        int b = 3;
        System.out.println((--x) + (++a) - (++b));
        System.out.println(a != x);
        System.out.println((x > a) || (a > b));
        {
            int i = 10;
            {
                if (i < 100)
                    System.out.println( 1 );
                else
                    System.out.println( 0 );

            }

        }


    }

}
