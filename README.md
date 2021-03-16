# GB
public class Lesson1 {

    public static void main(String[] args) {


        final float fOne = 5f;
        final float fTwo = 3.7f;
        final float fThree = 78f;
        final float fFour = 6f;
        System.out.println(" 1 задание: " + calculate(fOne, fTwo, fThree, fFour));
        System.out.println(" 2 задание: " + task10and20(8, 12));
        System.out.println(" 3 задание: " + ((isPositiveOrNegative(8)) ? "positive" : "negative") + "!");
        Object name;
        System.out.println(" 4 задание: " + welcome("Elena"));

    }

    private static float calculate(float a, float b, float c, float d) {
        return a * (b + (c / d));
    }


    public static boolean task10and20(int a, int b) {

        return (a + b <= 20) && (a + b >= 10);
    }


    private static boolean isPositiveOrNegative(int variable) {
        return variable >= 0;


    }

    private static String welcome(String name) {
        return "Привет " + name + "!";


    }
}
