public class SumCalculator {
    public static int calculateSum(int num1, int num2) {
        return num1 + num2;
    }

    public static void main(String[] args) {
        int num1 = 5;
        int num2 = 3;
        int sum = calculateSum(num1, num2);
        System.out.println("The sum of " + num1 + " and " + num2 + " is: " + sum);
    }
}
